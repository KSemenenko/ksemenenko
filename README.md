### Hey 👋

I'm Konstantin — founder & CTO at **[Managed Code](https://www.managed-code.com)**, building AI-native systems on .NET from Pau, France.

20+ years in software, mass of open source, one [book](https://www.amazon.com/dp/B0CTH5DH95), and a strong opinion that production-ready code starts at the first commit. I specialize in AI systems architecture, Microsoft Orleans, distributed systems, and the kind of .NET infrastructure that runs in production without drama.

---

#### Products

🧠 **[AIBase](https://aibase.fr/)** — enterprise knowledge platform with multi-agent workflows, GraphRAG retrieval, and real business process execution. Built for manufacturing, FMCG, and supply chain. Not a chatbot — a system that remembers, decides, and acts.

> **Case studies:** [AI Patent Attorney](https://www.managed-code.com/case-study/ai-patent-attorney) · [Ticket Booking Copilot](https://www.managed-code.com/case-study/ticket-booking-copilot) · [Food Delivery Copilot](https://www.managed-code.com/case-study/aibase-in-action-food-delivery-copilot)

🖥️ **[dotPilot](https://github.com/managedcode/dotPilot)** — local-first desktop control plane for AI agents. One workbench to manage agent fleets, connect Codex / Claude Code / GitHub Copilot, run local models via LLamaSharp and ONNX, browse repos, review diffs, and orchestrate sessions with approvals, telemetry, and replay. Built on `.NET 10`, `Uno Platform`, embedded `Orleans` silo, and `Microsoft Agent Framework`.

⚙️ **[MCAF](https://mcaf.managed-code.com/)** — framework for building software with AI coding agents. Repository memory, explicit rules, structured tests, repeatable delivery. The difference between "AI generated some code" and "AI shipped a working feature."

🌐 **[GraphRAG for .NET](https://github.com/managedcode/graphrag)** — ground-up `.NET 10` port of Microsoft's GraphRAG. Full indexing pipeline: semantic deduplication, community detection, orphan-node linking, token-budget trimming. Pluggable graph stores — Cosmos DB, Neo4j, Apache AGE/PostgreSQL.

🔗 **[SiloLinker](https://github.com/managedcode/SiloLinker)** — distributed link infrastructure for gated content, temporary access, and monetisation flows.

📊 **[Keyload](https://keyload.cloud/)** — monitoring, incident detection, and operational visibility for websites, APIs, and infrastructure.

📚 **[dotnet/skills](https://github.com/dotnet/skills)** — contributing to the official .NET team's curated skills for AI coding agents.

---

#### AI & Agent Tooling

| Project | Description |
|---------|-------------|
| [GraphRAG for .NET](https://github.com/managedcode/graphrag) | .NET-first GraphRAG — indexing, semantic dedup, community detection, pluggable graph stores |
| [MCAF](https://github.com/managedcode/MCAF) | Framework for building software products together with AI coding agents |
| [dotnet/skills](https://github.com/dotnet/skills) | Official .NET team's skills & agents for AI coding assistants |
| [MCPGateway](https://github.com/managedcode/MCPGateway) | Searchable MCP gateway for .NET |
| [ClaudeCodeSharpSDK](https://github.com/managedcode/ClaudeCodeSharpSDK) | CLI-first .NET SDK for Claude Code workflows |
| [CodexSharpSDK](https://github.com/managedcode/CodexSharpSDK) | CLI-first .NET SDK for OpenAI Codex workflows |
| [MarkItDown](https://github.com/managedcode/MarkItDown) | C# tool for converting files and office documents to Markdown |
| [Presidio](https://github.com/managedcode/presidio) | .NET port — detecting, redacting, and anonymizing sensitive data (PII) across text, images, and structured data |

---

#### Orleans & Distributed Systems

I've been deep in the Orleans ecosystem for years — building backplanes, identity layers, rate limiters, and load balancers on top of the virtual actor model. Most of these run in production across multiple projects.

| Project | Description |
|---------|-------------|
| [Orleans.SignalR](https://github.com/managedcode/Orleans.SignalR) | Scalable SignalR backplane powered by Orleans grains |
| [Orleans.Identity](https://github.com/managedcode/Orleans.Identity) | ASP.NET Identity integration for Orleans — auth on top of grains |
| [Orleans.RateLimiting](https://github.com/managedcode/Orleans.RateLimiting) | Rate limiting algorithms that actually work in distributed scenarios |
| [Orleans.Balancer](https://github.com/managedcode/Orleans.Balancer) | Load balancing and activation rebalancing across silos |
| [Orleans.Indexing](https://github.com/managedcode/Orleans.Indexing) | Search and indexing for grain state |

Orleans is also at the core of **dotPilot** (embedded silo inside the desktop app) and **AIBase** (session and workflow grain model).

---

#### Core .NET Infrastructure

| Project | Description |
|---------|-------------|
| [Storage](https://github.com/managedcode/Storage) | Universal interface for Azure Blob, AWS S3, GCS, SFTP, OneDrive, Google Drive, Dropbox, CloudKit, and local FS — swap providers without rewriting code |
| [Communication](https://github.com/managedcode/Communication) | Result pattern for .NET — replaces exceptions with type-safe return values, RFC 7807, pagination, railway-oriented programming |
| [TimeSeries](https://github.com/managedcode/TimeSeries) | Lock-free time-bucket metrics — accumulators, summers, grouped series. Orleans-friendly. |
| [MimeTypes](https://github.com/managedcode/MimeTypes) | 1,200+ MIME types with content sniffing, reverse lookup, runtime registration |
| [Database](https://github.com/managedcode/Database) | Unified interface for document-oriented NoSQL — Cosmos DB, MongoDB, LiteDB, SQLite, Azure Tables |
| [EnvironmentDetector](https://github.com/managedcode/EnvironmentDetector) | Detect whether code runs in test, Docker, Kubernetes, or Dapr environments |
| [IntegrationTestBaseKit](https://github.com/managedcode/IntegrationTestBaseKit) | ASP.NET integration testing with Testcontainers, Playwright, and SignalR |

---

#### Book

📖 **[C# Interview Guide](https://www.amazon.com/dp/B0CTH5DH95)** — Packt, 2024. Born from years of actually interviewing engineers and reviewing code. Fundamentals through advanced C#, LINQ, async, design patterns — plus interview strategy, salary negotiation, and the career stuff nobody teaches you.

[Amazon](https://www.amazon.com/dp/B0CTH5DH95) · [O'Reilly](https://www.oreilly.com/library/view/c-interview-guide/9781805120469/) · [Google Books](https://books.google.com/books/about/C_Interview_Guide.html?id=_tTzEAAAQBAJ)

---

#### Tech I work with

`C#` · `.NET` · `Orleans` · `Azure` · `Semantic Kernel` · `Microsoft.Extensions.AI` · `Microsoft Agent Framework` · `GraphRAG` · `Uno Platform` · `SignalR` · `Cosmos DB` · `Neo4j` · `PostgreSQL` · `Docker` · `Kubernetes`

---

#### About Managed Code

**[Managed Code](https://www.managed-code.com)** is both a company and an open source community.

The company is a boutique AI solutions agency based in France — we build AI-native systems on .NET for clients where production reliability is non-negotiable.

The **[Managed Code org](https://github.com/managedcode)** on GitHub is an open source community for .NET developers — reliable, actively maintained, and community-driven. Made in Ukraine 🇺🇦 with ❤️

---

#### Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=KSemenenko&show_icons=true&theme=default&hide_border=true&include_all_commits=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=KSemenenko&layout=compact&hide_border=true&langs_count=10)
![Streak](https://streak-stats.demolab.com?user=KSemenenko&hide_border=true)

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=KSemenenko&theme=minimal&hide_border=true&area=true)

---

<p align="center">
  <a href="https://www.ksemenenko.com">website</a> |
  <a href="https://www.managed-code.com">managed code</a> |
  <a href="https://aibase.fr/">aibase</a> |
  <a href="https://dotpilot.managed-code.com/">dotpilot</a> |
  <a href="https://www.linkedin.com/in/ksemenenk0">linkedin</a> |
  <a href="https://www.youtube.com/@managed-code">youtube</a>
  <a href="https://x.com/ksemenenk0">twitter</a> |
</p>
