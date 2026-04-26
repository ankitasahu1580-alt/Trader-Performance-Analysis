This project analyzes trader performance based on market sentiment using the Fear & Greed Index.
The goal is to understand how emotions like Fear, Greed, Extreme Fear, Extreme Greed, and Neutral sentiment impact trading outcomes (Closed PnL).

Dataset Used-:
fear_greed_index.csv → Market sentiment data
historical_data.csv → Trading data (PnL, size, trades).

Tools & Technologies-:
Python 
Pandas
Matplotlib

Analysis Performed-:
Data cleaning and preprocessing
Date formatting and merging datasets
Grouping data by sentiment (Classification)
Calculating:
Average PnL
Trade size analysis
Performance by sentiment.

Key Insights-:
Trading behavior varies significantly across sentiment categories
Extreme Fear and Extreme Greed show high volatility in PnL
Neutral markets tend to have more stable performance
Some sentiments show higher risk and reward patterns

Visualization-:
Boxplot of Closed PnL by Market Sentiment
Helps identify distribution, outliers, and risk patterns

How to Run-:
Download the repository
Open the .ipynb file in Jupyter Notebook / VS Code
Run all cells.

Conclusion-:
Market sentiment plays a crucial role in trading performance.
Understanding emotional market conditions can help in making better trading decisions.




