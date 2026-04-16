📈 Trader Performance vs. Market Sentiment Analysis
Objective
The goal of this analysis is to explore the relationship between market sentiment (measured by the Fear/Greed Index) and trader behavior/performance. The project aims to identify how emotional market cycles impact profitability and decision-making.

Key areas of analysis include:

Profitability: Evaluating PnL (Profit and Loss) and Win Rates.

Trading Behavior: Analyzing position sizing and long/short bias.

Sentiment Influence: Correlating performance with market sentiment classifications.

Predictive Modeling: Developing a model to estimate trade profitability.

Datasets
The analysis utilizes two primary data sources:

Market Sentiment Data: A dataset containing the Fear/Greed index with daily values and classifications (e.g., Extreme Fear, Neutral, Extreme Greed).

Historical Trader Data: Detailed transaction logs including execution prices, position sizes, side (Buy/Sell), closed PnL, and timestamps.

Tech Stack
Language: Python

Environment: Google Colab

Libraries:

pandas: For data manipulation and cleaning.

matplotlib & seaborn: For data visualization.

Methodology
1. Data Cleaning & Preparation
Both datasets were inspected and found to contain no missing (null) values.

Timestamps were converted to standard datetime formats to enable daily-level synchronization.

A common date column was established to merge sentiment classifications with individual trade data.

2. Analysis & Insights (Selected Findings)
Extreme Greed Efficiency: Traders often achieve their highest win rates during "Extreme Greed" conditions, typically favoring short positions with smaller position sizes.

Extreme Fear Risks: Conditions of "Extreme Fear" often lead to emotionally driven decisions, lower win rates, and a tendency to favor long positions inappropriately.

Trading Rules of Thumb
Based on the analysis, the following strategies are suggested:

Focus on Precision: In Greed-heavy markets, prioritize smaller, precise trades.

Avoid Directional Bias: During Extreme Fear, avoid heavy long positions and consider hedging or contrarian strategies.
