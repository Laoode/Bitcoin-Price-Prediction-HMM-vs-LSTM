# Bitcoin Price Prediction: HMM vs LSTM

## Introduction
This repository presents a comprehensive analysis and comparison of two machine learning models—Hidden Markov Model (HMM) and Long Short-Term Memory (LSTM)—for predicting Bitcoin prices. Historical Bitcoin price data, sourced from Yahoo Finance, is used to train and evaluate these models. The project aims to determine which model performs better in forecasting Bitcoin prices based on error metrics such as Absolute Percentage Error (APE), Average Absolute Error (AAE), Average Relative Percentage Error (ARPE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).

## Project Structure
- data/: Contains raw and processed data files.
  - `data-historycal-layer-1.csv`: Raw historical data for multiple cryptocurrencies fetched from Yahoo Finance.
  - `layer-1-btc.csv`: Filtered and cleaned Bitcoin price data, ready for model training.
- notebooks/: Jupyter notebooks for data fetching, exploratory data analysis (EDA), and model training.
  - `get_crypto_yahoo.ipynb`: Fetches historical cryptocurrency data from Yahoo Finance.
  - `EDA.ipynb`: Performs exploratory data analysis on Bitcoin price data, including visualizations of price trends.
  - `training_hmm_lstm.ipynb`: Trains and compares HMM and LSTM models for Bitcoin price prediction.
- images/: Stores visualizations generated during analysis, such as price trend plots and model performance comparisons.

## Key Findings
The comparison between HMM and LSTM models for Bitcoin price prediction showed that HMM significantly outperformed LSTM. Across multiple error metrics (APE, AAE, ARPE, RMSE, and MAPE), HMM was 93-94% more efficient than LSTM, indicating superior predictive accuracy and robustness for Bitcoin price forecasting.

## How to Run
1. Clone the repository: `git clone https://github.com/Laoode/Bitcoin-Price-Prediction-HMM-vs-LSTM.git`.
2. Install required libraries: `pip install yfinance pandas numpy matplotlib seaborn tensorflow hmmlearn`.
3. Run `get_crypto_yahoo.ipynb` to fetch the latest cryptocurrency data (optional if using provided data).
4. Run `EDA.ipynb` to explore and visualize the Bitcoin price data.
5. Run `training_hmm_lstm.ipynb` to train the HMM and LSTM models and compare their performance.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `tensorflow`, `hmmlearn`

## Contact
For questions or contributions, please contact yudhyprayitno567@gmail.com.
