# MNIST Digit Recognizer using ANN and CNN

## Project Overview

This project focuses on handwritten digit classification using Deep Learning techniques on the MNIST dataset.

The project was implemented in two stages:

1. Artificial Neural Network (ANN)
2. Convolutional Neural Network (CNN)

The objective is to classify handwritten digits (0–9) from grayscale images of size 28×28 pixels.

---

## Dataset

Dataset: MNIST Digit Recognizer

- Total Samples: 42,000
- Image Size: 28 × 28
- Number of Classes: 10 (Digits 0–9)

Each image is represented by 784 pixel values.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow
- Keras

---

# Phase 1: Artificial Neural Network (ANN)

### Architecture

Input Layer (784 neurons)

↓

Dense Layer (128 neurons, ReLU)

↓

Dense Layer (64 neurons, ReLU)

↓

Output Layer (10 neurons, Softmax)

### Concepts Learned

- Forward Propagation
- Activation Functions
- ReLU
- Softmax
- Loss Functions
- Backpropagation
- Gradient Descent
- Adam Optimizer

### ANN Performance

Accuracy:96.38%

---

# Phase 2: Convolutional Neural Network (CNN)

### Architecture

Conv2D (32 Filters, 3×3)

↓

MaxPooling2D

↓

Conv2D (64 Filters, 3×3)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128 neurons)

↓

Dropout

↓

Dense (10 neurons, Softmax)

### Concepts Learned

- Convolution Layer
- Filters / Kernels
- Feature Maps
- Pooling
- Flatten Layer
- Dropout
- CNN Architecture

### CNN Performance

Accuracy: 98.47%

---

## Model Evaluation

The models were evaluated using:

- Test Accuracy
- Confusion Matrix
- Error Analysis
- Wrong Prediction Visualization

Example Insights:

- Digits with similar shapes were occasionally confused.
- CNN reduced classification errors compared to a basic ANN.

---

## Features

✅ Data Preprocessing

✅ Data Normalization

✅ ANN Implementation

✅ CNN Implementation

✅ Confusion Matrix Visualization

✅ Error Analysis

✅ Model Saving (.h5)

✅ Prediction Visualization

---

## Results

| Model | Accuracy |
|---------|----------|
| ANN | 96.38% |
| CNN | 98.47% |

---

## Future Improvements

- Data Augmentation
- Batch Normalization
- Transfer Learning
- Real-time Digit Recognition using Webcam

---

