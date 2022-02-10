# fear and greed dapp

- get fear and greed score from an oracle (chainlink?)
- if over threshold (70?) AND bitcoin balance > 0 then sell BTC
- if under threshold (30?) AND DAI balance > 0 then buy BTC
- repeat this each dat/hour/[whatever period]
- be a smart contract deployable by a user & fundable via public address. corresponding private key would enable releasing funds.

notes:
- buy/sell via paraswap
- use [gelato](https://www.gelato.network/) to simulate cron
