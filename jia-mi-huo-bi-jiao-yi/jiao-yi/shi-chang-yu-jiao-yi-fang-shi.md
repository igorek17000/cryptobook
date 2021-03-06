# 市场与交易方式

## 现货市场

### 币币现货交易

目前通常进行数字资产交易的方式为：

> 1. 法币购买稳定币（USDT锚定美元，理论上1USDT=1美元）
> 2. 使用USDT作为基础货币进行比特币等数字资产

这种以一种币购买另一种币的方式被称作“<mark style="color:blue;">**币币交易**</mark>”或“<mark style="color:blue;">**现货交易**</mark>”。

### **币币**杠杆交易

杠杆交易是一种使用第三方提供的资金进行资产交易的方式。从本质上讲，杠杆交易对交易结果进行了放大，使交易者能够在盈利交易中获得更大的利润。这种扩大交易结果的能力使得杠杆交易在低波动性市场尤其是国际外汇市场中尤其受欢迎。

杠杆交易被广泛用于股票、现货和加密货币市场。在传统市场中，杠杆交易中借入的资金通常由投资经纪人提供。然而，在加密货币交易中，该部分资金通常由其他交易者提供，他们根据市场供需对杠杆交易收取一定的利息。除此之外，还有一部分加密货币交易所也为其用户提供杠杆交易。

{% hint style="info" %}
#### **币币杠杆可以做什么？** <a href="#h-er-bi-bi-gang-gan-ke-yi-zuo-shen-me" id="h-er-bi-bi-gang-gan-ke-yi-zuo-shen-me"></a>

* 看涨某币种行情，您可以利用本金作为保证金加持杠杆借币，本金和借来的币都“买入”该币种来开多仓，待行情上涨涨至理想价位“卖出”该币种，还清借来的币及利息后，剩余部分为赚取的“多向”收益；
* 看跌某币种行情，您可以利用本金作为保证金加持杠杆借该币种“卖出”来开空仓，待行情下跌至理想价位再“买入”该币种，还清借的该币种以及利息，剩余部分就是赚取的“空向”收益。
* 目前上线的统一账户将币币杠杆操作进行了精简，将借币、买币/卖币、卖币/买币、还币四步操作精简至两步操作：买入/卖出，平仓。单币种保证金模式下进行杠杆交易如果产生借币，无论是全仓还是逐仓，只要平仓就可以自动还币还息；跨币种保证金模式，如果借币产生负债，当平仓后，利息会计入负债，需要在币币交易下买币才可还清负债。
{% endhint %}

### 杠杆代币

杠杆代币本质上是一种带有杠杆功能的代币，是一种衍生品，旨在提供标的资产的杠杆倍数报酬。如同一般代币，杠杆代币可以在现货市场上被用户买卖交易，每个杠杆代币的背后都对应了一篮子的币安永续合约持仓。杠杆代币价格将时刻跟踪永续合约市场的价格变化，并随之产生杠杆水平的涨跌。 与杠杆交易不同，您可以在不需要任何抵押品、维持保证金和担心清算风险的情况下进入杠杆头寸。尽管用户无需担心清算风险，但由于杠杆代币的风险敞口来是从永续合约得来，这也意味着杠杆代币会受永续合约的价格变动、溢价、资金费率等因素影响。

### 闪兑

通过<mark style="color:blue;">**闪兑交易**</mark>，用户可以在几秒内将他们持有的数字货币兑换为另一种数字货币。

不同于订单撮合模式，闪兑使用的是柜台报价模式，不产生任何交易手续费，不存在滑点，因此闪兑价格与现货盘口价格存在一定的差价。

具体模式如下

1. 首先用户向柜台进行询价
2. 柜台会根据当前市场提供一个有竞争力的价格
3. 如果用户接受报价，即可进行快速交易

### :cherries:合约示例

|            现货产品 |   Binance   |    OKX   |
| --------------: | :---------: | :------: |
|        BTC-USDT |   BTCUSDT   | BTC-USDT |
| 高达4倍做多 BTC 杠杆代币 |  BTCUPUSDT  |          |
| 高达4倍做空 BTC 杠杆代币 | BTCDOWNUSDT |          |

## 期货市场

### 期货合约交易

在数字货币行业，期货合约市场是一个快速增长的行业，每月产生数万亿的交易量。与股票期权或商品期货合约一样，加密货币合约可以防止加密货币的波动和不利的价格变动。加密货币合约也是投资者推测加密货币未来价格的工具，并可用于对冲加密货币的价格变化。

#### <mark style="color:blue;">**交割合约**</mark>和<mark style="color:blue;">**永续合约**</mark>

期货合约根据有无到期交割日提供<mark style="color:blue;">**交割合约**</mark>和<mark style="color:blue;">**永续合约**</mark>两种合约产品。

> * 永续合约没有交割日，永不到期，因对标的价差回归合理的期望，如看涨方用户更多，看涨方需支付资金费至看跌方，看跌方获得资金费收益；如看跌方用户更多，看跌方需支付资金费至看涨方，看涨方获得资金费收益。
> * 交割合约具有交割日期，合约到期且未平仓时，不论合约带来盈利情况如何，都会按照指数价格最后一小时的算术平均价进行平仓，

不同交易所期货交割合约的数量不同。OKX根据交割日期，交割合约又分为当周、次周、当季、次季交割合约。

#### <mark style="color:blue;">U本位合约</mark>和<mark style="color:blue;">币本位合约</mark>

在交割合约和永续合约这两个大的模块中又可以根据保证金类型，细分为<mark style="color:blue;">U本位合约</mark>和<mark style="color:blue;">币本位合约</mark>。

|       |    U本位合约   |      币本位合约      |
| ----: | :--------: | :-------------: |
|   保证金 | USDT, BUSD | 加密貨幣（如BTC, ETH） |
| 保证金模式 |    逐仓/全仓   |      逐仓/全仓      |
| 混合保证金 |      是     |        否        |

关于U本位和币本位的更多比较请参考《[什麼是U本位合約和幣本位合約](https://www.binance.com/zh-CN/support/faq/85eac2bba0b342819122dc9bd4745e9b)》。

### :cherries:合约示例

|      币本位永续      |      BTCUSD     |   BTC-USD-SWAP  |
| :-------------: | :-------------: | :-------------: |
|      币本位当周      |                 |  BTC-USD-220701 |
|      币本位次周      |                 |  BTC-USD-220708 |
|      币本位当季      |  BTCUSD\_220930 |  BTC-USD-220930 |
|      币本位次季      |  BTCUSD\_221230 |  BTC-USD-221230 |
|      币本位永续      |     BTCUSDT     |                 |
|      U本位永续      |                 |   BTC-USDT-SWAP |
|      U本位当周      |                 | BTC-USDT-220701 |
|      U本位次周      |                 | BTC-USDT-220708 |
|      U本位当季      | BTCUSDT\_220930 | BTC-USDT-220930 |
|      U本位次季      |                 | BTC-USDT-221230 |
| 高达4倍做空BTC杠杆代币永续 |    BTCDOMUSDT   |     BTC-USDT    |

## 期权

期权指的是期权持有方在未来的某个时间段内或者某个时间点可以行使一定的权利，按照合约规定，期权买方可以选择执行权利（对买方有利），也可以选择放弃权利（对买方不利）；而期权的卖方有配合买方的义务。

期权相关基础知识介绍请参考《[什么是期权](https://www.binance.com/zh-CN/support/faq/bee2427f6a594741858d51e91a67e30d)》。

### 看涨期权与看跌期权

&#x20;期权合约可分为看涨期权以及看跌期权两大类型：

* 看涨期权：未来某个时间段内或者某个时间点可以以特定的价格买入特定数量的某种商品
* 看跌期权：未来某个时间段内或者某个时间点可以以特定的价格卖出特定数量的某种商品

### 欧式期权与美式期权

根据行权时间可以将期权分为欧式期权与美式期权。

* 美式期权：它能允许交易者在到期日前的任何时间执行权。
* 欧式期权：只能在到期日选择行权。

币安美式期权与传统期权相比，币安期权的到期日的时间范围较短，从5分钟到1天不等。 传统期权通常由于多重执行价格而缺乏流动性, 而币安期权只有一个行权价格，相当于币安合约的合约价格，因此币安期权可以提供更高的流动性。 在币安期权，交易者只能是买方，而不是卖方，因为币安是唯一的此期权发行人。因此，在币安期权是没有交易委托账本关。期权可被行权的方式分为两种：一是当交易者在期权到期日之前的任何时候行权该期权；二是该期权到期时，期权将被自动行权。交易者最大损失是他买入期权的权利金。损平价格是行权价格加上或减去溢价（取决于是买入还是卖出）。

币安欧式期权合约是统一使用USDT报价以及结算的期权合约产品；允许用户作为买方直接买入期权，同时也允许用户作为卖方发行期权；由于期权买方后续可选择行权，所以期权的卖方需要冻结保证金，保证期权买方在行权阶段能顺利执行合约权利； 而欧式期权的卖方收益则来源于期权费用，如买入期权后，到期由于最后标的资产价格与行权价格的价差使得期权持有方并没有收益，期权持有方会选择放弃行使权利，期权卖出方将不再需要支付额外费用，同时系统将退还保证金；





