# Checkout Test Cases

## TC-CHK-023 — Proceed to Checkout

### Preconditions

- The customer is logged in.
- Products are present in the cart.

### Test Data

- Configured cart.

### Test Steps

1. Open the Cart page.
2. Verify that products are available.
3. Select Proceed To Checkout.
4. Observe the checkout page.

### Expected Result

The customer should be navigated to the checkout page.

### Automation

**Automation Status:** Implemented in SanityE2E

---

**Scenario:** TS-CHK-24 — Delivery Address

## TC-CHK-024 — Verify Delivery Address

### Preconditions

- The customer is logged in.
- Products are available in the cart.
- Checkout is accessible.

### Test Data

- Registered customer address.

### Test Steps

1. Proceed to checkout.
2. Locate the delivery address section.
3. Verify that the customer's address information is displayed.

### Expected Result

The delivery address should be displayed during checkout.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-CHK-25 — Order Review

## TC-CHK-025 — Review Order Before Payment

### Preconditions

- The customer is logged in.
- Products are available in the cart.
- Checkout is accessible.

### Test Data

- Configured products.

### Test Steps

1. Proceed to checkout.
2. Review the order information.
3. Verify the order amount.
4. Continue to payment.

### Expected Result

The customer should be able to review the order before payment.

### Automation

**Automation Status:** Checkout navigation and cart total validation are automated. A separate order-review assertion is not currently implemented.
