# Scenario 05 - Checkout

This scenario covers the checkout process, including navigation from the shopping cart, verification of checkout information, and completion of the checkout details before order placement.

---

## TS 05 CHK 01 - Navigate to Checkout

### TC 05 CHK 01 A - Proceed to Checkout with Product in Cart

**Pre Condition:**

* User is logged in.
* At least one product is available in the shopping cart.

**Test Step:**

1. Open the shopping cart.
2. Review the cart contents.
3. Click the Proceed to Checkout option.

**Expected Output:**

* The user is successfully navigated to the checkout page.
* Checkout information is displayed.

**Automation Status:** Automated

---

### TC 05 CHK 01 B - Verify Checkout Product Details

**Pre Condition:**

* User is on the checkout page.
* Product has been added to the cart.

**Test Step:**

1. Review the product displayed in the checkout summary.
2. Verify the product information.
3. Verify the product quantity.
4. Verify the product price.

**Expected Output:**

* The checkout summary displays the correct product.
* The product quantity and price match the cart information.

**Automation Status:** Not Automated

---

## TS 05 CHK 02 - Verify Checkout Information

### TC 05 CHK 02 A - Verify Delivery Address

**Pre Condition:**

* User is logged in.
* User has a valid account with registered address information.
* User is on the checkout page.

**Test Step:**

1. Review the delivery address displayed on the checkout page.
2. Compare the displayed information with the registered user information.

**Expected Output:**

* The delivery address is displayed correctly.
* The address corresponds to the authenticated user's information.

**Automation Status:** Not Automated

---

### TC 05 CHK 02 B - Verify Billing Address

**Pre Condition:**

* User is logged in.
* User is on the checkout page.

**Test Step:**

1. Review the billing address displayed on the checkout page.
2. Verify the displayed address information.

**Expected Output:**

* The billing address is displayed correctly.
* The displayed information corresponds to the user's account information.

**Automation Status:** Not Automated

---

### TC 05 CHK 02 C - Verify Order Summary

**Pre Condition:**

* User is on the checkout page.
* Product has been added to the cart.

**Test Step:**

1. Review the order summary.
2. Verify the selected product.
3. Verify the quantity.
4. Verify the product price.
5. Verify the total amount.

**Expected Output:**

* The order summary displays the correct product and quantity.
* Product pricing and the total amount are displayed correctly.

**Automation Status:** Automated

---

## TS 05 CHK 03 - Complete Checkout

### TC 05 CHK 03 A - Enter Order Comments

**Pre Condition:**

* User is logged in.
* User is on the checkout page.
* Product is available in the order summary.

**Test Step:**

1. Enter a valid comment or order instruction in the available comment field.
2. Verify the entered information.

**Expected Output:**

* The comment is accepted successfully.
* The entered information is retained before proceeding with the order.

**Automation Status:** Not Automated

---

### TC 05 CHK 03 B - Proceed from Checkout to Payment

**Pre Condition:**

* User is logged in.
* Checkout information is displayed correctly.
* Product is available in the order summary.

**Test Step:**

1. Review the checkout information.
2. Review the order summary.
3. Click the appropriate option to proceed with the order.

**Expected Output:**

* The user is successfully navigated to the payment/order completion stage.
* The selected product and order information are retained.

**Automation Status:** Automated

---
