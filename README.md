# 🩺 Diabetes Prediction using Machine Learning

## 📌 Overview

This project predicts whether a person has diabetes based on medical data using Machine Learning classification algorithms.

The project compares:

- Logistic Regression
- Gaussian Naive Bayes

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
- Naive Bayes model training
- Model evaluation and comparison

---

## 📈 Model Performance

| Model               | Accuracy       | Precision      | Recall         | F1 Score       |
| ------------------- | -------------- | -------------- | -------------- | -------------- |
| Logistic Regression | 0.73           | 0.60           | 0.74           | 0.66           |
| Naive Bayes         | Add Your Score | Add Your Score | Add Your Score | Add Your Score |

---

## 📁 Project Structure

```bash
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
│   ├── logistic_regression_model.pkl
│   └── naive_bayes_model.pkl
│
├── reports/
│   ├── figures/
│   │   ├── confusion_matrix_lr.png
│   │   ├── confusion_matrix_nb.png
│   │   ├── correlation_heatmap.png
│   │   ├── feature_distribution.png
│   │   └── model_comparison.png
│   │
│   ├── lr_classification_report.txt
│   ├── lr_model_metrics.txt
│   ├── model_comparison.csv
│   ├── nb_classification_report.txt
│   └── nb_model_metrics.txt
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

- `01_eda.ipynb`
- `02_model_training.ipynb`

---

## 🎯 Goal

To understand a complete machine learning workflow and compare classification algorithms on a real-world medical dataset.
