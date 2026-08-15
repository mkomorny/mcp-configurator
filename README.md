# Mcp Configurator

Generates and validates local JSON configuration files that link desktop AI clients with external developer tools, databases, and third-party APIs via Model Context Protocol (MCP). Use when the user wants mcp.json / MCP client config, Claude Desktop / Cursor / Grok MCP setup, stdio or HTTP server entries, env vars for API keys, validating MCP config JSON, or "wire this tool into my AI client." Prefer this for config file generation; use mcp-plugin-integration-designer for product-level architecture and routing.

**Type:** Custom Grok agent  
**Compatible with:** Grok Build (native). Also usable as a subagent prompt in Claude Code and similar tools.

## Install

### Grok Build
Copy `agents/mcp-configurator.md` to `~/.grok/agents/` then reload agents (`/agents` or a new session).

### Other coding agents
Treat `agents/mcp-configurator.md` as a custom subagent prompt. Drop it into the agent folder your tool uses (for example `.claude/agents/` or a plugin `agents/` directory).

## Files

- `agents/mcp-configurator.md` — agent prompt (YAML frontmatter + instructions)

## License

MIT © Miranda Komorny
