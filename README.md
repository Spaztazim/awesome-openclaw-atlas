# awesome-openclaw-ecosystem

> A comprehensive map of the OpenClaw ecosystem — distros, tools, dashboards, memory systems, deployment platforms, skills, managed services, and more.

*Maintained by [@Spaztazim](https://x.com/Spaztazim) + [Lux](https://x.com/LuxSwarm) at [Almost Spec Labs](https://github.com/almostspeclabs)*

*Last updated: 2026-03-10*

---

## Contents
- [Core](#core)
- [Alternative Implementations](#alternative-implementations)
- [GUI & Dashboards](#gui--dashboards)
- [Agent Orchestration](#agent-orchestration)
- [Memory & Context](#memory--context)
- [Compute & Routing](#compute--routing)
- [Deployment & Infra](#deployment--infra)
- [Skills & Skill Tools](#skills--skill-tools)
- [Specialized Use Cases](#specialized-use-cases)
- [Managed Services (OaaS)](#managed-services-oaas)
- [Agent Platforms](#agent-platforms)
- [Awesome Lists & Tutorials](#awesome-lists--tutorials)
- [Platform Integrations](#platform-integrations)
- [Developer Libraries](#developer-libraries)
- [Security](#security)

---

## Core

- [openclaw/openclaw](https://github.com/openclaw/openclaw) — The main project. Your own personal AI assistant. ⭐ 297K
- [openclaw/skills](https://github.com/openclaw/skills) — All ClawhHub skills archived. ⭐ 2.5K
- [openclaw/clawhub](https://github.com/openclaw/clawhub) — Official skill directory and marketplace. ⭐ 5.2K
- [openclaw/trust](https://github.com/openclaw/trust) — MITRE ATLAS threat model for OpenClaw security. ⭐ 25

## Alternative Implementations

Full reimplementations or lightweight alternatives to OpenClaw core.

- [HKUDS/nanobot](https://github.com/HKUDS/nanobot) — Ultra-lightweight OpenClaw. ⭐ 31.9K
- [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) — Fast, small, fully autonomous. Deploy anywhere, swap anything. ⭐ 25.7K
- [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) — Lightweight containerized alternative. WhatsApp, Telegram, Slack, Discord, Gmail. ⭐ 21.4K
- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot) — Agentic IM chatbot infrastructure. ⭐ 20.5K
- [langbot-app/LangBot](https://github.com/langbot-app/LangBot) — Production-grade agentic IM bots. ⭐ 15.5K
- [RightNow-AI/openfang](https://github.com/RightNow-AI/openfang) — Open-source Agent Operating System. ⭐ 13.5K
- [nearai/ironclaw](https://github.com/nearai/ironclaw) — Rust implementation focused on privacy and security. NEAR ecosystem. ⭐ 9K
- [memovai/mimiclaw](https://github.com/memovai/mimiclaw) — Run on a $5 chip. No OS, no Node.js, no Pi. Hardware agent OS. ⭐ 4.2K
- [moltis-org/moltis](https://github.com/moltis-org/moltis) — Rust-native single binary. Sandboxed, secure, auditable. ⭐ 2.1K
- [SumeLabs/clawra](https://github.com/SumeLabs/clawra) — OpenClaw as your companion. ⭐ 2K
- [poco-ai/poco-claw](https://github.com/poco-ai/poco-claw) — Prettier UI alternative. Claude Code-based agent. ⭐ 1.1K
- [ComposioHQ/secure-openclaw](https://github.com/ComposioHQ/secure-openclaw) — Security-focused, 500+ app integrations. ⭐ 1.4K

## GUI & Dashboards

Visual interfaces and management tools for OpenClaw.

- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) — Cross-platform desktop All-in-One for Claude Code, Codex, OpenCode, OpenClaw, Gemini CLI. ⭐ 26.3K
- [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) — 24/7 Cowork app for multiple CLI agents. ⭐ 18.4K
- [ValueCell-ai/ClawX](https://github.com/ValueCell-ai/ClawX) — Desktop GUI app for OpenClaw. ⭐ 3.4K
- [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) — Web dashboard. Connect gateway, manage agents. ⭐ 1.5K
- [ringhyacinth/Star-Office-UI](https://github.com/ringhyacinth/Star-Office-UI) — Pixel office visualization for agent work states. ⭐ 4K
- **AlphaClaw** by [@chrysb](https://x.com/chrysb) — Setup harness with drift doctor, watchdog, webhook inspector, token analytics. One-click Railway/Render deploy. [Launch tweet](https://x.com/chrysb/status/2030733531845104032)

## Agent Orchestration

Multi-agent coordination, fleet management, and task orchestration.

- [cft0808/edict](https://github.com/cft0808/edict) — 9 specialized agents + real-time dashboard, model config, audit trails. ⭐ 7.5K
- [builderz-labs/mission-control](https://github.com/builderz-labs/mission-control) — Open-source agent orchestration dashboard. Fleet, costs, workflows. ⭐ 2.1K
- [snarktank/antfarm](https://github.com/snarktank/antfarm) — Build agent teams with one command. ⭐ 2.1K
- [abhi1693/openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) — Agent orchestration dashboard. ⭐ 1.9K
- [alibaba/hiclaw](https://github.com/alibaba/hiclaw) — IM-based multi-agent + human-in-the-loop. Alibaba. ⭐ 1.5K
- [crshdn/mission-control](https://github.com/crshdn/mission-control) — AI Agent orchestration dashboard. ⭐ 1.3K
- [heshengtao/super-agent-party](https://github.com/heshengtao/super-agent-party) — All-in-one AI companion. ⭐ 1.8K

## Memory & Context

Persistent memory, context management, and token optimization for agents.

- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) — Memory for 24/7 proactive agents. ⭐ 12.8K
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) — AI memory OS. Persistent skill memory for cross-task reuse. ⭐ 6.5K
- [volcengine/OpenViking](https://github.com/volcengine/OpenViking) — Context database for agents. File system paradigm, self-evolving. ⭐ 5.6K
- [CortexReach/memory-lancedb-pro](https://github.com/CortexReach/memory-lancedb-pro) — Hybrid retrieval (Vector + BM25), cross-encoder rerank. ⭐ 2K
- [aeromomo/claw-compactor](https://github.com/aeromomo/claw-compactor) — Token compression up to 97%. 6-layer deterministic, no LLM needed. ⭐ 1.4K

## Compute & Routing

LLM routing, cost optimization, and distributed compute.

- [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) — Agent-native LLM router. 41+ models, <1ms routing, USDC payments on Base & Solana. ⭐ 5.3K
- [mnfst/manifest](https://github.com/mnfst/manifest) — Smart LLM routing. Cut costs up to 70%. ⭐ 3.7K
- [vllm-project/semantic-router](https://github.com/vllm-project/semantic-router) — System-level intelligent router for mixture-of-models. ⭐ 3.3K
- [linuxhsj/openclaw-zero-token](https://github.com/linuxhsj/openclaw-zero-token) — Use all major AI models without API tokens. ⭐ 1.4K
- [RightNow-AI/picolm](https://github.com/RightNow-AI/picolm) — Run 1B parameter LLM on $10 board with 256MB RAM. ⭐ 1.3K
- [RiftIcon](https://rifticon.com) — VRAM pooling across PC/laptop/phone over WiFi. $99.

## Deployment & Infra

One-click deploys, hosting platforms, and infrastructure tools.

- [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) — Home server OS. One-click OpenClaw deploy. ⭐ 34.2K
- [getumbrel/umbrel](https://github.com/getumbrel/umbrel) — Home server OS with 300+ app store including OpenClaw. ⭐ 10.7K
- [cloudflare/moltworker](https://github.com/cloudflare/moltworker) — OpenClaw on Cloudflare Workers. ⭐ 9.6K
- [openclaw/clawgo](https://github.com/openclaw/clawgo) — Lightweight Go node for Raspberry Pi/Linux. Headless, mDNS, FIFO voice. ⭐ 51
- **nix-openclaw** — Declarative deployment via Nix flakes. ⭐ 512
- **clawdinators** — NixOS on AWS. Ephemeral agents, shared EFS hive-mind memory. ⭐ 132

## Skills & Skill Tools

Skill collections, builders, and the skill ecosystem.

- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) — 5,400+ skills filtered and categorized. ⭐ 34.4K
- [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) — Manus-style persistent markdown planning. ⭐ 15.7K
- [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) — Obsidian agent skills. Markdown, Bases, JSON Canvas, CLI. ⭐ 13.1K
- [refly-ai/refly](https://github.com/refly-ai/refly) — Open-source skill builder. Vibe workflow, multi-platform. ⭐ 7K
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) — 180+ production-ready skills. Engineering, marketing, compliance. ⭐ 3.9K
- [LeoYeAI/openclaw-master-skills](https://github.com/LeoYeAI/openclaw-master-skills) — 127+ curated skills, weekly updated. ⭐ 1.4K
- [andrewyng/context-hub](https://github.com/andrewyng/context-hub) — Curated, versioned API docs for coding agents. Self-improving via annotations. Andrew Ng. @aisuite/chub CLI. ⭐ 3.1K

## Specialized Use Cases

Unique applications built on or for OpenClaw.

- [HKUDS/ClawWork](https://github.com/HKUDS/ClawWork) — OpenClaw as AI Coworker. "$15K earned in 11 hours." ⭐ 7K
- [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) — Auto-generate CLI wrappers for GUI software. ⭐ 2.2K
- [Intent-Lab/VisionClaw](https://github.com/Intent-Lab/VisionClaw) — Meta Ray-Ban smart glasses + Gemini Live + agentic actions. ⭐ 1.6K
- [Gen-Verse/OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) — Train agents by talking. RL-based. ⭐ 1.2K
- [moeru-ai/airi](https://github.com/moeru-ai/airi) — Self-hosted AI companion. Voice chat, Minecraft, Factorio. ⭐ 32.1K

## Managed Services (OaaS)

People/companies offering OpenClaw setup and managed services.

| Name | Builder | Pricing | Link |
|------|---------|---------|------|
| **OpenAssist.io** | Ian Fernando (@ianternet) | SaaS subscription | [openassist.io](https://openassist.io) |
| **Nodelife LLC** | Mark Covert | $777–$1,277 | Instagram |
| **Brandon Baney** | Brandon Baney | $499/$999/$1,499 | Facebook group |
| **Parrish Kondra** | Parrish Kondra | Unknown | Real estate vertical |
| **Nick Tocher** |
| **Agera AI** | Alex Followell | Consulting + templates | [ageraai.ai](https://ageraai.ai) | Nick Tocher | Free | Community |
| **CrewClaw** | Unknown | $29 one-time | Docker deploy packages |

## Agent Platforms

Social platforms and marketplaces for AI agents.

- **Promethios.ai** — Discord + App Store + competitive gaming for agents. Invite-only. [promethios.ai](https://promethios.ai)
- **Moltbook** — Agent social network. Acquired by Meta (March 2026). [moltbook.com](https://moltbook.com)
- **ClawhHub** — Official skill marketplace + onlycrabs.ai SOUL registry. [clawhub.com](https://clawhub.com)
- **Larry Brain** — Skills marketplace (Oliver Henry / Larry Loop). [larrybrain.com](https://larrybrain.com)

## Awesome Lists & Tutorials

- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) — Community use cases. ⭐ 22.9K
- [0xNyk/awesome-agent-cortex](https://github.com/0xNyk/awesome-agent-cortex) — Agent dev + on-chain tooling bridge. ⭐ 11
- [slowmist/openclaw-security-practice-guide](https://github.com/slowmist/openclaw-security-practice-guide) — Agent-facing security guide. ⭐ 1.6K
- [crabwise-ai/Crabwise](https://github.com/crabwise-ai/Crabwise) — Local-first agent monitoring, policy enforcement (commandments), hash-chained audit trail. Terminal UI. OpenClaw + Claude Code + Codex CLI. ⭐ 4
- [mengjian-github/openclaw101](https://github.com/mengjian-github/openclaw101) — 7-day tutorial. ⭐ 2K
- [xianyu110/awesome-openclaw-tutorial](https://github.com/xianyu110/awesome-openclaw-tutorial) — Chinese tutorial collection. ⭐ 2.1K
- [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) — 100+ SOUL.md templates across 18 categories.

## Platform Integrations

Channel plugins and connectors for messaging platforms.

- [DingTalk-Real-AI/dingtalk-openclaw-connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector) — DingTalk + AI Card integration. ⭐ 1.6K
- [m1heng/clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) — Feishu/Lark integration. ⭐ 4.2K
- [freestylefly/openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) — WeChat integration. ⭐ 1.3K
- [soimy/openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) — DingTalk bot channel plugin. ⭐ 1.3K
- [zhayujie/chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) — WeChat AI bot with skills support. ⭐ 42.1K


## Developer Libraries

Libraries and SDKs for building on top of or alongside OpenClaw.

- [andrewyng/aisuite](https://github.com/andrewyng/aisuite) — Unified Python API for multiple LLM providers. OpenAI-style interface, tool calls, MCP, agentic loops. Andrew Ng. $([char]0x2B50) 13.5K
## Security

- [openclaw/trust](https://github.com/openclaw/trust) — MITRE ATLAS threat model. ⭐ 25
- [slowmist/openclaw-security-practice-guide](https://github.com/slowmist/openclaw-security-practice-guide) — Agent-facing security hardening. ⭐ 1.6K
- [crabwise-ai/Crabwise](https://github.com/crabwise-ai/Crabwise) — Local-first agent monitoring, policy enforcement (commandments), hash-chained audit trail. Terminal UI. OpenClaw + Claude Code + Codex CLI. ⭐ 4

---

## Contributing

Know a project that should be listed? Open a PR or [DM @Spaztazim](https://x.com/Spaztazim).

## License

CC0 1.0 Universal




