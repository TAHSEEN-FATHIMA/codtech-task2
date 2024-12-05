# codtech-task2
# Regression Model Comparison

# Overview

This project focuses on comparing three types of regression models: Linear Regression, Logistic Regression, and Multiple Regression. The goal is to demonstrate how each model is applied to different types of datasets, with a particular emphasis on evaluating performance using various metrics. The project explores real-world datasets like the Diabetes dataset and utilizes Python's scikit-learn library for model implementation and evaluation.

The project is structured as follows:

Linear Regression: Predicting a continuous target variable (diabetes progression) based on a single feature.

Logistic Regression: Classifying the presence or absence of diabetes based on multiple features.

Multiple Regression: Predicting the outcome using multiple features, showing the power of multiple independent variables.


# Objectives

The main objectives of this project are:

->To compare different types of regression models and assess their performance.

->To understand the application of regression models for both classification and regression tasks.

->To evaluate model performance using various metrics, including mean squared error, accuracy, and confusion matrices.

->To implement model training, prediction, and visualization using Python libraries.

# Key Activities

Data Preprocessing:

Load and clean the datasets.

Handle missing values and perform feature scaling.

Split the data into training and testing sets.

Model Implementation:

Linear Regression: Implemented to predict diabetes progression using a single feature (BMI).

Logistic Regression: Applied to classify whether a patient has diabetes (binary classification task).

Multiple Regression: Utilized multiple features like Insulin and Glucose to predict diabetes outcomes.

Model Evaluation:

For Linear Regression: Evaluating using mean squared error (MSE) and R-squared.

For Logistic Regression: Evaluation using accuracy and confusion matrix.

For Multiple Regression: Predictions made for new data points to showcase the model's capabilities.

Visualization:

Visualizing Linear Regression results (scatter plot and regression line).

Displaying the confusion matrix for Logistic Regression using a heatmap.

Performance Comparison:

Compare models based on accuracy for Logistic Regression and mean squared error (MSE) for Linear Regression.

Show the impact of using multiple features in regression models.

# Technologies Used

Python: Main programming language.

scikit-learn: Machine learning library for implementing regression models, splitting data, and evaluating performance.

Pandas: Data manipulation and preprocessing.

NumPy: Numerical operations.

Matplotlib: Visualization library to plot regression lines and confusion matrices.

Seaborn: For advanced visualization, particularly for plotting the confusion matrix.

# Files and Structure

linear_regression.py: Implementation and evaluation of Linear Regression for diabetes prediction.

logistic_regression.py: Implementation of Logistic Regression for diabetes classification, with confusion matrix visualization.

multiple_regression.py: Multiple Regression model using multiple features for diabetes outcome prediction.

diabetes.csv: Dataset used for Logistic and Multiple Regression models.

diabetes_X_y.npz: Preprocessed dataset used for Linear Regression.

Linear Regression:

Coefficients, Mean Squared Error, R-squared values printed.
Scatter plot with regression line.

Logistic Regression:

Model accuracy and confusion matrix printed.
Heatmap of confusion matrix shown.

Multiple Regression:

Predicted outcomes based on new input values printed



