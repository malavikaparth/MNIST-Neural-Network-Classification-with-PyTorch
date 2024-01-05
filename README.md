# MNIST-Neural-Network-Classification-with-PyTorch
This repository contains code for training a simple neural network on the MNIST dataset using PyTorch.

Introduction
This project aims to demonstrate the use of PyTorch to train a neural network for classifying handwritten digits from the MNIST dataset. The code utilizes a simple fully connected neural network architecture for this task.

Setup
Requirements
Python 3.x
PyTorch
torchvision
matplotlib

Model Architecture
The neural network architecture consists of:

Input layer: 784 neurons (flattened 28x28 images)
Hidden layer: 500 neurons (ReLU activation)
Output layer: 10 neurons (corresponding to classes 0-9)
Training
The code trains the neural network using the following configurations:

Number of epochs: 2
Batch size: 100
Learning rate: 0.001
Loss function: CrossEntropyLoss
Optimizer: Adam

Evaluation
The trained model is evaluated on the test set of 10,000 images to calculate accuracy.

Results
The accuracy of the network on the test set of 10,000 images is 91.77% on test set .
