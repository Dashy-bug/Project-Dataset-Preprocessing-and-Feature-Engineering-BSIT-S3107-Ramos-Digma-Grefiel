# FinMark Customer Segmentation using K-Means

## Project Overview
This project analyzes customer behavior data from FinMark Corporation to identify meaningful customer segments using unsupervised machine learning.

By grouping customers with similar transaction patterns and satisfaction levels, FinMark can improve targeted marketing strategies and personalized financial services.

---

## Project Workflow

Data Preprocessing  
→ Feature Engineering  
→ Exploratory Data Analysis  
→ Clustering (K-Means)  
→ Customer Segmentation  
→ Business Insights

---

## Dataset

The analysis uses two datasets:

Transaction Data
- Customer transactions
- Transaction amount
- Transaction type

Customer Feedback Data
- Satisfaction score
- Likelihood to recommend

These datasets were cleaned, merged, and aggregated to create customer-level behavioral features.

---

## Feature Engineering

Key engineered features include:

- Total Spending
- Transaction Frequency
- Average Satisfaction Score
- Likelihood to Recommend
- Log-transformed Spending

These features capture both financial activity and customer sentiment.

---

## Clustering Method

K-Means clustering was applied after feature scaling.

Steps performed:

1. Feature selection
2. Data normalization
3. Optimal cluster testing (Elbow + Silhouette)
4. Model training
5. PCA visualization

---

## Customer Segments Identified

The clustering analysis revealed four customer personas:

### Ideal Champions
High spending, strong engagement, and high recommendation likelihood.

### Silent High-Spenders
High spending but lower likelihood to recommend.

### Vocal Critics
Moderate spending but highly opinionated customers.

### At-Risk Low Value
Low spending and lower engagement.

---

## Business Insights

The segmentation allows FinMark to implement targeted strategies:

Ideal Champions → loyalty programs  
Silent High-Spenders → referral incentives  
Vocal Critics → service improvement initiatives  
At-Risk Low Value → re-engagement campaigns

---

## Authors

BSIT-S3107  
Ramos, Digma
