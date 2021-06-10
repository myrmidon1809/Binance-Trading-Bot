# Binance-Trading-Bot
Bot created to trade cryptocurrencies on the Binance platform

Currently set to trade XRP/AUD based on the following indicators:
Execute BUY order if Heikin Ashi close > Heikin Ashi open, 
AND Heikin Ashi low > EMA, 
AND Heikin Ashi low > Parabolic SAR, 
AND Heikin Ashi low >= Heikin Ashi close, 
AND if at least last 3 of last 5 candles close price < open price

Sell order is still a WIP
