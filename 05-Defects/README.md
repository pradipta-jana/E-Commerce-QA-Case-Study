# Defect Management

## Current Case Study Status

No application defect has been invented for this case study without execution evidence.

The supplied latest automation execution does contain a **framework/execution issue**, not an application functional defect:

### Automation Execution Issue

**Exception:** `NoSuchWindowException`

**Failure Location:** `SeleniumUtils.closeAdIfPresent()` during `HomePage.clickSignupLogin()`

**Impact:** The Sanity E2E test stops before the login/product/cart/checkout/payment flow executes.

**Classification:** Automation Framework / Test Infrastructure

**Not classified as:** Application defect

### Why it is documented

A QA portfolio should distinguish between:

- Application defects
- Automation defects
- Environment/infrastructure failures
- Test-data issues

This case is retained as execution evidence and should be addressed in the framework before claiming a fresh end-to-end PASS.
