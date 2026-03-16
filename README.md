<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:0c445c,100:008080&height=200&section=header&text=Konstantin%20Semenenko&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Founder%20%26%20CTO%20@%20Managed%20Code%20·%20Pau,%20France&descSize=16&descColor=88cccc&descAlignY=55" alt="konstantin"/>
</p>

<p align="center">
  <a href="https://www.managed-code.com"><img src="https://img.shields.io/badge/Managed%20Code-0F172A?style=flat-square&logo=vercel&logoColor=white" alt="Managed Code"></a>
  <a href="https://aibase.fr/"><img src="https://img.shields.io/badge/AIBase-2563EB?style=flat-square&logo=sparkfun&logoColor=white" alt="AIBase"></a>
  <a href="https://dotpilot.managed-code.com/"><img src="https://img.shields.io/badge/dotPilot-008080?style=flat-square" alt="dotPilot"></a>
  <a href="https://www.amazon.com/dp/B0CTH5DH95"><img src="https://img.shields.io/badge/C%23%20Interview%20Guide-FF9900?style=flat-square&logo=amazon&logoColor=white" alt="Book"></a>
  <a href="https://x.com/ksemenenk0"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="https://www.linkedin.com/in/ksemenenk0"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/managedcode"><img src="https://img.shields.io/badge/managedcode-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Org"></a>
</p>

---

I run **[Managed Code](https://www.managed-code.com)** — a boutique AI solutions agency in France. We build AI-native product systems on the .NET stack for clients where production failures aren't an option. 20+ years in software — from sysadmin to architecture to running the company. Made in Ukraine 🇺🇦, building from France 🇫🇷.

Below is what I'm shipping right now and the open-source infrastructure behind it.

---

## Products

### 🧠 [AIBase](https://aibase.fr/)

Enterprise knowledge platform for multi-agent workflows. Not a chatbot wrapper — a system that ingests company knowledge, retrieves it through GraphRAG, and lets AI agents remember context, make decisions, and execute real business processes. Built for manufacturing, FMCG, and supply chain operations.

**In production:**
[AI Patent Attorney](https://www.managed-code.com/case-study/ai-patent-attorney) · [Ticket Booking Copilot](https://www.managed-code.com/case-study/ticket-booking-copilot) · [Food Delivery Copilot](https://www.managed-code.com/case-study/aibase-in-action-food-delivery-copilot)

---

### 🖥️ [dotPilot](https://github.com/managedcode/dotPilot)

Local-first desktop control plane for AI agents. A single operator workbench where you manage agent profiles, connect external runtimes (Codex, Claude Code, GitHub Copilot), run local models via LLamaSharp/ONNX, browse repos, review diffs, and orchestrate sessions with approvals, telemetry, and replay — all from one UI.

Built on `.NET 10`, `Uno Platform`, embedded `Orleans` silo, and `Microsoft Agent Framework`. Not just for coding agents — supports research, analysis, and operator-style workflows.

---

### ⚙️ [MCAF](https://mcaf.managed-code.com/)

Framework for building software together with AI coding agents. Repository memory, explicit rules, structured docs, tests, and repeatable delivery. The difference between "AI wrote some code" and "AI shipped a feature."

---

### 🌐 [GraphRAG for .NET](https://github.com/managedcode/graphrag)

Ground-up .NET 10 port of Microsoft's GraphRAG. Full indexing pipeline — semantic deduplication, community detection, orphan-node linking, token-budget trimming. Pluggable graph stores: Cosmos DB, Neo4j, Apache AGE/PostgreSQL. Because the .NET ecosystem shouldn't depend on Python subprocesses for retrieval infrastructure.

---

### 📚 [dotnet/skills](https://github.com/dotnet/skills)

The official .NET team's curated skills for AI coding agents. I contribute here and advocate for this ecosystem — if AI agents are going to write .NET code, they should know the idioms, not just the syntax.

---

### 📊 [Keyload](https://keyload.cloud/)

Monitoring, incident detection, and operational visibility for websites, APIs, and infrastructure.

---

## Open Source — [managedcode](https://github.com/managedcode)

Open source community for .NET developers. Everything here runs in production somewhere. If we ship it, we maintain it.

<details>
<summary><strong>AI & Agent Tooling</strong></summary>
<br>

| | | |
|---|---|---|
| [MCPGateway](https://github.com/managedcode/MCPGateway) | Searchable MCP gateway for .NET | ![](https://img.shields.io/github/stars/managedcode/MCPGateway?style=flat-square) |
| [ClaudeCodeSharpSDK](https://github.com/managedcode/ClaudeCodeSharpSDK) | CLI-first .NET SDK for Claude Code | ![](https://img.shields.io/github/stars/managedcode/ClaudeCodeSharpSDK?style=flat-square) |
| [CodexSharpSDK](https://github.com/managedcode/CodexSharpSDK) | CLI-first .NET SDK for OpenAI Codex | ![](https://img.shields.io/github/stars/managedcode/CodexSharpSDK?style=flat-square) |
| [MarkItDown](https://github.com/managedcode/MarkItDown) | Convert office docs → Markdown in C# | ![](https://img.shields.io/github/stars/managedcode/MarkItDown?style=flat-square) |

</details>

<details>
<summary><strong>Orleans & Distributed Systems</strong></summary>
<br>

| | | |
|---|---|---|
| [Orleans.SignalR](https://github.com/managedcode/Orleans.SignalR) | Scalable SignalR backplane on Orleans | ![](https://img.shields.io/github/stars/managedcode/Orleans.SignalR?style=flat-square) |
| [Orleans.Identity](https://github.com/managedcode/Orleans.Identity) | ASP.NET Identity for Orleans grains | ![](https://img.shields.io/github/stars/managedcode/Orleans.Identity?style=flat-square) |
| [Orleans.RateLimiting](https://github.com/managedcode/Orleans.RateLimiting) | Distributed rate limiting | ![](https://img.shields.io/github/stars/managedcode/Orleans.RateLimiting?style=flat-square) |
| [Orleans.Balancer](https://github.com/managedcode/Orleans.Balancer) | Activation rebalancing across silos | ![](https://img.shields.io/github/stars/managedcode/Orleans.Balancer?style=flat-square) |
| [Orleans.Indexing](https://github.com/managedcode/Orleans.Indexing) | Search & indexing for grain state | ![](https://img.shields.io/github/stars/managedcode/Orleans.Indexing?style=flat-square) |

</details>

<details>
<summary><strong>Core Infrastructure</strong></summary>
<br>

| | | |
|---|---|---|
| [Storage](https://github.com/managedcode/Storage) | One interface for Azure, AWS, GCS, SFTP, OneDrive, Dropbox — swap without rewriting | ![](https://img.shields.io/github/stars/managedcode/Storage?style=flat-square) |
| [Communication](https://github.com/managedcode/Communication) | Result pattern + RFC 7807 + pagination | ![](https://img.shields.io/github/stars/managedcode/Communication?style=flat-square) |
| [TimeSeries](https://github.com/managedcode/TimeSeries) | Lock-free time-bucket metrics | ![](https://img.shields.io/github/stars/managedcode/TimeSeries?style=flat-square) |
| [SiloLinker](https://github.com/managedcode/SiloLinker) | Distributed link infrastructure for gated content | ![](https://img.shields.io/github/stars/managedcode/SiloLinker?style=flat-square) |

</details>

---

## Book

📖 **[C# Interview Guide](https://www.amazon.com/dp/B0CTH5DH95)** — Packt, 2024. Born from years of actually interviewing engineers and reviewing code, not from copying documentation. Covers fundamentals through advanced topics, plus the career strategy and soft skills part that everyone ignores until it's too late. [Amazon](https://www.amazon.com/dp/B0CTH5DH95) · [O'Reilly](https://www.oreilly.com/library/view/c-interview-guide/9781805120469/)

---

## How I Build

> Production-ready code from the first commit.

I've watched too many "we'll clean it up later" turn into permanent technical debt with compound interest. So the rule is simple: clear architecture, explicit boundaries, strong typing, thorough tests, and the discipline to keep all of it coherent when the scope inevitably grows.

If the system can't survive real load, real change, and real responsibility — it's not done.

<details>
<summary>Also</summary>
When the problem gets really hard, the Finnish power metal band <em>Battle Beast</em> gets really loud. This correlation is not accidental. 🤘
</details>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KSemenenko&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9" height="160" alt="stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KSemenenko&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=c9d1d9&langs_count=8" height="160" alt="languages">
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:0c445c,100:008080&height=100&section=footer" alt="footer"/>
</p>

<p align="center">
  <em>Let's build things that last.</em>
</p>
