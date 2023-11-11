# Algorithmic Trading

## Task 1 - Unsupervised Learning Trading Strategy
- Unsupervised Learning Trading Strategy, utilizing S&P 500 stocks data to master features, indicators, and portfolio optimization.
### Features and technical indicators used for each stock.
* Garman-Klass Volatility
* RSI
* Bollinger Bands
* ATR
* MACD
* Dollar Volume
### For each month select assets based on the cluster and form a portfolio based on Efficient Frontier max sharpe ratio optimization
* First we will filter only stocks corresponding to the cluster we choose based on our hypothesis.
* Momentum is persistent and my idea would be that stocks clustered around RSI 70 centroid should continue to outperform in the following month - thus I would select stocks corresponding to cluster 3.
* Then maximise the sharpe ratio with Efficient Frontier Optimizer.
* Apply diversification according to weight bound constraints.
## Task 2 - Twitter Sentiment Trading Strategy
- Leveraged the power of social media with the Twitter Sentiment Investing Strategy, ranking NASDAQ stocks based on engagement and evaluating performance against the QQQ return.
## Task 3 - Intraday GARCH Trading Strategy
- The Intraday Strategy will introduce you to the GARCH model, combining it with technical indicators to capture both daily and intraday signals for potential lucrative positions.
