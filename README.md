# Digit Recognition Deep Learning

This repository provides an end-to-end notebook for recognizing handwritten digits using neural networks.

## Overview

This project applies a convolutional neural network (CNN) to classify images of handwritten digits. Using Python, TensorFlow, and Keras, the notebook demonstrates data preprocessing, model training, evaluation, and prediction. The underlying dataset is typically MNIST, a benchmark dataset for digit recognition.

## Features

- Uses deep learning (CNN) for image classification.
- Covers the workflow from data loading to prediction.
- Visualizes model performance and predictions.
- Easy to customize and extend for related tasks.

## Requirements

Ensure you have the following installed:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

Install the dependencies with:

```bash
pip install tensorflow keras numpy matplotlib jupyter
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Simonatraj/digit-recognition-deep-learning.git
   cd digit-recognition-deep-learning
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Open and run `number-image-recognition.ipynb`:**
   - Walk through the cells sequentially to preprocess data, build and train the model, and visualize results.

## Usage

- Loads and visualizes the digit dataset.
- Preprocesses images (normalization, dimension reshaping).
- Builds a CNN using Keras/TensorFlow.
- Trains and validates the model.
- Evaluates metrics; plots learning curves and confusion matrix.
- Predicts on new handwritten digit images.

## Example Results

- CNNs routinely achieve over 98% accuracy on standard digit recognition tasks.
- Notebook includes plots of loss and accuracy per epoch, and showcases real predictions.
