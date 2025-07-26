# 💳 Credit Card Fraud Detection using Machine Learning

This project demonstrates how to detect fraudulent credit card transactions using a **Random Forest Classifier** on an imbalanced dataset. It includes data analysis, model training, evaluation, and visualization of results using Python.

## 📂 Dataset

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It includes **284,807 transactions**, among which only **492 are fraudulent**.

📥 **[Download the Dataset](https://drive.google.com/file/d/1pJ043b0EDNYYrGEZHZeZIZ4bHKyOA1C7/view?usp=sharing)**  

## 🧠 Technologies Used

- Python 🐍
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 🚀 Features

✅ Exploratory Data Analysis  
✅ Handling Class Imbalance  
✅ Fraud vs Valid Transaction Analysis  
✅ Correlation Heatmap  
✅ Train-Test Split  
✅ Random Forest Classifier  
✅ Model Evaluation with:
- Accuracy
- Precision
- Recall
- F1-Score
- Matthews Correlation Coefficient (MCC)
- Confusion Matrix Visualization

---

## 📊 Project Flow

### 1. 📁 Data Loading & Cleaning
- Loaded CSV using `pandas`
- Split data into fraud and valid cases

### 2. 🔍 Exploratory Analysis
- Used `describe()` to understand amount distribution
- Calculated outlier ratio
- Visualized correlation matrix using a heatmap

### 3. 🧪 Model Building
- Removed `Class` column from features
- Split into train-test (80/20)
- Used `RandomForestClassifier` from `sklearn`

### 4. ✅ Model Evaluation

| Metric | Score |
|--------|-------|
| Accuracy | 99.96% |
| Precision | 97.74% |
| Recall | 77.55% |
| F1-Score | 86.36% |
| MCC | 86.91% |

🔷 **Confusion Matrix** shows high true positive rate with minimal false positives.

---

## 📌 Key Insights

- Fraud cases are extremely rare (~0.17%)
- Precision is prioritized to avoid false alarms
- MCC is a robust metric in imbalanced scenarios

---
