Sales Data Analyzer
Project Overview

The Sales Data Analyzer is a data analysis project designed to demonstrate how structured sales data can be stored, processed, and analyzed using MySQL and Python-based data analysis libraries. The project focuses on extracting meaningful business insights from retail sales transactions through statistical analysis and visualization techniques.

This project simulates a real-world retail environment where sales data is stored in a relational database and analyzed to evaluate revenue trends, product performance, and overall business growth.

Objectives

Store and manage sales data using MySQL

Connect MySQL database with Python

Perform data cleaning and preprocessing using Pandas

Calculate total revenue generated from sales

Analyze monthly sales performance and growth trends

Identify the best-selling product based on revenue

Perform statistical analysis using NumPy

Visualize product-wise sales performance and monthly trends

Technologies Used

Python

MySQL

Pandas

NumPy

Matplotlib

MySQL Connector for Python

Database Schema

The project uses a MySQL database named:

sales_analysis


It contains a table named:

sales

Table Structure
Column Name	Data Type	Description
id	INT	Primary Key
date	DATE	Transaction date
product	VARCHAR	Product name
quantity	INT	Quantity sold
price	FLOAT	Price per unit
Project Workflow

Connect Python to MySQL database

Create database and sales table

Insert sales transaction data

Load data into Pandas DataFrame

Perform data cleaning

Calculate revenue for each transaction

Group sales data by month

Calculate monthly growth percentage

Identify best-selling product

Perform statistical analysis using NumPy

Visualize monthly sales trend using line graph

Visualize product-wise revenue using bar chart

Key Features

Total revenue calculation

Monthly sales growth analysis

Best-selling product identification

Mean revenue calculation

Median revenue calculation

Standard deviation of revenue

Trend analysis using linear regression

Monthly sales trend visualization

Product-wise revenue bar chart

How to Run the Project
Step 1: Install Required Libraries

Run the following command:

pip install mysql-connector-python pandas numpy matplotlib

Step 2: Start MySQL Server

Ensure that your MySQL server is running.

Step 3: Update Database Credentials

Open the Python script and update:

host
user
password


according to your MySQL setup.

Step 4: Run the Python Script

Execute the script:

python main.py


The script will:

Create database and table

Insert sample data

Perform analysis

Display statistical outputs

Generate visual graphs

Output

The project generates:

Total revenue

Monthly sales summary

Monthly growth percentage

Best-performing product

Mean revenue

Median revenue

Standard deviation

Sales trend analysis

Monthly sales line graph

Product revenue bar chart
