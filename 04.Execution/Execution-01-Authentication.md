# Execution 01 - Authentication

## Execution Overview

**Scenario:** Scenario 01 - Authentication

**Execution Scope:** Authentication

**Execution Objective:**
Validate the login and logout functionality of the application against the defined authentication test cases.

---

## Test Execution

### TS 01 AUT 01 - Login

#### TC 01 AUT 01 A - Login with Valid Credentials

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
User is successfully logged in and the authenticated user information is displayed.

**Actual Result:**
User was successfully logged in and the authenticated user information was displayed.

**Defect:**
None

---

#### TC 01 AUT 01 B - Login with Invalid Credentials

**Execution Status:** Not Executed

**Expected Result:**
User is not authenticated and an appropriate login error message is displayed.

**Actual Result:**
*To be updated after execution.*

**Defect:**
*N/A*

---

#### TC 01 AUT 01 C - Login Without Credentials

**Execution Status:** Not Executed

**Expected Result:**
User is not authenticated and the application performs the appropriate validation for the missing credentials.

**Actual Result:**
*To be updated after execution.*

**Defect:**
*N/A*

---

### TS 01 AUT 02 - Logout

#### TC 01 AUT 02 A - Logout from Authenticated Session

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
User is successfully logged out and the application returns to the unauthenticated state.

**Actual Result:**
User was successfully logged out and the application returned to the unauthenticated state.

**Defect:**
None

---

## Execution Summary

**Total Test Cases:** 4

**Executed:** 2

**Passed:** 2

**Failed:** 0

**Blocked:** 0

**Not Executed:** 2

**Automation Coverage:** 2 / 4

**Automation Coverage Percentage:** 50%

---

## Defects / Observations

No defects were identified during execution of the tested happy-path scenarios.

The remaining negative and validation scenarios are yet to be executed.