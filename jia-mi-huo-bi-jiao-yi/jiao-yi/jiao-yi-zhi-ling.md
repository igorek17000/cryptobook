# 交易指令

## 市价指令

在您下单后，市价单将以市场现价尽快执行。您可以使用它来下达买入和卖出订单。

有关如何下达市价单，欲知详情，敬请参阅[《市价单是什么以及如何下单》](https://www.binance.com/cn/support/faq/12cba755d6334ad98ced0b66ddde66ec)。

## 限价指令

限价单是按特定限价在订单簿中挂出的订单。设置限价单时，可以选择最高买入价格或最低卖出价格。当市价达到或优于限价后，交易平台将自动推动限价单成交。

在大多数情况下，限价单会降低手续费，因为您作为挂单方而不是吃单方进行交易。

有关限价单，欲知详情，敬请参阅[《限价单是什么？》](https://academy.binance.com/cn/articles/what-is-a-limit-order)。

### **只做 Maker (Post only) 订单**

下限价单时，您可以勾选 \[只做 Ｍaker] 的选项，这样您的订单将不会立即在市场中执行。它将会在订单簿上以Maker 订单的形式存在，但是不会和已经在订单簿上的订单匹配。只做 Maker 订单会为市场增加流动性。以吃单方执行订单时，您将只需支付Maker 费，不会支付Taker费。\
但是，如果您想要立即执行部分订单，例如，您想要以高于目前市价的价格购买资产，系统将会在您下单时自动取消您的订单。

### **生效时间订单**

生效时间指的是您的订单在被执行或过期之前维持有效的时间。这样可以让您更具体的掌握时间参数，您可以在下单时自订时间。币安提供 GTC (有效直到取消)、IOC (立即成交或取消) 或 FOK (全部成交或取消) 等订单选项：

* GTC (有效直到取消)：订单将维持有效到成交或被您取消。
* IOC (立即成交或取消)：以可用价格及数量立即尝试成交全部或部分订单，然后取消剩馀未成交的订单部分。如果您下单时所选择的价格没有可供应的数量，订单将会立即被取消。请注意，此订单类型不支持冰山委托。
* FOK (全部成交或取消)：订单必须立即完全成交 (全部成交)，否则将被取消 (完全取消)。请注意，此订单类型不支持冰山委托。

## 止盈止损

### 止损单

止损单是在市场达到您设定的止损价时出发的市价单。一旦代币价格达到您设定的止损价，它就是一个以市场价买入和出售代币的订单。

一旦触发，止损单就会变成市价单，并以当前市场价执行。若没有达到止损价，您的订单就不会被执行。如果市场走势不利于您的仓位，您可以使用卖出止损单来最大程度地减少潜在损失。它们也可以用作“止盈”订单来退出仓位并保护未实现的利润。买入止损单可用来以较低的价格进入市场。

限价单和止损单之间的区别就在于，前者将以您设定的限价（或更高价格）执行订单，而后者将以当前市场价（作为市价单）执行订单。但要注意的是，如果市场价变化过快，您的订单的成交价格可能会显著不同于触发价格。

### 限价止损单 <a href="#header-4" id="header-4"></a>

限价止损单结合了止损单和限价单的功能。一旦达到止损价，它将自动触发限价单。订单仅在市场价达到限价（或更高价格）时达成。如果您没有时间密切监控您的投资组合，可以考虑使用限价止损单来限制您在交易中可能遭受的损失。

在下达限价止损单时，您必须定义两个价格：止损价和限价。限价止损单和限价单之间的区别就在于，前者只会在达到止损价时下达限价单，而后者会立即在订单簿中下达订单。

例如，如果币安币(BNB)目前的交易价格是600美元，您以590的止损价下达了卖出限价止损单。这意味着，如果币安币(BNB)价格降至590美元，系统将自动以您制定的限价设置卖出限价单（例如585美元），您的订单可能以585美元或更高的价格卖出。然而，您的订单最终执行与否无法保证。若市场价变化太快，很有可能您的订单依然不会执行。

### 限价止盈止损单

限价止盈止损单设有止盈止损价和限价。您可以设置可接受的最小利润金额或您愿意在交易中花费、损失的最大金额。当达到触发价格时，将自动下达限价单。&#x20;

限价止盈止损单是控制交易损失的好工具。例如，比特币的交易价格为40,000美元，而您设置了限价止盈止损单，将止盈止损价设定为39,500美元，将限价设定为39,000美元。当价格从40,000美元跌至39,500美元时，将下达39,000美元的限价单。

## OCO订单

二选一(OCO)订单是限价单与限价止盈止损单的组合。您同时下达两个订单，一旦触发一个订单，另一个订单就会被取消。因此，只能执行其中一个订单。&#x20;

例如，比特币的价格为40,000美元。当价格达到39,000美元时，您可以使用OCO订单买入1比特币，或在价格上涨至41,000美元时卖出。其中一个订单将优先执行，这意味着第二个订单将自动取消。

有关OCO订单，欲知详情，敬请参阅[《OCO订单是什么？》](https://academy.binance.com/cn/articles/what-is-an-oco-order)。

## 跟踪委托单

现货跟踪止盈止损单让您以偏离市场价格的特定百分比下达预设订单。当市场波动时，这类订单特别有效，当交易没有朝着有利方向移动时，它可以帮您限制损失并保护收益。

&#x20;请注意，跟踪止盈止损单不会转向另一个方向。当价格以指定的百分比向相反方向变化时，它将以市场价格平仓或退出交易。

有关如何下达跟踪止盈止损单，欲知详情，敬请参阅[《跟踪止盈止损单是什么》](https://www.binance.com/cn/support/faq/360042299292)。

## 冰山单

冰山是一种大额订单拆分后分批挂单的策略。用户在进行大额交易时，为避免对市场造成过大冲击，需要将大单委托自动拆为多笔委托。这个策略会根据当前的最新买一/卖一价和用户设置的价格距离来计算委托价格，然后自动进行小单委托来挂单交易，在上一笔委托被全部成交或最新价格明显偏离当前委托价时，自动重新进行委托。

## 计划委托

计划委托是策略委托的一种。用户可以预先设置触发价格和委托价格，当市场价格到达触发价格时，系统会按委托价格自动下单。用户利用该委托可达到止盈止损平仓或是趋势开仓的目的。计划委托不会冻结用户的保证金或仓位。（这是和“止盈止损委托”唯一的区别）

## **只减仓委托**

只减仓订单只允许客户减少头寸，即下单数量无法大于持仓可平数量，否则下单会失败。此功能只在单向持仓模式下使用。

* 只减仓订单只允许客户执行仅减少当前头寸的买入或卖出订单。
* 只减仓订单不能用于在与现有头寸相同的方向上开仓（如果原始头寸为多头，则不能开更多多头，反之亦然）。
* 在下单止盈止损、仓位止盈止损场景中，止盈止损默认为只减仓类型，因此当下单数量超出仓位可平数量时，可能存在触发失败的情况。