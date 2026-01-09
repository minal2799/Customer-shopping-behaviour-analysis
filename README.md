# 🛒 Customer Shopping Behavior Analysis

**Python | SQL Server | Power BI**

## 📌 Project Overview

This project analyzes customer shopping behavior to uncover purchasing patterns, revenue drivers, and customer segmentation insights. The goal is to transform raw transactional data into actionable business intelligence using Python for data processing, SQL Server for storage and querying, and Power BI for visualization.

The project follows an **end-to-end analytics pipeline**: data cleaning → feature engineering → database integration → exploratory analysis → dashboarding.

---

## 🎯 Business Objectives

* Understand customer purchasing behavior across demographics and product categories
* Identify high-revenue customer segments
* Analyze the impact of subscriptions, discounts, and shipping methods on sales
* Enable data-driven marketing and retention strategies

---

## 📂 Dataset

* **Records:** 3,900+ customer transactions
* **Features:** 18 attributes including demographics, product details, purchase behavior, and subscription status
* **Source:** Public customer shopping behavior dataset (CSV format)

---

## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy
* **Database:** SQL Server (via SQLAlchemy & PyODBC)
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Loaded raw CSV data into Pandas DataFrame
* Validated schema and record counts

### 2️⃣ Data Cleaning & Feature Engineering

* Standardized column names
* Removed duplicate records
* Handled missing values
* Created derived features such as:

  * Age groups
  * Purchase frequency metrics

### 3️⃣ Data Storage (SQL Server)

* Persisted cleaned data into SQL Server using Python
* Automatically created relational tables via `df.to_sql()`
* Verified data integrity using SQL queries

### 4️⃣ Exploratory Data Analysis (EDA)

* Analyzed revenue distribution by:

  * Gender
  * Age group
  * Product category
  * Subscription status
  * Discount usage
* Identified customer segments contributing the majority of revenue

### 5️⃣ Visualization & Reporting

* Built an interactive Power BI dashboard with key KPIs:

  * Total customers
  * Average purchase value
  * Revenue by category
  * Subscription vs non-subscription trends
  * Customer segmentation insights

---

## 📊 Key Insights

* A small subset of customer segments contributes a **majority of total revenue**
* Subscription customers show **higher purchase frequency and average spend**
* Certain product categories consistently outperform others across age groups
* Discounts influence purchase behavior differently across demographics

