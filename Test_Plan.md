# Test Plan
## Retail Banking Web Application
Version: 1.0
Prepared By: Rishabh Gupta
Date: [Add Today's Date]

---

# 1. Introduction

## 1.1 Objective
The objective of this test plan is to define the testing strategy, scope, approach, resources, and schedule for validating the Retail Banking Web Application before production release.

## 1.2 Scope of Testing
The following modules are in scope:

- User Registration
- Login / Authentication
- Account Dashboard
- Fund Transfer
- Transaction History
- Logout & Session Management

Out of Scope:
- Mobile application
- Third-party payment gateway internal systems

---

# 2. Test Strategy

## 2.1 Testing Types

The following testing types will be performed:

- Functional Testing
- Regression Testing
- Negative Testing
- Boundary Value Testing
- User Acceptance Testing (UAT) Support

---

# 3. Test Approach

- Requirements will be analysed from BRD.
- Test scenarios will be derived from each requirement.
- Test cases will be documented in structured format.
- Execution results will be logged.
- Defects will be tracked in defect log with severity and priority.
- Requirement Traceability Matrix (RTM) will ensure full coverage.

---

# 4. Test Environment

- Application Type: Web-based
- Browser: Chrome (latest version)
- Operating System: Windows 10+
- Test Data: Dummy user accounts and simulated transaction data

---

# 5. Entry Criteria

Testing will begin when:

- BRD is signed off
- Test cases are reviewed and approved
- Test environment is stable and accessible

---

# 6. Exit Criteria

Testing will be considered complete when:

- All critical and high severity defects are resolved
- Minimum 95% test cases pass
- No open security defects
- UAT sign-off is received

---

# 7. Deliverables

- Business Requirements Document (BRD)
- Test Plan
- Test Cases Document
- Requirement Traceability Matrix (RTM)
- Defect Log
- UAT Execution Sheet
- Quality Metrics Report

---

# 8. Risk Assessment

| Risk ID | Description | Impact | Mitigation |
|---------|------------|--------|------------|
| R1 | OTP service failure | High | Conduct negative testing and simulate fallback scenarios |
| R2 | Session timeout errors | Medium | Perform session expiry validation testing |
| R3 | Incorrect balance deduction | Critical | Execute boundary and regression testing |

---

# 9. Defect Severity Levels

- Critical: System crash, data loss, incorrect financial deduction
- High: Core feature not working
- Medium: Functional issue with workaround
- Low: UI or minor validation issue

---

# 10. Approval

QA Lead: ___________________  
Business Representative: ___________________  
Date: ___________________

---

# End of Document
