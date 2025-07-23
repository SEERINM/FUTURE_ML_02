# 🚨 Churn Prediction System  
*Machine Learning Task 2 | By Future Interns*

## 📌 Project Overview

This project focuses on predicting **customer churn** using machine learning techniques. Churn prediction is vital in various industries like telecom, banking, and SaaS, helping businesses identify customers likely to leave and take proactive retention steps.

We’ve used a real-world **Telco Customer Churn dataset**

---

## 📂 Dataset

The dataset used in this project is:
- 📄 **WA_Fn-UseC_-Telco-Customer-Churn.csv**  
- It contains information about demographics, services availed, contract types, billing methods, and churn status.

---

## 📌 Key Highlights

### ✅ 1. Data Preprocessing
- Handled missing values in `TotalCharges`
- Removed irrelevant columns like `customerID`
- Converted categorical features to numerical using **Label Encoding**
- Addressed class imbalance using **SMOTE**

### 📊 2. Exploratory Data Analysis (EDA)
- Visualized distribution of continuous features
- Boxplots to check for outliers
- Count plots for categorical columns
- Correlation heatmap for numerical features

### 🤖 3. Model Training
Trained and evaluated the following models:
- Decision Tree
- Random Forest
- XGBoost (XGBRFClassifier)
- Used `cross_val_score` for validation

### 📈 4. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 💾 5. Model Serialization
- Saved trained model using **Pickle**
- Saved encoders for future predictions

### 🧠 6. Predictive System
- Created an input system to predict churn on new customer data
- Output includes both predicted label and churn probability

### 🔍 7. Feature Importance
- Plotted feature importances using bar graph

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Scikit-learn**
- **XGBoost**
- **imblearn (SMOTE)**
- **Pickle**

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `Churn.ipynb` | Main Jupyter Notebook |
| `customer_churn_model.pkl` | Trained Random Forest model |
| `encoders.pkl` | Label encoders for categorical features |
| `churn_output.csv` | Output predictions with probabilities |
| `README.md` | Project documentation |

---


