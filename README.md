# 币迹 CoinTrace

**追踪每一笔持仓，冷钱包也不迷路。**

一个完全运行在浏览器本地的加密货币持仓追踪工具。无需注册、无需登录、数据不上云。

![Static Badge](https://img.shields.io/badge/本地运行-无需登录-6366f1)
![Static Badge](https://img.shields.io/badge/数据-本地存储-22c55e)
![Static Badge](https://img.shields.io/badge/行情-CoinGecko-f59e0b)
![Static Badge](https://img.shields.io/badge/License-MIT-blue)

---

## ✨ 功能

- 📊 **Excel 导入** — 支持 `.xlsx / .xls / .csv`，自动识别日期、花费、数量列，支持人民币 / 美元等多种货币换算
- 💹 **实时行情** — 接入 CoinGecko，覆盖 45+ 主流币种，每 60 秒自动刷新
- 📈 **盈亏追踪** — 自动计算平均成本、当前市值、盈亏金额与百分比
- 🔐 **冷钱包友好** — 买入后转移到冷钱包不影响成本记录
- 🌙 **日夜模式** — 一键切换，偏好自动保存
- ➕ **自定义行情列表** — 增删任意币种，支持搜索所有 CoinGecko 上的币
- 💾 **本地存储** — 数据保存在浏览器，支持导出 / 导入 JSON 备份

---

## 🚀 使用方式

**方法一：直接下载使用（推荐）**

1. 下载 [`index.html`](./index.html)
2. 双击用浏览器打开
3. 完成 ✅

**方法二：在线访问**

👉 [cointrace.pages.dev](https://cointrace.pages.dev) *(即将上线)*

---

## 📥 Excel 导入说明

支持从交易所导出的 Excel 记录，典型格式如下：

| 日期 | 花费 | 个数 | 单价 |
|------|------|------|------|
| 2024-11-26 | 59.99 | 78.51 | 0.764 |

导入时可分别选择「花费列」和「单价列」的货币（人民币 / 美元等），系统自动换算为 USD 统一展示。

---

## 🛠 技术栈

| 项目 | 说明 |
|------|------|
| 纯 HTML / CSS / JS | 零依赖，无需构建 |
| [SheetJS](https://sheetjs.com/) | Excel 文件解析 |
| [CoinGecko API](https://www.coingecko.com/api) | 实时价格数据（免费） |
| localStorage | 本地数据持久化 |

---

## 🤝 参与贡献

欢迎提 Issue 和 PR！

- 发现 Bug → [提 Issue](../../issues)
- 想要新功能 → [讨论区](../../discussions)
- 直接改代码 → Fork 后提 PR

**常见改进方向：**
- [ ] 手机端适配
- [ ] 多钱包 / 多账户管理
- [ ] 卖出记录与已实现盈亏
- [ ] 图表（持仓占比、成本走势）
- [ ] 多语言支持

---

## 📄 License

[MIT](./LICENSE) — 随便用，随便改，开心就好。

---

<p align="center">
  <sub>数据来源：CoinGecko｜本工具不构成投资建议</sub>
</p>
