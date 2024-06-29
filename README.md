# Multi Layer Perceptron
Building Multi Layer Perceptron from scratch

## Description
This project implements a Multi-Layer Perceptron (MLP) for classifying images as "cat" or "not cat" using neural networks.

## Features
- Trains an MLP on a dataset of cat images for binary classification.
- Uses relu activation for hidden layers and sigmoid activation for the output layer.
- Achieves 80% accuracy on test data after 2250 iterations.


## Methodology
### Model Architecture
The MLP architecture consists of an input layer, two hidden layers (100 units and 200 units respectively), and an output layer for binary classification.

### Training Procedure
- Parameters initialization: Random weights (Xavier initialization) and zero biases.
- Forward propagation: Compute activations using relu for hidden layers and sigmoid for output.
- Cost computation: Cross-entropy loss for binary classification.
- Backward propagation: Compute gradients using chain rule and update parameters using gradient descent.

### Hyperparameters
- Learning Rate: 0.03
- Number of Iterations: 2250
- Activation Function: Relu for hidden layers, sigmoid for output layer.

### Evaluation Metrics
- Accuracy: 80% on test data.
- Loss Curves: Plots showing the decrease of training loss over iterations.

