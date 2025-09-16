#<h1 align="center"> Business Insights 360 - AtliQ Hardware </h1>

## Project Overview

AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

I worked on this project by following the Codebasics PowerBi Course, 

Here is my report link - 

Here is my presentation link - 

## Problem Statement

AtliQ, a business with operations expanding across multiple countries, was struggling with the increasing complexity of its operations. Despite their rapid growth, the company was relying heavily on Excel for data analysis, which was time-consuming, error-prone, and lacked scalability. This caused inefficiencies in decision-making and led to significant financial losses, particularly in their Latin American market, due to the inability to extract meaningful insights from their data in real time.

### Tech Stack used
* SQL
* Power BI Desktop & Power BI Service
* Excel
* DAX Studio
* Project Charter file 
<br><br>

# Data Sources
  The dashboard gathers data from two primary sources:

&nbsp;&nbsp;&nbsp;&nbsp;**1. Excel/CSV Files:** Targets and Market Share data and related information are sourced from Excel and CSV files.

&nbsp;&nbsp;&nbsp;&nbsp;**2. MySQL Database**: Facts and Dimension for all departments are retrieved from a MySQL database.

## Datasets:

Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions

### Data Modeling
* Established Data modeling between 15 tables
* Establishing the right relationships between tables is crucial for correct & effective Data analysis
* Utilized Snowflake Schema for Data modeling
<img align="center" src="https://github.com/TheYashMalore/Business-Insights-360/blob/main/Screenshot%202025-09-16%20112219.png" height="600" width="1400">
<br><br>

### Dashboard View
* <h3>Home Page: Centralized hub for seamless Page navigation</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/fc120612-1875-4833-a37d-7309d22f5a3d.png" height="540" width="960"> <br><br><br>
* <h3>Finance view: Financial metrics analysis</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/36ce93ee-6fce-4a3b-b46d-2e38fbf6c04a.png" height="540" width="960"> <br><br>
* <h3>Sales view:</b> Sales performance insights</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/746cb5be-206d-4cf5-b544-48f28658016c.png" height="540" width="960"> <br><br>
* <h3>Marketing view: Marketing strategy insights</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/a5352dbe-6ba4-4b09-8175-5ac160c4a79c.png" height="540" width="960"> <br><br>
* <h3>Supply Chain view: Supply chain metrics & Operations optimization</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/a699e665-dae5-4672-a0be-3552f0205f09.png" height="540" width="960"> <br><br>
* <h3>Products view: Insights on Key products & customers</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/2967e1fc-d93c-4f59-934a-efc91d136f13.png" height="540" width="960"> <br><br>
* <h3>Executive view: Historical metrics customized for Executive members that enables strategic decision making</h3> <img align="center" src="https://mavenanalyticsio-upload-bucket-prod.s3.us-west-2.amazonaws.com/195370316/projects/4114838b-8b65-467a-b6b1-83f9bc6772a3.png" height="540" width="960"> <br><br>

<a href="https://app.powerbi.com/links/OzMUi-GqA9?ctid=8a4497cd-19ec-4c9a-87c0-06f4d0fe41ec&pbi_source=linkShare"> View Live Dashboard </a> <br><br>

### KPIs & Metrics
* Key Performance Indicatos(KPIs):
  - Net Sales, Gross Marign%, Net Profit%, Forecast Accuracy%, Net Error & Absolute Error

* Key Metrics:
  - Profit & Loss Statement
  - Inventory Risk
  - Gross Margin & Gross Margin% Variance
  - AtliQ's Market Share & Revenue Contribution 
<br><br>

### Insights
* <b>Finance:</b>
  - Exponential growth in Net Sales observed every year since inception, with a 353.5% growth in FY 2022
  - Rapid expansion since 2021 has resulted in a loss of 14%
  - Peak sales period occurs between October to December each fiscal year
* <b>Sales:</b>
  - Amazon and AtliQ Exclusive are key customers, contributing $496.9 million and $361.1 million in Net Sales, respectively
  - The best-selling product is "AQ HOME Allin 1 Gen 2," with Net Sales of $213 million in FY 2022
* <b>Marketing:</b>
  - The APAC region contributes the highest sales volume
  - Spain is the most profitable market, with a 7.7% Net Profit margin
  - The 'Notebook' segment and 'Business Laptop' category have the highest demand and Net Sales
  - Operational Expenses are consistently high due to rapid market expansion
* <b>Supply Chain:</b>
  - Forecast accuracy has been around 80% each fiscal year, but stockouts (OOS) and excess inventory issues are leading to missed sales opportunities and increased costs
* <b>Products:</b>
  - Top 5 markets by revenue are India, USA, South Korea, UK, and Canada
  - The AQ 5000 series Electron 8 5900X Desktop Processor has the highest Gross Margin % in the top 5 markets
* <b>Executive:</b>
  - The Retailer Channel and PCs Division are the highest contributors to revenue
  - The top 5 customers contribute to 38.7% of the revenue, with Amazon leading at 13.6%
  - AtliQ's Market Share increased to 5.9% in FY 2022
  - North America sub-zone contributes 26% of revenue, the highest
  - In South Europe, AtliQ’s Market share increased by up to 6.6%
<br><br>

### Recommendations
* Continue evaluating financial metrics through yearly P&L statements
* During market expansion, optimize operational expenses to minimize losses
* Run promotional campaigns and social media contests for customers and consumers during the peak sales period of the festive season to further boost sales
* Optimize discount strategies for certain customers to increase Gross Margin and reward customers with better sales performance
* In South Korea, new customers can be acquired as no new customers have been gained in the last four years.
* Optimize inventory levels to reduce risks like stockouts (OOS) and excess inventory
* Involve cross-functional teams in the forecasting process to ensure effective planning and maximize resource utilization, reducing risks such as OOS or excess inventory
* Conduct surveys in the LATAM region to better understand consumer behavior and focus on products with the highest demand, ensuring better market penetration
<br><br>

### Key Enhancements to the Dashboard
* Pop-ups for Information & to Find support for users enhanching User Experience
* Seamless Page Navigation
* Data refreshed button & Data last loaded button
<br><br>
### Business Terms Learned:
Gross Margin, Gross Margin %, Gross Sales, Gross Sales %, Pre-invoice deductions, Post-invoice deductions, Net sales, Net Invoice Sales, Net Profit, Net Profit %, COGS (cost of goods sold), YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

### Conclusion
Through this Business Insights 360 project, I've developed a customized report for AtliQ Hardware that is user-friendly, optimized the dashboard for swift performance & empowered AtliQ Hardware with strategic data driven decision making abilities.
