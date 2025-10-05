# Quantitative-Finance
Quantitative Finance bootcamp learning and practice material.

Project: Portfolio Strategy using Machine Learning and Sharpe Ratio

Combining Machine Learning with Modern Portfolio Theory for Smarter Investing

🟥 1. Objective

Goal: Build a self-learning portfolio that selects and weights the best-performing stocks using AI + Quant Finance.

🧠 Machine Learning → predicts outperformers
📈 Modern Portfolio Theory → allocates capital optimally

📊 Universe: 50 large-cap US stocks | Benchmark: S&P 500 | Rebalanced quarterly

🟦 2. Data & Features

📅 Period: 2018–2025 (daily data)
📚 Features:

1M, 3M, 6M momentum returns

Volatility (risk)

Sharpe Ratio (risk-adjusted return)

Beta (market sensitivity)

Drawdown (downside risk)

🧮 Target: Will this stock beat the S&P 500 in the next 3 months?

🟩 3. ML Model

⚙️ Random Forest Classifier
🔁 Trained on rolling 3-year window
⏱ Retrained quarterly (no look-ahead bias)
🎯 Predicts top 10 stocks expected to outperform

🟨 4. Portfolio Optimization

📊 Optimization Method: Sharpe Ratio Maximization
⚖️ Constraints:

5% ≤ Weight ≤ 25%

Σ Weights = 1
📅 Rebalance Frequency: Every 3 months (~63 trading days)

🟪 5. Backtesting & Evaluation

🧭 Test Period: 2020–2025
📈 Metrics Evaluated:

Cumulative Return

Quarterly Return Comparison

Sharpe Ratio (risk-adjusted return)

Top Contributor per Quarter

Cumulative PnL by Stock

✅ Rolling backtest
✅ No future data leakage
✅ Continuous learning framework

🟧 6. Key Results

🏆 Cumulative Performance:

ML+Quant Portfolio > S&P 500


🔥 Top Stocks: NVDA, AAPL, MSFT, AMZN, LLY

💡 Consistent outperformance with controlled risk.
