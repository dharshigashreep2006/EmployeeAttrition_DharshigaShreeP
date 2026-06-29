# 📊 Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations because replacing experienced employees increases recruitment costs, training time, and reduces productivity.

This project develops a **Machine Learning classification model** to predict whether an employee is likely to leave the company based on various factors such as job role, monthly income, work-life balance, overtime, business travel, and years of experience.

The objective is to help HR teams identify employees at risk of leaving and take proactive retention measures.

---

## 🎯 Project Objectives

- Analyze employee attrition patterns.
- Clean and preprocess HR data.
- Perform Exploratory Data Analysis (EDA).
- Train and compare multiple Machine Learning models.
- Evaluate model performance using classification metrics.
- Identify the most important factors influencing employee attrition.
- Provide actionable HR recommendations.

---

## 📂 Dataset Information

**Dataset:** IBM HR Analytics Employee Attrition Dataset

| Attribute | Value |
|-----------|-------|
| Total Records | 1470 |
| Features | 35 (Expanded to 44 after encoding) |
| Target Variable | Attrition (Yes / No) |

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📈 Project Workflow

### ✅ Task 1 – Data Loading & Exploration
- Loaded HR dataset
- Explored dataset structure
- Calculated attrition rate
- Identified numerical and categorical features

### ✅ Task 2 – Data Cleaning & Preprocessing
- Checked missing values
- Removed irrelevant columns
- Encoded categorical variables
- Scaled numerical features

### ✅ Task 3 – Exploratory Data Analysis
- Attrition by Department
- Attrition by Job Role
- Monthly Income Analysis
- Work-Life Balance Analysis
- Years at Company Analysis

### ✅ Task 4 – Model Building
Three classification models were trained:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📊 Model Evaluation

The models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 🏆 Best Performing Model

**Logistic Regression**

It achieved the best overall balance between Recall, F1-Score, and ROC-AUC, making it the most suitable model for predicting employee attrition in this project.

---

## 📉 Visualizations Included

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income Box Plot
- Confusion Matrix Heatmap
- Top 10 Feature Importance
- ROC Curve Comparison

---

## 💡 Key Business Insights

- Sales Department experienced the highest employee attrition.
- Sales Representatives and Laboratory Technicians showed higher attrition rates.
- Overtime and frequent business travel increased the likelihood of employee attrition.
- Career growth and work-life balance influenced employee retention more than salary alone.

---

## 📁 Repository Structure

```
EmployeeAttrition_DharshigaShreeP
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── summary.pdf
├── README.md
└── charts/
```

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Open `analysis.ipynb` using Jupyter Notebook or Google Colab.
3. Install the required Python libraries.
4. Run all notebook cells sequentially.

---

## 👩‍💻 Author

**Dharshiga Shree P**

Data Sciene Intern
XYLofy AI

---

## ⭐ Project Outcome

This project demonstrates the complete end-to-end Machine Learning workflow, from data preprocessing and visualization to predictive modeling and business recommendations. The final model provides valuable insights that can assist HR teams in identifying employees at risk of attrition and supporting informed retention strategies.
