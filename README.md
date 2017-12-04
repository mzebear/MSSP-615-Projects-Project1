# MSSP-615-Projects-Project1
first project

Stock Price Action Model

High Level Hypothesis:

Low Price Stocks have high volatility. Most often these stocks are referred to as penny stocks and are small companies that are publically held. There is a black cloud surrounding the penny stock industry when talking to finance professionals due to their high  volatility. However this volatility is often due to market sentiments and news surrounding the small companies.  Some hedge funds and other financial firms will release newsletters, articles, or even ads to support or dissuade the public from buying these stocks. Therefore, I believe that market sentiment plays a large role in the movement and momentum of their stock price. 

Analysis Plan:

The plan is to collect time series stock price data for a groups of penny stocks (small_cap). Then collect market sentiment data in the form of google searches of the stock ticker for the same period. 

Data to be used (7 months of data)

	1. R package - Quantmod - access to daily Open, High, Low, Close, Adjusted, Volume stock data
	2. R package - gtrendsR - Google's API ticker names search frequency (as a comparitive function to the other days pull)

Modeling:

Multilevel model across companies to predict stock price
