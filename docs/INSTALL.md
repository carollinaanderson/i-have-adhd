# 📦 INSTALL — i-have-adhd skill

## opencode (recommended)

```bash
# 1. Create your skills directory
mkdir -p ~/.agents/skills

# 2. Clone or copy
git clone https://github.com/carollinaanderson/i-have-adhd ~/.agents/skills/i-have-adhd
# or: cp -r i-have-adhd ~/.agents/skills/

# 3. Use it
#   /i-have-adhd          → activates for the whole session
#   "stop adhd mode"      → deactivates
#   Or just ask naturally: "answer this ADHD-friendly please"
```

## Claude Code

Add `agents/openai.yaml` to your `.claude/skills/` directory (or merge into your agent config). It defines the same output contract for OpenAI-compatible agents.

## Gemini CLI

Add `agents/gemini.toml` to your Gemini CLI skills directory:

```bash
mkdir -p ~/.gemini/skills
cp agents/gemini.toml ~/.gemini/skills/
```

## Verify it's active

Ask a deliberately vague question ("what's next?") — if the answer starts with a numbered next action, the skill is working. If you get a wall of text, re-check your skill path and restart the agent.
