# MNIST
This project implements and trains two neural network models (MLP and LeNet) for handwritten digit classification using the MNIST dataset.

# MNIST Handwritten Digit Classification

This project demonstrates how to classify handwritten digits from the MNIST dataset using PyTorch.

## What it does

The code trains two different neural network models to recognize handwritten digits (0-9):

1. **Multilayer Perceptron (MLP):** A basic neural network with fully connected layers.
2. **LeNet:** A convolutional neural network (CNN) designed for image recognition.

## How it works

1. **Data Loading:** It downloads the MNIST dataset, which contains images of handwritten digits and their corresponding labels.
2. **Model Creation:** It defines the architecture of the MLP and LeNet models using PyTorch layers.
3. **Training:** It trains the models using the training data to learn the patterns of handwritten digits.
4. **Testing:** It evaluates the models on the test data to measure their accuracy.

## How to use

1. Make sure you have PyTorch installed (`pip install torch torchvision torchaudio`).
2. Run the code in a Jupyter Notebook or Google Colab environment.
3. The code will download the MNIST dataset and train the models.
4. You can view the training progress and final accuracy of the models.

## Requirements

* Python 3.x
* PyTorch
* Torchvision
* Torchaudio

## Results

The models achieve high accuracy on the MNIST dataset, demonstrating the effectiveness of neural networks for handwritten digit classification.

## Notes

* The code is written in Python using PyTorch.
* The MNIST dataset is automatically downloaded if it's not already present.
* The models can be further improved by adjusting the hyperparameters or using different architectures.
