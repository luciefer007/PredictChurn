# 📉 Customer Churn Prediction

This project uses logistic regression to predict customer churn using the Telco Customer Churn dataset from Kaggle.

## 📌 Overview

Churn prediction is a critical business problem in the telecom industry. This notebook explores the Telco dataset to build a classification model that predicts whether a customer is likely to leave the company or not.

---

## 🔍 Dataset

- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Contains customer demographics, account details, and service usage.
- Target column: `Churn` (Yes or No)

---

## 🧠 Machine Learning Task

- Type: Binary Classification
- Algorithm: Logistic Regression
- Metric: Accuracy, Precision, Recall, F1-score

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming |
| pandas | Data manipulation |
| scikit-learn | Modeling & Evaluation |
| Google Colab | Notebook Environment |

---

## 🚀 How To Run

1. Download the dataset from the [Kaggle Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Open the `customer_churn_prediction_colab.ipynb` file in Google Colab
3. Upload the dataset using the upload widget
4. Run all cells to:
   - Preprocess data
   - Train logistic regression model
   - Evaluate and save predictions

## 📈 Sample Output

Example metrics:
- Accuracy: ~80%
- Precision/Recall: Depends on class balance
- Confusion Matrix output

## 📤 Exported Files

- `churn_predictions.csv`: File with actual and predicted churn status for test samples.
