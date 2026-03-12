# Sales & Profit Analysis Dashboard (Power BI)

## Project Overview

This project presents a **Power BI dashboard designed to analyze sales performance, profitability, and customer behavior** using a retail dataset.
The goal of the project is to transform raw transactional data into actionable business insights through interactive visualizations and well-structured analytics.

The dashboard focuses on three key analytical perspectives:

* **Overall business performance**
* **Product and profitability analysis**
* **Customer behavior and revenue contribution**

The project demonstrates core data analysis skills including **data modeling, DAX measures, KPI design, and business-oriented visualization.**

---

# Dataset

The dataset used in this project is based on a retail sales dataset that includes transactional information such as:

* Order ID
* Customer Name
* Product
* Category
* Region
* State
* Sales
* Profit
* Quantity
* Order Date

From this data, several analytical measures were created to evaluate business performance.

---

# Key Metrics (DAX Measures)

The dashboard includes several calculated measures created in Power BI:

Total Revenue
Total Profit
Profit Margin
Orders per Customer
Year-over-Year Growth (YoY)

Example DAX measures:

Total Revenue =
SUM(Sales[Sales])

Profit Margin =
DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales]))

Sales LY =
CALCULATE([Total Revenue], SAMEPERIODLASTYEAR(Calendar[Date]))

YoY Growth % =
DIVIDE([Total Revenue] - [Sales LY], [Sales LY])

---

# Dashboard Structure

The report is divided into **three analytical pages**.

## 1. Business Overview

Provides a high-level view of company performance.

Key visuals:

* KPI Cards (Total Revenue, Profit Margin, Orders per Customer)
* Sales Trend Over Time
* Segment Contribution to Sales
* Sales by State

Purpose:
Understand overall performance and growth trends.

---

## 2. Product Profitability Analysis

Focuses on product and category-level profitability.

Key visuals:

* Sales vs Profit Scatter Plot
* Profit Margin by Category
* Top Performing Products
* Products Generating Negative Profit

Purpose:
Identify profitable products and detect loss-generating items.

---

## 3. Customer Performance Analysis

Analyzes customer contribution and purchasing behavior.

Key visuals:

* Customer Profit Margin Distribution
* Sales by Customer
* Orders per Customer KPI
* Sales by Geographic Location

Purpose:
Understand which customers generate the most revenue and which contribute the most to profitability.

---

# Key Insights

The dashboard enables the following types of insights:

* Identification of **top revenue-generating customers**
* Detection of **products generating negative profit**
* Analysis of **sales and profitability distribution across categories**
* Evaluation of **customer purchasing patterns**
* Geographic distribution of sales performance

---

# Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

---

# Skills Demonstrated

This project demonstrates practical skills relevant to a **Data Analyst role**, including:

* Data transformation
* Business metric design
* KPI development
* Analytical storytelling with dashboards
* Visualization best practices
* Profitability and customer behavior analysis

---

# Repository Structure

PowerBI-Sales-Dashboard/

dataset/
sales_dataset.csv

dashboard/
sales_analysis_dashboard.pbix

images/
dashboard_overview.png

README.md

---

# Future Improvements

Possible future improvements include:

* Adding a **geographical map visualization**
* Implementing **customer segmentation (RFM analysis)**
* Creating **forecasting models for sales trends**
* Integrating the dashboard with a **live data source**

---

# Author

Marcos Capponi

Aspiring Data Analyst focused on data analytics, data engineering, and international opportunities in the data field.
