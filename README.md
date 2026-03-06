# Business Insights 360

## Project Overview
Business Insights 360 is a comprehensive Power BI analytics project dedicated to enabling data-driven decision-making for AtliQ Hardware. By integrating sales, finance, marketing, and supply chain data, this solution provides stakeholders and management with actionable insights across key business domains.

## Objective
The main objective is to answer critical stakeholder questions in real time, monitor business KPIs, and support strategic planning through powerful dashboard visualizations. The project promotes a data-centric culture and helps illuminate underlying patterns affecting business outcomes, enabling continuous improvement.

## Technology Stack
- **Power BI Desktop & Service:** Interactive dashboards, visualizations, automation.
- **SQL:** Data querying, database management.
- **Excel:** Data cleaning and transformation.
- **DAX & DAX Studio:** Calculations, dynamic measures, report optimization.

## Dataset
Understanding the available data is critical before analysis. The data consists of:

### Dimension Tables
- **dim_customer:** 27 distinct markets (e.g., India, USA, Spain), 75 customers, platforms (Brick & Mortar, E-commerce), and three channels (Retailer, Direct, Distributors).
- **dim_market:** 27 markets, 7 sub-zones, 4 regions (APAC, EU, nan, LATAM).
- **dim_product:** Divisions like P & A, Peripherals, Accessories, with 14 categories including Internal HDD, Keyboard, and more.

### Fact Tables
- **fact_forecast_monthly:** Forecast quantity data to improve customer satisfaction and reduce warehouse costs.
- **fact_sales_monthly:** Actual sold quantity data similar in structure to the forecast table.
- Additional tables like **freight_cost**, **gross_price**, **manufacturing_cost**, **Pre_invoice_deductions**, and **Post_invoice_deductions** covering cost, price, and deductions details.

## Project Implementation
- Based on [Codebasics Power BI methodologies](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project) for best practices.
- Focus on data cleaning, data modeling, calculated columns, DAX measures, interactive navigation, and dynamic titles.
- Includes conditional formatting, KPI indicators, drill-downs, and role-based access management.

## Report Views

## Home View
Central navigation hub.

<p align="center">
<img src="Images/Home.png" width="800">
</p>

## Finance View
Profit & Loss analysis, cost control, and net sales trends.

<p align="center">
<img src="Images/Finanial_View.png" width="800">
</p>

## Sales View
Customer performance and gross margin analysis.

<p align="center">
<img src="Images/Sales_View.png" width="800">
</p>

## Marketing View
Campaign effectiveness and product segment performance.

<p align="center">
<img src="Images/Marketing_View.png" width="800">
</p>

## Supply Chain View
Inventory management, risk analysis, and forecast accuracy.

<p align="center">
<img src="Images/Supply_Chain_View.png" width="800">
</p>

## Executive View
High-level KPIs, revenue breakdowns, and market share insights.

<p align="center">
<img src="Images/Executive_View.png" width="800">
</p>
## Key Outcomes
- AtliQ Hardware’s market share increased significantly from **1.1% to 5.9%**, indicating strong growth and improved market presence.
- **Latin America recorded the lowest net sales**, while **APAC performed the best**, followed by **North America**.
- Within the **APAC region, India generated the highest net sales**, making it the top-performing market in that region.
- **Amazon and AtliQ Exclusive are the highest-performing customers**, contributing significantly to overall revenue.
- The **Notebook segment frequently faces stock shortages**, suggesting the need for better inventory planning.
- **Operational expenses increased compared to 2021**, negatively impacting net profit margins.
- Revenue opportunities exist with customers like **Flipkart and Sage**.
- In **India, GM% variance is negative (Benchmark – Current)**, indicating performance exceeded the target.

---

*This README provides a detailed overview and documentation for the Business Insights 360 Power BI project to help stakeholders understand the project's scope, data, implementation, and outcomes.*
