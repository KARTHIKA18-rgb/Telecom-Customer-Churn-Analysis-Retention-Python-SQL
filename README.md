# 📊 Telecom Customer Churn Analysis & Retention | Python, SQL

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project analyzes customer behavior to identify the key factors influencing churn and provides actionable insights that can help improve customer retention.

The analysis is performed using Python and interactive visualizations to understand customer demographics, service usage, contract types, payment methods, and billing patterns.

---

## 🎯 Objectives

- Analyze customer churn patterns.
- Identify factors contributing to customer attrition.
- Compare churn across different customer segments.
- Generate business insights for improving customer retention.
- Visualize trends using interactive charts.

---

## 📂 Dataset

**Dataset Name:** Telco Customer Churn Dataset

The dataset contains information about **7,043 telecom customers** with **21 features**, including:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

**Target Variable**

- **Churn**
  - Yes
  - No

---

## 🛠️ Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly Express
- Seaborn

---

## 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
```

---

## 🔍 Data Analysis Process

### 1. Data Loading

- Imported CSV dataset
- Created a working copy of the data

### 2. Data Understanding

- Checked dataset shape
- Displayed column names
- Examined data types
- Summary statistics
- Unique values
- Missing values

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

- Overall Churn Distribution
- Gender vs Churn
- Senior Citizen vs Churn
- Contract Type vs Churn
- Internet Service vs Churn
- Payment Method vs Churn
- Tenure Distribution
- Monthly Charges Distribution
- Total Charges vs Tenure

---

# 📈 Visualizations Included

- 📌 Overall Churn Pie Chart
- 👨‍👩‍👧 Gender-wise Churn Analysis
- 👴 Senior Citizen Churn Comparison
- 📄 Contract Type Analysis
- 🌐 Internet Service Analysis
- 💳 Payment Method Analysis
- ⏳ Tenure Distribution
- 💰 Monthly Charges Distribution
- 📊 Total Charges vs Tenure Scatter Plot

---

# 💡 Key Insights

### 📌 Overall Churn

- Majority of customers stayed with the company.
- A significant portion of customers discontinued the service, highlighting the importance of retention strategies.

### 📄 Contract Type

- Customers with **Month-to-Month contracts** showed the highest churn rate.
- Customers with **One-Year** and **Two-Year contracts** were more likely to stay.

### 🌐 Internet Service

- Fiber Optic users experienced relatively higher churn.
- Customers without internet service had comparatively lower churn.

### 💳 Payment Method

- Customers using **Electronic Check** showed higher churn.
- Automatic payment methods were associated with better customer retention.

### ⏳ Tenure

- Customers with shorter tenure were more likely to churn.
- Long-term customers had a much lower churn rate.

### 💰 Monthly Charges

- Customers paying higher monthly charges tended to churn more frequently.

### 👴 Senior Citizens

- Senior citizens showed a comparatively higher churn rate than non-senior customers.

### 👨 Gender

- Churn rates between male and female customers were nearly similar, indicating gender had minimal impact.

---

# 📊 Business Recommendations

- Encourage customers to switch from month-to-month to long-term contracts.
- Improve customer experience for Fiber Optic users.
- Offer loyalty rewards to new customers during the first year.
- Introduce discounts for automatic payment methods.
- Monitor customers with high monthly charges and provide personalized retention offers.
- Focus retention campaigns on customers with low tenure.

---

## 📁 Project Structure

```
Telecom-Customer-Churn/
│
├── Telecom_Customer_Churn_Analysis.ipynb
├── Telco-Customer-Churn.csv
├── README.md
└── images/
```

---

## 🚀 Future Improvements

- Build a Machine Learning model for churn prediction.
- Create an interactive Power BI dashboard.
- Perform feature engineering and model optimization.
