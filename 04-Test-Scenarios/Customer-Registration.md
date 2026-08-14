# Customer Registration Test Scenarios

**Requirement:** REQ-CAM-01 — Customer Registration  
**Jira:** [KAN-7](https://pradipta-qa-portfolio.atlassian.net/browse/KAN-7)

### TS-CAM-01 — Successful Registration

Verify that a new customer can complete the registration process using valid information and successfully create an account.

### TS-CAM-02 — Missing Required Information

Verify that the registration process handles missing required information appropriately.

### TS-CAM-03 — Existing Email Address

Verify that registration is prevented when an email address already associated with an account is used.

### TS-CAM-04 — Invalid Email Format

Verify that the registration process handles an incorrectly formatted email address appropriately.

### TS-CAM-05 — Account Creation Confirmation

Verify that the application displays the account creation confirmation after successful registration.

**Covered by:** TC-CAM-001 — Successful Customer Registration

### TS-CAM-06 — Login State After Registration

Verify that the customer is logged in after successful registration and the logged-in customer state is displayed.

**Covered by:** TC-CAM-001 — Successful Customer Registration