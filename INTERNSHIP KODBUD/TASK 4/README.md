# Salary Prediction Model (Linear Regression)

##  Overview

This project builds a machine learning model to predict salary based on factors such as:
- Years of experience
- Job role
- Education level
- Location (optional)

The objective is to understand regression modeling, feature handling, and model evaluation using real-world structured data.

---

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

##  Dataset

Dataset Source: Kaggle Salary Dataset / Custom Dataset

Features Used:
- Years of Experience
- Education Level
- Job Title
- Company Size (optional)
- Location (optional)

Target Variable:
- Salary

---

##  Implementation Steps

### 1️ Data Loading
- Imported dataset using Pandas.
- Inspected data types and null values.

### 2️ Data Cleaning
- Handled missing values.
- Converted categorical variables using One-Hot Encoding.
- Ensured numeric columns were properly formatted.

### 3️ Feature Selection
- Selected relevant independent variables.
- Defined Salary as the dependent variable.

### 4️ Train-Test Split
- Split dataset into 80% training and 20% testing data.

### 5️ Model Training
- Applied Linear Regression model from Scikit-learn.
- Trained model on training dataset.

### 6️ Model Evaluation
- Evaluated using:
  - Mean Squared Error (MSE)
  - R² Score

---

##  Model Performance

- Mean Squared Error (MSE): (example) 1,200,000
- R² Score: (example) 0.82

Interpretation:
- Lower MSE indicates better prediction accuracy.
- R² close to 1 indicates strong model performance.

---

##  Visualizations

- Scatter plot of Experience vs Salary
- Regression line visualization
- Residual error plot (optional)

---

##  Key Learning Outcomes

- Understanding Linear Regression
- Handling categorical variables
- Evaluating regression models
- Interpreting R² and MSE

---

##  Future Improvements

- Apply Ridge or Lasso Regression
- Feature scaling optimization
- Hyperparameter tuning
- Try Random Forest Regressor
- Deploy as a web app using Flask or Streamlit

---
