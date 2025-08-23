# LSTM-Transformer Petroleum Prediction

Python implementation of a hybrid sLSTM + Transformer model for petroleum engineering data prediction.

## Project Description
This repository contains the Python scripts used to train and test an sLSTM-Transformer model for time series prediction in petroleum engineering. The model combines stabilized LSTM cells with Transformer encoder-decoder blocks for accurate forecasting.

## Features
- Data preprocessing and MinMax normalization
- sLSTM implementation
- Transformer encoder-decoder architecture
- Training, validation, and testing pipelines
- Model evaluation metrics: R2, MAE, RMSE, MAPE
- Prediction output saved as Excel file

## Requirements
- Python 3.8+
- PyTorch 1.12
- NumPy 1.23
- Pandas 1.2
- Matplotlib 3.5
- scikit-learn 1.5
- tqdm 4.66
- timm 1.0

Install dependencies with pip:

```bash
pip install torch numpy pandas matplotlib scikit-learn tqdm timm
