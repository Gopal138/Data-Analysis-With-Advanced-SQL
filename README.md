# Data-Analysis-With-Advanced-SQL
QL-based Exploratory Data Analysis (EDA) and Advanced Analytics on retail sales data — includes trend analysis, customer segmentation, performance metrics, and business insights using SQL queries.
Exploratory Data Analysis & Advanced Analytics Project – Sales & Customer Insights

This project focuses on performing comprehensive Exploratory Data Analysis (EDA) and Advanced Analytics on a retail dataset to uncover actionable business insights. The analysis is structured in progressive phases—starting from basic exploration to in-depth customer segmentation and performance evaluation.

🔍 Objectives:
Understand the structure and quality of the data.

Explore key dimensions (like country, product category, birthdate) and measures (like sales, quantity, price).

Identify sales patterns, customer behavior, and product performance over time.

Segment customers based on purchase history, age group, and spending behavior.

🗂️ Datasets Used:
gold.dim_customers – Contains customer demographic details.

gold.dim_products – Includes product metadata like category, subcategory, and cost.

gold.fact_sales – Records transactional data such as sales amount, quantity, price, and order date.

🔧 Project Workflow:
✅ Step 1: Database & Column Exploration
Listed available tables and columns from the database using INFORMATION_SCHEMA.

Understood structure and relationship between fact and dimension tables.

✅ Step 2: Dimension Exploration
Category Analysis: Identified product categories, subcategories, and product counts.

Date Analysis: Analyzed order date range, earliest/latest transactions.

Customer Birthdate Analysis: Found youngest and oldest customers.

✅ Step 3: Measure Exploration
Calculated total sales, average price, total quantity sold, number of orders, total products, and total customers.

Generated a key metrics summary report using UNION queries.

✅ Step 4: Magnitude Analysis
Compared customer count by country and gender.

Compared product counts and average costs by category.

Evaluated total revenue by category, customer, and country.

✅ Step 5: Ranking Analysis
Identified Top 5 best-selling and worst-performing products based on revenue.

📈 Advanced Data Analytics:
1. Change Over Time (Trend Analysis)
Analyzed total sales, unique customers, and quantity sold yearly and monthly.

Used DATETRUNC() for monthly time-series analysis.

2. Cumulative Analysis
Calculated running total of monthly and yearly sales using WINDOW FUNCTIONS.

Implemented moving average to track pricing trends over time.

3. Performance Analysis
Compared product sales performance against average product sales and previous year’s performance.

Derived insights like "Above/Below Average" and "Increasing/Decreasing" using LAG() and CASE statements.

4. Part-to-Whole (Proportional) Analysis
Calculated contribution percentage of each product category to total revenue.

5. Data Segmentation
Segmented products by cost range (e.g., Below 100, 100–500).

Segmented customers by spending behavior and lifespan into:

VIP (long-term & high spending),

Regular (long-term & low spending),

New (short-term).

📊 Final Output: Customer Report View
Created a dynamic SQL VIEW named customer_report that includes:

Demographic details (name, age group).

Transaction KPIs (total orders, total sales, quantity, and products).

Behavioral segmentation (VIP, Regular, New).

Customer lifetime value metrics:

Lifespan

Recency

Average Order Value

Monthly Spend

📌 Tools & Concepts Used:
SQL (Window Functions, CTEs, Aggregations, Joins, CASE, Views)

Time Series Analysis

Customer Segmentation

Performance Benchmarking

Trend & Proportional Analysis

📁 Project Outcome:
This project demonstrates strong SQL skills applied to real-world data analysis. The insights derived help in:

Identifying high-value customers

Tracking business growth

Evaluating product performance

Driving data-driven decisions in sales and marketing

