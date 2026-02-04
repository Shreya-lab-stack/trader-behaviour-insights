# Trader Behavior Insights – Fear vs Greed Analysis

## Overview
This project analyzes how trader behavior and performance change across
different market sentiment regimes (Fear vs Greed).

The goal is to identify behavioral patterns and derive actionable trading
recommendations.

---

## Data
- Trader transaction dataset
- Market sentiment index
- Data aligned at daily level

---

## Methodology
1. Cleaned and validated both datasets
2. Converted timestamps and aligned data by date
3. Engineered key metrics:
   - Trade frequency
   - Long/short ratio
   - Leverage proxy
   - Performance proxy
4. Compared trader behavior across Fear vs Greed periods
5. Segmented traders based on activity and risk behavior

---

## Key Insights
- Trader performance differs noticeably between Fear and Greed regimes
- Risk-taking (leverage and trade frequency) increases during Greed periods
- High-frequency traders react more strongly to sentiment changes

---

## Strategy Recommendations
- Reduce leverage exposure during Fear periods to control downside risk
- Increase trade frequency selectively during Greed periods for experienced traders

---

## How to Run
1. Clone this repository
2. Open `notebook/trader_behavior_analysis.ipynb`
3. Run all cells sequentially

No additional setup is required beyond standard Python data libraries.
