# Telco Customer Churn Prediction

This project analyzes a Telco Customer Churn dataset and builds a machine learning model to predict churn. The notebook walks through data preprocessing, feature selection, dimensionality reduction using PCA, and training a classifier to evaluate performance.

## Dataset

The dataset used is: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

- Contains customer demographics, account information, and churn labels.
- Target variable: `Churn`

## ML Overview

1. **Data Preprocessing**
   - Dropping unnecessary columns (e.g., `customerID`)
   - Handling categorical variables with label encoding and one-hot encoding

2. **Feature Selection**
   - SelectKBest
   - ExtraTreesClassifier for feature importance

3. **Dimensionality Reduction**
   - PCA for reducing feature space

4. **Model Training**
   - Support Vector Machine (SVM)

5. **Model Evaluation**
   - Confusion matrix


