# Task 1 — Web Application QA Report

## 1. Project Information

| Field | Details |
|---|---|
| Tester | [Your Name] |
| Application | RealWorld Conduit |
| Application URL | [Insert exact URL tested] |
| Test date | [Insert date] |
| Browser | [Insert browser and version] |
| Operating system | Windows [10/11] |
| Test type | Manual functional and responsive testing |

## 2. Objective

The objective was to manually test the web application, verify important user journeys, identify unexpected behaviour, and document potential defects.

## 3. Test Cases and Results

| ID | Test scenario | Reported result | Status |
|---|---|---|---|
| TC-01 | Open homepage | Homepage loaded | Pass |
| TC-02 | Register with valid details | Registration succeeded | Pass |
| TC-03 | Submit empty registration form | Validation displayed | Pass |
| TC-04 | Enter invalid email | Invalid email rejected | Pass |
| TC-05 | Login with valid credentials | Login succeeded | Pass |
| TC-06 | Create article | Article created | Pass |
| TC-07 | Edit article | Article updated | Pass |
| TC-08 | Refresh after editing | Changes persisted | Pass |
| TC-09 | Delete article | Article deleted | Pass |
| TC-10 | Logout and browser back navigation | Test passed | Pass |
| TC-11 | Login with incorrect password | Test passed | Pass |
| TC-12 | Submit empty article | Test passed | Pass |
| TC-13 | Enter special characters | Test passed | Pass |
| TC-14 | Article ownership | Test marked as passed; exact steps not recorded | Needs detail |
| TC-15 | Mobile responsiveness | Test passed | Pass |

## 4. Potential Defects Requiring Investigation

These areas were marked for investigation. They are not confirmed defects because exact reproduction steps and evidence have not yet been recorded.

| ID | Area | Initial priority | Status |
|---|---|---|---|
| QA-01 | Duplicate registration | Medium | Needs investigation |
| QA-02 | Search functionality | Medium | Needs investigation |
| QA-03 | Cross-account authorization | Critical if confirmed | Needs investigation |
| QA-04 | Pagination | Medium | Needs investigation |
| QA-05 | Network failure handling | High if failures are silent or cause data loss | Needs investigation |



**Important:** Cross-account authorization should receive special attention. Verify using two separate accounts whether one user can edit or delete another user's article.

## 5. Overall Summary

The reported tests covered the main user journeys, including registration, login, article creation, editing, persistence, deletion, validation, logout, and responsive design.

Most reported core functional tests passed. Five additional areas were flagged for investigation: duplicate registration, search functionality, cross-account authorization, pagination, and network failure handling.

These potential defects must be reproduced and documented before being included as confirmed bugs in the final report.

## 6. Recommendations

1. Re-test each potential defect and capture evidence.
2. Verify that users cannot modify another user's content.
3. Check that search and pagination return correct results.
4. Verify that network errors are communicated clearly.
5. Ensure all validation messages are understandable.

