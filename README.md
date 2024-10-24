# LITA_Class_Project

This is where I documented my first project while learning data analysis with the Incubator Hub.

### Project Title: Sales Analysis

### Project Overview
---
The Sales Analysis project aims to explore and understand sales data to identify trends, patterns, and insights that can drive better business decisions. The analysis covers various aspects such as sales performance, customer behavior, product trends, and geographic distribution. The goal is to help businesses make data-driven decisions by providing a comprehensive understanding of their sales data.

### Data Sources
---
The primary data source used here is Data Sale.csv, which is open-source data that can be freely downloaded from an online repository such as Kaggle, FRED, or any other site.

### Tools Used
---
- Microsoft Excel [Download Here].(https://www.microsoft.com)
    1. For Data Cleaning
    2. For Data Analysis
    3. For Visualization.
      
- SQL - Structured Query Language for Querying of Data.
- PowerBI - Power Business Intelligence for Data Visualization, Business Intelligence Reporting, Data Integration, Data Modeling, Dashboard and Report sharing.
- Github for Portfolio Building.

### Data Cleaning and Preparation
---
In the initial phase of the Data cleaning and preparation, we perform the following actions;
  1. Handling Missing Data
  2. Removing Duplicate Records
  3. Correcting Data Types
  4. Handling Outliers
  5. Standardizing and Normalizing Data
  6. Dealing with Inconsistent Data
  7. Handling Data Entry Errors
  8. Data Integration and Merging
  9. Removing Irrelevant Data

### Exploratory Data Analysis
EDA involved exploring the Data to answer some questions about the Data such as;
- What is the overall sales trend
- Which products are top sellers
- What are the products on peak sales?

### Data Analysis
---
This is where I include some basic lines of code, queries, or even some of the DAX expressions used during my analysis.

```Excel
- SUM: =SUM(A2:A100) to calculate the total.
- AVERAGE: =AVERAGE(B2:B100) to calculate the average.
- MEDIAN: =MEDIAN(C2:C100) to find the median.
- STDEV.P/STDEV.S: =STDEV.P(D2:D100) for population standard deviation or =STDEV.S(D2:D100) for sample standard deviation.
- COUNT: =COUNT(E2:E100) to count the number of numeric entries.
- =IF(A2 > 1000, "High", "Low") to classify data based on a condition.
- =IF(A2 > 1000, "High", "Low") to classify data based on a condition.
```

```SQL
- SELECT * FROM sales_data; to select all columns from a table
- SELECT 
    SUM(Sales) AS Total_Sales,
    AVG(Sales) AS Average_Sales,
    COUNT(*) AS Transaction_Count
FROM sales_data; to Calculate the total sales, average sales, and count of transactions
- SELECT *
FROM sales_data
WHERE Region = 'West'; to Get sales data for a specific region
- SELECT 
    Region, 
    SUM(Sales) AS Total_Sales, 
    AVG(Profit) AS Average_Profit
FROM sales_data
GROUP BY Region; to Calculate total sales and average profit by region
```

```PowerBI
- Profit Margin = DIVIDE([Profit], [Sales], 0) * 100 to Calculate the Profit Margin as a percentage
- Total Sales = SUM(Sales[Sales]) Total Sales Measure
- Average Profit = AVERAGE(Sales[Profit]) Average Profit Measure
```

### Data Visualization
---
![Bar Chart](https://github.com/user-attachments/assets/9b482705-b658-455a-84ae-9b85c7e931f3)
![Sales Reort using Slicer](https://github.com/user-attachments/assets/49633d90-3af0-4827-9218-4e241560ca90)
![Pivot Table](https://github.com/user-attachments/assets/4f6718e0-8740-42f2-89c8-9c24b4f7553d)


