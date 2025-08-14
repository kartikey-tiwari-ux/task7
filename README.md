# Task 7 - Basic Sales Summary from SQLite Database using Python

## Overview
This project connects to a SQLite database, retrieves sales data using SQL queries, and visualizes it with a bar chart.

## Steps
1. Created `sales_data.db` with a `sales` table containing product, quantity, and price.
2. Connected to the database using `sqlite3`.
3. Queried total quantity and revenue grouped by product.
4. Loaded results into a Pandas DataFrame.
5. Printed results and plotted a bar chart using Matplotlib.

## Technologies Used
- Python
- SQLite (sqlite3)
- Pandas
- Matplotlib

## How to Run
1. Install Python 3.x
2. Install required libraries:
   ```bash
   pip install pandas matplotlib
Run the Python script:

bash
Copy
Edit
python task7.py
Output
Console output with total quantity and revenue per product.

Bar chart saved as sales_chart.png.
