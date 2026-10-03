# claude-skills

Claude Code plugins by josebert.

## Install

```
/plugin marketplace add Josebert2001/claude-skills
/plugin install system-architect@josebert-skills
/plugin install learn-ai-coding@josebert-skills
```

Get updates with `/plugin marketplace update josebert-skills`.

## Plugins

- **system-architect** — think and work as a systems architect. `system-prompt.md` in the skill folder is a standalone version for pasting into claude.ai custom instructions.

- **learn-ai-coding**: a six-step course for beginners who want to build with an AI agent and don't know where to start. Run the steps in order in an empty project folder: `/learn-ai-coding:1-start`, `2-idea`, `3-plan`, `4-blueprint`, `5-build`, `6-ship`. Progress is saved in `plan/`, so each step can start in a fresh conversation.

## Updating

Edit the skill, bump `version` in `plugins/<name>/.claude-plugin/plugin.json`, commit and push. Installed copies only update when the version changes.
