# Stock Monitor 股票监控软件

这是一个 C++ 软件，适用于 Windows/Linux, 可以放到服务器上运行，以便在条件触发后自动发邮件提醒。

![Stock Monitor 主界面](https://useful.dpdns.org/assets/stock_monitor/stock_monitor_main.png)

- 支持 1 个第三方数据源：StockHubX, 需要注册获取其API Key, 免费。
- 支持 2 个监控指标：MACD, 均线，均支持自定义参数，支持金叉、死叉、正负、变长/缩短、水上水下监控；均线支持跌破、突破。
- 支持组合指标：同时满足时才触发。
- 支持多个独立组合：任一满足均触发。
- 支持监控多个标的。
- 支持监控A股的股票、ETF场内基金。
- 可免费试用 7 天全功能；7天后仍可继续免费使用，但监控目标数量限制为2；可[购买激活码](https://l.creem.io/stock-monitor)解锁。
- 由于数据源限制，暂不支持美股。
- 由于数据源限制，暂不支持分红股息率指标。

更多信息见：<https://useful.dpdns.org/zh/blog/2026/11/stock_monitor_a_share_alert_with_etf_support/>
