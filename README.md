# Retail-Store-Data-Warehouse-DFF

# 🏬 Retail Store Data Warehouse (DFF)

## 📌 Project Overview
This project focuses on the **design and implementation of a data warehouse** for **Dominick’s Finer Foods (DFF)**, a former grocery store chain in Chicago. The dataset, originally collected in partnership with the **Chicago Booth School of Business**, contains **store-level data from 1989 to 1994**, covering **100 stores** and over **3,500 Universal Product Codes (UPCs)** across **25 different product categories**.  

The primary objective was to build a scalable **data warehouse** that enables retail analytics, including **pricing strategies, inventory management, sales trends, and customer behavior analysis**.

---

## 🎯 Project Goals
The project aimed to:
- **Develop a Data Warehouse**: Implement a **star schema** design for efficient querying.
- **Implement ETL Processes**: Extract, transform, and load (ETL) data from raw CSV files.
- **Analyze Business Metrics**: Generate insights into **sales trends, promotional effectiveness, and store performance**.
- **Optimize Data Storage and Retrieval**: Use **Kimball’s methodology** to design a structured and efficient warehouse.

---

## 📊 Business Problems Addressed
The project leverages historical data to answer key business questions, including:
- 📈 **Pricing Strategies**: Impact of different pricing models on sales and profitability.
- 📦 **Inventory Optimization**: Enhancing stock levels and shelf space allocation.
- 🏆 **Competitive Analysis**: Understanding brand performance across product categories.
- 🎯 **Promotional Effectiveness**: How promotions influence consumer purchases.
- 🔄 **Sales Trends**: Identifying product categories with declining or increasing sales.
- 👥 **Customer Segmentation**: Analyzing purchasing patterns based on income demographics.
- 🎟 **Coupon Effectiveness**: Evaluating which brands benefited most from promotional discounts.

---

## 🏗 Methodology & Implementation

### 🔹 Data Warehouse Design
The **Star Schema Model** was implemented for structured storage and fast retrieval.

#### **Fact Tables:**
- `Store_Fact`: Captures weekly sales data for different product categories.
- `Movement_Fact`: Tracks product movement (sales, quantity, and pricing).

#### **Dimension Tables:**
- `Store_Dim`: Stores demographic data of each retail outlet.
- `Product_Dim`: Stores UPC-level product details.
- `Time_Dim`: Provides a structured time-based reference for analysis.
- `Movement_Dim`: Stores promotional and sales campaign data.

### 🔹 ETL Process
The ETL (**Extract, Transform, Load**) pipeline was built using **Microsoft SQL Server Integration Services (SSIS)** and included:

1. **Data Extraction**: Collected structured data from CSV and SAS files.
2. **Data Cleaning & Transformation**: Handled missing values, duplicate records, and inconsistent formats.
3. **Data Loading**: Processed data into the final **fact and dimension tables** for analytics.

### 🔹 Technologies Used
- **Data Processing**: Microsoft SQL Server (**SSIS, SSMS**)
- **Data Modeling**: Star Schema, Kimball’s Dimensional Modeling
- **ETL Tools**: SQL Server Integration Services (**SSIS**)
- **Data Storage**: SQL Server Database
- **Visualization & Analytics**: Pivot tables, charts, and SQL queries

---

## 📌 Key Insights from the Project
- **📊 High-demand products**: Identified top-selling product categories for better stock management.
- **📅 Seasonal trends**: Analyzed holiday season sales of alcohol and grocery items.
- **👥 Customer segmentation**: Understood purchasing patterns based on income demographics.
- **🎟 Coupon efficiency**: Evaluated which brands benefited most from promotional discounts.
- **📉 Declining categories**: Identified products with a year-over-year decrease in sales.

---
