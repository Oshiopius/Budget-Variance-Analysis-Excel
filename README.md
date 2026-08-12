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

#### Variance : Actual amount compared with Budget.

#### Variance % : Variance expressed as a percentage of Budget.

#### Quarter : Used to support time-based analysis.

#### Variance Classification : Variance was classified as Favorable or Unfavorable based on Account Type.

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
1. Overall performance
FY2025 actuals came in 1.2% over budget overall ($27.7M actual vs $27.4M budget). This was driven almost entirely by revenue overperformance (+3.1% favorable across every revenue line) rather than expense overruns, where total expenses landed just 0.03% over budget, effectively flat.

2. Largest monthly variances
December had by far the largest swing, with revenue beating budget by $166,545, more than double the next-highest month (November, $62,912). On the expense side, monthly variances were much smaller and split fairly evenly between over and under, with March ($5,299 unfavorable) and November (-$6,910, favorable) at the extremes.

3. Departments with the largest unfavorable variances
Sales & Marketing had the largest expense overrun at $30,413 over budget (+1.1%), followed by Research & Development ($8,708, +0.4%). Together these two departments account for roughly 90% of all unfavorable department-level expense variance.

4. Departments consistently within or below budget
Supply Chain (-1.1%) and Legal & Compliance (-1.1%) were the most disciplined, followed by Human Resources, Information Technology, and Finance & Admin, all landing under budget for the year.

5. Expense categories driving unfavorable variance
Commissions ($19,663 over, +4.7%) and External Research ($6,497 over, +4.3%) were the two largest contributors. Together with Advertising & Promotions, these three line items account for about 59% of all unfavorable expense variance FY2025-wide.

6. Revenue lines with the largest variances
Every revenue line beat budget. Licensing Revenue had the strongest relative performance (+5.0%), while Product Revenue contributed the largest dollar impact ($146,539 over budget, +3.5%) given its size.

7. Concentration of variance
Unfavorable variance is concentrated rather than spread evenly: two departments (Sales & Marketing, R&D) account for ~90% of unfavorable department variance, and three expense line items account for ~59% of unfavorable expense variance. This means budget attention for FY2026 can be targeted rather than applied across the board.
---

## Recommendations

1. Protect, don't cut, Sales & Marketing's budget. Its overrun is concentrated in Commissions, which scales with revenue performance — the same year Commissions ran 4.7% over, total revenue beat budget by $316,110. Cutting this budget risks cutting the driver behind the revenue upside.
2. Revisit the December budget assumption for FY2026. December's budget was already set ~67% higher than the average month, but actuals still outpaced it by more than any other month. The seasonal step-up needs to be sized more generously next year.
3. Use Supply Chain and Legal & Compliance as forecasting benchmarks. Their consistent under-budget performance suggests a forecasting approach (or level of spend discipline) worth understanding and potentially applying to less predictable departments.
4. Investigate External Research spend before FY2026 planning. Unlike Commissions, its overrun isn't as clearly tied to a measurable output — worth a conversation with R&D on whether this is a one-off or a recurring cost creep.
5. Target the concentrated 90%, not the whole budget. Since two departments and three expense lines account for the bulk of unfavorable variance, FY2026 budget review time is better spent there than doing an even review across all 11 departments.


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

