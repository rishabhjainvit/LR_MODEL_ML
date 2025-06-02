# Logistic Regression Classifier

## Description

I built a simple Logistic Regression (LR) model in Python to demonstrate how to train, evaluate, and use a binary classification algorithm. This repository contains all the code needed to:

- Load and preprocess a dataset
- Train a logistic regression model using scikit-learn
- Evaluate the model’s performance
- Save and load the trained model for inference

I chose logistic regression because it’s a lightweight, interpretable classifier that works well on linearly separable data. You can adapt this code to your own CSV dataset by updating the data-loading section.

## Features

- **Data Loading & Preprocessing**  
  I show how to read a CSV file using pandas, handle missing values, and split data into training and test sets.

- **Model Training**  
  The code uses `sklearn.linear_model.LogisticRegression` to fit a model on the training set.

- **Evaluation**  
  I calculate accuracy, precision, recall, and display a confusion matrix to demonstrate how well the model performs.

- **Model Persistence**  
  I use `joblib` to save the trained model to disk and load it later for inference.

## Prerequisites

- Python 3.7+  
- pip (package installer for Python)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/logistic-regression-classifier.git
   cd logistic-regression-classifier
