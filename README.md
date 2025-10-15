# MCP Server Deep Dive — Installation

1. Prerequisite: ensure `uvx` is installed and available on your PATH.

2. Add the installer entry to your configuration (example JSON):
```json
"mcp-example": {
    "command": "uvx",
    "args": [
      "--from",
      "https://github.com/Sefiane-dev/mcpserverexample.git",
      "mcp-server"
    ]
    }
```

3. Run the installation (example CLI):
```bash
uvx --from https://github.com/Sefiane-dev/mcpserverexample.git mcp-server
```