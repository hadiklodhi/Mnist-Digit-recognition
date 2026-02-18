# Mnist-Digit-recognition

This project implements a **Handwritten Digit Recognition Model** using the **MNIST dataset** and an **Artificial Neural Network (ANN)**. The model is trained to accurately classify grayscale images of handwritten digits (0–9) using supervised learning techniques.

## 📌 Project Overview

The goal of this project is to build a deep learning model capable of recognizing handwritten digits. The MNIST dataset contains 70,000 labeled images (60,000 training + 10,000 testing), each of size 28×28 pixels.

This project covers the complete machine learning workflow:

* Data loading
* Data preprocessing
* Model building
* Training
* Evaluation

It serves as a foundational deep learning project for understanding neural networks and image classification.


## 📂 Dataset

* **Dataset:** MNIST
* **Image Size:** 28 × 28 pixels
* **Classes:** 10 (Digits 0–9)
* **Total Samples:** 70,000

Each image is grayscale and flattened before being fed into the neural network.


## 🏗️ Model Architecture

The model is built using an **Artificial Neural Network (ANN)** consisting of:

* Input Layer (784 neurons – flattened 28×28 image)
* One or more Hidden Layers (Fully Connected)
* Output Layer (10 neurons – Softmax activation)

### Activation Functions:

* ReLU (Hidden Layers)
* Softmax (Output Layer)

### Loss Function:

* Categorical Crossentropy

### Optimizer:

* Adam

## ⚙️ Implementation Steps

1. **Data Preprocessing**

   * Normalize pixel values (0–255 → 0–1)
   * Flatten 28×28 images into 784-length vectors
   * One-hot encode target labels

2. **Model Training**

   * Forward propagation
   * Backpropagation
   * Weight updates using optimizer

3. **Model Evaluation**

   * Accuracy on test dataset
   * Loss analysis

## 📊 Results

The model achieves strong classification accuracy on the test dataset, demonstrating the effectiveness of ANN for image recognition tasks.


## 🚀 Technologies Used

* Python
* TensorFlow / Keras 
* Matplotlib (for visualization)


## 🎯 Learning Outcomes

* Understanding Artificial Neural Networks
* Working with image datasets
* Implementing classification models
* Model training and evaluation
* Basics of deep learning workflows


## 📌 Future Improvements

* Add more hidden layers (Deep Neural Network)
* Implement CNN for improved performance
* Add confusion matrix visualization
* Hyperparameter tuning


