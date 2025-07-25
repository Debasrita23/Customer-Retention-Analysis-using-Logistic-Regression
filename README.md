# Customer Churn Analysis using Logistic Regression


This project aims to predict customer churn in a telecom company using **Logistic Regression**. Early identification of at-risk customers can help businesses retain users through targeted strategies.

---

## 📂 Dataset

**File:** `Telco-Customer-Churn.csv`  
**Source:** IBM Sample Dataset

### Features include:
- Customer demographics (e.g., Gender, SeniorCitizen)
- Service usage (e.g., InternetService, StreamingTV)
- Account information (e.g., Tenure, MonthlyCharges, PaymentMethod)
- Target: `Churn` (Yes = 1, No = 0)

---

## 🧠 Project Highlights

- Cleaned and preprocessed data (handled nulls, label encoded categories)
- Scaled features with `StandardScaler`
- Trained a **Logistic Regression** model
- Evaluated with Accuracy, Confusion Matrix, and ROC-AUC Curve

---

## 📊 Results

- **Accuracy**: ~80%  
- **Important features**: Contract Type, Tenure, Monthly Charges  
- ROC Curve plotted with AUC for model performance visualization

