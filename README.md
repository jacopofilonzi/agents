# agents

My personal Claude Code plugin. It provides `/agents:bootstrap`, which sets up the agent directives of a project.

## Install

```sh
claude plugin marketplace add jacopofilonzi/agents
claude plugin install agents@agents
```

## Keep it updated

Auto-update is off by default for this marketplace. Turn it on once from `/plugin` > Marketplaces > `agents` > Enable auto-update.

`plugin.json` deliberately has no `version` field, so every commit on `main` counts as a new version.
