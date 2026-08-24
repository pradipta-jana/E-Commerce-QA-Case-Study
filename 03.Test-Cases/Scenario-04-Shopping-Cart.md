# Scenario 04 - Shopping Cart

This scenario covers shopping cart functionality, including adding products and validating the product, quantity, price, and cart total.

---

## TS 04 CRT 01 - Add Product to Cart

### TC 04 CRT 01 A - Add a Product to the Cart

**Pre Condition:**

* Application is accessible.
* A valid product is available.
* User is on the product listing or product details page.

**Test Step:**

1. Select the required product.
2. Click the Add to Cart option.
3. Open the shopping cart.

**Expected Output:**

* The selected product is successfully added to the cart.
* The product is displayed in the shopping cart.

**Automation Status:** Automated

---

### TC 04 CRT 01 B - Add Multiple Products to the Cart

**Pre Condition:**

* Application is accessible.
* Multiple valid products are available.

**Test Step:**

1. Select the first product.
2. Add the product to the cart.
3. Select another product.
4. Add the second product to the cart.
5. Open the shopping cart.

**Expected Output:**

* All selected products are successfully added to the cart.
* Each selected product is displayed in the shopping cart.

**Automation Status:** Automated

---

### TC 04 CRT 01 C - Add the Same Product Multiple Times

**Pre Condition:**

* Application is accessible.
* A valid product is available.

**Test Step:**

1. Select the required product.
2. Add the product to the cart.
3. Add the same product again.
4. Open the shopping cart.

**Expected Output:**

* The application handles the repeated product addition correctly.
* The cart reflects the expected product quantity and pricing.

**Automation Status:** Automated

---

## TS 04 CRT 02 - Verify Cart Contents

### TC 04 CRT 02 A - Verify Product in Cart

**Pre Condition:**

* A product has been added to the cart.

**Test Step:**

1. Open the shopping cart.
2. Locate the added product.
3. Verify the displayed product information.

**Expected Output:**

* The correct product is displayed in the cart.
* The displayed product corresponds to the product that was added.

**Automation Status:** Automated

---

### TC 04 CRT 02 B - Verify Product Quantity

**Pre Condition:**

* A product has been added to the cart.

**Test Step:**

1. Open the shopping cart.
2. Verify the quantity displayed for the product.

**Expected Output:**

* The product quantity is displayed correctly.

**Automation Status:** Not Automated

---

### TC 04 CRT 02 C - Verify Product Price

**Pre Condition:**

* A product has been added to the cart.

**Test Step:**

1. Open the shopping cart.
2. Verify the displayed product price.

**Expected Output:**

* The product price displayed in the cart is correct.

**Automation Status:** Automated

---

### TC 04 CRT 02 D - Verify Cart Total

**Pre Condition:**

* One or more products have been added to the cart.

**Test Step:**

1. Open the shopping cart.
2. Review the product prices and quantities.
3. Verify the displayed cart total.

**Expected Output:**

* The cart total is calculated and displayed correctly based on the products and quantities in the cart.

**Automation Status:** Automated

---
