# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: training-plan-progress/C22697079-verify-completed-course-credits-mapped-course-list-requirement-area.spec.ts >> Training Plan Progress >> C22697079: Verify a completed course credits the mapped Course List Requirement Area
- Location: src/tests/training-plan-progress/C22697079-verify-completed-course-credits-mapped-course-list-requirement-area.spec.ts:25:7

# Error details

```
Error: Missing required environment variable: MY_TRAINING_PLAN_ID
```

# Test source

```ts
  1  | export interface TrainingPlanProgressContext {
  2  |   planId: number;
  3  |   requirementAreaLabel: string;
  4  |   courseName: string;
  5  |   memberDisplayName: string;
  6  |   planProgressPath: string;
  7  | }
  8  | 
  9  | const requiredEnv = (key: string): string => {
  10 |   const value = process.env[key]?.trim();
  11 |   if (!value) {
> 12 |     throw new Error(`Missing required environment variable: ${key}`);
     |           ^ Error: Missing required environment variable: MY_TRAINING_PLAN_ID
  13 |   }
  14 |   return value;
  15 | };
  16 | 
  17 | const requiredEnvNumber = (key: string): number => {
  18 |   const value = requiredEnv(key);
  19 |   const parsed = Number.parseInt(value, 10);
  20 |   if (Number.isNaN(parsed)) {
  21 |     throw new Error(`Environment variable ${key} must be a number. Received: ${value}`);
  22 |   }
  23 |   return parsed;
  24 | };
  25 | 
  26 | export const TrainingPlanProgressData = {
  27 |   planId: (): number => requiredEnvNumber('MY_TRAINING_PLAN_ID'),
  28 | 
  29 |   requirementAreaLabel: (): string => requiredEnv('MY_TRAINING_PLAN_REQUIREMENT_AREA'),
  30 | 
  31 |   courseName: (): string => {
  32 |     const override = process.env.SCHEDULED_TRAINING_COURSE_NAME?.trim();
  33 |     if (override) {
  34 |       return override;
  35 |     }
  36 |     return requiredEnv('MY_TRAINING_PLAN_COURSE_NAME');
  37 |   },
  38 | 
  39 |   memberDisplayName: (): string => {
  40 |     const override = process.env.TRAINING_PLAN_MEMBER_NAME?.trim();
  41 |     if (override) {
  42 |       return override;
  43 |     }
  44 |     const fromEnv = process.env.PERSONNEL_DISPLAY_NAME?.trim();
  45 |     if (fromEnv) {
  46 |       return fromEnv;
  47 |     }
  48 |     throw new Error('Missing required environment variable: TRAINING_PLAN_MEMBER_NAME or PERSONNEL_DISPLAY_NAME');
  49 |   },
  50 | 
  51 |   planProgressPath: (): string => `/training-v2/plans/view/${TrainingPlanProgressData.planId()}`,
  52 | 
  53 |   context: (): TrainingPlanProgressContext => ({
  54 |     planId: TrainingPlanProgressData.planId(),
  55 |     requirementAreaLabel: TrainingPlanProgressData.requirementAreaLabel(),
  56 |     courseName: TrainingPlanProgressData.courseName(),
  57 |     memberDisplayName: TrainingPlanProgressData.memberDisplayName(),
  58 |     planProgressPath: TrainingPlanProgressData.planProgressPath(),
  59 |   }),
  60 | };
  61 | 
```