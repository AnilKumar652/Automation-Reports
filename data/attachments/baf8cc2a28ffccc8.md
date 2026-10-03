# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: credentials/C58112-verify-first-edit-of-credential-in-personnel-updates-correctly.spec.ts >> Credentials — Personnel >> @smoke @regression C58112: Verify first edit of credential in Personnel updates correctly
- Location: src/tests/credentials/C58112-verify-first-edit-of-credential-in-personnel-updates-correctly.spec.ts:20:7

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
              - row "Id Email Public Name Limit Dispatches Send SMS? Push Notifications Active Area(s)" [ref=e60]:
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
            - rowgroup [ref=e85]:
              - row "Actions" [ref=e86]:
                - columnheader "Actions" [ref=e87]:
                  - generic [ref=e88]: Actions
            - generic "Grid body" [ref=e89]:
              - rowgroup [ref=e90]:
                - row "Press Space to toggle row selection (unchecked)" [ref=e91]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e92]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e93] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e94]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e95]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e96] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e97]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e98]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e99] [cursor=pointer]
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
                - row "Press Space to toggle row selection (unchecked)" [ref=e118]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e119]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e120] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e121]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e122]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e123] [cursor=pointer]
              - generic "Grid columns" [ref=e124]:
                - rowgroup [ref=e125]:
                  - row "53280 katia@firstduesizeup.com Katia 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e126]:
                    - gridcell "53280" [ref=e127]
                    - gridcell "katia@firstduesizeup.com" [ref=e128]:
                      - generic [ref=e131]: katia@firstduesizeup.com
                    - gridcell "Katia" [ref=e132]:
                      - generic [ref=e135]: Katia
                    - gridcell [ref=e136]
                    - gridcell [ref=e140]
                    - gridcell [ref=e144]
                    - gridcell [ref=e148]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e152]:
                      - generic [ref=e154]:
                        - generic [ref=e155]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e156] [cursor=pointer]
                  - row "71875 Justin@firstdue.com Justin Dillard 2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac... Click to show more content" [ref=e158]:
                    - gridcell "71875" [ref=e159]
                    - gridcell "Justin@firstdue.com" [ref=e160]:
                      - generic [ref=e163]: Justin@firstdue.com
                    - gridcell "Justin Dillard" [ref=e164]:
                      - generic [ref=e167]: Justin Dillard
                    - gridcell [ref=e168]
                    - gridcell [ref=e172]
                    - gridcell [ref=e176]
                    - gridcell [ref=e180]
                    - gridcell "2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac... Click to show more content" [ref=e184]:
                      - generic [ref=e186]:
                        - generic [ref=e187]: 2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac...
                        - button "Click to show more content" [ref=e188] [cursor=pointer]
                  - row "92581 andre.dinsdale@firstdue.com Andrew Dinsdale 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e190]:
                    - gridcell "92581" [ref=e191]
                    - gridcell "andre.dinsdale@firstdue.com" [ref=e192]:
                      - generic [ref=e195]: andre.dinsdale@firstdue.com
                    - gridcell "Andrew Dinsdale" [ref=e196]:
                      - generic [ref=e199]: Andrew Dinsdale
                    - gridcell [ref=e200]
                    - gridcell [ref=e204]
                    - gridcell [ref=e208]
                    - gridcell [ref=e212]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e216]:
                      - generic [ref=e218]:
                        - generic [ref=e219]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e220] [cursor=pointer]
                  - row "114893 louis.sorace@firstdue.com Louis Sorace 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e222]:
                    - gridcell "114893" [ref=e223]
                    - gridcell "louis.sorace@firstdue.com" [ref=e224]:
                      - generic [ref=e227]: louis.sorace@firstdue.com
                    - gridcell "Louis Sorace" [ref=e228]:
                      - generic [ref=e231]: Louis Sorace
                    - gridcell [ref=e232]
                    - gridcell [ref=e236]
                    - gridcell [ref=e240]
                    - gridcell [ref=e244]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e248]:
                      - generic [ref=e250]:
                        - generic [ref=e251]: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e252] [cursor=pointer]
                  - row "116671 test_automation@firstduesizeup.com Fire Department Admin - Test1 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e254]:
                    - gridcell "116671" [ref=e255]
                    - gridcell "test_automation@firstduesizeup.com" [ref=e256]:
                      - generic [ref=e259]: test_automation@firstduesizeup.com
                    - gridcell "Fire Department Admin - Test1" [ref=e260]:
                      - generic [ref=e263]: Fire Department Admin - Test1
                    - gridcell [ref=e264]
                    - gridcell [ref=e268]
                    - gridcell [ref=e272]
                    - gridcell [ref=e276]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e280]:
                      - generic [ref=e282]:
                        - generic [ref=e283]: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e284] [cursor=pointer]
                  - row "130341 john.christensen@firstdue.com John Christensen 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e286]:
                    - gridcell "130341" [ref=e287]
                    - gridcell "john.christensen@firstdue.com" [ref=e288]:
                      - generic [ref=e291]: john.christensen@firstdue.com
                    - gridcell "John Christensen" [ref=e292]:
                      - generic [ref=e295]: John Christensen
                    - gridcell [ref=e296]
                    - gridcell [ref=e300]
                    - gridcell [ref=e304]
                    - gridcell [ref=e308]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e312]:
                      - generic [ref=e314]:
                        - generic [ref=e315]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e316] [cursor=pointer]
                  - row "132324 Kieran.tate@firstdue.com Kieran Tate 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e318]:
                    - gridcell "132324" [ref=e319]
                    - gridcell "Kieran.tate@firstdue.com" [ref=e320]:
                      - generic [ref=e323]: Kieran.tate@firstdue.com
                    - gridcell "Kieran Tate" [ref=e324]:
                      - generic [ref=e327]: Kieran Tate
                    - gridcell [ref=e328]
                    - gridcell [ref=e332]
                    - gridcell [ref=e336]
                    - gridcell [ref=e340]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e344]:
                      - generic [ref=e346]:
                        - generic [ref=e347]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e348] [cursor=pointer]
                  - row "135216 jeran.scruggs@firstdue.com Martha Herrera 2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul... Click to show more content" [ref=e350]:
                    - gridcell "135216" [ref=e351]
                    - gridcell "jeran.scruggs@firstdue.com" [ref=e352]:
                      - generic [ref=e355]: jeran.scruggs@firstdue.com
                    - gridcell "Martha Herrera" [ref=e356]:
                      - generic [ref=e359]: Martha Herrera
                    - gridcell [ref=e360]
                    - gridcell [ref=e364]
                    - gridcell [ref=e368]
                    - gridcell [ref=e372]
                    - gridcell "2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul... Click to show more content" [ref=e376]:
                      - generic [ref=e378]:
                        - generic [ref=e379]: 2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul...
                        - button "Click to show more content" [ref=e380] [cursor=pointer]
                  - row "135924 patrick.morgan@firstduesizeup.com Patrick Morgan 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e382]:
                    - gridcell "135924" [ref=e383]
                    - gridcell "patrick.morgan@firstduesizeup.com" [ref=e384]:
                      - generic [ref=e387]: patrick.morgan@firstduesizeup.com
                    - gridcell "Patrick Morgan" [ref=e388]:
                      - generic [ref=e391]: Patrick Morgan
                    - gridcell [ref=e392]
                    - gridcell [ref=e396]
                    - gridcell [ref=e400]
                    - gridcell [ref=e404]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e408]:
                      - generic [ref=e410]:
                        - generic [ref=e411]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e412] [cursor=pointer]
                  - row "136341 patrick.tucker@firstdue.com Patrick Tucker 104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win... Click to show more content" [ref=e414]:
                    - gridcell "136341" [ref=e415]
                    - gridcell "patrick.tucker@firstdue.com" [ref=e416]:
                      - generic [ref=e419]: patrick.tucker@firstdue.com
                    - gridcell "Patrick Tucker" [ref=e420]:
                      - generic [ref=e423]: Patrick Tucker
                    - gridcell [ref=e424]
                    - gridcell [ref=e428]
                    - gridcell [ref=e432]
                    - gridcell [ref=e436]
                    - gridcell "104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win... Click to show more content" [ref=e440]:
                      - generic [ref=e442]:
                        - generic [ref=e443]: 104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win...
                        - button "Click to show more content" [ref=e444] [cursor=pointer]
                  - row "137110 Andrew.Engler@firstdue.com Andrew Engler 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e446]:
                    - gridcell "137110" [ref=e447]
                    - gridcell "Andrew.Engler@firstdue.com" [ref=e448]:
                      - generic [ref=e451]: Andrew.Engler@firstdue.com
                    - gridcell "Andrew Engler" [ref=e452]:
                      - generic [ref=e455]: Andrew Engler
                    - gridcell [ref=e456]
                    - gridcell [ref=e460]
                    - gridcell [ref=e464]
                    - gridcell [ref=e468]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e472]:
                      - generic [ref=e474]:
                        - generic [ref=e475]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e476] [cursor=pointer]
              - rowgroup [ref=e478]:
                - row "More options" [ref=e479]:
                  - gridcell "More options" [ref=e480]:
                    - generic [ref=e481]:
                      - button "Edit" [ref=e482] [cursor=pointer]
                      - button "Delete" [ref=e484] [cursor=pointer]
                      - generic "More options" [ref=e487]:
                        - button "More options" [ref=e488] [cursor=pointer]
                - row "More options" [ref=e490]:
                  - gridcell "More options" [ref=e491]:
                    - generic [ref=e492]:
                      - button "Edit" [ref=e493] [cursor=pointer]
                      - button "Delete" [ref=e495] [cursor=pointer]
                      - generic "More options" [ref=e498]:
                        - button "More options" [ref=e499] [cursor=pointer]
                - row "More options" [ref=e501]:
                  - gridcell "More options" [ref=e502]:
                    - generic [ref=e503]:
                      - button "Edit" [ref=e504] [cursor=pointer]
                      - button "Delete" [ref=e506] [cursor=pointer]
                      - generic "More options" [ref=e509]:
                        - button "More options" [ref=e510] [cursor=pointer]
                - row "More options" [ref=e512]:
                  - gridcell "More options" [ref=e513]:
                    - generic [ref=e514]:
                      - button "Edit" [ref=e515] [cursor=pointer]
                      - button "Delete" [ref=e517] [cursor=pointer]
                      - generic "More options" [ref=e520]:
                        - button "More options" [ref=e521] [cursor=pointer]
                - row "More options" [ref=e523]:
                  - gridcell "More options" [ref=e524]:
                    - generic [ref=e525]:
                      - button "Edit" [ref=e526] [cursor=pointer]
                      - button "Delete" [ref=e528] [cursor=pointer]
                      - generic "More options" [ref=e531]:
                        - button "More options" [ref=e532] [cursor=pointer]
                - row "More options" [ref=e534]:
                  - gridcell "More options" [ref=e535]:
                    - generic [ref=e536]:
                      - button "Edit" [ref=e537] [cursor=pointer]
                      - button "Delete" [ref=e539] [cursor=pointer]
                      - generic "More options" [ref=e542]:
                        - button "More options" [ref=e543] [cursor=pointer]
                - row "More options" [ref=e545]:
                  - gridcell "More options" [ref=e546]:
                    - generic [ref=e547]:
                      - button "Edit" [ref=e548] [cursor=pointer]
                      - button "Delete" [ref=e550] [cursor=pointer]
                      - generic "More options" [ref=e553]:
                        - button "More options" [ref=e554] [cursor=pointer]
                - row "More options" [ref=e556]:
                  - gridcell "More options" [ref=e557]:
                    - generic [ref=e558]:
                      - button "Edit" [ref=e559] [cursor=pointer]
                      - button "Delete" [ref=e561] [cursor=pointer]
                      - generic "More options" [ref=e564]:
                        - button "More options" [ref=e565] [cursor=pointer]
                - row "More options" [ref=e567]:
                  - gridcell "More options" [ref=e568]:
                    - generic [ref=e569]:
                      - button "Edit" [ref=e570] [cursor=pointer]
                      - button "Delete" [ref=e572] [cursor=pointer]
                      - generic "More options" [ref=e575]:
                        - button "More options" [ref=e576] [cursor=pointer]
                - row "More options" [ref=e578]:
                  - gridcell "More options" [ref=e579]:
                    - generic [ref=e580]:
                      - button "Edit" [ref=e581] [cursor=pointer]
                      - button "Delete" [ref=e583] [cursor=pointer]
                      - generic "More options" [ref=e586]:
                        - button "More options" [ref=e587] [cursor=pointer]
                - row "More options" [ref=e589]:
                  - gridcell "More options" [ref=e590]:
                    - generic [ref=e591]:
                      - button "Edit" [ref=e592] [cursor=pointer]
                      - button "Delete" [ref=e594] [cursor=pointer]
                      - generic "More options" [ref=e597]:
                        - button "More options" [ref=e598] [cursor=pointer]
              - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
          - generic [ref=e609]:
            - generic [ref=e610]: Showing 1 to 20 of 60 records
            - generic [ref=e611]: Page 1 of 3
            - generic "More options" [ref=e613]:
              - button "Select page size" [ref=e614] [cursor=pointer]: "Page size: 20"
            - button "Download CSV" [ref=e616] [cursor=pointer]
            - generic [ref=e618]:
              - button "Go to the previous page" [disabled] [ref=e619]: Previous
              - button "Go to the next page" [ref=e621] [cursor=pointer]: Next
  - contentinfo [ref=e623]: © 2026 First Due
  - generic:
    - button "Chat Close Maven Chat" [ref=e624] [cursor=pointer]:
      - img "Chat" [ref=e626]
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