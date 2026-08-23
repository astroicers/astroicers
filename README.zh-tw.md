[🇺🇸 English](README.md) | [🇹🇼 繁體中文](README.zh-tw.md)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/card-zh-dark.svg">
  <img alt="Astroicers — Offensive Security · Infrastructure · Open Source" src="./assets/card-zh-light.svg" width="100%">
</picture>

# 嗨,我是 Harry Chen 👋

## 攻擊安全 | 基礎架構 | 開源

[![Blog](https://img.shields.io/badge/Blog-astroicers.link-blue?style=flat-square&logo=hugo)](https://astroicers.link)
[![GitHub](https://img.shields.io/github/followers/astroicers?label=Follow&style=social)](https://github.com/astroicers)

資安工程師,從紅隊演練與滲透測試起家。這幾年在做的事,是把攻擊者的那套思維寫成開源工具:一個 AI 自己挑目標、下手法的自主紅隊平台,一套把開發準則變成 AI 護欄的協定,還有台灣資安內容的自動化。搞懂攻擊才守得住,而工具是把這份理解留給下一個人的方法。

### 關於我

- 🔭 正在開發 **[Athena](https://github.com/astroicers/Athena)** - 開源核心、原始碼公開的 C5ISR + OODA 自主紅隊平台(Rust):LLM 驅動的 OODA 迴圈自己挑下一個目標與手法,scope / opsec / 交戰規則的閘門直接焊進執行路徑
  - **[athena-sdk](https://github.com/astroicers/athena-sdk)** - Apache-2.0,可熱插拔 OODA 模組的 Rust 契約 traits
  - **[athena-tools](https://github.com/astroicers/athena-tools)** - Apache-2.0,資料驅動的 MCP 工具目錄(加工具不改核心)
- 📐 建立 **[AI-SOP-Protocol](https://github.com/astroicers/AI-SOP-Protocol)** - 把你的開發準則編譯成 Claude 每次 session 自動載入的護欄:TDD、ADR、commit 閘、發版檢查。v5 三級成熟度 + G1–G6 品質閘,以 Claude Code plugin 發布
- 🛡️ **台灣資安內容**自動化
  - **[security-weekly-mcp](https://github.com/astroicers/security-weekly-mcp)** - MCP Server 驅動的資安週報,涵蓋 32 個國際與台灣來源
  - **[security-glossary-tw](https://github.com/astroicers/security-glossary-tw)** - 台灣資安術語標準化平台,470+ 條術語;另有可搜尋的 glossary.astroicers.link
  - 🌐 **[資安術語庫網站](https://glossary.astroicers.link)** - 470+ 台灣資安術語的線上查詢網站
- 🧰 **AI 工具鏈**——給 agent 協作的 skill、registry 與研究
  - **[starseam](https://github.com/astroicers/starseam)** - 個人設計系統,以 shadcn registry 形式發布。物件是星兜:板疊板、以星鉚之。這個部落格就穿著它
  - **[Ghidra-MCP-WSL-Auto](https://github.com/astroicers/Ghidra-MCP-WSL-Auto)** - 在 WSL2 上一鍵部署 Ghidra + GhidraMCP,給資安研究者的 AI 輔助逆向環境
  - **[skill-quality-research](https://github.com/astroicers/skill-quality-research)** - 97 個 Agent Skill repo 的星數梯度分析:高星的共同點是「好裝」而不是「寫得好」,附可執行的 skill-reviewer 審查工具
  - **Claude Code skills** — 我自己在用的寫作與整合規範: [talk-craft](https://github.com/astroicers/talk-craft) · [slidev-deck-stack](https://github.com/astroicers/slidev-deck-stack) · [visual-web-stack](https://github.com/astroicers/visual-web-stack)
- 🔧 **工具**——為了解決某個具體問題長出來的小東西
  - **[outline-terraform-aws](https://github.com/astroicers/outline-terraform-aws)** - 用 Terraform 與 Ansible 把 Outline Wiki 部署上 AWS
  - **[zst2vmdk](https://github.com/astroicers/zst2vmdk)** - 把 Zstandard 壓縮的 VMA 檔轉成 VMDK,供虛擬機遷移使用
  - **[extension-guard](https://github.com/astroicers/extension-guard)** - VS Code 擴充套件的供應鏈安全掃描器

### 公開紀錄

- 發現並回報 Trend Micro 官網 XSS 漏洞(2020)
- 發現並回報 Dcard 官網 Open Redirect 漏洞(2020)

### 技術棧

**程式語言** ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) · ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) · ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) · ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) · C · Bash

**攻擊工具** Metasploit · Cobalt Strike · Burp Suite · BloodHound · Mimikatz · Impacket · Nuclei

**雲端與容器** ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) · ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) · ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) · AWS · Azure

**專業領域** Red Team · Penetration Testing · Cloud Security · Zero Trust · Supply Chain Security · Reverse Engineering

### 專業證照

**Offensive Security**

- 🎯 OSCP (Offensive Security Certified Professional)

**Cloud Security**

- 🔒 CCSK (Certificate of Cloud Security Knowledge)
- ☁️ AWS SAA (AWS Solutions Architect – Associate)

**Others**

- 🚨 ECIH (EC-Council Certified Incident Handler)
- 🐧 RHCSA (Red Hat Certified System Administrator)
- ☁️ Azure Fundamentals (Microsoft Azure Fundamentals)
- 🪟 MCSE (Microsoft Certified Solutions Expert)

### 演講經歷

| 年份 | 活動 | 主題 |
|------|------|------|
| 2026 | [COSCUP × UbuCon Asia 2026](https://coscup.org/2026/) (Hackers In Taiwan) | [打造 OODA 原生的紅隊平台:當 AI 指揮擊殺鏈](https://coscup.org/2026/session/EHKNXW) *(與 Alex Chih 合講)* |
| 2026 | [CYBERSEC 資安大會](https://cybersec.ithome.com.tw/) | [AI 從小兵變指揮官,擊殺鏈如何從工具箱進化為核彈](https://cybersec.ithome.com.tw/2026/session/4231) *(AI 攻擊論壇)* |
| 2024 | [CYBERSEC 資安大會](https://cybersec.ithome.com.tw/) | [雲端安全新視野:以開源工具解決雲端資安盲點](https://pastevent.cybersec.ithome.com.tw/2024/session-page/2719) |
| 2023 | [AWS Community Day Taiwan](https://awscmd.tw/2023/index.html) | 勇敢抵禦!怕痛的我,把防禦力點滿就對了:探索 OpenAppSec 在 AWS 上的無懼之道 |
| 2022 | [CYBERSEC 資安大會](https://cybersec.ithome.com.tw/) | 攻破駭客隱藏手腳 - 微軟端點防護 *(Microsoft 攤位特邀講師)* |

### 站外連結

[GitHub](https://github.com/astroicers) · [LinkedIn](https://www.linkedin.com/in/chi-hsiu-chen-897528172/) · [Credly](https://www.credly.com/users/chi-hsiu-chen) · [Blog](https://astroicers.link)

---

*"Stay curious, stay paranoid."*
