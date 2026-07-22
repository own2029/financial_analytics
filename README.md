# Financial Analytics Dashboard — Power BI

## Project Overview

The **Financial Analytics Dashboard** is an interactive Power BI project designed to provide **real-time insights into transactions, customers, and financial risks**. The dashboard enables users to monitor key financial KPIs, analyze transaction patterns, evaluate customer segments, and identify performance trends across states, genders, and transaction types.

This project demonstrates the use of **Power BI, DAX, Power Query, and data visualization techniques** to transform raw financial transaction data into meaningful business intelligence.

---

## Dashboard Preview

![Financial Analytics Dashboard](./dashboard.png)

---

## Key Metrics

* **Total Amount:** 138M
* **Previous Year Amount:** 135.77M
* **Total Transactions:** 14.94K
* **Previous Year Transactions:** 15.03K
* **Average Transaction Value:** 9.21K
* **Previous Year Average Transaction Value:** 9.03K
* **Total Fees:** 217.27K
* **Previous Year Total Fees:** 217.54K
* **Total Tax:** 39.11K

---

## Dashboard Features

### KPI Cards

* Total Amount
* Total Transactions
* Average Transaction Value
* Total Fees
* Total Tax
* Previous Year (PY) comparisons for all major KPIs

### Trend Analysis

* **Total Fees by Month:** Tracks monthly fee trends from January to December.
* **Dynamic Metric Selection:** Allows users to switch between different financial metrics for analysis.

### Customer Analysis

* **Customer Segment Analysis:** Retail, Premium, SME, Corporate, and Wealth segments.
* **Gender Analysis:** Distribution of transaction amounts between Male and Female customers.

### Transaction Analysis

* **Transaction Status:** Success, Failed, and Pending transaction percentages.
* **Transaction Type Analysis:** Loan EMI, Transfer, Deposit, Investment, Card Payment, Withdrawal, Bill Payment, and more.
* **Detailed Transaction Table:** Includes transaction ID, customer name, date, type, status, gender, segment, state, amount, fees, and tax.

### Geographic Analysis

* **State-wise Total Amount:** Compares financial activity across multiple states, including Maharashtra, Karnataka, Gujarat, Tamil Nadu, Uttar Pradesh, and others.

### Interactive Filters

* Year
* Merchant Category
* Occupation
* Gender
* Dynamic Metric Selector

---

## Key Insights

* **Retail customers** contribute the highest transaction amount, accounting for **76M**.
* **Successful transactions** dominate the dataset with **85.38%**, indicating strong operational performance.
* **Female customers** contribute slightly more transaction value (**52.79%**) compared to male customers.
* **Loan EMI** and **Transfer** transactions represent the largest transaction amounts among all transaction types.
* **Maharashtra** records the highest state-wise transaction amount at **22M**.
* Monthly fee trends show fluctuations, with peaks observed in **February, March, October, and December**.

---

## Tools & Technologies Used

* **Power BI Desktop** — Dashboard development and visualization
* **Power Query** — Data cleaning and transformation
* **DAX** — Calculated measures and KPI creation
* **Data Modeling** — Relationship management and schema design
* **Microsoft Excel / CSV** — Data source preparation

---

## Data Model

The dashboard is built using a structured financial transaction dataset containing:

* Transaction details
* Customer information
* Transaction types
* Transaction status
* Fees and tax values
* Geographic data
* Customer segments

---

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Use the slicers to filter data by year, merchant category, occupation, gender, and dynamic metrics.
4. Explore KPI cards, charts, and tables to gain financial insights.

---

## Repository Structure

```text
├── Financial_Analytics_Dashboard.pbix
├── dashboard.png
├── README.md
└── data/
    └── financial_transactions.csv
```

---

## Learning Outcomes

Through this project, I strengthened my skills in:

* Power BI dashboard design
* Financial data analysis
* KPI development
* DAX calculations
* Power Query transformations
* Interactive data visualization
* Business intelligence reporting

---

## Author

**Md Saiful Islam**

Aspiring Data Analyst | Power BI | SQL | Excel | Data Visualization

Feel free to connect with me on LinkedIn and explore more of my data analytics projects.
