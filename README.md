Basic Sales Summary from SQLite Database
Objective:
This project aims to use SQL inside Python to retrieve basic sales information (such as total quantity sold and total revenue) from a small SQLite database.
The results are then displayed using print statements and a basic bar chart.

Project Description
In this project, we connect to a small SQLite database (sales_data.db) containing sales data. Using SQL queries within Python, we pull key information, including total quantity sold and total revenue per product. 
The results are then displayed in a simple table format and visualized using a bar chart.

Steps:
Database Setup: Create an SQLite database sales_data.db with a sales table containing sales records.

SQL Queries: Run SQL queries to aggregate sales data, such as the total quantity sold and total revenue for each product.

Data Display: Display the query results using Python's print() function.

Visualization: Create a bar chart to visualize the total revenue for each product.

Technologies Used
Python: Programming language used for querying the database and visualizing the results.

SQLite: Database engine built into Python, used for storing sales data.

pandas: Library used to load SQL query results into a DataFrame.

matplotlib: Library used to generate the bar chart for visualizing total revenue.
