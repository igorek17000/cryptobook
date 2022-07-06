# 保证金

在虚拟合约市场上，交易者只需根据合约价格，按一定比率交纳少量资金作为履行合约的财力担保，便可参与合约的买卖，这种资金就是虚拟合约保证金。

\
欧易提供两种保证金制度，全仓保证金与逐仓保证金。

全仓模式下：开仓保证金=面值张数／最新[标记价格](https://www.okx.com/academy/zh/how-to-understand-the-latest-transaction-price-index-price-and-mark-price-cn?channelFlag=ACE503633)／[杠杆](https://www.okx.com/academy/zh/how-to-choose-digital-currency-contract-leverage-and-distinguish-between-open-positions-and-full-positions-cn?channelFlag=ACE503633)，用户的开仓保证金将随价格变化而变动。

逐仓模式下：开仓保证金=面值张数／开仓均价／[杠杆](https://www.okx.com/academy/zh/how-to-choose-digital-currency-contract-leverage-and-distinguish-between-open-positions-and-full-positions-cn?channelFlag=ACE503633)，开仓保证金固定不变。

## 梯度保证金

即梯度维持保证金率制度，维持保证金率是用户维持当前仓位所需的最低保证金率，当保证金率小于等于用户当前所需维持保证金率+平仓手续费率时，即触发爆仓。

[逐仓](https://www.okx.com/academy/zh/how-to-choose-digital-currency-contract-leverage-and-distinguish-between-open-positions-and-full-positions-cn?channelFlag=ACE503633)：保证金率=（固定保证金+未实现盈亏）／仓位价值，仓位价值=面值张数／最新[标记价格](https://www.okx.com/academy/zh/how-to-understand-the-latest-transaction-price-index-price-and-mark-price-cn?channelFlag=ACE503633)

[全仓](https://www.okx.com/academy/zh/how-to-choose-digital-currency-contract-leverage-and-distinguish-between-open-positions-and-full-positions-cn?channelFlag=ACE503633)：保证金率=（余额+已实现盈亏+未实现盈亏）／（仓位价值+挂单冻结保证金杠杆倍数），仓位价值=面值\*张数／最新[标记价格](https://www.okx.com/academy/zh/how-to-understand-the-latest-transaction-price-index-price-and-mark-price-cn?channelFlag=ACE503633)

\
为防止大仓位爆仓时对市场流动性造成冲击，产生大的穿仓损失，欧易实行阶梯维持保证金率制度。即，用户的持仓仓位越大，维持保证金率越高，用户可选的最高杠杆倍数越低。



