# Power BI Churn Analysis

## Overview

This project involves the analysis of churn patterns among bank customers using Power BI. The primary objectives were to clean and preprocess the data, create data models, develop custom measures using DAX, and visualize insights to understand customer behavior. This README provides an overview of the project and its key components.

![Power BI Dashboard]https://github.com/ViviyanT/Power_BI_Churn_Analysis/blob/main/Dashboard.png

## Project Goals and Objectives

- Data Preparation: Clean and preprocess the provided bank customer churn data.
- Data Modeling: Create meaningful data models and relationships.
- Custom Measures: Develop custom measures using DAX to analyze churn rate.
- Visualizations: Create informative visualizations to explore relationships between churn and various factors.
- Analysis: Explore relationships between churn rate and various factors to identify correlations.

## Data Source

The dataset for this project is available on Kaggle: [Bank Customer Churn Prediction](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction).

## Key Steps

### Data Preparation

- Utilized Power Query for data preparation.
- Cleaned and transformed the raw data:
  - Renamed columns for clarity.
  - Handled irrelevant columns.
  - Corrected data types.
  - Replaced numeric codes with meaningful labels.
  - Grouped data for Age, Credit Score, and Balance into manageable ranges.
  - Ensured proper data types for the grouped columns.

### Data Modeling

- Structured data models to establish relationships.
- Ensured correct relationships between data queries.

### Custom Measures

- Developed custom measures using DAX:
  - Count of customers.
  - Count of churned customers.
  - Churn rate (percentage of customers who left).

### Visualizations

- Created informative visualizations, including:
  - Cards displaying total customers and churn rate.
  - Donut charts to visualize customer distribution by various factors.
  - Line and clustered column charts to explore relationships between churn rate and grouped factors (e.g., age groups, credit score groups, account balance).
  - Ensured correct sorting for ascending order in visualizations.

### Analysis

#### Key Findings

- **Age Group Impact:** The highest churn rate is observed in customers ranging from their mid-30s to around 60 years old. This age segment exhibits a notably higher likelihood of churning compared to other age groups.

- **Credit Score Influence:** Churn rate tends to be highest among customers with lower credit scores.

- **Account Balance Dynamics:** Customers with account balances exceeding 200,000  exhibit a higher churn rate. This observation raises questions about the factors influencing the decision to leave the bank among customers with higher account balances.

These insights provide valuable information for the bank to strategize and focus efforts on retaining customers, especially those in the identified high-churn categories.

## Instructions

To explore the Power BI analysis and report:

1. Download and install Power BI Desktop.
2. Open the Power BI file included in this repository.
3. Interact with the report, explore visualizations, and gain insights.

---

