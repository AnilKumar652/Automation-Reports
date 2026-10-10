# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: credentials/C5701947-verify-filters-in-credentials-personnel.spec.ts >> Credentials — Personnel >> @regression C5701947: Verify filters in Credentials - Personnel
- Location: src/tests/credentials/C5701947-verify-filters-in-credentials-personnel.spec.ts:17:7

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
              - search [ref=e48]:
                - generic [ref=e49]:
                  - button "Trigger search" [ref=e50] [cursor=pointer]
                  - searchbox "Search..." [active] [ref=e52]: halFD@firstduesizeup.com
                  - button "Clear search" [ref=e53] [cursor=pointer]
          - treegrid [ref=e58]:
            - rowgroup [ref=e59]:
              - row [ref=e60]:
                - columnheader [ref=e61]:
                  - checkbox [ref=e63] [cursor=pointer]
            - rowgroup [ref=e64]:
              - row "Id Email Public Name Limit Dispatches Send SMS? Push Notifications Active Area(s)" [ref=e65]:
                - columnheader "Id" [ref=e66]:
                  - generic [ref=e68] [cursor=pointer]: Id
                - columnheader "Email" [ref=e69]:
                  - generic [ref=e71] [cursor=pointer]: Email
                - columnheader "Public Name" [ref=e72]:
                  - generic [ref=e74] [cursor=pointer]: Public Name
                - columnheader "Limit Dispatches" [ref=e75]:
                  - generic [ref=e77] [cursor=pointer]: Limit Dispatches
                - columnheader "Send SMS?" [ref=e78]:
                  - generic [ref=e80] [cursor=pointer]: Send SMS?
                - columnheader "Push Notifications" [ref=e81]:
                  - generic [ref=e83] [cursor=pointer]: Push Notifications
                - columnheader "Active" [ref=e84]:
                  - generic [ref=e86] [cursor=pointer]: Active
                - columnheader "Area(s)" [ref=e87]:
                  - generic [ref=e89]: Area(s)
            - rowgroup [ref=e90]:
              - row "Actions" [ref=e91]:
                - columnheader "Actions" [ref=e92]:
                  - generic [ref=e93]: Actions
            - generic "Grid body" [ref=e94]:
              - rowgroup [ref=e95]:
                - row "Press Space to toggle row selection (unchecked)" [ref=e96]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e97]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e98] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e99]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e100]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e101] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e102]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e103]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e104] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e105]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e106]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e107] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e108]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e109]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e110] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e111]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e112]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e113] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e114]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e115]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e116] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e117]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e118]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e119] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e120]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e121]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e122] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e123]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e124]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e125] [cursor=pointer]
                - row "Press Space to toggle row selection (unchecked)" [ref=e126]:
                  - gridcell "Press Space to toggle row selection (unchecked)" [ref=e127]:
                    - checkbox "Press Space to toggle row selection (unchecked)" [ref=e128] [cursor=pointer]
              - generic "Grid columns" [ref=e129]:
                - rowgroup [ref=e130]:
                  - row "53280 katia@firstduesizeup.com Katia 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e131]:
                    - gridcell "53280" [ref=e132]
                    - gridcell "katia@firstduesizeup.com" [ref=e133]:
                      - generic [ref=e136]: katia@firstduesizeup.com
                    - gridcell "Katia" [ref=e137]:
                      - generic [ref=e140]: Katia
                    - gridcell [ref=e141]
                    - gridcell [ref=e145]
                    - gridcell [ref=e149]
                    - gridcell [ref=e153]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e157]:
                      - generic [ref=e159]:
                        - generic [ref=e160]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e161] [cursor=pointer]
                  - row "71875 Justin@firstdue.com Justin Dillard 2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac... Click to show more content" [ref=e163]:
                    - gridcell "71875" [ref=e164]
                    - gridcell "Justin@firstdue.com" [ref=e165]:
                      - generic [ref=e168]: Justin@firstdue.com
                    - gridcell "Justin Dillard" [ref=e169]:
                      - generic [ref=e172]: Justin Dillard
                    - gridcell [ref=e173]
                    - gridcell [ref=e177]
                    - gridcell [ref=e181]
                    - gridcell [ref=e185]
                    - gridcell "2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac... Click to show more content" [ref=e189]:
                      - generic [ref=e191]:
                        - generic [ref=e192]: 2026A103, 2026e1001, Abbeville County FD SC, Abbeville EMS SC, Ac...
                        - button "Click to show more content" [ref=e193] [cursor=pointer]
                  - row "92581 andre.dinsdale@firstdue.com Andrew Dinsdale 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e195]:
                    - gridcell "92581" [ref=e196]
                    - gridcell "andre.dinsdale@firstdue.com" [ref=e197]:
                      - generic [ref=e200]: andre.dinsdale@firstdue.com
                    - gridcell "Andrew Dinsdale" [ref=e201]:
                      - generic [ref=e204]: Andrew Dinsdale
                    - gridcell [ref=e205]
                    - gridcell [ref=e209]
                    - gridcell [ref=e213]
                    - gridcell [ref=e217]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e221]:
                      - generic [ref=e223]:
                        - generic [ref=e224]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e225] [cursor=pointer]
                  - row "114893 louis.sorace@firstdue.com Louis Sorace 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e227]:
                    - gridcell "114893" [ref=e228]
                    - gridcell "louis.sorace@firstdue.com" [ref=e229]:
                      - generic [ref=e232]: louis.sorace@firstdue.com
                    - gridcell "Louis Sorace" [ref=e233]:
                      - generic [ref=e236]: Louis Sorace
                    - gridcell [ref=e237]
                    - gridcell [ref=e241]
                    - gridcell [ref=e245]
                    - gridcell [ref=e249]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e253]:
                      - generic [ref=e255]:
                        - generic [ref=e256]: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e257] [cursor=pointer]
                  - row "116671 test_automation@firstduesizeup.com Fire Department Admin - Test1 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e259]:
                    - gridcell "116671" [ref=e260]
                    - gridcell "test_automation@firstduesizeup.com" [ref=e261]:
                      - generic [ref=e264]: test_automation@firstduesizeup.com
                    - gridcell "Fire Department Admin - Test1" [ref=e265]:
                      - generic [ref=e268]: Fire Department Admin - Test1
                    - gridcell [ref=e269]
                    - gridcell [ref=e273]
                    - gridcell [ref=e277]
                    - gridcell [ref=e281]
                    - gridcell "104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2... Click to show more content" [ref=e285]:
                      - generic [ref=e287]:
                        - generic [ref=e288]: 104 FW FD Barnes Ang MA, 123TESTED, 12LISTAS, 13_empty, 14 JULY 2...
                        - button "Click to show more content" [ref=e289] [cursor=pointer]
                  - row "130341 john.christensen@firstdue.com John Christensen 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e291]:
                    - gridcell "130341" [ref=e292]
                    - gridcell "john.christensen@firstdue.com" [ref=e293]:
                      - generic [ref=e296]: john.christensen@firstdue.com
                    - gridcell "John Christensen" [ref=e297]:
                      - generic [ref=e300]: John Christensen
                    - gridcell [ref=e301]
                    - gridcell [ref=e305]
                    - gridcell [ref=e309]
                    - gridcell [ref=e313]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e317]:
                      - generic [ref=e319]:
                        - generic [ref=e320]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e321] [cursor=pointer]
                  - row "132324 Kieran.tate@firstdue.com Kieran Tate 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e323]:
                    - gridcell "132324" [ref=e324]
                    - gridcell "Kieran.tate@firstdue.com" [ref=e325]:
                      - generic [ref=e328]: Kieran.tate@firstdue.com
                    - gridcell "Kieran Tate" [ref=e329]:
                      - generic [ref=e332]: Kieran Tate
                    - gridcell [ref=e333]
                    - gridcell [ref=e337]
                    - gridcell [ref=e341]
                    - gridcell [ref=e345]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e349]:
                      - generic [ref=e351]:
                        - generic [ref=e352]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e353] [cursor=pointer]
                  - row "135216 jeran.scruggs@firstdue.com Martha Herrera 2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul... Click to show more content" [ref=e355]:
                    - gridcell "135216" [ref=e356]
                    - gridcell "jeran.scruggs@firstdue.com" [ref=e357]:
                      - generic [ref=e360]: jeran.scruggs@firstdue.com
                    - gridcell "Martha Herrera" [ref=e361]:
                      - generic [ref=e364]: Martha Herrera
                    - gridcell [ref=e365]
                    - gridcell [ref=e369]
                    - gridcell [ref=e373]
                    - gridcell [ref=e377]
                    - gridcell "2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul... Click to show more content" [ref=e381]:
                      - generic [ref=e383]:
                        - generic [ref=e384]: 2026A103, Abbeville County FD SC, Abbeville EMS SC, Acadian Ambul...
                        - button "Click to show more content" [ref=e385] [cursor=pointer]
                  - row "135924 patrick.morgan@firstduesizeup.com Patrick Morgan 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e387]:
                    - gridcell "135924" [ref=e388]
                    - gridcell "patrick.morgan@firstduesizeup.com" [ref=e389]:
                      - generic [ref=e392]: patrick.morgan@firstduesizeup.com
                    - gridcell "Patrick Morgan" [ref=e393]:
                      - generic [ref=e396]: Patrick Morgan
                    - gridcell [ref=e397]
                    - gridcell [ref=e401]
                    - gridcell [ref=e405]
                    - gridcell [ref=e409]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e413]:
                      - generic [ref=e415]:
                        - generic [ref=e416]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e417] [cursor=pointer]
                  - row "136341 patrick.tucker@firstdue.com Patrick Tucker 104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win... Click to show more content" [ref=e419]:
                    - gridcell "136341" [ref=e420]
                    - gridcell "patrick.tucker@firstdue.com" [ref=e421]:
                      - generic [ref=e424]: patrick.tucker@firstdue.com
                    - gridcell "Patrick Tucker" [ref=e425]:
                      - generic [ref=e428]: Patrick Tucker
                    - gridcell [ref=e429]
                    - gridcell [ref=e433]
                    - gridcell [ref=e437]
                    - gridcell [ref=e441]
                    - gridcell "104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win... Click to show more content" [ref=e445]:
                      - generic [ref=e447]:
                        - generic [ref=e448]: 104 FW FD Barnes Ang MA, 13_empty, 14 JULY 2025, 174th Attack Win...
                        - button "Click to show more content" [ref=e449] [cursor=pointer]
                  - row "137110 Andrew.Engler@firstdue.com Andrew Engler 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e451]:
                    - gridcell "137110" [ref=e452]
                    - gridcell "Andrew.Engler@firstdue.com" [ref=e453]:
                      - generic [ref=e456]: Andrew.Engler@firstdue.com
                    - gridcell "Andrew Engler" [ref=e457]:
                      - generic [ref=e460]: Andrew Engler
                    - gridcell [ref=e461]
                    - gridcell [ref=e465]
                    - gridcell [ref=e469]
                    - gridcell [ref=e473]
                    - gridcell "104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel... Click to show more content" [ref=e477]:
                      - generic [ref=e479]:
                        - generic [ref=e480]: 104 FW FD Barnes Ang MA, 10 - Bellerose Fire Department, 11 - Bel...
                        - button "Click to show more content" [ref=e481] [cursor=pointer]
              - rowgroup [ref=e483]:
                - row "More options" [ref=e484]:
                  - gridcell "More options" [ref=e485]:
                    - generic [ref=e486]:
                      - button "Edit" [ref=e487] [cursor=pointer]
                      - button "Delete" [ref=e489] [cursor=pointer]
                      - generic "More options" [ref=e492]:
                        - button "More options" [ref=e493] [cursor=pointer]
                - row "More options" [ref=e495]:
                  - gridcell "More options" [ref=e496]:
                    - generic [ref=e497]:
                      - button "Edit" [ref=e498] [cursor=pointer]
                      - button "Delete" [ref=e500] [cursor=pointer]
                      - generic "More options" [ref=e503]:
                        - button "More options" [ref=e504] [cursor=pointer]
                - row "More options" [ref=e506]:
                  - gridcell "More options" [ref=e507]:
                    - generic [ref=e508]:
                      - button "Edit" [ref=e509] [cursor=pointer]
                      - button "Delete" [ref=e511] [cursor=pointer]
                      - generic "More options" [ref=e514]:
                        - button "More options" [ref=e515] [cursor=pointer]
                - row "More options" [ref=e517]:
                  - gridcell "More options" [ref=e518]:
                    - generic [ref=e519]:
                      - button "Edit" [ref=e520] [cursor=pointer]
                      - button "Delete" [ref=e522] [cursor=pointer]
                      - generic "More options" [ref=e525]:
                        - button "More options" [ref=e526] [cursor=pointer]
                - row "More options" [ref=e528]:
                  - gridcell "More options" [ref=e529]:
                    - generic [ref=e530]:
                      - button "Edit" [ref=e531] [cursor=pointer]
                      - button "Delete" [ref=e533] [cursor=pointer]
                      - generic "More options" [ref=e536]:
                        - button "More options" [ref=e537] [cursor=pointer]
                - row "More options" [ref=e539]:
                  - gridcell "More options" [ref=e540]:
                    - generic [ref=e541]:
                      - button "Edit" [ref=e542] [cursor=pointer]
                      - button "Delete" [ref=e544] [cursor=pointer]
                      - generic "More options" [ref=e547]:
                        - button "More options" [ref=e548] [cursor=pointer]
                - row "More options" [ref=e550]:
                  - gridcell "More options" [ref=e551]:
                    - generic [ref=e552]:
                      - button "Edit" [ref=e553] [cursor=pointer]
                      - button "Delete" [ref=e555] [cursor=pointer]
                      - generic "More options" [ref=e558]:
                        - button "More options" [ref=e559] [cursor=pointer]
                - row "More options" [ref=e561]:
                  - gridcell "More options" [ref=e562]:
                    - generic [ref=e563]:
                      - button "Edit" [ref=e564] [cursor=pointer]
                      - button "Delete" [ref=e566] [cursor=pointer]
                      - generic "More options" [ref=e569]:
                        - button "More options" [ref=e570] [cursor=pointer]
                - row "More options" [ref=e572]:
                  - gridcell "More options" [ref=e573]:
                    - generic [ref=e574]:
                      - button "Edit" [ref=e575] [cursor=pointer]
                      - button "Delete" [ref=e577] [cursor=pointer]
                      - generic "More options" [ref=e580]:
                        - button "More options" [ref=e581] [cursor=pointer]
                - row "More options" [ref=e583]:
                  - gridcell "More options" [ref=e584]:
                    - generic [ref=e585]:
                      - button "Edit" [ref=e586] [cursor=pointer]
                      - button "Delete" [ref=e588] [cursor=pointer]
                      - generic "More options" [ref=e591]:
                        - button "More options" [ref=e592] [cursor=pointer]
                - row "More options" [ref=e594]:
                  - gridcell "More options" [ref=e595]:
                    - generic [ref=e596]:
                      - button "Edit" [ref=e597] [cursor=pointer]
                      - button "Delete" [ref=e599] [cursor=pointer]
                      - generic "More options" [ref=e602]:
                        - button "More options" [ref=e603] [cursor=pointer]
              - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
            - rowgroup
          - generic [ref=e614]:
            - generic [ref=e615]: Showing 1 to 20 of 67 records
            - generic [ref=e616]: Page 1 of 4
            - generic "More options" [ref=e618]:
              - button "Select page size" [ref=e619] [cursor=pointer]: "Page size: 20"
            - button "Download CSV" [ref=e621] [cursor=pointer]
            - generic [ref=e623]:
              - button "Go to the previous page" [disabled] [ref=e624]: Previous
              - button "Go to the next page" [ref=e626] [cursor=pointer]: Next
  - contentinfo [ref=e628]: © 2026 First Due
  - generic:
    - button "Chat Close Maven Chat" [ref=e629] [cursor=pointer]:
      - img "Chat" [ref=e631]
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