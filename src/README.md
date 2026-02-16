Trader Behaviour vs Market Sentiment Analysis
Objective

This project analyzes how market sentiment (Fear/Greed) influences trader behavior, trading risk, and profitability using Hyperliquid trading data.
The goal is to identify behavioral patterns and derive actionable strategy insights that can improve trading performance and risk management.

Datasets

Bitcoin Market Sentiment Dataset

Contains daily Fear/Greed classification

Used to measure market emotional state

Hyperliquid Historical Trader Data

Includes trade execution details, position size, leverage, timestamps, and PnL

Used to analyze trader behavior and performance

Methodology

Data cleaning and timestamp alignment across datasets

Feature engineering of trader level daily metrics:

Daily PnL

Trade frequency

Average position size

Win rate

Sentiment-based comparison of trader behavior and profitability

Trader segmentation based on trading activity and position sizing

Behavioral clustering using KMeans to identify trader archetypes

Predictive modeling of trader profitability using Gradient Boosting

Key Insights

Trading behavior changes significantly across Fear and Greed market conditions.

High-frequency traders tend to exhibit higher volatility in profitability.

Behavioral segmentation reveals distinct trader archetypes with different risk return characteristics.

Trade frequency, position size, and sentiment indicators are strong predictors of trader profitability.

Strategy Recommendations

Apply sentiment aware leverage and position sizing controls during high-risk sentiment periods.

Limit excessive trading frequency to reduce over trading losses.

Implement segment specific risk management rules tailored to trader behavior profiles.
