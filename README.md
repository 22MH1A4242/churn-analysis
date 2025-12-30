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

<img width="1091" height="599" alt="image" src="https://github.com/user-attachments/assets/2ea81201-933a-4625-a83a-e851f0c83b3e" />
<img width="737" height="495" alt="Screenshot 2025-12-30 170822" src="https://github.com/user-attachments/assets/d34d4944-7ddc-418e-a0be-785e6dd0a5ea" />
<img width="732" height="499" alt="Screenshot 2025-12-30 170835" src="https://github.com/user-attachments/assets/71261250-549c-4b72-a1cb-73e230820f15" />
<img width="1195" height="851" alt="Screenshot 2025-12-30 170928" src="https://github.com/user-attachments/assets/efbc7421-3a7d-4aed-a45d-caa7b69e9fe4" />
<img width="1293" height="650" alt="Screenshot 2025-12-30 170942" src="https://github.com/user-attachments/assets/22f3077e-69f6-455e-b426-6fd9218ef555" />
<img width="674" height="545" alt="Screenshot 2025-12-30 171002" src="https://github.com/user-attachments/assets/13996ca0-f4ed-456a-b86d-32f01831bd77" />
<img width="823" height="526" alt="Screenshot 2025-12-30 171008" src="https://github.com/user-attachments/assets/e62db27b-5a3a-4305-b870-45519d57a287" />
<img width="1402" height="510" alt="Screenshot 2025-12-30 165824" src="https://github.com/user-attachments/assets/18826205-e1b8-4ba7-a65b-5acd6fef3e4a" />
<img width="1333" height="829" alt="Screenshot 2025-12-30 171058" src="https://github.com/user-attachments/assets/8859c79e-3e10-433c-bdf4-b56c87e55c1f" />
<img width="767" height="571" alt="Screenshot 2025-12-30 171112" src="https://github.com/user-attachments/assets/66c98262-20be-41e7-822d-e2860a71f35c" />
