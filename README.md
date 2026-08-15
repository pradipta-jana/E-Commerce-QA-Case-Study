# QA Case Study

## Overview

This repository demonstrates an end-to-end QA Engineering approach for the Automation Exercise eCommerce application.

The case study connects:

**Business Requirement → Test Scenario → Test Case → Execution → Automation**

**GitHub:** Detailed QA portfolio and project documentation.

**Jira:** QA tracking and project management for features, testing, defects, and traceability.


## System Under Test

**Application:** Automation Exercise  
**Domain:** eCommerce  
**URL:** https://automationexercise.com/

## Business Areas

- Customer Account Management
- Product Discovery
- Shopping Cart
- Checkout
- Payment
- Order & Purchase

## Testing Types

- Functional Testing
- Positive Testing
- Negative Testing
- Regression Testing
- End-to-End Testing
- UI Automation Testing
- Test Data Management
- Defect Management
- Test Reporting

## Technology & Tools

### QA Management & Collaboration

- [Jira](https://pradipta-qa-portfolio.atlassian.net/jira/software/projects/KAN/summary)
- GitHub

### Automation

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model

### Supporting Framework Components

- Apache POI / Excel
- Log4j2
- Extent Reports
- Configuration management
- Reusable Selenium utilities


## Automation Coverage

### Automated

- Customer login
- Product search
- Product availability validation
- Product details navigation
- Product price retrieval
- Cart clearing
- Multiple product addition
- Excel-driven quantity
- Expected cart total calculation
- Actual cart total validation
- Delivery address validation
- Payment form entry
- Payment submission
- Order confirmation
- Logout flow

### Partially Automated / Manual

- Product category browsing
- Product brand browsing
- Dedicated product-price-in-cart assertion
- Standalone remove-product test
- Dedicated order-review assertion
- Negative login scenarios
- Invoice download


## Project Structure

```text
qa-case-study/
│
├── 01-Project-Overview/
│   ├── 01-Application-Overview.md
│   ├── 02-Business-Flows.md
│   └── 03-Scope.md
│
├── 02-Requirements/
│   ├── 01-Customer-Account-Management.md
│   ├── 02-Product-Discovery.md
│   ├── 03-Shopping-Cart.md
│   ├── 04-Checkout.md
│   ├── 05-Payment.md
│   └── 06-Order-Purchase.md
│
├── 03-Traceability/
│   └── README.md
│
├── 04-Test-Scenarios/
│   ├── Customer-Registration.md
│   ├── Customer-Login.md
│   ├── Product-Discovery.md
│   ├── Shopping-Cart.md
│   ├── Checkout.md
│   ├── Payment.md
│   └── Order-Purchase.md
│
├── 05-Test-Cases/
│   ├── Customer-Registration.md
│   ├── Customer-Login.md
│   ├── Product-Discovery.md
│   ├── Shopping-Cart.md
│   ├── Checkout.md
│   ├── Payment.md
│   └── Order-Purchase.md
│
├── 06-Defects/
│   └── README.md
│
└── 07-Test-Execution/
    ├── Customer-Registration.md
    ├── Customer-Login.md
    ├── Product-Discovery.md
    ├── Shopping-Cart.md
    ├── Checkout.md
    ├── Payment.md
    └── Order-Purchase.md
```

## QA Engineering Focus

This case study demonstrates a practical QA Engineering approach across:

* Business understanding
* Requirement analysis
* Test design
* Functional and end-to-end testing
* Automation of high-value scenarios
* Defect identification and classification
* Test execution and reporting
* Traceability and QA documentation

The focus is on demonstrating how a QA Engineer approaches a real-world application, rather than automation scripting alone.
