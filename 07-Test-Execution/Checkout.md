# Checkout Test Execution

## TC-CHK-023 — Proceed to Checkout

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The CartPage implementation provides checkout navigation and the Sanity E2E flow invokes it after adding the configured products.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.

---

## TC-CHK-024 — Verify Delivery Address

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework verifies the delivery-address section using `isDeliveryAddressDisplayed()` after navigating to checkout.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.

---

## TC-CHK-025 — Review Order Before Payment

**Execution Type:** Automation / Partial Assertion

### Execution Evidence

The framework navigates to checkout and validates the cart total and delivery address before placing the order.

### Current Status

**Automation Coverage:** Partial

A dedicated order-review assertion is not currently implemented.
