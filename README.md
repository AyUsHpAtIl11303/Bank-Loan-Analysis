# 🏦 Bank Loan Portfolio Analysis

### End-to-End Data Analytics & Business Intelligence Project

An end-to-end banking analytics project focused on analyzing loan applications, funding performance, borrower characteristics, loan quality, and portfolio trends using **SQL, Excel, Power BI, and Tableau**.

The project transforms raw loan data into interactive dashboards and actionable business insights to support data-driven lending decisions.

---

## 📌 Project Overview

The objective of this project is to analyze a bank's loan portfolio and provide a comprehensive view of:

- Loan application performance
- Funded and received amounts
- Loan quality and repayment status
- Borrower characteristics
- Loan purposes and terms
- Geographic distribution
- Interest rate and DTI trends
- Monthly application trends

**Analysis Workflow:**

`Raw Data → Data Analysis → SQL Queries → KPI Development → Dashboard Development → Business Insights`

---

## 🎯 Business Problem

Traditional loan reporting can make it difficult to understand lending operations, borrower behavior, and loan performance from a single view.

This project addresses the problem by developing interconnected analytical dashboards that provide dynamic insights into lending operations, borrower demographics, financial metrics, and loan performance.

The dashboards are designed to help decision-makers evaluate portfolio performance and identify important lending trends.

---

## 📊 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Loan Applications | 38.6K |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Average Interest Rate | 12.05% |
| Average DTI | 13.33% |
| Good Loan Applications | 33.2K |
| Bad Loan Applications | 5.3K |
| Good Loan Issued | 86.2% |
| Bad Loan Issued | 13.8% |

The dashboard also tracks **Month-to-Date (MTD)** and **Month-over-Month (MoM)** performance for major KPIs.

---

## 💰 Funding & Collection Performance

- **$435.8M** in total funded amount
- **$473.1M** in total amount received
- **$54.0M** MTD funded amount
- **$58.1M** MTD received amount
- **13.0%** MoM increase in funded amount
- **15.8%** MoM increase in received amount

---

## 🟢 Good Loan vs 🔴 Bad Loan Analysis

### 🟢 Good Loans

- Good Loan Applications: **33.2K**
- Good Loan Issued: **86.2%**
- Good Loan Funded Amount: **$370.2M**
- Good Loan Received Amount: **$435.8M**

### 🔴 Bad Loans

- Bad Loan Applications: **5.3K**
- Bad Loan Issued: **13.8%**
- Bad Loan Funded Amount: **$65.5M**
- Bad Loan Received Amount: **$37.3M**

---

## 📈 Loan Status Analysis

| Loan Status | Applications | Funded Amount | Amount Received | Avg. Interest | Avg. DTI |
|---|---:|---:|---:|---:|---:|
| Fully Paid | 32,145 | $351.36M | $411.59M | 11.64% | 13.17% |
| Charged Off | 5,333 | $65.53M | $37.28M | 13.88% | 14.00% |
| Current | 1,098 | $18.87M | $24.20M | 15.10% | 14.72% |
| **Total** | **38,576** | **$435.76M** | **$473.07M** | **12.05%** | **13.33%** |

---

## 📅 Loan Application Trends

Monthly loan applications increased from approximately **2.3K in January** to **4.3K in December**, indicating stronger application activity toward the end of the year.

---

## 🗺️ Geographic Analysis

The dashboard provides state-level analysis of loan applications using an interactive geographic visualization.

This helps identify:

- States with higher loan activity
- Regional lending patterns
- Geographic concentration
- State-level application trends

---

## ⏳ Loan Term Analysis

| Loan Term | Share |
|---|---:|
| 36 Months | 73.2% |
| 60 Months | 26.8% |

The **36-month term** represents the majority of loan applications.

---

## 🎯 Loan Purpose Analysis

The project analyzes applications across multiple purposes:

- Debt Consolidation
- Credit Card
- Other
- Home Improvement
- Major Purchase
- Small Business
- Car
- Wedding
- Medical

**Debt consolidation** is the largest loan purpose, with approximately **18K applications**.

---

## 🏠 Home Ownership Analysis

Loan applications are analyzed across:

- RENT
- MORTGAGE
- OWN

The dashboard shows approximately **18K applications from renters** and **17K from mortgage holders**.

---

## 📊 Dashboard

### 1. Executive Summary

Provides a high-level view of:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI
- Good vs Bad Loan analysis
- Loan status performance

![Executive Summary](assets/summary.png)

---

### 2. Portfolio Overview

Provides interactive analysis of:

- Monthly loan application trends
- State-level applications
- Loan term distribution
- Employee length
- Loan purpose
- Home ownership

![Portfolio Overview](assets/overview.png)

---

### 3. Loan Details

Provides granular loan-level information including:

- Loan ID
- Loan Purpose
- Home Ownership
- Grade
- Sub Grade
- Issued Date
- Funded Amount
- Interest Rate
- Installment
- Received Amount

![Loan Details](assets/details.png)

---

## 🛠️ Tools & Technologies

### Data Analysis
- SQL
- Microsoft Excel

### Business Intelligence
- Microsoft Power BI
- Tableau

### Data Visualization
- Power BI
- Tableau
- Excel

### Version Control
- Git
- GitHub

---

## 🔍 SQL Analysis

SQL was used to calculate and analyze:

- Total loan applications
- Total funded amount
- Total amount received
- Average interest rate
- Average DTI
- Loan status
- Good vs Bad loans
- Monthly trends
- Loan purpose
- Loan term
- Employment length
- Home ownership
- Geographic distribution

---

## Overview of Dashboard
<img width="2075" height="1200" alt="overview" src="https://github.com/user-attachments/assets/7fdc3693-cfab-41da-8274-daee8d559ac8" />

<img width="2075" height="1200" alt="details" src="https://github.com/user-attachments/assets/0b9e65ef-5983-449d-b5ce-0799222b3137" 

<img width="2075" height="1200" alt="summary" src="https://github.com/user-attachments/assets/f2dbb7fc-b820-42f2-8810-efce0bcccb8e" />




## 📁 Repository Structure

```text
Bank-Loan-Analysis/
│
├── assets/
│   ├── summary.png
│   ├── overview.png
│   └── details.png
│
├── data/
│   └── financial_loan.csv
│
├── sql/
│   ├── loan_queries.sql
│   └── bankloan_sqlquery.pdf
│
├── excel/
│   └── loan_data_analysis.xlsx
│
├── powerbi/
│   └── bank_loan_data_insights.pbix
│
├── tableau/
│   └── bank_loan_data_viz.twbx
│
├── documentation/
│   ├── analytical_BI_report.pdf
│   ├── domain_insights.docx
│   ├── loan_data_terms.docx
│   └── problem_statement.pdf
│
└── README.md
