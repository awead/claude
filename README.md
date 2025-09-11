# Claude Code

Configuration and agents.

## Installation

### System

```bash
ln -Fs ${PWD}/settings.json  ~/.claude/settings.json
ln -Fs ${PWD}/agents  ~/.claude/agents
```

### Local Examples

Deny all tools to a given directory:

```bash
cp examples/deny_all.json > ${DIR}/.claude/settings.local.json
```
