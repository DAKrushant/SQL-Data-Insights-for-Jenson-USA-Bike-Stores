# 📊 SQL Data Insights for Jenson USA – Bike Stores
### Author: Krushant Shah

  - This project delivers SQL-based business insights for Jenson USA, a multi-store bike retailer.
  - Using the BikeStores relational database, the analysis focuses on customer behavior, staff performance, inventory health, and store operations.

  The project includes 12 analytical SQL queries, each answering a real business question that supports data-driven decision making.

### 🚀 Project Objectives

  - The goal of this project is to use SQL to uncover insights across:

### ✅ Customer Behavior

  - Who are the highest-spending customers?
  - How often do customers purchase from each store?
  - Which customers purchase across all product categories?

### ✅ Staff Performance

  - Which staff generate the most sales?
  - Who has zero sales and may require attention/training?

### ✅ Inventory Insights

  - Top-selling products
  - Highest-priced products in each category
  - Products that have NEVER been ordered

### ✅ Store Operations

  - Store-wise sales performance
  - Category revenue leaders
  - Product demand trends over time

### 🗂 Dataset / Schema
This project is based on the BikeStores dataset provided for analysis.

#### Key tables include:

  ### Table Name	Description
      stores    	Store locations & details
      staff	      Employee details
      customers	  Customer master data
      products	  Product catalog
      categories	Product categories
      orders	    Customer orders
      order_items	Line-level product data
      stocks	    Store inventory quantities

The complete data dictionary is provided in bikestores_data_dictionary.pdf.

### 🧠 Key SQL Concepts Used

  - JOINS (Inner, Left)
  - GROUP BY & Aggregations
  - Window Functions (ROW_NUMBER, SUM OVER)
  - Subqueries & CTEs
  - EXISTS / NOT EXISTS
  - Ranking queries
  - Median calculation logic
  - Business logic formulation using SQL

### 📝 Insight Queries Included
#### ▶️ How to Run This Project

  - Install MySQL 8+
  - Create the schema using Bikes - create objects.sql
  - Load sample data using Bikes - load data.sql
  - Open Jensons_Data_Insights_Queries.sql
  - Run queries individually to generate insights
  - This workflow ensures the dataset is built correctly before analysis.

### 📌 Deliverables

  - SQL Queries
  - Database Schema
  - Data Dictionary
  - Business Insights
  - GitHub-ready project structure
  - Markdown documentation (README.md)

