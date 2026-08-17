# Order & Purchase Test Cases

## TC-ORD-029 — Place Order

### Preconditions

- The customer is logged in.
- Products are present in the cart.
- Checkout is accessible.
- Test payment data is available.

### Test Data

- Configured products.
- Configured payment details.

### Test Steps

1. Proceed from the Cart page to checkout.
2. Verify the delivery address.
3. Continue to payment.
4. Enter payment details.
5. Submit payment.
6. Observe the order state.

### Expected Result

The configured order should be submitted successfully.

### Automation

**Automation Status:** Implemented in SanityE2E

---

**Scenario:** TS-ORD-30 — Order Confirmation

## TC-ORD-030 — Verify Order Confirmation

### Preconditions

- The order has been submitted.

### Test Data

- Configured order.

### Test Steps

1. Submit payment.
2. Read the confirmation message.
3. Verify the displayed confirmation.

### Expected Result

The application should display `Order Placed!`.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-ORD-31 — Download Invoice

## TC-ORD-031 — Download Invoice

### Preconditions

- A customer order has been placed successfully.
- An invoice is available.

### Test Data

- Successfully placed order.

### Test Steps

1. Complete an order.
2. Navigate to the relevant order/invoice area.
3. Select the invoice download option.
4. Verify that the invoice is downloaded.
5. Verify that the downloaded file is available.

### Expected Result

The invoice should be downloaded successfully.

### Automation

**Automation Status:** Not Automated

The current AutomationFramework does not implement invoice download validation.
