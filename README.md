# Cryptocurrency Price Trend Analysis and Trading Strategy Project

## Introduction
Cryptocurrency trading has gained immense popularity in recent years, attracting traders and investors worldwide. With the volatile nature of cryptocurrency markets, traders often seek analytical tools and strategies to make informed decisions. In this project, we aim to analyse cryptocurrency price trends and develop a trading strategy based on technical indicators.

## Objective
The main objective of this project is to perform a comprehensive analysis of cryptocurrency price trends and develop a trading strategy based on simple moving average (SMA) crossover signals.

## Methodology
1. **Data Acquisition**: We obtained cryptocurrency price data from the CSV file 'XMR_All_graph_coinmarketcap1.csv'. This dataset contains timestamped data including open, high, low, close prices, and trading volume.
2. **Data Preprocessing**: We converted the 'timestamp' column to datetime format for easier manipulation. Calculated additional columns such as price change, price change percentage, and SMA for 50 and 200 days.
3. **Technical Analysis**: Utilized SMA crossover strategy: When the 50-day SMA crosses above the 200-day SMA, it generates a buy signal, and when it crosses below, it generates a sell signal.
4. **Visualization**: Plotted cryptocurrency price trends, SMA lines, and trading signals using Matplotlib. Generated separate graphs for price trend analysis and volume analysis to provide comprehensive insights.

## Results
1. **Price Trend Analysis**: Analysed cryptocurrency price trends over time. Identified potential buy and sell signals based on SMA crossover strategy. Text annotations provided next to buy and sell points for easy interpretation.
2. **Volume Analysis**: Examined trading volume of the cryptocurrency over time. Assessed the level of market participation and liquidity. Provided keys for buy and sell signals for reference.

## Discussion
The SMA crossover strategy provides a simple yet effective approach to identify potential entry and exit points in cryptocurrency trading. Volume analysis complements price trend analysis and helps assess market sentiment and liquidity. Further optimization and back testing of the trading strategy may enhance its performance and reliability.

## Conclusion
This project demonstrated the process of analysing cryptocurrency price trends and developing a trading strategy based on SMA crossover signals. By combining technical analysis techniques with visualization tools, traders can make informed decisions and improve their trading performance in cryptocurrency markets.

## Future Directions
Explore additional technical indicators and machine learning models for advanced trading strategies. Implement risk management techniques and back testing frameworks for thorough evaluation of trading strategies. Stay updated with market developments and continuously refine trading strategies to adapt to changing market conditions.

## References
- Analyzing Cryptocurrency Markets Using Python
- ojasvi92/CryptoCurrency-trend-analysis - GitHub
- GitHub - kyleecodes/Crypto-Trend-Analysis: Exploring the market ...
- Comprehensive Guide to Trading with Trend Analysis with Python

## Footnote
Overall, this project provides valuable insights into cryptocurrency trading and serves as a foundation for further research and exploration in this rapidly evolving field.
