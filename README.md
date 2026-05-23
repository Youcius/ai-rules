# Claude Rules

My personal [Claude Code](https://claude.ai/code) global configuration.

## What's inside

- **CLAUDE.md** — Global instructions for Claude Code, loaded automatically from `~/.claude/CLAUDE.md`

## Usage

Clone to your home directory:

```bash
git clone https://github.com/Youcius/claude-rules.git
```

Then symlink or copy the files you need:

```bash
# On macOS/Linux
ln -sf ~/claude-rules/CLAUDE.md ~/.claude/CLAUDE.md

# On Windows (PowerShell)
New-Item -ItemType SymbolicLink -Path ~\.claude\CLAUDE.md -Target ~\claude-rules\CLAUDE.md -Force
```

Or just copy the content into your own `~/.claude/CLAUDE.md`.
