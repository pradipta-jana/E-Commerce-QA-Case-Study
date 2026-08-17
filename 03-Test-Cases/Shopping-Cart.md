# Shopping Cart Test Cases

## TC-CART-016 — Add Product to Cart

### Preconditions

- A valid product is available.
- The customer can access the product details page.

### Test Data

- Product: Blue Top
- Quantity: 2

### Test Steps

1. Open the Products page.
2. Search for the product.
3. Open the product details.
4. Set quantity to 2.
5. Add the product to the cart.
6. Open the Cart page.
7. Verify the product and quantity.

### Expected Result

The selected product should be added to the cart with the requested quantity.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-CART-17 — Add Multiple Products

## TC-CART-017 — Add Multiple Products to Cart

### Preconditions

- The configured products are available.
- Test data is available in Excel.

### Test Data

| Product | Quantity |
|---|---:|
| Blue Top | 2 |
| Men Tshirt | 3 |

### Test Steps

1. Clear any existing cart items.
2. Read the configured product data.
3. Search for the first product.
4. Set its quantity.
5. Add it to the cart.
6. Repeat for the second product.
7. Open the Cart page.
8. Verify that the configured products are present.

### Expected Result

The configured products should be added to the cart with their requested quantities.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-CART-18 — Add Product with Required Quantity

## TC-CART-018 — Add Product with Required Quantity

### Preconditions

- A valid product is available.

### Test Data

- Product: Blue Top
- Quantity: 2

### Test Steps

1. Open the product details.
2. Enter quantity 2.
3. Add the product to the cart.
4. Open the Cart page.
5. Verify the displayed quantity.

### Expected Result

The cart should contain the product with the requested quantity.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-CART-19 — Verify Product Price

## TC-CART-019 — Verify Product Price

### Preconditions

- A product has been added to the cart.

### Test Data

- Product: Blue Top

### Test Steps

1. Open the product details.
2. Read the displayed product price.
3. Add the product to the cart.
4. Open the Cart page.
5. Compare the product price with the selected product price.

### Expected Result

The product price in the cart should match the selected product price.

### Automation

**Automation Status:** Price is retrieved by automation; direct cart-line price assertion is not currently implemented.

---

**Scenario:** TS-CART-20 — Verify Cart Total

## TC-CART-020 — Verify Cart Total

### Preconditions

- The configured products are available.
- The cart can be opened.

### Test Data

| Product | Quantity |
|---|---:|
| Blue Top | 2 |
| Men Tshirt | 3 |

### Test Steps

1. Clear any existing cart items.
2. Read product names and quantities from Excel.
3. Search for each configured product.
4. Retrieve the product price.
5. Calculate expected total as price × quantity.
6. Add each product to the cart.
7. Open the Cart page.
8. Retrieve the displayed cart total.
9. Compare actual and expected totals.

### Expected Result

The displayed cart total should match the calculated expected total.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

---

**Scenario:** TS-CART-21 — Remove Product

## TC-CART-021 — Remove Product from Cart

### Preconditions

- At least one product exists in the cart.

### Test Data

- Existing cart product.

### Test Steps

1. Open the Cart page.
2. Select the remove action for a cart item.
3. Observe the cart.
4. Verify that the selected item is no longer present.

### Expected Result

The selected product should be removed from the cart.

### Automation

**Automation Status:** Cart deletion is implemented as a reusable framework operation and is used to clear the cart before the E2E flow. A standalone remove-product assertion is not currently implemented.

---

**Scenario:** TS-CART-22 — Verify Empty Cart

## TC-CART-022 — Verify Empty Cart

### Preconditions

- One or more products exist in the cart.

### Test Data

- Existing cart items.

### Test Steps

1. Open the Cart page.
2. Remove the existing cart items.
3. Verify the empty-cart message/state.

### Expected Result

The application should display the expected empty-cart state.

### Automation

**Automation Status:** Automated  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework
