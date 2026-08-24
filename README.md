# i-have-adhd

> **Shape output for a reader with ADHD.** Lead with the next action. Number multi-step work. Restate state across turns. Suppress tangents. Give specific time estimates. Make wins visible.

[![Type](https://img.shields.io/badge/Type-Agent%20Skill-8b5cf6.svg)](#)
[![Format](https://img.shields.io/badge/Format-Markdown%20%2B%20YAML%20%2F%20TOML-orange.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A skill for your coding agent (opencode, Claude Code, Gemini CLI, and friends) that stops it from burying the answer. Built by someone with AuADHD, for anyone whose brain needs structure, not walls of text.

---

## 🧠 Why this exists

You ask a question. The agent replies with 800 words. You need the **answer** in the first 20.

This skill encodes the opposite: output is **shaped so an ADHD brain can act on it** — every response leads with what to do next, keeps state visible, and makes progress tangible.

## ✨ What it does

| Rule | Effect |
|---|---|
| ⏭ Lead with the next action | The first line is always "do this first" |
| 🔢 Number multi-step work | Steps are ordered and countable — no walls of text |
| 🔄 Restate state across turns | "Where we are" is repeated, never assumed |
| ✂️ Suppress tangents | Side notes get quarantined, not interleaved |
| ⏱ Specific time estimates | "2 min" not "quickly" |
| 🏆 Make wins visible | Progress is celebrated in the output itself |

## 🚀 Install & use

### opencode
1. Copy this folder to `~/.agents/skills/i-have-adhd/` (or your skills directory)
2. Invoke with `/i-have-adhd` — or just ask naturally for ADHD-friendly output
3. It stays **on for the rest of the session** until you say "stop adhd mode"

### Claude Code / Gemini CLI
Drop the contents of `agents/` into your agent config:
- `agents/openai.yaml` → OpenAI-compatible agents
- `agents/gemini.toml` → Gemini CLI skills

Full setup: [docs/INSTALL.md](docs/INSTALL.md)

## 🗂 Repository layout

```
i-have-adhd/
├── SKILL.md            # the skill definition (human + agent readable)
├── agents/
│   ├── openai.yaml     # config for OpenAI-compatible agents
│   └── gemini.toml     # config for Gemini CLI
├── docs/
│   └── INSTALL.md      # installation guide
└── examples/           # before/after output samples
```

## 🤝 Contributing

Have a rule that works for your ADHD? Open a PR — this skill should grow with the community that needs it.

## 📄 License

MIT.
