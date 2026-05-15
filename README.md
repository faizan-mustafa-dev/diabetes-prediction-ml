# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Overview

This project predicts whether a person has diabetes based on medical data using a Logistic Regression model.

---

## 📊 Dataset

- Source: Diabetes dataset
- Target column: `Outcome`
  - 0 → No Diabetes
  - 1 → Diabetes

---

## ⚙️ Workflow

- Data loading
- Data cleaning (handled missing/invalid values)
- Exploratory Data Analysis (EDA)
- Train-test split
- Feature scaling
- SMOTE for class balancing
- Logistic Regression model training
- Model evaluation

---

## 📈 Model Performance

- Accuracy: 0.73
- Precision: 0.60
- Recall: 0.74
- F1 Score: 0.66

---

## 📁 Project Structure

```
diabetes-prediction-ml/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_model_training.ipynb
│
├── models/
│   └── logistic_regression_model.pkl
│
├── reports/
│   ├── figures/
│   ├── classification_report.txt
│   └── model_metrics.txt
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- joblib

---

## 🚀 How to Run This Project

```bash
pip install -r requirements.txt
```

Then open notebooks:

- 01_eda.ipynb
- 02_model_training.ipynb

---

## 🎯 Goal

To understand a complete machine learning workflow using Logistic Regression.
