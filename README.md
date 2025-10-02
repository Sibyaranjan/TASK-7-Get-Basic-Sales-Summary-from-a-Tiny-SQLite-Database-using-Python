# TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python

This project demonstrates a comprehensive analysis of a sales dataset using Python. The dataset, sourced from an Excel file (Sales Dataset.xlsx), contains sales records with columns such as OrderNumber, OrderDate, Customer Name Index, Channel, Currency Code, Warehouse Code, Delivery Region Index, Product Description Index, Order Quantity, Unit Price, Line Total, and Total Unit Cost.

The analysis is divided into two main parts:

SQL-based Queries using SQLite: Load the data into an in-memory SQLite database and perform various aggregations and filters (e.g., total revenue, quantity sold, sales by region/channel).
Visualizations using Matplotlib and Seaborn: Generate a variety of plots to explore trends, distributions, and relationships (e.g., bar charts, line plots, heatmaps, scatter plots).
This project is ideal for data analysts, students, or anyone learning data manipulation and visualization in Python.

Features
SQL Operations (via SQLite)
Total number of orders and unique products.
Aggregations: Total quantity sold, total revenue (Line Total), total cost (Total Unit Cost), and profit.
Averages: Average unit price and average order value.
Grouped analyses: Top products/customers by quantity/revenue, sales by delivery region, channel, warehouse, and currency.
Filtering: Revenue for specific years (e.g., 2023) or warehouses.
Export results to CSV (e.g., top products).
Visualizations
Matplotlib Plots
Bar chart: Revenue by delivery region.
Line chart: Monthly revenue trend over time.
Pie chart: Revenue distribution by channel.
Scatter plot: Order quantity vs. unit price (colored by channel).
Histogram: Distribution of line totals.
