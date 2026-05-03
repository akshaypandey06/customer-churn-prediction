# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is a major challenge in the telecom industry, where customers discontinue using services.  
This project aims to predict whether a customer will churn using machine learning techniques.

It is a **binary classification problem**:

- **1 → Churn**
- **0 → No Churn**

The objective is to help businesses identify high-risk customers and improve retention strategies.

---

## 📂 Dataset

- **Dataset:** Telco Customer Churn Dataset
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/blastchar/telco-customer-churn  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🔍 Project Workflow

1. Data Loading  
2. Data Cleaning  
   - Converted `TotalCharges` to numeric  
   - Removed missing values  
3. Exploratory Data Analysis (EDA)  
4. Data Preprocessing  
   - One-hot encoding  
   - Train-test split  
5. Feature Scaling (numerical features only)  
6. Model Building  
   - Logistic Regression  
   - Random Forest  
   - Decision Tree  
   - KNN  
   - SVM  
7. Model Evaluation  
   - Accuracy, Precision, Recall, F1 Score  
   - ROC Curve and ROC-AUC Score  

---

## 🤖 Models Used

- Logistic Regression  
- Random Forest  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  

---

## 📈 Results

- **Best Model:** Logistic Regression  
- Achieved highest ROC-AUC (~0.83)  
- Random Forest also performed well  
- Decision Tree showed comparatively lower performance  

---

## 💡 Key Insights

- Customers with **low tenure** are more likely to churn  
- **Month-to-month contracts** have higher churn rates  
- Higher **monthly charges** increase churn probability  
- Lack of **technical support/services** leads to higher churn  

---

## 🚀 Conclusion

The model successfully predicts customer churn and provides actionable insights.  
It can help telecom companies identify high-risk customers and improve retention strategies.

---

## 📁 Project Structure

Customer_Churn_Project/
│
├── churn_model.ipynb
├── README.md

---

## 👤 Prepared By

**AKSHAY PANDEY**  
Email: akshaypandey806@gmail.com  
Phone: 9098743494  

---
