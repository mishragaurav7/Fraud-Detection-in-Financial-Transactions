# 💳 Fraud Detection in Financial Transactions

This project builds a machine learning model to detect fraudulent transactions using a Random Forest Classifier. By applying feature scaling, SMOTE for class balancing, and rigorous evaluation, the model achieved **99% recall** for fraud cases and a **ROC-AUC score of 0.9961**.

---

## 📌 Problem Statement

Financial institutions face major losses due to fraud. The goal of this project is to accurately identify suspicious transactions based on historical data and prevent potential frauds before they occur.

---

## 📊 Dataset Overview

- **Rows:** 500 transactions  
- **Columns:** 13 (including `Time`, `Amount`, `V1–V10`, `Class`)  
- **Target:** `Class` → 0 = Non-Fraud, 1 = Fraud  
- The dataset is **imbalanced**: 480 non-fraud vs. 20 fraud transactions.

---

## 🔍 Exploratory Data Analysis (EDA)

### ▶️ Class Distribution

<img width="349" height="212" alt="Distribution" src="https://github.com/user-attachments/assets/5169ef0c-b955-427a-ba8f-a71824654a47" />

---

## ⚙️ Machine Learning Pipeline

### ✅ Preprocessing
- Scaled features using `StandardScaler`
- Balanced the dataset using **SMOTE**

### ✅ Model
- Trained a **Random Forest Classifier**
- Used **train-test split** (70/30) after resampling

### ✅ Evaluation Metrics
| Metric        | Score |
|---------------|-------|
| Accuracy      | 97%   |
| Recall (Fraud)| 99%   |
| F1-Score      | 0.97  |
| ROC-AUC       | 0.9961|

---

## 📈 Confusion Matrix

|               | Predicted Non-Fraud | Predicted Fraud |
|---------------|---------------------|-----------------|
| Actual Non-Fraud | 92                  | 4               |
| Actual Fraud      | 1                   | 95              |

---

## 🧠 ROC Curve

<img width="403" height="307" alt="image" src="https://github.com/user-attachments/assets/e194faae-6fcf-4fea-9a6c-4de7e2dee8f1" />

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Jupyter Notebook

---

 **## 📁 How to Run**
1. Clone the repository
2. Install required libraries
3. Run the notebook  in Jupyter

---

## 📬 Contacts 

**Gaurav Mishra**  
📧 Email:7mishragaurav@gmail.com
🌐 LinkedIn: (www.linkedin.com/in/gaurav-mishra-3788ba271)
🐙 GitHub: (https://github.com/mishragaurav7)

---




