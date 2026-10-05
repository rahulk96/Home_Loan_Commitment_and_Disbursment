# Home Loan Commitment and Disbursement

## Project Overview

This Business Analysis project models the **Home Loan Commitment and Home Loan Disbursement** process for **Housing Development Corporation Ltd. (HDC)**.

HDC is an NBFC primarily involved in the housing finance sector. HDC intends to replace its legacy IT system with a more robust, secure and advanced application.

**SmartWork** has been selected to develop the new IT application.

As a **Business Analyst working with SmartWork**, my responsibility is to understand and document the relevant business processes before the development of the new IT application.

---

## Project Objective

The objective of this project is to document and model the business process for:

- **Home Loan Commitment**
- **Home Loan Disbursement**

The process model represents the key activities, decision points and responsibilities involved in the end-to-end home loan process.

---

## Process Overview

### Home Loan Commitment

The process covers the evaluation of a customer's home loan application and creation of a loan commitment.

**Flow:**

`Loan Application → Application Verification → Eligibility Check → Approval/Rejection → Loan Commitment`

### Home Loan Disbursement

The process begins after the loan commitment and covers the verification and release of the approved loan amount.

**Flow:**

`Loan Commitment → Disbursement Request → Condition Verification → Disbursement Approval → Loan Disbursement → Account Update`

---

## End-to-End Process

```text
Home Loan Application
        ↓
Application Verification
        ↓
Eligibility Check
        ↓
Eligible?
   /           \
 No             Yes
 ↓               ↓
Reject        Approve Loan
                 ↓
          Loan Commitment
                 ↓
       Accept Loan Commitment
                 ↓
        Disbursement Request
                 ↓
       Verify Conditions
                 ↓
       Conditions Satisfied?
          /             \
        No               Yes
        ↓                 ↓
      Hold          Approve Disbursement
                          ↓
                    Disburse Loan
                          ↓
                  Update Loan Account
                          ↓
                         End
