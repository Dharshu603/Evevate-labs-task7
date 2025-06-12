# Evevate-labs-task7
# 🛒 Sales Summary using SQLite and Python

## 📌 Objective
This project demonstrates how to:
- Create a small SQLite database using Python
- Insert sample sales data
- Perform basic SQL queries to calculate total quantity and revenue by product
- Display the results using Python’s `print()` and `matplotlib` bar chart

---

## 🧰 Tools Used
- **Python 3.x**
- **SQLite** (via `sqlite3`, built-in)
- **Pandas** for data handling
- **Matplotlib** for visualization
- **Jupyter Notebook / .py script**

---

## 📁 Files Included

| File Name         | Description |
|------------------|-------------|
| `sales_summary.py` | Main Python script (SQLite connection, query, visualization) |
| `sales_data.xlsx` | Sample sales data (Excel format) |
| `sales_data.db`   | SQLite database file (created on first run) |
| `sales_chart.png` | Output bar chart showing revenue by product |
| `README.md`       | Project overview |

---

## 🧪 Sample Data Preview

| id | product | quantity | price |
|----|---------|----------|-------|
| 1  | Apples  | 10       | 2.5   |
| 2  | Bananas | 5        | 1.0   |
| 3  | Oranges | 8        | 1.5   |
| 4  | Apples  | 6        | 2.5   |
| 5  | Bananas | 7        | 1.0   |
| 6  | Oranges | 4        | 1.5   |

---

📊 Output
Console Output
Sales Summary:
   product  total_qty  revenue
0  Apples         16     40.0
1  Bananas        12     12.0
2  Oranges        12     18.0

💡 Learning Outcomes
Use of SQLite with Python

Writing and executing SQL queries

Loading SQL results into Pandas DataFrame

Visualizing with Matplotlib



