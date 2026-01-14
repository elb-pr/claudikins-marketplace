![Claudikins Plugin & Skills Marketplace](banner.png)

# Claudikins Marketplace

## Installation

Add this marketplace to Claude Code:

```bash
claude plugins:add https://github.com/aMilkStack/claudikins-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [claudikins-automatic-context-manager](https://github.com/aMilkStack/claudikins-automatic-context-manager) | Automatic context handoff for Claude Code. When context hits 60%, generates a summary and continues in a fresh session. |
| [claudikins-tool-executor](https://github.com/aMilkStack/claudikins-tool-executor) | Meta-MCP server consolidating multiple MCPs into 3 context-efficient tools with semantic search. Reduces token usage from ~25% to 0.5% of context window. |
| [claudikins-klaus](https://github.com/aMilkStack/claudikins-klaus) | Debugging assistance through Klaus, a dramatically irritated AI persona with Eastern European flair who fixes your code while playing imaginary Pong against you. |
| [claudikins-grfp](https://github.com/aMilkStack/claudikins-github-readme-for-perfectionists) | High-quality README creation through dual-AI collaborative analysis. Claude and Gemini analyse your codebase in parallel, research exemplar READMEs, then co-author documentation section by section. |
| [claudikins-changelog-guru](https://github.com/aMilkStack/claudikins-changelog-guru) | Expert knowledge of Claude Code's feature history. Query when features were added, what's in each version, and capability evolution via /changelog. |

## Contributing

Want to add your plugin? Open a PR adding your plugin to `.claude-plugin/marketplace.json`.
