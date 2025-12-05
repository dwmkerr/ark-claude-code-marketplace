# Ark Claude Code Marketplace

Claude Code plugin for working with [Ark](https://github.com/mckinsey/agents-at-scale-ark).

## Plugin: ark

Skills for Ark development and testing:

| Skill | Description |
|-------|-------------|
| **chainsaw** | Run and write Chainsaw e2e tests with mock-llm |
| **dashboard** | Test Ark Dashboard UI with Playwright |
| **setup** | Set up and install Ark from source |
| **analysis** | Analyze the Ark codebase |

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add dwmkerr/ark-claude-code-marketplace
```

Install the plugin:

```
/plugin install ark@ark-claude-code-marketplace
```

## Local Development

Test locally:

```bash
/plugin marketplace add ./path/to/ark-claude-code-marketplace
/plugin install ark@ark-claude-code-marketplace
```
