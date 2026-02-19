# Sales Data Analyzer

## Overview
Sales Data Analyzer is a data analysis project developed to demonstrate how structured transactional sales data can be stored, processed, and analyzed using MySQL and Python.  
The project focuses on extracting meaningful business insights such as revenue trends, product performance, and monthly growth patterns from retail sales data.

This project simulates a real-world business scenario where sales transactions are managed within a relational database and analyzed using data analysis and statistical techniques.

---

## Objectives

- Store and manage sales transaction data using MySQL  
- Establish database connectivity with Python  
- Perform data cleaning and preprocessing using Pandas  
- Calculate total revenue generated from sales  
- Analyze monthly sales performance and growth trends  
- Identify best-performing products based on revenue  
- Perform statistical analysis using NumPy  
- Visualize sales trends and product performance  

---

## Technologies Used

- Python  
- MySQL  
- Pandas  
- NumPy  
- Matplotlib  
- MySQL Connector for Python  

---

## Database Schema

The project uses a MySQL database named:

```
sales_analysis
```

It contains a table named:

```
sales
```

### Table Structure

| Column Name | Data Type | Description |
|------------|-----------|-------------|
| id         | INT       | Primary Key |
| date       | DATE      | Transaction Date |
| product    | VARCHAR   | Product Name |
| quantity   | INT       | Quantity Sold |
| price      | FLOAT     | Price Per Unit |

---

## Project Workflow

1. Connect Python to MySQL database  
2. Create database and sales table  
3. Insert transactional sales data  
4. Load data into Pandas DataFrame  
5. Perform data cleaning  
6. Calculate revenue for each transaction  
7. Group data by month for trend analysis  
8. Calculate monthly growth percentage  
9. Identify best-selling product  
10. Perform statistical analysis using NumPy  
11. Visualize monthly sales trend  
12. Visualize product-wise revenue distribution  

---

## Key Features

- Total revenue calculation  
- Monthly sales growth analysis  
- Best-selling product identification  
- Mean revenue calculation  
- Median revenue calculation  
- Standard deviation analysis  
- Sales trend detection  
- Monthly sales trend line graph  
- Product-wise revenue bar chart  

---

## Installation and Setup

### Step 1: Install Required Libraries

Run the following command:

```
pip install mysql-connector-python pandas numpy matplotlib
```

---

### Step 2: Ensure MySQL Server is Running

Start your MySQL server before executing the script.

---

### Step 3: Update Database Credentials

Update the following credentials in the Python script according to your MySQL configuration:

```
host
user
password
```

---

### Step 4: Run the Python Script

Execute the script using:

```
python main.py
```

The script will automatically:

- Create the database and table  
- Insert sample sales data  
- Perform revenue and growth analysis  
- Identify best-performing products  
- Display statistical outputs  
- Generate visual graphs  

---

## Output

The project generates the following outputs:

- Total revenue  
- Monthly sales summary  
- Monthly growth percentage  
- Product-wise revenue analysis  
- Best-performing product  
- Statistical measures (mean, median, standard deviation)  
- Monthly sales trend visualization  
- Product-wise revenue bar chart  

---

## Author

Developed By theycreate_developer-AbdulBasit.

---

