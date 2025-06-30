# 💳 Credit Risk Modeling

This project aims to predict whether a loan applicant is likely to default based on their financial and credit history. By building a classification model, financial institutions can reduce the risk of issuing high-risk loans.

---

## 🔍 Objective

To identify loan applicants with a high probability of default using machine learning techniques and feature engineering on credit-related datasets.

---

## 📊 Features Used

- `credit_amount`: Total loan requested
- `duration`: Loan repayment period
- `income`: Applicant’s income
- `credit_utilization`: `credit_amount / (duration + 1)`
- `income_to_loan_ratio`: `income / (credit_amount + 1)`
- Employment & Housing Status
- Credit History, Purpose of Loan, etc.

---

## 🧠 Machine Learning Models

| Model                 | Accuracy | AUC Score |
|----------------------|----------|-----------|
| Logistic Regression  | ~78%     | ~0.79     |
| LightGBM Classifier  | ~85%     | ~0.87     |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- LightGBM
- Seaborn, Matplotlib

---

## 📈 Evaluation Metrics

- Confusion Matrix
- Classification Report
- ROC-AUC Curve
- F1-Score, Precision, Recall

---

## 📷 Visualizations

- ROC Curve (AUC comparison)
- Confusion Matrix heatmap
- Feature Distribution Plots

---

## 🚀 How to Run

1. Open `credit_risk_modeling.ipynb` in Google Colab.
2. Upload the dataset `credit_dataset.csv`.
3. Run all cells to train, test, and evaluate models.

---

## 📂 Dataset

You can use any open credit risk dataset, such as:

**🔗 Kaggle Source**:  
[Credit Scoring Dataset – mlcourse](https://www.kaggle.com/datasets/kashnitsky/mlcourse)

---

## ✅ Outcomes

- Identified the most impactful features for credit risk assessment
- LightGBM outperformed baseline logistic regression
- Learned how to handle real-world financial datasets effectively

---

## 📌 Author

Developed during a Data Science Internship – 2025  
[Your Name](#) | [LinkedIn](#) | [GitHub](#)

---

