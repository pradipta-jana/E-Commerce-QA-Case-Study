# Customer Login Test Cases

**Requirement:** REQ-CAM-03 — Customer Login  
**Jira:** [KAN-9](https://pradipta-qa-portfolio.atlassian.net/browse/KAN-9)  
**Scenario:** TS-CAM-07 — Successful Customer Login

## TC-CAM-007 — Successful Customer Login

### Preconditions

- A registered customer account exists.
- Valid login credentials are available.
- User is not currently logged in.

### Test Data

- Email: Registered customer email
- Password: Valid password

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter the registered customer email address.
4. Enter the valid password.
5. Submit the login form.
6. Verify the logged-in customer state.

### Expected Result

The customer should be logged in successfully and the application should display the logged-in customer state.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework


---

**Scenario:** TS-CAM-08 — Invalid Email

## TC-CAM-008 — Login with Invalid Email

### Preconditions

- User is not logged in.
- An invalid or unregistered email address is available.

### Test Data

- Email: Invalid or unregistered email address
- Password: Valid password

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter an invalid or unregistered email address.
4. Enter a valid password.
5. Submit the login form.
6. Observe the application response.

### Expected Result

The application should prevent login and display an appropriate error message.


---

**Scenario:** TS-CAM-09 — Invalid Password

## TC-CAM-009 — Login with Invalid Password

### Preconditions

- User is not logged in.
- A registered customer account exists.

### Test Data

- Email: Registered customer email
- Password: Incorrect password

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter the registered customer email address.
4. Enter an incorrect password.
5. Submit the login form.
6. Observe the application response.

### Expected Result

The application should prevent login and display an appropriate error message.


---

**Scenario:** TS-CAM-10 — Missing Login Credentials

## TC-CAM-010 — Login with Missing Credentials

### Preconditions

- User is not logged in.

### Test Data

- Email: Blank or missing
- Password: Blank or missing

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Leave the email and/or password field blank.
4. Submit the login form.
5. Observe the application response.

### Expected Result

The application should prevent login when required credentials are missing and should handle the missing input appropriately.