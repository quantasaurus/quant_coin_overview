# QuantCoin Overview

## Provide tooling and visualization for algorand
- [vanity wallet generator](https://github.com/quantasaurus/vanity_wallet_generator)
- various wallet scraping/viz tools
- backtesting framework over past 7 days 
- Accurate price impact quotes
- Wallet message scraping

## Produce generalized trading bots for users
  ### Types of bots:
  - [DCA](https://github.com/quantasaurus/DCA_bot) - buys a set amount of ASA at set time interval (e.g. spend 10 algos every hour on QuantCoin)
  - Nibbler - buys a set amount of ASA when price drops X%
  - Buy the dip - DCA bot that compares price against previous day and buys dip if present
  - Speedy launch buy - Bot meant to quickly make one buy for new pool/token launch
  - SMA 50/200 Buy/Sell - Uses 50 and 200 SMA for buy/sell triggers.  
  - Grid bot - If price < x then buy; if price > y then sell
  - Deadman bot - Immediate dumpage when trigger met
  - Iceberg Seller - Splits sell order into chunks and sells at specified interval
  
## Hold bot competitions
  - Speed (release a test ASA and pool.  first bot to buy wins.  QuantCoin for entry fee)
  - Trading (release a test ASA and pool.  Bot to make most profit wins.  QuantCoin for entry fee)
  
## QuantCoin Liquidity Automated Trading
  - QuantCoin to be utilized in liquidity pools with assets predicted to increase in value
  - Increase in other asset values also increases QuantCoin value
  - Simple linear regression model at first to pick which assets to provide liquidity for
  - Rebalance possibly daily or as necessary
  
