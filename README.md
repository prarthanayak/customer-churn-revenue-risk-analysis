Customer Churn & Revenue Risk Analysis

📌 Problem Statement

Customer churn directly impacts revenue and long-term business sustainability.
This project analyzes telecom customer data to identify churn drivers, estimate revenue at risk, and help prioritize customer retention efforts using data-driven insights.

🎯 Business Objective

Identify key factors contributing to customer churn

Segment customers based on churn risk and revenue impact

Estimate potential revenue at risk due to churn

Support data-driven retention prioritization

🗂 Dataset

Source: Telecom customer churn dataset

Records: ~7,000 customers

Key Features:

Customer tenure

Contract type

Monthly charges

Payment method

Churn indicator

🔍 Approach & Methodology

Data Cleaning & Preparation

Handled missing values and encoded categorical variables

Prepared data for analysis and modeling

Exploratory Data Analysis (EDA)

Analyzed churn distribution

Studied churn patterns across contract types, tenure, and charges

Identified high-risk customer segments

Churn Modeling

Built predictive churn models using machine learning

Evaluated model performance using classification metrics

Used churn probabilities to segment customers by risk level

Revenue Risk Estimation

Linked churn likelihood with monthly charges

Estimated potential revenue exposure from high-risk customers

📈 Key Insights

Month-to-month contract customers show significantly higher churn rates

Customers with shorter tenure are more likely to churn

High monthly charges combined with high churn probability indicate critical revenue risk segments

Not all churn should be prevented — prioritization is essential for cost-effective retention

💡 Business Recommendations

Focus retention efforts on high-value, high-risk customers

Design targeted offers for month-to-month contract users

Avoid spending retention resources on low-revenue churn segments

Use churn probability thresholds to guide retention strategy

🛠 Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook
