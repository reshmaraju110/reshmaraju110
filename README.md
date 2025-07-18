# 8 CNN-Based Stock Price Prediction

This repository contains a Convolutional Neural Network (CNN) model built using Python to predict stock price trends based on historical stock data.

# Project Overview

The goal of this project is to use a CNN architecture to learn and predict stock price movement or trends from historical stock data. While CNNs are typically used in image recognition, here they are adapted for 1D time-series forecasting.

# Files

- `cnnprediction.ipynb`: Main Jupyter Notebook containing code for data preprocessing, model training, evaluation, and visualization.

# Features

- Data preprocessing and normalization
- Reshaping historical price data for CNN input
- CNN model construction using Keras/TensorFlow
- Training, evaluation, and performance plotting

# Model Architecture

The CNN model consists of:
- 1D Convolution layers to extract temporal features
- MaxPooling layers
- Dense layers for prediction
- Loss: MSE (Mean Squared Error)
- Optimizer: Adam

# Data

The model uses historical stock price data (e.g., Open, High, Low, Close). You can replace the dataset with your own CSV file.

# How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/reshmaraju110/reshmaraju110.git
   cd reshmaraju110
   
  Open the notebook:
    bash jupyter notebook cnnprediction.ipynb
    
Run all cells in the notebook to:
  Load and preprocess the data
  Train the CNN model
  Evaluate performance with plots

📈 Sample Output
(Optional: Insert sample charts or model accuracy/loss screenshots)
