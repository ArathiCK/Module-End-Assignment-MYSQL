# E-Commerce Customer Churn Analysis Using MySQL

## Objectives
- Clean and prepare the customer churn dataset.
- Handle missing values using mean and mode imputation.
- Remove outliers and standardize inconsistent values.
- Transform data by renaming columns and creating meaningful categories.
- Analyze customer churn, payment preferences, order behavior, and satisfaction.
- Combine customer and return data using SQL joins.

## Tools and Technologies
- **Database:** MySQL
- **Tool:** MySQL Workbench
- **Language:** SQL
- **Dataset:** E-Commerce Customer Churn Dataset

## Assignment Workflow

### 1. Data Cleaning
- Replaced missing values using mean and mode imputation.
- Removed records with warehouse-to-home distances greater than 100 km.
- Standardized preferred login devices, order categories, and payment modes.

### 2. Data Transformation
- Renamed columns for consistency and readability.
- Created `ComplaintReceived` to categorize customers based on complaint status.
- Created `ChurnStatus` to classify customers as Active or Churned.
- Removed the original `Complain` and `Churn` columns after creating the new categories.

### 3. Data Exploration and Analysis
Performed SQL analysis to answer business questions, including:

- Counting active and churned customers.
- Calculating average tenure and total cashback for churned customers.
- Analyzing complaints among churned customers.
- Identifying city tiers with the highest customer churn.
- Finding the most preferred payment modes.
- Analyzing order trends, coupon usage, and app engagement.
- Comparing satisfaction scores and cashback across order categories.
- Categorizing customers by warehouse distance and analyzing churn patterns.
- Identifying high-order-count customers.
- Creating a customer returns table and joining it with customer data to identify churned customers who made complaints.

## SQL Concepts Used
- `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, and `LIMIT`
- Aggregate functions: `COUNT()`, `SUM()`, `AVG()`, and `MAX()`
- Conditional logic using `CASE`
- Subqueries
- `UPDATE`, `DELETE`, `ALTER TABLE`, and `CREATE TABLE`
- `INSERT INTO`
- `JOIN`
- Data cleaning and transformation techniques

## Key Learning Outcomes
- Gained practical experience in cleaning and transforming real-world datasets using SQL.
- Practiced aggregate functions, filtering, grouping, and subqueries.
- Learned to create meaningful customer categories for analysis.
- Applied joins to combine customer and return records.
- Developed skills in answering business questions using structured queries.

## Conclusion
This Assignment demonstrates the use of MySQL for data preparation and exploratory analysis of e-commerce customer churn. The analysis helps explore customer retention patterns, payment preferences, purchasing behavior, and complaint-related returns.

## Repository Contents
- `README.md` – Project documentation
- `E-Commerce Customer churn db` – SQL queries used for data cleaning, transformation, and analysis 


