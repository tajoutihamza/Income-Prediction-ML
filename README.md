# Income Prediction with Machine Learning
## Overview
This repository contains the code and analysis for predicting whether a person earns more than $50,000 per year using machine learning. The project involves data preprocessing, exploratory data analysis, feature engineering, and implementing various machine learning models to compare which one offers the best accuracy.

## Contents
Income-Prediction-ML.ipynb: Jupyter Notebook containing the main code for the project.
income_evaluation.csv: Dataset used for training and testing the models.

## Clone the repository:

``` bash
git clone https://github.com/tajoutihamza/Income-Prediction-ML.git
```
Open and run the Jupyter Notebook Income-Prediction-ML.ipynb in Google Colab or any compatible environment.

## Explore the analysis, code, and results.

### Dataset
The project uses the income_evaluation.csv dataset, which includes various features such as age, education, marital status, occupation, and more.

### Model Training
The notebook includes the implementation and evaluation of several machine learning models:

* Random Forest
* Naive Bayes
* Support Vector Machine (Linear and RBF kernels)
* Decision Tree
* Logistic Regression
* Gradient Boosting
* k-Nearest Neighbors (k-NN)
* Multilayer Perceptron (MLP) Neural Network
### Model Tuning
A grid search is performed to find the best hyperparameters for the Random Forest model, improving its performance.

## Evaluation
The performance of each model is evaluated using accuracy, classification reports, and confusion matrices. Additionally, the best-performing Random Forest model with tuned hyperparameters is showcased.
## Results
The results folder contains visualizations and metrics illustrating the performance of each model.
