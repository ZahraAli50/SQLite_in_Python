# SQLite_in_Python
ales Data Analysis with SQLite and Python

This project demonstrates how to use **SQLite** with **Python** to store, query, and analyze basic sales data. It includes the creation of a simple sales database, insertion of sample data, and a summary query to extract total quantities and revenue per product.

---

## Tools Used


- SQLite (via Python's built-in 'sqlite3' module)
- pandas (for data manipulation)
- matplotlib (for basic visualization)
- Jupyter Notebook 

---

##  Project Structure

- 'sales_data.db': SQLite database file automatically created by the script
- SQLite_in_Python.ipynb: Main Python code to create table, insert data, run SQL queries, and plot results


---

## Features

- Creates a SQLite database with a 'sales' table (if it doesn't already exist)
- Inserts sample sales data into the table
- Executes a SQL query to compute:
  - Total quantity sold per product
  - Total revenue (quantity × price) per product
- Displays the results using:
  - 'print()' for console output
  - 'matplotlib' for a bar chart visualization
