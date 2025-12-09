# Handwritten Digit Recognition using CNN

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) to classify
handwritten digit images (0–9) using the MNIST dataset.
The model learns visual patterns from images and achieves high classification accuracy.

## 🎯 Problem Statement
To build a deep learning model capable of recognizing handwritten digits from grayscale images.

## 📊 Dataset
- MNIST Handwritten Digits Dataset
- 70,000 grayscale images
- Image size: 28×28 pixels
- 10 output classes (digits 0–9)

> The dataset is loaded directly using TensorFlow/Keras.

## 🛠 Technologies Used
- Python
- TensorFlow
- Keras
- Convolutional Neural Networks (CNN)
- NumPy
- Matplotlib

## ⚙️ Model Architecture
- Convolutional layers for feature extraction
- MaxPooling layers for downsampling
- Fully connected (Dense) layers for classification
- Softmax output layer

## 🚀 Training Details
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Batch Size: 64
- Validation Split: 10%

## ✅ Results
- Validation Accuracy: ~98%
- Test Accuracy: ~98%
- Loss decreased consistently across epochs

## 🧪 Sample Prediction
The trained model correctly predicts handwritten digits from unseen test images.

## 🚀 How to Run
1. Open `handwritten_digit_cnn.ipynb`
2. Run all cells sequentially
3. MNIST dataset will load automatically
4. Model training and evaluation results will be displayed

## 👤 Author
Boggala Meghasyam 
AIML Student, RMD College

