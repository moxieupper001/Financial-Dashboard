# Financial-Dashboard

### Dashboard Link : [https://app.powerbi.com/groups/me/reports/4801ea95-391f-4a2c-ad2f-6c10a5f7daed/ReportSection?](https://app.powerbi.com/view?r=eyJrIjoiYzYyOGY2MjUtMmIzMC00YTlmLWFjZGUtZTE2NTk2YmY5OGEyIiwidCI6IjUxYTBhNjljLTBlNGYtNGIzZC1iNjQyLTEyZTAxMzE5ODYzNSIsImMiOjh9)

# Please download the PBIW5- Finanacial Dashboard.pbix file above to view the dashboard

## Problem Statement

The Dashboard shows the financial statement of the organisation, this helps the organisation to simplify and understand their financial statement and make good sound decision to help improve profit and customer satisfaction. The financial statement calculates the gross profit and Gross profit percentage which will help the business to renegotiate terms with the suppliers in the new business year. The financial Simulator help the business management to make sound decision about the percentage change in variables (unit price, Quantity etc) and the resultant effect on the organisation Profit/Loss, and this can help in better negotiation and increasing selling price at the most profitable rate.

## Overview
Designed and built a multi-page, interactive Power BI dashboard providing end-to-end visibility into revenue, profitability and cost performance for a multi-supplier retail/wholesale/online business. The solution combines historical financial reporting with a dynamic financial simulator, enabling stakeholders to model the impact of pricing, cost and volume changes on profitability in real time, supporting faster, more confident commercial decision-making.

## Business Objective

The dashboard was built to answer three core business questions:

#1. Where is revenue and margin being generated across sales channels, suppliers and product categories?
#2. How is financial performance trending month-on-month, and where are the variances against prior periods?
#3. What would happen to profitability if key commercial levers (price, volume, cost, expenses) were changed, before those decisions are made?

## Key Features
# 1. Revenue & Margin Analysis Page

#. Real-time KPI cards for Operational Revenue ($9.68M), Gross Margin ($4.02M) and % Gross Margin (42%), each with embedded trend sparklines and "best month" callouts to instantly highlight peak performance periods.
#. Supplier-level performance table breaking down revenue, gross margin and % GM across 5 suppliers, using conditional formatting (data bars and colour-coded % of GM) to make outliers immediately visible.
#. Revenue by Sales Team and Category visual, decomposing Retail, Wholesale and Online channels by Drinks vs. Food, enabling channel and category profitability comparison at a glance.
#. Fully interactive with slicers for Month, Sales Team and Supplier, allowing users to drill into any dimension without needing technical support.

<img width="1920" height="1032" alt="PBIW5 - Financial Dashboard pdf - Adobe Acrobat Reader (64-bit) 06_07_2026 09_52_41" src="https://github.com/user-attachments/assets/30407bdb-9ee3-4b2d-a834-48982ca2abc3" />


# 2. Income Statement Page

 - Full P&L structure (Gross Revenue → Cost of Sales → Gross Margin → Operating Expenses → Operating Income) rebuilt as an interactive DAX-driven statement rather than a static export.
#. Built Vertical Analysis (VA%) and Horizontal Analysis (HA%) calculations directly into the model, automatically showing each line item as a % of revenue and its % change versus the prior month, standard financial analysis techniques automated for instant reporting.
#. Waterfall chart visualising Operating Income build-up by month, making it easy to see which months drove overall annual profitability ($2.2M total operating income).

<img width="1920" height="1032" alt="PBIW5 - Financial Dashboard pdf - Adobe Acrobat Reader (64-bit) 06_07_2026 09_50_27" src="https://github.com/user-attachments/assets/1a899b8f-1202-4d5b-a051-6b0ddf628b6d" />

# 3. Financial Simulator ("What-If") Page

#. Built a fully interactive scenario modelling tool using Power BI What-If Parameters, allowing users to adjust Quantity of Items, Unit Price, Product Costs and Expenses via sliders and instantly see the recalculated impact on Revenue, Costs, Expenses and Operating Income.
#. Dynamic variance table compares the original P&L against the simulated scenario side-by-side (PnL vs. PnL Scenario vs. VAR%) for every month, turning the dashboard from a reporting tool into a decision-support and forecasting tool.

<img width="1920" height="1032" alt="PBIW5 - Financial Dashboard pdf - Adobe Acrobat Reader (64-bit) 06_07_2026 09_50_37" src="https://github.com/user-attachments/assets/bb0a6455-bdeb-4ee1-acac-23c91f244045" />

## Technical Skills Demonstrated
# DAX: Custom measures for KPIs, running totals, month-over-month variance, vertical/horizontal analysis, and dynamic what-if calculations
# Power BI What-If Parameters: Built interactive scenario modelling without needing external tools
# Data Modelling: Structured relational data model connecting sales, supplier, product and time dimensions
# Data Visualisation Design: Consistent dark-themed UI, custom KPI cards, waterfall charts, conditional formatting, and cross-filtering slicers designed for executive-level readability
# Financial Analysis Techniques: Applied standard finance concepts (P&L structure, gross margin analysis, vertical/horizontal analysis, variance analysis) directly into an automated reporting tool

## Business Impact


# This dashboard demonstrates the ability to:

#. Replace static, manual month-end reporting with a live, self-service reporting tool, reducing time spent producing recurring reports
#. Give non-technical stakeholders the ability to explore performance data independently via slicers, without needing analyst support for every query
#. Support pricing, procurement and cost decisions through real-time scenario simulation, rather than relying on offline spreadsheet modelling
#. Present complex financial data (P&L, variance analysis) in a way that's accessible to non-finance stakeholders





