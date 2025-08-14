# Python-SQLite Sales Data Analysis & Visualization

**Author:** Vishal Kumar  
**LinkedIn:** [https://www.linkedin.com/in/vishal013/](https://www.linkedin.com/in/vishal013/)  

---

## Overview  
This project demonstrates a complete workflow for working with **SQLite databases in Python** for sales data analysis.  
It covers every step from **database creation** to **data analysis and visualization**, making it a practical resource for both beginners and intermediate data analytics learners.  

The script checks if a database exists; if not, it creates one (`sales_data.db`) and inserts **100 random sales records** across multiple product categories such as laptops, phones, tablets, and accessories. Using Python’s built-in `sqlite3` library, SQL queries are run to generate insights including:  

- Total quantity sold per product  
- Total revenue  
- Month-wise revenue trends  

The results are displayed in **Pandas DataFrames** for easy interpretation, and **Matplotlib** is used to create:  

- Bar charts for product-wise revenue comparison  
- Line charts for tracking revenue trends over time  

All charts are saved as image files for reporting purposes.  

---

## Features  

- **Automated Data Generation:** Creates 100 random sales records with product details, quantities, prices, and sale dates.  
- **SQL Integration in Python:** Executes SQL queries for aggregation and summarization.  
- **Clean Data Presentation:** Uses Pandas to display results in a readable format.  
- **Data Visualization:** Produces clear, professional charts to support decision-making.  
- **Offline, Self-Contained Workflow:** No internet or external database setup required.  

---

## Learning Outcomes  

By working through this project, you will:  

1. Learn how to connect Python to SQLite databases.  
2. Write and execute SQL queries within Python scripts.  
3. Perform data aggregation and grouping using `GROUP BY`.  
4. Create meaningful visualizations with Matplotlib.  
5. Build a self-contained, automated data analysis script.  

---

## Tools & Technologies  

- **Python** – Programming language  
- **SQLite** – Lightweight database  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  

---

## Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/yourusername/Python-SQLite-Sales-Data-Analysis-Visualization.git
