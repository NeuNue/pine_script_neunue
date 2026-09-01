# NeuNue 的 Pine Script 工具库

TradingView Pine Script v6 指标与工具集合，由 **NeuNue** 开发维护。关注**量价、资金流与关键价位**：从买卖压力（CVD）的背离与吸筹，到基于 1 小时证据的支撑 / 阻力热力图。每个脚本独立成册，均有单独的中文说明页。

> ⚠️ **免责声明**：本仓库内所有脚本、指标仅供学习与研究使用，**不构成任何投资建议**。据此操作，风险自负。

[![Pine Script v6](https://img.shields.io/badge/Pine%20Script-v6-00B55D?style=flat&logo=tradingview&logoColor=white)](https://www.tradingview.com/pine-script-docs/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Bilibili](https://img.shields.io/badge/Bilibili-445605-00A1D6?style=flat&logo=bilibili&logoColor=white)](https://space.bilibili.com/445605)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/MwUQFkH4Cx)

---

## 🔗 社区与交流

- **Bilibili**：<https://space.bilibili.com/445605>
- **Discord 社区**：<https://discord.gg/MwUQFkH4Cx>
- **QQ 群**：`1083130056`

---

## 📁 脚本索引

| 脚本 | 文件夹 | 适用情况 | 一句话说明 |
| --- | --- | --- | --- |
| [CVD Z-Score（累积成交量差值 Z 分数）](cvd_zscore/README.md) | [`cvd_zscore/`](cvd_zscore/) | 主流加密货币、A 股；15 分钟 / 1 小时 | 基于量价关系，使用 Z 分数量化买卖盘，识别吸筹、衰竭与量价背离 |
| [关键价位热力图（美股 + 加密货币）](key_level_heatmap/README.md) | [`key_level_heatmap/`](key_level_heatmap/) | 美股大盘股与高流动性 ETF，或 BTC、ETH、SOL 等主流币合约 / 现货；1 分钟～1 小时图表 | 基于已收盘 1 小时证据，把支撑 / 阻力合并为带强度的热力区间；含美股版与 7×24 加密货币版 |

## 🚀 使用方式

1. 在仓库中找到对应脚本文件夹，打开其 README 查看适用情况与参数说明；
2. 复制文件夹内的 `.pine` 文件全部内容；
3. 在 TradingView 打开 Pine 编辑器，粘贴，点击"添加到图表"。

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源。
