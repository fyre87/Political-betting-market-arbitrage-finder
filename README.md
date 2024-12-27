# Political-betting-market-arbitrage-finder

Political betting markets are not efficient markets, and arbitrage opportunities seem to routinely pop up between various popular political betting websites. 

This bot uses a lightweight language model to compare all of the active prompts across [**PredictIt**](https://www.predictit.org/) and [**Polymarket**](https://polymarket.com/), then uses real time data to find arbitrage opportunities net of the fees on both sites. 


## Example output
```
Found arbitrage in: Will Kamala Harris win the 2024 US presidential election?
  Best YES Polymarket: $0.395
  Best NO  Polymarket: $0.606
  Best YES Predictit:  $0.52
  Best NO  Predictit:  $0.5
  Shares   Purchased:   1117.31843575419
  YES Profit (given $1000): $128.49. Implied yearly return: 5511227.17%
  NO  Profit (given $1000): $51.40. Implied yearly return: 9142.62%
    YES Profit % after 5% withdrawl fee: 5511227.17%
    NO  Profit % after 5% withdrawl fee: 13.43%
```
