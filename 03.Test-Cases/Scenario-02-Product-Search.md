# Scenario 02 - Product Search

This scenario covers product search functionality and validation of the returned search results.

---

## TS 02 PSR 01 - Search Product

### TC 02 PSR 01 A - Search for a Valid Product

**Pre Condition:**

* Application is accessible.
* User is on the Products page.
* A valid product name is available for search.

**Test Step:**

1. Navigate to the Products page.
2. Enter a valid product name in the search field.
3. Click the Search button.

**Expected Output:**

* The search is executed successfully.
* Products relevant to the entered search term are displayed.

**Automation Status:** Automated

---

### TC 02 PSR 01 B - Search with a Partial Product Name

**Pre Condition:**

* Application is accessible.
* User is on the Products page.
* A valid partial product name is available.

**Test Step:**

1. Navigate to the Products page.
2. Enter a partial product name in the search field.
3. Click the Search button.

**Expected Output:**

* The search is executed successfully.
* Relevant products matching the search term are displayed.

**Automation Status:** Not Automated

---

### TC 02 PSR 01 C - Search with a Non-Existing Product

**Pre Condition:**

* Application is accessible.
* User is on the Products page.
* A product name that does not exist in the catalogue is available.

**Test Step:**

1. Navigate to the Products page.
2. Enter a non-existing product name in the search field.
3. Click the Search button.

**Expected Output:**

* The search is executed successfully.
* No matching products are displayed, or the application provides an appropriate indication that no matching product was found.

**Automation Status:** Not Automated

---

## TS 02 PSR 02 - Verify Search Results

### TC 02 PSR 02 A - Verify Searched Product

**Pre Condition:**

* A valid product search has been performed.
* Search results are displayed.

**Test Step:**

1. Review the displayed search results.
2. Locate the searched product.
3. Compare the displayed product with the search criteria.

**Expected Output:**

* The searched product is displayed.
* The displayed product matches the search criteria.

**Automation Status:** Automated

---

### TC 02 PSR 02 B - Open Product from Search Results

**Pre Condition:**

* A valid product search has been performed.
* Search results are displayed.

**Test Step:**

1. Locate the required product in the search results.
2. Select the product.

**Expected Output:**

* The selected product details page is displayed.
* The displayed product corresponds to the product selected from the search results.

**Automation Status:** Automated

---
