# AI Rules

Personal AI coding assistant configuration for Claude Code and Codex CLI.

## What's inside

- **CLAUDE.md** — Global instructions for Claude Code (`~/.claude/CLAUDE.md`)
- **AGENTS.md** — Global instructions for Codex CLI (`~/.codex/AGENTS.md`)

## Usage

```bash
git clone https://github.com/Youcius/ai-rules.git
```

Symlink or copy the files:

```bash
# Claude Code (macOS/Linux)
ln -sf ~/ai-rules/CLAUDE.md ~/.claude/CLAUDE.md

# Claude Code (Windows PowerShell)
New-Item -ItemType SymbolicLink -Path ~\.claude\CLAUDE.md -Target ~\ai-rules\CLAUDE.md -Force

# Codex CLI
ln -sf ~/ai-rules/AGENTS.md ~/.codex/AGENTS.md
```
