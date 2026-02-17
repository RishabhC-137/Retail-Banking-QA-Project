# Retail Banking QA Project

## Overview

This repository demonstrates a structured Quality Assurance (QA) validation framework for a simulated Retail Banking Web Application.

The objective of this project is to simulate end-to-end QA governance including requirement analysis, test planning, test case design, defect tracking, UAT validation, and quality metrics reporting.

This project reflects real-world QA documentation practices aligned with enterprise software delivery standards.

---

## Application Scope

The Retail Banking Web Application includes the following modules:

- User Registration
- Login / Authentication
- Account Dashboard
- Fund Transfer (with OTP validation)
- Transaction History
- Secure Logout & Session Management

---

## QA Deliverables Included

### 1. Business Requirements Document (BRD)
Defines structured functional and non-functional requirements with requirement IDs.

File: `BRD.md`

---

### 2. Test Plan
Defines scope, strategy, environment, entry/exit criteria, risks and deliverables.

File: `Test_Plan.md`

---

### 3. Test Cases (60 Structured Cases)
- Functional Testing
- Negative Testing
- Boundary Value Testing
- Security Testing (SQL Injection attempt)
- Session Handling Validation
- Financial transaction validation

Each test case includes:
- Requirement mapping
- Severity classification
- Execution status

File: `Test_Cases.xlsx`

---

### 4. Requirement Traceability Matrix (RTM)
Ensures every requirement is mapped to corresponding test cases to maintain complete coverage.

File: `RTM.xlsx`

---

### 5. Defect Log
Includes realistic banking-related defects with:
- Severity
- Priority
- Reproduction steps
- Expected vs Actual result
- Status tracking

File: `Defect_Log.xlsx`

---

### 6. UAT Execution Sheet
Simulated business validation scenarios with execution results and sign-off tracking.

File: `UAT_Execution.xlsx`

---

### 7. Quality Metrics Report
Includes:
- Test execution summary
- Defect classification summary
- Release recommendation
- Observations and risk assessment

File: `Quality_Report.md`

---

## Testing Approach

The testing lifecycle followed:

1. Requirement Analysis
2. Test Planning
3. Test Case Design
4. Test Execution
5. Defect Logging & Tracking
6. Traceability Validation
7. UAT Support
8. Quality Reporting & Release Recommendation

---

## Tools Used

- Microsoft Excel (Test Cases, RTM, Defect Log, UAT Sheet)
- Markdown Documentation (BRD, Test Plan, Quality Report)
- Git & GitHub (Version Control and Documentation Management)

---

## Key QA Focus Areas

- Financial transaction accuracy
- OTP validation integrity
- Account lock mechanism
- Session timeout handling
- Security validation (SQL Injection prevention)
- Regression coverage

---

## Release Status

Application is NOT recommended for production release until all Critical and High severity defects are resolved and UAT sign-off is completed.

---

## Author

Rishabh Gupta  
Quality Assurance Enthusiast  
GitHub: https://github.com/RishabhC-137
