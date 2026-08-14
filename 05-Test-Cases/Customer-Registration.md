# Customer Registration Test Cases

**Requirement:** REQ-CAM-01 — Customer Registration  
**Jira:** [KAN-7](https://pradipta-qa-portfolio.atlassian.net/browse/KAN-7)  
**Scenario:** TS-CAM-01 — Successful Registration

## TC-CAM-001 — Successful Customer Registration

### Preconditions

- User is not logged in.
- A unique email address is available for registration.

### Test Data

- Customer Name: Test Customer
- Email: Unique email address
- Password: Valid password
- Other required registration details: Valid values

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter a unique customer name and email address.
4. Submit the signup form.
5. Enter the required account and personal information.
6. Submit the registration form.
7. Verify the account creation confirmation.
8. Verify that the customer is logged in after successful registration.

### Expected Result

The customer account should be created successfully, the application should display the account creation confirmation, and the customer should be logged in.

---


**Scenario:** TS-CAM-02 — Missing Required Information

## TC-CAM-002 — Registration with Missing Required Information

### Preconditions

- User is not logged in.
- A unique email address is available for registration.

### Test Data

- Customer Name: Test Customer
- Email: Unique email address
- Password: Valid password
- One or more required registration fields: Blank
- Remaining required fields: Valid values

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter a unique customer name and email address.
4. Submit the signup form.
5. Leave one or more required registration fields blank.
6. Enter valid values in the remaining required fields.
7. Submit the registration form.
8. Observe the application behavior.

### Expected Result

The application should prevent completion of the registration when required information is missing and should indicate the missing information appropriately.

---

**Scenario:** TS-CAM-03 — Existing Email Address

## TC-CAM-003 — Registration with Existing Email

### Preconditions

- User is not logged in.
- An email address that is already registered in the application is available.

### Test Data

- Customer Name: Test Customer
- Email: Existing registered email address
- Password: Valid password

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter a customer name and an already registered email address.
4. Submit the signup form.
5. Observe the application response.

### Expected Result

The application should prevent registration using the existing email address and display an appropriate error message.

---

**Scenario:** TS-CAM-04 — Invalid Email Format

## TC-CAM-004 — Registration with Invalid Email Format

### Preconditions

- User is not logged in.
- A test email address with an invalid format is available.

### Test Data

- Customer Name: Test Customer
- Email: Invalid email format
- Password: Valid password

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Signup/Login page.
3. Enter a customer name and an invalid email address.
4. Submit the signup form.
5. Observe the application response.

### Expected Result

The application should prevent registration when an invalid email format is provided and should indicate that the email address is invalid.

