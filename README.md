# agent-skills

Self-collected skills for coding agents (Claude Code and others). Each folder in `skills/` is one skill.

## Install

Copy the skill folders (the contents of `skills/`, not the folder itself) into your agent's skills directory:

```sh
mkdir -p ~/.claude/skills && cp -R skills/* ~/.claude/skills/    # Claude Code
mkdir -p ~/.agents/skills && cp -R skills/* ~/.agents/skills/    # other agents
```

## Skills

- `report-findings`: writes a self-contained report of findings from a long conversation, for a reader who has not seen it.
