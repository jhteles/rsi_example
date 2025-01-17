# rsi_example

Hello!

Here is a code to calculate real time RSI for bitcoin or whichever asset in yahoo finances. One can set the start and end date and the time increment. A simple and an interactive charts are plotted.

## Inputs
- symbol \
  Are found in Yahoo Finance, e.g. BTC-USD for Bitcoin or ETH-USD for Ethereum
  
- interval \
  According to yfinance library it can be [1m, 2m, 5m, 15m, 30m, 60m, 90m, 1h, 1d, 5d, 1wk, 1mo, 3mo]
  
- start timestamp
 
- end timestamp \
  can be set to current date by timestamp.now() or any previous date
  
- time zone \
  set UTC by default 
  
  The **moving average** is set to 14.

  The **overbought level** is set to 70 and the **oversold level** is set to 30.
  
## References

https://finance.yahoo.com/markets/crypto/all/ \
https://algotrading101.com/learn/yfinance-guide/ \
https://mayerkrebs.com/relative-strength-index-rsi-in-python/
