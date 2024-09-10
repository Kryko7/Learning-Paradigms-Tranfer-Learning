# Transfer Learning with ResNet18 on MNIST

This repository demonstrates the use of **transfer learning** with a pretrained ResNet18 model to classify the **MNIST** dataset.

## Overview

Transfer learning allows a model trained on a large dataset to be adapted for a different task with a smaller dataset. In this project, we:
- Use **ResNet18** pretrained on ImageNet.
- Modify the final layer to classify 10 classes (digits 0-9).
- Fine-tune the model on the MNIST dataset (grayscale images).
- Visualize the results of predictions on the test data.

## Dataset

**MNIST** consists of 28x28 grayscale images of handwritten digits:
- Training set: 60,000 images.
- Test set: 10,000 images.

## Key Steps

1. **Data Loading**: Load and preprocess the MNIST dataset.
2. **Model Adaptation**: Modify ResNet18 to handle grayscale images and output 10 classes.
3. **Fine-tuning**: Train the model on MNIST.
