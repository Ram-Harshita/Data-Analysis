Customer Shopping Behavior Analysis
________________________________________
1. Project Overview
This project is an end-to-end data analytics case study built to demonstrate hands-on skills required for a Data Analyst role. It showcases the complete workflow from raw data to business insights using Python, MySQL, and Power BI.
The objective is to analyze customer shopping behavior and answer key business questions related to revenue, discounts, subscriptions, products, shipping preferences, and customer segments.
________________________________________
2. Tools & Technologies
Tool	Usage
Python (Pandas)	- Data loading, cleaning, exploration
VS Code -	Development environment
MySQL 8.0	- Relational database
SQL Pro for MySQL -	SQL querying & database management
SQLAlchemy + PyMySQL	- Python–MySQL connectivity
Power BI -	Data visualization & dashboards
________________________________________
3. Dataset Description
Dataset: Customer Shopping Behavior (CSV)
________________________________________
4. Python: Data Exploration & Preparation
Objectives
•	Validate data quality
•	Understand data structure
•	Prepare data for database storage
Steps Performed
•	Loaded CSV using Pandas
•	Checked missing values and data types
•	Generated descriptive statistics
•	Dropped irrelevant columns
________________________________________
5. MySQL: Database Setup
Database Creation
CREATE DATABASE customer_behavior;
USE customer_behavior;
Data Ingestion from Python
Data was written from Pandas into MySQL using SQLAlchemy.
________________________________________
6. SQL Analysis (Business Questions)
Q1. Total Revenue by Gender
Q2. High-Value Customers Using Discounts
Q3. Top 5 Products by Average Review Rating
Q4. Average Purchase Amount by Shipping Type
Q5. Subscriber vs Non-Subscriber Analysis
Q6. Products with Highest Discount Usage
Q7. Customer Segmentation
________________________________________
7. Power BI Dashboard
Dashboard Components
•	Total Revenue KPI
•	Average Purchase Amount KPI
•	Revenue by Gender (Bar Chart)
•	Subscription Impact Analysis
•	Shipping Type Comparison
•	Discount Usage Insights
•	Top Products by Rating

Data Source
•	MySQL Database: customer_behavior
•	Connected via MySQL connector
________________________________________
8. Key Business Insights
•	Subscribers show higher average spending
•	Express shipping customers generally spend more
•	High-rated products drive consistent customer satisfaction
•	Discounts do not always reduce overall spend
•	Loyal customers contribute significantly to revenue
________________________________________
9. Conclusion
This project demonstrates the ability to convert raw data into actionable business insights using industry-standard analytics tools. It reflects real-world data analyst responsibilities.
________________________________________
10. Future Enhancements
•	Advanced Power BI DAX measures
•	Predictive modeling using Python
•	Automated ETL pipelines
•	Deployment via Power BI Service
________________________________________
