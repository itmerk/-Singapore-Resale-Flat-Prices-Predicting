# Singapore-Resale-Flat-Prices-Predicting
# Resale Flat Price Prediction Web Application

## Overview:
This project aims to develop a user-friendly web application that predicts the resale prices of flats in Singapore. The predictive model utilized in the application is based on historical data of resale flat transactions obtained from the Singapore Housing and Development Board (HDB). By inputting relevant details such as town, flat type, storey range, etc., users can obtain an estimated resale price for a flat.

## Motivation:
The resale flat market in Singapore is highly competitive, making it challenging to accurately estimate the resale value of a flat. This project seeks to address this challenge by leveraging machine learning techniques to provide users with a reliable estimation of resale prices based on various factors such as location, flat type, floor area, and lease duration.

## Scope:
Data Collection and Preprocessing: Gathered a dataset of resale flat transactions from the Singapore Housing and Development Board (HDB) spanning from 1990 to the present day. Preprocessed the data to clean and structure it for machine learning purposes.
Feature Engineering: Extracted relevant features from the dataset including town, flat type, storey range, floor area, flat model, and lease commence date. Additionally, created any additional features that could enhance prediction accuracy.
Model Selection and Training: Selected an appropriate machine learning model for regression such as linear regression, decision trees, or random forests. Trained the model on the historical data, utilizing a portion of the dataset for training purposes.
Model Evaluation: Evaluated the model's predictive performance using regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 Score.
Streamlit Web Application: Developed a user-friendly web application using Streamlit that allows users to input details of a flat (town, flat type, storey range, etc.). Utilized the trained machine learning model to predict the resale price based on user inputs.
Deployment on Render: Deployed the Streamlit application on the Render platform to make it accessible to users over the internet.
Testing and Validation: Thoroughly tested the deployed application to ensure it functions correctly and provides accurate predictions.

## Deliverables:
Well-trained machine learning model for resale price prediction.
User-friendly web application deployed on the Render platform.
Documentation and instructions for using the application.
Project report summarizing the data analysis, model development, and deployment process.

## Data Source:
The dataset of resale flat transactions was obtained from Singapore Housing and Development Board (HDB) - Data.gov.sg.
