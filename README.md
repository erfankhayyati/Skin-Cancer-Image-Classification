# Skin-Cancer-Image-Classification
Research Proposal Project for ANN course

This project focuses on the classification of skin cancer images using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN). The dataset used for this project is the ISIC Dataset, organized into binary classification categories: benign and malignant.

Project Overview

The aim of this project is to:

Build and compare ANN and CNN models for skin cancer image classification.

Evaluate the performance of CNN models using transfer learning techniques against custom ANN architectures.

Generate a 6-page IEEE-style report detailing the findings and implementation.

Dataset Details

The ISIC dataset is structured as follows:

Train Folder:

Contains subfolders: benign/ and malignant/.

Test Folder:

Contains subfolders: benign/ and malignant/.

Each subfolder contains labeled images of skin lesions for training and testing.

Environment and Tools

Programming Language: Python

Framework: TensorFlow (preferred)

Hardware: Laptop with GPU RTX 3060

IDE: Jupyter Notebook (or equivalent)

Preprocessing Steps

Image Loading and Labeling:

Images are loaded from their respective folders.

Labels are derived from the folder names (benign or malignant).


Resizing and Normalization:

Images are resized to a consistent dimension (e.g., 224x224).

Pixel values are normalized to the range [0, 1].

Splitting:

The dataset is split into training, validation, and test sets (if not already divided).

Model Details

1. Artificial Neural Network (ANN)

A custom ANN model is implemented for binary classification.

Input: Flattened image pixels.

Hidden Layers: Fully connected layers with ReLU activation.

Output: Sigmoid activation for binary classification.

2. Convolutional Neural Network (CNN)

CNN architecture leverages transfer learning (e.g., ResNet, VGG, or Inception).

Layers:

Pre-trained feature extractor.

Fully connected layers for classification.

Output layer with Sigmoid activation.

Performance Metrics

Accuracy

Precision

Recall

F1 Score

