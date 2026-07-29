<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1488CC,2B32B2&height=200&section=header&text=ChatNext-Assistant&fontSize=62&fontColor=ffffff&animation=twinkling" width="100%" />

<img src="https://img.icons8.com/?id=43664&format=png&size=100" width="90" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=1488CC&center=true&vCenter=true&width=700&height=50&lines=Self-Hosted%20ChatGPT%20Web%20+%20Desktop%20Client;Next.js%20+%20Tauri%20%E2%80%94%20fork%20of%20NextChat" alt="Typing SVG" />

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](#)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](#)
[![Tauri](https://img.shields.io/badge/Tauri-Desktop-FFC131?style=for-the-badge&logo=tauri&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
[![License](https://img.shields.io/github/license/AfnanSharif/ChatNext-Assistant?style=for-the-badge&color=yellow)](LICENSE)

</div>

---

## 📖 Overview

**ChatNext-Assistant** is a self-hosted ChatGPT-style web client (package name `nextchat`,
based on the open-source **NextChat** project): a Next.js web UI with an optional **Tauri**
desktop build, MCP (Model Context Protocol) support, and multi-provider model config.

## 🏗️ Project Layout

```
ChatNext-Assistant/
├── app/
│   ├── page.tsx, layout.tsx   # Next.js app router
│   ├── api/                     # API routes (model providers)
│   ├── components/                # Chat UI
│   ├── store/                       # Client state
│   ├── mcp/                          # Model Context Protocol integration
│   └── masks/                          # Prompt presets
├── src-tauri/                # Desktop app (Tauri)
└── docker-compose.yml
```


## ⚡ Setup & Run

### 🪟 Windows / 🍎 macOS / 🐧 Linux — Web
```bash
git clone https://github.com/AfnanSharif/ChatNext-Assistant.git
cd ChatNext-Assistant
yarn install   # or npm install

cp .env.template .env.local
# set OPENAI_API_KEY (or other provider keys) in .env.local

yarn dev       # http://localhost:3000
```

### 🐳 Docker (all platforms)
```bash
docker compose up --build
```

### 🖥️ Desktop app (Tauri) — requires Rust toolchain
```bash
yarn tauri dev
```

---

<div align="center">

**Created by [AfnanSharif](https://github.com/AfnanSharif)** · ⭐ star this repo if it helped you

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1488CC,2B32B2&height=80&section=footer" width="100%" />

</div>
