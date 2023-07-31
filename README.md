# Home_Sales
Home Sales Analysis using PySpark - README

Overview

This project aims to analyze home sales data using PySpark SQL functions. The dataset used for this analysis is "home_sales_revised.csv." The tasks involve answering specific questions using SparkSQL and exploring the performance impact of caching and partitioning.

Steps

Rename the Notebook: Rename the "Home_Sales_starter_code.ipynb" file as "Home_Sales.ipynb."
Import PySpark SQL Functions: Import the necessary PySpark SQL functions for the assignment.
Read Data: Read the "home_sales_revised.csv" data in the starter code into a Spark DataFrame.
Create Temporary Table: Create a temporary table called "home_sales" from the Spark DataFrame.
Answer Questions using SparkSQL:
Q1: What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
Q2: What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
Q3: What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
Q4: What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
Cache the Temporary Table: Cache the temporary table "home_sales."
Check Caching: Verify if the temporary table "home_sales" is cached.
Filtered Query with Caching: Run the query filtering out the view ratings with an average price greater than or equal to $350,000 using the cached data. Determine the runtime and compare it to the uncached runtime.
Partitioning: Partition the formatted Parquet home sales data by the "date_built" field.
Temporary Table for Parquet Data: Create a temporary table for the Parquet data.
Filtered Query with Partitioning: Run the query filtering out the view ratings with an average price greater than or equal to $350,000 using the partitioned data. Determine the runtime and compare it to the uncached runtime.
Uncache the Temporary Table: Uncache the "home_sales" temporary table.
Verify Uncaching: Verify that the "home_sales" temporary table is uncached using PySpark.
Download and Upload: Download your "Home_Sales.ipynb" file and upload it into your "Home_Sales" GitHub repository.
This project demonstrates how to perform data analysis using PySpark SQL functions and optimize performance through caching and partitioning. It provides insights into the home sales data based on various criteria, making it useful for decision-making in the real estate industry.
