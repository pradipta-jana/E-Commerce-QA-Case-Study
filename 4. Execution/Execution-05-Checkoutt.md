# Execution 05 - Checkout

## Execution Overview

**Scenario:** Scenario 05 - Checkout

**Execution Scope:** Checkout

**Execution Objective:**
Validate the checkout process, including navigation from the shopping cart, verification of checkout information, order summary, and progression toward the payment/order completion stage.

---

## Test Execution

### TS 05 CHK 01 - Navigate to Checkout

#### TC 05 CHK 01 A - Proceed to Checkout with Product in Cart

**Automation Status:** Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The user is successfully navigated to the checkout page and checkout information is displayed.

**Actual Result:**
The user was successfully navigated to the checkout page and the checkout information was displayed correctly.

**Defect:**
N/A

---

#### TC 05 CHK 01 B - Verify Checkout Product Details

**Automation Status:** Not Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The checkout summary displays the correct product, quantity, and price matching the cart information.

**Actual Result:**
The checkout summary displayed the correct product, quantity, and price matching the cart information.

**Defect:**
N/A

---

### TS 05 CHK 02 - Verify Checkout Information

#### TC 05 CHK 02 A - Verify Delivery Address

**Automation Status:** Not Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The delivery address is displayed correctly and corresponds to the authenticated user's information.

**Actual Result:**
The delivery address was displayed correctly and matched the authenticated user's information.

**Defect:**
N/A

---

#### TC 05 CHK 02 B - Verify Billing Address

**Automation Status:** Not Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The billing address is displayed correctly and corresponds to the user's account information.

**Actual Result:**
The billing address was displayed correctly and matched the user's account information.

**Defect:**
N/A

---

#### TC 05 CHK 02 C - Verify Order Summary

**Automation Status:** Automated

**Execution Status:** Not Executed

**Result:** Not Executed

**Expected Result:**
The order summary displays the correct product, quantity, product price, and total amount.

**Actual Result:**
Not Executed.

**Defect:**
N/A

---

### TS 05 CHK 03 - Complete Checkout

#### TC 05 CHK 03 A - Enter Order Comments

**Automation Status:** Not Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The comment is accepted successfully and the entered information is retained before proceeding with the order.

**Actual Result:**
The order comment was accepted successfully and the entered information was retained before proceeding with the order.

**Defect:**
N/A

---

#### TC 05 CHK 03 B - Proceed from Checkout to Payment

**Automation Status:** Automated

**Execution Status:** Executed

**Result:** Pass

**Expected Result:**
The user is successfully navigated to the payment/order completion stage and the selected product and order information are retained.

**Actual Result:**
The user was successfully navigated from checkout to the payment/order completion stage, and the selected product and order information were retained.

**Defect:**
N/A

---

## Execution Summary

**Total Test Cases:** 7

**Executed:** 6

**Passed:** 6

**Failed:** 0

**Blocked:** 0

**Not Executed:** 1

**Automation Mapping:** 3 / 7

**Automation Mapping Percentage:** 42.86%

---

## Defects / Observations

No execution defects or observations were identified for the executed test cases.
