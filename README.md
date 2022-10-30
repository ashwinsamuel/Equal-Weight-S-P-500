# Equal-Weight-S-P-500

The S&P 500 is the world's most popular stock market index. The largest fund that is benchmarked to this index is the SPDR® S&P 500® ETF Trust. It has more than US$250 billion of assets under management.

The goal of this project is to create a Python script that will accept the value of your portfolio and tell you how many shares of each S&P 500 constituent you should purchase to get an equal-weight version of the index fund.

I used the IEX Cloud API token as a data provider. A sandbox API token was used, which means that the data used is randomly-generated and has no cost associated with it. 

The ouput is an excel sheet recommended_trades.xlsx that lists all the stocks and the no of shares to buy for each of the stocks for the supplied portfolio value.
