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

Name: TAYYEB ISRAR
Date: 05/12/2025

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
- **Target time**: <12 seconds
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
- **Target time**: <18 seconds
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

## 2. Metrics Breakdown

| Task                             | Target Time (s) | Mean Time (s) | Median Time (s) | Range of Times (s) | Target - Mean (s) | Median Absolute Deviation (s) |
|----------------------------------|-----------------|---------------|-----------------|--------------------|-------------------|-------------------------------|
| T1 - Keyboard Navigation         | < 10            | 7.78          | 8.13            | 5.22 - 10.0        | 2.22              | 1.87                          |
| T2 - Confirmation Visible        | < 8             | 5.13          | 5.13            | 4.38 - 5.88        | 2.87              | 0.75                          |
| T3 - Updating Task Details       | < 12            | 15.45         | 9.73            | 9.64 - 26.97       | -3.45             | 0.09                          |

### Reflection / Initial Thoughts

My data contains some valuable insights into the overall task performance. All of the tasks are relatively close to the target times, with some above and others below.
The Median Absolute Deviations suggest a fairly close spread, but the high spread in the range shows outliers. One key outlier in this study can be explained by one participant,
whose 'low typing speed' which noticeably affected their times to complete certain tasks involving extra/precise typing, such as Tasks 3 and 5.

The Median Absolute Deviations (MADs) show a tight spread, indicating consistent performance among participants excluding outliers.

## 3. Findings Table

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

## 4. Pilot Metrics (metrics.csv)

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

-   **P1_1985**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard navigation. Used JS and no-JS.
-   **P2_6741**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard-only. Used JS and no-JS. 
-   **P3_1993**: Standard Mouse + HTMX, 'Somewhat Confident' with keyboard navigation. Used JS and no-JS.

**Total participants**: n=3

------------------------------------------------------------------------

## 5. Implementation Diffs

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
    --pico-background-color: #962020 !important;
    --pico-border-color: #7a1a1a !important;
    --pico-color: #ffffff !important;
}
button.btn-delete:hover,
button.btn-delete:focus {
    --pico-background-color: #7f0000 !important;
    --pico-border-color: #5c0000 !important;
}
```

**What changed**: Modified the Delete Task button to be part of a class with special 'danger' styling, of red background, and added override styling in the base.

**Why**: Helps with 3.2.4 (AA) - Consistent Identification, and clearly indicates a dangerous action to users.

**Impact**: Changing the colour of the 'dangerous' button to reflect its apparent danger can clearly convey the severity of the action to users, helping them to think twice before mistakenly deleting a task, and can assist in reducing frustrating misclicks, improving UX.

------------------------------------------------------------------------

### Fix 3: Increase task title size relative to buttons

**Addresses finding**: Finding #5 (Labels too small compared to buttons)

**Before**:

(src/main/resources/statics/css/custom.css:193):

``` css
.task-title {
  display: block;
  font-weight: 500;
  margin-bottom: 0.25rem;
  word-wrap: break-word;
}
```

**After**:

(src/main/resources/statics/css/custom.css:193):

``` css
.task-title {
  display: block;
  font-weight: 500;
  margin-bottom: 0.3rem;
  word-wrap: break-word;
}
```
(src/main/resources/templates/_layout/base.peb:67):

``` css
.task-title {
  font-size:1.5rem;
}
```

**What changed**: Added override on the font size, increasing the font size of the task title by a factor of 1.5.

**Why**: Supports 1.4.3 (AA) - Text Size / Contrast, since it improves the ratio between overly large buttons and smaller text.

**Impact**: Improving the text size ratio benefits the user by increasing legibility and establishing the most important section within a task view, the title, rather than the buttons, ensuring it is visually prominent.

------------------------------------------------------------------------

## 6. Verification Results

### Part A: Regression Checklist (20 checks)

**Instructions**: Test all 20 criteria. Mark pass/fail/n/a + add notes.

| Check            | Criterion                             | Level       | Result | Notes                                                                                                                    |
|------------------|---------------------------------------|-------------|--------|--------------------------------------------------------------------------------------------------------------------------|
| **Keyboard (5)** |                                       |             |        |                                                                                                                          |
| K1               | 2.1.1 All actions keyboard accessible | A           | Pass   | Tested tab and enter on all buttons, and all were functional.                                                            |
| K2               | 2.4.7 Focus visible                   | AA          | Pass   | Barely passed - focus was visible on all elements, but quite hard to see on the blue buttons.                            |
| K3               | No keyboard traps                     | A           | Pass   | Can successfully Tab through filter, edit, delete without any traps                                                      |
| K4               | Logical tab order                     | A           | Pass   | Tabbing follows the sequential ordering of the elements.                                                                 |
| K5               | Skip links present                    | AA          | Pass   | Skip to main content works perfectly.                                                                                    |
| **Forms (3)**    |                                       |             |        |                                                                                                                          |
| F1               | 3.3.2 Labels present                  | A           | Pass   | All the inputs have an associated label and an aria-describedby label, pointing to them/other elements.                  |
| F2               | 3.3.1 Errors identified               | A           | Pass   | Errors announce themselves in every situation from within the 'status' div.                                              |
| F3               | 4.1.2 Name/role/value                 | A           | Pass   | All the form controls either have explicit or implicit roles which are also correctly announced by the screen reader.    |
| **Dynamic (3)**  |                                       |             |        |                                                                                                                          |
| D1               | 4.1.3 Status messages                 | AA          | Pass   | Status div exists, has status role, and appears after relevant events.                                                   |
| D2               | Live regions work                     | AA          | Fail   | Events are not announced by the screen reader, only shown in text.                                                       |
| D3               | Focus management                      | A           | Fail   | Focus does not correctly change to the error summary after a submit.                                                     |
| **No-JS (3)**    |                                       |             |        |                                                                                                                          |
| N1               | Full feature parity                   | ---         | Fail   | Edit functionality does not work in no-JS mode.                                                                          |
| N2               | POST-Redirect-GET                     | ---         | Pass   | Functional and valid submissions only occur once.                                                                        |
| N3               | Errors visible                        | A           | Fail   | Errors do not appear when in no-JS mode.                                                                                 |
| **Visual (3)**   |                                       |             |        |                                                                                                                          |
| V1               | 1.4.3 Contrast minimum                | AA          | Pass   | All essential text, buttons, labels and headings meet AA. Only minor hint text is below.                                 |
| V2               | 1.4.4 Resize text                     | AA          | Pass   | All content is still visible at 200% zoom.                                                                               |
| V3               | 1.4.11 Non-text contrast              | AA          | Fail   | All non-text elements have acceptable contrast except the focus indicator which fails when on action buttons (e.g. Edit) |
| **Semantic (3)** |                                       |             |        |                                                                                                                          |
| S1               | 1.3.1 Headings hierarchy              | A           | Pass   | Headings are not skipped and follow proper hierarchy, h1 -> h2 -> h3.                                                    |
| S2               | 2.4.1 Bypass blocks                   | A           | Pass   | A skip link exists for main content, and the main role is successfully linked to the main app area.                      |
| S3               | 1.1.1 Alt text                        | A           | Pass   | No images have been used so passes by default.                                                                           |


**Summary**: 15/20 pass, 5/20 fail

**Critical failures** (if any):
- D3: Focus management - Since the focus does not accurately swap focus, I could change the focusing logic or add an anchor to that point of the page.
- N3: Errors visible (no-JS) - As of right now, the noJS version is incapable of displaying errors. This could be fixed by adding a special section in the server-side rendering of the template with a status/error message.

## 7. Second Pilot

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
| P4_1337          | Yes                                | 05/12/2025 12:01               |
| P5_3591          | Yes                                | 05/12/2025 14:21               |

---

### Metrics Breakdown 2

| Task                             | Target Time (s) | Mean Time (s) | Median Time (s) | Range of Times (s) | Target - Mean (s) | Median Absolute Deviation (s) |
|----------------------------------|-----------------|---------------|-----------------|--------------------|-------------------|-------------------------------|
| T1 - Keyboard Navigation         | < 10            | 4.16          | 4.16            | 3.48 - 4.84        | 5.84              | 0.68                          |
| T2 - Confirmation Visible        | < 8             | 3.93          | 3.93            | 3.69 - 4.17        | 4.07              | 0.24                          |
| T3 - Updating Task Details       | < 12            | 5.41          | 5.41            | 5.22 - 5.60        | 6.59              | 0.19                          |
| T4 - Filtering Tasks             | < 14            | 8.62          | 8.62            | 7.99 - 5.24        | 5.38              | 0.63                          |
| T5 - No JavaScript is No Problem | < 18            | 8.00          | 8.00            | 7.70 - 8.29        | 10.0              | 0.29                          |

------------------------------------------------------------------------

### Part B: Before/After Comparison

Key: 
- MAD = Median Absolute Deviation, a measure of consistency

| Metric                | Before (Week 9, n=3) | After (Week 10, n=2) | Change | Target Met? |
|-----------------------|----------------------|----------------------|--------|-------------|
| No-JS error detection | 0/3 (0%)             | 0/2 (0%)             | +0%    | No          |
| Task Input Error Rate | 1/3 (33%)            | 0/2 (0%)             | -33%   | Yes         |
| Focus Management Rate | 0/3 (0%)             | 0/2 (0%)             | +0%    | No          |
| Task 1 Median         | 8.13s                | 4.16s                | -43.8% | Yes         |
| Task 1 MAD            | 1.87s                | 0.68s                | -63.6% | N/A         |
| Task 2 Median         | 5.13s                | 3.93s                | -23.4% | Yes         |
| Task 2 MAD            | 0.75s                | 0.24s                | -68.0% | N/A         |
| Task 3 Median         | 9.73s                | 5.41s                | -44.4% | Yes         |
| Task 3 MAD            | 0.09s                | 0.19s                | +111%  | N/A         |
| Task 4 Median         | 10.2s                | 8.62s                | -15.5% | Yes         |
| Task 4 MAD            | 0.62s                | 0.63s                | -1.61% | N/A         |
| Task 5 Median         | 18.59s               | 8.00s                | -60.0% | Yes         |
| Task 5 MAD            | 3.41s                | 0.29s                | -91.5% | N/A         |
| WCAG 1.4.3 pass       | Fail                 | Pass                 | +100%  | Yes         |

**Re-pilot details**:

All participants once again used a mixture of both standard and non-standard setups.

-   **P4_1337**: Standard Mouse + HTMX, 'Not Comfortable' with keyboard navigation. Used both JS and no-JS.
-   **P5_3591**: Standard Mouse + HTMX, 'Not Comfortable' with keyboard-only. Used JS and no-JS.

**Limitations / Honest reporting**: The changes seemed to be successful overall. Participant results suggested that the time of completion has reduced across the board, sometimes quite dramatically. However, it must be acknowledged that the sample size of n=2 for the repilot was smaller than the original, which can cause misrepresentation of real effects. Furthermore, some metrics and critical issues remain unchanged - this is due to different fixes being done (based on perhaps-misjudged priority).

------------------------------------------------------------------------

## 8. Evidence Folder Contents

### Screenshots

| Filename                  | What it shows                               | Context / Link to finding                          |
|---------------------------|---------------------------------------------|----------------------------------------------------|
| before_fix1_hint.png      | App without task title hint                 | Finding #3 – Title length requirement invisible    |
| after_fix1_hint.png       | App with task title hint added              | Finding #3 – Title length requirement invisible    |
| before_fix2_delete.png    | App with original blue Delete button        | Finding #1 - Delete Button not visually distinct   |
| after_fix2_delete.png     | App with modified red Delete button         | Finding #1 - Delete Button not visually distinct   |
| before_fix3_title.png     | App with previous, smaller, title font size | Finding #3 - Labels too small compared to buttons  |
| after_fix3_title.png      | App with larger title font size             | Finding #3 - Labels too small compared to buttons  |
| regression-axe-report.png | Axe DevTools screenshot of 0 issues         | Verification of WCAG violation not being committed |


------------------------------------------------------------------------

### Pilot Notes
  
- **P1_1985**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard navigation. Used JS and no-JS:

T1
- Time was stressful (pressure)
- Works fine
- Tab is simple and easy to use
- Moderately confident using keyboard navigation, doesn't use it often

T2
- Simple to delete a task
- Having to confirm each time is annoying
- Mouse is slow

T3
- Editing task button is rather big and imposing
- Double-click to edit would be nice
- Name is very small compared to buttons
- Edit & Delete look similar (colourwise), could be red for delete.

T4
- Apply filter button is pointless, as the search is dynamic
- Filtering section looks nice/polished (UI).
- Feels like a search bar - no ability to search by time created/category.

T5
- No confirmation on deletion, could add
- Otherwise no noticeable difference, refresh is so fast and therefore can't see it.
- Quick

-   **P2_6741**: Standard Mouse + HTMX, 'Moderately Confident' with keyboard-only. Used JS and no-JS:

T1
- Simple task, basic testing.
- Make it known to the user that the title is >= 3 characters.
- Add a description for that section.
- Moderately confident in using the keyboard navigation.

T2
- Easy to remove task
- Pop-up window is reassuring
- Would it work with a screen reader (from a dev perspective)?
- Recycle bin to restore deleted tasks
- Delete should signal danger, with colour red

T3
- Different colour for edit/save buttons, symbols maybe
- Intuitive to edit a task
- Text is good-sized

T4
- Easy to use
- Looks nice
- Totally fine as-is

T5
- Works the same
- Refresh is a little annoying

- **P3_1993**: Standard Mouse + HTMX, 'Somewhat Confident' with keyboard navigation. Used JS and no-JS. 

T1
- Task was easy and intuitive
- Using Tab for navigation is standard and simple
- Somewhat comfortable using keyboard navigation, but prefers mouse
- Alert wasn't immediately visible

T2
- Very easy, easier than the first, because mouse is available for navigation
- Delete could be red to signal danger.
- Prompt is fine

T3
- Little harder due to more options - need to be careful about pressing the right button
- Cancel is smaller than Save which is nice so don't accidentally cancel.

T4
- Fast when filtering, it's not immediately obvious if being filtered or not when viewed from above
- Filter button seems redundant because the bar itself handles the filtering

T5
- Easy to use
- No alert is given on page refresh
- Didn't notice the refreshes

- **P4_1337**: Standard Mouse + HTMX, 'Not Comfortable' with keyboard navigation. Used both JS and no-JS.

T1
- Good that you can add tasks with enter
- Easy and intuitive to complete the task
- Not comfortable with keyboard navigation on web browsers, only NeoVim bindings

T2
- Easy task
- Not a a fan of red button, but it does signify danger to the user which is good.
- Red border instead of button would be nice

T3
- Task was easy, straightforward
- Cancel button could be a little bigger.
- Colour is nice

T4
- Easy task to complete
- Task names look nice, decently-sized
- Didn't use the filter button.

T5
- Task was fine, had no problems
- Refresh was quite fast, not jarring and hard to notice
- No alert was given at the top

- **P5_3591**: Standard Mouse + HTMX, 'Not Comfortable' with keyboard-only. Used JS and no-JS.

T1
- Simple task, straightforward to complete
- UI is boring and easy to understand
- Not comfortable with keyboard navigation

T2
- Easy task
- Not a fan of JavaScript status message, looks ugly

T3
- Simple task
- Same UI, no real complaints

T4
- Easy to complete task
- UI was fine
- Average user won't understand why the filter section specifies it works without JavaScript

T5
- Easy to do
- UI is boring and simple

------------------------------------------------------------------------

## Evidence Chain Example (Full Trace)

Here is one finding with a complete evidence trail from data → fix → verification.

**Finding selected**: Finding #3 – Title length requirement invisible

**Evidence trail**:

1.  **Data**: P2_6741_pilot.md: T1, metrics.csv L3 also show that P2 triggered the validation due to a task that was too short in length.
2.  **Observation**: P2_6741_pilot.md: T1, complained about the lack of information.
3.  **Screenshot**: before-fix1-hint.png shows a lack of hints for how long a task name should be.
4.  **WCAG**: 3.3.2 (A) - Labels & Instructions violation - not enough instruction given to user (unlabeled requirement).
5.  **Prioritisation**: Findings Table (above) row 3 - Priority score 7 (Impact 5 + Inclusion 3 - Effort 1)
6.  **Fix**: Implementation Diffs section Fix #1 - Modified the existing title hint to now include a requirement for the minimum length of a task title (3 characters).
7.  **Verification**: Verification Section Part A row F1 - 3.3.1 is now a PASS
8.  **Before/after**: 7.  Verification Table Before/After comparison shows a Pass where it was previously a Fail.
9.  **Re-pilot**: P4_1337 was able to successfully complete the associated task in 3.48 seconds, which was a record time.
