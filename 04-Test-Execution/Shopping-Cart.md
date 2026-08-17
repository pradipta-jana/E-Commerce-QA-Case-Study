# Shopping Cart Test Execution

## TC-CART-017 — Add Multiple Products to Cart

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework reads the configured product names and quantities from Excel:

- Blue Top — 2
- Men Tshirt — 3

The E2E test then searches for each product, retrieves its price, sets the requested quantity and adds it to the cart.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run because the suite failed during initial application navigation.

---

## TC-CART-020 — Verify Cart Total

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework calculates:

`Expected Total = Σ(Product Price × Quantity)`

It then reads the cart total from the application and compares the actual and expected values using an assertion.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.

---

## TC-CART-022 — Verify Empty Cart

**Execution Type:** Automation  
**Automation Suite:** SanityE2E  
**Framework:** AutomationFramework

### Execution Evidence

The framework removes existing cart items before adding the configured products and explicitly verifies the empty-cart state.

### Current Status

**Automation Coverage:** Implemented

**Latest Suite Status:** Not independently validated in the supplied latest Surefire run.
