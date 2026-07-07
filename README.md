# Fashion-MNIST Clothing Classification

A multiclass neural network built using TensorFlow and Keras to classify grayscale clothing images into 10 categories.

## Overview

This project uses the Fashion-MNIST dataset and covers the complete neural network workflow, including:

- Image preprocessing and pixel normalization
- Training, validation, and test set evaluation
- Feedforward neural network with ReLU activations
- Multiclass classification using logits and softmax probabilities
- Training and validation performance analysis
- Confusion matrix and per-class evaluation
- Analysis of misclassified images
- Experimentation with L2 regularization and early stopping

## Technologies Used

- Python
- NumPy
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn

## Results

### Baseline Model

- **Test Accuracy:** 87.11%
- **Test Loss:** 0.4216

The model performed particularly well on classes such as **Trouser**, **Bag**, **Sandal**, and **Ankle boot**, while visually similar classes such as **Shirt**, **Pullover**, **Coat**, and **T-shirt/top** were more difficult to distinguish.

### Regularization Experiment

A second model was trained using L2 regularization and early stopping to address overfitting.

- **Test Accuracy:** 86.76%
- **Test Loss:** 0.4581

This configuration did not improve test performance, demonstrating the importance of experimentally evaluating regularization techniques and tuning hyperparameters.

## Course Reference

The neural network and multiclass classification concepts used in this project were learned through Andrew Ng's **Machine Learning Specialization** on Coursera.

I adapted these concepts to build, train, evaluate, and analyze a neural network using the Fashion-MNIST dataset.

## Future Improvements

Future improvements could include hyperparameter tuning, dropout regularization, data augmentation, and convolutional neural networks (CNNs) for better spatial feature learning.
