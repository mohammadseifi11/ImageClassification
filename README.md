# MNIST CNN Classifier

A simple CNN-based image classifier trained on the MNIST dataset using TensorFlow/Keras.

Goal: Build and evaluate a CNN model to classify handwritten digits with high accuracy.-

## 🔍 Project Overview

 **Dataset**: MNIST (60k train + 10k test grayscale images)
 **Model**: Custom CNN with 2 Conv2D layers, MaxPooling, Dropout, and Dense layers
 **Accuracy**: 99% on test set
 **Framework**: TensorFlow/Keras
 **Platform**: Google Colab



## How to Run

1. Clone the repository
2. Install requirements (`pip install -r requirements.txt`)
3. Open `notebooks/MnistClassification.ipynb` in Jupyter or Colab
4. Run all cells to retrain or evaluate the model

## Folder Structure

mnist-classifier/
├── notebooks/
│ └── MnistClassification.ipynb
├── models/
│ └── mnist-cnn-model.h5
├── README.md
├── requirements.txt
