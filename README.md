# Loan Prediction

This repository contains a machine learning pipeline for loan prediction. The goal of this project is to automate the loan eligibility process based on customer details provided while filling an online application form. 

By analyzing the provided dataset, we aim to identify customer segments that are eligible for a loan amount, enabling targeted marketing efforts towards these customers.

Dataset taken from [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/)

## Project Workflow

- Import the required libraries for data manipulation, visualization, preprocessing, and model training.
- Read the training and test datasets from CSV files.
- Perform data exploration by providing information, description, and a head of the training dataset.
- Preprocess the data by dropping irrelevant columns and handling missing values.
- Visualize the data to analyze the relationships between variables.
- Perform feature engineering by transforming and grouping numerical variables.
- Encode categorical variables using one-hot encoding.
- Split the data into training and testing sets.
- Train a Random Forest Classifier on the training data.
- Calculate and print the feature importances.
- Select the top important features.
- Train a calibrated Random Forest Classifier on the selected features using cross-validation.
- Make predictions on the validation set and calculate accuracy.
- Train the final model on the entire dataset using the selected features and calibrated classifier.
- Make predictions on the test dataset.
- Convert predicted probabilities to binary labels.
- Create a submission file with loan predictions.

## Usage

To use this code, follow these steps:

- Clone this repository.
- Install the required libraries mentioned in the code.
- Place the training and test datasets (in CSV format) in the appropriate directory.
- Run the code in a Python environment.
- The predicted loan approval status will be saved as a CSV file.

## Results

The final model achieves a certain level of accuracy in predicting the loan approval status based on the given dataset. The feature importances provide insights into the variables that contribute most to the prediction.

## Conclusion

This project demonstrates a machine learning pipeline for loan prediction, which can be used to automate the loan eligibility process in real-time. By analyzing customer details, the model can identify eligible loan applicants and enable targeted marketing strategies. The code and methodology can be further improved and customized to suit specific business requirements.
