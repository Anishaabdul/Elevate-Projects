#  1 .Retail Business Performance& Profitability Analysis 
# Project Title
Retail Sales Data Analysis using SQL and Power BI

---
# Project Description
This project focuses on analyzing retail sales data using SQL for data processing and Power BI for visualization. The objective is to extract meaningful insights from the dataset to support business decision-making.
The analysis includes total sales calculation, category-wise performance, regional analysis, and monthly sales trends.

---
# Tools & Technologies Used
MySQL (phpMyAdmin – XAMPP)
SQL (Structured Query Language)
Power BI
Jupyter Notebook (for data cleaning)
Microsoft Excel (if applicable)

---
# Dataset Description
The dataset contains retail transaction records including:
Transaction_ID
Product_Name
Product_Category
Quantity
Price_per_Unit
Total_Amount
Date
Region

---
# Data Processing
Cleaned dataset using Jupyter Notebook
Removed missing values
Standardized column names
Exported cleaned dataset for analysis
Imported dataset into MySQL database

---
# Database Implementation
Created database: retail_db
Created table: retail_sales_dataset
Inserted retail transaction data
Executed SQL queries for analysis

---
# SQL Analysis Performed
Retrieve all records
Calculate total sales using SUM()
Calculate total quantity sold
Category-wise sales analysis using GROUP BY
Region-wise sales analysis
Identify top-selling product using ORDER BY
Monthly sales trend using MONTH() function

---
# Power BI Dashboard
The Power BI dashboard includes:
Total Sales KPI
Total Quantity KPI
Sales by Category (Bar Chart)
Sales by Region (Pie Chart)
Monthly Sales Trend (Line Chart)
Top-Selling Product Analysis

---
# Key Insights
Electronics category generated the highest revenue.
Certain regions contributed more to overall sales.
Monthly analysis showed consistent sales growth.
High-demand products were identified for strategic planning.

---
# Conclusion
The project demonstrates how SQL and Power BI can be used together to perform data analysis and generate business insights. The findings help in improving decision-making, inventory planning, and marketing strategies.

---
# Files Included
retail_db.sql
Retail_Sales_Dashboard.pbix
cleaned_retail_dataset.csv
Project_Report.pdf

---
# 2 . Customer Lifetime Value (LTV) Prediction Model
# Project Overview
This project predicts Customer Lifetime Value (LTV) based on customer purchase behavior using Machine Learning.
The goal is to help businesses identify high-value customers for targeted marketing and retention strategies.

---
# Objective
To build a regression model that predicts customer lifetime value using:
Recency
Frequency
Average Order Value (AOV)

---
# Dataset
Online Retail Dataset (E-commerce Data)
Source: Kaggle
Link: https://www.kaggle.com/datasets/carrie1/ecommerce-data
The dataset contains transactional data including:
InvoiceNo
StockCode
Description
Quantity
InvoiceDate
UnitPrice
CustomerID
Country

---
# Tools & Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn (Random Forest Regressor)

---
# Project Workflow
1️. Data Preprocessing
Removed missing CustomerID values
Removed negative quantities and prices
Created TotalPrice column

2️. Feature Engineering (RFM Model)
Recency – Days since last purchase
Frequency – Number of unique invoices
Monetary – Total spending
AOV – Average Order Value

3️. Model Training
Train-test split (80-20)
Random Forest Regressor used
Model trained on RFM features

4️. Model Evaluation
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)

5️. Visualization
Feature Importance Plot
Actual vs Predicted LTV
LTV Distribution
Customer Segmentation Chart

6️. Customer Segmentation
Customers segmented into:
Low Value
Medium Value
High Value

---
# Results
Frequency was the most important predictor of LTV.
High AOV customers contribute significantly to revenue.
Top 33% customers generate majority of revenue.

---
# Deliverables
 Jupyter Notebook (.ipynb)
 Trained ML Model
 Visualizations
 Final_LTV_Predictions.csv
 Project Report (PDF)

---
# Business Impact
Helps in targeted marketing
Identifies high-value customers
Improves customer retention strategies
Increases revenue optimization

---
