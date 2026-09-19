# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: training-setup/categories/C22680549-verify-import-categories-rejects-non-csv-and-oversized-files.spec.ts >> Training setup categories >> @regression C22680549: Verify Import Categories rejects non-CSV and oversized files
- Location: src/tests/training-setup/categories/C22680549-verify-import-categories-rejects-non-csv-and-oversized-files.spec.ts:39:7

# Error details

```
Error: expect(received).toBe(expected) // Object.is equality

Expected: "duplicates"
Received: "success"
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
          - button "Collapse section menu" [ref=e15] [cursor=pointer]
          - generic [ref=e17]: Training Setup
        - generic [ref=e20]:
          - complementary [ref=e21]:
            - menu [ref=e25]:
              - menuitem "Settings" [ref=e26]:
                - generic [ref=e31]: Settings
              - menuitem "Notifications" [ref=e32]:
                - generic [ref=e37]: Notifications
              - menuitem "Categories" [ref=e38]:
                - generic [ref=e43]: Categories
              - menuitem "Topics" [ref=e44]:
                - generic [ref=e49]: Topics
              - menuitem "List Configuration" [ref=e50]:
                - generic [ref=e55]: List Configuration
              - menuitem "Standards" [ref=e56]:
                - generic [ref=e61]: Standards
              - menuitem "Field Management" [ref=e62]:
                - generic [ref=e67]: Field Management
              - menuitem "Training Import" [ref=e68]:
                - generic [ref=e73]: Training Import
              - menuitem "Instructor Management" [ref=e74]:
                - generic [ref=e79]: Instructor Management
              - menuitem "Import CTC" [ref=e80]:
                - generic [ref=e85]: Import CTC
          - generic [ref=e89]:
            - generic [ref=e91]:
              - generic [ref=e95]: Categories
              - button "Import Categories" [ref=e96] [cursor=pointer]: Import Categories
              - button "Add Category" [ref=e98] [cursor=pointer]: Add Category
            - generic [ref=e102]:
              - search [ref=e105]:
                - generic [ref=e106]:
                  - button "Filter" [ref=e107] [cursor=pointer]: Filter
                  - generic "More options" [ref=e110]:
                    - button "Columns" [ref=e111] [cursor=pointer]: Columns
                - search [ref=e113]:
                  - button "Expand search input" [ref=e114] [cursor=pointer]
              - treegrid [ref=e119]:
                - rowgroup [ref=e120]:
                  - row [ref=e121]:
                    - columnheader [ref=e122]:
                      - checkbox [ref=e124] [cursor=pointer]
                - rowgroup [ref=e125]:
                  - row "Name Created At Created By Associated Topics Associated Courses Show tooltip" [ref=e126]:
                    - columnheader "Name" [ref=e127]:
                      - generic [ref=e129] [cursor=pointer]: Name
                    - columnheader "Created At" [ref=e130]:
                      - generic [ref=e132] [cursor=pointer]: Created At
                    - columnheader "Created By" [ref=e133]:
                      - generic [ref=e135] [cursor=pointer]: Created By
                    - columnheader "Associated Topics" [ref=e136]:
                      - generic [ref=e138]: Associated Topics
                    - columnheader "Associated Courses Show tooltip" [ref=e139]:
                      - generic [ref=e141]:
                        - columnheader "Associated Courses" [ref=e142]
                        - button "Show tooltip" [ref=e144]
                - rowgroup [ref=e146]:
                  - row "Actions" [ref=e147]:
                    - columnheader "Actions" [ref=e148]:
                      - columnheader "Actions" [ref=e149]
                      - button [ref=e150] [cursor=pointer]
                - generic "Grid body" [ref=e152]:
                  - rowgroup [ref=e153]:
                    - row "Press Space to toggle row selection (unchecked)" [ref=e154]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e155]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e156] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e157]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e158]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e159] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e160]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e161]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e162] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e163]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e164]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e165] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e166]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e167]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e168] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e169]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e170]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e171] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e172]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e173]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e174] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e175]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e176]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e177] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e178]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e179]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e180] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e181]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e182]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e183] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e184]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e185]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e186] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e187]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e188]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e189] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e190]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e191]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e192] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e193]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e194]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e195] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e196]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e197]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e198] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e199]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e200]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e201] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e202]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e203]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e204] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e205]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e206]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e207] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e208]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e209]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e210] [cursor=pointer]
                    - row "Press Space to toggle row selection (unchecked)" [ref=e211]:
                      - gridcell "Press Space to toggle row selection (unchecked)" [ref=e212]:
                        - checkbox "Press Space to toggle row selection (unchecked)" [ref=e213] [cursor=pointer]
                  - generic "Grid columns" [ref=e214]:
                    - rowgroup [ref=e215]:
                      - row "A1 - Copy 09/04/2026 A1" [ref=e216]:
                        - gridcell "A1 - Copy" [ref=e217]
                        - gridcell "09/04/2026" [ref=e218]
                        - gridcell [ref=e219]
                        - gridcell [ref=e220]
                        - gridcell "A1" [ref=e221]
                      - row "AutoCat-1788514314138 09/04/2026 Mark Bark C" [ref=e222]:
                        - gridcell "AutoCat-1788514314138" [ref=e223]
                        - gridcell "09/04/2026" [ref=e224]
                        - gridcell "Mark Bark" [ref=e225]
                        - gridcell [ref=e226]
                        - gridcell "C" [ref=e227]
                      - row "AutoCat-1788514449796 09/04/2026 Mark Bark TOP ALL" [ref=e228]:
                        - gridcell "AutoCat-1788514449796" [ref=e229]
                        - gridcell "09/04/2026" [ref=e230]
                        - gridcell "Mark Bark" [ref=e231]
                        - gridcell "TOP" [ref=e232]
                        - gridcell "ALL" [ref=e233]
                      - row "AutoCat-1788587265808 09/05/2026 Mark Bark" [ref=e234]:
                        - gridcell "AutoCat-1788587265808" [ref=e235]
                        - gridcell "09/05/2026" [ref=e236]
                        - gridcell "Mark Bark" [ref=e237]
                        - gridcell [ref=e238]
                        - gridcell [ref=e239]
                      - row "AutoCat-1788587275816 09/05/2026 Mark Bark" [ref=e240]:
                        - gridcell "AutoCat-1788587275816" [ref=e241]
                        - gridcell "09/05/2026" [ref=e242]
                        - gridcell "Mark Bark" [ref=e243]
                        - gridcell [ref=e244]
                        - gridcell [ref=e245]
                      - row "AutoCat-1788674128507 09/06/2026 Mark Bark" [ref=e246]:
                        - gridcell "AutoCat-1788674128507" [ref=e247]
                        - gridcell "09/06/2026" [ref=e248]
                        - gridcell "Mark Bark" [ref=e249]
                        - gridcell [ref=e250]
                        - gridcell [ref=e251]
                      - row "AutoCat-1788674138858 09/06/2026 Mark Bark" [ref=e252]:
                        - gridcell "AutoCat-1788674138858" [ref=e253]
                        - gridcell "09/06/2026" [ref=e254]
                        - gridcell "Mark Bark" [ref=e255]
                        - gridcell [ref=e256]
                        - gridcell [ref=e257]
                      - row "AutoCat-1788760906980 09/07/2026 Mark Bark" [ref=e258]:
                        - gridcell "AutoCat-1788760906980" [ref=e259]
                        - gridcell "09/07/2026" [ref=e260]
                        - gridcell "Mark Bark" [ref=e261]
                        - gridcell [ref=e262]
                        - gridcell [ref=e263]
                      - row "AutoCat-1788760931336 09/07/2026 Mark Bark" [ref=e264]:
                        - gridcell "AutoCat-1788760931336" [ref=e265]
                        - gridcell "09/07/2026" [ref=e266]
                        - gridcell "Mark Bark" [ref=e267]
                        - gridcell [ref=e268]
                        - gridcell [ref=e269]
                      - row "AutoCat-1788792733626 09/07/2026 Mark Bark" [ref=e270]:
                        - gridcell "AutoCat-1788792733626" [ref=e271]
                        - gridcell "09/07/2026" [ref=e272]
                        - gridcell "Mark Bark" [ref=e273]
                        - gridcell [ref=e274]
                        - gridcell [ref=e275]
                      - row "AutoCat-1788792739650 09/07/2026 Mark Bark" [ref=e276]:
                        - gridcell "AutoCat-1788792739650" [ref=e277]
                        - gridcell "09/07/2026" [ref=e278]
                        - gridcell "Mark Bark" [ref=e279]
                        - gridcell [ref=e280]
                        - gridcell [ref=e281]
                      - row "AutoCat-1788846164382 09/08/2026 Mark Bark" [ref=e282]:
                        - gridcell "AutoCat-1788846164382" [ref=e283]
                        - gridcell "09/08/2026" [ref=e284]
                        - gridcell "Mark Bark" [ref=e285]
                        - gridcell [ref=e286]
                        - gridcell [ref=e287]
                      - row "AutoCat-1788846177826 09/08/2026 Mark Bark" [ref=e288]:
                        - gridcell "AutoCat-1788846177826" [ref=e289]
                        - gridcell "09/08/2026" [ref=e290]
                        - gridcell "Mark Bark" [ref=e291]
                        - gridcell [ref=e292]
                        - gridcell [ref=e293]
                      - row "AutoCat-1788932459196 09/09/2026 Mark Bark" [ref=e294]:
                        - gridcell "AutoCat-1788932459196" [ref=e295]
                        - gridcell "09/09/2026" [ref=e296]
                        - gridcell "Mark Bark" [ref=e297]
                        - gridcell [ref=e298]
                        - gridcell [ref=e299]
                      - row "AutoCat-1788932469255 09/09/2026 Mark Bark" [ref=e300]:
                        - gridcell "AutoCat-1788932469255" [ref=e301]
                        - gridcell "09/09/2026" [ref=e302]
                        - gridcell "Mark Bark" [ref=e303]
                        - gridcell [ref=e304]
                        - gridcell [ref=e305]
                      - row "AutoCat-1789019017402 09/10/2026 Mark Bark" [ref=e306]:
                        - gridcell "AutoCat-1789019017402" [ref=e307]
                        - gridcell "09/10/2026" [ref=e308]
                        - gridcell "Mark Bark" [ref=e309]
                        - gridcell [ref=e310]
                        - gridcell [ref=e311]
                      - row "AutoCat-1789019028040 09/10/2026 Mark Bark" [ref=e312]:
                        - gridcell "AutoCat-1789019028040" [ref=e313]
                        - gridcell "09/10/2026" [ref=e314]
                        - gridcell "Mark Bark" [ref=e315]
                        - gridcell [ref=e316]
                        - gridcell [ref=e317]
                      - row "AutoCat-1789105649135 09/11/2026 Mark Bark" [ref=e318]:
                        - gridcell "AutoCat-1789105649135" [ref=e319]
                        - gridcell "09/11/2026" [ref=e320]
                        - gridcell "Mark Bark" [ref=e321]
                        - gridcell [ref=e322]
                        - gridcell [ref=e323]
                      - row "AutoCat-1789105654247 09/11/2026 Mark Bark" [ref=e324]:
                        - gridcell "AutoCat-1789105654247" [ref=e325]
                        - gridcell "09/11/2026" [ref=e326]
                        - gridcell "Mark Bark" [ref=e327]
                        - gridcell [ref=e328]
                        - gridcell [ref=e329]
                      - row "AutoCat-1789191212283 09/12/2026 Mark Bark" [ref=e330]:
                        - gridcell "AutoCat-1789191212283" [ref=e331]
                        - gridcell "09/12/2026" [ref=e332]
                        - gridcell "Mark Bark" [ref=e333]
                        - gridcell [ref=e334]
                        - gridcell [ref=e335]
                  - rowgroup [ref=e336]:
                    - row [ref=e337]:
                      - gridcell [ref=e338]:
                        - generic [ref=e339]:
                          - button "Edit" [ref=e340] [cursor=pointer]
                          - button "Deactivate" [ref=e342] [cursor=pointer]
                          - button "Delete" [ref=e344] [cursor=pointer]
                    - row [ref=e346]:
                      - gridcell [ref=e347]:
                        - generic [ref=e348]:
                          - button "Edit" [ref=e349] [cursor=pointer]
                          - button "Activate" [ref=e351] [cursor=pointer]
                          - button "Delete" [ref=e353] [cursor=pointer]
                    - row [ref=e355]:
                      - gridcell [ref=e356]:
                        - generic [ref=e357]:
                          - button "Edit" [ref=e358] [cursor=pointer]
                          - button "Deactivate" [ref=e360] [cursor=pointer]
                          - button "Delete" [ref=e362] [cursor=pointer]
                    - row [ref=e364]:
                      - gridcell [ref=e365]:
                        - generic [ref=e366]:
                          - button "Edit" [ref=e367] [cursor=pointer]
                          - button "Deactivate" [ref=e369] [cursor=pointer]
                          - button "Delete" [ref=e371] [cursor=pointer]
                    - row [ref=e373]:
                      - gridcell [ref=e374]:
                        - generic [ref=e375]:
                          - button "Edit" [ref=e376] [cursor=pointer]
                          - button "Deactivate" [ref=e378] [cursor=pointer]
                          - button "Delete" [ref=e380] [cursor=pointer]
                    - row [ref=e382]:
                      - gridcell [ref=e383]:
                        - generic [ref=e384]:
                          - button "Edit" [ref=e385] [cursor=pointer]
                          - button "Deactivate" [ref=e387] [cursor=pointer]
                          - button "Delete" [ref=e389] [cursor=pointer]
                    - row [ref=e391]:
                      - gridcell [ref=e392]:
                        - generic [ref=e393]:
                          - button "Edit" [ref=e394] [cursor=pointer]
                          - button "Deactivate" [ref=e396] [cursor=pointer]
                          - button "Delete" [ref=e398] [cursor=pointer]
                    - row [ref=e400]:
                      - gridcell [ref=e401]:
                        - generic [ref=e402]:
                          - button "Edit" [ref=e403] [cursor=pointer]
                          - button "Deactivate" [ref=e405] [cursor=pointer]
                          - button "Delete" [ref=e407] [cursor=pointer]
                    - row [ref=e409]:
                      - gridcell [ref=e410]:
                        - generic [ref=e411]:
                          - button "Edit" [ref=e412] [cursor=pointer]
                          - button "Deactivate" [ref=e414] [cursor=pointer]
                          - button "Delete" [ref=e416] [cursor=pointer]
                    - row [ref=e418]:
                      - gridcell [ref=e419]:
                        - generic [ref=e420]:
                          - button "Edit" [ref=e421] [cursor=pointer]
                          - button "Deactivate" [ref=e423] [cursor=pointer]
                          - button "Delete" [ref=e425] [cursor=pointer]
                    - row [ref=e427]:
                      - gridcell [ref=e428]:
                        - generic [ref=e429]:
                          - button "Edit" [ref=e430] [cursor=pointer]
                          - button "Deactivate" [ref=e432] [cursor=pointer]
                          - button "Delete" [ref=e434] [cursor=pointer]
                    - row [ref=e436]:
                      - gridcell [ref=e437]:
                        - generic [ref=e438]:
                          - button "Edit" [ref=e439] [cursor=pointer]
                          - button "Deactivate" [ref=e441] [cursor=pointer]
                          - button "Delete" [ref=e443] [cursor=pointer]
                    - row [ref=e445]:
                      - gridcell [ref=e446]:
                        - generic [ref=e447]:
                          - button "Edit" [ref=e448] [cursor=pointer]
                          - button "Deactivate" [ref=e450] [cursor=pointer]
                          - button "Delete" [ref=e452] [cursor=pointer]
                    - row [ref=e454]:
                      - gridcell [ref=e455]:
                        - generic [ref=e456]:
                          - button "Edit" [ref=e457] [cursor=pointer]
                          - button "Deactivate" [ref=e459] [cursor=pointer]
                          - button "Delete" [ref=e461] [cursor=pointer]
                    - row [ref=e463]:
                      - gridcell [ref=e464]:
                        - generic [ref=e465]:
                          - button "Edit" [ref=e466] [cursor=pointer]
                          - button "Deactivate" [ref=e468] [cursor=pointer]
                          - button "Delete" [ref=e470] [cursor=pointer]
                    - row [ref=e472]:
                      - gridcell [ref=e473]:
                        - generic [ref=e474]:
                          - button "Edit" [ref=e475] [cursor=pointer]
                          - button "Deactivate" [ref=e477] [cursor=pointer]
                          - button "Delete" [ref=e479] [cursor=pointer]
                    - row [ref=e481]:
                      - gridcell [ref=e482]:
                        - generic [ref=e483]:
                          - button "Edit" [ref=e484] [cursor=pointer]
                          - button "Deactivate" [ref=e486] [cursor=pointer]
                          - button "Delete" [ref=e488] [cursor=pointer]
                    - row [ref=e490]:
                      - gridcell [ref=e491]:
                        - generic [ref=e492]:
                          - button "Edit" [ref=e493] [cursor=pointer]
                          - button "Deactivate" [ref=e495] [cursor=pointer]
                          - button "Delete" [ref=e497] [cursor=pointer]
                    - row [ref=e499]:
                      - gridcell [ref=e500]:
                        - generic [ref=e501]:
                          - button "Edit" [ref=e502] [cursor=pointer]
                          - button "Deactivate" [ref=e504] [cursor=pointer]
                          - button "Delete" [ref=e506] [cursor=pointer]
                    - row [ref=e508]:
                      - gridcell [ref=e509]:
                        - generic [ref=e510]:
                          - button "Edit" [ref=e511] [cursor=pointer]
                          - button "Deactivate" [ref=e513] [cursor=pointer]
                          - button "Delete" [ref=e515] [cursor=pointer]
                  - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
                - rowgroup
              - generic [ref=e523]:
                - generic [ref=e524]: Showing 1 to 20 of 74 records
                - generic [ref=e525]: Page 1 of 4
                - generic "More options" [ref=e527]:
                  - button "Select page size" [ref=e528] [cursor=pointer]: "Page size: 20"
                - generic [ref=e530]:
                  - button "Go to the previous page" [disabled] [ref=e531]: Previous
                  - button "Go to the next page" [ref=e533] [cursor=pointer]: Next
  - contentinfo [ref=e535]: © 2026 First Due
  - generic:
    - button "Chat Close Maven Chat" [ref=e536] [cursor=pointer]:
      - img "Chat" [ref=e538]
      - button "Close Maven Chat"
    - iframe
  - alert [ref=e539]:
    - generic [ref=e545]: Training Category added successfully!
    - text: "!"
  - generic [ref=e550]:
    - generic [ref=e552]:
      - generic [ref=e556]: Import Categories
      - button "Close" [ref=e557] [cursor=pointer]
    - generic [ref=e563]:
      - paragraph [ref=e564]: "You are attempting to import values that already exist in your list. Would you like to:"
      - list [ref=e565]:
        - listitem [ref=e566]: Update/overwrite existing records and import new records
        - listitem [ref=e567]: Reject the duplicated rows only, import new ones
        - listitem [ref=e568]: Cancel the operation
      - paragraph [ref=e569]: A file with the duplicate items have been downloaded.
    - generic [ref=e571]:
      - button "Update" [ref=e572] [cursor=pointer]
      - button "Reject" [ref=e573] [cursor=pointer]
      - button "Cancel" [ref=e574] [cursor=pointer]
```

# Test source

```ts
  1   | import { test, expect } from '@/fixtures';
  2   | import { testrailCase } from '@/integrations/testrail';
  3   | import { CategoriesData } from '@/modules/training-setup/data';
  4   | import {
  5   |   CancelCategoriesImportDuplicateTask,
  6   |   CloseImportCategoriesModalTask,
  7   |   CreateCategoryTask,
  8   |   DeleteCategoryTask,
  9   |   DismissCategoriesImportSuccessTask,
  10  |   OpenCategoriesPageTask,
  11  |   OpenImportCategoriesModalTask,
  12  |   RejectCategoriesImportDuplicatesTask,
  13  |   SearchCategoriesByNameTask,
  14  |   SubmitCategoriesImportTask,
  15  |   UpdateCategoriesImportDuplicatesTask,
  16  |   UploadCategoriesImportFileTask,
  17  | } from '@/modules/training-setup/tasks';
  18  | import {
  19  |   CategoryRowCountQuestion,
  20  |   CategoryRowVisibleQuestion,
  21  |   ImportCategoriesHelpTextQuestion,
  22  |   ImportCategoriesSuccessMessageQuestion,
  23  |   ImportCategoriesValidationTextQuestion,
  24  |   ImportDuplicateDialogControlsVisibleQuestion,
  25  |   ImportDuplicateDialogTextQuestion,
  26  |   ImportSubmitOutcomeQuestion,
  27  |   IsImportCategoriesFileListedQuestion,
  28  |   IsImportDuplicateDialogOpenQuestion,
  29  |   IsImportModalOpenQuestion,
  30  | } from '@/modules/training-setup/questions';
  31  | 
  32  | test.describe('Training setup categories', () => {
  33  |   test.setTimeout(180_000);
  34  | 
  35  |   test.beforeEach(async ({ admin }) => {
  36  |     await admin.attemptsTo(OpenCategoriesPageTask.page());
  37  |   });
  38  | 
  39  |   test('@regression C22680549: Verify Import Categories rejects non-CSV and oversized files', async ({ admin }) => {
  40  |     test.info().annotations.push(testrailCase(22680549));
  41  | 
  42  |     const importedCategoryName = CategoriesData.uniqueName();
  43  |     const duplicateImportPath = CategoriesData.importCsvWithName(importedCategoryName);
  44  | 
  45  |     await admin.attemptsTo(CreateCategoryTask.withName(importedCategoryName));
  46  | 
  47  |     const rowsBeforeValidation = await admin.asks(CategoryRowCountQuestion.onPage());
  48  | 
  49  |     await admin.attemptsTo(OpenImportCategoriesModalTask.dialog());
  50  |     expect(await admin.asks(IsImportModalOpenQuestion.check())).toBe(true);
  51  | 
  52  |     const helpText = await admin.asks(ImportCategoriesHelpTextQuestion.displayed());
  53  |     expect(helpText).toMatch(/Only CSV format is supported/i);
  54  |     expect(helpText).toMatch(/64\s*MB/i);
  55  | 
  56  |     await admin.attemptsTo(UploadCategoriesImportFileTask.fromPath(CategoriesData.nonCsvImportPath()));
  57  |     expect(await admin.asks(ImportCategoriesValidationTextQuestion.displayed())).toMatch(
  58  |       /can't upload files of this type/i,
  59  |     );
  60  |     expect(await admin.asks(CategoryRowCountQuestion.onPage())).toBe(rowsBeforeValidation);
  61  | 
  62  |     await admin.attemptsTo(UploadCategoriesImportFileTask.fromPath(CategoriesData.oversizedImportCsvPath()));
  63  |     expect(await admin.asks(ImportCategoriesValidationTextQuestion.displayed())).toMatch(
  64  |       /File is too big.*Max filesize: 64MiB/i,
  65  |     );
  66  |     expect(await admin.asks(CategoryRowCountQuestion.onPage())).toBe(rowsBeforeValidation);
  67  | 
  68  |     await admin.attemptsTo(UploadCategoriesImportFileTask.fromPath(duplicateImportPath));
  69  |     expect(await admin.asks(IsImportCategoriesFileListedQuestion.forPath(duplicateImportPath))).toBe(true);
  70  | 
  71  |     await admin.attemptsTo(SubmitCategoriesImportTask.inOpenModal());
> 72  |     expect(await admin.asks(ImportSubmitOutcomeQuestion.afterSubmit())).toBe('duplicates');
      |                                                                         ^ Error: expect(received).toBe(expected) // Object.is equality
  73  |     expect(await admin.asks(ImportDuplicateDialogControlsVisibleQuestion.check())).toBe(true);
  74  |     expect(await admin.asks(ImportDuplicateDialogTextQuestion.displayed())).toMatch(
  75  |       /already exist in your list/i,
  76  |     );
  77  | 
  78  |     await admin.attemptsTo(CancelCategoriesImportDuplicateTask.dialog());
  79  |     expect(await admin.asks(IsImportDuplicateDialogOpenQuestion.check())).toBe(false);
  80  | 
  81  |     await admin.attemptsTo(CloseImportCategoriesModalTask.dialog());
  82  |     await admin.attemptsTo(OpenImportCategoriesModalTask.dialog());
  83  |     await admin.attemptsTo(UploadCategoriesImportFileTask.fromPath(duplicateImportPath));
  84  |     await admin.attemptsTo(SubmitCategoriesImportTask.inOpenModal());
  85  |     expect(await admin.asks(ImportSubmitOutcomeQuestion.afterSubmit())).toBe('duplicates');
  86  |     await admin.attemptsTo(RejectCategoriesImportDuplicatesTask.dialog());
  87  |     expect(await admin.asks(IsImportDuplicateDialogOpenQuestion.check())).toBe(false);
  88  | 
  89  |     await admin.attemptsTo(CloseImportCategoriesModalTask.dialog());
  90  |     await admin.attemptsTo(OpenImportCategoriesModalTask.dialog());
  91  |     await admin.attemptsTo(UploadCategoriesImportFileTask.fromPath(duplicateImportPath));
  92  |     await admin.attemptsTo(SubmitCategoriesImportTask.inOpenModal());
  93  |     expect(await admin.asks(ImportSubmitOutcomeQuestion.afterSubmit())).toBe('duplicates');
  94  | 
  95  |     await admin.attemptsTo(UpdateCategoriesImportDuplicatesTask.dialog());
  96  |     expect(await admin.asks(ImportCategoriesSuccessMessageQuestion.displayed())).toMatch(
  97  |       /Successfully imported/i,
  98  |     );
  99  | 
  100 |     await admin.attemptsTo(DismissCategoriesImportSuccessTask.dialog());
  101 |     await admin.attemptsTo(SearchCategoriesByNameTask.forExactName(importedCategoryName));
  102 |     expect(await admin.asks(CategoryRowVisibleQuestion.named(importedCategoryName))).toBe(true);
  103 | 
  104 |     await admin.attemptsTo(DeleteCategoryTask.forCategory(importedCategoryName));
  105 |     expect(await admin.asks(CategoryRowVisibleQuestion.named(importedCategoryName))).toBe(false);
  106 |   });
  107 | });
  108 | 
```