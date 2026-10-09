# Test Plan: Student Registration Form

**Application under test:** https://demoqa.com/automation-practice-form
**Tester:** Aryan Bedade
**Test type:** Manual (functional, smoke, negative, boundary, retest, regression)
**Date:** [FILL: start date] to [FILL: end date]

## 1. Objective
Verify that the main user flows work as expected, find defects through positive, negative and boundary testing, and report them with clear steps to reproduce.

## 2. Scope
**In scope:** Mandatory field validation, name, email, mobile number, date of birth, subjects, hobbies, picture upload, address, state and city dropdowns, submission result window.
**Out of scope:** Performance, security testing, backend or database checks, automation.

## 3. Test Approach
- Test scenarios are written first, then detailed test cases (see the Excel file).
- Techniques used: Equivalence Partitioning (EP), Boundary Value Analysis (BVA), positive and negative testing.
- Each test case is executed manually. Actual results and screenshots are recorded.
- Failed tests are logged in the Defect Log (ID, severity, priority, steps, screenshots).
- After a defect is marked fixed, it is retested. Related flows are then regression tested.
  (Practice sites are not fixed by me, so retest and regression are simulated on the same build: re-run each failed case once and a smoke set of High priority cases, and note the result.)

## 4. Test Environment
| Item | Value |
|---|---|
| Browser | [FILL: e.g. Chrome version] and [FILL: e.g. Firefox version] |
| OS | [FILL: e.g. Windows 11] |
| Network | [FILL] |
| Test data | Dummy data only, no real personal or card details |



## 5. Entry Criteria
- Application URL is reachable.
- Test cases are reviewed and the test data is ready.

## 6. Exit Criteria
- All planned test cases are executed.
- All defects found are logged with severity and priority.
- Test Summary Report is prepared.

## 7. Severity and Priority
| Severity | Meaning |
|---|---|
| Critical | Feature unusable or blocks all further testing |
| High | Major function fails, no workaround |
| Medium | Function partly fails, workaround exists |
| Low | Cosmetic or minor issue |

Priority (High / Medium / Low) shows how soon the defect should be fixed.

## 8. Risks
- The practice site is third-party and may change or be down. Mitigation: note the date and browser of each run.
- Ads or pop-ups can block elements. Mitigation: close them or use another browser, and note it.

## 9. Deliverables
Test Plan, Test Scenarios, Test Cases, Execution Report, Defect Log, Test Summary Report, screenshots.
