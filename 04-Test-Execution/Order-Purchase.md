# Order & Purchase Test Execution

## TC-ORD-029 — Place Order

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The Sanity E2E flow completes checkout, enters payment information and invokes the Pay and Confirm Order action.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** FAIL

The supplied latest Surefire execution failed during initial application navigation before the order flow could execute.

---

## TC-ORD-030 — Verify Order Confirmation

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework contains an assertion against the application order confirmation message:

`Order Placed!`

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not reached in the supplied latest Surefire run.

---

## TC-ORD-031 — Download Invoice

**Execution Type:** Not Automated

### Current Status

**Automation Coverage:** Not Automated

Invoice download validation is documented as a future automation enhancement.
