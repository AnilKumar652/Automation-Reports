# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: agency-setup/organization/C5877541-verify-user-can-add-an-organization-shift.spec.ts >> Agency setup organization >> @smoke @regression C5877541: Verify user can add an organization shift
- Location: src/tests/agency-setup/organization/C5877541-verify-user-can-add-an-organization-shift.spec.ts:21:7

# Error details

```
TimeoutError: locator.waitFor: Timeout 60000ms exceeded.
Call log:
  - waiting for locator('role=gridcell[name="B Shift"i]') to be visible

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - link "Skip to main content":
    - /url: "#main-content"
  - generic [ref=e2]:
    - generic [ref=e4]:
      - banner [ref=e5]:
        - button "Show main sidebar" [ref=e8]:
          - img [ref=e9]
        - generic [ref=e14]:
          - generic [ref=e15]:
            - button "menu" [ref=e16] [cursor=pointer]:
              - generic [ref=e17]: menu
            - heading "Agency Setup" [level=4] [ref=e18]
          - generic [ref=e19]:
            - button "save Save" [disabled]:
              - generic: save
              - text: Save
        - generic:  
      - main [ref=e20]:
        - generic [ref=e24]:
          - generic [ref=e25]:
            - generic [ref=e26] [cursor=pointer]:
              - generic [ref=e27]: assignment_turned_in
              - generic [ref=e28]: General Information
            - generic [ref=e29]:
              - generic [ref=e30]: stars
              - generic [ref=e31]: Organization
            - generic [ref=e32] [cursor=pointer]:
              - generic [ref=e33]: settings
              - generic [ref=e34]: Settings
            - generic [ref=e35] [cursor=pointer]:
              - generic [ref=e36]: security
              - generic [ref=e37]: Security
          - generic [ref=e39]:
            - text:      
            - generic [ref=e41]:
              - generic [ref=e42]: ORGANIZATION
              - generic [ref=e43]:
                - button "Division (52)" [ref=e44] [cursor=pointer]
                - button "Shift (34)" [ref=e45]
                - button "Rank (32)" [ref=e46] [cursor=pointer]
                - button "Positions (121)" [ref=e47] [cursor=pointer]
              - generic [ref=e51]:
                - search "Search this list" [ref=e53]:
                  - group [ref=e54]:
                    - button "Open search" [ref=e55] [cursor=pointer]: 
                  - button " Filter" [ref=e56] [cursor=pointer]:
                    - generic [ref=e57]: 
                    - text: Filter
                - generic [ref=e58]:
                  - generic [ref=e59]:
                    - generic [ref=e61]:
                      - button "Delete selected" [disabled]:
                        - generic: 
                        - generic: Delete selected
                      - button "Add Shift" [ref=e62] [cursor=pointer]
                    - generic [ref=e64]:
                      - treegrid [ref=e66]:
                        - rowgroup [ref=e67]:
                          - row "Select all rows" [ref=e68]:
                            - columnheader "Select all rows" [ref=e69]:
                              - text: 
                              - checkbox "Select all rows" [ref=e72] [cursor=pointer]
                        - rowgroup [ref=e73]:
                          - row "Name" [ref=e74]:
                            - columnheader "Name" [ref=e75]:
                              - text: 
                              - generic [ref=e77] [cursor=pointer]: Name
                              - text: 
                              - generic: ↑ ↓  
                        - rowgroup [ref=e78]:
                          - row "Actions" [ref=e79]:
                            - columnheader "Actions" [ref=e80]:
                              - text: 
                              - generic [ref=e81]: Actions
                        - rowgroup [ref=e82]:
                          - row "Select row, AutoShift-1788509959087" [ref=e83]:
                            - gridcell "Select row, AutoShift-1788509959087" [ref=e84]:
                              - checkbox "Select row, AutoShift-1788509959087" [ref=e87] [cursor=pointer]
                          - row "Select row, AutoShift-1788510426411" [ref=e88]:
                            - gridcell "Select row, AutoShift-1788510426411" [ref=e89]:
                              - checkbox "Select row, AutoShift-1788510426411" [ref=e92] [cursor=pointer]
                          - row "Select row, A Shift" [ref=e93]:
                            - gridcell "Select row, A Shift" [ref=e94]:
                              - checkbox "Select row, A Shift" [ref=e97] [cursor=pointer]
                          - row "Select row, C Shift" [ref=e98]:
                            - gridcell "Select row, C Shift" [ref=e99]:
                              - checkbox "Select row, C Shift" [ref=e102] [cursor=pointer]
                          - row "Select row, Night Shift" [ref=e103]:
                            - gridcell "Select row, Night Shift" [ref=e104]:
                              - checkbox "Select row, Night Shift" [ref=e107] [cursor=pointer]
                          - row "Select row, AutoShift-1788510008823" [ref=e108]:
                            - gridcell "Select row, AutoShift-1788510008823" [ref=e109]:
                              - checkbox "Select row, AutoShift-1788510008823" [ref=e112] [cursor=pointer]
                          - row "Select row, AutoShift-1788510482696" [ref=e113]:
                            - gridcell "Select row, AutoShift-1788510482696" [ref=e114]:
                              - checkbox "Select row, AutoShift-1788510482696" [ref=e117] [cursor=pointer]
                          - row "Select row, AutoShift-1789535318604" [ref=e118]:
                            - gridcell "Select row, AutoShift-1789535318604" [ref=e119]:
                              - checkbox "Select row, AutoShift-1789535318604" [ref=e122] [cursor=pointer]
                          - row "Select row, Evening Shift" [ref=e123]:
                            - gridcell "Select row, Evening Shift" [ref=e124]:
                              - checkbox "Select row, Evening Shift" [ref=e127] [cursor=pointer]
                          - row "Select row, Morning Shift" [ref=e128]:
                            - gridcell "Select row, Morning Shift" [ref=e129]:
                              - checkbox "Select row, Morning Shift" [ref=e132] [cursor=pointer]
                          - row "Select row, AutoShift-1788507537993" [ref=e133]:
                            - gridcell "Select row, AutoShift-1788507537993" [ref=e134]:
                              - checkbox "Select row, AutoShift-1788507537993" [ref=e137] [cursor=pointer]
                          - row "Select row, AutoShift-1788510072345" [ref=e138]:
                            - gridcell "Select row, AutoShift-1788510072345" [ref=e139]:
                              - checkbox "Select row, AutoShift-1788510072345" [ref=e142] [cursor=pointer]
                          - row "Select row, AutoShift-1788508001136" [ref=e143]:
                            - gridcell "Select row, AutoShift-1788508001136" [ref=e144]:
                              - checkbox "Select row, AutoShift-1788508001136" [ref=e147] [cursor=pointer]
                          - row "Select row, AutoShift-1788510127876" [ref=e148]:
                            - gridcell "Select row, AutoShift-1788510127876" [ref=e149]:
                              - checkbox "Select row, AutoShift-1788510127876" [ref=e152] [cursor=pointer]
                          - row "Select row, AutoShift-1788508344762" [ref=e153]:
                            - gridcell "Select row, AutoShift-1788508344762" [ref=e154]:
                              - checkbox "Select row, AutoShift-1788508344762" [ref=e157] [cursor=pointer]
                          - row "Select row, AutoShift-1788510174021" [ref=e158]:
                            - gridcell "Select row, AutoShift-1788510174021" [ref=e159]:
                              - checkbox "Select row, AutoShift-1788510174021" [ref=e162] [cursor=pointer]
                          - row "Select row, AutoShift-1788510539249" [ref=e163]:
                            - gridcell "Select row, AutoShift-1788510539249" [ref=e164]:
                              - checkbox "Select row, AutoShift-1788510539249" [ref=e167] [cursor=pointer]
                          - row "Select row, AutoShift-1788508478426" [ref=e168]:
                            - gridcell "Select row, AutoShift-1788508478426" [ref=e169]:
                              - checkbox "Select row, AutoShift-1788508478426" [ref=e172] [cursor=pointer]
                          - row "Select row, AutoShift-1788510262801" [ref=e173]:
                            - gridcell "Select row, AutoShift-1788510262801" [ref=e174]:
                              - checkbox "Select row, AutoShift-1788510262801" [ref=e177] [cursor=pointer]
                          - row "Select row, AutoShift-1788789898829" [ref=e178]:
                            - gridcell "Select row, AutoShift-1788789898829" [ref=e179]:
                              - checkbox "Select row, AutoShift-1788789898829" [ref=e182] [cursor=pointer]
                        - rowgroup "Grid columns" [ref=e183]:
                          - row "AutoShift-1788509959087" [ref=e184]:
                            - gridcell "AutoShift-1788509959087" [ref=e185]
                          - row "AutoShift-1788510426411" [ref=e186]:
                            - gridcell "AutoShift-1788510426411" [ref=e187]
                          - row "A Shift" [ref=e188]:
                            - gridcell "A Shift" [ref=e189]
                          - row "C Shift" [ref=e190]:
                            - gridcell "C Shift" [ref=e191]
                          - row "Night Shift" [ref=e192]:
                            - gridcell "Night Shift" [ref=e193]
                          - row "AutoShift-1788510008823" [ref=e194]:
                            - gridcell "AutoShift-1788510008823" [ref=e195]
                          - row "AutoShift-1788510482696" [ref=e196]:
                            - gridcell "AutoShift-1788510482696" [ref=e197]
                          - row "AutoShift-1789535318604" [ref=e198]:
                            - gridcell "AutoShift-1789535318604" [ref=e199]
                          - row "Evening Shift" [ref=e200]:
                            - gridcell "Evening Shift" [ref=e201]
                          - row "Morning Shift" [ref=e202]:
                            - gridcell "Morning Shift" [ref=e203]
                          - row "AutoShift-1788507537993" [ref=e204]:
                            - gridcell "AutoShift-1788507537993" [ref=e205]
                          - row "AutoShift-1788510072345" [ref=e206]:
                            - gridcell "AutoShift-1788510072345" [ref=e207]
                          - row "AutoShift-1788508001136" [ref=e208]:
                            - gridcell "AutoShift-1788508001136" [ref=e209]
                          - row "AutoShift-1788510127876" [ref=e210]:
                            - gridcell "AutoShift-1788510127876" [ref=e211]
                          - row "AutoShift-1788508344762" [ref=e212]:
                            - gridcell "AutoShift-1788508344762" [ref=e213]
                          - row "AutoShift-1788510174021" [ref=e214]:
                            - gridcell "AutoShift-1788510174021" [ref=e215]
                          - row "AutoShift-1788510539249" [ref=e216]:
                            - gridcell "AutoShift-1788510539249" [ref=e217]
                          - row "AutoShift-1788508478426" [ref=e218]:
                            - gridcell "AutoShift-1788508478426" [ref=e219]
                          - row "AutoShift-1788510262801" [ref=e220]:
                            - gridcell "AutoShift-1788510262801" [ref=e221]
                          - row "AutoShift-1788789898829" [ref=e222]:
                            - gridcell "AutoShift-1788789898829" [ref=e223]
                        - rowgroup [ref=e224]:
                          - row "Edit Delete" [ref=e225]:
                            - gridcell "Edit Delete" [ref=e226]:
                              - generic [ref=e227]:
                                - button "Edit" [ref=e229] [cursor=pointer]: 
                                - button "Delete" [ref=e231] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e232]:
                            - gridcell "Edit Delete" [ref=e233]:
                              - generic [ref=e234]:
                                - button "Edit" [ref=e236] [cursor=pointer]: 
                                - button "Delete" [ref=e238] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e239]:
                            - gridcell "Edit Delete" [ref=e240]:
                              - generic [ref=e241]:
                                - button "Edit" [ref=e243] [cursor=pointer]: 
                                - button "Delete" [ref=e245] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e246]:
                            - gridcell "Edit Delete" [ref=e247]:
                              - generic [ref=e248]:
                                - button "Edit" [ref=e250] [cursor=pointer]: 
                                - button "Delete" [ref=e252] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e253]:
                            - gridcell "Edit Delete" [ref=e254]:
                              - generic [ref=e255]:
                                - button "Edit" [ref=e257] [cursor=pointer]: 
                                - button "Delete" [ref=e259] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e260]:
                            - gridcell "Edit Delete" [ref=e261]:
                              - generic [ref=e262]:
                                - button "Edit" [ref=e264] [cursor=pointer]: 
                                - button "Delete" [ref=e266] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e267]:
                            - gridcell "Edit Delete" [ref=e268]:
                              - generic [ref=e269]:
                                - button "Edit" [ref=e271] [cursor=pointer]: 
                                - button "Delete" [ref=e273] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e274]:
                            - gridcell "Edit Delete" [ref=e275]:
                              - generic [ref=e276]:
                                - button "Edit" [ref=e278] [cursor=pointer]: 
                                - button "Delete" [ref=e280] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e281]:
                            - gridcell "Edit Delete" [ref=e282]:
                              - generic [ref=e283]:
                                - button "Edit" [ref=e285] [cursor=pointer]: 
                                - button "Delete" [ref=e287] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e288]:
                            - gridcell "Edit Delete" [ref=e289]:
                              - generic [ref=e290]:
                                - button "Edit" [ref=e292] [cursor=pointer]: 
                                - button "Delete" [ref=e294] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e295]:
                            - gridcell "Edit Delete" [ref=e296]:
                              - generic [ref=e297]:
                                - button "Edit" [ref=e299] [cursor=pointer]: 
                                - button "Delete" [ref=e301] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e302]:
                            - gridcell "Edit Delete" [ref=e303]:
                              - generic [ref=e304]:
                                - button "Edit" [ref=e306] [cursor=pointer]: 
                                - button "Delete" [ref=e308] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e309]:
                            - gridcell "Edit Delete" [ref=e310]:
                              - generic [ref=e311]:
                                - button "Edit" [ref=e313] [cursor=pointer]: 
                                - button "Delete" [ref=e315] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e316]:
                            - gridcell "Edit Delete" [ref=e317]:
                              - generic [ref=e318]:
                                - button "Edit" [ref=e320] [cursor=pointer]: 
                                - button "Delete" [ref=e322] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e323]:
                            - gridcell "Edit Delete" [ref=e324]:
                              - generic [ref=e325]:
                                - button "Edit" [ref=e327] [cursor=pointer]: 
                                - button "Delete" [ref=e329] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e330]:
                            - gridcell "Edit Delete" [ref=e331]:
                              - generic [ref=e332]:
                                - button "Edit" [ref=e334] [cursor=pointer]: 
                                - button "Delete" [ref=e336] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e337]:
                            - gridcell "Edit Delete" [ref=e338]:
                              - generic [ref=e339]:
                                - button "Edit" [ref=e341] [cursor=pointer]: 
                                - button "Delete" [ref=e343] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e344]:
                            - gridcell "Edit Delete" [ref=e345]:
                              - generic [ref=e346]:
                                - button "Edit" [ref=e348] [cursor=pointer]: 
                                - button "Delete" [ref=e350] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e351]:
                            - gridcell "Edit Delete" [ref=e352]:
                              - generic [ref=e353]:
                                - button "Edit" [ref=e355] [cursor=pointer]: 
                                - button "Delete" [ref=e357] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e358]:
                            - gridcell "Edit Delete" [ref=e359]:
                              - generic [ref=e360]:
                                - button "Edit" [ref=e362] [cursor=pointer]: 
                                - button "Delete" [ref=e364] [cursor=pointer]: 
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                        - rowgroup
                      - text:    
                    - generic [ref=e369]:
                      - navigation "Pagination" [ref=e370]:
                        - list [ref=e371]:
                          - listitem "Page 1" [ref=e372] [cursor=pointer]:
                            - generic [ref=e373]: "1"
                          - listitem "Page 2" [ref=e374] [cursor=pointer]:
                            - generic [ref=e375]: "2"
                          - listitem "Next page" [ref=e376] [cursor=pointer]:
                            - generic [ref=e378]: 
                      - generic [ref=e379]:
                        - generic [ref=e380]: "Show:"
                        - list [ref=e382]:
                          - listitem "Show 20 per page" [ref=e383] [cursor=pointer]:
                            - generic [ref=e384]: "20"
                          - listitem "Show 50 per page" [ref=e385] [cursor=pointer]:
                            - generic [ref=e386]: "50"
                          - listitem "Show 100 per page" [ref=e387] [cursor=pointer]:
                            - generic [ref=e388]: "100"
                        - link "Download CSV" [ref=e390] [cursor=pointer]:
                          - /url: "#"
                          - generic [ref=e391]: 
                        - generic [ref=e392]: Showing 1 to 20 of 34
                  - generic [ref=e394]:
                    - generic [ref=e395]:
                      - generic [ref=e396]:
                        - generic [ref=e397]: 
                        - text: Filter
                      - generic [ref=e398]:
                        - button [ref=e399] [cursor=pointer]:
                          - generic: 
                        - button [ref=e400] [cursor=pointer]:
                          - generic: 
                    - generic [ref=e402]:
                      - generic [ref=e403]: "Name:"
                      - textbox [ref=e406]
                    - generic [ref=e407]:
                      - button [ref=e408] [cursor=pointer]:
                        - generic [ref=e409]: 
                        - text: Reset
                      - button [ref=e410] [cursor=pointer]: Cancel
                      - button [ref=e411] [cursor=pointer]:
                        - generic [ref=e412]: 
                        - text: Apply
                - text: 
            - text:                      
      - contentinfo [ref=e413]:
        - text: © 2017-2026 First Due. Powered by
        - link "LocalityMedia, Inc" [ref=e414] [cursor=pointer]:
          - /url: https://www.firstdue.com/
        - text: .
    - text: 
  - generic [ref=e415]:
    - generic [ref=e416] [cursor=pointer]: 
    - generic [ref=e420]:
      - heading "Add Shift" [level=2] [ref=e421]
      - generic [ref=e422]:
        - generic [ref=e423]: Name (required)
        - textbox "Name (required)" [ref=e424]: B Shift
      - generic [ref=e425]:
        - button "Save" [ref=e426] [cursor=pointer]: Save 
        - generic [ref=e427] [cursor=pointer]: Cancel
  - button "Live Chat Button" [ref=e429] [cursor=pointer]:
    - img "Live Chat Button" [ref=e430]
    - button "Close CustomGPT"
```

# Test source

```ts
  1   | import type { Actor } from '../Actor';
  2   | import { Interaction } from '../Interaction';
  3   | import type { Target } from '../Target';
  4   | import { resolveLocator } from '../Target';
  5   | import { BrowseTheWeb } from '../abilities/BrowseTheWeb';
  6   | import { Timeouts } from '@/config';
  7   | 
  8   | type SelectorState = 'attached' | 'detached' | 'visible' | 'hidden';
  9   | 
  10  | type WaitCondition =
  11  |   | { type: 'selector'; target: Target | string; state?: SelectorState; timeout?: number }
  12  |   | { type: 'load'; state?: 'load' | 'domcontentloaded' | 'networkidle' }
  13  |   | { type: 'url'; pathFragment: string; negate?: boolean; timeout?: number }
  14  |   | { type: 'urlOrError'; pathFragment: string; errorTarget: Target | string; timeout?: number };
  15  | 
  16  | export class Wait extends Interaction {
  17  |   private constructor(private readonly condition: WaitCondition) {
  18  |     super();
  19  |   }
  20  | 
  21  |   static until(
  22  |     target: Target | string,
  23  |     state: SelectorState = 'visible',
  24  |     timeout?: number,
  25  |   ): Wait {
  26  |     return new Wait({ type: 'selector', target, state, timeout });
  27  |   }
  28  | 
  29  |   static forLoadState(state: 'load' | 'domcontentloaded' | 'networkidle' = 'networkidle'): Wait {
  30  |     return new Wait({ type: 'load', state });
  31  |   }
  32  | 
  33  |   static untilUrlLeaves(pathFragment: string, timeout?: number): Wait {
  34  |     return new Wait({ type: 'url', pathFragment, negate: true, timeout });
  35  |   }
  36  | 
  37  |   static untilUrlLeavesOrError(
  38  |     pathFragment: string,
  39  |     errorTarget: Target | string,
  40  |     timeout?: number,
  41  |   ): Wait {
  42  |     return new Wait({ type: 'urlOrError', pathFragment, errorTarget, timeout });
  43  |   }
  44  | 
  45  |   describeAction(): string {
  46  |     switch (this.condition.type) {
  47  |       case 'selector': {
  48  |         const state = this.condition.state ?? 'visible';
  49  |         const timeoutSuffix = this.condition.timeout ? ` within ${this.condition.timeout}ms` : '';
  50  |         return `Wait until ${Interaction.targetLabel(this.condition.target)} is ${state}${timeoutSuffix}`;
  51  |       }
  52  |       case 'load':
  53  |         return `Wait for load state "${this.condition.state ?? 'networkidle'}"`;
  54  |       case 'url': {
  55  |         const timeoutSuffix = this.condition.timeout ? ` within ${this.condition.timeout}ms` : '';
  56  |         return this.condition.negate
  57  |           ? `Wait until URL leaves "${this.condition.pathFragment}"${timeoutSuffix}`
  58  |           : `Wait until URL contains "${this.condition.pathFragment}"${timeoutSuffix}`;
  59  |       }
  60  |       case 'urlOrError': {
  61  |         const timeoutSuffix = this.condition.timeout ? ` within ${this.condition.timeout}ms` : '';
  62  |         return `Wait until URL leaves "${this.condition.pathFragment}" or login error appears${timeoutSuffix}`;
  63  |       }
  64  |     }
  65  |   }
  66  | 
  67  |   describeDebugDetails(): string | undefined {
  68  |     switch (this.condition.type) {
  69  |       case 'selector':
  70  |         return Interaction.locatorDetail(this.condition.target);
  71  |       case 'urlOrError':
  72  |         return Interaction.locatorDetail(this.condition.errorTarget);
  73  |       default:
  74  |         return undefined;
  75  |     }
  76  |   }
  77  | 
  78  |   async performAs(actor: Actor): Promise<void> {
  79  |     const { page } = actor.abilityTo(BrowseTheWeb);
  80  | 
  81  |     switch (this.condition.type) {
  82  |       case 'selector':
> 83  |         await page.locator(resolveLocator(this.condition.target)).waitFor({
      |                                                                   ^ TimeoutError: locator.waitFor: Timeout 60000ms exceeded.
  84  |           state: this.condition.state,
  85  |           timeout: this.condition.timeout ?? Timeouts.default,
  86  |         });
  87  |         break;
  88  |       case 'load':
  89  |         await page.waitForLoadState(this.condition.state);
  90  |         break;
  91  |       case 'url': {
  92  |         const { pathFragment, negate, timeout } = this.condition;
  93  |         await page.waitForURL(
  94  |           (url) => negate
  95  |             ? !url.pathname.includes(pathFragment)
  96  |             : url.pathname.includes(pathFragment),
  97  |           {
  98  |             timeout: timeout ?? Timeouts.default,
  99  |             waitUntil: 'commit',
  100 |           },
  101 |         );
  102 |         break;
  103 |       }
  104 |       case 'urlOrError': {
  105 |         const { pathFragment, errorTarget, timeout } = this.condition;
  106 |         const resolvedTimeout = timeout ?? Timeouts.default;
  107 |         const errorLocator = page
  108 |           .locator(resolveLocator(errorTarget))
  109 |           .filter({ hasText: /\S/ });
  110 | 
  111 |         await Promise.race([
  112 |           page.waitForURL(
  113 |             (url) => !url.pathname.includes(pathFragment),
  114 |             { timeout: resolvedTimeout, waitUntil: 'commit' },
  115 |           ),
  116 |           errorLocator.first().waitFor({ state: 'visible', timeout: resolvedTimeout }).then(async () => {
  117 |             const message = (await errorLocator.first().textContent())?.trim() ?? 'Unknown login error';
  118 |             throw new Error(`Login failed: ${message}`);
  119 |           }),
  120 |         ]);
  121 |         break;
  122 |       }
  123 |     }
  124 |   }
  125 | }
  126 | 
```