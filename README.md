Customer Churn Prediction & Segmentation — Telco BI Project

Business Intelligence & Analytics 
Predicting telecom customer churn using machine learning and delivering actionable retention strategies through interactive dashboards.


Project Overview
Customer churn is one of the most critical challenges in the telecom industry. This project builds an end-to-end Business Intelligence and Analytics pipeline on a real-world Telco dataset of 7,043 customers, combining predictive ML models with RFM-based customer segmentation to identify at-risk customers and recommend targeted retention actions.


Methodology
1. Data Preprocessing

Handled missing values in TotalCharges
Encoded categorical variables
Feature scaling for model training

2. Exploratory Data Analysis (EDA)

Churn rate analysis by contract type, tenure, and payment method
Distribution of monthly charges among churned vs. retained customers
Support ticket keyword frequency analysis

3. Customer Segmentation (RFM Analysis)
Customers segmented into four groups based on Recency, Frequency, and Monetary value

5. Churn Risk Tiering

6. Machine Learning Models
Three classification models were trained and evaluated:
ModelAUC-ROCLogistic Regression0.838 BestANN (Neural Network)0.832Decision Tree0.826
ROC curves were plotted for all three models for visual comparison.

Dashboards
Python Dashboard (matplotlib / seaborn)

KPI cards: Total Customers, Churn Rate, CLV, High-Risk Count, Best AUC
Churn Rate by Contract Type (bar chart)
Churn Risk Tiers (pie chart)
Churn Rate by RFM Segment (bar chart)
RFM Segment Distribution (bar chart)
Model AUC-ROC Comparison (bar chart)
ROC Curves — All Models (line chart)
Top Churn Keywords from Support Tickets (frequency chart)
Retention Action Map (text legend)

Power BI Dashboard

Interactive filters by Churn, Contract, and Segment
Total Customers by Churn Risk Tier (pie chart)
Churn Rate by Contract Type (bar chart)
Total Customers by Segment Name (bar chart)
RFM Segment Distribution (donut chart)
Contract-level breakdowns with CLV and high-risk customer counts
Retention Action Map panel
