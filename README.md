# Telecom Customer Churn Analysis – Power BI Dashboard

## Project Overview

This project presents an interactive Power BI dashboard analysing customer churn in a telecom dataset. The objective is to identify key drivers of churn and provide actionable insights to support customer retention strategies.

The dashboard enables stakeholders to explore churn patterns across customer demographics, contract types, payment methods, and service usage.

---

## Business Objective

Customer churn is a critical challenge in the telecom industry, directly impacting revenue and customer lifetime value.

This project aims to:

- Identify high-risk customer segments
- Understand behavioural and service related churn drivers
- Support data driven retention strategies

---

## Dashboard Overview

The dashboard provides a comprehensive view of churn behaviour, including:

### Key Metrics
- Total Customers: 7,032  
- Churned Customers: 1,869  
- Churn Rate: 27%  
- Average Monthly Charges: 64.80  
- Average Tenure: 32.42 months  

---

## Key Insights

Based on the analysis:

- Customers on **month-to-month contracts** show significantly higher churn  
- **New customers (0–12 months)** are at highest risk of churn  
- **Electronic check users** exhibit the highest churn rate  
- Customers without **technical support services** churn more  
- Customers without **partners or dependents** show higher churn  
- Higher **monthly charges** are associated with increased churn  

---

## Business Recommendations

- Promote **auto-payment methods** (bank transfer / credit card) to reduce churn  
- Encourage **long-term contracts** through targeted incentives  
- Provide **retention offers for new customers (0–12 months)**  
- Offer **bundled technical support services** for high-risk customers  
- Design targeted campaigns for customers with **high monthly charges**

---

## Tools & Technologies

- Power BI  
- DAX (Data Analysis Expressions)  
- Data Modelling  
- Data Visualisation  

---

## Dashboard Preview

Telecom-churn-powerbi-dashboard/images/Telecom Customer Churn Dashboard.png

---

## Repository Structure

```
├── dashboard/
│ └── Telco customer churn.pbix
├── images/
│ └── Telecom Customer Churn Dashboard.png
├── README.md

```
---
## Dataset

This project uses a publicly available telecom customer churn dataset.

Dataset source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---
## About the Author

Suresh Sampath Manawadu  
MSc Data Science – Coventry University  

I am interested in applying data analytics and machine learning to solve real-world business problems, particularly in telecom,infrastructure power and energy domains.

---

## Related Project

This dashboard complements a machine learning pipeline developed using PySpark and XGBoost:

https://github.com/manawadus/Telco-churn-pyspark


