🛒 Customer Shopping Behavior Analysis

📌Overview

This project analyzes consumer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior. The primary objective is to identify actionable trends across demographics and product categories to help stakeholders optimize future marketing, inventory, and product strategies. 

📊 Dataset

The dataset consists of 3,900 transactions across 18 features.  

Demographics: Age, Gender, Location, and Subscription Status.  

Purchases: Item Purchased, Category, Purchase Amount (USD), and Season.  

Behavior Metrics: Discount Applied, Promo Code Used, Purchase Frequency, and Review Rating.  

🛠️ Tools & Technologies Used

Python (pandas): Data cleaning, imputation, and exploratory data analysis (EDA).

SQL (PostgreSQL): Advanced data querying, business transaction simulation, and customer segmentation.

Tableau: Interactive data visualization and dashboard creation.

Gamma & Word: Presentation and comprehensive project report generation.  

🚀 Project Steps

Data Preparation (Python): Imported the raw data, handled 37 missing values in the Review Rating column by imputing the category median, and engineered new features like age_group and purchase_frequency_days. 

Data Analysis (SQL): Loaded the cleaned dataset into a PostgreSQL database to run queries extracting insights on top-rated products, revenue by gender, and discount-dependent purchases. Customers were also segmented into New, Returning, and Loyal categories.  

Visualization (Power BI): Designed an interactive executive dashboard to highlight key KPIs and patterns visually.  

Reporting: Compiled a clear project report and presentation summarizing business recommendations.  

📈 Dashboard

The interactive Tableau dashboard provides a centralized view of the data, highlighting the 3.9K total customers, an average purchase amount of $59.76, and an average review rating of 3.75. Stakeholders can filter the visuals dynamically by subscription status, gender, product category, and shipping type. 

💡 Key Results & Insights

The Subscription Gap: Only 27% of the customer base is enrolled in the subscription program, leaving a massive 73% as non-subscribers. However, there is a huge opportunity to convert them, as 2,518 non-subscribers are repeat buyers.  

Revenue Drivers: Male customers drive significantly more revenue than female customers ($157,890 vs. $75,191). Furthermore, the Adult and Middle-Aged demographics are the core customer base driving the vast majority of sales.  

Category & Discount Reliance: Clothing is the absolute highest driver of both total revenue and transaction volume. However, the top 5 most purchased products have very high discount rates (between 47% and 50%), indicating a heavy reliance on promotions.  

Customer Loyalty: 80% of the customer base (3,116 customers) falls into the "Loyal" segment.  

⚙️ How to Run This Project

Clone the repository:Bashgit clone https://github.com/yourusername/customer-behavior-analysis.git

Python EDA: Open the notebooks/data_cleaning.ipynb file in Jupyter Notebook or VS Code to view the data cleaning and transformation steps.

SQL Queries: The sql_queries.sql file contains all the queries used for analysis. You can run these in pgAdmin or your preferred PostgreSQL environment.

Dashboard: Open the Customer_Behavior_Dashboard.pbix file in Power BI Desktop to interact with the visualizations.

Presentation: View the Project_Presentation.pdf (exported from Gamma) for the stakeholder pitch.
