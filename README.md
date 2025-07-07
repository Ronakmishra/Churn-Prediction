# 🚀 Churn Prediction

A modern analytics project using SQL Server, Power BI, and Python to uncover insights in customer data, visualize retention patterns, and predict which users are likely to leave—all in one place.

---

## 🚀 Project Overview

#### 🏁 Step 1: Bringing Data to Life (SQL Server)

Imported raw customer data into SQL Server, built the foundational `data_churn` database, and set up a robust staging table (`stg_Churn`) for all data cleaning. Designed key views like `vw_ChurnData` (tracks customer activity status) and `vw_JoinData` (monitors all new sign-ups).

---

#### 🔍 Step 2: Exploring & Transforming Insights

Used SQL scripts to deeply explore customer attributes, revenue, and missing values. Leveraged Power BI’s Power Query to engineer new fields (`Churn Status`), create age and charge groups, and reshape service data for powerful analytics.

---

#### 📊 Step 3: Telling the Story with Dashboards

Built interactive Power BI dashboards:

- **Churn Analysis:** Visualizes demographics, contracts, payment methods, usage, geography, and financial trends.
- **Prediction Insights:** Displays each customer’s churn probability, highlights the biggest drivers of churn, and summarizes key business metrics like churn rate and new customer counts.

---

#### 🤖 Step 4: Predicting the Future (Python ML)

Developed a Random Forest machine learning model in Python. Categorical features were encoded, data split for robust validation, and the model reached **96% accuracy**. Feature importance was visualized for interpretability. Predictions for new customers were exported to CSV for reporting and business use.

---

This workflow turns raw customer records into actionable retention insights, interactive dashboards, and accurate churn predictions—all integrated end to end.

---

## Highlights

- Complete data pipeline from ingestion to prediction
- Visual, actionable retention insights with dashboards
- Machine learning integration for smarter decisions

![Data Model](Data_model.png)

## 🔍 Insights Gained

**SQL Server** allowed me to efficiently organize, cleanse, and version large sets of customer data, forming a strong foundation for analysis.

**Power BI** transformed the processed data into dynamic dashboards, making it easy to visualize trends and uncover business insights.

**Machine Learning** brought predictive power to the project, enabling data-driven forecasts that support smarter retention strategies.
