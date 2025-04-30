# Heart-Disease-Prediction-Model

## Overview
This project uses machine learning to predict the presence of heart disease based on various medical attributes. The implementation is done in a Jupyter Notebook using Python and scikit-learn.

## Key Components

### 1. Data Preparation
- **Dataset**: The heart disease dataset contains 303 records with 14 features (13 predictors + 1 target).
- **Features**: Includes age, sex, chest pain type, resting blood pressure, cholesterol levels, etc.
- **Target**: Binary classification (1 = heart disease, 0 = no heart disease).

### 2. Data Exploration
- Checked for missing values (none found)
- Analyzed statistical measures of the data
- Verified class distribution (165 cases with heart disease, 138 without)

### 3. Model Development
- **Algorithm**: Logistic Regression
- **Data Split**: 80% training, 20% testing (stratified to maintain class distribution)
- **Training**: Model trained with increased max_iter=1000 for convergence

### 4. Model Evaluation
- **Training Accuracy**: 85.5%
- **Test Accuracy**: 80.3%

### 5. Predictive System
- Implemented a function to make predictions on new data
- Example predictions shown for both positive and negative cases

## Technical Implementation
- Libraries: NumPy, pandas, scikit-learn
- Key steps:
  - Data loading and inspection
  - Train-test split
  - Model training and evaluation
  - Prediction system

## Conclusion
The logistic regression model achieved reasonable accuracy in predicting heart disease presence. 
