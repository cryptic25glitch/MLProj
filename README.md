# Student Exam Performance Predictor

This project aims to predict a student's **Math score** based on various demographic and academic-related features using supervised machine learning algorithms. Multiple models were experimented with, and the best-performing one was selected based on evaluation metrics.

---

## Problem Statement

Given student-level attributes such as:

- Gender  
- Ethnicity  
- Parental level of education  
- Lunch type  
- Test preparation course status  
- Reading score  
- Writing score  

The objective is to accurately predict the **Math score**.

---

## Machine Learning Approach

### Features Used
- **Categorical:**
  - `gender`
  - `ethnicity`
  - `parental level of education`
  - `lunch`
  - `test preparation course`

- **Numerical:**
  - `reading score`
  - `writing score`

### Workflow
1. Data Cleaning and Preprocessing  
2. Encoding of Categorical Features  
3. Feature Scaling  
4. Training multiple machine learning models  
5. Evaluating models using performance metrics  
6. Selecting the best-performing model

### Algorithms Tried
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost  
- CatBoost  
- K-Nearest Neighbors  
 

**Best Model Selected:** Linear Regression (accuracy:0.88)  


---



