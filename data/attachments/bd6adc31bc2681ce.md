# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: credentials/C22181794-verify-imported-global-credential-does-not-require-state-province-at-agency-level.spec.ts >> Credentials >> @regression C22181794: Verify imported Global Credential does not require State / Province at agency level
- Location: src/tests/credentials/C22181794-verify-imported-global-credential-does-not-require-state-province-at-agency-level.spec.ts:24:7

# Error details

```
TimeoutError: locator.waitFor: Timeout 60000ms exceeded.
Call log:
  - waiting for locator('[data-testid="global-credential-form-save"]') to be hidden
    2 × locator resolved to visible <button title="Save" type="button" data-v-3546feee="" data-v-04e629ba="" disabled="disabled" class="button is-large is-primary" data-testid="global-credential-form-save">…</button>
    120 × locator resolved to visible <button title="Save" type="button" data-v-3546feee="" data-v-04e629ba="" class="button is-large is-primary" data-testid="global-credential-form-save">…</button>

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - link:
    - /url: "#main-content"
    - text: Skip to main content
  - banner [ref=e2]:
    - region [ref=e4]:
      - generic [ref=e5]:
        - generic [ref=e6]:
          - img [ref=e7]
          - heading [level=2] [ref=e8]: Super Admin
        - button [ref=e12] [cursor=pointer]
  - navigation [ref=e15]:
    - link [ref=e16] [cursor=pointer]:
      - /url: "#main-content"
      - text: Skip to main content
  - main [ref=e17]:
    - generic [ref=e20]:
      - generic [ref=e21]:
        - link [ref=e22] [cursor=pointer]:
          - /url: "#"
          - img [ref=e23]
          - generic [ref=e27]: "24"
        - generic [ref=e29]: Global Credentials
        - generic [ref=e31]:
          - button [ref=e32] [cursor=pointer]: Import Global Credentials
          - button [ref=e34] [cursor=pointer]: Add Global Credential
          - button [ref=e39] [cursor=pointer]
      - region [ref=e41]:
        - generic [ref=e44]:
          - search [ref=e47]:
            - generic [ref=e48]:
              - button [ref=e51] [cursor=pointer]:
                - generic [ref=e52]: Saved Views
              - button [ref=e57] [cursor=pointer]
            - generic [ref=e59]:
              - button [ref=e60] [cursor=pointer]: Filter
              - button [ref=e64] [cursor=pointer]: Columns
            - button [ref=e67] [cursor=pointer]
          - treegrid [ref=e72]:
            - rowgroup [ref=e73]:
              - row [ref=e74]:
                - columnheader [ref=e75]:
                  - checkbox [ref=e77] [cursor=pointer]
                  - generic [ref=e78]: Select
            - rowgroup [ref=e79]:
              - row [ref=e80]:
                - columnheader [ref=e81]:
                  - generic [ref=e83] [cursor=pointer]: ID
                - columnheader [ref=e84]:
                  - generic [ref=e86] [cursor=pointer]: Name
                - columnheader [ref=e87]:
                  - generic [ref=e89] [cursor=pointer]: Credential Type
                - columnheader [ref=e90]:
                  - generic [ref=e92] [cursor=pointer]: State / Province
                - columnheader [ref=e93]:
                  - generic [ref=e95] [cursor=pointer]: Issuing Authority
                - columnheader [ref=e96]:
                  - generic [ref=e98] [cursor=pointer]: Status
                - columnheader [ref=e99]:
                  - generic [ref=e101]: Credential Cycle
                - columnheader [ref=e102]:
                  - generic [ref=e104] [cursor=pointer]: Renewal Criteria
            - rowgroup [ref=e105]:
              - row [ref=e106]:
                - columnheader [ref=e107]:
                  - button [ref=e108] [cursor=pointer]
                  - generic [ref=e110]: Actions
            - rowgroup [ref=e111]:
              - row [ref=e112]:
                - gridcell [ref=e113]:
                  - checkbox [ref=e114] [cursor=pointer]
              - row [ref=e115]:
                - gridcell [ref=e116]:
                  - checkbox [ref=e117] [cursor=pointer]
              - row [ref=e118]:
                - gridcell [ref=e119]:
                  - checkbox [ref=e120] [cursor=pointer]
              - row [ref=e121]:
                - gridcell [ref=e122]:
                  - checkbox [ref=e123] [cursor=pointer]
              - row [ref=e124]:
                - gridcell [ref=e125]:
                  - checkbox [ref=e126] [cursor=pointer]
              - row [ref=e127]:
                - gridcell [ref=e128]:
                  - checkbox [ref=e129] [cursor=pointer]
              - row [ref=e130]:
                - gridcell [ref=e131]:
                  - checkbox [ref=e132] [cursor=pointer]
              - row [ref=e133]:
                - gridcell [ref=e134]:
                  - checkbox [ref=e135] [cursor=pointer]
              - row [ref=e136]:
                - gridcell [ref=e137]:
                  - checkbox [ref=e138] [cursor=pointer]
              - row [ref=e139]:
                - gridcell [ref=e140]:
                  - checkbox [ref=e141] [cursor=pointer]
            - rowgroup [ref=e142]:
              - row [ref=e143]:
                - gridcell [ref=e144]: FIR356
                - gridcell [ref=e145]: web services License
                - gridcell [ref=e146]: Fire (FIR)
                - gridcell [ref=e147]: National
                - gridcell [ref=e148]: Academic Fire Authority
                - gridcell [ref=e149]: Active
                - gridcell [ref=e150]: 1 Year(s)
                - gridcell [ref=e151]: Do not automatically renew / expire
              - row [ref=e152]:
                - gridcell [ref=e153]: AG7EMS033
                - gridcell [ref=e154]: AG7 Cred 033
                - gridcell [ref=e155]: EMS (EMS)
                - gridcell [ref=e156]: Virginia
                - gridcell [ref=e157]: "-"
                - gridcell [ref=e158]: Active
                - gridcell [ref=e159]: 2 Year(s)
                - gridcell [ref=e160]: Date all completion requirements met
              - row [ref=e161]:
                - gridcell [ref=e162]: AG7EMS001
                - gridcell [ref=e163]: AG7 Cred 001
                - gridcell [ref=e164]: EMS (EMS)
                - gridcell [ref=e165]: Virginia
                - gridcell [ref=e166]: "-"
                - gridcell [ref=e167]: Active
                - gridcell [ref=e168]: 2 Year(s)
                - gridcell [ref=e169]: Date all completion requirements met
              - row [ref=e170]:
                - gridcell [ref=e171]: AG7EMS002
                - gridcell [ref=e172]: AG7 Cred 002
                - gridcell [ref=e173]: EMS (EMS)
                - gridcell [ref=e174]: Virginia
                - gridcell [ref=e175]: "-"
                - gridcell [ref=e176]: Active
                - gridcell [ref=e177]: 2 Year(s)
                - gridcell [ref=e178]: Date all completion requirements met
              - row [ref=e179]:
                - gridcell [ref=e180]: AG7EMS003
                - gridcell [ref=e181]: AG7 Cred 003
                - gridcell [ref=e182]: EMS (EMS)
                - gridcell [ref=e183]: Virginia
                - gridcell [ref=e184]: "-"
                - gridcell [ref=e185]: Active
                - gridcell [ref=e186]: 2 Year(s)
                - gridcell [ref=e187]: Date all completion requirements met
              - row [ref=e188]:
                - gridcell [ref=e189]: AG7EMS004
                - gridcell [ref=e190]: AG7 Cred 004
                - gridcell [ref=e191]: EMS (EMS)
                - gridcell [ref=e192]: Virginia
                - gridcell [ref=e193]: "-"
                - gridcell [ref=e194]: Active
                - gridcell [ref=e195]: 2 Year(s)
                - gridcell [ref=e196]: Date all completion requirements met
              - row [ref=e197]:
                - gridcell [ref=e198]: AG7EMS005
                - gridcell [ref=e199]: AG7 Cred 005
                - gridcell [ref=e200]: EMS (EMS)
                - gridcell [ref=e201]: Virginia
                - gridcell [ref=e202]: "-"
                - gridcell [ref=e203]: Active
                - gridcell [ref=e204]: 2 Year(s)
                - gridcell [ref=e205]: Date all completion requirements met
              - row [ref=e206]:
                - gridcell [ref=e207]: AG7EMS006
                - gridcell [ref=e208]: AG7 Cred 006
                - gridcell [ref=e209]: EMS (EMS)
                - gridcell [ref=e210]: Virginia
                - gridcell [ref=e211]: "-"
                - gridcell [ref=e212]: Active
                - gridcell [ref=e213]: 2 Year(s)
                - gridcell [ref=e214]: Date all completion requirements met
              - row [ref=e215]:
                - gridcell [ref=e216]: AG7EMS007
                - gridcell [ref=e217]: AG7 Cred 007
                - gridcell [ref=e218]: EMS (EMS)
                - gridcell [ref=e219]: Virginia
                - gridcell [ref=e220]: "-"
                - gridcell [ref=e221]: Active
                - gridcell [ref=e222]: 2 Year(s)
                - gridcell [ref=e223]: Date all completion requirements met
              - row [ref=e224]:
                - gridcell [ref=e225]: AG7EMS008
                - gridcell [ref=e226]: AG7 Cred 008
                - gridcell [ref=e227]: EMS (EMS)
                - gridcell [ref=e228]: Virginia
                - gridcell [ref=e229]: "-"
                - gridcell [ref=e230]: Active
                - gridcell [ref=e231]: 2 Year(s)
                - gridcell [ref=e232]: Date all completion requirements met
            - rowgroup [ref=e233]:
              - row [ref=e234]:
                - gridcell [ref=e235]:
                  - generic [ref=e236]:
                    - button [ref=e237] [cursor=pointer]
                    - button [ref=e239] [cursor=pointer]
                    - button [ref=e241] [cursor=pointer]
              - row [ref=e243]:
                - gridcell [ref=e244]:
                  - generic [ref=e245]:
                    - button [ref=e246] [cursor=pointer]
                    - button [ref=e248] [cursor=pointer]
                    - button [ref=e250] [cursor=pointer]
              - row [ref=e252]:
                - gridcell [ref=e253]:
                  - generic [ref=e254]:
                    - button [ref=e255] [cursor=pointer]
                    - button [ref=e257] [cursor=pointer]
                    - button [ref=e259] [cursor=pointer]
              - row [ref=e261]:
                - gridcell [ref=e262]:
                  - generic [ref=e263]:
                    - button [ref=e264] [cursor=pointer]
                    - button [ref=e266] [cursor=pointer]
                    - button [ref=e268] [cursor=pointer]
              - row [ref=e270]:
                - gridcell [ref=e271]:
                  - generic [ref=e272]:
                    - button [ref=e273] [cursor=pointer]
                    - button [ref=e275] [cursor=pointer]
                    - button [ref=e277] [cursor=pointer]
              - row [ref=e279]:
                - gridcell [ref=e280]:
                  - generic [ref=e281]:
                    - button [ref=e282] [cursor=pointer]
                    - button [ref=e284] [cursor=pointer]
                    - button [ref=e286] [cursor=pointer]
              - row [ref=e288]:
                - gridcell [ref=e289]:
                  - generic [ref=e290]:
                    - button [ref=e291] [cursor=pointer]
                    - button [ref=e293] [cursor=pointer]
                    - button [ref=e295] [cursor=pointer]
              - row [ref=e297]:
                - gridcell [ref=e298]:
                  - generic [ref=e299]:
                    - button [ref=e300] [cursor=pointer]
                    - button [ref=e302] [cursor=pointer]
                    - button [ref=e304] [cursor=pointer]
              - row [ref=e306]:
                - gridcell [ref=e307]:
                  - generic [ref=e308]:
                    - button [ref=e309] [cursor=pointer]
                    - button [ref=e311] [cursor=pointer]
                    - button [ref=e313] [cursor=pointer]
              - row [ref=e315]:
                - gridcell [ref=e316]:
                  - generic [ref=e317]:
                    - button [ref=e318] [cursor=pointer]
                    - button [ref=e320] [cursor=pointer]
                    - button [ref=e322] [cursor=pointer]
            - rowgroup
          - generic [ref=e333]:
            - generic [ref=e334]: Showing 1 to 20 of 696 records
            - generic [ref=e335]: Page 1 of 35
            - button [ref=e338] [cursor=pointer]: "Page size: 20"
            - button [ref=e340] [cursor=pointer]
            - generic [ref=e342]:
              - button [disabled] [ref=e343]: Previous
              - button [ref=e345] [cursor=pointer]: Next
  - contentinfo [ref=e347]: © 2026 First Due
  - button [ref=e348] [cursor=pointer]
  - dialog "New Credential" [ref=e350]:
    - generic [ref=e352]:
      - generic [ref=e354]:
        - heading "New Credential" [level=2] [ref=e358]
        - button "Close" [ref=e359] [cursor=pointer]
      - generic [ref=e362]:
        - generic [ref=e365]:
          - generic [ref=e366]:
            - generic "Credential Name" [ref=e367]
            - generic [ref=e368]: "*"
          - textbox "Credential Name" [ref=e372]: experiences Certification
          - generic [ref=e376]: "Character limit: 25/100"
        - generic [ref=e379]:
          - generic [ref=e380]:
            - generic "Credential Type" [ref=e381]
            - generic [ref=e382]: "*"
          - generic "Open dropdown" [ref=e384]:
            - button "Fire (FIR)" [ref=e388]:
              - generic [ref=e389]: Fire (FIR)
        - generic [ref=e393]:
          - generic [ref=e394]:
            - generic "Credential ID" [ref=e395]
            - generic [ref=e396]: "*"
            - link "Manual entry" [ref=e398] [cursor=pointer]:
              - /url: "#"
          - textbox "Credential ID" [disabled] [ref=e402]: FIR373
        - generic [ref=e405]:
          - generic [ref=e406]:
            - generic "State / Province" [ref=e407]
            - generic [ref=e408]: "*"
          - generic "Open dropdown" [ref=e410]:
            - button "National" [ref=e414]:
              - generic [ref=e415]: National
        - generic [ref=e419]:
          - generic "Issue Authority" [ref=e421]
          - generic "Open dropdown" [ref=e423]:
            - button "Academic Fire Authority" [ref=e427]:
              - generic [ref=e428]: Academic Fire Authority
        - generic [ref=e434]:
          - generic [ref=e435]: Allow user submissions
          - checkbox "Allow user submissions" [ref=e438]
        - generic [ref=e441]:
          - generic [ref=e442]: Description
          - generic [ref=e444]:
            - generic [ref=e445]:
              - generic [ref=e446]:
                - button "Bold" [ref=e447] [cursor=pointer]
                - button "Italic" [ref=e449] [cursor=pointer]
                - button "Heading 2" [ref=e451] [cursor=pointer]
                - button "Heading 3" [ref=e453] [cursor=pointer]
              - generic [ref=e455]:
                - button "Quote" [ref=e456] [cursor=pointer]
                - button "Unordered List" [ref=e458] [cursor=pointer]
                - button "Ordered List" [ref=e460] [cursor=pointer]
              - button "Link" [ref=e463] [cursor=pointer]
              - generic [ref=e465]:
                - button "Preview" [ref=e466] [cursor=pointer]
                - button "Side by Side" [ref=e468] [cursor=pointer]
                - button "Fullscreen" [ref=e470] [cursor=pointer]
            - application [ref=e472]:
              - text:    2  3       
              - generic [ref=e473]:
                - textbox "Description" [ref=e474]
                - generic [ref=e477]:
                  - generic: Description
        - generic [ref=e481]:
          - generic "Credential Cycle" [ref=e483]
          - spinbutton "Credential Cycle" [ref=e487]: "1"
          - generic [ref=e491]: Optional. Leave blank if the credential does not expire.
        - generic [ref=e494]:
          - generic "Cycle period" [ref=e496]
          - generic "Open dropdown" [ref=e498]:
            - button "Years" [ref=e502]:
              - generic [ref=e503]: Years
        - generic [ref=e507]:
          - generic "Linked Training Plan" [ref=e509]
          - generic "Open dropdown" [ref=e511]:
            - button "Open dropdown" [ref=e515]
          - generic [ref=e521]: Optional. Link a global template training plan used when agencies import this credential.
        - generic [ref=e525]:
          - generic [ref=e527]:
            - heading "Prerequisite needed" [level=2] [ref=e529]
            - generic [ref=e530]: Enable if this credential requires other credentials to be completed first
          - checkbox "Toggle" [ref=e534]
        - generic [ref=e541]:
          - generic [ref=e543]:
            - heading "Grace Period" [level=2] [ref=e545]
            - generic [ref=e546]: Grace period for this credential
          - checkbox "Toggle" [ref=e550]
        - generic [ref=e555]:
          - generic [ref=e559]:
            - heading "Renewal Criteria" [level=2] [ref=e561]
            - generic [ref=e562]: Select a renewal criteria
          - generic [ref=e567]:
            - option "Date all completion requirements met Automatically will renew the credential when the user reaches 100% prior to the expiration date" [ref=e569] [cursor=pointer]:
              - generic [ref=e575]:
                - generic "Date all completion requirements met" [ref=e576]
                - generic "Automatically will renew the credential when the user reaches 100% prior to the expiration date" [ref=e577]
            - option "Date of expiration Automatically will renew the credential on the expiration date, regardless of completion progress" [ref=e579] [cursor=pointer]:
              - generic [ref=e585]:
                - generic "Date of expiration" [ref=e586]
                - generic "Automatically will renew the credential on the expiration date, regardless of completion progress" [ref=e587]
            - option "Date of expiration with completion Automatically will renew the credential at date of expiration when user reaches 100%" [ref=e589] [cursor=pointer]:
              - generic [ref=e595]:
                - generic "Date of expiration with completion" [ref=e596]
                - generic "Automatically will renew the credential at date of expiration when user reaches 100%" [ref=e597]
            - option "Do not automatically renew / expire For lifetime credentials or credentials tracked outside First Due. First Due will not automatically renew or expire them." [selected] [ref=e599] [cursor=pointer]:
              - generic [ref=e605]:
                - generic "Do not automatically renew / expire" [ref=e606]
                - generic "For lifetime credentials or credentials tracked outside First Due. First Due will not automatically renew or expire them." [ref=e607]
      - generic [ref=e609]:
        - button "Cancel" [ref=e610] [cursor=pointer]
        - button "Save" [ref=e611] [cursor=pointer]: Save
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