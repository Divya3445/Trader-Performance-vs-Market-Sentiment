# Trader-Performance-vs-Market-Sentiment

# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment and trader performance on Hyperliquid. The objective is to identify how different market sentiment conditions influence trader behavior, profitability, and trading activity.



## Dataset

Two datasets were used:

1. Bitcoin Fear & Greed Index
2. Hyperliquid Historical Trader Data



## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook



## Methodology

- Loaded and explored both datasets.
- Checked missing values and duplicates.
- Converted timestamps into a common date format.
- Merged datasets using the Date column.
- Performed exploratory data analysis.
- Calculated:
  - Daily Closed PnL
  - Trade Frequency
  - Average Trade Size
  - Win Rate
  - Long vs Short Analysis
  - Trader Segmentation



## Key Insights

- Extreme Greed showed the highest average trader profitability.
- Fear periods were associated with the largest average trade sizes.
- Neutral markets generally resulted in lower average profitability.



## Strategy Recommendations

- Increase exposure selectively during Extreme Greed while maintaining proper risk management.
- Reduce trading activity during Neutral market conditions and wait for stronger market signals.



## How to Run

1. Clone this repository.
2. Install required libraries:


pip install pandas numpy matplotlib


3. Open `analysis.ipynb` in Jupyter Notebook.

4. Run all cells sequentially.
