# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: credentials/C58111-verify-credential-date-range-displays-correctly-in-personnel.spec.ts >> Credentials — Personnel >> @regression C58111: Verify credential date range displays correctly in Personnel
- Location: src/tests/credentials/C58111-verify-credential-date-range-displays-correctly-in-personnel.spec.ts:18:7

# Error details

```
TimeoutError: locator.click: Timeout 10000ms exceeded.
Call log:
  - waiting for getByRole('button', { name: /Expand search input|Open search/i })
    - locator resolved to <button type="button" data-v-45734e6c="" title="Expand search input" aria-label="Expand search input" data-testid="user_list-search-input-expand" class="button is-medium is-text is-icon-only fd-search-input__expand-button fd-search-input__expand-button--medium">…</button>
  - attempting click action
    - waiting for element to be visible, enabled and stable
    - element is visible, enabled and stable
    - scrolling into view if needed
    - done scrolling

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - link "Skip to main content":
    - /url: "#main-content"
  - banner
  - navigation "Primary navigation" [ref=e2]:
    - link "Skip to main content" [ref=e3] [cursor=pointer]:
      - /url: "#main-content"
  - main "Main content area" [ref=e4]:
    - main "Main dynamic content area" [ref=e6]:
      - generic [ref=e7]:
        - generic [ref=e8]:
          - link "Show main sidebar" [ref=e9] [cursor=pointer]:
            - /url: "#"
            - img [ref=e10]
          - generic [ref=e16]: User List
          - generic [ref=e19]:
            - button "Bulk" [disabled] [ref=e22]: Bulk
            - button "Add" [ref=e24] [cursor=pointer]: Add
        - generic [ref=e29]:
          - search [ref=e32]:
            - generic [ref=e33]:
              - generic "More options" [ref=e35]:
                - button "Saved Views" [ref=e36] [cursor=pointer]:
                  - generic [ref=e37]: Saved Views
              - generic "More options" [ref=e41]:
                - button "More options" [ref=e42] [cursor=pointer]
            - button "Filter" [ref=e45] [cursor=pointer]: Filter
            - search [ref=e47]:
              - button "Expand search input" [ref=e48] [cursor=pointer]
          - treegrid [ref=e53]:
            - rowgroup [ref=e54]:
              - row [ref=e55]:
                - columnheader [ref=e56]:
                  - checkbox [ref=e58] [cursor=pointer]
            - rowgroup [ref=e59]:
              - row "Id Email Public Name Limit Dispatches Send SMS? Push Notifications Active Area(s) Role(s) Dispatch Incident Types Dispatch Units" [ref=e60]:
                - columnheader "Id" [ref=e61]:
                  - generic [ref=e63] [cursor=pointer]: Id
                - columnheader "Email" [ref=e64]:
                  - generic [ref=e66] [cursor=pointer]: Email
                - columnheader "Public Name" [ref=e67]:
                  - generic [ref=e69] [cursor=pointer]: Public Name
                - columnheader "Limit Dispatches" [ref=e70]:
                  - generic [ref=e72] [cursor=pointer]: Limit Dispatches
                - columnheader "Send SMS?" [ref=e73]:
                  - generic [ref=e75] [cursor=pointer]: Send SMS?
                - columnheader "Push Notifications" [ref=e76]:
                  - generic [ref=e78] [cursor=pointer]: Push Notifications
                - columnheader "Active" [ref=e79]:
                  - generic [ref=e81] [cursor=pointer]: Active
                - columnheader "Area(s)" [ref=e82]:
                  - generic [ref=e84]: Area(s)
                - columnheader "Role(s)" [ref=e85]:
                  - generic [ref=e87]: Role(s)
                - columnheader "Dispatch Incident Types" [ref=e88]:
                  - generic [ref=e90]: Dispatch Incident Types
                - columnheader "Dispatch Units" [ref=e91]:
                  - generic [ref=e93]: Dispatch Units
            - rowgroup [ref=e94]:
              - row "Actions" [ref=e95]:
                - columnheader "Actions" [ref=e96]:
                  - generic [ref=e97]: Actions
            - generic "Grid body" [ref=e98]:
              - rowgroup [ref=e99]:
                - row "Press Space to toggle row selection (unchecked)" [ref=e100]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e101]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e102] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e103]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e104]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e105] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e106]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e107]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e108] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e109]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e110]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e111] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e112]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e113]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e114] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e115]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e116]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e117] [cursor=pointer]
              - generic "Grid columns" [ref=e118]:
                - rowgroup [ref=e119]:
                  - row "53280 katia@firstduesizeup.com Katia 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e120]:
                    - gridcell "53280" [ref=e121]
                    - gridcell "katia@firstduesizeup.com" [ref=e122]:
                      - generic [ref=e124]: katia@firstduesizeup.com
                    - gridcell "Katia" [ref=e125]:
                      - generic [ref=e127]: Katia
                    - gridcell [ref=e128]
                    - gridcell [ref=e132]
                    - gridcell [ref=e136]
                    - gridcell [ref=e140]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e144]:
                      - generic [ref=e146]:
                        - text: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e147] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e149]:
                      - generic [ref=e151]: Super Admin
                    - gridcell "All Dispatches" [ref=e152]:
                      - generic [ref=e154]: All Dispatches
                    - gridcell "All Dispatches" [ref=e155]:
                      - generic [ref=e157]: All Dispatches
                  - row "71875 Justin@firstdue.com Justin Dillard 2026A103, 2026e1001, Abbeville EMS SC, Acadian Ambulance (LA), AC... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e158]:
                    - gridcell "71875" [ref=e159]
                    - gridcell "Justin@firstdue.com" [ref=e160]:
                      - generic [ref=e162]: Justin@firstdue.com
                    - gridcell "Justin Dillard" [ref=e163]:
                      - generic [ref=e165]: Justin Dillard
                    - gridcell [ref=e166]
                    - gridcell [ref=e170]
                    - gridcell [ref=e174]
                    - gridcell [ref=e178]
                    - gridcell "2026A103, 2026e1001, Abbeville EMS SC, Acadian Ambulance (LA), AC... Click to show more content" [ref=e182]:
                      - generic [ref=e184]:
                        - text: 2026A103, 2026e1001, Abbeville EMS SC, Acadian Ambulance (LA), AC...
                        - button "Click to show more content" [ref=e185] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e187]:
                      - generic [ref=e189]: Super Admin
                    - gridcell "All Dispatches" [ref=e190]:
                      - generic [ref=e192]: All Dispatches
                    - gridcell "All Dispatches" [ref=e193]:
                      - generic [ref=e195]: All Dispatches
                  - row "92581 andre.dinsdale@firstdue.com Andrew Dinsdale 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e196]:
                    - gridcell "92581" [ref=e197]
                    - gridcell "andre.dinsdale@firstdue.com" [ref=e198]:
                      - generic [ref=e200]: andre.dinsdale@firstdue.com
                    - gridcell "Andrew Dinsdale" [ref=e201]:
                      - generic [ref=e203]: Andrew Dinsdale
                    - gridcell [ref=e204]
                    - gridcell [ref=e208]
                    - gridcell [ref=e212]
                    - gridcell [ref=e216]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e220]:
                      - generic [ref=e222]:
                        - text: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e223] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e225]:
                      - generic [ref=e227]: Super Admin
                    - gridcell "All Dispatches" [ref=e228]:
                      - generic [ref=e230]: All Dispatches
                    - gridcell "All Dispatches" [ref=e231]:
                      - generic [ref=e233]: All Dispatches
                  - row "114893 louis.sorace@firstdue.com Louis Sorace 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e234]:
                    - gridcell "114893" [ref=e235]
                    - gridcell "louis.sorace@firstdue.com" [ref=e236]:
                      - generic [ref=e238]: louis.sorace@firstdue.com
                    - gridcell "Louis Sorace" [ref=e239]:
                      - generic [ref=e241]: Louis Sorace
                    - gridcell [ref=e242]
                    - gridcell [ref=e246]
                    - gridcell [ref=e250]
                    - gridcell [ref=e254]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e258]:
                      - generic [ref=e260]:
                        - text: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e261] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e263]:
                      - generic [ref=e265]: Super Admin
                    - gridcell "All Dispatches" [ref=e266]:
                      - generic [ref=e268]: All Dispatches
                    - gridcell "All Dispatches" [ref=e269]:
                      - generic [ref=e271]: All Dispatches
                  - row "116671 test_automation@firstduesizeup.com Fire Department Admin - Test1 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e272]:
                    - gridcell "116671" [ref=e273]
                    - gridcell "test_automation@firstduesizeup.com" [ref=e274]:
                      - generic [ref=e276]: test_automation@firstduesizeup.com
                    - gridcell "Fire Department Admin - Test1" [ref=e277]:
                      - generic [ref=e279]: Fire Department Admin - Test1
                    - gridcell [ref=e280]
                    - gridcell [ref=e284]
                    - gridcell [ref=e288]
                    - gridcell [ref=e292]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e296]:
                      - generic [ref=e298]:
                        - text: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e299] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e301]:
                      - generic [ref=e303]: Super Admin
                    - gridcell "All Dispatches" [ref=e304]:
                      - generic [ref=e306]: All Dispatches
                    - gridcell "All Dispatches" [ref=e307]:
                      - generic [ref=e309]: All Dispatches
                  - row "130341 john.christensen@firstdue.com John Christensen 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content Super Admin All Dispatches All Dispatches" [ref=e310]:
                    - gridcell "130341" [ref=e311]
                    - gridcell "john.christensen@firstdue.com" [ref=e312]:
                      - generic [ref=e314]: john.christensen@firstdue.com
                    - gridcell "John Christensen" [ref=e315]:
                      - generic [ref=e317]: John Christensen
                    - gridcell [ref=e318]
                    - gridcell [ref=e322]
                    - gridcell [ref=e326]
                    - gridcell [ref=e330]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e334]:
                      - generic [ref=e336]:
                        - text: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e337] [cursor=pointer]
                    - gridcell "Super Admin" [ref=e339]:
                      - generic [ref=e341]: Super Admin
                    - gridcell "All Dispatches" [ref=e342]:
                      - generic [ref=e344]: All Dispatches
                    - gridcell "All Dispatches" [ref=e345]:
                      - generic [ref=e347]: All Dispatches
              - rowgroup [ref=e348]:
                - row "More options" [ref=e349]:
                  - gridcell "More options" [ref=e350]:
                    - generic [ref=e351]:
                      - button "Edit" [ref=e352] [cursor=pointer]
                      - button "Delete" [ref=e354] [cursor=pointer]
                      - generic "More options" [ref=e357]:
                        - button "More options" [ref=e358] [cursor=pointer]
                - row "More options" [ref=e360]:
                  - gridcell "More options" [ref=e361]:
                    - generic [ref=e362]:
                      - button "Edit" [ref=e363] [cursor=pointer]
                      - button "Delete" [ref=e365] [cursor=pointer]
                      - generic "More options" [ref=e368]:
                        - button "More options" [ref=e369] [cursor=pointer]
                - row "More options" [ref=e371]:
                  - gridcell "More options" [ref=e372]:
                    - generic [ref=e373]:
                      - button "Edit" [ref=e374] [cursor=pointer]
                      - button "Delete" [ref=e376] [cursor=pointer]
                      - generic "More options" [ref=e379]:
                        - button "More options" [ref=e380] [cursor=pointer]
                - row "More options" [ref=e382]:
                  - gridcell "More options" [ref=e383]:
                    - generic [ref=e384]:
                      - button "Edit" [ref=e385] [cursor=pointer]
                      - button "Delete" [ref=e387] [cursor=pointer]
                      - generic "More options" [ref=e390]:
                        - button "More options" [ref=e391] [cursor=pointer]
                - row "More options" [ref=e393]:
                  - gridcell "More options" [ref=e394]:
                    - generic [ref=e395]:
                      - button "Edit" [ref=e396] [cursor=pointer]
                      - button "Delete" [ref=e398] [cursor=pointer]
                      - generic "More options" [ref=e401]:
                        - button "More options" [ref=e402] [cursor=pointer]
                - row "More options" [ref=e404]:
                  - gridcell "More options" [ref=e405]:
                    - generic [ref=e406]:
                      - button "Edit" [ref=e407] [cursor=pointer]
                      - button "Delete" [ref=e409] [cursor=pointer]
                      - generic "More options" [ref=e412]:
                        - button "More options" [ref=e413] [cursor=pointer]
              - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
          - generic [ref=e424]:
            - generic [ref=e425]: Showing 1 to 20 of 53 records
            - generic [ref=e426]: Page 1 of 3
            - generic "More options" [ref=e428]:
              - button "Select page size" [ref=e429] [cursor=pointer]: "Page size: 20"
            - button "Download CSV" [ref=e431] [cursor=pointer]
            - generic [ref=e433]:
              - button "Go to the previous page" [disabled] [ref=e434]: Previous
              - button "Go to the next page" [ref=e436] [cursor=pointer]: Next
  - contentinfo [ref=e438]: © 2026 First Due
  - generic:
    - button "Chat Close Maven Chat" [ref=e439] [cursor=pointer]:
      - img "Chat" [ref=e441]
      - button "Close Maven Chat"
    - iframe
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
> 31 |       await expand.click();
     |                    ^ TimeoutError: locator.click: Timeout 10000ms exceeded.
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
  43 |     await namedRow.waitFor({ state: 'visible', timeout: 30_000 });
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