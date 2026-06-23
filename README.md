# DevelopersHub Corporation – Data Science & Analytics Internship

**Intern:** Usama Zulfiqar

**Institution:** University of Lahore – Computer Science  
**Due Date:** 26th June 2026  
**Tasks Completed:** All 5 / 5  

---

## 📁 Repository Structure

```
DevelopersHub_Internship/
│
├── Task_1_Iris_EDA/
│   ├── iris.csv
│   └── Task_1_Iris_EDA.ipynb
│
├── Task_2_Credit_Risk_Prediction/
│   ├── loan_prediction.csv
│   └── Task_2_Credit_Risk_Prediction.ipynb
│
├── Task_3_Customer_Churn_Prediction/
│   ├── churn_modelling.csv
│   └── Task_3_Customer_Churn_Prediction.ipynb
│
├── Task_4_Insurance_Claim_Prediction/
│   ├── medical_insurance.csv
│   └── Task_4_Insurance_Claim_Prediction.ipynb
│
├── Task_5_Personal_Loan_Acceptance/
│   ├── bank_marketing.csv
│   └── Task_5_Personal_Loan_Acceptance.ipynb
│
└── README.md
```

---

## Task Summaries

### ✅ Task 1: Exploring and Visualizing the Iris Dataset
**Objective:** Understand how to read, summarize, and visualize a dataset.  
**Dataset:** Iris Dataset (150 rows, 5 columns)  
**Approach:** Loaded the dataset using pandas, explored structure with `.shape`, `.columns`, `.head()`. Created scatter plots, histograms, box plots, a pair plot, and correlation heatmap using matplotlib and seaborn.  
**Key Result:** Petal length and width are the best features for distinguishing iris species. Setosa is completely separable; Versicolor and Virginica show slight overlap.

---

### ✅ Task 2: Credit Risk Prediction
**Objective:** Predict whether a loan applicant is likely to default.  
**Dataset:** Loan Prediction Dataset (614 rows, 13 columns)  
**Approach:** Handled missing values using mode/median imputation. Performed EDA on key features (loan amount, income, credit history). Trained Logistic Regression and Decision Tree classifiers. Evaluated with accuracy and confusion matrix.  
**Key Result:** Credit history is the strongest predictor. Both models achieve strong accuracy on the test set.

---

### ✅ Task 3: Customer Churn Prediction (Bank Customers)
**Objective:** Identify customers likely to leave the bank.  
**Dataset:** Churn Modelling Dataset (10,000 rows, 14 columns)  
**Approach:** Cleaned data and dropped irrelevant columns. Encoded Gender (Label Encoding) and Geography (One-Hot Encoding). Trained Logistic Regression and Random Forest classifiers. Analyzed feature importance to identify churn drivers.  
**Key Result:** Age, IsActiveMember, and Balance are the top churn predictors. Germany has the highest churn rate by geography.

---

### ✅ Task 4: Predicting Insurance Claim Amounts
**Objective:** Estimate medical insurance claim amounts from personal data.  
**Dataset:** Medical Cost Personal Dataset (1,338 rows, 7 columns)  
**Approach:** Trained Linear Regression and Random Forest Regressor. Visualized the impact of BMI, age, and smoking status on charges. Evaluated with MAE and RMSE.  
**Key Result:** Smoking status is the single most impactful feature. Random Forest significantly outperforms Linear Regression due to non-linear interactions.

---

### ✅ Task 5: Personal Loan Acceptance Prediction
**Objective:** Predict which customers are likely to accept a personal loan offer.  
**Dataset:** Bank Marketing Dataset (5,000 rows, 17 columns)  
**Approach:** Explored age, job, marital status, and education distributions. Encoded all categorical features. Trained Logistic Regression and Decision Tree classifier. Extracted business insights on customer segments most likely to accept.  
**Key Result:** Call duration and previous campaign outcome are the strongest predictors. Tertiary-educated, middle-aged, single customers have the highest acceptance rates.

---

## 🛠 Technologies Used
- **Python 3**
- **Pandas** – data loading and manipulation
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – machine learning models and evaluation

## 📬 Contact
**Email:** usamazulfiqar173@gmail.com
**GitHub:** https://github.com/UsamaZulfiqar-7
