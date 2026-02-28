📊 Task-3: Customer Segmentation & Churn Deep-Dive Analysis
🎯 Objective

The objective of this project is to solve a multi-faceted business problem by analyzing customer churn patterns and building an interactive Tableau dashboard that enables data-driven decision making.

This project focuses on identifying high-risk customer segments and providing actionable business insights through KPI tracking and segmentation analysis.

📌 Core Key Performance Indicators (KPIs)

The following KPIs were formally defined and calculated:

Churn Rate
Churn Rate = AVG(Churn)
Measures the percentage of customers who have exited the bank.

Retention Rate
Retention Rate = 1 - AVG(Churn)
Indicates customer loyalty and stability.

Total Customers
Total Customers = COUNT(Customer ID)
Represents the total active customer base.

Average Account Balance
Average Balance = AVG(Balance)
Helps evaluate customer value and financial engagement.

These KPIs provide a clear snapshot of business health and customer behavior.

🔎 Deep-Dive Analysis: Customer Segmentation

A segmentation strategy was implemented based on customer balance:

High Value Customers

Medium Value Customers

Low Value Customers

This segmentation allows the business to understand which customer groups are most likely to churn.

Key Insights:

High value customers show a comparatively higher churn rate.

Medium value customers demonstrate moderate churn behavior.

Low value customers have the lowest churn percentage.

This suggests potential dissatisfaction or service gaps among premium customers.

These insights help prioritize retention strategies where they matter most.

📊 Interactive Dashboard Features

The Tableau dashboard includes:

KPI Cards (Churn Rate, Retention Rate, Total Customers, Avg Balance)

Segment-wise Churn Rate visualization

Segment-wise Total Customers comparison

Segment-wise Average Balance analysis

Interactive filtering by Customer Segment

Clean and structured layout for business presentation

The dashboard allows users to dynamically explore customer segments and analyze churn patterns interactively.

💡 Business Recommendations

Based on the analysis:

Develop targeted retention campaigns for High Value customers.

Investigate service quality and engagement gaps for premium segments.

Implement personalized offers to reduce churn risk.

Monitor churn KPIs regularly using automated dashboards.

🛠 Tools Used

Python (Data Cleaning & Segmentation)

Pandas & Seaborn (EDA)

Tableau (Dashboard & Visualization)

GitHub (Project Documentation)
