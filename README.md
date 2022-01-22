# OANDA_API_ADD
Getting data is always the hardest part of data science, here is a handy script that uses the OANDA Rest api and 
tpqoa to pull data from any date range, avoiding the 5000 candle limit.

User must set the granularity (candle freqeuncy) and start/end date in the same format as the given example. 

A small example on how to call the functions is given, both produce a pandas dataframe with the title of the instrument, 
this can be placed into an SQL database if so desired. 

V2: GET_DATA_SQL

PROGRAM ALLOWS FOR ALL INSTRUMENTS TO BE DOWNLOADED AND SAVED INTO AN SQL DATABASE SPLIT BY BID AND ASK PRICE. 

V3: formating updates, intial call downloads the most up to date candle stick data. Example of how to download all instruments into an SQL database. 

Happy analysis, and may you be forever profitable.
