# 🏦 Loan Prediction Project

This is a machine learning project to predict whether a loan application will be **approved (1)** or **not approved (0)** based on applicant data.

---

## 📌 Problem Statement

Banks receive many loan applications, but not all applicants are eligible. The goal is to **predict loan approval** using historical data and machine learning models.

---

## 📊 Dataset

The dataset used is from **Kaggle** and contains information such as:

- Gender
- Marital Status
- Education
- Employment
- Applicant Income
- Loan Amount
- Credit History
- Loan Status (Target)

---

## 🛠️ Project Steps

1. **Data Cleaning**
   - Handled missing values
   - Encoded categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends and relationships
   - Checked class imbalance

3. **Model Training**
   - Logistic Regression (with class weights)
   - Decision Tree Classifier (with class weights)
   - Random Forest Classifier (with class weights)

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1 Score

---

## 🤖 Model Comparison

| Model               | Accuracy | Recall (Class 1) | Precision (Class 1) | F1 Score (Class 1) |
|---------------------|----------|------------------|---------------------|--------------------|
| Logistic Regression | 0.75     | 0.89             | 0.76                | 0.82               |
| Decision Tree       | 0.75     | 0.85             | 0.78                | 0.81               |
| Random Forest       | 0.79     | 0.97             | 0.76                | 0.86               |

✅ **Best Performing Model:** Random Forest Classifier

---

## 🎯 Key Learnings

- Learned how to handle missing data and imbalanced classes
- Compared different classifiers
- Evaluated models with proper metrics
- Understood the importance of recall in financial applications

---

## 🚫 What I Did Not Do (Yet)

- Did not use **XGBoost** due to time and complexity
- Did not perform **cross-validation**
- Did not build a **frontend/app interface**

These can be added in future versions.

---

## 🔜 Future Work

- Add XGBoost or LightGBM
- Try cross-validation
- Improve feature selection
- Build a simple dashboard or web app

---

## 🙏 Acknowledgements

- Thanks to **Kaggle** for the dataset
- This project was done as part of my learning path to become a **Data Scientist in Banking**

---

## 💬 Contact

Feel free to connect with me on LinkedIn "Jean Daniel Sonou" or email me at jeandanielsonou@gmail.com

