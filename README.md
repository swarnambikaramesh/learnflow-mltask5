# learnflow-mltask5
Netflix Stock Price Prediction
This repository contains code for predicting stock prices using a neural network model based on the Netflix stock dataset obtained from Kaggle.

Dataset
The dataset used in this project is sourced from Kaggle: Netflix Stock Dataset

Dataset Information
File Name: NFLX.csv
Contents: The dataset contains historical stock data related to Netflix, including columns like Date, Open, High, Low, Close, Volume, and Adj Close.
Usage: The 'Low' column from this dataset is used as a target variable for training the predictive model.
Code Overview
The code in this repository performs the following tasks:

Loading and Preprocessing Data:

Loads the dataset 'NFLX.csv' using Pandas and preprocesses it for model training.
Converts non-numeric columns, fills missing values, and creates target classes based on quantiles.
Model Training:

Utilizes TensorFlow's Keras API to build and train a neural network model for stock price prediction.
Compiles the model with appropriate loss and optimizer functions.
Trains the model on the prepared dataset and evaluates its accuracy.
Performance Evaluation and Visualization:

Generates a classification report and a confusion matrix heatmap to visualize model performance.
Displays the confusion matrix heatmap using Matplotlib.
Prediction:

Makes predictions using the trained model on sample inputs from the test set.
