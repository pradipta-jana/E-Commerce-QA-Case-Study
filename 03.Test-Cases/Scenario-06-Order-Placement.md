# Scenario 06 - Order Placement

This scenario covers the order placement process, including payment information, order submission, and successful completion of the purchase.

---

## TS 06 ORD 01 - Enter Payment Information

### TC 06 ORD 01 A - Enter Valid Payment Details

**Pre Condition:**

* User is logged in.
* User has completed the checkout process.
* User is on the payment page.

**Test Step:**

1. Enter a valid card name.
2. Enter a valid card number.
3. Enter a valid CVC.
4. Enter a valid expiry month.
5. Enter a valid expiry year.

**Expected Output:**

* All payment information is accepted successfully.
* User can proceed with placing the order.

**Automation Status:** Automated

---

### TC 06 ORD 01 B - Submit Payment with Missing Payment Details

**Pre Condition:**

* User is logged in.
* User has completed the checkout process.
* User is on the payment page.

**Test Step:**

1. Leave one or more required payment fields empty.
2. Attempt to submit the payment.

**Expected Output:**

* The order is not placed.
* The application performs appropriate validation for the missing payment information.

**Automation Status:** Not Automated

---

## TS 06 ORD 02 - Place Order

### TC 06 ORD 02 A - Place Order with Valid Payment Details

**Pre Condition:**

* User is logged in.
* User has completed checkout.
* Valid payment information has been entered.

**Test Step:**

1. Review the payment information.
2. Submit the payment/order.
3. Wait for the order processing to complete.

**Expected Output:**

* The order is successfully placed.
* The application proceeds to the order confirmation state.

**Automation Status:** Automated

---

### TC 06 ORD 02 B - Prevent Order Placement with Invalid Payment Details

**Pre Condition:**

* User is logged in.
* User has completed checkout.
* Invalid payment information is available.

**Test Step:**

1. Enter invalid payment information.
2. Attempt to submit the payment/order.

**Expected Output:**

* The application handles the invalid payment information appropriately.
* The order is not incorrectly confirmed as successfully placed.

**Automation Status:** Not Automated

---

## TS 06 ORD 03 - Order Completion

### TC 06 ORD 03 A - Verify Order Placement Completion

**Pre Condition:**

* User has submitted a valid order.
* Order processing has completed.

**Test Step:**

1. Complete the order placement process.
2. Review the resulting application state.

**Expected Output:**

* The application indicates that the order placement process has completed successfully.
* The user can proceed to verify the placed order.

**Automation Status:** Automated

---
