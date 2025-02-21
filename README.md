Predicting Credit Card Approvals – Machine Learning Project

Overview:

This project predicts credit card approvals using Logistic Regression, leveraging a dataset with numerical and categorical attributes. The objective is to automate the approval process by building an accurate classification model through data preprocessing, feature engineering, and model optimization.

Key Steps:

1️) Data Preprocessing

Handled missing values by applying mean imputation for numerical data and mode imputation for categorical data.
Dropped irrelevant features to improve model performance.
Encoded categorical variables using one-hot encoding and ensured alignment between train and test datasets.
Normalized numerical features using MinMax scaling for consistent data distribution.

2️) Model Training & Evaluation

Trained a Logistic Regression model to classify credit card approvals.
Performed hyperparameter tuning using GridSearchCV, optimizing:
Tolerance (tol): [0.01, 0.001, 0.0001]
Max iterations (max_iter): [100, 150, 200]
Evaluated model performance using accuracy score and a confusion matrix.

Results:

Best Model: Logistic Regression with optimized hyperparameters.
Accuracy Score: 100%
