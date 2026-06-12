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

1. **Write a SQL query to retrieve all columns for sales made on '2022-11-05**:
2. **Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022**:
3. **Write a SQL query to calculate the total sales (total_sale) for each category.**:
4. **Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.**:
5. **Write a SQL query to find all transactions where the total_sale is greater than 1000.**:
6. **Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.**:
7. **Write a SQL query to calculate the average sale for each month. Find out best selling month in each year**:
8. **Write a SQL query to find the top 5 customers based on the highest total sales**:
9. **Write a SQL query to find the number of unique customers who purchased items from each category.**:
10. **Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17)**:

## Findings

- **Customer Demographics**: The dataset includes customers from various age groups, with sales distributed across different categories such as Clothing and Beauty.
- **High-Value Transactions**: Several transactions had a total sale amount greater than 1000, indicating premium purchases.
- **Sales Trends**: Monthly analysis shows variations in sales, helping identify peak seasons.
- **Customer Insights**: The analysis identifies the top-spending customers and the most popular product categories.

## Reports

- **Sales Summary**: A detailed report summarizing total sales, customer demographics, and category performance.
- **Trend Analysis**: Insights into sales trends across different months and shifts.
- **Customer Insights**: Reports on top customers and unique customer counts per category.

## Conclusion

This project helped me gain practical experience in SQL by working with retail sales data. It involved database creation, data cleaning, exploratory data analysis (EDA), and solving business problems using SQL queries. Through this project, I analyzed sales trends, customer purchasing behavior, and product performance to generate meaningful business insights and strengthen my data analysis skills.
