# ds_Assignment
#  Trader Behavior vs Market Sentiment (Fear/Greed)

This repository contains my Data Science assignment for the **Junior Data Scientist – Trader Behavior Insights** role at **PrimeTrade AI / Bajarangs**.

---

##  Objective
Analyze how **trader performance metrics (PnL, leverage, trade size, direction)** align or differ with **Bitcoin market sentiment** (Fear vs Greed).

---

##  Datasets
1. **Historical Trader Data (Hyperliquid)** – includes execution price, size, side, timestamp, PnL, etc.  
2. **Bitcoin Fear & Greed Index** – includes daily sentiment classification (Fear, Greed, Extreme Fear, etc.)

---

##  Steps Performed
1. **Data Cleaning & Preprocessing**  
   - Parsed timestamps and numeric columns  
   - Normalized trade side (BUY/SELL)  
   - Merged with sentiment dataset by date  

2. **Exploratory Data Analysis (EDA)**  
   - PnL and win-rate distribution across sentiments  
   - Trade size behavior under Fear vs Greed  
   - BUY vs SELL counts by sentiment  
   - Correlation heatmap between numeric features  

3. **Visualization Outputs**
   - `avg_pnl_by_sentiment.png`  
   - `size_usd_by_sentiment.png`  
   - `trade_side_distribution.png`  
   - `correlation_heatmap.png`

4. **Report**
   - `ds_report.pdf` includes summary insights and plots.

---

##  Repository Structure

