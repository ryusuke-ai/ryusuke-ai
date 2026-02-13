# Hi, I'm Ryusuke 👋

**AI Engineer** building autonomous multi-agent systems that run in production 24/7.

I design systems where AI agents observe their own behavior, learn from past mistakes, and coordinate through natural language — all while keeping humans in the loop.

---

## 🔭 Featured Project: Argus

> AI-powered multi-agent orchestration platform controlled through Slack

A production-grade TypeScript monorepo that wraps the **Claude Agent SDK** with hook-based observation, enabling real-time monitoring and episodic memory across all agent executions.

**What it does:**

- Processes natural language commands from Slack → dispatches AI agents → returns structured results
- Autonomous Inbox Agent that classifies, queues, and executes tasks with failure detection and crash recovery
- Deep Research mode with multi-source web investigation and structured Block Kit reports
- Multi-platform content pipeline across 10 SNS platforms with phased generation and human approval gates
- Full observability dashboard where every tool invocation is recorded and reconstructable

**Key architecture decisions:**

- **Observation-First** — Every tool call is recorded via hooks. Full execution history is always reconstructable
- **Episodic Memory** — Errors and resolutions stored in a `lessons` table, injected into future prompts
- **MCP Integration** — Knowledge bases, Gmail, Calendar exposed as Model Context Protocol servers with role-based access
- **Dual-Mode Execution** — Auto-detects Claude Max Plan (local, free) vs API key (server, paid)

**Scale:**

```
12 packages | 1,165+ tests | 15+ DB tables | 10 SNS platforms | 4 MCP servers
```

[![Argus](https://img.shields.io/badge/Argus-View_Repository-blue?style=for-the-badge&logo=github)](https://github.com/ryusuke-ai/argus)

---

## 🛠 Tech Stack

**AI & Agents**

![Claude Agent SDK](https://img.shields.io/badge/Claude_Agent_SDK-black?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-purple?style=flat-square)
![Anthropic API](https://img.shields.io/badge/Anthropic_API-black?style=flat-square&logo=anthropic&logoColor=white)

**Languages & Runtime**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_22-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![ESM](https://img.shields.io/badge/ES_Modules-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Slack Bolt](https://img.shields.io/badge/Slack_Bolt-4A154B?style=flat-square&logo=slack&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)

**Testing**

![Vitest](https://img.shields.io/badge/Vitest_4-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ryusuke-ai&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ryusuke-ai&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</p>

---

## 💡 What I Care About

- **Observability over trust** — AI agents should be auditable. Every action recorded, every decision traceable.
- **Graceful degradation** — Systems should work with reduced capability rather than not work at all.
- **Human-in-the-loop by design** — Automation should amplify human judgment, not replace it.
- **Learning from failure** — Episodic memory turns every error into a permanent improvement.

---

## 📫 Get in Touch

[![GitHub](https://img.shields.io/badge/GitHub-ryusuke--ai-181717?style=flat-square&logo=github)](https://github.com/ryusuke-ai)
