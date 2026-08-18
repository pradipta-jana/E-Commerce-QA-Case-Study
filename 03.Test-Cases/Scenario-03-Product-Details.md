# Scenario 03 - Product Details

This scenario covers validation of product information and the user's ability to proceed from the product details page toward the shopping cart.

---

## TS 03 PDT 01 - Verify Product Details

### TC 03 PDT 01 A - Verify Product Name

**Pre Condition:**

* Application is accessible.
* User is on the Products page.
* A product is available in the product listing.

**Test Step:**

1. Select a product from the product listing.
2. Open the product details page.
3. Verify the product name.

**Expected Output:**

* The product details page is displayed.
* The product name is displayed correctly.

**Automation Status:** Not Automated

---

### TC 03 PDT 01 B - Verify Product Price

**Pre Condition:**

* Product details page is displayed.

**Test Step:**

1. Review the product details.
2. Verify the displayed product price.

**Expected Output:**

* The product price is displayed correctly.

**Automation Status:** Automated

---

### TC 03 PDT 01 C - Verify Product Category and Availability

**Pre Condition:**

* Product details page is displayed.

**Test Step:**

1. Review the product information.
2. Verify the product category.
3. Verify the product availability.

**Expected Output:**

* The product category is displayed correctly.
* The product availability information is displayed correctly.

**Automation Status:** Not Automated

---

### TC 03 PDT 01 D - Verify Product Information

**Pre Condition:**

* Product details page is displayed.

**Test Step:**

1. Review the available product information.
2. Verify the displayed product details.

**Expected Output:**

* Relevant product information is displayed correctly.
* The information corresponds to the selected product.

**Automation Status:** Not Automated

---

## TS 03 PDT 02 - Navigate from Product Details to Cart

### TC 03 PDT 02 A - Add Product to Cart from Product Details

**Pre Condition:**

* Product details page is displayed.
* A valid product is available.

**Test Step:**

1. Select the required product.
2. Click the Add to Cart option.
3. Proceed to the cart.

**Expected Output:**

* The selected product is successfully added to the cart.
* The user can proceed to the cart.

**Automation Status:** Automated

---

### TC 03 PDT 02 B - Verify Selected Product in Cart

**Pre Condition:**

* A product has been added to the cart from the product details page.

**Test Step:**

1. Open the shopping cart.
2. Locate the added product.
3. Compare the product with the product selected from the Product Details page.

**Expected Output:**

* The selected product is displayed in the cart.
* The product displayed in the cart corresponds to the selected product.

**Automation Status:** Automated

---
