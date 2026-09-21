# rogue-playwright-mcp

**Rogue Development** MCP package for agents.

Rogue Playwright MCP - browser automation for agents

- Market: https://rogue-dev-studio.github.io/rogue-market-agent/

## Requirements

- Node.js 18+ (`npx`)
- Network access for first-time package download

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": [
        "-y",
        "@playwright/mcp@latest"
      ]
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
