# MNIST Digit Classification with Neural Network  

## Overview  
This project implements a simple neural network from scratch to classify handwritten digits using the [MNIST dataset](http://yann.lecun.com/exdb/mnist/). The model is built with forward propagation, backpropagation, and gradient descent.  

## Dataset  
The MNIST dataset consists of grayscale images of handwritten digits (0-9):  
- **60,000 training images**  
- **10,000 test images**  
- Each image is **28x28 pixels**, flattened into a **784-dimensional vector**.  

## Model Architecture  
The neural network has:  
- **Input layer**: 784 neurons (one per pixel)  
- **Hidden layers**:  
  - Layer 1: 4 neurons (ReLU activation)  
  - Layer 2: 8 neurons (ReLU activation)  
- **Output layer**: 10 neurons (Softmax activation)  

## Training  
- **Loss function**: Categorical Cross-Entropy  
- **Optimization**: Gradient Descent  
- **Activation Functions**: ReLU (hidden layers) & Softmax (output layer)  
- **Weight Initialization**: Small random values  
- **Training updates**:  
  - Loss printed every **100 epochs**  
  - Accuracy printed every **25 epochs**  

