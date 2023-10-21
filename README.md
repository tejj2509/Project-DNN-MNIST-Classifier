# MNIST Digit Classification with Deep Learning

## Overview

This project leverages deep neural networks to perform handwritten digit classification using the MNIST dataset. The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0-9), making it a foundational dataset for machine learning and computer vision tasks. The primary goal is to build a deep learning model that accurately identifies and classifies these handwritten digits.

## Model Performance

- Training Accuracy: 99.96%
- Test Accuracy: 97.64%

The impressive accuracy achieved by the model underscores its capability to recognize the intricate variations in human handwriting.

## Prerequisites

Before running the code, ensure you have the following prerequisites installed:

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the required libraries using pip:

```shell
pip install tensorflow keras numpy matplotlib
```

## Usage

1. **Data Preprocessing**: The MNIST dataset is preprocessed to normalize pixel values and one-hot encode labels for training.

2. **Model Building**: A deep neural network (DNN) model is constructed, consisting of input layers, hidden layers, and an output layer tailored for digit classification.

3. **Training**: The model is trained on the training dataset, and training progress can be monitored for loss and accuracy.

4. **Evaluation**: The model's performance is assessed using the test dataset.

5. **Applications**: Explore the versatile applications of accurate handwritten digit recognition in various domains.

## Applications

This project showcases the significance of accurate digit recognition in real-world applications, including:

- Optical Character Recognition (OCR)
- Autonomous Vehicles
- Quality Control in Manufacturing
- Inventory Management
- Educational Apps


## Acknowledgments

- The MNIST dataset is courtesy of Yann LeCun and Corinna Cortes.
- The project draws inspiration from the deep learning and computer vision communities.
