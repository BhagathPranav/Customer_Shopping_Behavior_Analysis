# 🛒 Customer Shopping Behavior Analysis: End-to-End Data Pipeline & Dashboard

## 📌 Executive Summary
This project analyzes consumer shopping behavior using a dataset of 3,900 retail transactions. The goal of this analysis is to uncover insights into spending patterns, customer segmentation, and subscription behavior to help stakeholders optimize future marketing, inventory, and customer retention strategies. 

By building a complete data pipeline from Python (cleaning) to PostgreSQL (analysis) and Tableau (visualization), this project translates raw transactional data into actionable business intelligence.

## 🛠️ Tech Stack & Tools
* **Data Manipulation & Cleaning:** Python (Pandas)
* **Database & Querying:** PostgreSQL, pgAdmin
* **Data Visualization:** Tableau Desktop
* **Reporting & Presentation:** Gamma, Microsoft Word

## 📊 The Dataset
The analysis is based on **3,900 transactions** containing 18 distinct features:
* **Demographics:** Age, Gender, Location, and Subscription Status.
* **Purchases:** Item Purchased, Category, Purchase Amount (USD), and Season.
* **Behavior Metrics:** Discount Applied, Purchase Frequency, and Review Rating.

## 🚀 Methodology & Project Steps

1. **Data Preparation (Python):** * Handled missing data (imputed 37 missing `Review Rating` values using category medians).
   * Engineered new analytical features, including `age_group` and `purchase_frequency_days`.
2. **Exploratory Data Analysis (SQL):** * Loaded the cleaned dataset into a PostgreSQL database.
   * Simulated business transactions and wrote complex queries to extract insights on top-rated products, revenue by demographic, and discount reliance.
   * Segmented the customer base into *New*, *Returning*, and *Loyal* cohorts.
3. **Interactive Visualization (Tableau):** * Designed a dynamic executive dashboard centralizing key performance indicators (KPIs).
   * Implemented global interactive filters allowing stakeholders to slice data by Subscription Status, Gender, Category, and Shipping Type.
4. **Strategic Reporting:** * Compiled a comprehensive project report and stakeholder presentation to communicate business recommendations clearly.

## 💡 Key Business Insights & Recommendations

* **The Subscription Opportunity:** Only **27%** of the customer base is enrolled in the subscription program. However, 2,518 non-subscribers are repeat buyers, presenting a massive opportunity for a targeted conversion campaign.
* **Core Revenue Drivers:** Male customers generate significantly more revenue than female customers (**$157,890 vs. $75,191**). Additionally, the *Adult* and *Middle-Aged* demographics are the most profitable segments.
* **Category Performance & Discount Reliance:** *Clothing* is the highest driver of both total revenue and transaction volume. However, the top 5 most purchased products experience high discount rates (47%–50%), indicating a need to review promotional pricing strategies to protect profit margins.
* **Customer Loyalty:** A striking **80%** of the customer base (3,116 customers) falls into the "Loyal" segment, indicating strong brand retention.

## ⚙️ How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/customer-behavior-analysis.git](https://github.com/yourusername/customer-behavior-analysis.git)
