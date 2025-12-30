📌 Customer Churn Prediction – Machine Learning Project



🔹 Problem Statement

Customer churn is a critical challenge for subscription-based businesses. This project aims to predict whether a customer is likely to churn based on demographic details, service usage, and billing information, and to identify the key factors influencing customer retention.



🔹 Dataset Source

\- Dataset: Telco Customer Churn Dataset

\- Source: Kaggle

\- Records: 7,043 customers

\- Target Variable: Churn (Yes / No)

\- Features: Customer demographics, service subscriptions, contract details, and billing data



🔹 Steps Taken

1️⃣ Data Cleaning \& Preprocessing

\- Converted TotalCharges from object to numeric and handled missing values

\- Verified data quality and ensured no null values

\- One-hot encoded categorical variables

\- Created new features such as High Spender flag and Tenure groups



2️⃣ Exploratory Data Analysis (EDA)

\- Analyzed churn distribution (class imbalance: ~26% churn)

\- Visualized churn trends across contract type, internet service, tenure, and monthly charges

\- Identified higher churn among month-to-month contracts and short-tenure customers



3️⃣ Feature Engineering

\- Applied one-hot encoding to categorical variables (32 total features)

\- Prepared ML-ready dataset

\- Performed 80/20 train-test split with stratification



4️⃣ Model Building \& Evaluation

\- Trained Logistic Regression and Random Forest models

\- Evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC

\- Achieved ~79% accuracy and ROC-AUC ≈ 0.82



🔹 Key Insights

\- Month-to-month contract customers have the highest churn

\- Customers with lower tenure are more likely to churn

\- Higher monthly charges correlate strongly with churn

\- Contract type and tenure are the strongest churn predictors



🔹 Visualizations Included

\- Churn distribution

\- Churn by contract type

\- Churn by internet service

\- Monthly charges vs churn

\- Tenure vs churn

\- Correlation heatmap

\- ROC curve and model evaluation plots



🔹 Final Outputs

\- Cleaned and ML-ready dataset

\- Trained churn prediction model

\- EDA and evaluation visualizations

\- Feature importance analysis



✅ Resume Value

\- End-to-end ML pipeline

\- Business-focused insights

\- Strong evaluation metrics (ROC-AUC > 0.82)

\- Clear data visualization and interpretation



