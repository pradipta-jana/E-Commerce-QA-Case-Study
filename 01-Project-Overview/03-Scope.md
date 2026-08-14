# Scope

## 1. In Scope

The QA Case Study covers selected business-critical workflows of the Automation Exercise eCommerce application.

### Customer Account Management
- Registration
- Existing email validation
- Login
- Invalid login validation
- Logout
- Account deletion

### Product Discovery
- Product listing
- Product search
- Product details
- Category browsing
- Brand browsing

### Shopping Cart
- Add product
- Add multiple products
- Product quantity
- Product price
- Cart total
- Remove product
- Empty cart

### Checkout
- Proceed to checkout
- Delivery address
- Order review

### Payment
- Enter payment details
- Submit payment
- Payment/order confirmation

### Order & Purchase
- Place order
- Order confirmation
- Invoice download

## 2. Testing Scope

The case study demonstrates:

- Requirement analysis
- Functional Testing
- Positive Testing
- Negative Testing
- Regression Testing
- End-to-End Testing
- UI Automation Testing
- Test Data Management
- Defect Management
- Test Execution and Reporting
- Requirement-to-test traceability

## 3. Out of Scope

- Performance Testing
- Security Testing
- Accessibility Testing
- Exhaustive Cross-Browser Testing
- Mobile Application Testing
- API Testing
- Database/SQL validation

## 4. Automation Boundary

The case study intentionally separates **documented functional scope** from **currently automated scope**.

The current AutomationFramework provides automation for the core Sanity E2E path:

```text
Login
  ↓
Product Search / Details
  ↓
Cart Clear
  ↓
Excel-driven Product Addition
  ↓
Cart Total Validation
  ↓
Delivery Address Validation
  ↓
Payment
  ↓
Order Confirmation
  ↓
Logout
```

Some documented scenarios remain manual or partially automated, including category/brand browsing, dedicated negative cases, invoice download and standalone order-review assertions.

## 5. Scope Boundary

The objective is not complete application coverage. The objective is to demonstrate a practical QA Engineering lifecycle with defensible traceability and a realistic automation boundary.
