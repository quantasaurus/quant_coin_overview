# Quant Tools Overview

## Provide tooling and visualization for algorand
- [vanity wallet generator](https://github.com/quantasaurus/vanity_wallet_generator)
- various wallet scraping analytics
- viz tools
- strategy backtesting framework over past 7 days 
- [strategy backtesting framework for 6 months](https://github.com/quantasaurus/strategy_backtest_long)
- Accurate price impact quotes
- Wallet message scraping

## Produce generalized trading bots for users
  ### Types of bots:
  - [DCA](https://github.com/quantasaurus/DCA_bot) - buys a set amount of ASA at set time interval (e.g. spend 10 algos every hour on Headline)
  - Nibbler - buys a set amount of ASA when price drops X%
  - Buy the dip - DCA bot that compares price against previous day and buys dip if present
  - Speedy launch buy - Bot meant to quickly make one buy for new pool/token launch
  - SMA 50/200 Buy/Sell - Uses 50 and 200 SMA for buy/sell triggers.  
  - Grid bot - If price < x then buy; if price > y then sell
  - Deadman bot - Immediate dumpage when trigger met
  - Iceberg Seller - Splits sell order into chunks and sells at specified interval
  - Follower Bot - Set another wallet to watch and follower bot will make the same trades
  - Revenge Bot - Set another wallet to watch and as soon as they buy ASA this bot sells same ASA
  
## Future bot competitions
  - Speed (release a test ASA and pool.  first bot to buy wins all entry fees)
  - Trading (release a test ASA and pool.  Bot to make most profit wins all entry fees)


  
