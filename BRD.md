# Business Requirements Document (BRD)
## Retail Banking Web Application
Version: 1.0  
Prepared By: Rishabh Gupta  
Date: [Add Today's Date]

---

# 1. Introduction

## 1.1 Purpose
The purpose of this document is to define the functional and high-level business requirements for the Retail Banking Web Application. This system allows customers to register, log in, manage their accounts, perform fund transfers, and review transaction history securely.

## 1.2 Scope
The application provides core retail banking features including:
- User Registration
- Secure Authentication
- Account Dashboard
- Fund Transfer
- Transaction History
- Logout and Session Management

The system is web-based and accessible via modern browsers.

---

# 2. Stakeholders

- Business Team
- Development Team
- QA Team
- End Users (Retail Banking Customers)

---

# 3. Functional Requirements

---

## 3.1 User Registration

BR-01: The system shall allow new users to register using:
- Full Name
- Email Address
- Mobile Number
- Password

BR-02: The system shall validate email format before submission.

BR-03: The system shall ensure email uniqueness.

BR-04: The password must:
- Be minimum 8 characters
- Contain at least one numeric digit

BR-05: The system shall send a confirmation email upon successful registration.

---

## 3.2 Login / Authentication

BR-06: The system shall allow users to log in using registered Email and Password.

BR-07: The system shall validate credentials before granting access.

BR-08: After 3 consecutive failed login attempts, the account shall be locked for 15 minutes.

BR-09: Upon successful login, the user shall be redirected to the Account Dashboard.

---

## 3.3 Account Dashboard

BR-10: The dashboard shall display:
- Account Number
- Available Balance

BR-11: The dashboard shall display the last 5 recent transactions.

BR-12: The system shall auto-refresh balance after any successful transaction.

---

## 3.4 Fund Transfer

BR-13: The system shall allow transfer to registered beneficiaries.

BR-14: The system shall validate sufficient balance before processing transfer.

BR-15: The system shall require OTP verification before completing transfer.

BR-16: Upon successful OTP validation:
- Amount shall be deducted
- Transaction shall be recorded

BR-17: The system shall display appropriate error message if:
- OTP is incorrect
- Balance is insufficient
- Session is expired

---

## 3.5 Transaction History

BR-18: The system shall allow users to view transaction history.

BR-19: The system shall allow filtering by date range.

BR-20: The system shall allow downloading transaction history as PDF.

---

## 3.6 Logout

BR-21: The system shall allow users to log out securely.

BR-22: The system shall invalidate session after logout.

BR-23: The system shall redirect user to login page after logout.

---

# 4. Non-Functional Requirements

NFR-01: The system shall load dashboard within 3 seconds under normal conditions.

NFR-02: The system shall ensure secure password storage (hashed).

NFR-03: The system shall implement HTTPS secure communication.

NFR-04: The system shall auto-expire user session after 10 minutes of inactivity.

---

# 5. Assumptions

- OTP service is available and operational.
- Email service is integrated successfully.
- Users have stable internet connectivity.

---

# 6. Constraints

- Application is web-based only.
- No mobile application included in this release.

---

# 7. Acceptance Criteria

- All critical and high severity defects resolved.
- 95% test cases pass rate.
- No open security-related defects.
- UAT sign-off completed.

---

# End of Document
