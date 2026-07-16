# Budget Variance Analysis Using Excel

## Project Overview

This project analyzes Budget vs Actual financial performance using Microsoft Excel.

The objective was to identify favorable and unfavorable budget variances across revenue lines, departments, and expense categories, and highlight the areas requiring management attention.

---
## Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Budget Variance Analysis Dashboard](#budget-variance-analysis-dashboard)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [Project Files](#project-files)
- [Project Status](#project-status)

---
## Business Problem

Management requires a clear view of budget performance to understand where actual results deviated from budgeted expectations.

The analysis focuses on identifying the timing, departments, revenue lines, and expense categories contributing to significant budget variances.

---

## Business Questions

1. How did actual performance compare with the overall budget?
2. Which months had the largest favorable and unfavorable variances?
3. Which departments had the largest unfavorable variances?
4. Which departments consistently performed within or below budget?
5. Which expense categories contributed most to unfavorable variance?
6. Which revenue lines had the largest favorable or unfavorable variances?
7. Are budget variances concentrated in a small number of departments or line items?

---

## Dataset

The dataset contains financial records covering a 12-month period.

The dataset includes the following fields:

* Date
* Month
* Account Type
* Department
* Line Item
* Budget
* Actual

The dataset contains both Revenue and Expense records across multiple departments and financial line items.

---

## Data Preparation

Before beginning the analysis, I reviewed and prepared the dataset for analysis.

The following steps were completed:

* Reviewed the structure and data types of the dataset.
* Checked for missing values and duplicate records.
* Verified date formats.
* Standardized the financial data structure.
* Added calculated fields to support budget variance analysis.

### Calculated Fields

#### Variance

Actual amount compared with Budget.

#### Variance %

Variance expressed as a percentage of Budget.

#### Quarter

Used to support time-based analysis.

#### Variance Classification

Variance was classified as Favorable or Unfavorable based on Account Type.

For Revenue:

* Actual above Budget = Favorable

For Expenses:

* Actual above Budget = Unfavorable

---

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the structure and quality of the dataset before conducting the budget variance analysis.

The EDA included:

* Dataset overview
* Data quality checks
* Record distribution by Account Type
* Record distribution by Department
* Monthly record distribution
* Basic financial summaries

![Exploratory Data Analysis](BVA%20Exploratory%20Data%20Analysis.png)

---

## Budget Variance Analysis Dashboard

PivotTables and summary calculations were used to analyze variance across all categories
The analysis was designed to identify both favorable and unfavorable budget performance and an interactive Excel dashboard was created to provide a management-level view of budget performance.

The dashboard includes:

* Budget vs Actual comparison, showing monthly variance trends
* Overall variance status
* Top 5 variance by department
* Top 5 variance by line items
* Favorable and unfavorable variance Status

Interactive slicers were included to allow users to filter the analysis by relevant financial dimensions.

![Budget Variance Dashboard](BVA%20Dashboard.png)

---

## Key Findings 
Coming soon...

---

## Recommendations

Coming Soon...


---

## Tools Used

* Microsoft Excel
* Excel Tables
* PivotTables
* PivotCharts
* Conditional Formatting
* Excel formulas
* Slicers

---

## Project Files

- [Raw Data](Budget%20Variance%20Analysis%20Raw%20Data.xlsx)
- [Completed Excel Analysis](Budget%20Variance%20Analysis.xlsx)

---

## Project Status

In Progress

