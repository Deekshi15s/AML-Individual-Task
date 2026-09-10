# House Prices ML Classification

## Project Overview

This project focuses on applying machine learning techniques to a house prices dataset. The project demonstrates how machine learning algorithms can be used to analyze housing-related data and perform prediction based on the available features.

The project follows a complete machine learning workflow, including data loading, data exploration, preprocessing, model training, prediction, and performance evaluation.

## Objective

The main objectives of this project are:

- To analyze the house prices dataset.
- To understand the different features available in the dataset.
- To preprocess the data for machine learning.
- To implement machine learning algorithms.
- To train the models using the available housing data.
- To evaluate and compare the performance of the models.
- To identify the better-performing model.

## Dataset

The dataset contains information related to houses and their corresponding prices.

The housing attributes are used as input features for the machine learning models, while the house price is used as the prediction target.

## Machine Learning Algorithms

The project implements machine learning algorithms for predicting house prices.

### Linear Regression

Linear Regression is a supervised machine learning algorithm used for predicting a continuous numerical value. In this project, it is used to estimate the price of a house based on its available features.

### Decision Tree Regression

Decision Tree Regression predicts house prices by creating a tree-like structure of decisions based on the input features. It can capture nonlinear relationships between housing attributes and prices.

### Naive Bayes

Naive Bayes is primarily a classification algorithm based on probability and Bayes' theorem. If included in the project as a classification experiment, it can be used after converting the target into suitable classes.

## Methodology

The project follows these steps:

1. Load the house prices dataset.
2. Explore and understand the dataset.
3. Check the data types and missing values.
4. Perform data preprocessing.
5. Select input features and target variable.
6. Split the dataset into training and testing data.
7. Train the machine learning models.
8. Generate predictions using the test data.
9. Evaluate model performance.
10. Compare the results of the implemented models.
11. Identify the best-performing model.

## Evaluation

The models are evaluated using suitable performance metrics based on the prediction task.

For regression models, commonly used metrics include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help measure how closely the predicted house prices match the actual prices.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Structure

```text
House_Prices_ML_Classification_Final/
│
├── House_Prices_ML_Classification_Final.ipynb
├── README.md
└── dataset/
    └── House_Prices.csv
