# 📉 ChurnVision: Predicting Customer Churn in Telecom using Machine Learning

Welcome to **ChurnVision**, an end-to-end machine learning project that predicts telecom customer churn using advanced analytics and explainable AI techniques (SHAP). This project combines data science best practices, visual storytelling, and business insight generation.

---

## 🚀 Project Overview

- 🎯 **Objective**: Predict whether a customer will churn (leave) based on account and service-related features.
- 📊 **Dataset**: Telco Customer Churn (7,043 entries, 21 columns)
- 🧠 **Techniques**: EDA, Feature Engineering, Classification Modeling, SHAP Explainability
- 📦 **Tools Used**: Python, Pandas, Scikit-learn, XGBoost, Seaborn, SHAP, Matplotlib, Plotly

---

## 📂 Folder Structure

```
churn-prediction/
│
├── notebook/                      # Kaggle-ready .ipynb file
├── data/                         # Dataset files (CSV)
├── images/                       # Exported plots (optional)
├── README.md                     # Project overview
```

---

## 🛠️ Key Steps

1. **Data Cleaning**
   - Missing value handling
   - Type conversion (`TotalCharges`)
   - Outlier detection

2. **EDA & Visualization**
   - Churn rate analysis
   - KDE plots, bar charts, pie charts
   - Categorical vs target analysis

3. **Feature Engineering**
   - Label Encoding for binary columns
   - One-Hot Encoding for multiclass columns
   - StandardScaler for numeric features

4. **Modeling & Evaluation**
   - Models: Logistic Regression, Random Forest, XGBoost
   - Metrics: Accuracy, Precision, Recall, F1, ROC AUC
   - Cross-model performance comparison

5. **Explainability (SHAP)**
   - Global feature importance
   - Individual prediction interpretation
   - Force & summary plots

---

## 🏆 Model Performance

| Model               | Accuracy | F1 Score | ROC AUC |
|---------------------|----------|----------|---------|
| Logistic Regression | 0.80     | 0.66     | 0.83    |
| Random Forest       | 0.82     | 0.70     | 0.85    |
| XGBoost             | **0.84** | **0.72** | **0.86** |

---

## 💡 Business Insights

- 📉 Month-to-month contracts are strongly associated with churn.
- 💸 High monthly charges increase churn risk.
- 🕐 Short-tenure customers are more likely to leave.

**Recommendation**: Promote long-term contracts and loyalty incentives for new customers.

---

## 📎 Resources

- [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- [SHAP Documentation](https://shap.readthedocs.io/en/latest/index.html)

---

## 🙌 Author

👤 **Your Name Here**  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile)  
🐙 [GitHub](https://github.com/yourusername)  
📩 you@example.com

---

> ⭐ *If you like this project, don't forget to give it a star and connect!*  
