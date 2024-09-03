# KAIM-W1
## A repo for Kifya Ai Mastery program Week 1

# Financial News and Stock Price Correlation Analysis

This project focuses on the detailed analysis of a large corpus of financial news data to discover correlations between news sentiment and stock market movements. The analysis primarily involves Google stock data and associated news headlines, with the goal of understanding how sentiment in financial news impacts stock price behavior. The project involves three main tasks:
### 1. Financial News Sentiment Analysis:
Sentiment analysis is performed on the financial news headlines to categorize them as positive, negative, or neutral. This provides a quantitative measure of the tone of each article.

### 2. Technical Indicators Analysis with TA-Lib:
Stock price data is analyzed using technical indicators such as Simple Moving Average (SMA), Exponential Moving Average (EMA), Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD) to identify trends and potential trading signals.

### 3. Correlation Analysis:
The project investigates the relationship between the daily sentiment scores derived from the news data and the daily returns of the selected stocks to determine the impact of news sentiment on stock price movements.

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks containing the analysis.

## How to Run

1. Clone the repository:
   ```bash
   https://github.com/BekLG/KAIM-W1.git

2. Install the required dependencies::
   ```bash
   pip install -r requirements.txt

3. Open the Jupyter notebook and run the cells to see the analysis


## Dependencies

- pandas
- matplotlib.pyplot
- seaborn
- TextBlob
- CountVectorizer (from sklearn)
- LatentDirichletAllocation (from sklearn)
- TfidfVectorizer (from sklearn)
- pynance
- TA-Lib

