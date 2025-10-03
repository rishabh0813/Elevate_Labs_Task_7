# Elevate_Labs_Task_7
Task 7: Basic Sales Summary using SQLite and Python
📌 Objective
The goal of this task was to:

Create a small SQLite database (sales_data.db) with one sales table.
Write SQL queries inside Python to pull simple sales summaries (like total quantity and total revenue).
Load results into pandas for analysis.
Visualize the results using matplotlib.
🛠 Tools & Libraries
Python (sqlite3, pandas, matplotlib)
SQLite (built-in with Python)
Jupyter Notebook / Python script
📂 Dataset
A small table sales with the following fields:

id (integer, primary key)
product (text)
quantity (integer)
price (real)
Sample inserted data:

("Laptop", 3, 1000.0),
("Laptop", 2, 950.0),
("Phone", 5, 500.0),
("Phone", 8, 450.0),
("Tablet", 4, 300.0),
("Tablet", 6, 280.0),
("Headphones", 10, 50.0),
("Headphones", 15, 45.0)

## 📈 Visualizations

Different charts were created to explore the data:

Bar Chart – Revenue by product

Pie Chart – Revenue share of each product

Line Chart – Revenue trend (example with products sorted)

##❓ Interview Q&A
1. How did you connect Python to a database?
2. What SQL query did you run?
3. What does GROUP BY do?
4. How did you calculate revenue?
5. How did you visualize the result?
6. What does pandas do in your code?
7. What’s the benefit of using SQL inside Python?
8. Could you run the same SQL query directly in DB Browser for SQLite?
