# Bank Loan Report Analysis | Power BI + SQL + Python

## Project Title 

**Bank Loan Portfolio Performance & Risk Analysis Dashboard**

An end-to-end financial analytics project analyzing 37+ loan records to evaluate lending performance, borrower risk, repayment trends, and portfolio health using Power BI, SQL validation, and Python-based analysis.

## Short Description / Purpose

This project analyzes a bank’s lending portfolio to monitor loan performance, repayment behavior, borrower risk metrics, and monthly growth trends.

The objective is to:
- Track total lending activity
- Evaluate portfolio quality (Good vs Bad Loans)
- Monitor risk using Interest Rate & DTI metrics
- Support data-driven lending and risk management decisions

## Tech Stack

- Power BI – Interactive dashboard & KPI visualization
- SQL – KPI validation & aggregation queries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly) – Data analysis & visualization
- Excel – Raw dataset source
- Jupyter Notebook – Analytical environment

## Features / Highlights

### Executive Portfolio KPIs

- **Total Loan Applications:** 38,576
- **Total Funded Amount:** $435.76M
- **Total Amount Received:** $473.07M
- **Average Interest Rate:** 12.05%
- **Average DTI:** 13.33%

#### Month-to-Date (December 2021)
- MTD Applications: 4,314
- MTD Funded Amount: $53.98M
- MTD Amount Received: $58.07M

### Loan Quality Analysis

#### Good Loans (Fully Paid + Current)
- Applications: 33,243
- Funded Amount: $370.22M
- Amount Received: $435.79M
- Portfolio Share: **86.18%**

#### Bad Loans (Charged Off)
- Portfolio Share: **13.82%**
- Represents key risk exposure segment

This segmentation helps evaluate portfolio stability and default risk.

### Monthly Lending Growth (2021)

Strong upward trend observed:

- January Funded: $25.03M
- June Funded: $34.16M
- September Funded: $40.91M
- December Funded: $53.98M

~115% growth in monthly funded volume from Jan to Dec 2021.

### Regional Analysis

State-level breakdown of:
- Loan Applications
- Funded Amount
- Amount Received

Helps identify:
- High-performing lending regions
- Regional repayment behavior
- Concentration risk

### Loan Term Analysis

Distribution across:
- 36 Months
- 60 Months

Analysis includes:
- Funded Amount by Term
- Total Payment by Term
- Application Distribution by Term

Supports evaluation of long-term vs short-term lending risk.

### Employment Length Analysis

Examined impact of borrower employment length on:
- Loan applications
- Funded amount
- Repayment behavior

Helps understand borrower financial stability trends.

### Home Ownership Analysis

Treemap visualization shows distribution across:
- Mortgage
- Rent
- Own
- Other

Used to analyze borrower asset-backed risk behavior.

### Loan Purpose Analysis

Top lending categories analyzed:
- Debt Consolidation
- Credit Card
- Home Improvement
- Small Business
- Car Loans

Helps identify dominant revenue-driving segments.

## SQL Validation Layer

All Power BI KPIs were cross-verified using SQL queries:

- COUNT() for total applications
- SUM() for funded & received amounts
- AVG() for Interest Rate & DTI
- CASE logic for Good vs Bad Loan %

Ensured 100% data integrity between:
- Excel Dataset
- SQL Output
- Power BI Dashboard

## Business Impact & Insights

 Portfolio Stability: 86.18% Good Loan ratio indicates strong portfolio health.  
 Risk Monitoring: 13.82% Bad Loans highlight manageable but important credit risk exposure.  
 Revenue Growth: 115% increase in monthly funding shows aggressive lending expansion in 2021.  
 Profitability Signal: Total Amount Received ($473.07M) exceeds Total Funded ($435.76M).  
 Strategic Planning: State, employment, and term-level insights support risk-based pricing decisions.  

## Snapshot
![Preview](https://github.com/Harshnd2004/Bank-Loan-Report-Analysis/blob/main/Snapshot%20ofbank%20Dashboard.PNG)
