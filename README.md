##  Project Overview

This project implements an Image Classification system using a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 different categories.
The model is built using TensorFlow & Keras and demonstrates the fundamentals of Deep Learning.

## Objectives
Understand the basics of Convolutional Neural Networks

Perform image preprocessing and normalization

Build and train a CNN model

Evaluate model performance

Visualize accuracy and loss using graphs

## Technologies Used
Python

TensorFlow / Keras

NumPy

Matplotlib

## Dataset
Dataset Name: CIFAR-10

Total Images: 60,000

Image Size: 32 × 32

Classes (10):

Airplane

Automobile

Bird
Cat

Deer

Dog

Frog

Horse

Ship

Truck

* The dataset is loaded using TensorFlow Keras built-in dataset loader.

## Methodology / Workflow
Load CIFAR-10 dataset

Normalize image pixel values

One-hot encode class labels

Build CNN architecture

Compile the model

Train the model

Evaluate performance on test data

Visualize accuracy and loss graphs

## CNN Architecture
Convolution Layer (32 filters)

Max Pooling

Convolution Layer (64 filters)

Max Pooling

Flatten Layer

Dense Layer (128 units)

Dropout (0.5)

Output Layer (Softmax – 10 classes)

## Results
Achieved good classification accuracy on CIFAR-10

Training and validation accuracy improved over epochs

Loss decreased steadily, indicating proper learning

## Visualizations Included
raining vs Validation Accuracy graph

Training vs Validation Loss graph

Sample image predictions

## Analysis

The CNN model effectively learned spatial features from low-resolution images.

Dropout helped reduce overfitting, and normalization improved convergence speed.

The project highlights the strength of CNNs for image-based tasks.

## Conclusion

This project successfully demonstrates image classification using a CNN.
It strengthened understanding of deep learning concepts such as convolution, pooling, and feature extraction using TensorFlow.

## Author
Sanjeevani Tyagi
B.Tech Computer Science Engineering (2nd Year)
