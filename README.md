# 🏦 Bank Loan Analysis Report

A comprehensive **Power BI reporting solution** designed to monitor, analyze, and evaluate **bank loan performance, portfolio quality, and borrower demographics**. This interactive multi-page dashboard provides executive-level KPIs, granular operational insights, and detailed loan transaction records.

---

## 📊 Executive Summary

The **Bank Loan Analysis Dashboard** provides key insights into lending operations by tracking:

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average Debt-to-Income (DTI) Ratio

The dashboard enables financial analysts and risk stakeholders to evaluate overall portfolio health by segmenting loans into:

* **Good Loans:** `Fully Paid` and `Current`
* **Bad Loans:** `Charged Off`

---

## ✨ Key Features and Visualizations

The report is structured across three interactive dashboard pages.

### 1. Summary Dashboard

Provides high-level executive KPIs and portfolio performance analysis.

#### Key Performance Indicators

* Total Loan Applications with MTD and YoY growth analysis
* Total Funded Amount with MTD and YoY growth analysis
* Total Amount Received / Cash Collections
* Average Interest Rate
* Average Debt-to-Income (DTI) Ratio

#### Good Loan vs. Bad Loan Analysis

Analyzes portfolio quality using loan status segmentation.

**Good Loans**

* Total Funded Amount
* Total Amount Received
* Total Loan Applications
* Percentage of Total Loans

**Bad Loans**

* Total Funded Amount
* Total Amount Received
* Total Loan Applications
* Percentage of Total Loans

#### Loan Status Analysis

Provides a detailed breakdown of loan performance across:

* `Fully Paid`
* `Current`
* `Charged Off`

Metrics analyzed include total applications, funded amount, amount received, average interest rate, and average DTI.

---

### 2. Overview Dashboard

Provides interactive analysis of lending trends, geographic distribution, and borrower demographics.Images of dashboard landing pages
<img width="1556" height="877" alt="image" src="https://github.com/user-attachments/assets/da6e2b3b-472e-47ee-a881-1abdaa601ff8" />
<img width="1547" height="872" alt="image" src="https://github.com/user-attachments/assets/21518fb6-91a3-4cb6-8d7b-61a101efb4cd" />
<img width="1532" height="875" alt="image" src="https://github.com/user-attachments/assets/5f6fc4ed-0510-4be1-b812-fc112a103729" />



#### Monthly Trends

Tracks the historical progression of loan applications and funded amounts over time.

#### Geographic Analysis

Visualizes loan volume and total funding across US states.

#### Loan Term Analysis

Compares the distribution of:

* Short-term loans: `36 months`
* Long-term loans: `60 months`

#### Employment Length Distribution

Analyzes borrowers based on employment tenure.

#### Loan Purpose Analysis

Breaks down the portfolio by loan purpose, including:

* Debt Consolidation
* Credit Card Payoff
* Home Improvement
* Small Business
* Other Loan Categories

#### Home Ownership Analysis

Analyzes loan distribution across:

* `RENT`
* `MORTGAGE`
* `OWN`

---

### 3. Details Dashboard

Provides a granular view of individual loan records for operational analysis and validation.

#### Loan-Level Records

Tracks detailed information including:

* Loan ID
* Grade
* Sub-Grade
* Issue Date
* Purpose
* Interest Rate
* Verification Status
* Debt-to-Income Ratio
* Total Payments
* Loan Status

#### Interactive Filters

Users can dynamically filter data by:

* Grade
* Sub-Grade
* State
* Purpose
* Verification Status

---

## 🧮 DAX Measures and Key Metrics

### Total Loan Applications

```DAX
Total Loan Applications = COUNT(Loan_ID)
```

Calculates the total number of loan applications.

### Total Funded Amount

```DAX
Total Funded Amount = SUM(Loan_Amount)
```

Calculates the aggregate principal amount funded.

### Total Amount Received

```DAX
Total Amount Received = SUM(Total_Payment)
```

Calculates the total cash payments received from borrowers.

### Average Interest Rate

```DAX
Avg Interest Rate = AVERAGE(Interest_Rate)
```

Calculates the average interest rate across the loan portfolio.

### Average DTI

```DAX
Avg DTI = AVERAGE(DTI)
```

Calculates the average borrower Debt-to-Income ratio.

### Good Loan Percentage

Calculates the percentage of loans classified as:

* `Fully Paid`
* `Current`

### Bad Loan Percentage

Calculates the percentage of loans classified as:

* `Charged Off`

---

## 🗂️ Data Model and Filtering

The Power BI report uses a structured data model to support interactive reporting and portfolio analysis.

### Global Slicers

Dynamic filters are available across the main report pages for:

* State
* Grade
* Verification Status

### Interactive Navigation

An integrated page navigation bar enables seamless movement between:

* Summary
* Overview
* Details

---

## 🛠️ Tools and Technologies

* **Power BI** — Dashboard development and data visualization
* **DAX** — KPI calculations and business metrics
* **SQL** — Data extraction, transformation, and validation
* **Data Modeling** — Structured relationships and analytical reporting

---

## 📈 Business Value

This dashboard enables financial analysts and decision-makers to:

* Monitor lending and portfolio performance
* Track loan application and funding trends
* Evaluate borrower characteristics
* Analyze interest rates and DTI ratios
* Identify good and bad loan segments
* Assess geographic and demographic lending patterns
* Review detailed loan-level records for operational analysis
#### The following readme file is AI generated with mindful prompt instruction given by me , If you still feel you want more context please do contact me with email address provided in my git, Don't blindly copy the project as I am happy to help :) 
