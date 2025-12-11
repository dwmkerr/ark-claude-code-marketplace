# Ark Claude Code Marketplace

Claude Code plugin for working with [Ark](https://github.com/mckinsey/agents-at-scale-ark).

![Ark Analysis Screenshot](./docs/ark-analysis-claude-code-screenshot.png)

Note: these skills are largely designed for agents running in sandboxes, with access to `kind` to run clusters.

## Quickstart

Open Claude, choose `/Plugin` to interactively add the marketplace `dwmkerr/ark-claude-code-marketplace`, or:

```bash
claude /plugin marketplace add dwmkerr/ark-claude-code-marketplace
claude /plugin install ark@ark-claude-code-marketplace
```

For local development or fork:

```bash
# Change the path on 'add' to your path.
claude /plugin marketplace add ./
```

## Plugin: ark

**Examples**

> Use the 'ark researcher' agent to discover how the MCP Asynchronous Task protocol works, this was only released in November 2025 so you will have to do a lot of exploration

### Skills

| Skill | Description |
|-------|-------------|
| **chainsaw** | Run and write Chainsaw e2e tests with mock-llm |
| **dashboard** | Test Ark Dashboard UI with Playwright |
| **setup** | Set up and install Ark from source |
| **analysis** | Analyze the Ark codebase |
| **research** | Research technical solutions with web search and GitHub repo analysis |
| **architecture** | Ark architecture and design patterns |

### Agents

| Agent | Description |
|-------|-------------|
| **researcher** | Research technical solutions with evidence gathering |
| **ark-architect** | Design Ark architecture and CRDs |
| **ark-prototyper** | Build prototypes and proof-of-concepts |
| **ark-protocol-orchestrator** | Orchestrate protocol implementations |
| **ark-issues** | Manage GitHub issues |
