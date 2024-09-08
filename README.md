RSI Strategy Backtest with Benchmark Comparison

This repository contains a Python script that backtests a Relative Strength Index (RSI) based trading strategy on Tesla (TSLA) and compares its performance against a buy-and-hold strategy on S&P 500 Futures (ES=F). The backtest is conducted using the VectorBT library, enabling efficient data retrieval, strategy implementation, and performance analysis.

Features:

- The script applies a 14-period RSI on TSLA, generating buy signals when RSI crosses above 50 and sell signals when RSI crosses below 50.
- The strategy's performance is compared against a benchmark buy-and-hold strategy on ES=F (S&P 500 Futures).
- The script generates visual comparisons of portfolio values and includes relevant performance statistics for both the RSI strategy and the benchmark.
- Users can adjust the start and end dates and the data interval (e.g., daily) to backtest different periods.

Requirements:

- Python 3.7 or higher
- yfinance library
- vectorbt library
- matplotlib library
