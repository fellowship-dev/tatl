# Tatl → Navvi

**Tatl has been merged into [Navvi](https://github.com/fellowship-dev/navvi).**

The companion agents (`navvi-browse`, `navvi-login`, `navvi-signup`) now ship with Navvi directly.

## Install

```bash
npx skills add fellowship-dev/navvi
```

Or add the MCP server:

```json
{
  "mcpServers": {
    "navvi": {
      "command": "uvx",
      "args": ["navvi@latest"]
    }
  }
}
```

See **[fellowship-dev/navvi](https://github.com/fellowship-dev/navvi)** for full documentation.
