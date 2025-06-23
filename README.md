# 📊 Sentiment-Driven Trader Behavior Analysis

This project explores how Bitcoin market sentiment, measured via the Fear & Greed Index, influences trader performance on the Hyperliquid platform. Using historical trade records and sentiment labels, the analysis uncovers behavioral patterns that can inform smarter trading strategies.

## 🎯 Objective

To identify how emotions in the crypto market (Fear vs. Greed) impact:
- Profitability and PnL distribution
- Win rate of trades
- Coin-specific behavior
- Trader activity intensity

## 🔎 Key Insights

- **Win rates** and **average PnL** are higher during Greed phases, especially for high-volume tokens.
- **Fear periods** often correlate with wider variability and more extreme losses.
- Certain coins like ETH and SOL exhibit stronger sentiment-linked volatility compared to BTC.
- Trade volume and leverage behavior subtly shift across sentiment zones.

## 📊 Visualizations

- Line plot of sentiment score over time
- PnL distribution by sentiment (boxplot + barplot)
- Coin-wise PnL comparison during Fear vs. Greed
- Daily average PnL alongside sentiment score (dual-axis)
- Trade count and win rate visualization by sentiment

## ⚙️ How to Run

1. Clone the repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
