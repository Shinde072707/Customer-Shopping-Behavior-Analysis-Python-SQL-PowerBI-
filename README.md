🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover spending patterns, customer segments, product preferences, and subscription behavior. The goal is to generate actionable business insights that help improve sales strategy, customer engagement, and long-term loyalty. 

Customer Shopping Behavior Anal…
The analysis combines:
Python → Data cleaning & preprocessing
SQL → Business query analysis
Power BI → Interactive dashboard visualization

🎯 Business Problem

A retail company wants to understand how customer demographics, product categories, discounts, reviews, and seasons influence purchase behavior and repeat buying.

Main Question:

How can customer shopping data be used to identify trends, improve engagement, and optimize marketing and product strategies? 

Business Problem Document

📊 Dataset Information

Total Records: ~3,900 transactions

Total Features: 18 columns

Includes:

Customer Demographics → Age, Gender, Location, Subscription Status

Purchase Details → Product, Category, Price, Season, Size, Color

Shopping Behavior → Discounts, Promo Codes, Frequency, Ratings, Shipping Type

Missing values existed in review ratings and were handled during preprocessing. 

Customer Shopping Behavior Anal…

🧪 Project Workflow
1️⃣ Data Preprocessing (Python)

Data loading using Pandas

Missing value treatment using median imputation

Column renaming and standardization

Feature engineering:

Age groups creation

Purchase frequency calculation

Data exported to database for SQL analysis 

Customer Shopping Behavior Anal…

2️⃣ Data Analysis (SQL)

Business questions solved:

Revenue comparison by gender

High spending discount users

Top rated products

Shipping type vs purchase amount

Subscribers vs non-subscribers spending

Customer segmentation (New / Returning / Loyal)

Revenue contribution by age group 

Customer Shopping Behavior Anal…

3️⃣ Dashboard (Power BI)

Created an interactive dashboard showing:

Revenue trends

Customer segments

Product performance

Subscription insights

Discount impact

🧠 Key Business Insights

Subscription customers generate higher long-term revenue

Loyal customers contribute major revenue share

Certain products depend heavily on discounts

Age group and shipping type influence purchase value 

Customer Shopping Behavior Anal…

💡 Business Recommendations

Improve subscription benefits

Launch loyalty reward programs

Optimize discount strategies

Focus marketing on high-value customer segments 

Customer Shopping Behavior Anal…

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib)

SQL (PostgreSQL)

Power BI

Jupyter Notebook

📂 Project Structure
├── data/
│   └── customer_shopping_behavior.csv
├── sql/
│   └── customers.sql
├── notebook/
│   └── analysis.ipynb
├── dashboard/
│   └── customer_behavior_dashboard.pbix
├── docs/
│   └── Business Problem Document.pdf
│   └── Project Report.pdf
└── README.md

🚀 How to Run

Clone repository

Load dataset into Python

Run preprocessing notebook

Load cleaned data into SQL database

Run SQL queries

Open Power BI dashboard file

📈 Future Improvements

Machine Learning prediction model

Customer churn prediction

Recommendation system

Real-time dashboard integration

👨‍💻 Author

Shubham