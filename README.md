# Neural Network for Breast Cancer Prediction using PyTorch

This project implements a neural network using PyTorch to predict breast cancer based on the Wisconsin Breast Cancer dataset.

## Project Overview

This neural network model is designed to classify breast cancer tumors as either malignant or benign. It uses a simple feedforward neural network architecture implemented in PyTorch and trained on the Breast Cancer Wisconsin (Diagnostic) Data Set.

## Features

- Data preprocessing using StandardScaler
- PyTorch implementation of a feedforward neural network
- Training on GPU if available
- Evaluation on both training and test sets

## Requirements

- Python 3.x
- PyTorch
- scikit-learn
- numpy

## Installation

Clone this repository and install the required packages:

```bash
git clone https://github.com/your-username/breast-cancer-prediction-pytorch.git
cd breast-cancer-prediction-pytorch


## Model Architecture

* Input layer: 30 features
* Hidden layer: 64 neurons with ReLU activation
* Output layer: 1 neuron with Sigmoid activation

## Results

The model achieves:
* Training accuracy: 97.36%
* Test accuracy: 96.49%

## Future Improvements

* Experiment with different network architectures
* Implement cross-validation
* Add data visualization
* Explore feature importance

## License

This project is open source and available under the MIT License.

## Acknowledgments

* Breast Cancer Wisconsin (Diagnostic) Data Set
* PyTorch documentation
* scikit-learn documentation
