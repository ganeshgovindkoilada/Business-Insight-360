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
- **Home View:** Central navigation hub.
- **Finance View:** Profit & Loss, cost control, net sales trends.
- **Sales View:** Customer performance, gross margin analysis.
- **Marketing View:** Campaign effectiveness, segment performance.
- **Supply Chain View:** Inventory management, risk analysis, forecast accuracy.
- **Executive View:** High-level KPIs, revenue breakdowns, market share.

## Key Outcomes
- **Empowered Decision Making:** Strategic choices based on rich and timely data.
- **Versatile Analysis:** Supports finance, sales, marketing, and supply chain decisions.
- **Continuous Improvement:** Adaptable insights updated with evolving data and business needs.

---

*This README provides a detailed overview and documentation for the Business Insights 360 Power BI project to help stakeholders and users understand the project's scope, data, implementation, and outcomes.*
