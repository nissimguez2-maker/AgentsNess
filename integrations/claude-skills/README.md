# Claude Agent Skills

Installs every agent as a **Claude Skill** — `~/.claude/skills/<slug>/SKILL.md` — for **one-pass prompts** you invoke for a single transformation (e.g. "humanize this", "write the exec summary"). Claude keeps each skill's `name` + `description` in context and pulls in the full body only when it's the right tool for the task.

> This is the **one-pass / skill** path. For delegated, multi-step work, install the same agents as **subagents** instead: `./scripts/install.sh --tool claude-code` (→ `~/.claude/agents/`). The two are complementary and can both be installed from the same source.

## Install

```bash
./scripts/convert.sh --tool claude-skills      # generate integrations/claude-skills/<slug>/SKILL.md
./scripts/install.sh --tool claude-skills      # copy to ~/.claude/skills/
```

## Format

Each skill is `~/.claude/skills/<slug>/SKILL.md`:

```markdown
---
name: <slug>                 # lowercase-hyphen, matches the folder, ≤64 chars
description: '<what it does>' # ≤1024 chars — Claude reads this to decide when to use it
---
> One-pass skill. Apply the expertise below in a single response.

<the full agent persona>
```

## Notes
- `description` is auto-trimmed to Claude's 1024-char limit on a word boundary.
- Generated files are git-ignored; re-run `convert.sh` after editing any agent.
