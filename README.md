# Task 03 – Features and Hyperparameter Tuning

## Project Overview
This project improves a Student Placement Prediction model using feature engineering, cross-validation and hyperparameter tuning.

## Features Engineered
1. Academic Average – Average of SSC, HSC and Degree percentages.
2. Skill Average – Average of E-test and MBA percentages.
3. Academic Improvement – Difference between Degree and SSC percentages.

## Machine Learning Model
- Logistic Regression
- GridSearchCV
- 5-Fold Stratified Cross-Validation

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

## Before and After Comparison
The notebook compares the original Logistic Regression model with the feature-engineered and tuned model using cross-validation.

Actual evaluation results are available in the notebook.

## How to Run

1. Clone this repository.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Open `Task_03_Features_Tuning.ipynb` in VS Code or Jupyter Notebook.
4. Run all cells.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook.
