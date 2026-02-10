# Loan Approval Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether a loan application will be **approved or rejected** based on applicant personal, financial, and employment details using Machine Learning techniques.

The project follows the **complete end-to-end ML pipeline**, from data preprocessing and exploratory data analysis (EDA) to model training and evaluation.

---

## 🎯 Objective
To build a machine learning model that accurately predicts **loan approval status** based on factors such as:
- Applicant income
- Co-applicant income
- Credit score
- Employment status
- Loan amount
- Loan term
- Property area
- Other demographic attributes

---

## 🗂️ Dataset Description
The dataset contains both **numerical** and **categorical** features related to loan applicants.

### Key Features:
- `Applicant_Income`
- `Coapplicant_Income`
- `Age`
- `Dependents`
- `Credit_Score`
- `Employment_Status`
- `Loan_Amount`
- `Loan_Term`
- `Property_Area`
- `Loan_Purpose`

### Target Variable:
- `Loan_Approved` (Yes / No)

---

## ⚙️ Project Workflow

1. **Data Loading**
   - Loaded dataset using Pandas
   - Initial inspection and shape analysis

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling using StandardScaler
   - Splitting data into training and testing sets

3. **Exploratory Data Analysis (EDA)**
   - Distribution plots (histograms)
   - Count plots for categorical variables
   - Box plots for loan approval comparison
   - Correlation heatmap

4. **Model Building**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier

5. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

---

## 🧠 Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Results
The models were evaluated using multiple performance metrics.  
Random Forest and Logistic Regression provided competitive results, demonstrating the effectiveness of feature engineering and preprocessing.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure
