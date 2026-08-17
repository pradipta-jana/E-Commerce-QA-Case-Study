# Customer Account Management Requirements — Execution

## Customer Registration

# Customer Registration Test Execution

**Requirement:** REQ-CAM-01 — Customer Registration  
**Jira:** [KAN-7](https://pradipta-qa-portfolio.atlassian.net/browse/KAN-7)

## TC-CAM-001 — Successful Customer Registration

**Execution Type:** Manual  
**Result:** PASS

### Execution Summary

The successful customer registration scenario was manually executed against the Automation Exercise application.

The registration workflow completed successfully and the expected account creation and logged-in states were verified.

### Result

**PASS** ✅

### Automation Status

**Not Automated**

The scenario is currently covered through manual testing. Automation may be considered in a future enhancement based on automation priority and framework coverage.

## Customer Login

# Customer Login Test Execution

**Requirement:** REQ-CAM-03 — Customer Login  
**Jira:** [KAN-9](https://pradipta-qa-portfolio.atlassian.net/browse/KAN-9)

## TC-CAM-007 — Successful Customer Login

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework  
**Result:** PASS

### Execution Summary

The successful customer login scenario was executed as part of the existing Sanity E2E automation suite.

The test successfully:

1. Opened the Signup/Login page.
2. Submitted valid registered customer credentials.
3. Logged in successfully.
4. Verified the logged-in customer state.

### Result

**PASS** ✅

The login flow completed successfully and the expected logged-in state was verified.
