# Customer-Churn-Analysis
Customer Churn Analysis is a data analytics project focused on understanding the reasons why customers leave a service (churn). Using real-world telecom customer data, the project leverages Python and powerful visualization libraries to identify key trends, patterns, and factors that contribute to customer churn.

Customer churn analysis helps businesses understand why customers stop using their service. This project focuses on analyzing a telecom company's dataset to identify churn patterns and provide actionable insights using Python and data visualization.

---
## 📁 Dataset

- File: `Customer Churn.csv`
- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 🧠 Project Objective

The goal of this project is to:
- Analyze customer attributes and behaviors that lead to churn
- Visualize key trends and drivers of customer attrition
- Support business decisions to reduce churn and improve customer retention

---

## 🗂️ Dataset Overview

The dataset used is from a telecom company and includes customer demographic info, services used, contract types, payment methods, tenure, and whether the customer has churned.

### Key Columns:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`, `TechSupport`, etc.
- `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
- `Churn` (Target variable)

---

## 🧼 Data Preprocessing

- Missing values in `TotalCharges` replaced and converted to float.
- `SeniorCitizen` (1/0) mapped to 'Yes'/'No' for clarity.
- Cleaned and explored data using `.info()` and `.describe()`.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations were created to explore churn patterns across multiple dimensions:

### 1. Churn Distribution
- Count and pie chart show ~26.5% of customers have churned.

### 2. Senior Citizens
- Higher churn among senior citizens.

### 3. Contract Types
- Month-to-month customers churn the most.
- One-year and two-year contracts reduce churn.

### 4. Services Used
- Lack of **tech support**, **online security**, or **backup** correlates with higher churn.
- Fiber optic users churn more than DSL users.

### 5. Tenure
- Short-tenure customers (new users) are more likely to leave.

### 6. Payment Method
- Electronic check users churn more than those using mailed checks or bank transfer.

---

## 📈 Visualizations

The project uses `matplotlib` and `seaborn` to generate charts such as:
- Count plots
- Pie charts
- Bar charts
- Stacked bar plots
- Histograms

These help identify key risk factors contributing to churn.

---

## 💡 Key Insights

| Insight | Recommended Action |
|--------|---------------------|
| Month-to-month contracts → High churn | Promote long-term contracts |
| Senior citizens churn more | Offer tailored plans or better support |
| Fiber optic churn is high | Educate on benefits or lower cost |
| Short-tenure churn | Improve early engagement experience |
| Lack of tech support/security | Upsell support packages |
| Electronic check users churn | Offer digital-friendly options |

---

## 🛠️ Tools & Libraries

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook / VS Code

---

## 📌 Business Use Case

This analysis is essential for:
- Telecom and subscription-based companies
- Marketing teams targeting high-risk customers
- Customer success teams developing retention strategies

---

## 🚀 Future Work

- Build predictive models (e.g., logistic regression, decision trees)
- Deploy as an interactive dashboard using Streamlit or Power BI
- Include feature importance with ML models


