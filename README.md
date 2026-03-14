# Loan-Approval-Prediction
End-to-end Machine Learning project that predicts loan approval status using applicant financial and demographic data with data preprocessing, EDA, and model evaluation.
# 🏦 Loan Status Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange)
![Status](https://img.shields.io/badge/Project-Complete-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Financial institutions receive thousands of loan applications every day.
Evaluating whether a loan should be approved or rejected is a critical task.

This project builds a **Machine Learning model that predicts loan approval status** based on applicant information such as income, credit history, education, and property area.

The project demonstrates a **complete end-to-end Data Science workflow** from data preprocessing to model evaluation.

---

## 🎯 Objective

The objective of this project is to:

✔ Analyze loan applicant data
✔ Identify factors influencing loan approval
✔ Build a machine learning model to predict loan status
✔ Evaluate model performance

---

## 📊 Dataset Description

The dataset contains information about loan applicants.

### Features

| Feature           | Description               |
| ----------------- | ------------------------- |
| Gender            | Applicant gender          |
| Married           | Marital status            |
| Education         | Education level           |
| ApplicantIncome   | Applicant income          |
| CoapplicantIncome | Co-applicant income       |
| LoanAmount        | Loan amount requested     |
| Loan_Amount_Term  | Loan repayment period     |
| Credit_History    | Credit history status     |
| Property_Area     | Urban / Semiurban / Rural |

### Target Variable

`Loan_Status`

* **Y → Loan Approved**
* **N → Loan Rejected**

---

## 🔍 Project Workflow

### 1️⃣ Data Collection

The dataset was imported from an Excel file containing loan applicant details.

---

### 2️⃣ Data Cleaning

Performed preprocessing tasks such as:

* Handling missing values
* Data type corrections
* Removing inconsistencies

---

### 3️⃣ Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand the data distribution.

Key visualizations included:

* Loan approval distribution
* Income distribution
* Loan amount analysis
* Credit history impact

---

### 4️⃣ Feature Engineering

Categorical variables were converted into numerical values for machine learning models.

Examples:

* Label Encoding
* Feature transformation

---

### 5️⃣ Model Training

Multiple machine learning algorithms were tested:

* Logistic Regression
* Decision Tree
* Random Forest

---

### 6️⃣ Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix

The best performing model was selected based on predictive performance.

---

## 🛠️ Technologies Used

| Tool             | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming             |
| Pandas           | Data analysis           |
| NumPy            | Numerical computation   |
| Matplotlib       | Data visualization      |
| Seaborn          | Statistical plots       |
| Scikit-learn     | Machine learning        |
| Jupyter Notebook | Development environment |

---

## 📂 Project Structure

```
Loan-Status-Prediction-ML
│
├── data
│   └── loan_data.csv
│
├── notebooks
│   └── Loan_Status_Prediction.ipynb
│
├── requirements.txt
│
└── README.md
```

---

## 📈 Results

The trained machine learning model successfully predicts **loan approval status** using applicant demographic and financial features.

This project demonstrates how machine learning can assist financial institutions in **automating loan approval decisions**.

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Advanced feature engineering
* Model deployment using **Streamlit**
* Building a **loan approval web application**

---

## 👩‍💻 Author

**Himanshi Gupta**

Aspiring Data Scientist
MSc Mathematics with Data Science

---

⭐ If you found this project useful, feel free to **star the repository**!
