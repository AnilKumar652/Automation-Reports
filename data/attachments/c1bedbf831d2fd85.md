# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: asset-management-setup/location-groups/C45059-create-edit-station-groups.spec.ts >> Asset management setup location groups >> C45059: Create/Edit Station Groups
- Location: src/tests/asset-management-setup/location-groups/C45059-create-edit-station-groups.spec.ts:17:7

# Error details

```
TimeoutError: locator.waitFor: Timeout 60000ms exceeded.
Call log:
  - waiting for locator('role=cell[name="West Midlands Team"i]') to be visible

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
        - generic [ref=e14]: Setup
        - generic:
          - generic:  
      - main [ref=e15]:
        - generic [ref=e21]:
          - list [ref=e23]:
            - listitem [ref=e24]:
              - generic "Settings" [ref=e25] [cursor=pointer]
            - listitem [ref=e26]:
              - generic "Checklist" [ref=e27] [cursor=pointer]
            - listitem [ref=e28]:
              - generic "Work Orders" [ref=e29] [cursor=pointer]
            - listitem [ref=e30]:
              - generic "Preventative Maintenance" [ref=e31] [cursor=pointer]
            - listitem [ref=e32]:
              - generic "Notification" [ref=e33] [cursor=pointer]
            - listitem [ref=e34]:
              - generic "External Sharing" [ref=e35] [cursor=pointer]
            - listitem [ref=e36]:
              - generic "Apparatus Groups" [ref=e37] [cursor=pointer]
            - listitem [ref=e38]:
              - generic "Equipment Groups" [ref=e39] [cursor=pointer]
            - listitem [ref=e40]:
              - generic "Location Groups" [ref=e41] [cursor=pointer]
            - listitem [ref=e42]:
              - generic "Kit Groups" [ref=e43] [cursor=pointer]
            - listitem [ref=e44]:
              - generic "Fluid Types" [ref=e45] [cursor=pointer]
            - listitem [ref=e46]:
              - generic "Inventory" [ref=e47] [cursor=pointer]
            - listitem [ref=e48]:
              - generic "Orders" [ref=e49] [cursor=pointer]
            - listitem [ref=e50]:
              - generic "FEMA Cost Codes" [ref=e51] [cursor=pointer]
          - generic [ref=e54]:
            - heading "Location Groups" [level=2] [ref=e56]
            - search [ref=e57]:
              - generic [ref=e58]:
                - generic [ref=e59]:
                  - generic [ref=e60]:
                    - generic [ref=e61]: Name
                    - textbox "Name" [ref=e63]
                  - generic [ref=e64]:
                    - generic [ref=e65]: Description
                    - textbox "Description" [ref=e67]
                - generic [ref=e68]:
                  - button "Search" [ref=e69] [cursor=pointer]
                  - link "Reset" [ref=e70] [cursor=pointer]:
                    - /url: "#"
              - generic "Download" [ref=e72]:
                - generic [ref=e73]: 
            - generic "New Location Group" [ref=e76] [cursor=pointer]
            - table [ref=e77]:
              - rowgroup [ref=e78]:
                - row "Position Name Description Actions" [ref=e79]:
                  - columnheader "Position" [ref=e80]
                  - columnheader "Name" [ref=e81]
                  - columnheader "Description" [ref=e82]
                  - columnheader "Actions" [ref=e83]
              - rowgroup [ref=e84]:
                - row " AutoLocationGroup-1788790000013 Automation location group 1788790000013  " [ref=e85]:
                  - cell "" [ref=e86]:
                    - generic "Drag and Drop" [ref=e87]: 
                  - cell "AutoLocationGroup-1788790000013" [ref=e88]
                  - cell "Automation location group 1788790000013" [ref=e89]
                  - cell " " [ref=e90]:
                    - generic "Edit" [ref=e91] [cursor=pointer]: 
                    - generic "Delete" [ref=e92] [cursor=pointer]: 
                - row " AutoLocationGroup-1788844028818 Automation location group 1788844028818  " [ref=e93]:
                  - cell "" [ref=e94]:
                    - generic "Drag and Drop" [ref=e95]: 
                  - cell "AutoLocationGroup-1788844028818" [ref=e96]
                  - cell "Automation location group 1788844028818" [ref=e97]
                  - cell " " [ref=e98]:
                    - generic "Edit" [ref=e99] [cursor=pointer]: 
                    - generic "Delete" [ref=e100] [cursor=pointer]: 
                - row " AutoLocationGroup-1788930355751 Automation location group 1788930355751  " [ref=e101]:
                  - cell "" [ref=e102]:
                    - generic "Drag and Drop" [ref=e103]: 
                  - cell "AutoLocationGroup-1788930355751" [ref=e104]
                  - cell "Automation location group 1788930355751" [ref=e105]
                  - cell " " [ref=e106]:
                    - generic "Edit" [ref=e107] [cursor=pointer]: 
                    - generic "Delete" [ref=e108] [cursor=pointer]: 
                - row " AutoLocationGroup-1789016932445 Automation location group 1789016932445  " [ref=e109]:
                  - cell "" [ref=e110]:
                    - generic "Drag and Drop" [ref=e111]: 
                  - cell "AutoLocationGroup-1789016932445" [ref=e112]
                  - cell "Automation location group 1789016932445" [ref=e113]
                  - cell " " [ref=e114]:
                    - generic "Edit" [ref=e115] [cursor=pointer]: 
                    - generic "Delete" [ref=e116] [cursor=pointer]: 
                - row " AutoLocationGroup-1789016946375 Automation location group 1789016946375  " [ref=e117]:
                  - cell "" [ref=e118]:
                    - generic "Drag and Drop" [ref=e119]: 
                  - cell "AutoLocationGroup-1789016946375" [ref=e120]
                  - cell "Automation location group 1789016946375" [ref=e121]
                  - cell " " [ref=e122]:
                    - generic "Edit" [ref=e123] [cursor=pointer]: 
                    - generic "Delete" [ref=e124] [cursor=pointer]: 
                - row " AutoLocationGroup-1789103267900 Automation location group 1789103267900  " [ref=e125]:
                  - cell "" [ref=e126]:
                    - generic "Drag and Drop" [ref=e127]: 
                  - cell "AutoLocationGroup-1789103267900" [ref=e128]
                  - cell "Automation location group 1789103267900" [ref=e129]
                  - cell " " [ref=e130]:
                    - generic "Edit" [ref=e131] [cursor=pointer]: 
                    - generic "Delete" [ref=e132] [cursor=pointer]: 
                - row " AutoLocationGroup-1789188986595 Automation location group 1789188986595  " [ref=e133]:
                  - cell "" [ref=e134]:
                    - generic "Drag and Drop" [ref=e135]: 
                  - cell "AutoLocationGroup-1789188986595" [ref=e136]
                  - cell "Automation location group 1789188986595" [ref=e137]
                  - cell " " [ref=e138]:
                    - generic "Edit" [ref=e139] [cursor=pointer]: 
                    - generic "Delete" [ref=e140] [cursor=pointer]: 
                - row " AutoLocationGroup-1789276803939 Automation location group 1789276803939  " [ref=e141]:
                  - cell "" [ref=e142]:
                    - generic "Drag and Drop" [ref=e143]: 
                  - cell "AutoLocationGroup-1789276803939" [ref=e144]
                  - cell "Automation location group 1789276803939" [ref=e145]
                  - cell " " [ref=e146]:
                    - generic "Edit" [ref=e147] [cursor=pointer]: 
                    - generic "Delete" [ref=e148] [cursor=pointer]: 
                - row " AutoLocationGroup-1789363531658 Automation location group 1789363531658  " [ref=e149]:
                  - cell "" [ref=e150]:
                    - generic "Drag and Drop" [ref=e151]: 
                  - cell "AutoLocationGroup-1789363531658" [ref=e152]
                  - cell "Automation location group 1789363531658" [ref=e153]
                  - cell " " [ref=e154]:
                    - generic "Edit" [ref=e155] [cursor=pointer]: 
                    - generic "Delete" [ref=e156] [cursor=pointer]: 
                - row " AutoLocationGroup-1789449519826 Automation location group 1789449519826  " [ref=e157]:
                  - cell "" [ref=e158]:
                    - generic "Drag and Drop" [ref=e159]: 
                  - cell "AutoLocationGroup-1789449519826" [ref=e160]
                  - cell "Automation location group 1789449519826" [ref=e161]
                  - cell " " [ref=e162]:
                    - generic "Edit" [ref=e163] [cursor=pointer]: 
                    - generic "Delete" [ref=e164] [cursor=pointer]: 
                - row " AutoLocationGroup-1789535594121 Automation location group 1789535594121  " [ref=e165]:
                  - cell "" [ref=e166]:
                    - generic "Drag and Drop" [ref=e167]: 
                  - cell "AutoLocationGroup-1789535594121" [ref=e168]
                  - cell "Automation location group 1789535594121" [ref=e169]
                  - cell " " [ref=e170]:
                    - generic "Edit" [ref=e171] [cursor=pointer]: 
                    - generic "Delete" [ref=e172] [cursor=pointer]: 
                - row " West Sussex Group Cicuta vel cena depereo vere benevolentia cruciamentum ocer.  " [ref=e173]:
                  - cell "" [ref=e174]:
                    - generic "Drag and Drop" [ref=e175]: 
                  - cell "West Sussex Group" [ref=e176]
                  - cell "Cicuta vel cena depereo vere benevolentia cruciamentum ocer." [ref=e177]
                  - cell " " [ref=e178]:
                    - generic "Edit" [ref=e179] [cursor=pointer]: 
                    - generic "Delete" [ref=e180] [cursor=pointer]: 
                - row " West Yorkshire Team Vorago amaritudo bellicus.  " [ref=e181]:
                  - cell "" [ref=e182]:
                    - generic "Drag and Drop" [ref=e183]: 
                  - cell "West Yorkshire Team" [ref=e184]
                  - cell "Vorago amaritudo bellicus." [ref=e185]
                  - cell " " [ref=e186]:
                    - generic "Edit" [ref=e187] [cursor=pointer]: 
                    - generic "Delete" [ref=e188] [cursor=pointer]: 
                - row " Grant County Group Caecus conculco voluptates callide cetera avaritia.  " [ref=e189]:
                  - cell "" [ref=e190]:
                    - generic "Drag and Drop" [ref=e191]: 
                  - cell "Grant County Group" [ref=e192]
                  - cell "Caecus conculco voluptates callide cetera avaritia." [ref=e193]
                  - cell " " [ref=e194]:
                    - generic "Edit" [ref=e195] [cursor=pointer]: 
                    - generic "Delete" [ref=e196] [cursor=pointer]: 
                - row " Jefferson County Group Dolorum subvenio apud tripudio defetiscor tabula ascit credo animadverto.  " [ref=e197]:
                  - cell "" [ref=e198]:
                    - generic "Drag and Drop" [ref=e199]: 
                  - cell "Jefferson County Group" [ref=e200]
                  - cell "Dolorum subvenio apud tripudio defetiscor tabula ascit credo animadverto." [ref=e201]
                  - cell " " [ref=e202]:
                    - generic "Edit" [ref=e203] [cursor=pointer]: 
                    - generic "Delete" [ref=e204] [cursor=pointer]: 
                - row " County Fermanagh Group Deduco maxime appono studio adflicto.  " [ref=e205]:
                  - cell "" [ref=e206]:
                    - generic "Drag and Drop" [ref=e207]: 
                  - cell "County Fermanagh Group" [ref=e208]
                  - cell "Deduco maxime appono studio adflicto." [ref=e209]
                  - cell " " [ref=e210]:
                    - generic "Edit" [ref=e211] [cursor=pointer]: 
                    - generic "Delete" [ref=e212] [cursor=pointer]: 
                - row " Strathclyde Team Sed sollers amaritudo defero.  " [ref=e213]:
                  - cell "" [ref=e214]:
                    - generic "Drag and Drop" [ref=e215]: 
                  - cell "Strathclyde Team" [ref=e216]
                  - cell "Sed sollers amaritudo defero." [ref=e217]
                  - cell " " [ref=e218]:
                    - generic "Edit" [ref=e219] [cursor=pointer]: 
                    - generic "Delete" [ref=e220] [cursor=pointer]: 
                - row " Nottinghamshire Team Cupiditas quos tredecim cicuta.  " [ref=e221]:
                  - cell "" [ref=e222]:
                    - generic "Drag and Drop" [ref=e223]: 
                  - cell "Nottinghamshire Team" [ref=e224]
                  - cell "Cupiditas quos tredecim cicuta." [ref=e225]
                  - cell " " [ref=e226]:
                    - generic "Edit" [ref=e227] [cursor=pointer]: 
                    - generic "Delete" [ref=e228] [cursor=pointer]: 
                - row " Lincolnshire Team Tergum adnuo apud solitudo uxor amplexus conatus.  " [ref=e229]:
                  - cell "" [ref=e230]:
                    - generic "Drag and Drop" [ref=e231]: 
                  - cell "Lincolnshire Team" [ref=e232]
                  - cell "Tergum adnuo apud solitudo uxor amplexus conatus." [ref=e233]
                  - cell " " [ref=e234]:
                    - generic "Edit" [ref=e235] [cursor=pointer]: 
                    - generic "Delete" [ref=e236] [cursor=pointer]: 
                - row " Logan County Team Virgo temporibus carpo maxime quos tardus ex ad vaco.  " [ref=e237]:
                  - cell "" [ref=e238]:
                    - generic "Drag and Drop" [ref=e239]: 
                  - cell "Logan County Team" [ref=e240]
                  - cell "Virgo temporibus carpo maxime quos tardus ex ad vaco." [ref=e241]
                  - cell " " [ref=e242]:
                    - generic "Edit" [ref=e243] [cursor=pointer]: 
                    - generic "Delete" [ref=e244] [cursor=pointer]: 
            - generic [ref=e245]:
              - generic [ref=e246]:
                - generic:
                  - list:
                    - listitem [ref=e247]:
                      - link "1" [ref=e248] [cursor=pointer]:
                        - /url: "#"
                    - listitem [ref=e249]:
                      - link "2" [ref=e250] [cursor=pointer]:
                        - /url: "#"
                    - listitem [ref=e251]:
                      - link "→" [ref=e252] [cursor=pointer]:
                        - /url: "#"
              - list [ref=e253]:
                - listitem [ref=e254]:
                  - generic [ref=e255]: "20"
                - listitem [ref=e256]:
                  - link "50" [ref=e257] [cursor=pointer]:
                    - /url: "#"
                - listitem [ref=e258]:
                  - link "100" [ref=e259] [cursor=pointer]:
                    - /url: "#"
                - listitem [ref=e260]:
                  - link "All" [ref=e261] [cursor=pointer]:
                    - /url: "#"
      - contentinfo [ref=e262]:
        - text: © 2017-2026 First Due. Powered by
        - link "LocalityMedia, Inc" [ref=e263] [cursor=pointer]:
          - /url: https://www.firstdue.com/
        - text: .
    - text: 
  - generic [ref=e265] [cursor=pointer]: 
  - generic:
    - button "Chat Close Maven Chat" [ref=e266] [cursor=pointer]:
      - img "Chat" [ref=e268]
      - button "Close Maven Chat"
    - iframe
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