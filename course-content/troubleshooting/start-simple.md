---
description: How to start simple with deep learning models?
---

# Start Simple

{% embed url="https://www.youtube.com/watch?v=xTjPrYUmPhk" caption="Start Simple - Troubleshooting" %}

## Summary

* **Choose a simple architecture**:
  * LeNet/ResNet for images.
  * LSTM for sequences.
  * Fully-connected network with one hidden layer for all other tasks.
* **Use sensible hyper-parameter defaults**:
  * Adam optimizer with a “magic” learning rate value of 3e-4.
  * ReLU activation for fully-connected and convolutional models and TanH activation for LSTM models.
  * He initialization for ReLU and Glorot initialization for TanH.
  * No regularization and data normalization.
* **Normalize data inputs**: subtracting the mean and dividing by the variance.
* **Simplify the problem**:
  * Working with a small training set around 10,000 examples.
  * Using a fixed number of objects, classes, input size, etc.
  * Creating a simpler synthetic training set like in research labs.

