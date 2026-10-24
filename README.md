# Convolutional Neural Networks (CNN) - From Scratch & TensorFlow/Keras

This project covers both the theoretical foundations of **Convolutional Neural Networks (CNNs)** implemented completely from scratch using **NumPy**, and practical model building using **TensorFlow/Keras**.

##  Project Overview

The project is divided into two main parts:

### Part 1: NumPy Implementation (From Scratch)
* **Zero Padding (`zero_pad`)**: Pads image borders with zeros to preserve spatial dimensions.
* **Single Step Convolution (`conv_single_step`)**: Applies a filter on a single slice to compute an output neuron.
* **Convolution Forward & Backward (`conv_forward`, `conv_backward`)**: Implements full forward propagation and backpropagation (computing gradients for weights, biases, and previous activations).
* **Pooling Forward & Backward (`pool_forward`, `pool_backward`)**: Implements max and average pooling operations alongside helper utilities like window mask creation and value distribution.

### Part 2: TensorFlow & Keras Implementation
* **Binary Classification Model (`happyModel`)**: Builds a sequential model (`ZEROPAD2D -> CONV2D -> BATCHNORM -> RELU -> MAXPOOL -> FLATTEN -> DENSE`) using `tf.keras.layers`.
* **Convolutional Multi-class Model (`convolutional_model`)**: Builds a functional API model (`CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> DENSE`) for multi-class classification with softmax activation.

---

## 🛠️ Tech Stack
* **Python**
* **NumPy** (For underlying tensor and matrix operations)
* **TensorFlow / Keras** (For high-level deep learning model architectures)

---
