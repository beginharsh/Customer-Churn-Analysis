# Customer-Churn-Analysis Banking Domain
finding the churn rate and determining what could be the contributing factor in increasing of the churn rate to help business make informed decisions
Project Overview

Customer churn is a critical challenge for banks, directly impacting revenue and long-term customer value. This project focuses on identifying high-risk customer segments, understanding key churn drivers, and enabling data-driven retention strategies using interactive analytics.

The analysis is performed on a dataset of ~10,000 banking customers and visualized using Power BI.

## 🎯 Business Problem
-The organization was experiencing a ~20% customer churn rate without clear visibility into:
-Which customer segments were churning the most
-What behavioral and financial factors were driving churn
-Where retention efforts should be prioritized

As a result, retention actions were reactive and non-targeted, leading to revenue leakage, especially from high-value customers.

## ⚙️ What Was Done
-Cleaned and prepared customer-level data for analysis 
-Segmented customers based on:
  - Age groups
  - Credit score bands
  - Account balance ranges
  - Product ownership
  - Credit card ownership
  - Activity status (active vs inactive)
- Built an interactive Power BI dashboard to:
  - Track overall churn KPIs
  - Compare churn rates across customer segments
  - Identify high-risk and high-value churn cohorts

## 📊 Key Metrics Analyzed
- Overall churn rate (%)
- Churn rate by age group
- Churn rate by credit score band
- Churn rate by account balance range
- Churn comparison by activity status
- Product and credit card ownership vs churn

## 💡 Key Insights

Overall churn rate ~20%, but churn was highly concentrated in specific segments

51–60 age group showed the highest churn (~56%), indicating risk among mid-to-late career customers

High-balance customers (>₹200K) had elevated churn (~55%), posing significant revenue risk

Customers with credit scores between 500–600 showed higher churn compared to prime segments

Inactive customers churned significantly more than active customers


## 📈 Recommendations

- Implement early-warning churn triggers for high-balance and mid-age customer segments
- Design relationship-based retention programs for high-value customers instead of generic offers
- Improve engagement and cross-sell strategies (e.g., credit card adoption) to reduce inactivity-driven churn
- Monitor mid-credit score customers closely with targeted loyalty and engagement initiatives


## 🛠 Tools & Technologies
- Power BI – Data modeling, DAX measures, interactive dashboards
- Excel / CSV – Data preparation and validation
- SQL (conceptual) – Churn segmentation logic
