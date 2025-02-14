# Homeassignment1
Student Information

Name: Ashritha Reddy
Course: Neural Networks and Deep Learning
University: University of Central Missouri
Submission Date: 2/13/2025

Project Overview

This assignment covers fundamental concepts in deep learning, including tensor manipulations, loss functions, optimizer comparisons, and logging using TensorBoard.
The tasks implemented are:

Tensor Manipulations & Reshaping

Creating and reshaping tensors

Performing broadcasting operations

Understanding tensor rank and shape

Loss Functions & Hyperparameter Tuning

Computing Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE)

Observing the impact of different predictions on loss values

Visualizing loss values using Matplotlib

Training a Model with Different Optimizers

Training an MNIST model using Adam and SGD optimizers

Comparing training and validation accuracy trends

Plotting optimizer performance

Training a Neural Network and Logging to TensorBoard

Training an MNIST model and enabling TensorBoard logging

Analyzing loss and accuracy trends using TensorBoard

Setup Instructions

Prerequisites

Ensure you have Python and TensorFlow installed. If not, install them using:

pip install tensorflow numpy matplotlib

Running the Code

Clone the repository from GitHub:

git clone [Your_GitHub_Repo_Link]
cd [Repo_Name]

Run the Python script:

python assignment.py

To visualize TensorBoard logs, run:

tensorboard --logdir logs/fit

Explanation of Code

Task 1: Tensor Manipulations

Generates a random tensor and manipulates its shape and dimensions.

Demonstrates broadcasting and addition with a smaller tensor.

Task 2: Loss Functions

Computes loss values for different predictions.

Plots a bar chart comparing MSE and Cross-Entropy Loss.

Task 3: Optimizer Comparison

Trains the MNIST dataset using Adam and SGD optimizers.

Compares validation accuracy and plots results.

Task 4: TensorBoard Logging

Trains a neural network while logging accuracy and loss values.

Provides steps to visualize training progress using TensorBoard.

Conclusion

This assignment provides hands-on experience with tensor operations, loss functions, optimizer comparison, and model training visualization using TensorBoard.
