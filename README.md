# Student Performance Prediction

## Project Overview

This project focuses on predicting student performance based on various factors such as gender, study time, parental education, and test preparation course participation. The goal is to leverage machine learning to understand how these features influence student outcomes, specifically their scores in math, reading, and writing. The project demonstrates a full machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, and deployment.

## Problem Statement

In an educational context, understanding the factors that contribute to student performance can help in developing better strategies for improving academic outcomes. By using machine learning, we aim to predict student test scores based on various personal and academic factors. This prediction could guide interventions aimed at improving academic performance, particularly for students who may need additional support.

## Key Features

- **Data Ingestion**: The project starts with ingesting data from a CSV file containing information about student demographics, study habits, and scores.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features to prepare the data for modeling.
- **Model Training**: Multiple machine learning algorithms, such as Linear Regression, Random Forest, and Gradient Boosting, are trained to predict student scores.
- **Evaluation**: The performance of each model is evaluated using metrics like Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R² to determine the best model.
- **Deployment**: A Flask-based prediction pipeline allows users to input new data and get real-time predictions on student performance.

## Project Goals

- **Predicting Scores**: Use machine learning to predict student performance (math, reading, and writing scores) based on their personal information and study habits.
- **Exploring Feature Importance**: Understand which features (e.g., parental education level, study time) have the most significant impact on student performance.
- **End-to-End Workflow**: Demonstrate the complete machine learning pipeline, from raw data collection to model deployment in a web application.

## Tools and Technologies Used

- **Programming Language**: Python
- **Data Handling and Analysis**: Pandas, NumPy
- **Machine Learning Libraries**: Scikit-learn for model training and evaluation
- **Web Development**: Flask for building the prediction API
- **Visualization**: Matplotlib, Seaborn for data exploration and result visualization

## Dataset

The dataset used in this project is the **Student Performance Indicator** dataset, which contains 1,000 rows and 8 columns. The features include:
- **Student Demographics**: Gender, ethnicity
- **Study Habits**: Study time, test preparation course
- **Parental Influence**: Parental education level
- **Scores**: Scores in math, reading, and writing

The dataset provides a mix of categorical and numerical data, which is used to train the model and make predictions on unseen data.

## Key Steps in the Project

1. **Data Collection**: The dataset is loaded and initially explored to understand its structure and features.
2. **Data Preprocessing**: Categorical features are one-hot encoded, missing values are imputed, and numerical features are scaled for consistent model training.
3. **Model Training**: A variety of models (Linear Regression, Random Forest, and Gradient Boosting) are trained, and their performance is evaluated using key metrics.
4. **Model Evaluation**: Model performance is compared, and the best-performing model is selected based on evaluation metrics like MAE, RMSE, and R².
5. **Deployment**: The selected model is integrated into a Flask web application to make real-time predictions based on user input.

