# OANDA_API_ADD
Getting data is always the hardest part of data science, here is a handy script that uses the OANDA Rest api and 
tpqoa to pull data from any date range, avoiding the 5000 candle limit.

User must set the ticker, granularity (candle freqeuncy) and start/end date in the same format as the given example. 

2 functions are used, the 'apicall' forms a database with about 24 hours of lag, the 'api_update' brings the database to the current datetime. 
A small example on how to call the functions is given, both produce a pandas dataframe with the title of the instrument, 
this can be placed into an SQL database if so desired. 

Happy analysis, and may you be forever profitable.
