# Banking-Customer-Churn-Data-Wrangling
Data Immersion, Quality Assessment, and Data Cleaning for a Banking Customer Churn Dataset
# 📊 Banking Customer Churn – Data Cleaning & Transformation

## 📌 Project Overview
This project focuses on data immersion, quality assessment, and data cleaning using a banking customer churn dataset.  
The objective is to prepare a clean, analysis-ready dataset by identifying and resolving common data quality issues encountered in financial services data.

---

## 🏦 Dataset Description
- **Domain:** Banking & Finance  
- **Dataset Type:** Customer Churn  
- **Records:** Bank customers  
- **Target Variable:** `Exited` (indicates whether a customer has churned)

Since no dataset was provided, a publicly available banking customer churn dataset was selected to demonstrate industry-relevant data preprocessing techniques.

---

## 🧾 Features Included
The dataset contains demographic, financial, and behavioral attributes such as:
- Credit Score  
- Age  
- Tenure  
- Account Balance  
- Number of Products  
- Credit Card Ownership  
- Activity Status  
- Estimated Salary  
- Customer Churn Status  

A detailed **data dictionary** is included in the repository.

---

## 🔍 Step 1: Data Access & Familiarization
- Loaded the dataset using Python (Pandas)
- Reviewed dataset structure, dimensions, and data types
- Examined sample records and summary statistics
- Created a data dictionary to understand feature meaning and business relevance

---

## ⚠️ Step 2: Data Quality Assessment
The dataset was assessed for common data quality issues, including:
- Missing values  
- Duplicate records  
- Incorrect data types  
- Inconsistent categorical values  
- Outliers in numerical features  
- Class imbalance in the churn variable  

---

## 🧹 Step 3: Data Cleaning & Transformation
The following preprocessing steps were performed:
- Removed duplicate records  
- Handled missing values using median (numerical) and mode (categorical)  
- Corrected data types for binary and numerical fields  
- Standardized categorical values  
- Addressed outliers using IQR-based capping  

### Feature Engineering:
- Age Groups  
- Tenure Groups  
- Balance-to-Salary Ratio  

The final dataset is clean and suitable for further analysis or modeling.

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📁 Repository Structure
Banking-Customer-Churn-Data-Wrangling
│
├── data/
│ └── bank_churn_dataset.csv
├── notebook/
│ └── data_cleaning.ipynb
├── data_dictionary.xlsx
├── cleaned_bank_churn.csv
└── README.md

---

## ✅ Outcome
- Delivered a cleaned and transformed banking customer churn dataset  
- Demonstrated a structured data wrangling and preprocessing workflow  
- Prepared the dataset for downstream analytics or predictive modeling  

---

## 📈 Key Learnings
- Practical handling of financial data quality issues  
- Importance of feature engineering in customer analytics  
- Application of industry-standard data preprocessing techniques  

---

## 👤 Author
**Pre-final year Computer Science student**  
Focused on data analytics and software development
