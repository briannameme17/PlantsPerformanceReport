

## Overview
The **Plant Co. Performance Report** is an interactive Power BI dashboard designed to evaluate the performance of **plant-related products** across multiple dimensions, including sales, quantity, and gross profit. The data model and visualizations allow decision-makers to explore how indoor, outdoor, and landscape plants are performing across regions, time periods, and customer accounts.  

The dashboard focuses on **year-to-date (YTD) vs previous year-to-date (PYTD)** performance, highlighting growth trends and profitability within the plant industry. By combining transactional sales data with product categories, this report delivers actionable insights for monitoring business health and identifying areas of opportunity.  

---

## Project Title
**Plant Co. Performance Report**

---

## Objectives
- Track and compare **plant sales and quantity performance** year-over-year.  
- Analyze growth across different plant product types (Indoor, Outdoor, Landscape).  
- Evaluate gross profit % (GP%) to understand plant product profitability.  
- Identify **top- and bottom-performing regions and customers** in the plant industry.  
- Provide an interactive dashboard for monitoring performance trends.  

---

## Steps Taken
1. **Data Preparation**
   - Imported data from the **Plant_DTS Excel file** as the primary source.  
   - Connected fact and dimension tables (`Fact_Sales`, `Dim_Product`, `Dim_Account`, `Dim_Date`).
   - Ensured product hierarchy fields (Plant Family, Group, Type, Size) were standardized for analysis.

2. **Data Cleaning & Transformation**
   - Extracted date hierarchy for YTD and PYTD comparisons.
   - Validated plant product attributes and account location data.
   - Built calculated fields for plant sales and profitability.

3. **DAX Measures**
   - Created measures for `YTD`, `PYTD`, `YTD vs PYTD Variance`, and `GP%`.
   - Used dynamic measures to allow switching between **Plant Quantity, Sales, and Gross Profit** KPIs.

4. **Visualization & Dashboarding**
   - Designed KPI cards for **Plant Sales, Quantity, and GP%**.
   - Built:
     - **Waterfall chart** – monthly variance in plant quantities.
     - **Bar chart** – performance by product type (Indoor, Outdoor, Landscape).
     - **Tree map** – bottom 10 underperforming countries for plant sales.
     - **Scatter plot** – account segmentation by GP% and plant sales.
   - Added slicers to filter by year, region, and plant type.

5. **Reporting & Insights**
   - Published an easy-to-navigate dashboard with segmented insights for business users.
   - Highlighted growth areas, underperforming regions, and customer contribution to total sales.

---

## Tools Used
- **Power BI Desktop** – data modeling, DAX, and dashboard creation.
- **Excel/CSV** – supporting source data.
- **DAX (Data Analysis Expressions)** – KPIs and measures for plant sales & profitability.

---

## Key Insights (2023)
- **Quantity Performance**
  - YTD Plant Quantity: **555.66K** units.
  - PYTD Plant Quantity: **538.61K** units.
  - Variance: **+17.05K units (growth)**.
  - Gross Profit Margin: **39.62%**.

- **Plant Product Segmentation**
  - **Indoor, Outdoor, and Landscape** categories consistently contributed, with peaks in **March, April, and November**.
  - Seasonal fluctuations suggest plant demand aligns with growing seasons and landscaping cycles.

- **Geographic Trends**
  - Strongest markets: United States and other high-volume regions.
  - Underperforming countries: **China (-9.76K)**, **France (-9.36K)**, **Sweden (-6.71K)** vs PYTD.

- **Account Profitability**
  - Majority of accounts cluster around **40% GP%**, with opportunities to improve margins for low-performing accounts.
  - Top accounts balance **high plant sales volume** with strong profitability.


