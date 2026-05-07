# Customer Churn Prediction & Revenue Analysis Using Machine Learning

## 📌 Project Overview
This project focuses on predicting customer churn and analyzing revenue-related customer behavior using Machine Learning techniques. The objective is to help businesses identify customers who are likely to leave the company and uncover the major factors influencing churn decisions.

The project demonstrates an end-to-end Data Science workflow including:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine Learning model training
- Model evaluation
- Business insight generation

By leveraging predictive analytics, organizations can improve customer retention strategies, reduce revenue loss, and make data-driven business decisions.

---

# 🚀 Key Features

✅ Customer churn prediction using Machine Learning  
✅ Revenue and customer behavior analysis  
✅ Data cleaning and preprocessing pipeline  
✅ Feature encoding and transformation  
✅ Exploratory Data Analysis (EDA)  
✅ Logistic Regression model implementation  
✅ Model performance evaluation using classification metrics  
✅ Business-focused insights for retention strategies  

---

# 🧠 Business Problem

Customer churn is one of the most critical challenges faced by subscription-based and service-oriented companies. Losing customers directly impacts revenue and long-term business growth.

This project aims to:
- Predict whether a customer is likely to churn
- Identify patterns behind customer attrition
- Analyze factors affecting customer retention
- Support proactive business decision-making

---

# 📂 Dataset Information

The dataset contains customer demographic, subscription, and billing-related information.

### Important Features

| Feature Name        | Description |
|---------------------|-------------|
| customer_id         | Unique customer identifier |
| gender              | Customer gender |
| age                 | Customer age |
| country             | Customer country |
| contract_type       | Monthly or yearly subscription |
| monthly_charges     | Monthly billing amount |
| tenure              | Customer relationship duration |
| churn               | Target variable (0 = No Churn, 1 = Churn) |

---

# ⚙️ Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

---

# 📊 Project Workflow

## 1️⃣ Data Collection
- Imported customer dataset using Pandas
- Inspected data structure and feature types

## 2️⃣ Data Preprocessing
- Handled missing values
- Converted categorical variables into numerical format
- Applied one-hot encoding
- Prepared training and testing datasets

## 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Examined customer revenue patterns
- Investigated relationships between churn and customer attributes

## 4️⃣ Feature Engineering
- Encoded categorical variables
- Removed unnecessary columns
- Prepared ML-ready feature matrix

## 5️⃣ Model Building
Implemented:
- Logistic Regression Classifier

## 6️⃣ Model Evaluation
Evaluated performance using:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report

---

# 📈 Machine Learning Model

## Logistic Regression

The Logistic Regression model was trained to classify customers into:
- Churn Customers
- Non-Churn Customers

The model helps businesses:
- Detect high-risk customers
- Improve customer retention campaigns
- Reduce revenue leakage

---

# 📉 Business Insights Generated

The analysis helps identify:
- High-risk customer segments
- Revenue-impacting churn patterns
- Customer behavior trends
- Subscription-related churn factors

These insights can support:
- Customer retention strategies
- Personalized marketing
- Revenue optimization

---

# 🏗️ Project Structure

```bash
Customer-Churn-Prediction/
│
├── customer_data.csv
├── Customer Project.ipynb
├── README.md
│
├── outputs/
│   ├── charts/
│   ├── reports/
│
└── requirements.txt
