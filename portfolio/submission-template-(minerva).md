**Student**: Tayyeb Israr 201829422

**Submission date**: 05/12/2025

**Academic Year**: 2025-26

------------------------------------------------------------------------

## Privacy & Ethics Statement

- [x] I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names)
- [x] I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible)
- [x] I confirm all participants gave informed consent
- [x] I confirm this work is my own (AI tools used for code assistance are cited below)

**AI tools used** (if any): None were required.

------------------------------------------------------------------------

## 1. Protocol & Tasks

### Link to Needs-Finding

#### **Job Story #1**: Keyboard Navigation

**Situation**: When I stop being able to use my trackpad/mouse
**Motivation**: I want to be able to navigate the task manager using alternative methods
**Outcome**: So I can continue managing tasks without being limited by hardware issues
**Underlying need**: Because depending solely on one input method creates an accessibility gap and interrupts task completion
**WCAG**: 2.1.1 Keyboard (A)

**How Task 1 tests this**: The participant tests a relevant function with no mouse, ensuring usability.

#### **Job Story #2**: Confirmation visible

**Situation**: When I submit a form (add/edit/delete task)
**Motivation**: I want immediate, explicit confirmation that the action succeeded
**Outcome**: So I can trust the interface without refreshing to verify
**Underlying need**: Because uncertainty about save status causes anxiety and inefficient workarounds
**WCAG**: 4.1.3 Status Messages (AA)

**How Task 2 tests this**: The participant performs a task requiring a confirmation message, and verifies the job story's concern is addressed.

#### **Job Story #3**: Updating Task Details

**Situation**: When I realise I need to change a detail about a task (e.g., due date, priority, description)
**Motivation**: I want to be able to quickly edit the task without starting from scratch
**Outcome**: So I don't waste time remaking and deleting tasks and losing momentum
**Underlying need**: Because maintaining up-to-date task information is essential for effective time management.
**WCAG**: WCAG 2.1.1 Keyboard (A)

**How Task 3 tests this**: Participant edits a given task with a more relevant name, demonstrating the working edit function.

#### **Job Story #4**: Filtering Tasks

**Situation**: When I look through my task list
**Motivation**: I want to be able to separate my tasks using a search
**Outcome**: So it remains easy to view and navigate certain tasks when there is a lot
**Underlying need**: Because searching through a lot of tasks is cumbersome
**WCAG**: 2.4.7 Focus Visible (AA)

**How Task 4 tests this**: The participant tests the filter functionality and uses it to successfully delete a task.

#### **Job Story S5**: Reliable Access On Low Battery
**Situation**: When I lose charge on my phone, therefore losing access to timed reminders
**Motivation**: I want backup visibility (e.g. desktop alerts or synced reminders)
**Outcome**: So I don't miss important tasks due to one device failing
**Underlying need**: Because relying solely on one device increases the vulnerability of missed deadlines
**WCAG**: 2.4.5 Multiple Ways (AA)

**Task was not assigned for this story**

#### **Job Story S6**: No JavaScript is No Problem
**Situation**: When I cannot use JavaScript on my browser
**Motivation**: I want to still be able to use my applications, like my todo list.
**Outcome**: So I don't miss important deadlines just because of a software or hardware limitation
**Underlying need**: Because being able to use apps in different modes of accessibility is crucial for a well-designed application.

**How Task 5 tests this**: The participant tests the navigation and functionality of the app when JavaScript is disabled.

------------------------------------------------------------------------

### Evaluation Tasks

#### Task 1 (T1): Keyboard Navigation

- **Scenario**: You sit down to manage your tasks on your laptop, but you realise your mouse has stopped working. You disconnect the mouse, and attempt to use the trackpad, only to realise it also has stopped functioning.
- **Action**: Please use the keyboard only to navigate to the 'Add Task' textbox, enter a task, then save it.
- **Success**: User has successfully created a new task
- **Target time**: <10 seconds
- **Linked to**: Job Story 1

#### Task 2 (T2): Confirmation Visible

- **Scenario**: You have a list of tasks that you’ve been managing, and you’re ready to clean up your task list by removing a completed or irrelevant task
- **Action**: Please navigate to 'delete task', and delete a task of your choice. Look for and acknowledge the notification.
- **Success**: Notification of task successfully appears, and is acknowledged by the user.
- **Target time**: <8 seconds
- **Linked to**: Job Story 2

#### Task 3 (T3): Updating Task Details

- **Scenario**: You've just completed the first section of a multi-step task, and it seems wrong to create a new task for the next part.
- **Action**: Please edit a task from the list, giving it the name '[Name of the task] Part 2', and then save it.
- **Success**: The task is saved in the list with the correct name, and there is an alert confirmation at the top.
- **Target time**: <10 seconds
- **Linked to**: Job Story 3

#### Task 4 (T4): Filtering Tasks

- **Scenario**: You've not got a lot of time to waste, and you need to find a certain task very quickly. There are 7 tasks already present.
- **Action**: Please use the filter text box to filter the tasks for 'update'. Delete the only task that appears.
- **Success**: The task 'Software update' is successfully deleted.
- **Target time**: <14 seconds
- **Linked to**: Job Story 4

#### Task 5 (T5): No JavaScript is No Problem

- **Scenario**: Your browser's JavaScript functionality has stopped working - lots of websites you've tried no longer load correctly. You need to access your tasks to add something you have due later.
- **Action**: Please navigate to the tasks list, and add a task named 'Check add noJS'. Save it, then navigate back to it, and delete the task named 'Delete noJs'.
- **Success**: The task 'Check add noJS' is successfully added, and 'Delete noJS' has been deleted.
- **Target time**: <12 seconds
- **Linked to**: Job Story 6

---

### My Consent Script (I read verbatim)

**Introduction**:
"Thank you for participating in my HCI evaluation. This will take about 20 minutes. I'm testing my task management interface, not you. There are no right or wrong answers."

**Rights**:
- [x] "Your participation is voluntary. You can stop at any time without giving a reason."
- [x] "Your data will be anonymous. I'll use a code (like P1) instead of your name."
- [x] "I may take screenshots, screen recordings (without audio) and notes. I'll remove any identifying information."
- [x] "I will only keep the data I collect until the end of this academic year, and it will be deleted before the new year begins."
- [x] "Do you consent to participate?" [Wait for verbal yes]

### Participants & Consent

| Participant Code | Read Consent Script to Participant | Date and Time of Given Consent |
|------------------|------------------------------------|--------------------------------|
| P1_1985          | Yes                                | 02/12/2025 14:42               |
| P2_6741          | Yes                                | 02/12/2025 14:03               |
| P3_1993          | Yes                                | 02/12/2025 14:20               |

---

## 2. Findings Table

**Priority formula**: (Impact + Inclusion) - Effort

| Finding                              | Data Source(s)                             | Observation                                                                                                                | WCAG                                   | Impact (1-5) | Inclusion (1-5) | Effort (1-5) | Priority |
|--------------------------------------|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|----------------------------------------|--------------|-----------------|--------------|----------|
| Delete Button not visually distinct  | P1_1985_pilot.md: T3, metrics.csv L44      | P1_1985: "Edit and Delete look the same in colour, could be red for delete.", 14:47                                        | 3.2.4 (AA) - Consistent Identification | 5            | 3               | 2            | 6        |
| Filter Button redundant/unclear      | P3_1993_pilot.md: T4, metrics.csv L29-32   | P3_1993: "The filter button seems redundant because the bar itself does the filtering", 14:26                              | 3.3.2 (A) - Labels & Instructions      | 3            | 2               | 3            | 2        |
| Title length requirement invisible   | P2_6741_pilot.md: T1, metrics.csv L3       | P2_6741: "You should make it known to the user that the title 3 or more characters", 14:05                                 | 3.3.2 (A) - Labels & Instructions      | 5            | 3               | 1            | 7        |
| Confirmation behaviour inconsistent  | P2_6741_pilot.md: T2, P3_1993_pilot.md: T5 | P2_6741: "The pop-up window [for HTMX] is reassuring", 14:06, P3_1993_pilot.md: "No alert is given on page refresh", 14:28 | 3.3.4 (AA) - Error Prevention          | 3            | 4               | 4            | 3        |
| Labels too small compared to buttons | P1_1985_pilot.md: T3, metrics.csv L44      | P1_1985: "The name [of the task] is very small compared to the buttons", 14:46                                             | 1.4.3 (AA) - Text Size / Contrast      | 3            | 4               | 1            | 6        |

**Top 3 priorities for redesign**:

1.  Finding #3 - Priority score 7
2.  Finding #1 - Priority score 6
3.  Finding #5 - Priority score 6

------------------------------------------------------------------------

## 3. Pilot Metrics (metrics.csv)

``` csv
ts_iso,session_id,request_id,task_code,step,outcome,ms,http_status,js_mode
2025-12-02T14:04:58.909621Z,P2_6741,r_99c9b7de,T0_list,success,,98,200,off
2025-12-02T14:05:05.909621Z,P2_6741,r_98e5b230,T3_add,validation_error,min_length,0,400,on
2025-12-02T14:05:12.909621Z,P2_6741,r_98e5b230,T3_add,success,,21,200,on
2025-12-02T14:05:20.909621Z,P2_6741,r_c1b55661,T0_list,success,,6,200,off
2025-12-02T14:05:35.942666Z,P2_6741,r_b7a0ea2d,T0_list,success,,8,200,off
2025-12-02T14:05:40.309877Z,P2_6741,r_b367a17f,T3_add,success,,6,200,on
2025-12-02T14:06:26.496929Z,P2_6741,r_d4b00734,T0_list,success,,8,200,off
2025-12-02T14:06:30.998770Z,P2_6741,r_d6c3e375,T4_delete,success,,4,200,on
2025-12-02T14:07:10.924066Z,P2_6741,r_605a0b4f,T0_list,success,,11,200,off
2025-12-02T14:09:16.166698Z,P2_6741,r_765a6dda,T0_list,success,,15,200,off
2025-12-02T14:09:20.860832Z,P2_6741,r_f3f16088,T1_filter,success,,10,200,on
2025-12-02T14:09:21.777904Z,P2_6741,r_bdc09e15,T1_filter,success,,4,200,on
2025-12-02T14:09:22.234997Z,P2_6741,r_2d353c80,T1_filter,success,,5,200,on
2025-12-02T14:09:24.447821Z,P2_6741,r_ece8ffe5,T1_filter,success,,12,200,on
2025-12-02T14:09:27.562796Z,P2_6741,r_9b66a25b,T4_delete,success,,3,200,on
2025-12-02T14:10:23.304246Z,P2_6741,r_4241aaa9,T1_filter,success,,8,200,off
2025-12-02T14:10:23.313040Z,P2_6741,r_845aea17,T0_list,success,,6,200,off
2025-12-02T14:10:48.215920Z,P2_6741,r_fc470f5f,T3_add,success,,1,200,off
2025-12-02T14:10:48.231540Z,P2_6741,r_bea41005,T0_list,success,,10,200,off
2025-12-02T14:10:51.802018Z,P2_6741,r_b365aa06,T4_delete,success,,4,200,off
2025-12-02T14:10:51.812436Z,P2_6741,r_39f39168,T0_list,success,,7,200,off
2025-12-02T14:21:46.109683Z,P3_1993,r_64b767a4,T0_list,success,,5,200,off
2025-12-02T14:21:57.451707Z,P3_1993,r_55eb248b,T3_add,success,,3,200,on
2025-12-02T14:23:32.523544Z,P3_1993,r_87bbf5a8,T0_list,success,,9,200,off
2025-12-02T14:23:37.275474Z,P3_1993,r_abdc4ba1,T4_delete,success,,2,200,on
2025-12-02T14:24:34.457771Z,P3_1993,r_29b84294,T0_list,success,,5,200,off
2025-12-02T14:25:38.954912Z,P3_1993,r_64ece8d6,T0_list,success,,10,200,off
2025-12-02T14:25:43.471212Z,P3_1993,r_04b57b05,T1_filter,success,,4,200,on
2025-12-02T14:25:44.040881Z,P3_1993,r_3a28ca7b,T1_filter,success,,2,200,on
2025-12-02T14:25:44.431335Z,P3_1993,r_32bdbad6,T1_filter,success,,3,200,on
2025-12-02T14:25:45.083027Z,P3_1993,r_3fa5c41a,T1_filter,success,,4,200,on
2025-12-02T14:25:48.815783Z,P3_1993,r_2c259876,T4_delete,success,,2,200,on
2025-12-02T14:27:59.590045Z,P3_1993,r_ab95ac44,T1_filter,success,,8,200,off
2025-12-02T14:27:59.602845Z,P3_1993,r_1922b7ac,T0_list,success,,8,200,off
2025-12-02T14:28:13.297016Z,P3_1993,r_4f24e91b,T3_add,success,,14,200,off
2025-12-02T14:28:13.305271Z,P3_1993,r_89f2ea8d,T0_list,success,,5,200,off
2025-12-02T14:28:18.693710Z,P3_1993,r_c0b8ba60,T4_delete,success,,5,200,off
2025-12-02T14:28:18.705358Z,P3_1993,r_a1c91cba,T0_list,success,,6,200,off
2025-12-02T14:45:04.438163Z,P1_1985,r_20b73f05,T0_list,success,,10,200,off
2025-12-02T14:45:11.052011Z,P1_1985,r_85fda7a9,T3_add,success,,9,200,on
2025-12-02T14:45:48.591047Z,P1_1985,r_96fb4adc,T0_list,success,,9,200,off
2025-12-02T14:45:51.047622Z,P1_1985,r_6258fe41,T4_delete,success,,4,200,on
2025-12-02T14:46:55.591146Z,P1_1985,r_7b57a3be,T0_list,success,,7,200,off
2025-12-02T14:47:34.434799Z,P1_1985,r_0094064e,T0_list,success,,10,200,off
2025-12-02T14:47:37.425068Z,P1_1985,r_e8296117,T1_filter,success,,8,200,on
2025-12-02T14:47:40.568278Z,P1_1985,r_e843a571,T4_delete,success,,4,200,on
2025-12-02T14:49:15.583545Z,P1_1985,r_3ef430e2,T0_list,success,,16,200,off
2025-12-02T14:49:23.982697Z,P1_1985,r_516df8a0,T3_add,success,,16,200,off
2025-12-02T14:49:23.993521Z,P1_1985,r_99898ae1,T0_list,success,,7,200,off
2025-12-02T14:49:27.309196Z,P1_1985,r_6f30beb5,T4_delete,success,,4,200,off
2025-12-02T14:49:27.322410Z,P1_1985,r_1620840d,T0_list,success,,9,200,off
```

**Participant summary**:

All participants used a mixture of both standard and non-standard setups.

-   **P1_1985**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard navigation
-   **P2_6741**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard-only
-   **P3_1993**: Standard Mouse + HTMX, 'Somewhat Confident' with keyboard navigation

**Total participants**: n=3

------------------------------------------------------------------------

## 4. Implementation Diffs

### Fix 1: Add a task title length requirement

**Addresses finding**: Finding #3 (Title length requirement invisible)

**Before** (src/main/resources/templates/tasks/index.peb:49):

``` kotlin
<small id="title-hint">Keep it short and specific.</small>
```

**After** (src/main/resources/templates/tasks/index.peb:49):

``` kotlin
<small id="title-hint">Keep it short and specific. <strong> 3 characters minimum </strong></small>
```

**What changed**: Modified the existing title hint to now include a requirement for the minimum length of a task title (3 characters).

**Why**: This helps with WCAG 3.3.2 (A) - Labels & Instructions, as it informs the user on how to use a feature correctly.

**Impact**: The addition of this instruction inside the hint improves user experience by reducing stress and friction induced by 400 errors due to an invalid (too short) title being attempted as input. No regular users would have known this requirement, and this will also be announced by a screen reader, so this will benefit all users.

------------------------------------------------------------------------

### Fix 2: Make the Delete button visually distinct from other buttons

**Addresses finding**: Finding #1 (Delete Button not visually distinct)

**Before**:

(src/main/resources/templates/tasks/_item.peb:16)
``` kotlin
<button type="submit" aria-label="Delete task: {{ task.title }}">Delete</button>
```

**After**:

(src/main/resources/templates/tasks/_item.peb:16)
``` kotlin
<button class="btn-delete" type="submit" aria-label="Delete task: {{ task.title }}">Delete</button>
```

(src/main/resources/templates/_layout/base.peb:57)
``` css
button.btn-delete {
    --pico-background-color: #d32f2f !important;
    --pico-border-color: #b71c1c !important;
    --pico-color: #ffffff !important;
}
button.btn-delete:hover,
button.btn-delete:focus {
  --pico-background-color: #b71c1c !important;
  --pico-border-color: #7f0000 !important;
}
```

**What changed**: Modified the Delete Task button to be part of a class with special 'danger' styling, of red background, and added override styling in the base.

**Why**: Helps with 3.2.4 (AA) - Consistent Identification, and clearly indicates a dangerous action to users.

**Impact**: Changing the colour of the 'dangerous' button to reflect its apparent danger can clearly convey the severity of the action to users, helping them to think twice before mistakenly deleting a task, and can assist in reducing frustrating misclicks, improving UX.

------------------------------------------------------------------------

### Fix 3: Increase task title size relative to buttons

**Addresses finding**: Finding #5 (Labels too small compared to buttons)

**Before**:

``` kotlin
```

**After**:

``` kotlin
```

**What changed**:

**Why**: 

**Impact**: 

------------------------------------------------------------------------

## [5. Verification Results](#5-verification-results){.header} {#5-verification-results}

### [Part A: Regression Checklist (20 checks)](#part-a-regression-checklist-20-checks){.header}

**Instructions**: Test all 20 criteria. Mark pass/fail/n/a + add notes.

::: table-wrapper
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| Check            | Criterion                             | Level       | Result            | Notes                                                          |
+==================+=======================================+=============+===================+================================================================+
| **Keyboard (5)** |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K1               | 2.1.1 All actions keyboard accessible | A           | \[pass/fail\]     | \[e.g., "Tested Tab/Enter on all buttons"\]                    |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K2               | 2.4.7 Focus visible                   | AA          | \[pass/fail\]     | \[e.g., "2px blue outline on all interactive elements"\]       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K3               | No keyboard traps                     | A           | \[pass/fail\]     | \[e.g., "Can Tab through filter, edit, delete without traps"\] |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K4               | Logical tab order                     | A           | \[pass/fail\]     | \[e.g., "Top to bottom, left to right"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| K5               | Skip links present                    | AA          | \[pass/fail/n/a\] | \[e.g., "Skip to main content works"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Forms (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F1               | 3.3.2 Labels present                  | A           | \[pass/fail\]     | \[e.g., "All inputs have or aria-label"\]                      |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F2               | 3.3.1 Errors identified               | A           | \[pass/fail\]     | \[e.g., "Errors have role=alert (FIXED in Fix #1)"\]           |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| F3               | 4.1.2 Name/role/value                 | A           | \[pass/fail\]     | \[e.g., "All form controls have accessible names"\]            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Dynamic (3)**  |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D1               | 4.1.3 Status messages                 | AA          | \[pass/fail\]     | \[e.g., "Status div has role=status"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D2               | Live regions work                     | AA          | \[pass/fail\]     | \[e.g., "Tested with NVDA, announces 'Task added'"\]           |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| D3               | Focus management                      | A           | \[pass/fail\]     | \[e.g., "Focus moves to error summary after submit"\]          |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **No-JS (3)**    |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N1               | Full feature parity                   | ---         | \[pass/fail\]     | \[e.g., "All CRUD ops work without JS"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N2               | POST-Redirect-GET                     | ---         | \[pass/fail\]     | \[e.g., "No double-submit on refresh"\]                        |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| N3               | Errors visible                        | A           | \[pass/fail\]     | \[e.g., "Error summary shown in no-JS mode"\]                  |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Visual (3)**   |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V1               | 1.4.3 Contrast minimum                | AA          | \[pass/fail\]     | \[e.g., "All text 7.1:1 (AAA) via CCA"\]                       |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V2               | 1.4.4 Resize text                     | AA          | \[pass/fail\]     | \[e.g., "200% zoom, no content loss"\]                         |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| V3               | 1.4.11 Non-text contrast              | AA          | \[pass/fail\]     | \[e.g., "Focus indicator 4.5:1"\]                              |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| **Semantic (3)** |                                       |             |                   |                                                                |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S1               | 1.3.1 Headings hierarchy              | A           | \[pass/fail\]     | \[e.g., "h1 → h2 → h3, no skips"\]                             |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S2               | 2.4.1 Bypass blocks                   | A           | \[pass/fail\]     | \[e.g., "                                                      |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   | ::: {role="main"}                                              |
|                  |                                       |             |                   | landmark,                                                      |
|                  |                                       |             |                   |                                                                |
|                  |                                       |             |                   | for filter"\]                                                  |
|                  |                                       |             |                   | :::                                                            |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
| S3               | 1.1.1 Alt text                        | A           | \[pass/fail\]     | \[e.g., "No images in interface OR all have alt"\]             |
+------------------+---------------------------------------+-------------+-------------------+----------------------------------------------------------------+
:::

**Summary**: \[X/20 pass\], \[Y/20 fail\] **Critical failures** (if any): \[List any Level A fails\]

------------------------------------------------------------------------

### [Part B: Before/After Comparison](#part-b-beforeafter-comparison){.header}

**Instructions**: Compare Week 9 baseline (pre-fix) to Week 10 (post-fix). Show improvement.

::: table-wrapper
Metric                    Before (Week 9, n=X)   After (Week 10, n=Y)   Change             Target Met?
  ------------------------- ---------------------- ---------------------- ------------------ -------------
SR error detection        \[e.g., 0/2 (0%)\]     \[e.g., 2/2 (100%)\]   \[e.g., +100%\]    \[✅/❌\]
Validation error rate     \[e.g., 33%\]          \[e.g., 0%\]           \[e.g., -33%\]     \[✅/❌\]
Median time \[Task X\]    \[e.g., 1400ms\]       \[e.g., 1150ms\]       \[e.g., -250ms\]   \[✅/❌\]
WCAG \[criterion\] pass   \[fail\]               \[pass\]               \[--- \]           \[✅/❌\]
:::

**Re-pilot details**:

-   **P5** (post-fix): \[Variant - e.g., "Screen reader user, NVDA + keyboard"\] - \[Date piloted\]
-   **P6** (if applicable): \[Variant\] - \[Date\]

**Limitations / Honest reporting**: \[If metrics didn't improve or only modestly: explain why. Small sample size? Wrong fix? Needs more iteration? Be honest - valued over perfect results.\]

------------------------------------------------------------------------

## [6. Evidence Folder Contents](#6-evidence-folder-contents){.header} {#6-evidence-folder-contents}

**Instructions**: List all files in your evidence/ folder. Provide context.

### [Screenshots](#screenshots){.header}

::: table-wrapper
Filename                    What it shows                           Context/Link to finding
  --------------------------- --------------------------------------- --------------------------------------
before-sr-error.png         Error message without role="alert"      Finding #1 - SR errors not announced
after-sr-error.png          Error message WITH role="alert" added   Fix #1 verification
regression-axe-report.png   axe DevTools showing 0 violations       Verification Part A
\[your-screenshot-3.png\]   \[Description\]                         \[Which finding/fix this supports\]
:::

**PII check**:

-   All screenshots cropped to show only relevant UI
-   Browser bookmarks/tabs not visible
-   Participant names/emails blurred or not visible

------------------------------------------------------------------------

### [Pilot Notes](#pilot-notes){.header}

**Instructions**: Attach pilot notes as separate files (P1-notes.md, P2-notes.md, etc.). Summarize key observations here.

**P1** (\[ Variant - e.g., "Standard mouse + HTMX"\]):

-   **Key observation 1**: \[Quote + timestamp - e.g., "Struggled with filter button (09:47)"\]
-   **Key observation 2**: \[Quote + timestamp\]

**P2** (\[Variant\]):

-   **Key observation 1**: \[Quote + timestamp\]
-   **Key observation 2**: \[Quote + timestamp\]

\[Repeat for P3, P4 if applicable\]

------------------------------------------------------------------------

## [Evidence Chain Example (Full Trace)](#evidence-chain-example-full-trace){.header}

**Instructions**: Pick ONE finding and show complete evidence trail from data → fix → verification.

**Finding selected**: \[e.g., "Finding #1 - SR errors not announced"\]

**Evidence trail**:

1.  **Data**: metrics.csv lines 47-49 show P2 (SR user) triggered validation_error 3 times
2.  **Observation**: P2 pilot notes timestamp 14:23 - Quote: "I don't know if it worked, didn't hear anything"
3.  **Screenshot**: before-sr-error.png shows error message has no role="alert" or aria-live
4.  **WCAG**: 3.3.1 Error Identification (Level A) violation - errors not programmatically announced
5.  **Prioritisation**: findings-table.csv row 1 - Priority score 7 (Impact 5 + Inclusion 5 - Effort 3)
6.  **Fix**: implementation-diffs.md Fix #1 - Added role="alert" + aria-live="assertive" to error span
7.  **Verification**: verification.csv Part A row F2 - 3.3.1 now PASS (tested with NVDA)
8.  **Before/after**: verification.csv Part B - SR error detection improved from 0% to 100%
9.  **Re-pilot**: P5 (SR user) pilot notes - "Heard error announcement immediately, corrected and succeeded"

**Complete chain**: Data → Observation → Interpretation → Fix → Verification ✅

------------------------------------------------------------------------

## [Submission Checklist](#submission-checklist){.header}

Before submitting, verify:

**Files**:

-   This completed template (submission-template.md)
-   metrics.csv (or pasted into Section 3)
-   Pilot notes (P1-notes.md, P2-notes.md, etc. OR summarised in Section 6)
-   Screenshots folder (all images referenced above)
-   Privacy statement signed (top of document)

**Evidence chains**:

-   findings-table.csv links to metrics.csv lines AND/OR pilot notes timestamps
-   implementation-diffs.md references findings from table
-   verification.csv Part B shows before/after for fixes

**Quality**:

-   No PII in screenshots (checked twice!)
-   Session IDs anonymous (P1_xxxx format, not real names)
-   Honest reporting (limitations acknowledged if metrics didn't improve)
-   WCAG criteria cited specifically (e.g., "3.3.1" not just "accessibility")

**Pass criteria met**:

-   n=2+ participants (metrics.csv has 2+ session IDs)
-   3+ findings with evidence (findings-table.csv complete)
-   1-3 fixes implemented (implementation-diffs.md shows code)
-   Regression complete (verification.csv has 20 checks)
-   Before/after shown (verification.csv Part B has data)

------------------------------------------------------------------------

**Ready to submit?** Upload this file + evidence folder to Gradescope by end of Week 10.

**Estimated completion time**: 12-15 hours across Weeks 9-10

**Good luck!**
