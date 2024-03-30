# Cryptocurrency Price Prediction

## Introduction

This repository contains code for predicting the prices of various cryptocurrencies using machine learning models. The prediction is made based on historical price data of cryptocurrencies such as Monero (XMR), Ethereum (ETH), Wrapped Bitcoin (WBTC), and Bitcoin (BTC). The project focuses on implementing a linear regression model for price prediction.

## Files

- **prediction-of-cryptocurrency-price.ipynb**: This Jupyter Notebook contains the Python code for data preprocessing, model training, and visualization of cryptocurrency price prediction.
- **coin_Monero.csv**: Dataset containing historical price data for Monero.
- **coin_Ethereum.csv**: Dataset containing historical price data for Ethereum.
- **coin_WrappedBitcoin.csv**: Dataset containing historical price data for Wrapped Bitcoin.
- **coin_Bitcoin.csv**: Dataset containing historical price data for Bitcoin.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Plotly

## Usage

1. Open the `prediction-of-cryptocurrency-price.ipynb` notebook in a Jupyter environment or Google Colab.
2. Run the code cells sequentially to perform data preprocessing, model training, and visualization.
3. Adjust parameters as needed for experimentation or improvement.
4. Analyze the results and insights obtained from the prediction models.

## Data Preprocessing

- The dataset for each cryptocurrency is loaded from the respective CSV file.
- A target column (`Prediction`) is created to predict the price 'N' days into the future (default value of N is set to 5).
- Independent and dependent datasets are created for each cryptocurrency by shifting the closing price data by the projection value.

## Model Training

- Linear regression models are used for predicting cryptocurrency prices.
- The datasets are split into training and testing sets (85% training, 15% testing).
- The model is trained on the training data and evaluated using the testing data.

## Visualization

- Visualization of historical price trends and predicted prices is performed using Plotly.
- Line plots are generated to visualize the trends in Open, Close, High, Low, and Predicted prices for each cryptocurrency.

## Contributors

- Dinesh Kumar
- skdineshkumar1764@gmail.com
