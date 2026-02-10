# Task 14 – ETL Mini Pipeline (Python)

## Objective
To build a simple ETL (Extract, Transform, Load) pipeline using Python for retail sales data.

## Tools Used
- Python
- Pandas
- SQLite
- Jupyter Notebook

## Dataset
Retail sales dataset containing order, customer, product, sales, and profit information.

## ETL Process

### 1. Extract
- Loaded raw retail sales data from a CSV file.

### 2. Transform
- Standardized column names
- Created derived columns:
  - Profit Margin
  - High Value Order flag
- Cleaned and structured the data
- Split data into separate entities:
  - Customers
  - Orders
  - Products

### 3. Load
- Exported transformed data into multiple CSV files
- Loaded final datasets into a SQLite database with separate tables

## Outputs
- Cleaned and processed CSV files
- SQLite database with customers, orders, and products tables
- Jupyter Notebook demonstrating the ETL workflow

## Outcome
This task demonstrates a complete ETL workflow and practical data engineering skills using Python.
