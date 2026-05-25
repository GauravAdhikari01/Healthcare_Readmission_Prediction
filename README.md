# 🏥 Healthcare Readmission Prediction Analysis

An end-to-end Healthcare Analytics and Machine Learning project focused on predicting **30-day hospital readmissions** for diabetes patients using Python. This project analyzes real-world healthcare data from 130 US hospitals to identify high-risk patients, improve patient outcomes, and reduce healthcare costs. 

---

## 📌 Project Overview

Hospital readmissions are one of the biggest challenges in healthcare systems, leading to increased operational costs and poor patient outcomes. This project builds a predictive analytics pipeline to identify patients at high risk of readmission within 30 days after discharge.

### 🎯 Objective

* Predict 30-day hospital readmissions
* Identify key risk factors affecting readmission
* Perform healthcare-focused exploratory data analysis
* Build machine learning models for prediction
* Generate actionable business and clinical insights

### 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

### 📂 Dataset

**Diabetes 130-US Hospitals (1999–2008)**
Source: UCI Machine Learning Repository

* Total Records: **101,766**
* Features: Demographics, diagnoses, lab tests, medications, hospital utilization, admission details, and outcomes 

---

# 📊 Key Project Workflow

## 1️⃣ Data Acquisition & Understanding

* Imported and explored healthcare datasets
* Performed initial data inspection
* Understood patient demographics and hospital records

## 2️⃣ Data Cleaning & Preprocessing

* Handled missing values
* Removed duplicate and inconsistent records
* Encoded categorical variables
* Feature engineering for predictive modeling

## 3️⃣ Exploratory Data Analysis (EDA)

* Patient age distribution analysis
* Readmission trend analysis
* Correlation analysis
* Diagnosis category insights
* Emergency visits & inpatient utilization analysis
* Healthcare utilization patterns

## 4️⃣ Machine Learning Modeling

Implemented and compared multiple ML models:

* Logistic Regression
* Random Forest
* Decision Tree

### ✅ Best Performing Model

**Random Forest Classifier**

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 75.54% |
| Precision | 19.49% |
| Recall    | 38.09% |
| F1 Score  | 25.79% |
| ROC-AUC   | 0.6529 |



---

# 🔍 Key Insights

## 📈 Readmission Statistics

* Overall 30-day readmission rate: **11.16%**
* Total readmissions identified: **11,357**
* Elderly patients showed significantly higher readmission rates

## ⚠️ Major Risk Factors

* Previous inpatient admissions
* Frequent emergency department visits
* Circulatory and respiratory diagnoses
* Elderly age groups (70+)



---

# 💡 Business Impact Analysis

### Hypothetical Healthcare Cost Analysis

Assumptions:

* Average readmission cost: **$15,000**
* Intervention cost per patient: **$1,000**
* Intervention effectiveness: **70%**

### Estimated Outcomes

| Metric                           | Value  |
| -------------------------------- | ------ |
| Patients requiring intervention  | 4,438  |
| Estimated readmissions prevented | 606    |
| Potential savings                | $9.08M |
| Net benefit                      | $4.64M |



---

# 🏥 Patient Risk Stratification

| Risk Category  | Readmission Rate |
| -------------- | ---------------- |
| Low Risk       | 4.9%             |
| Medium Risk    | 9.8%             |
| High Risk      | 18.1%            |
| Very High Risk | 41.5%            |



---

# 🚀 Future Improvements

* Hyperparameter tuning
* Deep learning implementation
* Real-time prediction dashboard
* EHR integration
* Deployment using Flask/Streamlit
* Advanced imbalance handling (SMOTE)

---

# 📌 Recommendations

* Implement discharge risk scoring
* Prioritize high-risk patient follow-ups
* Enhance transitional care management
* Improve medication reconciliation workflows
* Deploy model into hospital EHR systems



---

# 📚 Learning Outcomes

Through this project, I learned:

* Real-world healthcare data preprocessing
* Handling imbalanced datasets
* Healthcare-focused EDA
* Predictive analytics workflow
* Machine learning model evaluation
* Business impact analysis
* Professional project documentation



---


# ⭐ If You Like This Project

Give this repository a ⭐ and share your feedback!

