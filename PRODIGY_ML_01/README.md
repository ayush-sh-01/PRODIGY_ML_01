# House Price Prediction - Task 1 (PRODIGY ML Internship)

This repository contains the implementation of Task 1 for the Prodigy Infotech Machine Learning internship. The task involves predicting house prices using the Kaggle dataset "House Prices - Advanced Regression Techniques".

## Folder Structure

PRODIGY_ML_01/
├── data_description.txt
├── sample_submission.csv
├── test.csv
├── train.csv
├── house_price_prediction.ipynb
└── submission.csv


## Dataset

- train.csv: Training data with features and target SalePrice.
- test.csv: Test data without target column.
- sample_submission.csv: Sample format for submission.
- data_description.txt: Description of dataset features.

## Objective

Predict house prices (SalePrice) for the test dataset using machine learning models.  

## Approach

1. Load train and test datasets.
2. Explore data and handle missing values.
3. Train a Linear Regression model on the training data.
4. Generate predictions on the test data.
5. Export predictions to submission.csv.

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (for Linear Regression)
- Jupyter Notebook / VS Code

## Result

- Predicted house prices for the test dataset are stored in submission.csv.
- Optional: Submitted predictions to Kaggle to evaluate performance.
