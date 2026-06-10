# docs 页面规划

## 当前仓库定位

当前仓库定位为：**Telegram USDT / TRX 地址查询与监听教程库**。

它和其他可能存在的仓库要区分开：

- 不做纯官网介绍；
- 不做 Telegram 会员服务介绍；
- 不做单独的能量租用价格页；
- 不做泛区块链百科；
- 重点写“用户遇到问题后如何解决”。

## README 主页目标

README 负责承接宽泛搜索意图，例如：

- Telegram USDT 地址查询机器人
- USDT TRX 地址监听
- TRC20 USDT 到账提醒
- Telegram 查 USDT 收支

README 不要写得太长，主要承担导航作用，把用户引导到 docs 的细分教程。

## docs 长尾页面规划

建议按每周 1-2 篇的节奏更新，不要一次性发布太多相似页面。

### 第一阶段：基础问题页

1. `trc20-usdt-address-query.md`  
   主题：如何查询 TRC20 USDT 地址收支记录  
   状态：已生成

2. `telegram-address-monitoring.md`  
   主题：如何在 Telegram 设置 USDT 地址监听提醒  
   搜索意图：到账提醒、地址监控、资金变动提醒

3. `trx-fee-energy-rental.md`  
   主题：TRX 手续费不足怎么办，什么时候需要能量租用  
   搜索意图：TRC20 转账手续费、TRX 不足、能量租用

### 第二阶段：排查问题页

4. `usdt-transfer-not-found.md`  
   主题：USDT 转账查不到记录的原因和排查步骤

5. `wrong-network-usdt-transfer.md`  
   主题：USDT 网络选错后应该如何判断和处理

6. `telegram-bot-wallet-safety.md`  
   主题：使用 Telegram 链上查询机器人时如何保护钱包安全

### 第三阶段：使用场景页

7. `team-payment-address-monitoring.md`  
   主题：团队收款地址如何做到账提醒和流水核对

8. `merchant-usdt-receipt-checklist.md`  
   主题：商户收 USDT 前后的核对清单

9. `telegram-id-query-guide.md`  
   主题：Telegram ID 查询有什么用，如何避免认错人

## 内链规则

每篇 docs 页面底部都应该链接到：

- README；
- 上一篇相关教程；
- 下一篇相关教程；
- 一个安全提醒页面。

这样可以让用户和搜索引擎都更容易理解页面之间的关系。

## 标题写法

建议标题用“问题 + 解决路径”，不要只堆关键词。

推荐：

- TRC20 USDT 地址查询教程：如何查看收款和转账记录
- USDT 转账查不到怎么办：从网络、地址和确认状态排查
- TRX 不足无法转 USDT：手续费和能量租用的区别

避免：

- USDT查询_USDT查询机器人_USDT地址查询_USDT监听
- 最好用的USDT机器人
- 全网第一TRX能量租用机器人
