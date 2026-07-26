# 🛍️ Customer Shopping Behavior Analysis

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql">
<img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi">
<img src="https://img.shields.io/badge/Data%20Analytics-End--to--End-success?style=for-the-badge">

</p>

---

# 📌 Project Overview

Customer Shopping Behavior Analysis is an end-to-end Data Analytics project that analyzes customer purchasing patterns using Python, PostgreSQL, and Power BI.

The project covers the complete analytics workflow, including data cleaning, feature engineering, SQL-based business analysis, and interactive dashboard development. The objective is to transform raw customer transaction data into actionable business insights that support data-driven decision making.

---

# 🎯 Project Objectives

- Analyze customer purchasing behavior
- Understand customer demographics
- Identify high-value customer segments
- Compare subscription and non-subscription customers
- Analyze product categories and revenue
- Study customer review ratings
- Evaluate shipping preferences
- Build an interactive business dashboard

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- pgAdmin 4
- Power BI
- Jupyter Notebook
- Git
- GitHub

---

# 📂 Project Structure

```
customer_behavior_analysis
│
├── dataset/
│   └── customer_shopping_data.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── report/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── README.md
│
└── LICENSE
```

---

# 📊 Dataset Information

The dataset contains customer shopping transactions collected from an e-commerce platform.

### Dataset Summary

- Total Records : **3,900**
- Total Features : **18**
- Missing Values : **37** (Review Rating)

### Features Include

- Customer ID
- Age
- Gender
- Location
- Item Purchased
- Category
- Purchase Amount
- Subscription Status
- Review Rating
- Shipping Type
- Discount Applied
- Purchase Frequency
- Previous Purchases
- Season
- Size
- Color

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed using Python:

- Imported dataset using Pandas
- Data exploration
- Missing value treatment
- Column standardization
- Feature engineering
- Created Age Groups
- Purchase frequency transformation
- Removed redundant columns
- Loaded cleaned data into PostgreSQL

---

# 🧠 SQL Business Analysis

The project answers multiple real-world business questions using PostgreSQL.

### Revenue Analysis

- Revenue by Gender
- Revenue by Age Group
- Revenue by Category

### Customer Analysis

- Subscriber vs Non-Subscriber Analysis
- Customer Segmentation
- Repeat Buyer Analysis
- High Spending Customers

### Product Analysis

- Top Rated Products
- Most Purchased Products
- Discount Dependent Products
- Top Products by Category

### Sales Analysis

- Shipping Type Comparison
- Average Purchase Amount
- Category-wise Sales
- Purchase Frequency Analysis

---

# 📈 Power BI Dashboard

The interactive dashboard provides business insights through multiple visualizations.
![Dashboard](https://github.com/amanpawar2004/customer_behavior_analysis/blob/main/customer_shopping_behavior_ss.png?raw=true)

### Dashboard Features

- Total Customers KPI
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Analysis
- Interactive Filters
- Gender Analysis
- Shipping Type Analysis

---

# 📊 Key Insights

- Clothing generated the highest revenue among all product categories.
- Young Adults contributed the highest revenue.
- Most customers were non-subscribers.
- Express Shipping showed a slightly higher average purchase amount than Standard Shipping.
- Loyal customers represented the largest customer segment.
- Product discounts significantly influenced purchasing behavior.

---

# 🚀 Skills Demonstrated

### Python

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis

### SQL

- Joins
- CTEs
- Window Functions
- Aggregate Functions
- Subqueries
- CASE Statements
- Ranking Functions
- Business Queries

### Power BI

- KPI Cards
- Bar Charts
- Donut Charts
- Slicers
- Interactive Dashboard
- DAX Measures
- Data Visualization

---

# 💼 Business Recommendations

- Increase customer subscriptions by offering exclusive member benefits.
- Reward repeat buyers through loyalty programs.
- Promote top-rated products in marketing campaigns.
- Optimize discount strategies to improve profitability.
- Focus marketing efforts on high-revenue customer segments.
- Improve inventory planning based on category performance.

---

# ▶️ Getting Started

## Clone Repository

```bash
git clone https://github.com/amanpawar2004/customer_behavior_analysis.git
```

---

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn psycopg2 jupyter
```

---

## Run the Notebook

Open

```
Customer_Shopping_Behavior_Analysis.ipynb
```

Execute all cells.

---

## PostgreSQL

Create a database.

Import the cleaned dataset.

Run

```
customer_behavior_sql_queries.sql
```

---

## Power BI

Open the Power BI dashboard file.

Refresh the dataset connection.

Explore the interactive dashboard.

---

# 🎯 Learning Outcomes

This project enhanced my practical knowledge of:

- Data Cleaning
- Exploratory Data Analysis
- SQL Query Optimization
- PostgreSQL
- Customer Segmentation
- Business Analytics
- Dashboard Development
- Data Visualization
- End-to-End Analytics Workflow

---

# 📈 Future Enhancements

- Machine Learning based Customer Segmentation
- Customer Churn Prediction
- Sales Forecasting
- Recommendation System
- Automated Dashboard Refresh
- Cloud Deployment

---

# 👨‍💻 Author

## Aman Pawar

**Data Analyst | SQL | Python | PostgreSQL | Power BI | Machine Learning**

- GitHub: https://github.com/amanpawar2004
- LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

---

# ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub.

Your support motivates me to build more real-world Data Analytics and AI projects.

---

## 📜 License

This project is licensed under the MIT License.
