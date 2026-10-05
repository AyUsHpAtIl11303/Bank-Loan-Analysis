# 🏦 Bank Loan Portfolio Analysis

### End-to-End Data Analytics & Business Intelligence Project

An end-to-end analytics project focused on analyzing a bank's loan portfolio, understanding borrower behavior, evaluating loan quality, and identifying trends that can support data-driven lending decisions.

The project combines **SQL, Excel, Power BI, and Tableau** to transform raw loan data into meaningful business insights and interactive dashboards.

---

## 📌 Project Overview

Banks need to continuously monitor loan applications, funded amounts, repayment performance, borrower characteristics, and portfolio risk.

This project analyzes a bank loan dataset to answer important business questions such as:

- How is loan application volume changing over time?
- How much money has been funded and received?
- What proportion of loans are performing vs. non-performing?
- Which loan purposes generate the highest demand?
- How do interest rates and DTI vary across borrowers?
- Which states and customer segments contribute most to the portfolio?
- What factors are associated with higher loan risk?

The analysis follows a complete workflow:

**Raw Data → Data Preparation → SQL Analysis → KPI Development → Excel Validation → Power BI / Tableau Dashboards → Business Insights**

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Analyze overall loan portfolio performance
- Track loan applications and funding trends
- Evaluate Good Loan vs. Bad Loan performance
- Analyze borrower characteristics and loan purposes
- Monitor key financial KPIs
- Identify patterns in loan repayment and risk
- Compare trends across states, loan terms, and customer segments
- Build interactive dashboards for business decision-making

---

## 🗂️ Dataset

The project uses a financial loan dataset containing information about loan applications, borrowers, loan characteristics, and repayment performance.

### Key fields include:

| Field | Description |
|---|---|
| Loan ID | Unique identifier for each loan |
| Address State | Borrower's state |
| Employee Length | Length of employment |
| Employee Title | Borrower's employment title |
| Grade | Loan risk grade |
| Sub Grade | Detailed risk classification |
| Home Ownership | Borrower's housing status |
| Issue Date | Loan origination date |
| Loan Status | Current loan performance status |
| Purpose | Reason for taking the loan |
| Term | Loan duration |
| Annual Income | Borrower's annual income |
| DTI | Debt-to-Income ratio |
| Installment | Monthly loan payment |
| Interest Rate | Annual interest rate |
| Loan Amount | Principal loan amount |

---

# 🔎 Analysis Workflow

## 1️⃣ Data Preparation

The raw loan dataset was prepared for analysis by:

- Reviewing data structure and field definitions
- Validating data quality
- Preparing fields for analysis
- Standardizing relevant attributes
- Creating categories required for portfolio analysis

Excel was also used for preliminary validation and analysis.

---

## 2️⃣ SQL Analysis

SQL Server was used to perform analytical queries and calculate business KPIs.

The analysis includes:

- Total loan applications
- Monthly loan application trends
- Total funded amount
- Total amount received
- Average interest rate
- Average DTI
- Loan status analysis
- Good vs. Bad loan analysis
- State-level analysis
- Loan purpose analysis
- Loan term analysis
- Employment length analysis
- Home ownership analysis

### Example business questions addressed using SQL:

```sql
-- Total Loan Applications
SELECT COUNT(*) AS Total_Loan_Applications
FROM financial_loan;

-- Total Funded Amount
SELECT SUM(loan_amount) AS Total_Funded_Amount
FROM financial_loan;

-- Average Interest Rate
SELECT AVG(int_rate) AS Average_Interest_Rate
FROM financial_loan;
