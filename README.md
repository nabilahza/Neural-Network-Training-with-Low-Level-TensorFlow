### Neural Network Training with Low-Level TensorFlow
This project implements a single-hidden-layer neural network using low-level TensorFlow programming (without Keras). 
The focus is on understanding and and implementing key aspects of neural network training, including the gradient descent algorithm, 
forward pass, and backpropagation.

### Overview
This is a group assignment designed to enhance understanding of neural network fundamentals through hands-on implementation. 
The model learns from the given dataset to estimate weights using gradient descent, and key functions like loss computation, 
activation functions, and the training loop are implemented from scratch.

### Features

**1. Core Functions:**

loss_fn: Computes the loss function.
sigmoid: Implements the Sigmoid activation function.
relu: Implements the ReLU activation function.
forward: Conducts the forward pass for label prediction.
train: Performs forward pass, computes gradients, and updates weights and biases.
fit: Implements the training loop for the neural network.

**2. Model Specifications:**

Neural network with a single hidden layer using ReLU activation.
Customizable number of units in the hidden layer.

**3. Dataset Handling:**

Dataset is split into training (70%), validation (10%), and test (20%) sets.
Training set: Used to estimate model weights.
Validation set: Used to validate the model during training.
Test set: Used to evaluate the final model performance.

**4. Visualization and Evaluation:**

Training and validation loss are displayed for each epoch.
Training and validation loss graphs are plotted post-training.
Confusion matrix and classification report are generated for test set evaluation.
