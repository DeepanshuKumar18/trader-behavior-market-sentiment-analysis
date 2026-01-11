# Trader Behavior vs Market Sentiment Analysis

##  Overview
This project explores the relationship between **trader performance** and **market sentiment** in the cryptocurrency market using real historical trading data and the Bitcoin Fear & Greed Index.

The goal is to understand how emotions such as fear and greed influence trading behavior and to derive insights that can support smarter trading strategies.

---

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- **Columns:** `date`, `classification`
- Represents daily market sentiment:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

### 2. Historical Trader Data (Hyperliquid)
- Key columns used:
  - `Account`
  - `Coin`
  - `Execution Price`
  - `Size USD`
  - `Side`
  - `Timestamp IST`
  - `Closed PnL`

---

##  Analysis Performed

- Data cleaning and preprocessing
- Merging sentiment data with trade-level data
- Exploratory Data Analysis (EDA)
- Sentiment-wise analysis of:
  - Trade count
  - Profit & Loss (PnL)
  - Win rate
  - Trade size
- Visualization of key behavioral patterns

---

##  Key Insights

- Trading activity is highest during **Fear** and **Greed** periods.
- **Extreme Greed** shows the highest average profitability and win rate.
- **Fear** leads to larger but riskier trades.
- **Extreme Fear** is the least favorable condition for consistent trading performance.
- Larger trade sizes increase risk exposure but do not guarantee higher profits.

---
