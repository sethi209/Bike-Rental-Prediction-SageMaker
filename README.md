# Introduction
This repository contains a project focused on predicting bike rental demand using Amazon SageMaker. The goal is to develop a machine learning model that accurately forecasts the number of bike rentals based on various factors such as weather conditions, time of day, and day of the week.

# Technologies Used
Amazon SageMaker
Python
Jupyter Notebooks
AWS S3
XGBoost

# Project Structure
The project is structured as follows:

# Notebooks:
cloud_training.ipynb: Notebook for training the machine learning model on SageMaker.
cloud_prediction.ipynb: Notebook for making predictions using the deployed model endpoint.

# Data:
bike_train.csv: Training dataset containing historical bike rental data.
bike_validation.csv: Validation dataset for model evaluation.
bike_test.csv: Test dataset for making predictions.

# Instructions
To run the notebooks and deploy the model, follow these steps:
Setup AWS Account: Ensure you have an AWS account with necessary permissions to access SageMaker and S3.

# Notebook Execution:
Open cloud_training.ipynb and follow the instructions to train the model on SageMaker.
Open cloud_prediction.ipynb to make predictions using the deployed model endpoint.

#Deploy Model:
Follow the instructions in the training notebook to deploy the trained model as an endpoint on SageMaker.

# Test Predictions:
Use cloud_prediction.ipynb to test predictions on new data or evaluate model performance.
