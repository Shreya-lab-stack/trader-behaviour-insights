# Trader Behavior Insights – Fear vs Greed Analysis

## Overview
This project analyzes how trader behavior and performance change across
different market sentiment regimes (Fear vs Greed).

The objective is to identify behavioral patterns at a **daily level**
and derive actionable trading recommendations.

---

## Data
- Trader transaction dataset
- Market sentiment index (Fear vs Greed classification)
- Both datasets aligned at **daily granularity**

---

## Methodology
1. Loaded and validated both datasets (shape, missing values, duplicates)
2. Converted timestamps and aligned data by date
3. Engineered daily-level metrics:
   - Daily PnL (performance proxy)
   - Daily trade count (activity level)
   - Average trade size (risk proxy)
4. Merged trader metrics with daily sentiment labels
5. Compared trader behavior across Fear vs Greed regimes
6. Segmented traders based on risk and activity patterns

---

## Key Insights
- Average daily PnL is higher during Greed periods, but with increased variability
- Trade frequency rises significantly during Greed and drops during Fear
- Traders take larger average position sizes during Greed, indicating higher risk exposure
- Long positions dominate during Greed, confirming sentiment-driven directional bias
- Performance differences are primarily driven by behavioral changes rather than skill improvement


---

## Strategy Recommendations
- During **Fear** periods, reduce position size and leverage to limit downside risk  
- During **Greed** periods, higher activity strategies can be selectively applied to experienced traders with controlled risk  

---

## Repository Structure

Trader-Behavior-Insights/
│
├── notebook/
│   └── trader_behavior_analysis.ipynb
│
├── outputs/
│   ├── trade_frequency_by_sentiment.png
│   ├── avg_pnl_by_sentiment.png
│   └── daily_pnl_by_sentiment.png
│
├── data/
│   └── README.md   
│
├── README.md

---

## How to Run
1. Clone this repository
2. Open `notebook/trader_behavior_analysis.ipynb`
3. Run all cells sequentially

No additional setup is required beyond standard Python data libraries.

---

## How to Run
1. Clone this repository
2. Open `notebook/trader_behavior_analysis.ipynb`
3. Run all cells sequentially

No additional setup is required beyond standard Python data libraries.
