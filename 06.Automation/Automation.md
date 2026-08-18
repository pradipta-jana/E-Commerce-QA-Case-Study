# Automation Objective

The objective of automation is to validate high-value, repeatable, and stable application workflows that are suitable for regression testing.

The current automation implementation focuses primarily on the end-to-end shopping journey, covering authentication, product search, product validation, cart operations, checkout, order placement, and order confirmation.

### Automation Repository: [Automation Framework](https://github.com/pradipta-jana/AutomationFramework)

## Autumation Status

#### Automated

* Customer login
* Product search
* Product availability validation
* Product details navigation
* Product price retrieval
* Cart clearing
* Multiple product addition
* Excel-driven quantity
* Expected cart total calculation
* Actual cart total validation
* Delivery address validation
* Payment form entry
* Payment submission
* Order confirmation
* Logout flow

#### Partially Automated / Manual

* Product category browsing
* Product brand browsing
* Dedicated product-price-in-cart assertion
* Standalone remove-product test
* Dedicated order-review assertion
* Negative login scenarios
* Invoice download

# Selenium Automation Framework

A modular Selenium automation framework built using **Java, Selenium WebDriver, TestNG and Maven**.

The framework demonstrates practical automation concepts such as **Page Object Model, reusable utilities, configuration management, test data handling, logging and reporting**.

## Tools & Technologies

* Java
* Selenium WebDriver
* TestNG
* Maven
* Apache POI
* Log4j2
* Extent Reports

## Framework Structure

```text
Test Layer
    ↓
Page Object Layer
    ↓
Utility Layer
    ↓
Driver / Configuration
    ↓
Selenium WebDriver
```

Supporting components:

```text
Test Data → Excel
Logging   → Log4j2
Reports   → Extent Reports
```

## Execution Flow

```text
TestNG Test → BaseTest → DriverFactory → Page Objects → SeleniumUtils → Application → Validation → Reports + Logs
```

The current E2E flow covers:

**Login → Product Selection → Cart → Checkout → Payment → Order Confirmation → Logout**

## Key Areas

* Selenium WebDriver
* Page Object Model
* Framework architecture
* Reusable Selenium utilities
* TestNG
* Maven
* Excel-based test data
* Logging & reporting
* Configuration management
* E2E automation design

## Current Limitations

* Chrome is currently the primary supported browser.
* Ad/popup handling is being refined for better iframe handling.
* Some framework components are still under improvement.

## Planned Improvements

* Robust ad/popup handling
* Cross-browser execution
* API automation integration
* CI/CD with GitHub Actions

## Development Approach

The framework is being developed **incrementally**, focusing on practical automation problems rather than adding features just for the sake of complexity.

The goal is to build a framework that is **understandable, reusable and maintainable**.

---

**Status:** Actively Under Development
