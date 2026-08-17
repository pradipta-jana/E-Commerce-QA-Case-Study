# Payment Test Cases

## TC-PAY-026 — Enter Payment Details

### Preconditions

- The customer has reached the payment page.
- A test payment dataset is available.

### Test Data

- Cardholder Name: Configured test value
- Card Number: Configured test value
- CVC: Configured test value
- Expiry Month: Configured test value
- Expiry Year: Configured test value

### Test Steps

1. Enter the cardholder name.
2. Enter the card number.
3. Enter the CVC.
4. Enter the expiry month.
5. Enter the expiry year.
6. Verify that the payment details are accepted by the form.

### Expected Result

The payment form should accept the configured test payment information.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-PAY-27 — Submit Payment

## TC-PAY-027 — Submit Payment

### Preconditions

- Required payment information has been entered.
- The order is ready for payment.

### Test Data

- Configured test payment dataset.

### Test Steps

1. Enter the required payment details.
2. Select Pay and Confirm Order.
3. Wait for the application response.

### Expected Result

The payment should be submitted and the application should proceed to order confirmation.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-PAY-28 — Payment Confirmation

## TC-PAY-028 — Verify Payment and Order Confirmation

### Preconditions

- Payment has been submitted successfully.

### Test Data

- Configured test payment dataset.

### Test Steps

1. Submit the payment.
2. Read the order confirmation message.
3. Compare the message with the expected value.

### Expected Result

The application should display `Order Placed!` after successful payment and order placement.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework
