# Neural Networks with MNIST

## Overview

This project seeks to classify handwritten digits with neural networks and PyTorch using the MNIST dataset.

## Dataset

The MNIST dataset contains 28x28 grayscale images of handwritten digits. There are 60,000 training images and 10,000 test images. Each image have their associated labels.

## Implementation

The model used to classify the data is a fully connected neural network with three hidden layers. The neural network utilizes a standard architecture of a forward algorithm with the ReLU activation function and the cross-enttopy loss as the loss function, followed by backpropagation. Gradient descent is performed using Adam optimizer. The prediction corresponds to the index of the largest element of the output array.

## Results

The following figures compare the confusion matricies before and after training. The rows correspond to the true class, while the colums correspond to the columns are the predicted class. Greater values along the diagonal represent better classification ability.

<p float="left">
  <img src="image1.png" width="45%" />
  <img src="image2.png" width="45%" />
</p>
