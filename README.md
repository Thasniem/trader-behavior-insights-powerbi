
# Impact of Market Sentiment on Trader Profitability - A Trader Behaviour Insights

## 📌 Objective
Explore the relationship between trader performance and market sentiment using real historical data, uncover hidden behavioral patterns, and extract insights to improve trading strategy.

## 📊 Datasets Used
1. **historical_data.csv** – Contains trade-level data (account, coin, execution price, size, leverage, PnL, etc.)
2. **fear_greed_index.csv** – Contains daily market sentiment (Fear/Greed classification)

## 🧪 Methodology
- Cleaned and preprocessed timestamps
- Created derived metrics: Total PnL, Avg Leverage, Trade Volume, Avg Execution Price
- Merged datasets using common Date column
- Built 12 unique Power BI visuals across 10 report pages

## 📈 Visuals Included
1. Bar Chart – Avg PnL by Sentiment
2. Line Chart – PnL Trend over Time
3. Area Chart – Trade Volume Over Time
4. Waterfall Chart – Daily PnL Breakdown
5. KPI Cards – Total PnL, Avg Leverage, Trade Volume
6. Scatter Plot – Avg Leverage vs PnL (colored by Sentiment)
7. Pie Chart – PnL Contribution by Sentiment
8. Donut Chart – Trade Volume by Coin
9. Decomposition Tree – PnL explained by Sentiment → Coin → Side
10. Matrix/Heatmap – PnL by Date and Sentiment
11. Q&A Visual – Interactive NLP query for insights
12. Card Visuals – High-level snapshot values

## 🧠 Key Insights
- Traders earned more on average during **Greed** sentiment days than during **Fear** days.
- High leverage did not consistently lead to higher profit, suggesting smarter risk management is needed.
- Specific coins contributed disproportionately to PnL under certain sentiment types.

## 🛠️ Tools Used
- Power BI Desktop
- Power Query Editor
- DAX Measures
- Custom Visuals & Formatting

## Note
This project was developed as part of the application for the role:
**Junior Data Scientist – Trader Behavior Insights**



