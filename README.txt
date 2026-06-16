========================================================================
README: Comprehensive Financial and Sentiment Dataset (Crypto & Stocks)
========================================================================

1. DATASET OVERVIEW
-------------------
- File Name: Crypto_Stock_Dataset_100K.csv
- Total Records: 100,000
- Asset Classes Included: Stocks (59,646 records) & Cryptocurrencies (40,354 records)
- Temporal Coverage: January 01, 2020, to January 08, 2026
- Core Tracked Symbols: 
  * Stocks: AAPL, NVDA, GOOGL, TSLA, MSFT, AMD, NFLX, AMZN, META, INTC
  * Cryptocurrencies: BTC, ETH, BNB, AVAX, XRP, MATIC, DOT, ADA, DOGE, SOL

2. FEATURE DEFINITIONS (21 COLUMNS)
-----------------------------------
- Date: Daily timestamp of the record (YYYY-MM-DD).
- Asset_Type: Categorical identifier ('Stock' or 'Crypto').
- Symbol: The trading ticker of the asset (e.g., BTC, AAPL).
- Open / High / Low / Close: Core daily candlestick price metrics.
- Volume: Total traded volume within the 24-hour period.
- Market_Cap: The total circulating market capitalization.
- Daily_Return_Percent: Calculated daily percentage change in closing price.
- Volatility_Index: Quantified rolling index representing price fluctuations.
- SMA_7 / SMA_30: Simple Moving Averages computed over 7-day and 30-day windows.
- EMA_12 / EMA_26: Exponential Moving Averages for short- and mid-term trends.
- RSI: Relative Strength Index (Momentum oscillator bounded between 0-100).
- MACD: Moving Average Convergence Divergence value.
- Bollinger_Upper / Bollinger_Lower: Rolling statistical volatility bands.
- Sentiment_Score: Quantified market tone ranging from -1.0 (highly bearish) to +1.0 (highly bullish).
- Market_Sentiment: Categorical classification ('Positive', 'Negative', 'Neutral').

3. SENTIMENT DISTRIBUTION
--------------------------
- Negative: 39,947 records
- Positive: 39,936 records
- Neutral: 20,117 records

4. POTENTIAL USE CASES
-----------------------
This multimodal dataset is heavily optimized for:
- Time-series forecasting using LSTM, GRU, or Transformer networks.
- Algorithmic trading system evaluation and backtesting.
- Quantitative asset price modeling combined with NLP-derived sentiment inputs.
- Classification tasks based on broad market trends ('Market_Sentiment').

5. LICENSING & CITATION
-----------------------
Distributed under Creative Commons Attribution 4.0 International (CC BY 4.0). 
Please cite this dataset repository and its official DOI if utilized in any academic or commercial publications.

Link: https://data.mendeley.com/datasets/552326krwn/2

Cite this dataset:
HOSSAIN, MD RAIHAN (2026), “A Comprehensive Financial and Sentiment Dataset of Cryptocurrencies and Stocks (2020–2026)”, Mendeley Data, V2, doi: 10.17632/552326krwn.2
========================================================================
