<div align="center">

# 🩺 skills-doctor

**Audit your installed skills for broken frontmatter, vague triggers, conflicts and leaked secrets. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/skills-doctor)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/skills-doctor?style=social)](https://github.com/milad-ahmd/skills-doctor)
![Category](https://img.shields.io/badge/category-Agent%20Productivity-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/skills-doctor/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

<img src="assets/demo.gif" alt="skills-doctor demo (real output)" width="760"/>

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- skills-doctor
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/skills-doctor /tmp/skills-doctor
mkdir -p ~/.claude/skills && cp -r /tmp/skills-doctor/skills/skills-doctor ~/.claude/skills/
```

**Per project:** copy `skills/skills-doctor` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/skills-doctor/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Check my installed skills
Why isn't my skill triggering?
```

The full workflow, rules and output format are in [`SKILL.md`](skills/skills-doctor/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
