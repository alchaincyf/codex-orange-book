[English README](README.md) | **中文**

<p align="center">
  <img src="banner.png" width="55%" />
</p>

# OpenAI Codex 从入门到精通

> 橙皮书系列 · 花叔 著 · v2.0.0（2026年5月）

OpenAI Codex 的完整实战手册，覆盖**五种形态**：CLI、桌面 App、Cloud、IDE 扩展、Chrome 扩展。从安装到独立构建产品，一周内带你从零起步。

作者从未手写过一行代码，却用 AI 做出了 App Store 付费榜第一的产品、出版了 8 本技术书、运营着 30 万粉丝的自媒体矩阵。

## v2.0.0 改了什么

v1 是 2026 年 4 月 14 日完稿的。一个月后 Codex 大幅变化，必须出 v2：

- **GPT-5.5** 空降默认模型：SWE-bench Verified 82.6%、Terminal-Bench 2.0 82.7%、输出 token 降 40%
- **形态从四种变五种**：Codex for Chrome 5 月 7 日上线；桌面 App 一次性放出 Computer Use、In-App Browser、Memory、图像生成和跨天续跑的 Automations
- **Auto-review 改变审批模型**：约 99% 低风险动作自动通过，不再每次打断
- **三档 Pro 定价**（$20 / $100 / $200）取代旧的两档——$100 Pro 是独立开发者的甜蜜点
- **`/goal` 持久化目标系统**：一个目标可以跨 `/clear`、跨 compaction、跨 session 存活

完整 v1 → v2 修订说明见 §00。

## 下载

| 格式 | 文件 | 大小 |
|------|------|------|
| PDF | [**Codex-Complete-Guide-zh-v2.0.0.pdf**](Codex-Complete-Guide-zh-v2.0.0.pdf) | 7.5 MB |
| EPUB（微信读书优化版） | [**Codex-Complete-Guide-zh-v2.0.0.epub**](Codex-Complete-Guide-zh-v2.0.0.epub) | 5.6 MB |
| HTML（单文件） | [**Codex-Complete-Guide-zh-v2.0.0.html**](Codex-Complete-Guide-zh-v2.0.0.html) | 214 KB |

> 💡 PDF 文件建议下载后阅读，体验更佳。GitHub 在线预览可能无法完整渲染。

## 本书内容

| 部分 | 章节 | 主题 |
|------|------|------|
| **基础** | §01–§03 | Codex 五种形态 · 10 分钟安装 · 你的第一个项目 |
| **日常工作流** | §04–§06 | CLI 深度使用（Auto-review 与沙箱）· AGENTS.md · 桌面 App 五件套 |
| **超出本地机器** | §07–§08 | Cloud 与 Chrome 扩展 · Skills、MCP、Automations、/goal 四大扩展能力 |
| **构建真实产品** | §09–§10 | 从想法到上线 · Codex + Claude Code 双线开发者心智模型 |
| **附录** | A–C | 命令速查（含 `/vim`、`/hooks`、`/goal`、`/ide`、`codex remote-control`）· 定价（三档 Pro）· 常见问题 |

## 适合谁读

- **工程师**：想用 Agent 式编程把效率拉到 10x，把精力从样板代码转移到架构决策
- **Claude Code 用户**：想评估要不要加 Codex，§10 给了基于真实数据的对比与组合建议
- **产品经理与创业者**：想自己做 MVP，Codex 的 Cloud 和 Automations 让一个人同时推多个任务

不需要 AI 编程经验。从零开始，但不在基础概念上磨叽。

## 不回避粗糙之处

这本书不修饰：

- SWE-Bench Pro：GPT-5.5 仍输给 Claude Opus 4.7（58.6% vs 64.3%）
- GPT-5.5 在 Codex 内 1M 上下文实际可用约 258K
- Windows 上 Full Access 模式确实删过用户全盘文件（370GB / 700GB / 240GB 多人证实），绝对不要开
- MultiAgentV2 仍有三个 GitHub 未修 bug（#16657 / #17523 / #14233）

## 预览

<p align="center">
  <img src="screenshots/cover.png" width="45%" />
  <img src="screenshots/content-preview.png" width="45%" />
</p>

## 橙皮书系列

这是橙皮书系列第 8 本，面向 AI Native Builder 的实战指南：

- Claude Code 从入门到精通
- Claude Code 源码解析
- Harness Engineering
- Agent Skills
- OpenClaw：养一只你自己的 AI
- Hermes Agent
- Polymarket 指南
- **OpenAI Codex 从入门到精通** ← 你在这里

完整合集见 [huasheng.ai](https://www.huasheng.ai/)。

## 关于作者

**花叔（HuaShu）** · AI Native Coder · 独立开发者

小猫补光灯（App Store 付费榜第一）的开发者，8 本橙皮书作者，全平台 30 万+ 粉丝。所有产品全部用 AI 完成，从未手写过一行代码。被 CCTV 与《人民日报》报道为「手搓经济」代表人物。

- X/Twitter：[@AlchainHust](https://x.com/AlchainHust)
- YouTube：[@Alchain](https://www.youtube.com/@Alchain)
- B 站：[花叔v](https://space.bilibili.com/14097567/)
- 微信公众号：花叔
- 官网：[huasheng.ai](https://www.huasheng.ai/)

## 协议

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
  <img alt="CC BY-NC-SA 4.0" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" />
</a>

本作品基于 [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/) 协议发布。在保留署名的前提下，可自由分享和改编（非商用）。
