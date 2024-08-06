# Business-Insights-360-Power-BI
Introduction

Welcome to the repository for the Power BI report developed for AtliQ Hardware, a fictitious company in the computer hardware industry. AtliQ Hardware operates by supplying products to a diverse range of customers, including major retailers, distributors, and direct channels, ultimately catering to end consumers.

Objective

* The primary objective of this project is to leverage the powerful data visualization and analysis capabilities of Power BI to derive actionable insights across various business dimensions. 

* These include finance, sales, marketing, supply chain, and executive views. The project aims to enhance decision-making processes, identify growth opportunities, and improve overall business performance by doing so.

Sample View
![Screenshot (164)](https://github.com/user-attachments/assets/fe4b6bb8-9e81-42d9-9df4-832249898731)

Database Schema

* Dimension Tables

dim_customer

75 distinct customers throughout the market
2 types of platforms: Brick & Mortar (Physical/offline store) and E-commerce (Online Store)
Three channels: Retailer, Direct, Distributors

dim_market

27 distinct markets (e.g., India, USA, Spain)
7 sub-zones
4 regions: APAC, EU, nan, LATAM

dim_product

Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage
14 different categories (e.g., Internal HDD, keyboard)
Different variants available for the same product

* Fact Tables

fact_forecast_monthly

Used to forecast the customer’s need in advance, leading to higher customer satisfaction and reduced storage costs.
Renormalized by the data engineering team for analytical work.
The dates of the month are replaced by the start date of the month.
Contains forecast quantities needed by the customer.

fact_sales_monthly

Similar to the fact_forecast_monthly table, but with actual sold quantities.

Miscellaneous Data

freight_cost: Details of travel cost and other costs for each market with fiscal year

gross_price: Details of gross prices with product code

manufacturing_cost: Details of manufacturing cost with product code and year

Pre_invoice_deductions: Details of pre-invoice deductions percentage for each customer with year

Post_invoice_deductions: Details of post-invoice deductions and other deductions

Note: The Database which has both fact and dimension tables, consists of more than 1.4 Million records of different products, customers, purchases, etc..



Key Achievements and Impact:

In this Power BI project, several important techniques and tools were utilized to achieve impactful results. Here are the key achievements and their impact on AtliQ Hardware:

* Exploratory Data Analysis using SQL:

Achievement: Conducted thorough exploratory data analysis to uncover initial patterns and insights.

Impact: Laid a strong foundation for further analysis and ensured data readiness for visualization.

* Connecting SQL and Power BI:

Achievement: Established seamless connections between SQL databases and Power BI.

Impact: Enabled efficient data retrieval and integration, facilitating real-time analysis.

* Data Shaping with Power Query:

Achievement: Transformed and cleaned data using Power Query to prepare it for analysis.

Impact: Improved data quality and relevance, ensuring accurate insights.

* Building Data Models:

Achievement: Created robust data models to organize and relate various data sources.

Impact: Enhanced data consistency and enabled complex analyses across multiple dimensions.

* Crafting Date Tables using M Language:

Achievement: Developed custom date tables to support time-based analysis.

Impact: Provided precise time-related insights, crucial for trend analysis and forecasting.

* Crafting Measures with DAX:

Achievement: Defined advanced measures using DAX for in-depth analysis.

Impact: Enabled sophisticated calculations and metrics, enhancing the depth of insights.

* Understanding Filter Context:

Achievement: Mastered filter context in DAX to ensure accurate calculations.

Impact: Delivered more precise and contextually relevant insights.

* Using Bookmarks for Visual Switching:

Achievement: Implemented bookmarks to facilitate seamless switching between visuals.

Impact: Improved user experience and navigability within the reports.

* Page Navigation through Buttons:

Achievement: Added buttons for intuitive page navigation.

Impact: Enhanced report interactivity and usability.

* Conditional Formatting:

Achievement: Applied conditional formatting to highlight key insights.

Impact: Made reports more engaging and visually appealing.

* KPI Indicators:

Achievement: Incorporated KPI indicators to track key performance metrics.

Impact: Provided quick and clear visibility into critical business metrics.

* Generated Columns:

Achievement: Utilized generated columns to enhance data analysis.

Impact: Improved analytical capabilities by creating new data attributes.

* Performance Optimization with DAX Studio:

Achievement: Optimized report performance using DAX Studio.

Impact: Ensured faster data processing and a smoother user experience.

* Tools Used:

MySQL: For managing and querying databases.

Power BI Desktop: For building and visualizing reports.

MS Excel: For initial data manipulation and analysis.

DAX Language: For creating measures and calculated columns.

DAX Studio: For optimizing DAX queries and improving report performance.

These achievements collectively enhanced AtliQ Hardware's data-driven decision-making capabilities, enabling the company to gain valuable insights across finance, sales, marketing, supply chain, and executive views.




