# CoFiX v2.1 Parameters Changed

The usdt pair is removed, and the parameters of CoFiX v2.1 is adjusted, see the table below for details 

github: https://github.com/Computable-Finance/CoFiX-V2.1

Upgrade time: Aug-31-2021 09:30 AM +UTC

# Parameter List

| Name | Value |
| ---- | ---- |
| Oracle price deviation limit | ±10% |
| θ | 0.002 |
| VOL-usdt | 100 |
| VOL-hbtc | 100 |
| VOL-nest | 5 |
| VOL-cofi | 0.5 |
| Mining speed for trader of binary pool | 0.5CoFi/eth |
| Mining speed for trader of eth anchor pool | ** 0.0CoFi/eth ** |
| Mining speed for trader of usd anchor pool | ** 0.0CoFi/usd ** |
| Trade mining percent for CNode | 10% |
| Mining speed for CNode | 0.2CoFi/block |
| Mining speed for LP | 1.8CoFi/block |
| LP-nest speed | 0.4CoFi/block |
| LP-hbtc speed | 0.2CoFi/block |
| LP-cofi speed | 0.4CoFi/block |
| LP-xeth speed | ** 0.2CoFi/block ** |
| LP-xpeth speed | 0.15CoFi/block |
| LP-xusdt speed | ** 0.2CoFi/block ** |
| LP-xpusd speed | ** 0.15CoFi/block ** |
| LP-xusdc speed | 0.1CoFi/block |
| ETH/USDT ratio | 1 : 2000 |
| ETH/HBTC ratio | 20 : 1 |
| ETH/NEST ratio | 1 : 100000 |
| ETH/COFI ratio | 1 : 2000 |
| CoFi repurchase speed | 500CoFi/block |
| CoFi repurchase limit | 150000 |
| Oracle price deviation limit for repurchase | ±10% |
| Block time | 14 seconds |
| k formula | K = 0.002 + 2 * D^0.5 * σ |
| Impact cost | C = vol * 0.001 |

CoFiXCore

2021.08.31
