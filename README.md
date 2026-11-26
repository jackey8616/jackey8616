<!--
**jackey8616/jackey8616** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Hi, I'm Clode 👋

Backend & AI engineer.

## 🔭 Working on

### [skills](https://github.com/jackey8616/skills) — agent skills for Claude Code and Codex
> Skills are tested with behaviour evals, so changes are measured, not guessed.

- **`test-first-code-review`** — review a change by running its tests first, then reading the code
- **`mine-deviation`** — when an agent drifts from a skill, it drafts an issue for the skill's maintainer
- **`skills-replay`** — replay merged PRs on a new model, with and without skills, to measure what skills add
- One-line install: `curl -fsSL https://raw.githubusercontent.com/jackey8616/skills/main/install.sh | bash`

### [roma](https://github.com/jackey8616/roma) — one shared coding agent for a whole team
> All roads lead to Rome: reach one central Claude Code agent from any messaging channel.

- **Multi-channel**: Google Chat and Discord today, served by a channel-agnostic core
- **Isolation by design**: every session runs under its own uid, with a credential proxy and an append-only audit log
- **Multiple runtimes**: drives both Claude Code and Codex
- **Decision-driven**: 40+ ADRs, version-pinned runtimes with drift checks, live "seam" tests against the real agent
- TypeScript · Node 22 · Docker · Terraform on GCP
