# Neural Network Exercises: XOR Classification and Loss Function Comparison

## Overview

This project contains two related neural network exercises that demonstrate fundamental concepts in neural networks and binary classification.

### Exercise 1: Single-Layer Perceptron vs Multi-Layer Perceptron

The first exercise demonstrates why a Single-Layer Perceptron fails to solve the XOR classification problem and how a Multi-Layer Perceptron (MLP) with a hidden layer can overcome this limitation.

### Exercise 2: MSE vs Binary Cross Entropy

The second exercise compares Mean Squared Error (MSE) and Binary Cross Entropy (BCE) as loss functions for binary classification. It includes manual calculations and a neural network implementation to compare their training behavior and convergence.

---

# Objectives

## Exercise 1: XOR Classification

- Understand the architecture of a Single-Layer Perceptron.
- Construct the XOR truth table.
- Visualize XOR data points in a 2D coordinate system.
- Prove mathematically that XOR is not linearly separable.
- Understand why a single linear decision boundary cannot classify XOR.
- Understand how a hidden layer enables nonlinear classification.
- Design an MLP architecture capable of solving XOR.
- Implement an XOR classifier using TensorFlow.
- Use sigmoid activation functions.
- Use Binary Cross Entropy as the loss function.
- Plot the training loss.
- Visualize the learned decision boundary.
- Calculate the final prediction accuracy.

## Exercise 2: MSE vs BCE

- Calculate MSE manually for binary classification predictions.
- Calculate BCE manually for binary classification predictions.
- Compare MSE and BCE values.
- Understand why BCE is more suitable for binary classification.
- Understand the gradient behavior of MSE and BCE.
- Train two identical neural networks using different loss functions.
- Compare training loss and accuracy.
- Compare convergence behavior.
- Visualize and analyze training loss curves.

---

# Technologies Used

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

---

# Installation

Install the required Python libraries using:

```bash
pip install tensorflow numpy matplotlib
