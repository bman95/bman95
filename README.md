<h1 align="center">Bryan Frías</h1>

<p align="center">
  <b>AI Engineer</b> · agentic systems, LLM tooling and document intelligence in production
</p>

<p align="center">
  <a href="mailto:bryanfrias95@gmail.com"><img src="https://img.shields.io/badge/Email-bryanfrias95%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/bman95?tab=repositories"><img src="https://img.shields.io/badge/GitHub-bman95-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

I build AI systems that have to survive contact with real users: coding-agent
orchestration, LLM pipelines whose output can be checked, and backends that turn
messy documents into structured data. Most of my day job is private enterprise
work; the projects below are the parts I can show.

### What I work on

- **Agentic engineering** — plugins, skills and orchestration for coding agents (Claude Code, Codex): planning issues, dispatching autonomous implementers in isolated worktrees, reviewing and merging.
- **LLMs you can verify** — deterministic engines first, with the model as a constrained layer on top whose claims are validated against computed facts.
- **Document intelligence** — OCR and extraction pipelines that feed ERP systems, RAG over large document collections, diagnostic assistants for industrial environments.
- **Backends and automation** — Python/FastAPI services, queues and workers, browser automation over the Chrome DevTools Protocol.

### Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**issue-runner**](https://github.com/bman95/claude-issue-runner-plugin) | Claude Code and Codex plugin for the full agentic issue pipeline, from an idea to merged PRs. Reconciles scope with existing issues, builds a dependency DAG and dispatches each issue to an autonomous implementer subagent with fresh-eyes reviewers. | Agent skills · Bash · GitHub CLI |
| **Caissa** <sub>(private · in development)</sub> | Finds a chess player's recurring leaks from their Lichess history. The engine is fully deterministic and reproducible byte-for-byte; an optional LLM "coach" renderer sits outside it and is validated claim-by-claim against the computed findings. Demo on request. | Python · Parquet · TypeScript |
| [**ccprofile**](https://github.com/bman95/ccprofile) | Profile manager for Claude Code: toggle groups of skills, subagents, commands, plugins and MCP servers to keep the context window lean, with per-directory auto-switching and token stats. | TypeScript · Node.js |
| [**chrome-bridge**](https://github.com/bman95/chrome-bridge) | Drive your real, everyday Chrome from Python scripts — no bundled browser or throwaway profile. Multi-profile and multi-tab over a native-messaging bridge. | Python · Chrome extension · CDP |

### Tech stack

**AI / LLM**&nbsp;
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![RAG](https://img.shields.io/badge/RAG-4B5563?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Backend**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

**Tooling**&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

<p align="center">Open to conversations about AI engineering and agentic tooling — <a href="mailto:bryanfrias95@gmail.com">get in touch</a>.</p>
