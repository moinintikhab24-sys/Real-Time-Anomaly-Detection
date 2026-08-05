# Real-Time Anomaly Detection in Financial Transactions

## Project Overview

This project detects fraudulent credit card transactions using unsupervised machine learning algorithms. Since fraud cases are extremely rare, anomaly detection techniques are used instead of traditional supervised classification.

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Preprocess the dataset using RobustScaler
- Implement Isolation Forest
- Implement Local Outlier Factor (LOF)
- Compare both models
- Evaluate using Precision, Recall, F1-Score and Confusion Matrix

---

## Dataset

Dataset: Credit Card Fraud Detection Dataset

Due to GitHub's 100 MB upload limit, the dataset is not included in this repository.

Download:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place `creditcard.csv` in the project folder before running the notebook.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Models Implemented

### Isolation Forest

- Detects anomalies by isolating observations using random decision trees.

### Local Outlier Factor (LOF)

- Detects anomalies by comparing the local density of observations with their neighbors.

---

## Evaluation Metrics

- Precision
- Recall
- F1 Score
- Confusion Matrix
- Precision–Recall Curve
- PCA Visualization
- Training Time Comparison

---

## Results Summary

| Model | Precision | Recall | F1 Score |
|------|----------:|-------:|---------:|
| Isolation Forest | 0.2305 | 0.2947 | 0.2587 |
| LOF | 0.0000 | 0.0000 | 0.0000 |

Isolation Forest achieved better fraud detection performance while requiring significantly less training time than Local Outlier Factor.

---

## Repository Contents

- anomaly_detection.ipynb
- Performance_Analysis_Report.pdf
- Live_Link.txt

---

## Author

Moin Intikhab
