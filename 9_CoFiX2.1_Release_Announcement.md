CoFiX v2.1 Release Announcement

CoFiX v2.1 has released on 2021-07-29 09:00+UTC

Compared to v2.0, v2.1 has made the following adjustments:
1. Added anchor pool function to enable 1:1 exchange rate among stablecoins, and the token obtained by the exchange is used as transaction fees. Two anchor pools, ETH-PETH and USDT-PUSD-USDC are launched in this update. LP can provide an asset supported by the anchor pool to make market.
2. Added CoFi-ETH binary pool support, and adjusted the existing binary pool fund ratio in the previous version. See the parameter table for details.
3. Adjusted the frequency of market making mining. See the parameter table for details.
4. Supported a variety of assets to repurchase CoFi, and at the same time adjusted the repurchase limit parameters, see the parameter table for details.
5. Introduced the modified volatility for price correction, so as to maximize the protection of LP's assets.
6. The contract structure and interface have been optimized and the contract address will be announced after the upgrade.

## Contract Addresses

### 2021-07-29@mainnet
| Name | Interfaces | mainnet |
| ---- | ---- | ---- |
| usdt | IERC20 | 0xdAC17F958D2ee523a2206206994597C13D831ec7 |
| hbtc | IERC20 | 0x0316EB71485b0Ab14103307bf65a021042c6d380 |
| peth | IERC20 | 0x53f878Fb7Ec7B86e4F9a0CB1E9a6c89C0555FbbD |
| pusd | IERC20 | 0xCCEcC702Ec67309Bc3DDAF6a42E9e5a6b8Da58f0 |
| usdc | IERC20 | 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |
| nest | IERC20 | 0x04abEdA201850aC0124161F037Efd70c74ddC74C |
| nestPriceFacade | INestPriceFacade, INestQuery | 0xB5D2890c061c321A5B6A4a4254bb1522425BAF0A |
| cnode | IERC20 | 0x558201DC4741efc11031Cdc3BC1bC728C23bF512 |
| cofi | IERC20 | 0x1a23a6BfBAdB59fa563008c0fB7cf96dfCF34Ea1 |
| cofixGovernance | ICoFiXGovernance | 0xa0376c279940b26d1D8D03eaB5a3d8bD3F6b0DD4 |
| cofixDAO | ICoFiXDAO | 0x2Cf06Aa521DD979Bc1b50ce44590A09db21d6A74 |
| cofixRouter | ICoFiXRouter | 0x57F0A4ef374B35eb32B61Dd8bc68C58e886CFC84 |
| cofixVaultForStaking | ICoFiXVaultForStaking | 0x7Bd4546DEdB397a0f0D7593A7Fa7f2Ceb3ff32E6 |
| cofixController | ICoFiXController | 0x8eFFbf9CA7dB20481cE9C25EA4B410b3B835D70E |
| CoFiXPair-usdt | ICoFiXPair, ICoFiXERC20 | 0xFa8055B3e0C36605bB31e23bC565C31eb3Dca386 |
| CoFiXPair-hbtc | ICoFiXPair, ICoFiXERC20 | 0xd312E8374fF2B0260A32aF5f91BA8d8EaFAE856B |
| CoFiXPair-nest | ICoFiXPair, ICoFiXERC20 | 0x2FA6F2d5e42630e872cD0F33C69D1c2708FF79Fd |
| CoFiXPair-cofi | ICoFiXPair, ICoFiXERC20 | 0x711EA25b70Bb580a7cb19DeBd0ab40A016c3fCbb |
| CoFiXAnchorPool-eth | ICoFiXAnchorPool | 0xD7E54D936ca1e7F0ed097D4Ec6140653eC60f85D |
| CoFiXAnchorPool-usd | ICoFiXAnchorPool | 0x31Aa5da47Cf6FBB203531D88e3FC47d46AE6D46b |
| xeth | ICoFiXERC20 | 0xB6e9B1D8814DA83a663832822765fc4d4008Fd97 |
| xpeth | ICoFiXERC20 | 0xAB53A40e3153901c761CE55EfA5F0789dbD5F047 |
| xusdt | ICoFiXERC20 | 0x172b260F92d1A0661e9888918a19154E99E0B9f0 |
| xpusd | ICoFiXERC20 | 0x2b06Af945F1c18A6bf02ac6E401Fd251d9FfdBCf |
| xusdc | ICoFiXERC20 | 0xF5beBE517eb95557CBcFd19a2BAfa8e9fC50C5EE |

CoFiXCore

2021.07.29