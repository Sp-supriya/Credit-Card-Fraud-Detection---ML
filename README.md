---

## 💳 Credit Card Fraud Detection - Machine Learning

This project focuses on building a machine learning model to detect fraudulent credit card transactions. Using real-world anonymized transaction data, the goal is to identify fraudulent activities with high accuracy and low false positives. The dataset is highly imbalanced, making this a challenging and practical application of ML in the finance and cybersecurity domains.

### 🔍 Objectives

* Analyze and preprocess the credit card transaction dataset.
* Handle class imbalance using techniques like SMOTE or undersampling.
* Train and evaluate various classification models (Logistic Regression, Random Forest, XGBoost, etc.).
* Improve model performance using hyperparameter tuning and cross-validation.
* Measure performance using precision, recall, F1-score, ROC-AUC, and confusion matrix.

### 📁 Dataset

* The dataset used is from [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).
* It contains transactions made by European cardholders in September 2013.
* Features are anonymized (V1 to V28) due to confidentiality, along with `Time`, `Amount`, and `Class` (target: 0 for normal, 1 for fraud).

### 🛠️ Tools & Technologies

* **Python**
* **Pandas, NumPy, Matplotlib, Seaborn**
* **Scikit-learn**
* **Imbalanced-learn (SMOTE)**
* **XGBoost**

### 📊 Evaluation Metrics

* Confusion Matrix
* Accuracy
* Precision & Recall
* F1-Score
* ROC-AUC Curve

### 🚀 Outcome

The final model can successfully distinguish between legitimate and fraudulent transactions with high recall and precision, making it a strong baseline for real-world fraud detection systems.

---
