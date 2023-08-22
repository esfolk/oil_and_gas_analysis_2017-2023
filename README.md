# oil_and_gas_analysis_2017-2023

Throughout the analysis, it's important to emphasize that the models and strategies explored represent a foundational and relatively simple approach to understanding the dynamics of the energy commodities market. While these initial models provided valuable insights and demonstrated potential profitability, they can be considered as starting points or building blocks.

The real potential lies in refining and expanding upon these foundational models. With the incorporation of more sophisticated techniques, advanced statistical methods, and potentially machine learning algorithms, the model's accuracy and profitability can be greatly enhanced. By integrating external factors, such as geopolitical events, macroeconomic indicators, and other relevant data sources, the model can become even more robust, adaptive, and capable of navigating the intricacies of the commodities market.

In essence, while the current models offer promising initial results, the journey towards a truly robust and high-performing trading strategy has just begun. The groundwork laid here paves the way for a more comprehensive, dynamic, and adaptive system that can capitalize on the myriad opportunities within the energy sector.


CTA style trend following analysis on E-Mini Futures using both discrete and stochastic models to test predictability. 

## 1. Data Loading and Initial Exploration:
Loaded three datasets related to futures of Brent Crude Oil, Natural Gas, and RBOB Gasoline.
Conducted an initial exploration of the datasets, visualizing the price movements over time.

## 2. Correlation & Cointegration Analysis:
Calculated the Pearson correlation coefficients between the assets to gauge their linear relationship.
Conducted cointegration tests using the Engle-Granger method, revealing potential mean-reverting relationships among the assets.

## 3. Moving Averages Visualization:
Visualized Simple, Exponential, and Volume Weighted Moving Averages for each asset, providing insights into trends and potential trading signals.

## 4. VAR and VARMA Modeling:
Implemented Vector Autoregression (VAR) to model interdependencies between the assets.
Extended the model to VARMA, capturing both autoregressive and moving average components.
Discussed the potential applications of VARMA in the context of a CTA trend following strategy.

## 5. Ornstein-Uhlenbeck (OU) Process:
Described the OU process, a mean-reverting stochastic process.
Estimated OU parameters for each asset and simulated potential future paths using Monte Carlo simulation.

## 6. Time Series Momentum (TSMOM) Strategy:
Visualized daily volume for Brent Crude, highlighting volume clustering.Conducted a return predictability analysis using pooled time-series cross-sectional regression, incorporating past returns of other assets.
Implemented and visualized the TSMOM strategy for Brent Crude, determining long and short positions based on a 12-month look-back period.
Evaluated the performance of the TSMOM strategy using metrics like cumulative returns, Sharpe ratio, Value at Risk, and maximum drawdown.
Strategic Insights & Further Development:

Discussed the potential of integrating the insights from various analyses to develop a more sophisticated trading model.
Explored potential sell points for the project, emphasizing the opportunities in the energy sector and the potential for diversification and risk management.
Throughout the session, we combined statistical methods, econometric modeling, and quantitative trading strategies to gain insights into the relationships and dynamics of the three energy commodities. The analyses provided foundational knowledge and potential directions for further refining and developing trading strategies.

