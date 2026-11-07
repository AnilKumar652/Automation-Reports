# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: my-training-plans/C22682169-verify-user-returns-to-plan-details-after-completing-a-course-action.spec.ts >> My Training Plans >> C22682169: Verify User Returns to Plan Details After Completing a Course Action
- Location: src/tests/my-training-plans/C22682169-verify-user-returns-to-plan-details-after-completing-a-course-action.spec.ts:21:7

# Error details

```
Error: Missing required environment variable: MY_TRAINING_PLAN_ID
```

# Test source

```ts
  1  | export interface MyTrainingPlanDetailsContext {
  2  |   planId: number;
  3  |   areaId: number;
  4  |   trainingPlanUserId: number;
  5  |   planName: string;
  6  |   requirementAreaLabel: string;
  7  |   courseName: string;
  8  |   planDetailsPath: string;
  9  | }
  10 | 
  11 | const requiredEnv = (key: string): string => {
  12 |   const value = process.env[key]?.trim();
  13 |   if (!value) {
> 14 |     throw new Error(`Missing required environment variable: ${key}`);
     |           ^ Error: Missing required environment variable: MY_TRAINING_PLAN_ID
  15 |   }
  16 |   return value;
  17 | };
  18 | 
  19 | const requiredEnvNumber = (key: string): number => {
  20 |   const value = requiredEnv(key);
  21 |   const parsed = Number.parseInt(value, 10);
  22 |   if (Number.isNaN(parsed)) {
  23 |     throw new Error(`Environment variable ${key} must be a number. Received: ${value}`);
  24 |   }
  25 |   return parsed;
  26 | };
  27 | 
  28 | export const MyTrainingPlansData = {
  29 |   planName: (): string => requiredEnv('MY_TRAINING_PLAN_NAME'),
  30 | 
  31 |   requirementAreaLabel: (): string => requiredEnv('MY_TRAINING_PLAN_REQUIREMENT_AREA'),
  32 | 
  33 |   courseName: (): string => requiredEnv('MY_TRAINING_PLAN_COURSE_NAME'),
  34 | 
  35 |   planId: (): number => requiredEnvNumber('MY_TRAINING_PLAN_ID'),
  36 | 
  37 |   areaId: (): number => requiredEnvNumber('MY_TRAINING_PLAN_AREA_ID'),
  38 | 
  39 |   trainingPlanUserId: (): number => requiredEnvNumber('MY_TRAINING_PLAN_USER_ID'),
  40 | 
  41 |   planDetailsPath: (): string => {
  42 |     const override = process.env.MY_TRAINING_PLAN_DETAILS_PATH?.trim();
  43 |     if (override) {
  44 |       return override;
  45 |     }
  46 | 
  47 |     const planId = MyTrainingPlansData.planId();
  48 |     const areaId = MyTrainingPlansData.areaId();
  49 |     const trainingPlanUserId = MyTrainingPlansData.trainingPlanUserId();
  50 |     return `/training-v2/my-plans/plan/${planId}/area/${areaId}?training_plan_user_id=${trainingPlanUserId}`;
  51 |   },
  52 | 
  53 |   detailsContext: (): MyTrainingPlanDetailsContext => ({
  54 |     planId: MyTrainingPlansData.planId(),
  55 |     areaId: MyTrainingPlansData.areaId(),
  56 |     trainingPlanUserId: MyTrainingPlansData.trainingPlanUserId(),
  57 |     planName: MyTrainingPlansData.planName(),
  58 |     requirementAreaLabel: MyTrainingPlansData.requirementAreaLabel(),
  59 |     courseName: MyTrainingPlansData.courseName(),
  60 |     planDetailsPath: MyTrainingPlansData.planDetailsPath(),
  61 |   }),
  62 | };
  63 | 
```