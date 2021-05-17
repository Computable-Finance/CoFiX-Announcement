# CoFiX v2.0 released on Ethereum mainnet

Upgrade time: May-17-2021 12:00 AM +UTC

github: https://github.com/Computable-Finance/CoFiX-V2.0

## Contract Addresses
|       Contract       |                  Address                   |
| :------------------: | :----------------------------------------: |
| USDT | 0xdAC17F958D2ee523a2206206994597C13D831ec7 |
| HBTC | 0x0316EB71485b0Ab14103307bf65a021042c6d380 |
| NEST | 0x04abEdA201850aC0124161F037Efd70c74ddC74C |
| WETH | 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2 |
| NestPriceFacade | 0xB5D2890c061c321A5B6A4a4254bb1522425BAF0A |
| NestVote | 0xDa52f53a5bE4cb876DE79DcfF16F34B95e2D38e9 |
| CoFiToken | 0x1a23a6BfBAdB59fa563008c0fB7cf96dfCF34Ea1 |
| CoFiXNode | 0x558201DC4741efc11031Cdc3BC1bC728C23bF512 |
| CoFiXV2Factory | 0x39816B841436a57729723d9DA127805755d2CB51 |
| CoFiXV2Router | 0x72A63055b9AA997A4311D0D068170e38F5455b82 |
| CoFiXV2Controller | 0xdE9972fe2567b7eEb3C015D7DCAefA8580877f7d |
| CoFiXV2VaultForLP | 0x618B7b93b07Bf78D04B2e8FB2B1C3B48049F8ED5 |
| CoFiXV2VaultForTrader | 0xb29A8d980E1408E487B9968f5E4f7fD7a9B0CaC5 |
| CoFiXV2VaultForCNode | 0x3881292cE52AeD0EdAFF1AC7A40DA12AB2453B84 |
| ETH/USDT V2Pair | 0x9DF98Ef91148fb0F2b9321D07f57C9bD0Ff8c381 |
| ETH/HBTC V2Pair | 0xe1162b20847117ACcB66C46C9bFabBa45c44bD4d |
| ETH/NEST V2Pair | 0xB8F9218536870eeC443aEBF7C15dE59E535d0e0a |
| CoFiXV2StakingRewards ETH/USDT Pair | 0x3C41B1bEAf0a3c0929233009bb49cF00Fd2E8D07 |
| CoFiXV2StakingRewards ETH/HBTC Pair | 0x50B48B17ee1E4d96113aaD5e3fa561495FAA23eB |
| CoFiXV2StakingRewards ETH/NEST Pair | 0x74246388De82e5c40A01F640c7cab678ac1C5C13 |
| V2CNodeStakingRewards CNode | 0x810c0379d3215c4109F203E1C802A09008f7EbA2 |
| CoFiXDAO | 0x278f5d08bEa1989BEfcC09A20ad60fB39702D556 |

# The specific modifications to CoFiX v2.0 are as follows：

1. Add hedging mining to solve the problem that users require manual hedging in v1.0. After the upgrade, liquidity providers can go on market-making with almost no impermanent losses.

2. Optimize the risk calculation algorithm and propose dynamic calculable K values and more refined hedging costs to improve the overall security of the system.

3. Eliminating mining of ordinary transactions. Only hedging transactions can be rewarded with CoFi Token.

4. the dividend model will be changed to a resale model, and the resale function will be added in later versions.

5. For pools that can be mined for hedging transactions, LP needs to send bilateral assets when providing liquidity and what to be retrieved are also bilateral assets.

After the upgrade, users will not be able to use v1.0 and need to manually withdraw funds from the old contract to participate in market-making again. v2.0 does not support resale temporarily, the team will support the resale function of CoFi Token in the subsequent version as soon as possible.

Computable Finance Protocol CoFiX is a decentralized exchange based on Ethereum with investment from Coinbase Ventures, Dragonfly Capital Partners and Huobi Capital. CoFiX solves the current problem of the low funding utilization and high slippage of DEX through its original “risk-computable” model.

As a member of the NEST eco-projects, CoFiX will provide a channel for price discovery, collateral settlement, etc for other eco-projects such as Parasset and ultimately empower the entire DeFi eco-system.


CoFiXCore

2021.05.17
