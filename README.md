# Basic-Deep-Learning-Exercise
Breast Cancer Classification using Artificial Neural Networks (ANN) with TensorFlow and Keras. The project implements a deep learning model with hyperparameter tuning, dropout regularization, and early stopping to classify tumors as benign or malignant.

# Breast Cancer Classification using Artificial Neural Network (ANN)

This project implements an Artificial Neural Network (ANN) to classify breast tumors as **Benign** or **Malignant** using the Breast Cancer dataset. The objective is to develop a reliable deep learning model for binary classification in healthcare.

## Project Overview

The project follows an end-to-end deep learning workflow, including:

- Data Preprocessing
- Train-Test Split
- Feature Scaling
- ANN Model Development
- Regularization Techniques
- Hyperparameter Tuning
- Model Evaluation

## Model Architecture

The ANN model was developed using TensorFlow and Keras with:

- Input Layer: 30 Features
- Hidden Layer 1: Dense layer with ReLU activation
- Hidden Layer 2: Dense layer with ReLU activation
- Dropout Layer for reducing overfitting
- Output Layer: Sigmoid activation for binary classification

## Advanced Techniques Used

- He Normal Weight Initialization
- L2 Regularization
- Dropout Regularization
- Early Stopping
- Hyperparameter Tuning using Keras Tuner Random Search
- Adam Optimizer
- Binary Cross-Entropy Loss Function

## Technologies Used

- Python
- TensorFlow
- Keras
- Keras Tuner
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Workflow

1. Load and preprocess the Breast Cancer dataset.
2. Split the dataset into training and testing sets.
3. Standardize the input features.
4. Build an ANN using TensorFlow/Keras.
5. Apply regularization techniques to reduce overfitting.
6. Optimize hyperparameters using Random Search.
7. Train the model using Early Stopping.
8. Evaluate the model using classification accuracy and loss curves.

## Key Features

- Binary classification of breast cancer diagnosis.
- Deep learning model with optimized architecture.
- Overfitting prevention using Dropout and L2 Regularization.
- Hyperparameter tuning for improved model performance.
- Easy to reproduce and extend for other medical classification tasks.

## Goal

The goal of this project is to demonstrate how Artificial Neural Networks can be applied to healthcare datasets for accurate breast cancer prediction and to explore optimization techniques that improve model generalization and performance.
