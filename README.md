# Retail Sales Analysis SQL Project

## Project Overview

**Project Title**: Retail Sales Analysis  
Business Problems Solved

**1. Identified Peak Business Hours**
<br>
Analyzed sales data to find the busiest times of the day.
This helps the store schedule more staff during peak hours.

**2. Identifying Top Customers**
<br>
Found customers who spend the most money.
This helps the business offer rewards and special discounts to loyal customers.

**3. Understanding Product Performance**
<br>
Analyzed which product categories generate the most sales.
This helps the business maintain the right stock and improve sales strategies.

**4. Analyzing Sales Trends**
<br>
Examined monthly sales patterns to identify high and low sales periods.
This helps the business prepare for peak seasons and manage inventory effectively.

*Business Impact:*<br>
Better understanding of customer behavior.<br>
Improved sales and marketing decisions.<br>
More effective inventory management.<br>
Smarter staffing and business planning.<br>

This project demonstrates SQL skills and techniques used by data analysts to explore, clean, and analyze retail sales data. It involves setting up a retail sales database, performing Exploratory Data Analysis (EDA), and answering business-related questions using SQL queries. The project helps in understanding how SQL can be used to extract insights from data and build a strong foundation in data analysis.

## Objectives

1. **Set up a retail sales database**: Set up a retail sales database and import the sales data into it.
2. **Data Cleaning**: Clean the data by finding and removing records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform Exploratory Data Analysis (EDA) to understand sales patterns and trends in the dataset.
4. **Business Analysis**: Use SQL queries to answer business questions and generate useful insights from the sales data.

## Project Structure

### 1. Database Setup

**Database Creation**: Created a database named retail_db to store and manage retail sales data. <br>**Database Selection**: Used the USE retail_db command to work within the database. <br>**Table Creation**: Created a table named retail_sales containing fields such as transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, COGS, and total sale amount.  <br>**Data Import**: Imported the retail sales dataset into the retail_sales table for analysis and reporting.  <br>**Data Verification**: Verified that the data was successfully loaded and ready for further analysis.

### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**:Identify the total number of unique customers.
- **Category Count**:List all unique product categories in the dataset.
- **Null Value Check**: Detect and remove records with missing or null values.

### 3. Data Analysis & Findings
The following SQL queries were developed to answer specific business questions:
- Which sales transactions occurred on a specific date?
- Which Clothing products had high sales volumes?
- Which product categories generated the highest revenue?
- What is the average age of Beauty category customers?
- Which transactions were high-value purchases?
- How do purchasing patterns differ by gender?
- Which month had the highest average sales each year?
- Who are the top 5 customers by total spending?
- How many unique customers purchased from each category?
- What are the busiest sales shifts during the day?

## Findings

- **Customer Demographics**: The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.
- **High-Value Transactions**: Several transactions had a total sale amount greater than 1000, indicating premium purchases.
- <img width="275" height="137" alt="image" src="https://github.com/user-attachments/assets/7e652215-2c91-4fa2-85d3-021e567f0fdf" />

- **Sales Trends**: Monthly analysis shows variations in sales, helping identify peak seasons.
- **Customer Insights**: The analysis identifies the top-spending customers and the most popular product categories.

## Reports

- **Sales Summary**: A detailed report summarizing total sales, customer demographics, and category performance.
- **Trend Analysis**: Insights into sales trends across different months and shifts.
- **Customer Insights**: Reports on top customers and unique customer counts per category.

## Conclusion

This project helped me gain practical experience in SQL by working with retail sales data. It involved database creation, data cleaning, exploratory data analysis (EDA), and solving business problems using SQL queries. Through this project, I analyzed sales trends, customer purchasing behavior, and product performance to generate meaningful business insights and strengthen my data analysis skills.
