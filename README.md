# E-Commerce-Sales-Analytics-Dashboard-2022
Interactive E-Commerce Sales Analytics Dashboard built using Google Looker Studio. Includes product performance analysis, customer insights, YoY sales comparison, and campaign evaluation based on internship tasks using the training dataset.
E-Commerce Sales Analytics Dashboard – 2022
🔹 Project Overview

This project extends the training dataset analysis by implementing additional internship tasks as interactive dashboards and analytical reports using Google Looker Studio.

The dashboard provides insights into:

Sales performance (2022)

Product performance & YoY comparison

Customer checkout behavior

Campaign effectiveness (Weekend vs Weekday analysis)

Category-level trends

All analysis was performed using the same dataset provided during training (finaldataset_cleaned.csv).

🔹 Tools Used

Google Looker Studio (Dashboard & Reporting)

CSV Dataset (Training Project Dataset)

Basic Data Transformation using Calculated Fields

🔹 Dataset

Dataset Used: finaldataset_cleaned.csv

Key fields:

order_date

year

category

sku_name

qty_ordered

before_discount

is_valid

is_gross

is_net

customer_id

registered_date

🔹 Data Transformations Applied

Converted order_date to proper date format

Filtered valid orders using is_valid = 1

Created calculated fields:

Sales 2021 vs Sales 2022

Sales Difference (YoY)

Percentage Change

Sales Status (UP / DOWN / FAIR)

Weekend vs Weekday classification

Handled division-by-zero issues in % change calculation

Removed duplicate customer_id using COUNT DISTINCT

🔹 Dashboard Pages
1️⃣ Executive Overview – 2022

Total Revenue

Total Quantity Sold

Total Orders

Total Customers

Monthly Sales Trend

Category Performance Trend

2️⃣ Product Performance Analysis

Top 5 Products – Mobiles & Tablets (Valid Orders, 2022)

Top 20 Sales Decrease – Others Category (YoY)

Percentage Change & Status Classification

3️⃣ Customer Insights

Total Customers

Checkout Completed but Payment Pending (2022)

Customer Registration Trend

Affected Customer List

4️⃣ Campaign Performance (Q4 2022)

Weekend vs Weekday Sales Comparison

Average Daily Sales Analysis

Campaign Effectiveness Insights

🔹 Key KPIs Measured

Total Revenue (Before Discount)

Total Quantity Sold

Year-over-Year Sales Difference

Percentage Sales Change

Customer Checkout Drop-offs

Weekend Campaign Impact

🔹 Business Insights

Weekday sales generally outperform weekend promotional campaigns.

Several products in the "Others" category experienced significant YoY decline.

Mobiles & Tablets dominate 2022 category sales.

A segment of customers completed checkout but did not complete payment, presenting marketing opportunity.

🔹 Interactive Features

Year Dropdown Filter

Category Filter

Date Range Control

Drill-down by Product

Conditional Formatting for Sales Status

🔹 Live Dashboard Link
https://lookerstudio.google.com/reporting/ec9e93c6-d446-42a6-ab0b-e0bb8e06c4c4
👉 

