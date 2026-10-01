# Image Classification with Deep Learning

## Project Overview

This project implements an image classification model using a
Convolutional Neural Network (CNN).

The model is trained on the CIFAR-10 dataset, which contains images
from 10 different classes:

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

The project demonstrates the complete deep learning workflow,
including data preprocessing, CNN construction, model training,
evaluation, performance visualization, and predictions on test images.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Dataset

The CIFAR-10 dataset is used for training and testing the model.

It contains 60,000 color images divided into 10 classes:

- 50,000 training images
- 10,000 testing images
- Image size: 32 × 32 pixels

## Model Architecture

The CNN includes:

- Convolutional layers for feature extraction
- Max-pooling layers for dimensionality reduction
- Flatten layer
- Dense neural network layers
- Softmax output layer for classification

## Training

The model is trained using:

- Adam optimizer
- Sparse categorical cross-entropy loss
- Accuracy as the evaluation metric

Training and validation accuracy and loss are visualized to monitor
the learning process.

## Results

The trained CNN achieved approximately **69% test accuracy**.

The project also visualizes predictions on test images and compares
the predicted class with the actual class.

## Example Applications

Image classification can be used in many areas, including:

- Medical imaging
- Autonomous vehicles
- Security systems
- Object recognition
- Industrial inspection

## Future Improvements

Possible improvements include:

- Training for more epochs
- Data augmentation
- Adding dropout
- Using a deeper CNN architecture
- Applying transfer learning with pretrained models
