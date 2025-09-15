
1. **Data Cleaning & Preprocessing**
   - Converted timestamps into standardized datetime format.
   - Extracted daily dates for alignment between sentiment data and trade data.
   - Created numerical `sentiment_score` from classification labels.
   - Merged datasets for account-wise daily statistics.

2. **Feature Engineering**
   - Calculated daily metrics per account:
     - Total & Average PnL
     - Total & Average Trade Size
     - Buy Ratio (percentage of buy trades)
     - Profit Trades & Profit Rate

3. **Exploratory Data Analysis (EDA)**
   - Visualized distribution of PnL, profit rate, and buy ratio across market sentiments.
   - Generated time-series plots of daily and cumulative PnL.
   - Built heatmaps to show account performance under different sentiments.
   - Explored relationships between trade size, PnL, and profitability.

4. **Key Insights**
   - Identified which sentiments correlate with higher profit rates.
   - Highlighted accounts with consistent profitability.
   - Found patterns between trade size and risk/reward behavior.

5. **Visualization Outputs**
   - Stacked bar charts for sentiment mix per day.
   - Correlation matrix heatmap for metric relationships
