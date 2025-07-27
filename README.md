# Stock Sentiment Analysis

This project analyzes the sentiment of news headlines related to Apple and Tesla, and correlates them with historical stock price movements. It uses natural language processing (NLP) techniques and machine learning to predict stock movement based on headline sentiment.

## Features

- Text preprocessing, lemmatization, and sentiment scoring (TextBlob & VADER)
- Merges headline sentiment with historical stock data (via yfinance)
- Trains a Linear Discriminant Analysis (LDA) model to predict stock movement
- Evaluates model performance (accuracy, precision, recall, F1, ROC AUC)
- Simulates trading strategies based on predictions (buy/sell signals, portfolio metrics)

## Usage

1. Install dependencies:
    ```
    pip install pandas numpy scikit-learn textblob vadersentiment yfinance matplotlib nltk
    ```
2. Run the Jupyter notebook:  
   Open `OpenProjectFinClub.ipynb` in VS Code or Jupyter and execute the cells step by step.

## Data

- `apple_dataset.csv` and `tesla_dataset.csv`: News headlines and stock movement labels
- Historical stock prices fetched using `yfinance`

## Results

- Model accuracy and metrics for both Apple and Tesla
- Portfolio simulation with stop-loss and take-profit
- Plots of buy/sell signals and portfolio value over time

## License

For educational and research purposes only.