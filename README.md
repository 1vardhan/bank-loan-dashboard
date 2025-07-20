 # 🏦 Bank Loan Portfolio Analysis Dashboard + Machine Learning

## 📊 Project Overview

This project empowers banking institutions and financial analysts to **monitor, evaluate, and optimize lending operations** using both **business intelligence (Power BI + SQL)** and **predictive analytics (Machine Learning)**.

### ✅ Key Capabilities:
- Business insights through **interactive dashboards**
- **Classification of good vs. bad loans**
- **ML model to predict default risk**
- Segment-wise performance metrics and geographic analysis

---

## 💡 Problem Statement

Banks often struggle with:
- Identifying **high-risk borrowers early**
- **Predicting loan default** to reduce financial losses
- Understanding **borrower profiles and behavior**
- Optimizing lending strategies across regions and products

---

## 🚀 Features

### 🔹 Power BI Dashboard
- **KPI Cards:** Total Loan Applications, Funded Amount, Received Amount, Avg. Interest Rate, Avg. DTI
- **Line Charts:** Application and Repayment Trends (Month-over-Month)
- **Donut/Bar Charts:** Loan Purpose, Term, Employment Length
- **Maps:** Lending distribution by state
- **Treemaps:** Home Ownership Segmentation
- **Drilldown Table:** Loan-level record inspection

### 🔹 SQL Data Pipeline
- All backend data cleaning and preparation via **raw SQL queries**
- Aggregations for:
  - MTD / PMTD performance
  - Good vs. Bad Loan Segments
  - Purpose & region-wise lending behavior
  - Loan health and recovery insights

---

## 🧠 Machine Learning Module

### 🔹 Goal:
Classify loans as **Good (Fully Paid/Current)** or **Bad (Charged Off)** using **Logistic Regression + SMOTE** to address class imbalance and **reduce false negatives**.

### 🔹 Steps:
- Preprocessing of loan data: missing value handling, encoding, scaling
- **SMOTE applied** to balance bad loan samples
- **Logistic Regression model** trained and evaluated
- Model compared with alternatives like XGBoost and Random Forest
- Logistic Regression chosen for better interpretability and risk sensitivity

### 🔹 Metrics:
- **Accuracy:** 92%
- **Recall (Bad Loans):** 95%
- **Confusion Matrix** indicates high precision and minimized false negatives

---

## 📈 KPIs Tracked

| KPI | Description |
|-----|-------------|
| Total Loan Applications | Number of loans applied |
| Funded Amount | Approved loan amounts |
| Received Amount | Repayment collected |
| Average Interest Rate | Borrower cost measure |
| Average DTI | Debt-to-Income risk |
| Good vs. Bad Loan Ratio | Health of portfolio |
| Month-over-Month Change | Lending performance trend |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI | Dashboarding and visualization |
| SQL | Data extraction, joins, filtering, aggregations |
| Python (Scikit-learn, imbalanced-learn, pandas) | ML pipeline |
| Jupyter/Colab | Model training and evaluation |
| SMOTE | Handling class imbalance |
| Logistic Regression | Default risk prediction |

---

## 📂 Folder Structure

