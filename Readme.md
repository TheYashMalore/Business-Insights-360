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
