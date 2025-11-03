# Customer-Churn-Analysis
Telco Customer Churn Prediction  This repository contains an end-to-end data analysis and machine learning project using the Telco Customer Churn Dataset. The goal of this project is to analyze key customer attributes, identify churn drivers, and build predictive models to help businesses improve customer retention.
Project Overview

Customer churn is a critical business metric, especially for subscription-based services. This project explores:

What factors influence customer churn

How customer demographics, subscribed services, and account information affect churn

Machine learning models to predict if a customer is likely to churn

📂 Dataset Information

The dataset used is the Telco Customer Churn dataset from IBM Sample Data Sets.

Each row represents a unique customer and includes information such as:

Category	Description
Target Variable	Churn – whether the customer left in the last month
Services Signed Up For	Phone, Internet, Security, Backup, Device Protection, Tech Support, Streaming
Customer Account Information	Tenure, Contract Type, Payment Method, Paperless Billing, Monthly & Total Charges
Demographics	Gender, Senior Citizen, Partner, Dependents
📏 Dataset Shape

Rows: 7,043

Columns: 21

🧾 Column Data Types

17 categorical, 2 numerical, 2 integer

📊 Exploratory Data Analysis (EDA)

Multiple visualizations were created to understand churn behavior and feature distribution using Matplotlib and Seaborn.

✅ Churn Distribution

Count plot & Pie chart to show churn ratio

~26.5% of customers have churned

👥 Customer Demographics vs Churn

Visualized churn patterns by:

Gender

Senior Citizen status

Tenure

Key findings:

Senior citizens show higher churn % than non-senior customers

🧾 Subscription Services vs Churn

Count plots across:

Internet Services

Online Security

Tech Support

Streaming Services

Device Protection, Online Backup, Multiple Lines

Insight:

Churn rate significantly increases when customers do not opt for support-oriented services like Tech Support & Online Security.

📄 Contract & Payment Method vs Churn

Visualizations show:

Month-to-month customers churn more than yearly contract users

Electronic check users have highest churn rate
Insights Summary

Short-term (month-to-month) customers have higher churn probability

Lack of value-added services (security/support) increases churn

Higher monthly charges correlate with churn

Senior citizens & electronic-check users churn more frequently
