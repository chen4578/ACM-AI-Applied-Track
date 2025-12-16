# Neural Networks with MNIST

## Overview

This project seeks to classify handwritten digits with neural networks and PyTorch using the MNIST dataset.

## Dataset

The MNIST dataset contains 28x28 grayscale images of handwritten digits. There are 60,000 training images and 10,000 test images. Each image has an associated label.

## Implementation

The model used to classify the data is a fully connected neural network with three hidden layers. The neural network utilizes a standard architecture of a forward algorithm with the ReLU activation function and the cross-entropy loss as the loss function, followed by backpropagation. Gradient descent is performed using the Adam optimizer. The prediction corresponds to the index of the largest element of the output array.

## Results

The following figures compare the confusion matrices before and after training. The rows correspond to the true class, while the columns correspond to the predicted class. Greater values along the diagonal represent better classification ability.

<p float="left">
  <img src="https://drive.google.com/uc?export=view&id=1LIhxea8xk47yEywDJEwmvOHRHuiNx_zS" width="45%" />
  <img src="https://drive.google.com/uc?export=view&id=1eb6ifwishqYDCU7DZU8NbO-GGRVluPfR" width="45%" />
</p>

The accuracy is approximately 91.6%.
