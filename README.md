
#  Credit Card Fraud Detection using Logistic Regression

This project focuses on detecting fraudulent credit card transactions using Logistic Regression. The dataset is highly imbalanced, and techniques are used to improve fraud detection performance.

##  Objective

Identify fraudulent credit card transactions based on historical data using **Logistic Regression**, a simple yet effective classification algorithm.

##  Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraudulent cases**: 492 (only ~0.17%)
- **Features**:
  - `Time`, `Amount`, `Class` (target)
  - 28 anonymized PCA components: `V1` to `V28`

## ⚙️ Workflow

1. **Data Preprocessing**
   - Checked for missing values


2. **Model Training**
   - Trained a **Logistic Regression** model using Scikit-learn
   - Tuned hyperparameters like `C`, `penalty`, `solver`

3. **Evaluation Metrics**
   - Accuracy

## 🧪 Results

accuracy 97

> Note: Emphasis is placed on **Recall** to ensure fraudulent transactions are not missed.

