## Data

* Daily spot exchange rates for EUR/USD, EUR/GBP, EUR/JPY, EUR/CHF, and EUR/CAD from 2004 onwards.
* Daily 3-month and 6-month government bond yields for each currency, used as proxies for risk-free interest rates.

## Methodology

* Carry Trade Calculation: Daily carry trade returns are calculated for each pair, incorporating daily exchange rate changes and interest rate differentials.
* Performance Metrics: Cumulative returns, annualized returns, annualized volatility, Sharpe ratios, and maximum drawdowns are calculated and visualized for each pair.
* Ranking: Currency pairs are ranked based on their historical risk-return profiles.
* Visualization: Various charts and graphs are used to illustrate the performance and risk characteristics of the carry trade strategies.

## Assumptions

* Risk-Free Rates: 3-month and 6-month government bond yields are used as proxies for risk-free interest rates.
* Uncovered Carry Trades: The analysis focuses on uncovered carry trades, where no hedging is used to mitigate exchange rate risk.
* Data Limitations: The analysis acknowledges potential limitations in data availability and accuracy.

## Observations

* SNB Event: The impact of the Swiss National Bank's (SNB) decision to remove the 1.20 floor on EUR/CHF on January 15, 2015, is visible in the analysis.

## Tools and Technologies

* Python
* Pandas
* Matplotlib

## Future Work

* Incorporate implied volatility and volatility risk premium using VIX data for EUR, JPY, and GBP pairs.
* Explore alternative risk measures like Value at Risk (VaR) and Conditional Value at Risk (CVaR).
* Develop a machine learning model to predict future carry trade performance.

## Conclusion

This project provides a comprehensive historical analysis of uncovered currency carry trades, offering insights into their potential returns and risks. The findings can be used to inform investment decisions and guide further research in this area.
