# QA Case Study

## Overview

This repository demonstrates an end-to-end QA Engineering approach for the Automation Exercise eCommerce application.

The case study connects:

**Business Requirement → Test Scenario → Test Case → Execution → Automation**

**GitHub:** Detailed QA portfolio and project documentation.

**[Jira:](https://pradipta-qa-portfolio.atlassian.net/jira/software/projects/KAN/summary)** QA tracking and project management for features, testing, defects, and traceability.

## System Under Test

**Application:** Automation Exercise
**Domain:** eCommerce
**Type:** Web Application
**URL:** https://automationexercise.com/

## Business Areas & Flows

#### Customer Account Management

Registration → Login → Logout

#### Product Discovery

Browse → Search → View Details

#### Shopping Cart

Add Product → Set Quantity → Add Multiple Products → Verify Price/Total → Remove/Clear Cart

#### Checkout

Cart → Proceed to Checkout → Verify Delivery Address → Review Order

#### Payment

Enter Payment Details → Submit Payment → Payment Confirmation

#### Order & Purchase

Place Order → Verify Order Confirmation → Download Invoice

## Testing Types

* Functional Testing
* Regression Testing
* End-to-End Testing
* UI Automation Testing

## Technology & Tools

### Automation

* Java
* Selenium WebDriver
* TestNG
* Maven
* Page Object Model

### Supporting Framework Components

* Apache POI / Excel
* Log4j2
* Extent Reports
* Configuration management
* Reusable Selenium utilities

## Automation Coverage

### The automated scenarios are implemented in the [Automation Framework](https://github.com/pradipta-jana/AutomationFramework) repository.

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

## Project Structure

The repository is organized around the key stages of the QA process:

* **Requirements** — Business requirements for each application area.
* **Traceability** — Mapping between requirements, test scenarios, test cases, and execution.
* **Test Scenarios** — High-level scenarios derived from the requirements.
* **Test Cases** — Detailed test cases covering positive and negative validations.
* **Defects** — Documented defects, investigation, and classification.
* **Test Execution** — Execution results and test status by business area.

## QA Engineering Focus

This case study demonstrates a practical QA Engineering approach covering:

* Business understanding
* Requirement analysis
* Test design
* Functional and end-to-end testing
* Automation of high-value scenarios
* Defect identification and classification
* Test execution and reporting
* Traceability and QA documentation

The focus is on demonstrating **how a QA Engineer approaches a real-world application**, rather than automation scripting alone.

The objective is **not to achieve complete application or end-to-end coverage**, but to demonstrate a practical QA Engineering approach by selecting meaningful business workflows, designing appropriate tests, automating high-value scenarios, and maintaining clear traceability and documentation.


## Connect

- [LinkedIn](www.linkedin.com/in/pradiptajana)