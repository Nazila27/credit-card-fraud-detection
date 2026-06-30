# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

Credit card fraud is one of the most critical challenges in the financial industry. Due to the highly imbalanced nature of fraud detection datasets, accurately identifying fraudulent transactions requires careful data analysis and appropriate machine learning techniques.

This project explores a real-world credit card transaction dataset, performs exploratory data analysis (EDA), and compares multiple machine learning models to detect fraudulent transactions.

---

## 🎯 Objectives

- Explore and understand the dataset
- Perform data preprocessing and cleaning
- Analyze transaction patterns
- Build multiple machine learning models
- Compare model performance
- Select the best-performing model for fraud detection

---

## 📂 Dataset

The dataset contains anonymized credit card transactions made by European cardholders.

- Features **V1–V28** are the result of **Principal Component Analysis (PCA)**.
- **Time** represents the elapsed time between transactions.
- **Amount** represents the transaction amount.
- **Class** is the target variable:
  - **0** = Legitimate Transaction
  - **1** = Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Scaling
7. Train-Test Split
8. Logistic Regression
9. Decision Tree
10. Random Forest
11. Model Comparison
12. Feature Importance
13. Final Conclusion

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|---------:|----------:|--------:|----------:|---------:|
| Logistic Regression | 0.9991 | 0.8485 | 0.5895 | 0.6957 | 0.9584 |
| Decision Tree | 0.9990 | 0.7204 | 0.7053 | 0.7128 | 0.8524 |
| Random Forest | **0.9995** | **0.9718** | **0.7263** | **0.8313** | 0.9239 |

---

## 🏆 Best Model

Among the evaluated models, **Random Forest** achieved the best overall performance.

Although Logistic Regression achieved the highest ROC-AUC score, Random Forest provided the best balance between **Precision**, **Recall**, and **F1-score**, making it the most suitable model for fraud detection in this project.

---

## 📁 Repository Structure

```
credit-card-fraud-detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Cross-validation
- Handling class imbalance with SMOTE
- Experimenting with XGBoost or LightGBM
- Deploying the model using Streamlit

---

## 👤 Author
Nazila Roudini

**Nazila Rdi**

This project was created as part of my Data Analytics & Machine Learning portfolio.
