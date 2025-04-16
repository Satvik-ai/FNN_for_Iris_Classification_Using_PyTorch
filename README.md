# Iris Classification Using PyTorch

## Overview
This project implements a neural network using PyTorch to classify the Iris dataset into different species. The model is trained and evaluated using standard deep learning techniques.

## Features
- Loads and preprocesses the Iris dataset
- Defines a neural network model using PyTorch
- Implements a training loop for model optimization
- Evaluates the model's performance

## Dataset
The Iris dataset is a well-known dataset in machine learning, containing features of different species of Iris flowers. It includes:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Model
The neural network consists of:
- Input layer (4 neurons for features)
- Hidden layers with activation functions
- Output layer (3 neurons for classification)

## Training
- Uses a loss function like CrossEntropyLoss
- Optimized using Adam optimizer
- Training loop with backpropagation

## Results
- Achieved high accuracy (96.67%) on Iris test data.
