# Driver-Based Financial Performance Analysis (Excel + Power BI)
![Financial Dashboard](PowerBI/Financial_dashboard.PNG) 
## Project Overview

This project demonstrates a **driver-based financial analysis model** built in Excel and visualized in Power BI.
The objective is to analyze company financial performance across **three products** by comparing **Actual vs Budget results**, identifying key variance drivers, and presenting the results in a financial dashboard.

---

## Financial Model Structure (Excel)

The financial model is structured using multiple components:

**1. Assumptions**

Contains the operational drivers used to build the financial model, including:

* Units sold per product
* Average selling price (ASP)
* Material cost
* Labor cost
* Overhead cost
* Monthly volume growth rate

These drivers are used to calculate revenue, COGS, and operating expenses.

---

**2. Budget P&L**

Represents the **planned financial performance** of the business for three products.

The budget income statement includes:

Revenue → COGS → Gross Profit → OPEX → Net Income

---

**3. Actual P&L**

Contains the **actual financial performance** of the business, allowing comparison against the budget.

---

**4. Variance Analysis**

Variance analysis breaks down performance differences between **Actual and Budget** into key drivers:

* Volume variance
* Price variance
* Unit cost variance

This allows identification of the operational factors impacting financial performance.

---

**5. Forecast Analysis**

A forecast model is created using **driver-based assumptions**, such as monthly volume growth, to estimate future financial performance.

---

## Data Pipeline

The data workflow for the project is:

Excel Financial Model
↓
Power Query (Data transformation)
↓
Star Schema Data Model in Power BI
↓
DAX Measures
↓
Financial Dashboard

---

## Power BI Dashboard

The Power BI dashboard provides an executive overview of financial performance.

Key elements included:

* Revenue, Gross Profit, and Net Income KPIs
* Budget vs Actual comparison
* Variance and Variance %
* Revenue monthly trend
* Net income monthly trend
* P&L statement comparison
* Executive insight summarizing financial performance

---

## Tools Used

* Microsoft Excel
* Power BI
* Power Query
* DAX

---

## Skills Demonstrated

* Driver-based financial modeling
* Budget vs Actual variance analysis
* Financial statement analysis
* Data modeling using star schema
* Financial dashboard development
* Business performance storytelling

---
