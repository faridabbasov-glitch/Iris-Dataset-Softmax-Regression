# Iris Dataset Softmax Regression

A from-scratch implementation of Softmax Regression (Multinomial Logistic Regression) for multi-class classification on the famous Iris dataset.

# Overview

This project implements a custom Softmax Regression classifier without using scikit-learn's built-in models. The implementation includes:

- Manual gradient descent optimization
- Feature normalization
- Cross-entropy loss function
- Softmax activation for multi-class classification

# Dataset

The project uses the **Iris dataset**, which contains 150 samples of iris flowers with 4 features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

The task is to classify flowers into 3 species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

# Requirements

pandas
numpy
matplotlib

# Results

The model achieves:
- Test Accuracy: 96.7% with optimal hyperparameters (lr=0.1, iterations=1000)
- Perfect accuracy 100% with higher learning rate (lr=0.5)

# Features

- From-scratch implementation (no sklearn models)
- Feature normalization (Z-score standardization)
- Cross-entropy loss with numerical stability
- Training loss visualization
- Train/test split (80/20)
- Hyperparameter tuning examples
