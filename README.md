# Image Classification with Deep Learning 🧠

## Project Overview

This project implements an image classification model using a
Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset.

The model learns visual features from images and classifies them into
10 different categories:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

## Dataset

The project uses the CIFAR-10 dataset, containing 60,000 color images
across 10 classes.

- 50,000 training images
- 10,000 test images
- Image size: 32 × 32 pixels

## CNN Architecture

The neural network uses:

- Convolutional layers for feature extraction
- Max-pooling layers for dimensionality reduction
- Flatten layer
- Dense layers
- Softmax output layer for 10-class classification

## Model Training & Evaluation

The model was trained using the Adam optimizer and sparse categorical
cross-entropy loss.

Training and validation accuracy and loss were monitored throughout
training.

### Final Result

**Test Accuracy: approximately 69%**

The trained model was also tested on unseen images, with predicted
classes compared against their actual labels.

## Future Improvements

The model could be improved by:

- Data augmentation
- Dropout regularization
- Additional convolutional layers
- Training for more epochs
- Transfer learning

## Purpose

This project demonstrates the fundamentals of deep learning for
computer vision, including dataset preprocessing, CNN development,
training, evaluation, and image prediction.
