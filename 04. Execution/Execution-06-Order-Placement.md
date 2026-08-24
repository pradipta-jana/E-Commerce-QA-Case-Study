# Execution 06 - Order Placement

## Execution Overview

**Scenario:** Scenario 06 - Order Placement

**Execution Scope:** Order Placement

**Execution Objective:**
Validate the order placement process, including payment information, order submission, and successful completion of the purchase.

---

## Test Execution

### TS 06 ORD 01 - Enter Payment Information

#### TC 06 ORD 01 A - Enter Valid Payment Details

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
All payment information is accepted successfully and the user can proceed with placing the order.

**Actual Result:**
Valid payment information was accepted successfully and the user was able to proceed with placing the order.

**Defect:**
None

---

#### TC 06 ORD 01 B - Submit Payment with Missing Payment Details

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The order is not placed and the application performs appropriate validation for the missing payment information.

**Actual Result:**
The application handled the missing payment information appropriately and the order was not incorrectly placed.

**Defect:**
None

---

### TS 06 ORD 02 - Place Order

#### TC 06 ORD 02 A - Place Order with Valid Payment Details

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The order is successfully placed and the application proceeds to the order confirmation state.

**Actual Result:**
The order was successfully placed and the application proceeded to the order confirmation state.

**Defect:**
None

---

#### TC 06 ORD 02 B - Prevent Order Placement with Invalid Payment Details

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The application handles the invalid payment information appropriately and the order is not incorrectly confirmed as successfully placed.

**Actual Result:**
The application handled the invalid payment information appropriately and the order was not incorrectly confirmed as successfully placed.

**Defect:**
None

---

### TS 06 ORD 03 - Order Completion

#### TC 06 ORD 03 A - Verify Order Placement Completion

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The application indicates that the order placement process has completed successfully and the user can proceed to verify the placed order.

**Actual Result:**
The application indicated successful completion of the order placement process and the user was able to proceed to verify the placed order.

**Defect:**
None

---

## Execution Summary

**Total Test Cases:** 5

**Executed:** 5

**Passed:** 5

**Failed:** 0

**Blocked:** 0

**Not Executed:** 0

**Automation Coverage:** 3 / 5

**Automation Coverage Percentage:** 60%

---

## Defects / Observations

No defects were identified during the execution of the Order Placement test cases.

All five test cases were executed successfully.
