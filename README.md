# Python-SQLite-Sales-Data-Analysis-Visualization
📖 Overview:
This project is a complete, self-contained demonstration of how to work with SQLite databases in Python for sales data analysis. It covers the full workflow from database creation to data analysis and visualization — making it a practical reference for both beginners and intermediate learners in data analytics.

The script first checks if a database exists; if not, it creates one (sales_data.db) and inserts 100 random sales records across multiple product categories such as laptops, phones, tablets, and accessories. Using the built-in sqlite3 library, SQL queries are executed to extract insights like total quantity sold per product, total revenue, and month-wise revenue trends. The results are displayed in Pandas DataFrames for easy readability and further analysis.

Visual insights are generated using Matplotlib, with a bar chart for product-wise revenue comparison and a line chart to track revenue trends over time. Both charts are saved as image files for reporting purposes.

🔹 Features:

1.Automatic Data Creation: Generates 100 random sales records with product names, quantities, prices, and sale dates.

2.SQL Inside Python: Uses standard SQL queries within Python scripts for data aggregation and summarization.

3.Pandas Integration: Displays query results in clean, formatted DataFrames.

4.Data Visualization: Produces professional charts to aid business decision-making.

5.Self-Contained Workflow: No internet or external database setup required — works offline using only Python’s built-in SQLite.


💡 Learning Outcomes:

1.Understand how to connect Python to SQLite databases.

2.Learn to write and run SQL queries inside Python.

3.Practice data aggregation and grouping using SQL GROUP BY.

4.Explore data visualization techniques with Matplotlib.

5.Gain experience in building automated, end-to-end analysis scripts.

🛠 Tools & Technologies:

1.Python – Main programming language.

2.SQLite – Lightweight embedded database.

3.Pandas – Data manipulation and analysis.

4.Matplotlib – Chart creation and visualization.
