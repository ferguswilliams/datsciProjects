# Group Machine Learning Project: Predicting Financial Fraud
## This project aimed to detect cases of fraud from a customer transactions dataset found on: https://www.kaggle.com/competitions/ieee-fraud-detection/data 
## The project was conducted as follows:
### 1. Data Exploration and Cleaning: There were far too many feature columns to go though individually, so analysis was conducted on groups of features (e.g. ID columns, email columns ..)  in turn. Where possible missing values were appropriately imputed, feature columns with too many missing values were dropped.
### 2. Model Training: An 80/20 training/test split was used to train a Random Forest Regressor that employs 20 estimators.
### 3. Model Evaluation: Accuracy scores and the confusion matrix were generated on the test data. The classification threshold was investigated to reduce False Negatives whilst maintaining satifactory accuracy. New metrics for model performance were generated to weight for False Negative occurences.