# Customer_Shopping_behavior_Analysis_Project.
I analyzed customer shopping behavior by cleaning data in Python (handling missing values and creating new columns). I loaded the cleaned data into PostgreSQL, wrote queries to extract business insights, and then visualized key metrics through an interactive Power BI dashboard.

🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases. The goal is to uncover insights into spending patterns, customer segments, and product preferences. The workflow moves from data cleaning in Python, SQL analysis in PostgreSQL, to dashboard creation in Power BI.

📊 Dataset

3,900 rows, 18 columns

Key features: Age, Gender, Purchase Amount, Review Rating, Discount, Category, Shipping Type

Missing values: 37 in Review Rating

🛠 Tools

Python (Pandas, NumPy)

PostgreSQL

Power BI

🔄 Steps

Loaded data with Pandas, explored with df.info() and describe().

Imputed missing ratings by category median, standardized columns, and created features (age group, purchase frequency).

Exported cleaned data to PostgreSQL.

Ran SQL queries: revenue by gender, top-rated products, discount analysis, customer segmentation.

Built a Power BI dashboard with key metrics and slicers.

📈 Dashboard

The Power BI dashboard includes: total customers, average purchase, revenue by category, and customer segments.

📊 Results

Loyal customers drive the highest revenue.

Discount users can still be high spenders.

Express shipping users show slightly higher average spend.

▶️ How to Run

Run data_cleaning.py to clean data.

Import the cleaned dataset into PostgreSQL.

Run SQL queries provided.

Open the Power BI dashboard (.pbix) for visualization
