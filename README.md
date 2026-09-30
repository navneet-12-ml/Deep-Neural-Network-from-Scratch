# Deep Neural Network from Scratch

A from-scratch implementation of a feed-forward deep neural network using NumPy, trained on the Fashion-MNIST dataset.

The project focuses on understanding the core mathematics and implementation of neural networks, including forward propagation, backpropagation, gradient descent, and numerical gradient checking, followed by experiments with different hyperparameters.

---

## Overview

This project implements a neural network from first principles using NumPy instead of relying on a deep learning framework for the core training process.

The implementation covers:

- Data preprocessing
- Forward propagation
- ReLU activation
- Softmax output
- Categorical cross-entropy loss
- Backpropagation
- Gradient descent
- Numerical gradient checking
- Model prediction
- Confusion matrix
- Hyperparameter experiments

The model is trained and evaluated on the **Fashion-MNIST** dataset.

---

## Network Architecture

The implemented neural network follows:

```text
Input Layer
    │
    │ 784 features
    ▼
Linear Layer
    │
    │ 128 neurons
    ▼
ReLU Activation
    │
    ▼
Linear Layer
    │
    │ 10 output classes
    ▼
Softmax
    │
    ▼
Class Prediction
