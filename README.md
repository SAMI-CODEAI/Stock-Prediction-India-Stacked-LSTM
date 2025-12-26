# Predicting Indian Stock Prices with Stacked LSTM


This Python project focuses on predicting Indian stock prices using a Stacked Long Short-Term Memory (LSTM) neural network model. It provides valuable insights into stock data for four prominent Indian companies: Reliance Industries, Tata Steel, HDFC Bank, and Infosys. Here's what you need to know:


### Stacked LSTM Model:
- **Sequential Model:** Utilizes Keras' Sequential model for building the LSTM architecture.
- **Stacked LSTM Layers:** Employs three LSTM layers stacked to capture intricate temporal patterns in stock prices.
- **Activation Functions:** Explores Swish activation for smoothness and improved performance.
- **Output Layer:** Features a dense output layer for continuous stock price prediction.

### Hyperparameter Tuning:
- **Optimization Functions:** Compares various functions like Adam, Nadam, Adagrad, and Adadelta for model training.
- **Epochs and Batch Size:** Experiment with different values to optimize training.
- **Dropout Layers:** Utilizes dropout layers to prevent overfitting and enhance generalization.

### Model Evaluation:
- Uses Root Mean Square Error (RMSE) to assess model performance, with an RMSE of approximately 25.99 as the benchmark.

## Exploratory Data Analysis (EDA):
### 1. Overview of All 4 Companies:
- Visualizes the closing prices of all four companies on a single plot.
- Offers insights into stock price trends over time.

### 2. Adjusted Close Price for Each Stock:
- Displays adjusted close prices for each stock via subplots.
- Provides historical performance snapshots.

### 3. Total Volume of Stock Traded Each Day:
- Depicts trading volume for each company over time.
- Reflects stock liquidity and investor interest.

### 4. Moving Average of Each Stock:
- Calculates and plots moving averages (10, 30, and 50 days) for each stock.
- Identifies trends and smoothes price fluctuations.

### 5. Daily Return:
- Computes and visualizes daily returns through line plots and histograms.
- Offers insights into daily price fluctuations and return distributions.

### 6. Correlation between Different Stocks & Closing Prices:
- Explores correlations between closing prices of the four companies.
- Uses scatter plots and correlation matrices to uncover relationships.

## Project Output:
This project provides an in-depth analysis of Indian stock data, from data collection to visualization and model development. It showcases the potential of LSTM neural networks in stock price prediction, with an RMSE benchmark of 25.99. Contributors are encouraged to fine-tune hyperparameters and apply diverse techniques to enhance model performance.


rmse
25.997853047279122
