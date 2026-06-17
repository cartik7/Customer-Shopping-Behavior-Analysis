# Customer-Shopping-Behavior-Analysis

**📌 Project Overview**


This project analyzes customer shopping behavior using Python, SQL, PostgreSQL, and Power BI to uncover actionable insights into purchasing patterns, customer segments, product performance, and revenue drivers.

The analysis is based on 3,900 customer transactions containing demographic information, purchase details, subscription status, shipping preferences, discounts, and review ratings.

The objective is to transform raw transactional data into business insights that support data-driven decision-making for marketing, customer retention, and sales optimization.


**🎯 Business Objectives**

Identify high-value customer segments.

Understand purchasing trends across demographics.

Evaluate the impact of discounts and subscriptions on revenue.

Analyze category and product performance.

Discover customer loyalty patterns.

Provide recommendations to improve customer retention and increase sales.


**📊 Dataset Information**

Records: 3,900 transactions

Features: 18 columns

**Key Variables**

| Category              | Features                                        |
| --------------------- | ----------------------------------------------- |
| Customer Demographics | Age, Gender, Location                           |
| Purchase Details      | Item Purchased, Category, Purchase Amount       |
| Customer Behavior     | Subscription Status, Previous Purchases         |
| Transaction Details   | Shipping Type, Payment Method, Discount Applied |
| Feedback              | Review Rating                                   |
| Time Factors          | Season, Purchase Frequency                      |


**🛠️ Tech Stack**

Python – Data cleaning, preprocessing, feature engineering, and data preparation

Pandas – Data manipulation and transformation

SQLAlchemy – Database connection and data loading

PostgreSQL – Data storage and SQL analysis

SQL – Business query analysis and insight generation

Power BI – Interactive dashboard development and data visualization

Jupyter Notebook – Analysis and data preparation workflow


**🔄 Project Workflow**


**1. Data Cleaning & Preparation**

Inspected data using df.info() and df.describe()

Standardized column names to snake_case

Handled missing values in the review_rating column using category median imputation

Removed redundant columns such as promo_code_used


**Created new features including:**

age_group

purchase_frequency_days

**2. Database Integration**

Imported the cleaned dataset into PostgreSQL

Performed SQL analysis to answer business questions


**3. Exploratory Data Analysis (EDA)**

Analyzed customer demographics

Studied spending patterns by age and gender

Evaluated category-wise sales performance

Examined subscription and shipping preferences


**4. Dashboard Development**

Created an interactive Power BI dashboard to visualize:

Revenue trends

Customer segments

Product performance

Subscription insights

Discount impact

Demographic analysis


**📈 Key Insights**

Clothing generated the highest revenue and sales volume.

Young adults contributed the largest share of revenue.

Male customers generated higher overall revenue in this dataset.

1,053 customers had active subscriptions.

Subscribers and non-subscribers showed similar average spending behavior.

839 discounted purchases exceeded the average purchase amount.

Top-rated products included Gloves, Sandals, Boots, Hat, and Skirt.

3,116 customers were classified as loyal customers.



**⭐ If you found this project useful, consider giving it a star.**
