# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn is a major challenge in the banking industry, where retaining customers is more cost-effective than acquiring new ones.  
This project aims to **predict customer churn** using machine learning techniques by analyzing customer demographics and financial behavior.

A **Random Forest Classifier** is trained after thorough data preprocessing, exploratory data analysis, and class imbalance handling.

---

## 🎯 Objectives
- Analyze customer behavior and churn patterns
- Perform exploratory data analysis (EDA)
- Handle class imbalance using oversampling techniques
- Build and evaluate a machine learning model for churn prediction

---

## 🗂️ Dataset
The dataset used in this project is publicly available on Kaggle.

🔗 **Download Dataset:**  
[Bank Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)

### Dataset Description
The dataset consists of customer-level banking information such as:
- Demographic details (Age, Gender)
- Financial attributes (Balance, Credit Score)
- Account-related features
- Target variable indicating whether the customer exited (churned)

### Notes
- The `Complain` feature was removed due to strong correlation with churn.
- Each customer ID is unique and appears only once.

---

## 🔍 Exploratory Data Analysis (EDA)
Key observations from EDA:
- The dataset is **highly imbalanced**.
- Older customers tend to churn more frequently.
- Female customers show slightly higher churn rates.
- Several numerical features exhibit different distributions for churned vs non-churned customers.

---

## ⚙️ Data Preprocessing
The following steps were applied:

- Separation of numerical and categorical features
- Encoding of categorical variables:
  - One-hot encoding for nominal features
  - Ordinal encoding for ordered features
- Feature scaling using Min-Max Scaling
- Handling class imbalance using **SMOTE**

---

## 🤖 Model Used
- **Random Forest Classifier**

### Why Random Forest?
- Handles non-linear relationships effectively
- Robust against overfitting
- Works well with tabular data

---

## 📊 Model Evaluation
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics provide a balanced view of performance, especially for imbalanced datasets.

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - imbalanced-learn

---

## ▶️ How to Run
 Clone the repository:
   ```bash
   git clone https://github.com/Aayush-0111/Customer-Churn-Prediction-Model
