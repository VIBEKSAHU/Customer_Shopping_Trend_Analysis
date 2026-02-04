# Customer_Shopping_Trend_Analysis
📊 Data Analytics Project – Customer Shopping Behavior Analysis
📌 Overview

This project focuses on analyzing customer shopping behavior using transactional retail data.
The objective is to uncover insights related to customer demographics, purchasing patterns, product performance, subscription behavior, and revenue trends to support data-driven business decisions.

The project follows a complete analytics lifecycle:

Data loading and exploration in Python

Data cleaning and feature engineering

SQL analysis using PostgreSQL

Interactive dashboard creation in Power BI

Final reporting and presentation

📂 Dataset

Source: Retail / Customer shopping dataset (CSV)

Records: ~3,900 transactions

Features: 18 columns

Key Fields:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season)

Behavioral data (Discount usage, Frequency of purchases, Review ratings)

Shipping and transaction details

🛠 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn

SQL: PostgreSQL

BI Tool: Power BI

Documentation: Report & PowerPoint

Environment: Jupyter Notebook / VS Code

🔄 Project Workflow & Steps
1️⃣ Data Loading & EDA (Python)

Loaded dataset using pandas

Performed initial exploration using .info() and .describe()

Analyzed distributions, trends, and basic statistics

2️⃣ Data Cleaning & Feature Engineering

Handled missing values (category-wise median imputation)

Standardized column names (snake_case)

Removed redundant columns

Created new features such as:

Age groups

Purchase frequency

Derived behavioral metrics

3️⃣ SQL Analysis (PostgreSQL)

The cleaned data was loaded into PostgreSQL to perform structured analysis, including:

Revenue comparison by gender

Identification of high-spending discount users

Top-rated products

Subscriber vs non-subscriber behavior

Shipping type impact on purchase value

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

📊 Power BI Dashboard

An interactive Power BI dashboard was built to visualize insights:

KPI cards (customers, average spend, ratings)

Revenue and sales by category

Customer segmentation by subscription status

Age group and behavioral analysis

Filters for category, gender, shipping type, and subscription status

The dashboard enables stakeholders to explore insights dynamically.

📈 Key Results & Insights

Subscribers contribute higher long-term value compared to non-subscribers

Certain products rely heavily on discounts, impacting margins

Loyal customers form the largest segment

Middle-aged and young adult groups generate the highest revenue

Express shipping users show slightly higher average spend

📑 Report & Presentation

A detailed analytical report documents methodology, findings, and recommendations

A PowerPoint presentation summarizes insights for non-technical stakeholders

Focus on business impact, not just metrics

▶️ How to Run the Project
Python (EDA & Cleaning)
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2


Run the Jupyter notebook or Python scripts for EDA and cleaning.

SQL

Set up PostgreSQL

Create tables and load cleaned data

Execute provided SQL queries for analysis

Power BI

Import cleaned dataset or PostgreSQL connection

Refresh data model

Explore interactive visuals

🎯 Business Value

This project demonstrates how raw transactional data can be transformed into actionable insights using Python, SQL, and Power BI.
It highlights strong skills in data cleaning, analysis, visualization, and communication, making it suitable for entry-level to early-career data analyst roles.

👤 Author

Vibek Kumar sahu    
