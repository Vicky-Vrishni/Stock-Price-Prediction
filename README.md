# Stock Price Prediction Using TensorFlow & LSTM

A deep learning project that predicts stock market closing prices using TensorFlow and LSTM neural networks trained on 5 years of historical Apple stock data.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Overview

Stock price prediction is one of the most challenging problems in finance, with real-world applications ranging from personal investment strategies to algorithmic trading. This project builds a prediction model using TensorFlow and Long Short-Term Memory (LSTM) networks — a type of Recurrent Neural Network (RNN) that works really well with time series data like stock prices.

The model is trained on 5 years of Apple stock price data and learns from historical patterns to forecast future closing prices.

## Features

- Loads and processes real historical stock price data using Pandas
- Handles malformed data lines during CSV loading
- Data preprocessing and normalization for better model performance
- LSTM based deep learning model built with TensorFlow and Keras
- Model compiled with optimizer, loss function, and evaluation metrics
- Visual comparison of Train data, Test data, and Predictions on a chart
- Forecasts future closing prices based on learned patterns

## Project Structure
```
Stock-Price-Prediction/
│
├── Stock Price Prediction Project using TensorFlow.ipynb  # Main Notebook
├── dataset/                                               # Stock data CSV
│   └── stock_data.csv
├── README.md                                              # Project documentation
└── requirements.txt                                       # Dependencies
```

## Installation

1. Clone the repository
```
git clone https://github.com/Vicky-Vrishni/Stock-Price-Prediction.git
```
2. Navigate to the project folder
```
cd Stock-Price-Prediction
```
3. Install the required libraries
```
pip install -r requirements.txt
```

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📊 Results

The model was trained and tested on Apple stock closing price data collected over a 5-year period. The output chart clearly shows three things — the training data, the test data, and the model's predictions — giving a visual sense of how closely the predicted values follow the actual stock prices.


## Contact

GitHub: _https://github.com/Vicky-Vrishni_ || 
Email: _skvickyadav942@gmail.com_ ||
LinkdIn: _https://www.linkedin.com/feed/_
