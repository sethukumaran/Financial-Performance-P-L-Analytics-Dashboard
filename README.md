# Financial-Performance-P-L-Analytics-Dashboard

1. Project Overview

This project is an end-to-end Financial Performance & P&L Analytics solution developed using Microsoft Power BI. The objective is to provide management with a consolidated view of revenue, profitability, operating expenses, EBITDA, and net profit while enabling comparison between Actual, Budget, and Forecast performance.

The dashboard analyzes financial performance across multiple Business Units (BU) and P&L categories, allowing users to identify performance gaps, profitability trends, and key areas requiring management attention.

2. Business Objective

The primary objective of this project is to transform detailed financial transaction data into an interactive management reporting solution that can answer questions such as:

How is actual revenue performing against budget and forecast?
Which Business Units are contributing most to revenue and profitability?
How does Gross Margin vary across Business Units and P&L categories?
Are operating expenses within the planned budget?
How is EBITDA performing against financial targets?
What are the major drivers of budget vs. actual variance?
How is current-year performance progressing compared with the previous financial year?
Which areas require management attention based on profitability and cost performance?
3. Dataset

The primary dataset contains approximately 55,000 financial records covering historical financial performance.

Key fields
Field	Description
P&L	Major financial/business category
BU	Business Unit
Breakup	Financial component such as Revenue, Cost, etc.
Type of Value	Actual, Budget or Forecast
Revenue Date	Financial transaction/reporting date
Value	Financial amount

The dataset supports financial analysis across multiple years, business units, P&L categories and reporting scenarios.

4. Key KPIs

The dashboard focuses on the following management KPIs:

Revenue

Measures total income generated from operations and compares Actual, Budget and Forecast values.

Gross Margin %

Measures profitability after accounting for the cost of sales.

Opex Ratio %

Measures operating expenses as a percentage of revenue and helps evaluate cost efficiency.

EBITDA %

Measures operating profitability before interest, tax, depreciation and amortization.

NPAT %

Measures Net Profit After Tax as a percentage of revenue.

Variance Analysis

Calculates the difference between Actual performance and Budget/Forecast expectations to highlight financial gaps.

5. Dashboard Structure
Executive Summary

The Executive Summary provides a high-level management view of financial performance.

Key visualizations include:

Revenue vs Budget vs Forecast by year
Revenue by Business Unit
Revenue by P&L
Gross Margin % trends
Gross Margin % by Business Unit
Gross Margin % by P&L
EBITDA trends
EBITDA by Business Unit
EBITDA by P&L
KPI cards for Revenue, Gross Margin, Opex Ratio, EBITDA and NPAT

Interactive filters allow users to analyze performance by:

Fiscal Year
Month
Business Unit
P&L category
Profit & Loss Statement

The P&L page provides a detailed financial statement view with comparison across:

Current month
YTD performance
Current financial year
Previous financial year

The analysis includes:

Total Revenue from Operations
Cost of Sales
Gross Profit
Gross Margin %
Other Income
Operating Expenses
Operating Expense %
EBITDA
Adjusted EBITDA
EBITDA %
EBIT
EBIT %
Interest Expense
Net Profit Before Tax
Net Profit Before Tax %
Tax Expense
Net Profit After Tax
Net Profit After Tax %

For each metric, Actual, Budget and Variance values are presented to support financial decision-making.

6. Analytical Approach

The project follows a structured BI development approach:

Raw Financial Data → Data Preparation → Data Modeling → DAX Measures → KPI Development → Variance Analysis → Interactive Dashboard → Business Insights

Data Preparation

Power Query was used to:

Clean and transform source data
Standardize data types
Prepare date fields
Structure financial categories
Validate financial values
Prepare data for analytical modeling
Data Modeling

The financial data was structured to support analysis across:

Date
Business Unit
P&L
Financial category
Scenario/type of value

A date-based analytical structure enables monthly, yearly and YTD reporting.

DAX & Measures

Calculated measures were developed for:

Revenue
Gross Profit
Gross Margin %
Operating Expenses
Opex Ratio %
EBITDA
EBITDA %
EBIT
NPAT
NPAT %
Budget variance
Forecast variance
YTD performance
Year-over-year comparison
7. Variance Analysis

A key component of the solution is financial variance analysis.

Actual vs Budget

Identifies whether the organization is performing above or below the approved financial plan.

Actual vs Forecast

Shows how actual performance compares with the latest expected financial outcome.

YTD Variance

Provides a cumulative view of financial performance during the financial year.

This enables management to distinguish between isolated monthly fluctuations and sustained performance trends.

8. Business Insights

The dashboard enables management to identify several important financial patterns:

Revenue performance can be evaluated against both Budget and Forecast expectations.
Business Units can be ranked based on revenue contribution and profitability.
Gross Margin analysis helps identify differences in profitability across business segments.
EBITDA analysis highlights the operating profitability of individual Business Units and P&L categories.
Operating Expense ratios provide visibility into cost efficiency.
Monthly and YTD variance analysis helps identify areas where actual performance is deviating from financial targets.
Year-over-year comparisons provide visibility into financial growth and changes in profitability.
9. Technical Skills Demonstrated
Power BI
Power Query
Data transformation
Data modeling
DAX
KPI development
Variance analysis
Time intelligence
Interactive filtering
Dashboard design
Financial reporting
Data Analytics
Financial performance analysis
Budget vs Actual analysis
Forecast analysis
Profitability analysis
Business Unit benchmarking
Trend analysis
Variance investigation
Management reporting
Business Skills
Financial KPI interpretation
P&L analysis
Management reporting
Performance monitoring
Data-driven decision support
10. Key Business Value

The solution converts detailed financial data into a single interactive management reporting platform.

Instead of manually reviewing large financial datasets, decision-makers can quickly understand:

What happened → Where it happened → How it compares with the plan → Why performance differs → Which areas require attention

This improves financial visibility and supports faster, data-driven business decisions.
