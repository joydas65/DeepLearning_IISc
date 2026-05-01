# L03: Neural Network Basics

## 1. Neural network

A neural network is made of layers.
Each layer is made of neurons.
Each neuron computes a weighted sum plus bias and then applies an activation function.

## 2. Neuron

z = weighted sum of inputs + bias  
a = activation(z)

Example activation:
- Linear
- ReLU
- Sigmoid
- Softmax

## 3. Layers

Input layer:
- Passes input data

Hidden layers:
- Learn representations

Output layer:
- Regression: numerical value
- Classification: class probabilities
- GenAI: text/image/audio/video tokens or outputs

## 4. Parameters

Parameters are learned from data.

Examples:
- Weights
- Biases

## 5. Hyperparameters

Hyperparameters are set before training.

Examples:
- Learning rate
- Batch size
- Number of layers
- Number of neurons
- Vocabulary size
- Embedding dimension

## 6. Loss function

Loss measures prediction error.

Regression:
Mean Squared Error

Classification:
Cross Entropy

## 7. Optimizer

Optimizer updates weights and biases to reduce loss.

Examples:
- Stochastic Gradient Descent
- Adam

## 8. Batch, iteration, epoch

Batch:
Subset of data used for one update.

Iteration:
One parameter update using one batch.

Epoch:
One full pass over the training dataset.

Example:
Dataset = 1000 samples  
Batch size = 200  
Iterations per epoch = 5

## 9. Train/dev/test

Development set:
Used for training and hyperparameter tuning.

Test set:
Unseen data used for final evaluation.

## 10. Overfitting

Overfitting happens when model performs well on training data but poorly on unseen data.

Regularization methods:
- Norm-based penalty
- Dropout
- Batch normalization
- Layer normalization
- Early stopping

## 11. Exam traps
- Parameters are learned; hyperparameters are set before training.
- One epoch may contain multiple iterations.
- Larger model capacity can increase overfitting risk.
- Test set should not be used for hyperparameter tuning.
- Loss function measures error; optimizer reduces loss.
