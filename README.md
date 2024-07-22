# micrograd
## Karpathy's micrograd - 20th Summer Project by Han 2024 

This is my note on learning Micrograd and implementing it from scratch using basic library. 

Micrograd library originally created by Karpathy, et al.

Written in Indonesian+English

## Mistakes made during learning
1. Forgot to add radd => reverse add to the class so when summing up the forward pass it gets error
2. Forgot to **reset gradients** before each backward pass since the backward pass accumulates +=, it will accumulate all passes not changing each gradient for each pass/iteration

## What I learned
- Neural Networks: Mathematical expressions that take data, weights, and parameters as input.
- Forward Pass: The process where input data is passed through the network to generate predictions.
- Loss Function: Measures the accuracy of predictions. Lower loss indicates better performance.
- Backpropagation: Used to calculate the gradient of the loss function to adjust parameters.
- Gradient Descent: An iterative process to minimize the loss by following the gradient.
- Training: Involves using different loss functions and updates, like cross-entropy loss for predicting sequences.
- **Micrograd**: Micrograd is an automatic gradient engine that implements backpropagation to evaluate gradients of a loss function with respect to neural network weights, enabling weight tuning to minimize loss.
- Basic Object Oriented Programming in Python
- Special methods in Python
- Derivative of math expression
- Chain Rule

Noted and Created by Han Summer 2024

Part of The 20th Summer Project
