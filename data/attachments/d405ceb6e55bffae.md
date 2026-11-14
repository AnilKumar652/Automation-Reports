# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: credentials/C58112-verify-first-edit-of-credential-in-personnel-updates-correctly.spec.ts >> Credentials — Personnel >> @smoke @regression C58112: Verify first edit of credential in Personnel updates correctly
- Location: src/tests/credentials/C58112-verify-first-edit-of-credential-in-personnel-updates-correctly.spec.ts:20:7

# Error details

```
TimeoutError: locator.waitFor: Timeout 30000ms exceeded.
Call log:
  - waiting for getByRole('row', { name: /halFD@firstduesizeup.com/i }).first() to be visible

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - link "Skip to main content":
    - /url: "#main-content"
  - banner
  - main "Main content area" [ref=e2]:
    - generic [ref=e5]:
      - generic [ref=e6]:
        - link "Show main sidebar" [ref=e7] [cursor=pointer]:
          - /url: "#"
          - img [ref=e8]
        - generic [ref=e14]: User List
        - generic [ref=e17]:
          - button "Bulk" [disabled] [ref=e20]: Bulk
          - button "Add" [ref=e22] [cursor=pointer]: Add
      - generic [ref=e27]:
        - search [ref=e30]:
          - generic [ref=e31]:
            - generic "More options" [ref=e33]:
              - button "Saved Views" [ref=e34] [cursor=pointer]:
                - generic [ref=e35]: Saved Views
            - generic "More options" [ref=e39]:
              - button "More options" [ref=e40] [cursor=pointer]
          - button "Open Filters" [ref=e43] [cursor=pointer]: Filter
          - search [ref=e45]:
            - search [ref=e46]:
              - generic [ref=e47]:
                - button "Trigger search" [ref=e48] [cursor=pointer]
                - searchbox "Search..." [active] [ref=e50]: halFD@firstduesizeup.com
                - button "Clear search" [ref=e51] [cursor=pointer]
        - treegrid [ref=e56]:
          - rowgroup [ref=e57]:
            - row "Select" [ref=e58]:
              - columnheader "Select" [ref=e59]:
                - checkbox [disabled] [ref=e61] [cursor=pointer]
                - generic [ref=e62]: Select
          - rowgroup [ref=e63]:
            - row "Id Email Public Name Limit Dispatches Send SMS? Push Notifications Active Area(s)" [ref=e64]:
              - columnheader "Id" [ref=e65]:
                - generic [ref=e67] [cursor=pointer]: Id
              - columnheader "Email" [ref=e68]:
                - generic [ref=e70] [cursor=pointer]: Email
              - columnheader "Public Name" [ref=e71]:
                - generic [ref=e73] [cursor=pointer]: Public Name
              - columnheader "Limit Dispatches" [ref=e74]:
                - generic [ref=e76] [cursor=pointer]: Limit Dispatches
              - columnheader "Send SMS?" [ref=e77]:
                - generic [ref=e79] [cursor=pointer]: Send SMS?
              - columnheader "Push Notifications" [ref=e80]:
                - generic [ref=e82] [cursor=pointer]: Push Notifications
              - columnheader "Active" [ref=e83]:
                - generic [ref=e85] [cursor=pointer]: Active
              - columnheader "Area(s)" [ref=e86]:
                - generic [ref=e88]: Area(s)
          - rowgroup [ref=e89]:
            - row "Actions" [ref=e90]:
              - columnheader "Actions" [ref=e91]:
                - generic [ref=e92]: Actions
          - rowgroup [ref=e93]
          - rowgroup "Grid columns" [ref=e94]
          - rowgroup [ref=e95]
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - rowgroup
          - row "Nothing to display in this view Try adjusting your filters, sorting, or columns — your data may be hidden. Or clear all filters to return to the default view.":
            - gridcell "Nothing to display in this view Try adjusting your filters, sorting, or columns — your data may be hidden. Or clear all filters to return to the default view.":
              - generic:
                - heading "Nothing to display in this view" [level=2]
                - generic: Try adjusting your filters, sorting, or columns — your data may be hidden. Or clear all filters to return to the default view.
        - generic [ref=e102]:
          - generic [ref=e103]: Showing 0 records
          - generic [ref=e104]: Page 1 of 1
          - generic "More options" [ref=e106]:
            - button "Select page size" [ref=e107] [cursor=pointer]: "Page size: 20"
          - button "Download CSV" [ref=e109] [cursor=pointer]
          - generic [ref=e111]:
            - button "Go to the previous page" [disabled] [ref=e112]: Previous
            - button "Go to the next page" [disabled] [ref=e114]: Next
  - contentinfo [ref=e116]: © 2026 First Due
  - button "Live Chat Button" [ref=e118] [cursor=pointer]:
    - img "Live Chat Button" [ref=e119]
    - button "Close CustomGPT"
```

# Test source

```ts
  1  | import type { Actor } from '@/framework';
  2  | import { Task } from '@/framework';
  3  | import { BrowseTheWeb } from '@/framework/abilities/BrowseTheWeb';
  4  | import { clickPinnedGridEditForRow } from '../utils/clickPinnedGridEditForRow';
  5  | 
  6  | export class TogglePersonnelRecordForUserTask extends Task {
  7  |   private constructor(
  8  |     private readonly userQuery: string,
  9  |     private readonly enabled: boolean,
  10 |   ) {
  11 |     super();
  12 |   }
  13 | 
  14 |   static enable(userQuery: string): TogglePersonnelRecordForUserTask {
  15 |     return new TogglePersonnelRecordForUserTask(userQuery, true);
  16 |   }
  17 | 
  18 |   static disable(userQuery: string): TogglePersonnelRecordForUserTask {
  19 |     return new TogglePersonnelRecordForUserTask(userQuery, false);
  20 |   }
  21 | 
  22 |   describeAction(): string {
  23 |     return `${this.enabled ? 'Enable' : 'Disable'} Personnel Record for "${this.userQuery}"`;
  24 |   }
  25 | 
  26 |   async performAs(actor: Actor): Promise<void> {
  27 |     const { page } = actor.abilityTo(BrowseTheWeb);
  28 | 
  29 |     const expand = page.getByRole('button', { name: /Expand search input|Open search/i });
  30 |     if (await expand.isVisible().catch(() => false)) {
  31 |       await expand.click();
  32 |     }
  33 | 
  34 |     const search = page.getByPlaceholder(/Search/i)
  35 |       .or(page.getByRole('textbox', { name: /Search/i }))
  36 |       .or(page.getByRole('searchbox'))
  37 |       .first();
  38 |     await search.waitFor({ state: 'visible', timeout: 15_000 });
  39 |     await search.fill(this.userQuery);
  40 |     await search.press('Enter');
  41 | 
  42 |     const namedRow = page.getByRole('row', { name: new RegExp(this.userQuery, 'i') }).first();
> 43 |     await namedRow.waitFor({ state: 'visible', timeout: 30_000 });
     |                    ^ TimeoutError: locator.waitFor: Timeout 30000ms exceeded.
  44 |     await namedRow.scrollIntoViewIfNeeded();
  45 |     await clickPinnedGridEditForRow(page, this.userQuery);
  46 | 
  47 |     const toggle = page.getByRole('switch', { name: /Personnel [Rr]ecord|Create personnel/i })
  48 |       .or(page.getByRole('checkbox', { name: /Personnel [Rr]ecord|Create personnel/i }))
  49 |       .or(page.locator('label').filter({ hasText: /Personnel record/i }).locator('..').getByRole('switch'))
  50 |       .or(page.locator('label').filter({ hasText: /Personnel [Rr]ecord/i }).locator('input, [role="switch"]'))
  51 |       .first();
  52 | 
  53 |     await toggle.waitFor({ state: 'visible', timeout: 20_000 });
  54 |     const isChecked = await toggle.isChecked().catch(async () => {
  55 |       const ariaChecked = await toggle.getAttribute('aria-checked');
  56 |       return ariaChecked === 'true';
  57 |     });
  58 | 
  59 |     if (isChecked !== this.enabled) {
  60 |       await toggle.click();
  61 |     }
  62 | 
  63 |     await page.getByRole('button', { name: /^Save$/i }).click();
  64 |     await page.waitForLoadState('domcontentloaded');
  65 |     // Users list should reload after save
  66 |     await page.getByRole('button', { name: /Add User/i })
  67 |       .or(page.getByText(/^Users$/i))
  68 |       .first()
  69 |       .waitFor({ state: 'visible', timeout: 30_000 })
  70 |       .catch(() => undefined);
  71 |   }
  72 | }
  73 | 
```