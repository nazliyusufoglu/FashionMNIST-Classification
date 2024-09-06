# Repository Overview

## File Description
This repository contains an IPython Notebook (`.ipynb` file) that demonstrates the classification of the Fashion-MNIST dataset using the KNN algorithm. It also includes results from various evaluation metrics.

## Fashion-MNIST Dataset
- **Source:** Zalando's article images.
- **Training Set:** 60,000 examples.
- **Test Set:** 10,000 examples.
- **Image Dimensions:** 28x28 grayscale images.
- **Labels:** Associated with 10 classes.
- **Purpose:** Fashion-MNIST is intended to be a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It has the same image size and structure of training and testing splits.

## Dataset Link
You can find the Fashion-MNIST dataset [here](https://www.kaggle.com/datasets/zalando-research/fashionmnist/data)

## Dataset Structure
- **Each Row:** Represents a separate image.
- **Column 1:** Contains the class label.
- **Remaining Columns:** Contain pixel values (784 total).
- **Pixel Values:** Indicate the darkness of the pixel (range: 1 to 255).

## Model Training
- **Method:** Supervised learning using the KNN algorithm.

## Model Evaluation
- **Metrics Used:** Accuracy, precision, recall, F1 score, and confusion matrix.
