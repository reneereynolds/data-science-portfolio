This is one of the assignments that I'm most proud of from an elective course during my master's program. It serves as a sample of my coding as well as communication abilities.


# Data Science Project – Cryptocurrency Returns and Trading Venues

## Scenario 

You work for a Washington, DC based regulatory agency and have been chosen to lead their new data science unit to detect trading anomalies, possible market manipulation, and to identify sources of systemic risk.  
Your group is conducting a major study on trading activity in cryptocurrencies that will be shared with global regulators at an important summit in Geneva in two weeks.  Your report will have a significant impact on how agencies will approach crypto trading and markets, and it is very likely to gain considerable attention in the press.  
Your goal is to develop a method to identify whether some of the reported transactions by venue can be relied upon or not.  A key objective of your research will be to identify whether there are predictable patterns in the return and volume data.  
You must report out your findings to senior management in a suitable format. 

## Assignment
1.	Read in the data crypto.csv which consists of major cryptocurrency prices in a recent period at 5-minute intervals.  The data identify the time (UCT), date, venue, price and volume.  (The dataset will be described in more detail in the practicum.)
2.	Create a consolidated ticker tape by time stamp.  Why do you need to do this step versus working with equity data?  
3.	What exchanges (venues) report the most activity in Bitcoin (BTC)?  Ethereum (ETH)?
4.	Compute 5-minute log returns.  For equity return data, one must typically adjust for dividends or corporate actions.  Is this necessary for crypto?  
5.	Similar to the factor project, see if you can construct a ML trading model that exploits lead-lag relationships.  Explain whether you think this is viable for a hedge fund or other type of trader.
6.	Use ML techniques to identify any observable patterns in the trading data.  For example, you may look for patterns by time of day (e.g., Asia trading hours), day of week (e.g., weekends vs. weekdays), trade size, etc.  Are there any robust findings that you can detect for the largest 5 cryptocurrencies? 
7.	What can you conclude given your mandate and the tight schedule for reporting to senior management?  Explain clearly and succinctly in the form of a memo to your senior management. (Keep it brief please to 1 page).
8.	Per exchange, calculate the first significant digit distribution. What inference do you draw?
