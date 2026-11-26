# Hi, I'm Clode 👋

Backend & AI engineer.

## 🔭 Working on

### [skills](https://github.com/jackey8616/skills) — agent skills for Claude Code and Codex

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?logo=openai&logoColor=white)

> Skills are tested with behaviour evals, so changes are measured, not guessed.

- **`test-first-code-review`** — review a change by running its tests first, then reading the code
- **`mine-deviation`** — when an agent drifts from a skill, it drafts an issue for the skill's maintainer
- **`skills-replay`** — replay merged PRs on a new model, with and without skills, to measure what skills add

```bash
curl -fsSL https://raw.githubusercontent.com/jackey8616/skills/main/install.sh | bash
```

### [roma](https://github.com/jackey8616/roma) — one shared coding agent for a whole team

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node 22](https://img.shields.io/badge/Node-22-5FA04E?logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Terraform on GCP](https://img.shields.io/badge/Terraform-GCP-844FBA?logo=terraform&logoColor=white)

> All roads lead to Rome: reach one central Claude Code agent from any messaging channel.

<details>
<summary>How it works</summary>

- **Multi-channel**: Google Chat and Discord today, served by a channel-agnostic core
- **Isolation by design**: every session runs under its own uid, with a credential proxy and an append-only audit log
- **Multiple runtimes**: drives both Claude Code and Codex
- **Decision-driven**: 40+ ADRs, version-pinned runtimes with drift checks, live "seam" tests against the real agent

</details>
