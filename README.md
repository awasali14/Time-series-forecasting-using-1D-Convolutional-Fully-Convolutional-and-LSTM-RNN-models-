# Time-series-forecasting-using-1D-Convolutional-Fully-Convolutional-and-LSTM-RNN-models




# Time Series Forecasting with CNN and LSTM in TensorFlow

## Overview

This repository contains an implementation of a time series forecasting model using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks in TensorFlow. The models predict future values based on historical time series data, demonstrating the use of 1D convolutional layers and stateful LSTMs for sequential data prediction.

## Motivation

The project was initiated to explore the effectiveness of combining CNNs and LSTMs to handle time series data, benefiting from CNNs' ability to extract patterns from sequences and LSTMs' capability to remember long-term dependencies.

## Problem Solved

The implementation addresses the challenge of forecasting future values from historical time series data, which is a common problem in various domains like finance, weather forecasting, and more. It showcases a method to improve prediction accuracy and model robustness by integrating CNN and LSTM layers.

## Learnings

- Implementation of sequential window datasets for time series analysis.
- Integration of 1D CNN layers for feature extraction from time series.
- Utilization of stateful LSTMs to maintain state across the batches of data.
- Application of callbacks like Learning Rate Scheduler, Early Stopping, and Model Checkpointing to enhance training phases.


## Model Details

The models are built using TensorFlow and Keras, featuring layers such as:

- **Conv1D**: For processing time series data.
- **LSTM**: To capture long-term dependencies in data sequences.
- **Dense**: For prediction output based on the extracted features.

Training involves adjusting learning rates and using early stopping criteria to prevent overfitting, ensuring optimal model performance.

## Results

Model performance is evaluated using Mean Absolute Error (MAE) between the predicted and actual values, with results visualized in plots showing training and validation accuracy and loss, as well as forecast comparisons.

