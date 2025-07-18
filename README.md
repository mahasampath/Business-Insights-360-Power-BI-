# Business-Insights-360-Power-BI-Dashboard
# BI-360 Power BI Dashboard
## Business Insights 360 Project Report for AtliQ Hardwares

### Project Overview
AtliQ Hardware has seen rapid growth in recent years. To stay ahead of competitors and make data-driven decisions, the company has implemented data analytics using Power BI for the first time. This project aims to provide insights into various aspects of the business, including Finance, Sales, Marketing, and Supply Chain, addressing stakeholder queries effectively.

[Live Power BI Report Link](https://app.powerbi.com/view?r=eyJrIjoiZWYwZGI3MzItMDA4Zi00MzliLWEzOGYtN2IyOWNlZjJhZTYyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
---

## Tech Stacks
- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)
- **Project Charter File**
- **Power BI Service**

---

## Power BI Techniques Learned
- Key questions to ask before starting a project.
- Creating calculated columns and measures using DAX.
- Data modeling best practices.
- Using bookmarks to switch between visuals.
- Page navigation with buttons for better user experience.
- Using the `DIVIDE` function to prevent division by zero errors.
- Creating a date table using M language for time intelligence.
- Dynamic titles based on applied filters.
- Implementing KPI indicators.
- Conditional formatting using icons or background colors in visuals.
- Data validation techniques for accurate reporting.
- Publishing reports to Power BI Services.
- Setting up a personal gateway for auto-refresh.
- Power BI App creation and collaboration via workspaces and access permissions.

---

## Business Terminology
- **Gross Price**
- **Pre-invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** - Cost of Goods Sold
- **YTD** - Year to Date
- **YTG** - Year to Go
- **Direct Retailers**
- **Distributors**
- **Consumers**

---

## Company Background
AtliQ Hardware has grown rapidly in recent years and expanded its operations globally. The company sells computers and accessories via three channels:
- **Retailers**
- **Direct**
- **Distributors**

Recently, AtliQ faced an unexpected loss due to opening a store in America based on intuition rather than solid analytics. Competitors already had dedicated analytics teams to make data-driven decisions. AtliQ Hardware has now committed to building its analytics team to gain valuable insights and make informed business decisions in the future.

---

## Project Kickoff Session
During the project kickoff, it is essential to clarify all aspects of the project, including:
- The objective of building the Power BI dashboard.
- Success metrics for the project.
- Project timeline and deadlines.
- Stakeholder expectations for previews before the final release.
- Fears or concerns stakeholders have about the project.
- The purpose of the dashboard and who will be using it.
- Stakeholder expectations and possible risks.
- Required resources and data for dashboard development.
- Stakeholder input on dashboard design and views.

---

## Dataset Understanding
Understanding the dataset is critical for accurate analysis. The dataset contains:

- **Dimension Table**: Static data such as customer and product details.
- **Fact Table**: Transactional data for sales and forecasting.

### Key Tables
- **dim_customer**: Contains customer information across 27 markets and two platforms (Brick & Mortar, E-commerce).
- **dim_market**: Contains market details across 27 markets, seven sub-zones, and four regions.
- **dim_product**: Product data across divisions (Peripherals, PC, Networking, etc.).
- **fact_forecast_monthly**: Forecasting customer demand to improve satisfaction and reduce warehouse costs.
- **fact_sales_monthly**: Sales data, structured similarly to the forecast table, but with actual sales values.
- **freight_cost**: Travel and other costs per market.
- **gross_price**: Gross prices by product code.
- **manufacturing_cost**: Manufacturing costs by product and year.
- **pre_invoice_deductions**: Pre-invoice deductions percentage for customers.
- **post_invoice_deductions**: Post-invoice deductions and additional deductions.

---

## Importing Data into Power BI
The dataset is sourced from a MySQL database. The data is imported into Power BI by providing the database access credentials.

---

## Data Modeling
Data modeling forms the foundation of the Power BI report. Poor data modeling can negatively impact report performance. In this project, we followed the **Snowflake Data Modeling Method** to ensure efficiency and scalability.

![DATA MODEL](https://github.com/user-attachments/assets/3dc586ef-8ce1-4609-af86-2701f9ec85ed)
---

## Dashboard Design
Based on the received mockups, the team designed various views and created necessary measures for the dashboard:

## Home View: 
A landing page with navigation buttons for all views.

![HOME](https://github.com/user-attachments/assets/469039ef-90b9-4ab7-b225-c79d0f02b304)

## Info:

![INFO](https://github.com/user-attachments/assets/ecfd0cd1-eab0-437d-b9cd-7ff8e721d448)

## Finance View: 
Key financial metrics and insights.

![FINANCE](https://github.com/user-attachments/assets/ad5a455a-07a4-409a-b461-93585f62249f)

## Sales View:
Sales performance across markets and channels.

![SALES](https://github.com/user-attachments/assets/2294980c-1f53-41fd-bd49-c9f981b1f3ff)

## Marketing View:
Marketing KPIs and campaign performance.

 ![MARKETING](https://github.com/user-attachments/assets/ecb3e97c-d788-4a45-9694-06be1baf73e6)
 
## Supply Chain View: 
Insights into the supply chain and inventory management.

![SUPPLY CHAIN](https://github.com/user-attachments/assets/3f9b2520-e1be-4af5-98e3-c43c3605f1fe)

## Executive View: 
High-level executive summary of business performance.

![EXECUTIVE](https://github.com/user-attachments/assets/0717c41f-734f-491e-a7d5-f5306b9e0f3c)

## Support:

![SUPPORT](https://github.com/user-attachments/assets/3003b83b-5b5b-480f-adb9-ec8e7eb06861)


---

## Project Outcome
This dashboard will help AtliQ Hardware make informed decisions based on data. It answers several critical business questions and supports deeper analysis in areas like Finance, Sales, Marketing, and Supply Chain.
