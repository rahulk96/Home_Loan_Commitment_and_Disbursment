# Home Loan Commitment and Disbursement

## Project Overview

This Business Analysis project models the **Home Loan Commitment and Home Loan Disbursement** process for Housing Development Corporation Ltd. (HDC).

HDC is an NBFC primarily involved in housing finance and intends to replace its legacy IT system with a more robust, secure and advanced application. SmartWork has been selected to develop the new application.

As a Business Analyst, the objective is to understand and document the business process before designing the new IT application.

---

## Project Objective

The objective of this project is to create a clear process model for:

- **Home Loan Commitment**
- **Home Loan Disbursement**

The Activity Diagram represents the key activities, decision points and responsibilities involved in the end-to-end process.

---

## Process Covered

### Home Loan Commitment

The process covers the evaluation of a customer's home loan application and creation of a loan commitment.

**High-level flow:**

`Loan Application → Application Verification → Eligibility Check → Approval/Rejection → Loan Commitment`

### Home Loan Disbursement

The process begins after the loan commitment and covers the request, verification and release of the approved loan amount.

**High-level flow:**

`Loan Commitment → Disbursement Request → Condition Verification → Disbursement Approval → Loan Disbursement → Account Update`

---

## End-to-End Process

The two processes are connected as follows:

```text
Home Loan Application
        ↓
Application Verification
        ↓
Eligibility Check
        ↓
Approval / Rejection
        ↓
Loan Commitment
        ↓
Customer Accepts Commitment
        ↓
Disbursement Request
        ↓
Verify Disbursement Conditions
        ↓
Conditions Satisfied?
        ↓
Disbursement Approval
        ↓
Loan Disbursement
        ↓
Update Loan Account
