## 📦 E-Commerce Shipping Optimization

## 🎯 Project Goal
This project focuses on identifying factors contributing to late deliveries and forecasting shipping/freight costs using predictive modeling techniques. By leveraging ~11,000 shipment records, we explore key drivers behind delivery performance and build models that support logistics optimization and operational efficiency.

## 🛠️ Workflow (CRISP-DM)
1. Business Understanding ✔️
2. Data Understanding 🔎
3. Data Preparation 🔄
4. Modeling data 🔗
5. Evaluation 📊
6. Deployment 💡

## 🗂️ Project Structure
- `data/` - Contains raw and cleaned data.
- `notebooks/` - Exploratory and modeling notebooks.
- `src/` - Scripts for data processing, modeling, and results

---

## 📌 Project Overview

Timely delivery is critical to customer satisfaction in e-commerce. Our objectives include:
1. Predict whether a shipment will arrive on time.
2. See what featuress caus these delays.
3. Make business decisions and adjustments to prevent delays.

We perform data cleaning, exploratory analysis, feature engineering, and develop machine learning models to uncover actionable insights.

---

## 📊 EDA Highlights

All EDA notebooks can be found in: [`notebooks/EDA`](notebooks/EDA)

---

## 🔍 Modeling Approach

### 1. **Classification Task** – Predicting Late Delivery
- Models: Logistic Regression, Random Forest, XGBoostclassifier

 🛠️ Technologies Used
Programming Language: Python

Data Manipulation: pandas, NumPy

Modeling: scikit-learn

Visualizations: Matplotlib, Seaborn

Development Environment: Jupyter Notebook, Google Colab

📈 Results
Model Performance: The best model achieved an accuracy of 66% post tuning in predicting on-time deliveries (Random Forest & XGBoost)
- Evaluation:
  Accuracy: 67%
  Precision: 0.76
  Recall: 0.67
  F1-score: 0.70
  ROC-AUC Curve: 74%


💡 Key Insights :
Discount Offered and derived Discount Ratio has a significant impact/correlation on delivery times ✅





