# Retail-Store-Data-Warehouse-DFF

Retail Store Data Warehouse (DFF)
📌 Project Overview
This project focuses on the design and implementation of a data warehouse for Dominick’s Finer Foods (DFF), a former grocery store chain in Chicago. The dataset, originally collected in partnership with the Chicago Booth School of Business, contains store-level data from 1989 to 1994, covering 100 stores and over 3,500 Universal Product Codes (UPCs) across 25 different product categories.

The primary objective was to build a scalable data warehouse that enables retail analytics, including pricing strategies, inventory management, sales trends, and customer behavior analysis.

🎯 Project Goals
The project aimed to:

Develop a Data Warehouse: Implement a star schema design for efficient querying.
Implement ETL Processes: Extract, transform, and load (ETL) data from raw CSV files.
Analyze Business Metrics: Generate insights into sales trends, promotional effectiveness, and store performance.
Optimize Data Storage and Retrieval: Use Kimball’s methodology to design a structured and efficient warehouse.
📊 Business Problems Addressed
The project leverages historical data to answer key business questions, including:

Pricing Strategies: How do different pricing models impact sales and profitability?
Inventory Optimization: How can shelf space and stock levels be improved?
Competitive Analysis: How do different brands perform across categories?
Promotional Effectiveness: How do promotions influence consumer purchases?
Sales Trends: Which categories have declining or increasing sales over time?
Demographics & Buying Patterns: How does customer income level influence purchase behavior?
Coupon Redemption Insights: What are the most effective promotions and buyback offers?
🏗 Methodology & Implementation
🔹 Data Warehouse Design
Star Schema Model: Implemented for structured storage and fast retrieval.
Fact Tables:
Store_Fact: Captures weekly sales data for different product categories.
Movement_Fact: Tracks product movement (sales, quantity, and pricing).
Dimension Tables:
Store_Dim: Stores demographic data of each retail outlet.
Product_Dim: Stores UPC-level product details.
Time_Dim: Provides a structured time-based reference for analysis.
Movement_Dim: Stores promotional and sales campaign data.
🔹 ETL Process
The ETL (Extract, Transform, Load) pipeline was built using Microsoft SQL Server Integration Services (SSIS) and included:

Data Extraction: Collected structured data from CSV and SAS files.
Data Cleaning & Transformation: Handled missing values, duplicate records, and inconsistent formats.
Data Loading: Processed data into the final fact and dimension tables for analytics.
🔹 Technologies Used
Data Processing: Microsoft SQL Server (SSIS, SSMS)
Data Modeling: Star Schema, Kimball’s Dimensional Modeling
ETL Tools: SQL Server Integration Services (SSIS)
Data Storage: SQL Server Database
Visualization & Analytics: Pivot tables, charts, and SQL queries
📌 Key Insights from the Project
High-demand products: Identified top-selling product categories for better stock management.
Seasonal trends: Analyzed holiday season sales of alcohol and grocery items.
Customer segmentation: Understood purchasing patterns based on income demographics.
Coupon efficiency: Evaluated which brands benefited most from promotional discounts.
Declining categories: Identified products with a year-over-year decrease in sales.
