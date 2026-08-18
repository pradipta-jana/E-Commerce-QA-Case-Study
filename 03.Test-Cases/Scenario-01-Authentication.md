# Scenario 01 - Authentication

This scenario covers authentication-related functionality, including user login and logout.

---

## TS 01 AUT 01 - Login

### TC 01 AUT 01 A - Login with Valid Credentials

**Pre Condition:**

* User has a registered account.
* Application is accessible.
* User is on the Login page.

**Test Step:**

1. Enter a valid registered email address.
2. Enter the corresponding valid password.
3. Click the Login button.

**Expected Output:**

* User is successfully logged in.
* The application displays the authenticated user's account information.

**Automation Status:** Automated

---

### TC 01 AUT 01 B - Login with Invalid Credentials

**Pre Condition:**

* Application is accessible.
* User is on the Login page.
* Invalid login credentials are available.

**Test Step:**

1. Enter an invalid email address or password.
2. Click the Login button.

**Expected Output:**

* User is not authenticated.
* The application displays an appropriate login error message.

**Automation Status:** Not Automated

---

### TC 01 AUT 01 C - Login Without Credentials

**Pre Condition:**

* Application is accessible.
* User is on the Login page.

**Test Step:**

1. Leave the email address field empty.
2. Leave the password field empty.
3. Click the Login button.

**Expected Output:**

* User is not authenticated.
* The application performs the appropriate validation for the missing credentials.

**Automation Status:** Not Automated

---

## TS 01 AUT 02 - Logout

### TC 01 AUT 02 A - Logout from Authenticated Session

**Pre Condition:**

* User is successfully logged in.

**Test Step:**

1. Click the Logout option.

**Expected Output:**

* User is successfully logged out.
* The application returns the user to the unauthenticated state.

**Automation Status:** Automated

---
