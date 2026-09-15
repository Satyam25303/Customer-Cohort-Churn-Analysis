# Customer Cohort & Churn Analysis

## 📊 Project Overview

This project analyzes customer churn and retention using a large retail dataset. Python was used for data cleaning, customer-level analysis, cohort analysis, and churn segmentation. Power BI was then used to create an interactive dashboard to visualize key customer behavior and retention insights.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- DAX
- Google Colab

## 📁 Dataset

The project uses the **Retail Data Warehouse – 12 Table 1M+ Rows Dataset** from Kaggle.

The dataset contains information about customers, orders, order items, payments, returns, shipments, products, stores, categories, suppliers, employees, and promotions.

## 🔍 Analysis Performed

- Customer-level revenue and order analysis
- Customer churn analysis
- Order frequency analysis
- Customer value segmentation
- Customer risk segmentation
- Value × risk analysis
- Revenue associated with customer risk
- Cohort-based customer retention analysis

## 📈 Key Insights

- Overall customer churn rate: **68.64%**
- **47.41%** of customers are classified as high risk.
- High-value customers have a churn rate of **58.60%**, compared with **78.30%** for low-value customers.
- Customers with only one order have a churn rate of **93.45%**.
- Customers with 7+ orders have a churn rate of **58.34%**.
- High-risk customers are associated with approximately **₹1.60 billion** in revenue.
- Cohort retention shows a sharp decline after the first purchase month, followed by relatively stable retention.

## 📊 Power BI Dashboard

![Customer Cohort & Churn Dashboard](dashboard.png)

The dashboard includes:

- Total Customers
- Total Revenue
- Churn Rate
- High-Risk Customers
- Churn Rate by Order Frequency
- Churn Rate by Customer Value
- Customer Risk Distribution
- Revenue by Customer Risk
- Cohort Retention Analysis

## 📂 Project Files

- `CustomerCohort&ChurnAnalysis.ipynb` — Python analysis notebook
- `Customer Cohort and Churn Analysis.pbix` — Power BI dashboard
- `dashboard.png` — Dashboard preview

## 🎯 Business Objective

The objective of this project is to identify customer groups with higher churn risk and understand how customer value and purchase frequency relate to retention. These insights can help businesses prioritize customer retention and engagement strategies.
