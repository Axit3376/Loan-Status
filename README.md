# Loan Status Prediction 🏦🤖

This notebook predicts whether a person will get **loan approval** or not based on various personal and financial factors.  
It applies **Machine Learning classification models** to analyze applicant details and automate the loan approval decision process.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Results](#results)

---

## 📖 Overview
Financial institutions receive a large number of loan applications daily.  
Manually evaluating each application can be time-consuming and inconsistent.  

This project builds a **predictive model** that learns from historical loan application data and predicts whether a loan should be approved or not.  

---

## 🧩 Features
The model uses the following applicant details as input:
- **Age**  
- **Gender**  
- **Education**  
- **Income**  
- **Expense**  
- **Home Ownership**  
- **Loan Amount**  
- **Loan Interest Rate**  
- **Loan Intent (purpose of loan)**  
- **Loan Percent Income**  
- **Credit History**  
- **Loan Defaults**  

**Target Variable:** `Loan_Status` (Approved / Not Approved)

---

## 📊 Dataset
- **Source:** Kaggle Dataset 
- **Size:** ~X rows × Y columns  
- **Cleaning Steps:**
  - Missing value handling
  - Encoding categorical variables
  - Scaling numerical features  

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas, NumPy (Data Preprocessing)
- Matplotlib, Seaborn (EDA & Visualization)
- Scikit-learn (ML Models)
- Jupyter Notebook

---

## 🔄 Project Workflow
1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical variables (Gender, Education, Loan Intent, etc.)  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of applicant income, loan amount, age, etc.  
   - Correlation between features and loan status  

3. **Model Training & Evaluation**
   - Logistic Regression   
   - Random Forest  
   - Support Vector Machine (SVM)   

   **Metrics Used:**
   - Accuracy, Precision, Recall, F1-Score  

4. **Prediction**
   - Model predicts loan approval status based on new input data.  

---

## 📈 Results
- Achieved an accuracy of **92%** on the test set.  

---

