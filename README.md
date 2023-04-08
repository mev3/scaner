# MEV DATA SCAN

通过Trace信息来搜集MEV相关交易，由于是通过Trace搜集，即使失败的交易可以被捕获到，相比 https://eigenphi.io/
，交易信息会更加全面。

## Sandwich Scan

Sandwich Scan 可以收集三明治攻击相关的交易信息，不仅可以收集成功的三明治攻击交易对，也可以搜集失败的三明治攻击交易对（如因为买入貔貅代币而无法卖出）。

此外本程序还可以检测买入卖出的Token是否收取交易手续费及收取的比例。

## Flashloan Scan

TODO

## Arbitarage Scan

TODO

## Explorer

TODO
