# CNNs with CIFAR-10

## Overview

This project aims to classify images from the CIFAR-10 dataset with a set of ten available classes using a convolutional neural network.

## Dataset

The dataset has 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. Each class has 6,000 32x32 images.

## Implementation

### Convolutional Layers

The model used to classify the data is a convolutional neural network. The neural network utilizes an architecture of three convolutional layers. Every convolution is followed by a batch normalization layer to normalize the feature maps and dropout to reduce overfitting. There is a max pooling layer after the second convolution to reduce dimensions. 

### Fully Connected Neural Network

Afterwards, the flattened output is passed through a hidden fully connected neural network with the ReLU activation function and cross-entropy loss as the loss function, followed by backpropagation. Gradient descent is performed using the Adam optimizer. The prediction corresponds to the index of the largest element of the output array.

## Results

After 10 epochs, the test accuracy is approximately 70.35%.
