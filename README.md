## RETAIL--SALES--ANALYSIS-SQL-project-
# Project Overview

1) Project Title: Retail Sales Analysis

The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries

2) Objectives -
     
   a- Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
   
   b- Data Cleaning: Identify and remove any records with missing or null values.
   
   c- Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
   
   d- Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

 3) Database Setup -
    
      a- Database Creation: The project starts by creating a database named p1_retail_db.
    
      b- Table Creation: A table named retail_sales is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender,age, 
         product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.
  
CREATE DATABASE p1_retail_db;

CREATE TABLE retail_sales
(
    transactions_id INT PRIMARY KEY,
    sale_date DATE,	
    sale_time TIME,
    customer_id INT,	
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,	
    cogs FLOAT,
    total_sale FLOAT
);
