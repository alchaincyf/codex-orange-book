**English** | [中文版 README](README_zh.md)

<p align="center">
  <a href="README.md"><img src="banner-en.png" width="44%" alt="English edition cover" /></a>
  &nbsp;&nbsp;
  <a href="README_zh.md"><img src="banner.png" width="44%" alt="Chinese edition cover" /></a>
</p>

<p align="center">
  <sub>← <a href="README.md">English edition</a> &nbsp;·&nbsp; <a href="README_zh.md">中文版</a> →</sub>
</p>

# OpenAI Codex: The Complete Guide

> Orange Book Series by HuaShu (花叔) · v2.0.1 (May 2026) · Available in **English** and **Chinese**

The definitive guide to OpenAI Codex — covering all **five forms**: CLI, Desktop App, Cloud, IDE Extension, and the new Chrome Extension, plus the mobile companion shipped on May 14. From installation to shipping products, this book takes you from zero to building independently in a week.

Written by someone who has never written a single line of code by hand, yet built an App Store #1 paid app, published 8 technical books, and runs a 300K-follower content operation — all powered by AI.

## 🎬 Launch Film · 15 seconds

<p align="center">
  <img src="launch-film.gif" width="80%" alt="Codex Orange Book — 15-second launch film" />
</p>

<p align="center">
  <em>Uses OpenAI's official visual identity. Designed with <a href="https://github.com/alchaincyf/huashu-design">Huashu-Design</a>.</em><br/>
  <a href="launch-film.mp4">⬇ Download 1080p MP4</a>
  &nbsp;·&nbsp;
  <a href="launch-film-zh.mp4">中文版</a>
</p>

## What's New

**v2.0.1 (May 15, 2026)** — addendum release:
- Added a coda on **Codex on mobile** (shipped May 14, 2026): Codex inside the ChatGPT mobile app, a remote control surface for your desktop Codex App. Covered in §01, §06, and the FAQ.
- **English edition now available** alongside the Chinese edition — native-prose translation, not a literal one.

**v2.0.0 (May 14, 2026)** — major revision after one month of Codex changes:
- **GPT-5.5** landed as the default model (SWE-bench Verified 82.6%, Terminal-Bench 2.0 82.7%, 40% fewer output tokens)
- **Five forms, not four**: Codex for Chrome shipped on May 7; Desktop App got Computer Use, In-App Browser, Memory, Image Generation, and multi-day Automations
- **Auto-review** changed the approval model: ~99% of low-risk actions now flow through without interrupting you
- **Three Pro tiers** ($20 / $100 / $200) replaced the old two-tier pricing — the new $100 Pro is the sweet spot for indie developers
- **Persistent `/goal` system** lets a single objective survive across `/clear`, compaction, and sessions

See §00 for the full v1 → v2 changelog.

## Download

### English edition

| Format | File | Size |
|--------|------|------|
| PDF | [**Codex-Complete-Guide-en-v2.0.1.pdf**](Codex-Complete-Guide-en-v2.0.1.pdf) | 1.7 MB |
| EPUB | [**Codex-Complete-Guide-en-v2.0.1.epub**](Codex-Complete-Guide-en-v2.0.1.epub) | 5.6 MB |
| HTML (single file) | [**Codex-Complete-Guide-en-v2.0.1.html**](Codex-Complete-Guide-en-v2.0.1.html) | 232 KB |

### Chinese edition (中文版)

| Format | File | Size |
|--------|------|------|
| PDF | [**Codex-Complete-Guide-zh-v2.0.1.pdf**](Codex-Complete-Guide-zh-v2.0.1.pdf) | 4.2 MB |
| EPUB (WeChat Reading optimized) | [**Codex-Complete-Guide-zh-v2.0.1.epub**](Codex-Complete-Guide-zh-v2.0.1.epub) | 5.6 MB |
| HTML (single file) | [**Codex-Complete-Guide-zh-v2.0.1.html**](Codex-Complete-Guide-zh-v2.0.1.html) | 220 KB |

> 💡 Download the PDF for the best reading experience. GitHub's online preview may not render properly.

## What This Book Covers

| Part | Chapters | Topics |
|------|----------|--------|
| **Foundations** | §01–§03 | Five forms of Codex (+ mobile coda) · 10-minute install · Your first project |
| **Daily Workflow** | §04–§06 | CLI deep dive (Auto-review + sandbox) · AGENTS.md · Desktop App (Computer Use + 5-piece suite + Mobile Companion) |
| **Beyond the Local Machine** | §07–§08 | Cloud + Chrome extension · Skills, MCP, Automations, /goal — the four extension layers |
| **Building Real Things** | §09–§10 | From idea to shipped product · Dual-tool mental model (Codex + Claude Code) |
| **Appendices** | A–C | Command reference (incl. `/vim`, `/hooks`, `/goal`, `/ide`, `codex remote-control`) · Pricing (three Pro tiers) · FAQ |

## Who Is This For

- **Engineers** who want 10x productivity with agentic coding — let Codex handle implementation while you focus on architecture
- **Claude Code users** evaluating Codex — §10 gives an honest, data-backed comparison of when to use which
- **Product Managers and Entrepreneurs** shipping MVPs solo — Codex's Cloud and Automations let one person run multiple tasks in parallel

No prior AI programming experience required. We start from zero but don't linger on basics.

## Honest About the Rough Edges

This book doesn't sugarcoat. Things you'll find called out:

- SWE-Bench Pro: GPT-5.5 still loses to Claude Opus 4.7 (58.6% vs 64.3%)
- 1M context in Codex is actually ~258K usable
- Full Access mode on Windows has deleted user files (370 GB, 700 GB, 240 GB reports) — never enable it
- MultiAgentV2 has three unfixed GitHub issues (#16657, #17523, #14233) as of v2 release
- Codex on mobile (May 14) is the Desktop App's remote companion, not a standalone phone agent — don't confuse them

## Orange Book Series

This is the eighth book in the Orange Book (橙皮书) series — practical, hands-on guides for AI-native builders:

- Claude Code: The Complete Guide
- Claude Code Source Code Analysis
- Harness Engineering
- Agent Skills
- OpenClaw: Build Your Own AI
- Hermes Agent
- Polymarket Guide
- **OpenAI Codex: The Complete Guide** ← you are here

Visit [huasheng.ai](https://www.huasheng.ai/) for the full collection.

## About the Author

**HuaShu (花叔)** · AI Native Coder · Indie Developer

Creator of Kitty Light (小猫补光灯, App Store #1 Paid App), author of 8 Orange Books, 300K+ followers across platforms. Built all products entirely with AI — never written a single line of code by hand. Featured on CCTV and People's Daily as a representative of the "hand-crafted economy" movement.

- X/Twitter: [@AlchainHust](https://x.com/AlchainHust)
- YouTube: [@Alchain](https://www.youtube.com/@Alchain)
- Bilibili: [花叔v](https://space.bilibili.com/14097567/)
- WeChat Official Account: 花叔
- Website: [huasheng.ai](https://www.huasheng.ai/)

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
  <img alt="CC BY-NC-SA 4.0" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" />
</a>

This work is licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/). You are free to share and adapt for non-commercial purposes with attribution.
