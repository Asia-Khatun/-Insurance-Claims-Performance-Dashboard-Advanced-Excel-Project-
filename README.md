
📊 **Insurance Claims Performance Dashboard (Advanced Excel Project)**

🧩 **Overview**
This project presents an Insurance Claims Performance Dashboard built using Advanced Excel, leveraging Power Query, Power Pivot, and DAX to simulate a real-world insurance analytics solution.
The dashboard tracks and analyzes insurance KPIs such as Premiums, Claims Paid, Underwriting Profit, Loss Ratio, Profit Margin, Settlement Ratio, and Average Processing Days — helping decision-makers understand overall business performance and claim efficiency.

💡 **Business Problem & Solution**
Problem: Insurance companies often struggle to monitor claim trends, loss ratios, and profitability efficiently across products and regions.
Solution: This dashboard consolidates all business-critical metrics into a single, interactive Excel model — offering decision-makers a real-time view of:

•	Claim volume vs. premium revenue

•	Loss and profit trends

•	Settlement efficiency

•	Regional and customer performance

⚙️ **Applications & Workflow**
🔹 Power Query – Data Cleaning & Preparation
Power Query was used for cleaning, transforming, and standardizing raw data from multiple sources (Claims, Premiums, Regions, Customers, Products).
Key steps included:

•	Removing duplicates and irrelevant columns

•	Merging and appending tables for consistency

•	Replacing and formatting missing or incorrect values

•	Creating conditional columns for claim statuses

•	Ensuring all columns had proper data types and date formats

👉 **Result**: A clean and well-structured dataset ready for modeling.

🔹 **Power Pivot** – Data Modeling & Relationships
Power Pivot was used to build a star schema model, connecting fact tables (Claims, Premiums) with dimension tables (Products, Customers, Regions, Channels, Date).

•	Relationships: One-to-many between dimensions and facts

•	Cross-filter direction: Single, to maintain clarity and integrity

•	Enhanced the model with calculated columns for easier DAX computations

👉 **Result**: A dynamic, scalable model enabling accurate aggregations and cross-table analysis.

🔹 **DAX Calculations**– Business KPIs
Key measures were created using DAX: SUM, CALCULATE, DIVIDE, DISTINCTCOUNT, and AVERAGEX to calculate and analyze financial and operational metrics:

•	Total Premium, Total Claim Paid, and Underwriting Profit

•	Profit Margin (%) and Loss Ratio (%)

•	Claim Settlement Ratio (CSR) and Average Processing Days

These measures provided insights into profitability trends, operational efficiency, and claim-handling performance over time.

🔹 **Excel Visualization** – Interactive Dashboard
The dashboard includes three analytical views:

1️⃣ Executive Summary –High-level KPIs with claim status distribution and underwriting overview.

2️⃣ Time-Series Trends –Year-over-year comparison of Premiums, Claims Paid, Profit, and Loss Ratios (2021–2025).

3️⃣ Regional & Customer Insights –Breakdown by Product Line, Region, Gender, and Channel.

All visuals are fully interactive, using slicers and timelines to filter data by Year, Product Line, and Region, creating a Power BI–like experience inside Excel.
👉 Each KPI card and chart delivers a clear message to executives — highlighting key trends, risks, and performance patterns.

🤖 **Automation Capability**
The model is designed for automated updates by connecting to a shared data folder, new monthly or quarterly data files can be loaded and refreshed automatically through Power Query, updating all visuals and KPIs in seconds.
This makes it ideal for small and medium-sized businesses seeking self-updating, low-cost reporting solutions.

📈 **Key Insights**

•	Identified products with higher claim-to-premium ratios and loss trends

•	Highlighted regions with delayed settlements and higher rejection rates

•	Analyzed year-over-year performance to improve underwriting strategies

**#AdvancedExcel #PowerQuery #PowerPivot #DAX #InsuranceAnalytics #ExcelDashboard #BusinessIntelligence #Automation #DataAnalytics #ExcelProjects #DataStorytelling**

