# Payment Test Execution

## TC-PAY-026 — Enter Payment Details

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

PaymentPage provides reusable methods for:

- Cardholder name
- Card number
- CVC
- Expiry month
- Expiry year

The Sanity E2E test obtains the values from configuration properties and enters them into the payment form.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.

---

## TC-PAY-027 — Submit Payment

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework invokes `clickPayAndConfirmOrder()` after entering the configured payment information.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.

---

## TC-PAY-028 — Verify Payment and Order Confirmation

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework retrieves the order confirmation message and asserts that it matches `Order Placed!`.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.
