# Bitcoin Price Prediction: Deep Learning vs Linear Regression

A comprehensive comparative study evaluating the effectiveness of deep learning regression models against traditional linear regression for cryptocurrency time series forecasting using Bitcoin OHLCV data.

## Project Overview

This project addresses a fundamental question in financial machine learning: **Do deep learning models provide superior performance over traditional linear regression for Bitcoin price prediction?** Through systematic experimentation and hyperparameter optimization, we compare multiple neural network architectures against baseline linear regression models.

### Novel Contribution
- **First-principles comparison** between deep learning and classical ML approaches
- **Controlled experimental design** with identical feature sets across all models
- **Hyperparameter optimization** to ensure fair deep learning model evaluation
- **Performance analysis** revealing surprising insights about model complexity vs accuracy

### Key Features
- **Time Series Regression**: 60-minute ahead Bitcoin percentage change prediction
- **Model Comparison Framework**: Linear Regression vs Deep Neural Networks
- **Extensive Feature Engineering**: 80+ technical indicators and statistical features
- **Systematic Hyperparameter Tuning**: Optimized deep learning architectures
- **Statistical Analysis**: Rigorous performance evaluation and significance testing

## Dataset

- **Source**: Kraken Exchange Bitcoin OHLCV data (BTCUSD_1.csv)
- **Time Period**: 3 years of high-frequency trading data
- **Granularity**: 1-minute intervals
- **Size**: 1,043,739 samples (951,222 after preprocessing)
- **Features**: Timestamp, Open, High, Low, Close, Volume, Number of Trades

### Data Characteristics
```
Sample Rate: 1 minute
Price Range: $16,500 - $73,750
Volume Range: 0.001 - 2,847 BTC
Time Span: January 2022 - December 2024
```

## Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Required Libraries
- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn, tensorflow
- **Visualization**: matplotlib, seaborn
- **Development**: jupyter

### Quick Start
1. Clone the repository:
```bash
git clone https://github.com/yourusername/bitcoin-dl-vs-linear.git
cd bitcoin-dl-vs-linear
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the analysis:
```bash
jupyter notebook bitcoin_deep_learning_regression.ipynb
```

