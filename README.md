# Handwritten Digit Recognition with CNN

This project demonstrates a simple Convolutional Neural Network (CNN) for recognizing handwritten digits using the MNIST dataset.

## Overview

The notebook contains a complete pipeline for:
- Loading and preprocessing the MNIST dataset
- Building and training a CNN model
- Evaluating model performance
- Saving and loading the trained model
- Making predictions and visualizing results

## Model Architecture

The CNN model consists of:
- Two convolutional layers with ReLU activation
- Two max-pooling layers
- One fully connected layer with 64 units
- Output layer with 10 units (one for each digit) using softmax activation

## Performance

After 5 epochs of training:
- Training accuracy: ~99.4%
- Test accuracy: ~98.9%

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

## Usage

1. Clone the repository
2. Install the required packages
3. Run the Jupyter notebook `HandWrittenDigit-CNN.ipynb`

The notebook will:
- Train the CNN model
- Save the model as `mnist_cnn.h5`
- Show sample predictions with visualization

## License

This project is open source and available to everyone. Feel free to use and modify it for your needs.

## Acknowledgments

- MNIST dataset
- TensorFlow/Keras documentation
