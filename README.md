---

## 💳 Credit Card Fraud Detection - MACHINE LEARNING

This project aims to build a machine learning model that can detect fraudulent credit card transactions. The dataset used is highly imbalanced, making it a good case study for applying classification techniques and handling data imbalance.

### Project Goals:

* Understand and preprocess the dataset
* Explore data imbalance and apply balancing techniques like SMOTE
* Train multiple ML models such as Logistic Regression, Random Forest, and XGBoost
* Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC

### Dataset:

* Sourced from [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* Includes 284,807 transactions with 492 fraud cases
* Features are anonymized (V1 to V28), with `Amount`, `Time`, and `Class` (target variable)

### Tools & Libraries:

* Python
* Pandas, NumPy, Seaborn, Matplotlib
* Scikit-learn
* Imbalanced-learn (SMOTE)
* XGBoost

### Results:

* Models were successfully trained and evaluated
* Achieved strong performance in detecting fraud with high recall and precision
* ROC-AUC score used to measure overall performance

---
