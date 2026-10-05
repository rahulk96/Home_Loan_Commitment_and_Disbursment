# Home Loan Commitment and Disbursement

## Project Overview

This Business Analysis project models the **Home Loan Commitment** and **Home Loan Disbursement** processes for Housing Development Corporation Ltd. (HDC).

HDC is an NBFC primarily involved in housing finance and intends to replace its legacy IT system with a more robust, secure and advanced application. SmartWork has been selected to develop the new application.

As a Business Analyst, the objective is to understand and document the business processes before designing the new IT application.

---

## Project Objective

The objective of this project is to create clear process models for:

1. **Home Loan Commitment**
2. **Home Loan Disbursement**

The models illustrate the key activities, decisions and responsibilities involved in each process.

---

## Processes Covered

### 1. Home Loan Commitment

The Home Loan Commitment process covers the activities involved in evaluating a customer's loan application and creating a loan commitment.

**High-level flow:**

`Loan Application → Verification → Eligibility Check → Approval/Rejection → Loan Commitment`

### 2. Home Loan Disbursement

The Home Loan Disbursement process covers the activities involved in verifying the conditions for disbursement and releasing the approved loan amount.

**High-level flow:**

`Disbursement Request → Condition Verification → Approval → Loan Disbursement → Account Update`

---

## Key Actors

| Actor | Responsibility |
|---|---|
| Customer | Submits loan application, provides required information, accepts commitment and requests disbursement |
| HDC Loan Officer | Verifies application, evaluates eligibility and manages commitment and disbursement activities |
| HDC System | Records loan information and updates the loan account |

---

## Project Deliverables

- Home Loan Commitment Activity Diagram
- Home Loan Disbursement Activity Diagram
- PlantUML source files
- Diagram images

---

## Repository Structure

```text
Home-Loan-Commitment-and-Disbursement/
│
├── README.md
│
├── Home_Loan_Commitment/
│   ├── Home_Loan_Commitment.puml
│   └── Home_Loan_Commitment.png
│
└── Home_Loan_Disbursement/
    ├── Home_Loan_Disbursement.puml
    └── Home_Loan_Disbursement.png
