# 🛍️ Customer Behavior Data Pipeline

An end-to-end data analytics project that processes retail shopping data through a full **ETL (Extract, Transform, Load)** pipeline. This project covers data cleaning in Python, storage in PostgreSQL, and final visualization in a Power BI/Tableau dashboard.

## 📊 Project Overview

This project analyzes a dataset of **3,900 customers** to identify purchasing trends and demographic insights. It is divided into three main phases:

### 1. Data Transformation (Python)

The `customer-trends-data-analysis.ipynb` notebook handles the heavy lifting of preparing the data:

* **Imputation**: Filled missing review ratings by calculating the median for each product category.
* **Feature Engineering**: Created custom segments like `age_group` and converted frequencies into numeric `purchase_frequency_days`.
* **Database Integration**: Used `SQLAlchemy` to automatically clean and push the data into a **PostgreSQL** database for further querying.

### 2. Deep Dive Analysis (SQL)

The `sql_queries.sql` script explores 10 business-critical questions:

* **Customer Segmentation**: Categorizes shoppers into "New," "Returning," and "Loyal" segments.
* **Product Rankings**: Identifies the top 3 items per category using SQL window functions.
* **Subscription Value**: Compares spending habits between subscribers and non-subscribers.

### 3. Visual Storytelling (Dashboard)

The final dashboard provides an interactive look at the business KPIs:

* **Average Spend**: $59.76 per transaction.
* **Revenue Leaders**: Clothing and Accessories drive the majority of sales.
* **Top Demographic**: Young Adults are the most active and highest-spending group.

## 🛠️ Tech Stack

* **Analysis**: Python (Pandas, NumPy, Matplotlib).
* **Database**: PostgreSQL.
* **Automation**: SQLAlchemy, Psycopg2.
* **Visualization**: Power BI / Tableau.

---

### Would you like me to add a "How to Setup" section so others can run your Python script on their own computers?
