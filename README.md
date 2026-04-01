# 📊 Customer Churn Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing customer churn behavior in a telecom company using Excel-based data analysis and dashboarding techniques. The goal is to identify key factors influencing customer churn and provide actionable insights to improve customer retention.

---

## 🎯 Objectives

* Analyze customer churn patterns
* Identify high-risk customer segments
* Understand the impact of contract types and tenure
* Provide insights to improve retention strategies

---

## 🧾 Dataset Description

The dataset contains customer-level information including:

* Customer demographics (gender, senior citizen, etc.)
* Account information (tenure, contract type)
* Services subscribed (online security, backup, etc.)
* Billing details (monthly charges, total charges)
* Target variable: **Churn (Yes/No)**

---

## 🧹 Data Cleaning Steps

The following steps were performed in Excel:

* Removed unnecessary columns (e.g., customerID)
* Handled missing values in `TotalCharges`
* Converted data types (text → numeric)
* Standardized categorical values (e.g., "No internet service" → "No")
* Removed duplicate records
* Created new features:

  * Customer Lifetime Value (CLV)
  * Tenure Groups
* Converted churn into binary format for analysis

---

## 📊 Dashboard Overview

![Dashboard Preview](Analysis%20Overview.png)

The dashboard provides a comprehensive view of customer churn through multiple KPIs and visualizations:

### 🔑 Key Metrics

* **Total Customers:** 5174
* **Churn Rate:** 36.12%
* **Churned Customers:** 1869

---

## 📈 Key Insights

### 📌 1. Contract Type Impact

* Customers with **month-to-month contracts** have the highest churn
* Long-term contracts (1-year, 2-year) significantly reduce churn

### 📌 2. Tenure Analysis

* Highest churn observed in **0–6 months tenure group**
* Customers staying longer are less likely to churn

### 📌 3. Services Impact

* Customers without **online security & backup services** show higher churn
* Value-added services improve retention

### 📌 4. Revenue Insights

* Customers who churn tend to have slightly lower average monthly charges
* High-value customers need targeted retention strategies

---

## 📌 Tools Used

* Microsoft Excel

  * Data Cleaning
  * Pivot Tables
  * Charts & Visualization
  * Dashboard Design

---

## 🚀 How to Use

1. Download the dataset
2. Open the Excel file
3. Explore the dashboard using filters/slicers
4. Analyze trends and insights

---

## 💡 Business Recommendations

* Promote long-term contracts to reduce churn
* Target new customers (0–6 months) with retention offers
* Bundle services like online security and backup
* Identify high-risk customers early using churn indicators

---

## 📁 Project Structure

```
📦 Customer-Churn-Analysis
 ┣ 📄 README.md
 ┣ 📊 Telco_Churn_Data.xlsx
 ┣ 🖼️ Analysis Overview.png
 ┗ 📁 Dashboard Files
```

---

## 🙌 Acknowledgements

This project is based on a Telco Customer Churn dataset commonly used for data analytics learning and practice.

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect!

---

⭐ If you like this project, don't forget to give it a star!
d
