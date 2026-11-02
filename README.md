# 🚢 Titanic Survival Prediction - Machine Learning Project

This project contains an end-to-end Machine Learning pipeline to predict passenger survival on the Titanic dataset.

## 🛠️ Workflow & Steps:
1. **Data Preprocessing:** Handled missing values (imputed Age using the **Median**).
2. **Feature Scaling:** Standardized numerical features using `StandardScaler` (fitted strictly on the training set to prevent Data Leakage).
3. **Model Comparison:** Trained and evaluated three models:
   - **KNN**
   - **Decision Tree**
   - **Random Forest** (Best Performing Model)

## 🚀 Tech Stack:
- Python, Pandas, Scikit-Learn
