# Credit_Card_Financial_Dashboard
Power bi Dashboard
# Credit Card Financial Dashboard

A Power BI-based financial dashboard designed to analyze credit card usage, customer behavior, and overall portfolio performance.

## Overview
This project focuses on evaluating how customers interact with different card categories and how those interactions influence revenue, spending activity, and credit utilization. The dashboard combines customer-level demographic data with card transaction and performance metrics to provide actionable business insights.

## Business Objective
The dashboard helps stakeholders understand:
- Card performance across Blue, Silver, Gold, and Platinum segments
- Customer acquisition cost and annual fee impact
- Activation rates within 30 days of card issuance
- Credit limit usage and revolving balance patterns
- Total transaction amount and transaction volume trends
- Spending behavior by category such as travel, fuel, grocery, bills, food, and entertainment
- Customer profile trends based on income, age, education, marital status, and satisfaction score

## Datasets
This repository includes the following source files:

- `cc_detail.csv` — Credit card transaction and financial data, including:
  - `Card_Category`
  - `Annual_Fees`
  - `Activation_30_Days`
  - `Customer_Acq_Cost`
  - `Credit_Limit`
  - `Total_Revolving_Bal`
  - `Total_Trans_Amt`
  - `Total_Trans_Vol`
  - `Avg_Utilization_Ratio`
  - `Transaction_Type`
  - `Spend_Category`
  - `Total_Amount_Spent`
  - `Delinquent_Flag`

- `cust_detail.csv` — Customer demographic and profile information, including:
  - `Customer_Age`
  - `Gender`
  - `Dependent_Count`
  - `Education_Level`
  - `Marital_Status`
  - `Income`
  - `Cust_Satisfaction_Score`
  - `House_Owner`, `Car_Owner`, and other lifestyle indicators

- `Credit_Card_Financial_Dashboard.pdf` — Exported Power BI dashboard presentation/report

## Dashboard Highlights
The dashboard is designed to provide a clear view of:
- Card category performance and revenue contribution
- Weekly and quarterly financial trends
- Transaction channel analysis (Swipe, Chip, Online)
- Spending distribution by category and customer segment
- Credit utilization risk indicators
- Customer satisfaction and demographic insights
- High-value customer patterns and portfolio health

## Tools Used
- Power BI
- CSV data analysis
- Business intelligence visualization

## Repository Structure
```text
Credit_Card_Financial_Dashboard/
├── README.md
├── cc_detail.csv
├── cust_detail.csv
├── Credit_Card_Financial_Dashboard.pdf
