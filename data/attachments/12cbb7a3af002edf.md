# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: agency-setup/organization/C5877540-verify-user-can-add-an-organization-division.spec.ts >> Agency setup organization >> @smoke @regression C5877540: Verify user can add an organization division
- Location: src/tests/agency-setup/organization/C5877540-verify-user-can-add-an-organization-division.spec.ts:21:7

# Error details

```
TimeoutError: locator.waitFor: Timeout 60000ms exceeded.
Call log:
  - waiting for locator('role=gridcell[name="Shoes"i]') to be visible

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
        - generic [ref=e20]:
          - text:  
          - button "Help" [ref=e24] [cursor=pointer]
      - main [ref=e26]:
        - generic [ref=e30]:
          - generic [ref=e31]:
            - generic [ref=e32] [cursor=pointer]:
              - generic [ref=e33]: assignment_turned_in
              - generic [ref=e34]: General Information
            - generic [ref=e35]:
              - generic [ref=e36]: stars
              - generic [ref=e37]: Organization
            - generic [ref=e38] [cursor=pointer]:
              - generic [ref=e39]: settings
              - generic [ref=e40]: Settings
            - generic [ref=e41] [cursor=pointer]:
              - generic [ref=e42]: security
              - generic [ref=e43]: Security
          - generic [ref=e45]:
            - text:      
            - generic [ref=e47]:
              - generic [ref=e48]: ORGANIZATION
              - generic [ref=e49]:
                - button "Division (52)" [ref=e50]
                - button "Shift (34)" [ref=e51] [cursor=pointer]
                - button "Rank (32)" [ref=e52] [cursor=pointer]
                - button "Positions (135)" [ref=e53] [cursor=pointer]
              - generic [ref=e57]:
                - search "Search this list" [ref=e59]:
                  - group [ref=e60]:
                    - button "Open search" [ref=e61] [cursor=pointer]: 
                  - button " Filter" [ref=e62] [cursor=pointer]:
                    - generic [ref=e63]: 
                    - text: Filter
                - generic [ref=e64]:
                  - generic [ref=e65]:
                    - generic [ref=e67]:
                      - button "Delete selected" [disabled]:
                        - generic: 
                        - generic: Delete selected
                      - button "Add Division" [ref=e68] [cursor=pointer]
                    - generic [ref=e70]:
                      - treegrid [ref=e72]:
                        - rowgroup [ref=e73]:
                          - row "Select all rows" [ref=e74]:
                            - columnheader "Select all rows" [ref=e75]:
                              - text: 
                              - checkbox "Select all rows" [ref=e78] [cursor=pointer]
                        - rowgroup [ref=e79]:
                          - row "Name" [ref=e80]:
                            - columnheader "Name" [ref=e81]:
                              - text: 
                              - generic [ref=e83] [cursor=pointer]: Name
                              - text: 
                              - generic: ↑ ↓  
                        - rowgroup [ref=e84]:
                          - row "Actions" [ref=e85]:
                            - columnheader "Actions" [ref=e86]:
                              - text: 
                              - generic [ref=e87]: Actions
                        - rowgroup [ref=e88]:
                          - row "Select row, AutoDivision-1788508008206" [ref=e89]:
                            - gridcell "Select row, AutoDivision-1788508008206" [ref=e90]:
                              - checkbox "Select row, AutoDivision-1788508008206" [ref=e93] [cursor=pointer]
                          - row "Select row, AutoDivision-1788508454545" [ref=e94]:
                            - gridcell "Select row, AutoDivision-1788508454545" [ref=e95]:
                              - checkbox "Select row, AutoDivision-1788508454545" [ref=e98] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510003473" [ref=e99]:
                            - gridcell "Select row, AutoDivision-1788510003473" [ref=e100]:
                              - checkbox "Select row, AutoDivision-1788510003473" [ref=e103] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510151734" [ref=e104]:
                            - gridcell "Select row, AutoDivision-1788510151734" [ref=e105]:
                              - checkbox "Select row, AutoDivision-1788510151734" [ref=e108] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510431120" [ref=e109]:
                            - gridcell "Select row, AutoDivision-1788510431120" [ref=e110]:
                              - checkbox "Select row, AutoDivision-1788510431120" [ref=e113] [cursor=pointer]
                          - row "Select row, AutoDivision-1789535406101" [ref=e114]:
                            - gridcell "Select row, AutoDivision-1789535406101" [ref=e115]:
                              - checkbox "Select row, AutoDivision-1789535406101" [ref=e118] [cursor=pointer]
                          - row "Select row, AutoDivision-1788507397802" [ref=e119]:
                            - gridcell "Select row, AutoDivision-1788507397802" [ref=e120]:
                              - checkbox "Select row, AutoDivision-1788507397802" [ref=e123] [cursor=pointer]
                          - row "Select row, AutoDivision-1788508216442" [ref=e124]:
                            - gridcell "Select row, AutoDivision-1788508216442" [ref=e125]:
                              - checkbox "Select row, AutoDivision-1788508216442" [ref=e128] [cursor=pointer]
                          - row "Select row, AutoDivision-1788508591939" [ref=e129]:
                            - gridcell "Select row, AutoDivision-1788508591939" [ref=e130]:
                              - checkbox "Select row, AutoDivision-1788508591939" [ref=e133] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510042799" [ref=e134]:
                            - gridcell "Select row, AutoDivision-1788510042799" [ref=e135]:
                              - checkbox "Select row, AutoDivision-1788510042799" [ref=e138] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510269896" [ref=e139]:
                            - gridcell "Select row, AutoDivision-1788510269896" [ref=e140]:
                              - checkbox "Select row, AutoDivision-1788510269896" [ref=e143] [cursor=pointer]
                          - row "Select row, AutoDivision-1788510470982" [ref=e144]:
                            - gridcell "Select row, AutoDivision-1788510470982" [ref=e145]:
                              - checkbox "Select row, AutoDivision-1788510470982" [ref=e148] [cursor=pointer]
                          - row "Select row, AutoDivision-1788789896138" [ref=e149]:
                            - gridcell "Select row, AutoDivision-1788789896138" [ref=e150]:
                              - checkbox "Select row, AutoDivision-1788789896138" [ref=e153] [cursor=pointer]
                          - row "Select row, AutoDivision-1788843985564" [ref=e154]:
                            - gridcell "Select row, AutoDivision-1788843985564" [ref=e155]:
                              - checkbox "Select row, AutoDivision-1788843985564" [ref=e158] [cursor=pointer]
                          - row "Select row, AutoDivision-1788860278371" [ref=e159]:
                            - gridcell "Select row, AutoDivision-1788860278371" [ref=e160]:
                              - checkbox "Select row, AutoDivision-1788860278371" [ref=e163] [cursor=pointer]
                          - row "Select row, AutoDivision-1788930315430" [ref=e164]:
                            - gridcell "Select row, AutoDivision-1788930315430" [ref=e165]:
                              - checkbox "Select row, AutoDivision-1788930315430" [ref=e168] [cursor=pointer]
                          - row "Select row, AutoDivision-1789016890845" [ref=e169]:
                            - gridcell "Select row, AutoDivision-1789016890845" [ref=e170]:
                              - checkbox "Select row, AutoDivision-1789016890845" [ref=e173] [cursor=pointer]
                          - row "Select row, AutoDivision-1789103176475" [ref=e174]:
                            - gridcell "Select row, AutoDivision-1789103176475" [ref=e175]:
                              - checkbox "Select row, AutoDivision-1789103176475" [ref=e178] [cursor=pointer]
                          - row "Select row, AutoDivision-1789188949086" [ref=e179]:
                            - gridcell "Select row, AutoDivision-1789188949086" [ref=e180]:
                              - checkbox "Select row, AutoDivision-1789188949086" [ref=e183] [cursor=pointer]
                          - row "Select row, AutoDivision-1789276675595" [ref=e184]:
                            - gridcell "Select row, AutoDivision-1789276675595" [ref=e185]:
                              - checkbox "Select row, AutoDivision-1789276675595" [ref=e188] [cursor=pointer]
                        - rowgroup "Grid columns" [ref=e189]:
                          - row "AutoDivision-1788508008206" [ref=e190]:
                            - gridcell "AutoDivision-1788508008206" [ref=e191]
                          - row "AutoDivision-1788508454545" [ref=e192]:
                            - gridcell "AutoDivision-1788508454545" [ref=e193]
                          - row "AutoDivision-1788510003473" [ref=e194]:
                            - gridcell "AutoDivision-1788510003473" [ref=e195]
                          - row "AutoDivision-1788510151734" [ref=e196]:
                            - gridcell "AutoDivision-1788510151734" [ref=e197]
                          - row "AutoDivision-1788510431120" [ref=e198]:
                            - gridcell "AutoDivision-1788510431120" [ref=e199]
                          - row "AutoDivision-1789535406101" [ref=e200]:
                            - gridcell "AutoDivision-1789535406101" [ref=e201]
                          - row "AutoDivision-1788507397802" [ref=e202]:
                            - gridcell "AutoDivision-1788507397802" [ref=e203]
                          - row "AutoDivision-1788508216442" [ref=e204]:
                            - gridcell "AutoDivision-1788508216442" [ref=e205]
                          - row "AutoDivision-1788508591939" [ref=e206]:
                            - gridcell "AutoDivision-1788508591939" [ref=e207]
                          - row "AutoDivision-1788510042799" [ref=e208]:
                            - gridcell "AutoDivision-1788510042799" [ref=e209]
                          - row "AutoDivision-1788510269896" [ref=e210]:
                            - gridcell "AutoDivision-1788510269896" [ref=e211]
                          - row "AutoDivision-1788510470982" [ref=e212]:
                            - gridcell "AutoDivision-1788510470982" [ref=e213]
                          - row "AutoDivision-1788789896138" [ref=e214]:
                            - gridcell "AutoDivision-1788789896138" [ref=e215]
                          - row "AutoDivision-1788843985564" [ref=e216]:
                            - gridcell "AutoDivision-1788843985564" [ref=e217]
                          - row "AutoDivision-1788860278371" [ref=e218]:
                            - gridcell "AutoDivision-1788860278371" [ref=e219]
                          - row "AutoDivision-1788930315430" [ref=e220]:
                            - gridcell "AutoDivision-1788930315430" [ref=e221]
                          - row "AutoDivision-1789016890845" [ref=e222]:
                            - gridcell "AutoDivision-1789016890845" [ref=e223]
                          - row "AutoDivision-1789103176475" [ref=e224]:
                            - gridcell "AutoDivision-1789103176475" [ref=e225]
                          - row "AutoDivision-1789188949086" [ref=e226]:
                            - gridcell "AutoDivision-1789188949086" [ref=e227]
                          - row "AutoDivision-1789276675595" [ref=e228]:
                            - gridcell "AutoDivision-1789276675595" [ref=e229]
                        - rowgroup [ref=e230]:
                          - row "Edit Delete" [ref=e231]:
                            - gridcell "Edit Delete" [ref=e232]:
                              - generic [ref=e233]:
                                - button "Edit" [ref=e235] [cursor=pointer]: 
                                - button "Delete" [ref=e237] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e238]:
                            - gridcell "Edit Delete" [ref=e239]:
                              - generic [ref=e240]:
                                - button "Edit" [ref=e242] [cursor=pointer]: 
                                - button "Delete" [ref=e244] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e245]:
                            - gridcell "Edit Delete" [ref=e246]:
                              - generic [ref=e247]:
                                - button "Edit" [ref=e249] [cursor=pointer]: 
                                - button "Delete" [ref=e251] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e252]:
                            - gridcell "Edit Delete" [ref=e253]:
                              - generic [ref=e254]:
                                - button "Edit" [ref=e256] [cursor=pointer]: 
                                - button "Delete" [ref=e258] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e259]:
                            - gridcell "Edit Delete" [ref=e260]:
                              - generic [ref=e261]:
                                - button "Edit" [ref=e263] [cursor=pointer]: 
                                - button "Delete" [ref=e265] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e266]:
                            - gridcell "Edit Delete" [ref=e267]:
                              - generic [ref=e268]:
                                - button "Edit" [ref=e270] [cursor=pointer]: 
                                - button "Delete" [ref=e272] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e273]:
                            - gridcell "Edit Delete" [ref=e274]:
                              - generic [ref=e275]:
                                - button "Edit" [ref=e277] [cursor=pointer]: 
                                - button "Delete" [ref=e279] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e280]:
                            - gridcell "Edit Delete" [ref=e281]:
                              - generic [ref=e282]:
                                - button "Edit" [ref=e284] [cursor=pointer]: 
                                - button "Delete" [ref=e286] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e287]:
                            - gridcell "Edit Delete" [ref=e288]:
                              - generic [ref=e289]:
                                - button "Edit" [ref=e291] [cursor=pointer]: 
                                - button "Delete" [ref=e293] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e294]:
                            - gridcell "Edit Delete" [ref=e295]:
                              - generic [ref=e296]:
                                - button "Edit" [ref=e298] [cursor=pointer]: 
                                - button "Delete" [ref=e300] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e301]:
                            - gridcell "Edit Delete" [ref=e302]:
                              - generic [ref=e303]:
                                - button "Edit" [ref=e305] [cursor=pointer]: 
                                - button "Delete" [ref=e307] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e308]:
                            - gridcell "Edit Delete" [ref=e309]:
                              - generic [ref=e310]:
                                - button "Edit" [ref=e312] [cursor=pointer]: 
                                - button "Delete" [ref=e314] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e315]:
                            - gridcell "Edit Delete" [ref=e316]:
                              - generic [ref=e317]:
                                - button "Edit" [ref=e319] [cursor=pointer]: 
                                - button "Delete" [ref=e321] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e322]:
                            - gridcell "Edit Delete" [ref=e323]:
                              - generic [ref=e324]:
                                - button "Edit" [ref=e326] [cursor=pointer]: 
                                - button "Delete" [ref=e328] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e329]:
                            - gridcell "Edit Delete" [ref=e330]:
                              - generic [ref=e331]:
                                - button "Edit" [ref=e333] [cursor=pointer]: 
                                - button "Delete" [ref=e335] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e336]:
                            - gridcell "Edit Delete" [ref=e337]:
                              - generic [ref=e338]:
                                - button "Edit" [ref=e340] [cursor=pointer]: 
                                - button "Delete" [ref=e342] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e343]:
                            - gridcell "Edit Delete" [ref=e344]:
                              - generic [ref=e345]:
                                - button "Edit" [ref=e347] [cursor=pointer]: 
                                - button "Delete" [ref=e349] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e350]:
                            - gridcell "Edit Delete" [ref=e351]:
                              - generic [ref=e352]:
                                - button "Edit" [ref=e354] [cursor=pointer]: 
                                - button "Delete" [ref=e356] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e357]:
                            - gridcell "Edit Delete" [ref=e358]:
                              - generic [ref=e359]:
                                - button "Edit" [ref=e361] [cursor=pointer]: 
                                - button "Delete" [ref=e363] [cursor=pointer]: 
                          - row "Edit Delete" [ref=e364]:
                            - gridcell "Edit Delete" [ref=e365]:
                              - generic [ref=e366]:
                                - button "Edit" [ref=e368] [cursor=pointer]: 
                                - button "Delete" [ref=e370] [cursor=pointer]: 
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
                    - generic [ref=e375]:
                      - navigation "Pagination" [ref=e376]:
                        - list [ref=e377]:
                          - listitem "Page 1" [ref=e378] [cursor=pointer]:
                            - generic [ref=e379]: "1"
                          - listitem "Page 2" [ref=e380] [cursor=pointer]:
                            - generic [ref=e381]: "2"
                          - listitem "Page 3" [ref=e382] [cursor=pointer]:
                            - generic [ref=e383]: "3"
                          - listitem "Next page" [ref=e384] [cursor=pointer]:
                            - generic [ref=e386]: 
                      - generic [ref=e387]:
                        - generic [ref=e388]: "Show:"
                        - list [ref=e390]:
                          - listitem "Show 20 per page" [ref=e391] [cursor=pointer]:
                            - generic [ref=e392]: "20"
                          - listitem "Show 50 per page" [ref=e393] [cursor=pointer]:
                            - generic [ref=e394]: "50"
                          - listitem "Show 100 per page" [ref=e395] [cursor=pointer]:
                            - generic [ref=e396]: "100"
                        - link "Download CSV" [ref=e398] [cursor=pointer]:
                          - /url: "#"
                          - generic [ref=e399]: 
                        - generic [ref=e400]: Showing 1 to 20 of 52
                  - generic [ref=e402]:
                    - generic [ref=e403]:
                      - generic [ref=e404]:
                        - generic [ref=e405]: 
                        - text: Filter
                      - generic [ref=e406]:
                        - button [ref=e407] [cursor=pointer]:
                          - generic: 
                        - button [ref=e408] [cursor=pointer]:
                          - generic: 
                    - generic [ref=e410]:
                      - generic [ref=e411]: "Name:"
                      - textbox [ref=e414]
                    - generic [ref=e415]:
                      - button [ref=e416] [cursor=pointer]:
                        - generic [ref=e417]: 
                        - text: Reset
                      - button [ref=e418] [cursor=pointer]: Cancel
                      - button [ref=e419] [cursor=pointer]:
                        - generic [ref=e420]: 
                        - text: Apply
                - text: 
            - text:                      
      - contentinfo [ref=e421]:
        - text: © 2017-2026 First Due. Powered by
        - link "LocalityMedia, Inc" [ref=e422] [cursor=pointer]:
          - /url: https://www.firstdue.com/
        - text: .
    - text: 
  - generic [ref=e423]:
    - button "Close" [ref=e424] [cursor=pointer]: 
    - generic [ref=e428]:
      - heading "Add Division" [level=2] [ref=e429]
      - generic [ref=e430]:
        - generic [ref=e431]: Name (required)
        - textbox "Name (required)" [ref=e432]: Shoes
      - generic [ref=e433]:
        - button "Save" [ref=e434] [cursor=pointer]: Save 
        - generic [ref=e435] [cursor=pointer]: Cancel
  - button [ref=e436] [cursor=pointer]
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