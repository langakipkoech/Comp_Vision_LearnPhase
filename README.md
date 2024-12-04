Features

    Data Preparation:
        Downloads the FashionMNIST dataset using torchvision.datasets.
        Visualizes individual and multiple random images with class labels.

    Model Architectures:
        Baseline Linear Model: A simple linear neural network for classification.
        Non-linear Model: Enhances the baseline by introducing ReLU activations.
        Convolutional Neural Network (CNN): Implements a two-layer convolutional architecture for improved performance.

    Training and Testing:
        Includes reusable training and testing functions.
        Tracks performance metrics such as accuracy and loss.

    Helper Functions:
        Downloads external helper functions for calculating accuracy.
        Includes a custom function to measure runtime for benchmarking.

    Prediction and Visualization:
        Uses trained models to make predictions on test data.
        Visualizes predictions with true labels for comparison.
