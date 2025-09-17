# Credit Score Classification Project

## 📌 Overview
This project analyzes customer financial and behavioral data to predict credit scores (Good, Standard, Poor) using machine learning models.  
The aim is to help financial institutions assess creditworthiness effectively.

## 📊 Dataset
- ~100,000 records
- 28 features: demographics, income, loans, delayed payments, credit utilization, etc.
- Target: `Credit_Score` (Good / Standard / Poor)

## 🛠️ Methods
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding & Scaling
- Handling Class Imbalance (SMOTE)
- Model Implementation:
  - Logistic Regression
  - Random Forest
  - XGBoost (tuned with Optuna)

## ✅ Results
- Logistic Regression: ~75% accuracy
- Random Forest: ~83% accuracy
- XGBoost (tuned): ~83% accuracy, macro-F1 ~0.82  
**XGBoost was the best performing model.**

## 🚀 Future Improvements
- Cost-sensitive learning
- Advanced feature engineering (e.g., debt-to-income ratio)
- Fairness and bias checks

## 📂 Files
- `Project1_Piasabazar_labmentix.ipynb` → main notebook
- `requirements.txt` → dependencies
- `README.md` → project details

- 🚀 How to Run

Clone the repo:

git clone https://github.com/your-username/credit-score-prediction.git


Navigate to project folder:

cd credit-score-prediction


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Project1_Piasabazar_labmentix.ipynb
