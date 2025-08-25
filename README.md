Sales Performance Analytics Dashboard
A Power BI solution analyzing sales across time, products, geographies, and customer segments to reveal drivers of revenue, profit, and margin. It demonstrates end‑to‑end BI: modeling, DAX, and storytelling with interactive exploration.

Highlights
Executive KPIs: Total Qty, Revenue, COGS, Profit, Margin with YoY deltas and transactions trend.

Time Intelligence: Monthly trends, quarter cards, weekday vs weekend mix, and weekday profit ranking.

Product Insights: Top 5 profitable SKUs, price bands (94% profit from expensive >150), and color-wise profit.

Customer & Inventory: Average age, gender mix, top customers, and sold vs unsold stock status.

Geography: Country filter with contribution trends; AU + US jointly lead total profit.

Files
/pbix: Sales Performance Analytics.pbix (report and measures).

/data: Sample CSVs and Power Query notes for reproducibility.

/docs: Screenshots and KPI dictionary.

Data Model
Star schema with FactSales, DimDate, DimProduct, DimCustomer, and DimGeography for performant slicing and time intelligence across pages and slicers.

Key DAX Concepts
YoY %, contribution shares, weekday/weekend mix, and price‑band segmentation using calculated measures and time intelligence functions.

Techniques applicable to ALL/ALLSELECTED/ALLEXCEPT scenarios for dynamic totals and context control in visuals and cards.

How to Run
Open the PBIX in Power BI Desktop (2024+ recommended).

Refresh data; inspect Model view; review measures in the report.

Explore pages: Overview, Time, Products, Customers, Geography; use slicers for year, month, weekday, country, and price band.

Use Cases
Identify best weekdays and quarters for profit optimization.

Prioritize high‑margin products/colors/price bands and align inventory planning.

Focus marketing in top‑contributing countries and customer segments.

Roadmap
Scenario analysis (promotions and pricing) and cohort retention.

Calculation groups for dynamic period comparisons and consistent formatting.

Power BI Service deployment with scheduled refresh and RLS by region.

Author
Karan Palav — Data Analytics practitioner focusing on Power BI, DAX, and decision‑ready dashboards.

