# CoFiX v2.0 Parameter Change Report

The repurchase quota is changed from 50 to 100 per block, and the cumulative upper limit is changed to 30,000.

The address of CoFiXDAO will changed.

Upgrade time: Jun-12-2021 06:00 AM +UTC

github: https://github.com/Computable-Finance/CoFiX-V2.0

# Parameter List

| Name | Value |
| ---- | ---- |
| Oracle price timeout | 3600 seconds |
| Oracle price deviation limit | ±10% |
| θ | 0.002 |
| VOL-BASE | 50 |
| CGama-usdt | 1 |
| CGama-hbtc | 1 |
| CGama-nest | 100 |
| Mining speed for trader | 0.1CoFi/eth |
| Trade mining percent for CNode | 10% |
| Mining speed for CNode | 0.2CoFi/block |
| Mining speed for LP | 1.8CoFi/block |
| LP-nest speed weight | 50% |
| LP-usdt speed weight | 25% |
| LP-hbtc speed weight | 25% |
| ETH/USDT ratio | 1:3000 |
| ETH/HBTC ratio | 20:1 |
| ETH/NEST ratio | 1:20000 |
| CoFi repurchase speed | 100CoFi/block |
| CoFi repurchase limit | 30000CoFi |
| Oracle price deviation limit for repurchase | ** ±10% ** |
| Block time | 14 seconds |
| k formula | K=(0.00002*T+40*σ)*γ(σ) |
| Impact cost | α=0，β=0.00002 |


CoFiXCore

2021.06.12
