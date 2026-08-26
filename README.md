# FNP-Sales-Data-analysis-Excel-
An interactive Excel dashboard built using Power Query, Power Pivot, and DAX to analyze sales performance for FNP (Ferns N Petals) across occasions, product categories, delivery timelines, and geography.
📊 Project Overview

This project transforms raw order-level sales data into a fully interactive Excel dashboard, enabling stakeholders to explore revenue trends by occasion, category, time period, product, and city — without writing a single formula themselves. The dashboard supports dynamic filtering via slicers for Order Date, Delivery Date, and Occasion.

🎯 Objective
Consolidate and clean raw sales data using Power Query
Build a relational data model in Power Pivot to support efficient, scalable analysis
Create DAX measures for key business metrics (revenue, order count, delivery time, average spend)
Design an interactive, single-page dashboard for quick executive-level insights
🛠️ Tools & Technologies
Tool	Purpose
Excel Power Query	Data extraction, cleaning, and transformation (ETL)
Power Pivot	Data modeling and relationship management
DAX (Data Analysis Expressions)	Custom calculated measures and KPIs
PivotTables / PivotCharts	Visualizations
Slicers & Timelines	Interactive filtering

🗂️ Data Model

Briefly describe your model here, for example:

Fact table: Orders (order ID, order date, delivery date, product, category, occasion, city, revenue)
Dimension tables: Date, Product, Occasion, City (if used)
Relationships: One-to-many relationships linking dimension tables to the fact table via Power Pivot's Diagram View

📐 Key DAX Measures

List the core measures you created, for example:

Total Revenue = SUM(Orders[Revenue])
Total Orders = COUNTROWS(Orders)
Avg Customer Spend = DIVIDE([Total Revenue], [Total Orders])
Avg Delivery Time = AVERAGE(Orders[Delivery Days])

📈 Dashboard Features
KPI Cards: Total Orders, Total Revenue, Avg. Order-to-Delivery Time, Avg. Customer Spend
Revenue by Occasion — bar chart
Revenue by Category — bar chart
Revenue by Day of Week — line chart
Revenue by Month — line chart
Top 5 Products by Revenue — bar chart
Top 10 Cities by Orders — bar chart
Slicers: Order Date, Delivery Date, Occasion

🔍 Key Insights
Anniversary and Holi are the top revenue-generating occasions
Soft Toys and Sweets lead category-level revenue
Revenue peaks sharply in February and August, aligning with Valentine's Day and Raksha Bandhan
Tuesday shows an unusual mid-week revenue spike
"Magnum Set" and "Quia Gift" are the top-performing products
Order volume is well distributed across tier-2/3 cities, led by Imphal, Dhanbad, and Kavali


📁 File Structure
├── FNP_Sales_Analysis.xlsx     # Main dashboard file (Power Query + Power Pivot + PivotCharts)
├── README.md                   # Project documentation


[
Optional: list any known limitations (e.g., static data snapshot, no live database connection)
Optional: note planned enhancements (e.g., migrating to Power BI, adding YoY comparison, adding a customer segmentation view)
