# Forex_Algo


This code tests various trading indicators using years of historical data to see relative gap up from initial starting points of 0.

The algorithmic techniques utilized included Keltner Channels, Bollinger Bands, MACD, and RSI.



The data folder consists of each tradeable instrument by the user and the respective granularity for full purpose testing. 
The Infrastructure folder is responsible for this data generation, and the oanda api is used for the source is this data. 

All Oanda API Info can be found in the api folders, and the exploration folders.

The methodology utilized was a testing -> class based system, where code was essentially tested for functionality and then converted into its respective class. 
This can be seen for API testing, indicator testing, data collection testing, etc.

For easy data analysis of the various instruments, the models folder was created simply to create an instrument based class. 


The relative gap up data, was transferred to excel files using the simulation folder, and currently used to test MA.

The xlsx file therefore consisted of gap up data for every tradeable instrument, with each possible granularity (or the granularity of the users choosing).

The indicators file in the technicals folder consists of the use case of the various possible trading strategies. 


This method of completion allows for the very simple backtesting of strategies, as there is very concise implementation.
