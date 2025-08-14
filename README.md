# Task 7: Basic Sales Summary from a Tiny SQLite Database using Python

## 📌 Objective
The goal of this task is to:
- Create a small SQLite database (`sales_data.db`) with sample sales data.
- Use Python to connect to the database and run basic SQL queries.
- Summarize total quantity sold and total revenue for each product.
- Display the results in both tabular and visual formats.

---

## 🛠 Tools Used
- **Python** (with built-in `sqlite3` module)
- **Pandas** (for data manipulation)
- **Matplotlib** (for plotting charts)
- **SQLite** (lightweight database, no setup required)
- **Jupyter Notebook** or `.py` script

---

## 📂 Dataset
A simple dataset of products with:
- **Product Name**
- **Quantity Sold**
- **Price per Unit**

Multiple entries for the same product are included to simulate repeated sales.

---

## 📊 Process Overview
1. **Create Database & Table**
   - Define a `sales` table with columns: `product`, `quantity`, `price`.
   - Insert sample sales records into the database.

2. **Query the Database**
   - Use SQL to calculate:
     - Total quantity sold for each product.
     - Total revenue (`quantity * price`) for each product.
   - Group results by product.

3. **Display Results**
   - Print the summary table in the console / Jupyter Notebook.
   - Plot a bar chart comparing **Quantity** and **Revenue** for each product.

4. **Save Output**
   - Save the bar chart as `sales_chart.png`.

---

## 📈 Expected Output
- **Printed Table** showing sales data
<img width="347" height="342" alt="sales_summary" src="https://github.com/user-attachments/assets/46b9f432-5775-4255-8114-89266b6bea2e" />

- **Bar graph** showing sales chart
<img width="640" height="480" alt="sales_chart" src="https://github.com/user-attachments/assets/39a96c4e-d97c-4f40-95a6-b1644c8f7f0f" />

---

## 🚀 Outcome
By completing this task, you will:
- Understand how to work with SQLite databases in Python.
- Write and execute basic SQL queries from Python.
- Load SQL results into Pandas for analysis.
- Create and save visualizations with Matplotlib.

