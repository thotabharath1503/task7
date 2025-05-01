# task7
# 🧾 Basic Sales Summary using SQLite and Python

This project demonstrates how to extract and visualize basic sales insights from a simple SQLite database using Python. It includes SQL querying, data processing with pandas, and data visualization with matplotlib.

# Objective

- Connect to a local SQLite database (`sales_data.db`)
- Query sales data (total quantity sold, total revenue per product)
- Display results in the console
- Plot a bar chart showing revenue by product

# Tools Used

- **Python**
- **SQLite3** (built into Python)
- **pandas** for data manipulation
- **matplotlib** for visualization

# Dataset

A single SQLite table `sales` with columns:
- `id` (Primary Key)
- `product` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)

Sample data is inserted automatically for testing when you first run the script.

# Output

- A printed DataFrame showing:
  - Product names
  - Total quantity sold
  - Total revenue
- A simple bar chart of revenue by product (`sales_chart.png`)

