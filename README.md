# TARGET-E-Commerce-Data-Analysis-Project
This project is a comprehensive data analysis of an e-commerce dataset using Python and SQL. It explores customer behavior, sales performance, and product trends through a series of basic to advanced SQL queries.
The Python Jupyter Notebook serves as a bridge to extract insights from the database using SQL embedded in Python, and presents findings with clean visualizations and statistics.

The goal is to provide insights into:

Customer demographics and behavior

Product and category performance

Seller revenue rankings

Sales trends over time

Retention and growth metrics

🧰 Technologies Used
Python (Pandas, Matplotlib/Seaborn, sqlite3)

Jupyter Notebook

SQL (SQLite syntax)

📁 Project Structure
bash
Copy
Edit
.
├── python+sql_ecommerce.ipynb     # Main analysis notebook
├── Questions.txt                  # Query prompt list (Basic → Advanced)
├── README.md                      # Project documentation
🚀 How to Use

cd ecommerce-sql-analysis
Launch the Notebook
Open python+sql_ecommerce.ipynb in Jupyter Notebook or VS Code.

Run the Notebook
The notebook:

Loads the dataset (presumably from a SQLite DB)

Runs SQL queries directly using Python

Presents insights with visuals and statistics

⚠️ Make sure the SQLite database (if used) is present in the working directory if required by the notebook.

📌 Query Categories
The analysis is driven by business questions categorized by complexity:

✅ Basic
Cities where customers are located

Orders in 2017

Total sales by category

Installment-based order percentages

Customer count per state

📊 Intermediate
Monthly order volume (2018)

Average products per order per city

Revenue share by product category

Correlation between product price and purchase frequency

Seller revenue rankings

🚀 Advanced
Moving average of order values per customer

Cumulative monthly sales by year

Year-over-year sales growth

Customer retention within 6 months

Top 3 customers per year by spend

These queries are implemented in SQL and visualized using Python for clear communication of results.
