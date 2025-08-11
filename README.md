#  Sales Data Analysis with Python and SQLite

This project demonstrates how to use Python to connect to a SQLite database, run basic SQL queries, and visualize simple sales metrics using pandas and matplotlib.

## Objective

- Create a SQLite database and table
- Insert sample sales data
- Use SQL to query total quantity and revenue per product
- Load results into pandas
- Display the data using `print` and a bar chart

##  Tools Used

- Python 3
- SQLite (`sqlite3`)
- pandas
- matplotlib
- Jupyter Notebook or a .py file

##  Files Included

- `Task-7(python connection with sqlite3).ipynb` — main Jupyter notebook
- `sales_data.db` — generated SQLite database
- `sales_chart.png` *(optional)* — saved bar chart image
- `README.md` — this documentation

##  How to Run

1. **Install requirements** (if not already installed):
   ```bash
   pip install pandas matplotlib
   ```

2. **Run the notebook** or execute the `.py` script:
   - In Jupyter: Open and run each cell in order
   - From terminal (if using `.py` file):
     ```bash
     python sales_summary.py
     ```

3. **Output**:
   - Console: Displays total quantity and revenue per product
   - Plot: Bar chart of revenue per product

##  Sample Output

- A printed table like:
  ```
     product  total_qty  revenue
  0    Apple         15     18.0
  1   Banana         30     15.0
  2   Orange         15     12.0
  ```

- A simple bar chart showing revenue per product.

