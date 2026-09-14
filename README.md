# 🎵 SQL Data Extraction & Analysis: Digital Music Store

## 📌 Project Overview
This project demonstrates the ability to extract, manipulate, and analyze relational data using **SQL** and **Python**. Using the widely recognized *Chinook* database (a digital music store simulation), I wrote complex SQL queries to join multiple tables and transform raw database records into actionable business insights.

## 🎯 Business Questions Answered
In this analysis, I addressed key business objectives:
1. **Customer Valuation:** Identified the top 5 most valuable customers based on total lifetime spending by joining `Customer` and `Invoice` tables.
2. **Product Performance:** Discovered the most popular music genres driving sales by performing a complex 3-way join across `Genre`, `Track`, and `InvoiceLine` tables.

## 🛠️ Tools & Technologies Used
* **Database Engine:** SQLite
* **Query Language:** SQL (Joins, Aggregations, Grouping)
* **Data Manipulation:** Python (Pandas)
* **Data Visualization:** Matplotlib & Seaborn

## 📈 Key Visual Insights
The analysis concludes with clean, professional data visualizations built with Seaborn, providing stakeholders with an immediate understanding of genre popularity and customer spending habits without needing to read raw data tables.

## 🚀 How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python installed along with `pandas`, `matplotlib`, and `seaborn`.
3. Open the `02_SQL_Data_Extraction.ipynb` notebook.
4. Run the cells to query the included `chinook.db` database and generate the visualizations in real-time.
