# 🧠 Logistic Regression Binary Classification Project

## 📌 Objective
This project builds a binary classifier using **Logistic Regression** on a structured dataset to predict a categorical outcome. It follows a complete machine learning pipeline using **Scikit-learn, Pandas, and Matplotlib** and includes model evaluation with metrics like **precision, recall, confusion matrix, ROC-AUC**, and **threshold tuning**.

---

## 🛠️ Tools & Libraries
- Python 3.8+
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📁 Project Structure

LogisticRegression-BinaryClassification/
│
├── data/
│ └── data.csv # Raw dataset used for classification
│
├── notebooks/
│ └── Task4_AI&ML.ipynb # Complete Jupyter notebook with code and analysis
│
├── images/
│ └── roc_curve.png # Evaluation plots (ROC, confusion matrix, etc.)
│
├── README.md # Project overview, objectives, and results
└── requirements.txt # Python dependencies

---

## 📊 Dataset Overview

The dataset consists of `569` rows and `33` columns. The target column is **binary** with values `0` and `1`, representing negative and positive outcomes, respectively.

Features include numerical and/or categorical attributes used to train the logistic regression model. The dataset was split into training and test sets and scaled using `StandardScaler`.

---

## 🚀 Model Overview

We trained a **Logistic Regression** model and evaluated it using:
- Confusion Matrix
- Accuracy, Precision, Recall, F1-Score
- ROC Curve & AUC
- Threshold Tuning with Sigmoid Interpretation

---

## 📈 Results Summary

- Accuracy: 0.9736842105263158
- Precision: 0.9761904761904762
- Recall: 0.9534883720930233
- F1 Score: 0.9647058823529412
Key features influencing predictions were:
- Custom Threshold (0.4) Evaluation:
  [[70  1]
  [ 1 42]]
- Precision: 0.9767441860465116
- Recall: 0.9767441860465116

---



