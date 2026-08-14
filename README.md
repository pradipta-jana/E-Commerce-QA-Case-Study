# QA Case Study

## Overview

This repository demonstrates an end-to-end QA Engineering approach for the Automation Exercise eCommerce application.

The case study is designed as a portfolio project and connects:

**Business Requirement → Test Scenario → Test Case → Execution → Automation / Evidence**

GitHub is the detailed QA portfolio/source-of-truth artifact. Jira is used as the supporting QA management artifact for feature tracking, status, defect lifecycle and traceability.

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

## QA Lifecycle

```text
Requirement
    ↓
Test Scenario
    ↓
Test Case
    ↓
Manual / Automation Execution
    ↓
Defect / Retest where applicable
    ↓
Evidence & Reporting
```

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

### QA / Management

- Jira
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

## Current Automation Framework

The supplied AutomationFramework contains a Sanity E2E flow covering:

```text
Login
  ↓
Product Search / Product Details
  ↓
Clear Existing Cart
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

### Current Test Data

The `ProductDetails` Excel sheet contains:

| Product | Quantity |
|---|---:|
| Blue Top | 2 |
| Men Tshirt | 3 |

Payment data is read from framework configuration.

## Automation Coverage

### Implemented

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
- Logout flow implementation

### Partial / Manual

- Product category browsing
- Product brand browsing
- Dedicated product-price-in-cart assertion
- Standalone remove-product test
- Dedicated order-review assertion
- Negative login scenarios
- Invoice download

## Execution Evidence

The repository was supplied with historical Extent reports and the latest Surefire result.

The latest supplied `SanityE2E` execution is **FAIL**, with:

`org.openqa.selenium.NoSuchWindowException`

The failure occurs during initial navigation while `SeleniumUtils.closeAdIfPresent()` attempts iframe/window handling before clicking Signup/Login.

Therefore, this case study intentionally does **not** claim a fresh end-to-end PASS from the latest execution artifact.

This is a framework/test-infrastructure issue rather than an application functional defect.

See:

`06-Defects/README.md`

for the classification.

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

## Jira Strategy

Customer Account Management currently has confirmed Jira mapping:

- KAN-7 — Customer Registration
- KAN-8 — Existing Email Validation
- KAN-9 — Customer Login
- KAN-10 — Invalid Login Validation
- KAN-11 — Customer Logout
- KAN-12 — Customer Account Deletion

New business-area Jira keys are intentionally marked `To be linked` until the actual Jira issues are created and confirmed.

This avoids false traceability.

Jira is not intended to duplicate the complete GitHub documentation tree.

## Portfolio Principle

The project demonstrates not only automation scripting but the broader QA Engineering lifecycle:

**Understand the business → derive requirements → design scenarios → write test cases → execute → automate high-value flows → classify failures → maintain traceability → report honestly.**
