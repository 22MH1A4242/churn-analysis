# 📊 Customer Churn Prediction – Machine Learning Project

## 📌 Problem Statement
Customer churn is a major challenge for subscription-based businesses.  
This project aims to predict whether a customer is likely to **churn (leave the service)** based on their demographic details, account information, and service usage patterns. Early churn prediction helps businesses take proactive retention actions.

---

## 📂 Dataset
- **Source:** Telecom Customer Churn Dataset (Kaggle / IBM sample dataset)
- **Rows:** 7,043 customers
- **Target Variable:** `Churn` (Yes / No)

### Key Features:
- Customer demographics (gender, senior citizen, dependents)
- Account information (tenure, contract type, payment method)
- Services subscribed (internet, security, streaming, tech support)
- Billing details (monthly charges, total charges)

---

## 🔧 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing
- Converted `TotalCharges` from object to numeric
- Handled missing values
- Encoded categorical variables using **one-hot encoding**
- Final dataset contained **32+ features**

---

### 2️⃣ Exploratory Data Analysis (EDA)
Performed visual analysis to understand churn behavior:
- Churn distribution (imbalanced: ~26% churn)
- Churn vs Contract Type
- Churn vs Internet Service
- Monthly Charges vs Churn
- Tenure vs Churn
- Correlation heatmap for numeric features

📊 Libraries used: **Seaborn, Matplotlib**

---

### 3️⃣ Feature Engineering
- Created derived features (e.g., high spenders)
- Removed non-informative columns (Customer ID)
- Stratified train-test split (80/20) to handle class imbalance

---

### 4️⃣ Model Building
Trained and evaluated Machine Learning models:
- **Logistic Regression**
- **Random Forest Classifier**

Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC Score

---

## 📈 Results

| Metric | Value |
|------|------|
| Accuracy | ~79% |
| ROC-AUC | ~0.82 |
| Churn Recall | ~50% |

✅ ROC-AUC > 0.82 indicates good separation between churn and non-churn customers.

---

## 🔍 Key Insights
- Customers on **month-to-month contracts** churn more
- **Higher monthly charges** are associated with higher churn
- **Longer tenure customers** are less likely to churn
- Lack of **online security and tech support** increases churn risk

---

## 🛠️ Tech Stack
- **Programming:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Tools:** Jupyter Notebook, Git, GitHub

---

## 📁 Project Structure
churn-analysis/
│── data/
│── notebooks/
│ └── churn_eda.ipynb
│── churn_cleaned.csv
│── requirements.txt
│── README.md


