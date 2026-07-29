# Stock Price Prediction

## Overview
- Purpose: Demonstrates loading historical stock data, feature engineering, training a model to predict stock prices, and visualizing results.

## Recommended Packages
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- yfinance (for data download)
- jupyter
- (optional) tensorflow or pytorch if deep learning models are used

## Quick Setup
1. Create and activate a virtual environment:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install --upgrade pip
```

2. Install packages (example):

```powershell
pip install pandas numpy scikit-learn matplotlib seaborn yfinance jupyter
# Optional for deep learning:
pip install tensorflow
```

## Running the Notebook
- Start Jupyter and open the notebook:

```powershell
jupyter notebook
```

- Run cells sequentially. The notebook contains sections for data download, preprocessing, model training, evaluation, and visualization.

## Notebook Structure
- Data: download from Yahoo Finance using `yfinance` or load a local CSV
- Features: moving averages, returns, volume-based features, and any engineered indicators
- Model: classical ML (e.g., RandomForest/LinearRegression) or deep learning (e.g., LSTM)
- Evaluation: train/test split, metrics (MAE, RMSE), and plots of predicted vs actual

