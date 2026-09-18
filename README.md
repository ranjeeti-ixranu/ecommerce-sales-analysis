# E-Commerce Sales Analysis

## Project Overview

This project analyzes an e-commerce sales dataset of 800 orders to identify product, regional, category, discount, and monthly sales performance.

The analysis was completed using **Google Sheets**, including data cleaning, pivot tables, calculated metrics, interactive slicers, and dashboard visualizations.

## Business Questions

* Which products generate the highest sales and profit?
* Which region performs best?
* Which category generates the most sales?
* How does discounting relate to profit margin?
* How do sales change throughout the year?
* What business actions could improve profitability?

## Dataset

The dataset contains 800 e-commerce orders with information including:

* Order ID
* Order Date
* Customer ID
* Product
* Category
* Region
* Quantity
* Unit Price
* Discount
* Sales
* Profit

## Data Cleaning

The dataset contained several quality issues that were addressed before analysis:

* Missing Discount value
* Missing Sales value
* Extra spaces in product names
* Inconsistent region formatting
* Added a Month field for time-based analysis

After cleaning, the data was checked to ensure the key fields were complete and consistently formatted.

## Key Performance Indicators

| KPI           |         Result |
| ------------- | -------------: |
| Total Orders  |            800 |
| Total Sales   | ₹18,093,339.54 |
| Total Profit  |  ₹2,389,159.45 |
| Profit Margin |         13.20% |

## Key Findings

### Product Performance

* **Laptop** was the top-selling product.
* **Laptop** was also the most profitable product.

### Regional Performance

* **West** generated the highest sales.
* **Central** had the highest regional profit margin at **14.24%**.

### Category Performance

* **Electronics** generated the highest sales.

### Discount Analysis

Profit margin increased as discount levels decreased in this dataset.

* 25% discount → 9.98% margin
* 20% discount → 11.25% margin
* 15% discount → 11.94% margin
* 10% discount → 13.49% margin
* 5% discount → 14.45% margin
* 0% discount → 15.29% margin

### Monthly Sales

Monthly sales showed noticeable variation throughout the year, with the highest sales occurring in **May** and lower sales during **October and November**.

## Dashboard

The interactive dashboard includes:

* Total Orders
* Total Sales
* Total Profit
* Profit Margin
* Region slicer
* Product slicer
* Sales by Product
* Profit by Product
* Profit Margin by Region
* Profit Margin by Discount
* Monthly Sales Trend

## Business Recommendations

### 1. Optimize discounting

Reduce unnecessary discounts to protect profit margins.

### 2. Prioritize top products

Focus inventory and marketing efforts on Laptop, the strongest product by sales and profit.

### 3. Replicate regional success

Analyze the West region's performance and identify strategies that could improve other regions.

### 4. Strengthen Electronics

Maintain strong Electronics inventory and explore cross-selling opportunities.

## Tools Used

* Google Sheets
* Pivot Tables
* Data Cleaning
* Calculated Metrics
* Charts
* Slicers
* Business Analysis

## Project Outcome

This project demonstrates a complete beginner-level data analysis workflow:

**Data Cleaning → Analysis → Visualization → Dashboard → Business Insights → Recommendations**

## Dashboard Preview

![E-Commerce Sales Analysis Dashboard](dashboard.png)
