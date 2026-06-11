# MNIST Digit Recognizer

## Project Overview

This project classifies handwritten digits (0–9) using an Artificial Neural Network (ANN) implemented with TensorFlow/Keras.

## Dataset

* MNIST Digit Recognizer Dataset
* 42,000 handwritten digit images
* 784 pixel features per image (28 × 28)

## Technologies Used

* Python
* Pandas
* NumPy
* TensorFlow / Keras
* Matplotlib
* Scikit-Learn

## Workflow

1. Load dataset
2. Data preprocessing
3. Train-test split
4. Pixel normalization
5. Build ANN model
6. Train using Adam optimizer
7. Evaluate model performance

## Model Architecture

* Dense(128, ReLU)
* Dense(64, ReLU)
* Dense(10, Softmax)

## Accuracy

96.38%

## Concepts Learned

* Artificial Neural Networks
* Forward Propagation
* Backpropagation
* ReLU Activation
* Softmax Activation
* Cross Entropy Loss
* Adam Optimizer
* Model Evaluation
