# BTC-RNN-LSTM-GRU-Forecasting

## Overview

This project focuses on predicting **Bitcoin daily log returns** using three neural network architectures: **RNN**, **LSTM**, and **GRU**. The repository includes implementations of each model and uses a dataset with market, macroeconomic, and crypto-specific indicators.

## Project Contents

- **BTC_RNN.ipynb**: RNN model for log return forecasting.
- **BTC_LSTM.ipynb**: LSTM model for handling long-term dependencies.
- **BTC_GRU.ipynb**: GRU model for efficient sequence modeling.
- **Open-Open-Dataset-BTC.csv**: Dataset used in the project.
- **README.md**: Project documentation.

## Dataset

The dataset contains:
- **Market data**: Open, High, Low, Close, Volume, MarketCap.
- **Crypto-specific metrics**: Fear & Greed Index, Hash Rate, Days Since Halving.
- **Macroeconomic indicators**: Inflation, M2SL, S&P500, DXY, VIX of VIX.
- **Moving Averages**: MA5, MA20.

## Methodology

1. **Preprocessing**: Data normalization, lagged feature creation.
2. **Models**:
   - **RNN**: Baseline sequence model.
   - **LSTM**: Handles long-term dependencies.
   - **GRU**: Simplified alternative to LSTM.
3. **Evaluation**: Metrics include MAE, RMSE, and MAPE.
