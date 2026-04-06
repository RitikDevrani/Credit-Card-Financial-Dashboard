# Credit Card Financial Dashboard (SQL + Power BI)
## Project Overview

This project focuses on analyzing credit card transaction and customer data using MySQL and Power BI to build an interactive financial dashboard.

The dashboard provides real-time insights into customer behavior, transaction patterns, revenue generation, and financial performance.

## Objectives
The main objectives of this project are:

• Analyze customer spending behavior

• Track transaction trends and revenue

• Understand customer demographics

• Identify high-value customers

• Monitor credit utilization and risk factors

## Database Design
The project uses a structured MySQL database (ccdb) with two main tables:

•  1. cc_detail (Credit Card Transactions)
 
  Client_Num
  
  Card_Category
  
  Annual_Fees
  
  Credit_Limit
  
  Total_Trans_Amt
  
  Total_Trans_Ct
  
  Avg_Utilization_Ratio
  
  Interest_Earned
  
  Delinquent_Acc
  
  Week_Start_Date, Quarter, Year

• 2. cust_detail (Customer Information)
  
  Client_Num
  
  Customer_Age
  
  Gender
  
  Education_Level
  
  Marital_Status
  
  Customer_Job
  
  Income
  
  State_cd
  
  Customer_Satisfaction_Score

## Data Import
Data is imported using MySQL LOAD DATA INFILE:

• credit_card.csv → cc_detail

• customer.csv → cust_detail

## Dashboard Features (Power BI)
The Power BI dashboard includes:

• Total Revenue Analysis

• Transaction Count & Amount

• Customer Segmentation (Age, Gender, Income)

• Credit Utilization Insights

• Delinquency & Risk Analysis

• Weekly & Quarterly Trends

## Key Insights
• High-income customers contribute significantly to total revenue

• Credit utilization ratio helps identify risky customers

• Certain states show higher transaction volumes

• Customers with higher satisfaction scores tend to spend more

• Delinquent accounts indicate potential financial risk

## & Technologies Used
• MySQL (Database & Queries)

• Power BI (Dashboard & Visualization)

• SQL (Data Extraction & Transformation)

• CSV Files (Data Source)

## Project Structure
Credit-Card-Financial-Dashboard

• ccdb.sql (Database + Table Creation Script)

• credit_card.csv

• customer.csv

• Credit Card Financial Dashboard.pbix

• README.md

## How to Run This Project
### 1. Setup Database
• Open MySQL

• Run the SQL script to create database and tables

### 2. Import Data
• Place CSV files in MySQL upload directory

• Execute LOAD DATA INFILE queries

### 3. Open Power BI File
• Open .pbix file in Power BI Desktop

• Refresh data connections

## Learning Outcomes
• Hands-on experience with SQL database design

• Data cleaning and transformation

• Building interactive dashboards in Power BI

• Understanding financial and customer analytics

## Future Improvements
• Add real-time database connectivity

• Include predictive analytics (customer churn/risk)

• Enhance dashboard with advanced DAX measures

• Deploy dashboard on Power BI Service

## Author

• Ritik Devrani

• Diploma in Computer Science

• BCA (IGNOU)
