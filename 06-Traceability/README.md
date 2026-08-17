# Requirement & Test Traceability

## Purpose

This document provides the high-level traceability model for the QA Case Study.

```text
Requirement
    ↓
Test Scenario
    ↓
Test Case
    ↓
Execution
    ↓
Automation / Evidence
    ↓
Defect / Retest where applicable
```

## Customer Account Management

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-CAM-01 | KAN-7 | TS-CAM-01 to TS-CAM-06 | TC-CAM-001 to TC-CAM-004 |
| REQ-CAM-02 | KAN-8 | Existing Email scenario | TC-CAM-003 |
| REQ-CAM-03 | KAN-9 | TS-CAM-07 | TC-CAM-007 |
| REQ-CAM-04 | KAN-10 | TS-CAM-08 to TS-CAM-10 | TC-CAM-008 to TC-CAM-010 |
| REQ-CAM-05 | KAN-11 | Logout coverage | Existing project scope |
| REQ-CAM-06 | KAN-12 | Account deletion coverage | Existing project scope |

## Product Discovery

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-PROD-01 | To be linked | TS-PROD-11 | TC-PROD-011 |
| REQ-PROD-02 | To be linked | TS-PROD-12 | TC-PROD-012 |
| REQ-PROD-03 | To be linked | TS-PROD-13 | TC-PROD-013 |
| REQ-PROD-04 | To be linked | TS-PROD-14, TS-PROD-15 | TC-PROD-014, TC-PROD-015 |

## Shopping Cart

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-CART-01 | To be linked | TS-CART-16 | TC-CART-016 |
| REQ-CART-02 | To be linked | TS-CART-17 | TC-CART-017 |
| REQ-CART-03 | To be linked | TS-CART-18 | TC-CART-018 |
| REQ-CART-04 | To be linked | TS-CART-19, TS-CART-20 | TC-CART-019, TC-CART-020 |
| REQ-CART-05 | To be linked | TS-CART-21, TS-CART-22 | TC-CART-021, TC-CART-022 |

## Checkout

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-CHK-01 | To be linked | TS-CHK-23 | TC-CHK-023 |
| REQ-CHK-02 | To be linked | TS-CHK-24 | TC-CHK-024 |
| REQ-CHK-03 | To be linked | TS-CHK-25 | TC-CHK-025 |

## Payment

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-PAY-01 | To be linked | TS-PAY-26 | TC-PAY-026 |
| REQ-PAY-02 | To be linked | TS-PAY-27 | TC-PAY-027 |
| REQ-PAY-03 | To be linked | TS-PAY-28 | TC-PAY-028 |

## Order & Purchase

| Requirement | Jira | Scenarios | Test Cases |
|---|---|---|---|
| REQ-ORD-01 | To be linked | TS-ORD-29 | TC-ORD-029 |
| REQ-ORD-02 | To be linked | TS-ORD-30 | TC-ORD-030 |
| REQ-ORD-03 | To be linked | TS-ORD-31 | TC-ORD-031 |

## Jira Strategy

GitHub remains the detailed QA portfolio/source-of-truth artifact.

Jira remains the supporting artifact for:

- Requirement and feature tracking
- Test management visibility
- Status
- Defect lifecycle
- Traceability

The full test-case documentation is intentionally not duplicated inside Jira.
