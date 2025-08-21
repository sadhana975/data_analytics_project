📊 Sales, Customer & Product Analytics using SQL
📌 Project Overview

This project is a SQL-based analytics solution designed to analyze sales, customer behavior, and product performance.
I built this project by following a YouTube tutorial, implementing it from scratch while learning SQL concepts and improving my understanding of data analysis and reporting using SQL.

The project covers:

Sales trends analysis

Running totals and moving averages

Product performance tracking

Customer segmentation (VIP, Regular, New)

KPI reports for management

🛠️ Tech Stack

SQL Server (T-SQL)

Dataset: Provided in tutorial (structured in star schema with fact_sales, dim_products, dim_customers)

📂 Project Structure & Queries
1. Sales Analysis

Sales by year & month

Running totals and moving averages

YoY performance comparison

2. Product Analytics

Yearly product performance vs average

High-performing vs low-performing products

Product segmentation by cost ranges

Created gold.report_products view with KPIs

3. Customer Analytics

Customer segmentation: VIP, Regular, New

Lifetime value and spending behavior

Customer KPIs:

Total orders, sales, quantity, products

Lifespan in months

Recency (months since last order)

Avg Order Value (AOV)

Avg Monthly Spend

Created gold.report_customers view with KPIs

📊 Key SQL Concepts Used

Aggregations (SUM, AVG, COUNT)

Window functions (LAG, SUM OVER, AVG OVER)

CTEs (WITH clause)

Case-based segmentation (CASE WHEN)

Joins (Fact & Dimension tables)

Views (CREATE VIEW)

🎯 Learnings

Writing analytical SQL queries for business insights

Using window functions for running totals, moving averages, and YoY analysis

Creating customer and product segmentation using CASE logic

Building reusable reporting views for business KPIs

Understanding how SQL supports data-driven decision making

🚀 How to Run

Load dataset into SQL Server (tables: fact_sales, dim_products, dim_customers).

Execute the SQL scripts in order:

Sales Analysis queries

Customer Report (gold.report_customers)

Product Report (gold.report_products)

Query the created views to explore results.

📝 Acknowledgment

This project was built by learning from a YouTube tutorial.
I re-implemented the queries from scratch to strengthen my SQL skills and applied additional documentation for better clarity
