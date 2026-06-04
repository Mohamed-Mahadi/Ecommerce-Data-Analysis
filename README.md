E-Commerce Sales Analysis (SQL Project)
Project Overview

This project analyses an e-commerce transaction dataset containing over 500,000 records. The goal was to answer key business questions related to sales performance, customer behaviour, product performance, geographic trends, and operational efficiency using SQL.

The analysis was conducted using PostgreSQL and focuses on transforming raw transactional data into actionable business insights.

Business Questions
Sales Performance Analysis
How is the business performing overall?
What are the monthly revenue trends?
How do orders, customers, and average order value change over time?
Product Analysis
Which products generate the most revenue?
Which products sell the highest quantities?
Which products perform poorly?
Customer Analysis
Who are the most valuable customers?
How much does the average customer spend?
What percentage of customers are repeat customers?
Geographic Analysis
Which countries generate the most revenue?
Which countries place the most orders?
Operational Analysis
How significant are cancellations?
Which countries experience the most cancellations?
Dataset

The dataset contains transaction-level e-commerce data, including:

Invoice Number
Product Information
Quantity Sold
Unit Price
Customer ID
Invoice Date
Country
Data Quality Checks

The following issues were identified and addressed:

Missing Customer IDs
Cancelled Orders (Invoice numbers beginning with "C")
Bad Debt Adjustments (Invoice numbers beginning with "A")
Invalid Pricing Records (Unit Price ≤ 0)

Records that could distort sales analysis were excluded from relevant calculations.

Tools Used
PostgreSQL
SQL
Microsoft Word (report documentation)
GitHub

Key Findings
1. Strong Seasonal Sales Performance

Revenue peaked between September and November, with November generating approximately £1.16 million in revenue.

Business Impact:
The business experiences significant seasonal demand during the final quarter of the year, highlighting the importance of inventory and operational planning.

2. Customer Growth Drives Revenue

Revenue growth was primarily driven by increases in both customer numbers and order volume rather than significant increases in average order value.

Business Impact:
Customer acquisition and retention appear to be major drivers of business performance.

3. Strong Customer Retention

Approximately 65.6% of customers were repeat customers.

Business Impact:
The business benefits from a loyal customer base, suggesting that customer retention strategies play a significant role in revenue generation.

4. Revenue is Highly Concentrated in the UK

The United Kingdom generated over £7.3 million in revenue and accounted for the majority of orders.

Business Impact:
While the UK market is a major strength, the business may benefit from diversifying revenue sources through international growth.

<img width="1032" height="580" alt="Screenshot 2026-06-04 011930" src="https://github.com/user-attachments/assets/f9dbdffe-f521-4e79-b653-3f9abbf82f34" />

Recommendations
Increase Preparation for Peak Season

Improve inventory management and marketing efforts ahead of the September–November sales period.

Focus on Customer Retention

Develop loyalty and customer retention initiatives to maximise the value of repeat customers.

Expand International Growth

Explore opportunities to grow revenue in international markets to reduce dependence on the UK market.

Project Structure
Ecommerce-Sales-Analysis/
│
├── README.md
├── Final_Report.pdf
├── SQL/
│   ├── 01_Data_Quality.sql
│   ├── 02_Business_Performance.sql
│   ├── 03_Product_Analysis.sql
│   ├── 04_Customer_Analysis.sql
│   ├── 05_Geographic_Analysis.sql
│   └── 06_Operational_Analysis.sql
│
└── Visualisations/
Skills Demonstrated
SQL Querying
Data Cleaning
Aggregations and Grouping
Date and Time Analysis
Customer Segmentation
Business Analysis
Data Storytelling
Insight Generation
Report Writing
Author

Mohamed Mahadi

This project was completed as part of my data analytics portfolio to demonstrate SQL proficiency and business-focused analytical thinking.
