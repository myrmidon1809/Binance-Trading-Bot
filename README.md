# Binance-Trading-Bot (WIP)
Bot created to trade cryptocurrencies on the Binance platform

Access the Binance Exchange through CCXT (https://github.com/ccxt/ccxt)
HA indicator from (https://github.com/twopirllc/pandas-ta/blob/11e7eda03f9ab68abf6173ce16c67d9b8785a1d9/pandas_ta/trend/ha.py)

Currently set to trade XRP/AUD based on the following indicators:
Execute BUY order if Heikin Ashi close > Heikin Ashi open, 
AND Heikin Ashi low > EMA, 
AND Heikin Ashi low > Parabolic SAR, 
AND Heikin Ashi low >= Heikin Ashi close, 
AND if at least last 3 of last 5 candles close price < open price

Sell order is still a work in progress
