# Execution 02 - Product Search

## Execution Overview

**Scenario:** Scenario 02 - Product Search

**Execution Scope:** Product Search

**Execution Objective:**
Validate the product search functionality and verify that the application returns appropriate search results based on the entered search criteria.

---

## Test Execution

### TS 02 PSR 01 - Search Product

#### TC 02 PSR 01 A - Search for a Valid Product

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The search is executed successfully and products relevant to the entered search term are displayed.

**Actual Result:**
The search was executed successfully and relevant products were displayed.

**Defect:**
None

---

#### TC 02 PSR 01 B - Search with a Partial Product Name

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The search is executed successfully and relevant products matching the partial search term are displayed.

**Actual Result:**
The search was executed successfully and relevant products matching the partial search term were displayed.

**Defect:**
None

---

#### TC 02 PSR 01 C - Search with a Non-Existing Product

**Execution Status:** Not Executed

**Result:** Not Executed

**Expected Result:**
The search is executed successfully and no matching products are displayed, or the application provides an appropriate indication that no matching product was found.

**Actual Result:**
*To be updated after execution.*

**Defect:**
*N/A*

---

### TS 02 PSR 02 - Verify Search Results

#### TC 02 PSR 02 A - Verify Searched Product

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The searched product is displayed and matches the search criteria.

**Actual Result:**
The searched product was displayed and matched the search criteria.

**Defect:**
None

---

#### TC 02 PSR 02 B - Open Product from Search Results

**Execution Status:** Executed

**Result:** Passed

**Expected Result:**
The selected product details page is displayed and corresponds to the product selected from the search results.

**Actual Result:**
The selected product details page was displayed and corresponded to the selected product.

**Defect:**
None

---

## Execution Summary

**Total Test Cases:** 5

**Executed:** 4

**Passed:** 4

**Failed:** 0

**Blocked:** 0

**Not Executed:** 1

**Automation Coverage:** 3 / 5

**Automation Coverage Percentage:** 60%

---

## Defects / Observations

No defects were identified during the executed Product Search test cases.

The non-existing product search scenario remains pending execution.
