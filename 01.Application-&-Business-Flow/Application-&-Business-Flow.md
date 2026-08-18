## Application & Business Flow

### Application Under Test

**Application:** Automation Exercise

**Domain:** eCommerce

**Type:** Web Application

**URL:** https://automationexercise.com/

Automation Exercise is an eCommerce web application used for practicing software testing. The application provides functionality around user authentication, product browsing and search, shopping cart management, checkout, and order placement.

For this case study, the testing scope focuses on the core customer purchase journey across these application areas.

### Business Flow

The selected end-to-end business flow represents a typical customer purchase journey:

**Login → Search Product → Product Details → Add to Cart → Verify Cart → Checkout → Place Order → Verify Order → Logout**

The flow validates the interaction between multiple application areas rather than testing each feature in isolation.

The journey covers:

* **Login** - Authenticate an existing customer.
* **Search Product** - Find the required product.
* **Product Details** - Verify the selected product information.
* **Add to Cart** - Add the selected product to the shopping cart.
* **Verify Cart** - Validate the product and cart information.
* **Checkout** - Proceed through the checkout process.
* **Place Order** - Complete the purchase.
* **Verify Order** - Confirm successful order placement.
* **Logout** - End the authenticated user session.

This business flow was selected because it represents a complete and meaningful customer journey while allowing multiple application components to be validated as part of a single end-to-end scenario.
