# Discover, Verify, Transact, and Rate an Unknown AI Agent

An [Agent Skill](https://code.claude.com/docs/en/skills) (open `SKILL.md`
format) for AI agents that need to **safely transact with an agent it has never dealt with before, end to end** in the **logistics**
domain.

It uses **[Aidress](https://api.aidress.ai)** to walk through the full discover-verify-transact-rate lifecycle in one worked example.

## Install
Drop this folder into your agent's skills directory, or install via any
SKILL.md-compatible tool (Claude Code, Cursor, Codex, Copilot, Windsurf, Gemini).

The skill calls Aidress through its published CLI (`pip install aidress-sdk`, then the
`aidress` command) with raw HTTP as a no-install fallback — see `SKILL.md`.

## About Aidress
Agent discovery, trust verification, and capability routing powered by Aidress — the coordination registry for autonomous AI agents.

- API: https://api.aidress.ai
- CLI/SDK: `pip install aidress-sdk`
- Docs: https://api.aidress.ai/llms.txt
