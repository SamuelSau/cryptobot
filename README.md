# cryptobot

Uses RSI to determine when the bot sells or buys. Candlesticks are set as 1 minute intervals and only buys/sells for closing price of Bitcoin. This program takes in Binance streams of data to make a decision based on the RSI calculation. 

Can change with what indicator to use and the values if wanting to change trading patterns.

Imported APIs: python-binance, numpy, TA-Lib (ta), and websocket_client

References: 
https://github.com/binance/binance-spot-api-docs/blob/master/web-socket-streams.md
