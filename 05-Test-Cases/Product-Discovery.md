# Product Discovery Test Cases

## TC-PROD-011 — Product Listing

### Preconditions

- The application is accessible.
- The customer can navigate to the Products page.

### Test Data

- Available product catalogue.

### Test Steps

1. Navigate to the Automation Exercise application.
2. Open the Products page.
3. Observe the product listing.
4. Verify that products are displayed.

### Expected Result

The Products page should display available products.

---

**Scenario:** TS-PROD-12 — Successful Product Search

## TC-PROD-012 — Successful Product Search

### Preconditions

- The Products page is accessible.
- A valid product name is available.

### Test Data

- Product: Blue Top

### Test Steps

1. Navigate to the Products page.
2. Enter `Blue Top` in the product search field.
3. Submit the search.
4. Verify that a matching product is displayed.
5. Open the product details.

### Expected Result

The matching product should be displayed and its details page should be accessible.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-PROD-13 — Product Details

## TC-PROD-013 — View Product Details and Price

### Preconditions

- A valid product is available.

### Test Data

- Product: Blue Top

### Test Steps

1. Search for the product.
2. Verify that the product is displayed.
3. Open the product details.
4. Read the displayed product price.

### Expected Result

The selected product details should be displayed and the product price should be retrievable.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-PROD-14 — Product Category Browsing

## TC-PROD-014 — Browse Products by Category

### Preconditions

- The Products page is accessible.
- At least one category is available.

### Test Data

- Available product category.

### Test Steps

1. Open the Products page.
2. Select an available category.
3. Observe the displayed products.
4. Verify that the products correspond to the selected category.

### Expected Result

Products belonging to the selected category should be displayed.

### Automation

**Automation Status:** Not Automated

---

**Scenario:** TS-PROD-15 — Product Brand Browsing

## TC-PROD-015 — Browse Products by Brand

### Preconditions

- The Products page is accessible.
- At least one brand is available.

### Test Data

- Available product brand.

### Test Steps

1. Open the Products page.
2. Select an available brand.
3. Observe the displayed products.
4. Verify that the products correspond to the selected brand.

### Expected Result

Products belonging to the selected brand should be displayed.

### Automation

**Automation Status:** Not Automated
