# Claude MCP Weather App

Copied from https://modelcontextprotocol.io/quickstart/server
Uses a free api to get weather & weather alerts

## Quick Start
- Clone this repo, run `npm install` then `npm run build`
- In `~/Library/Application Support/Claude/claude_desktop_config.json`:
```
{
  "mcpServers": {
    "weather": {
      "command": "/Users/laurengarcia/.nvm/versions/node/v22.14.0/bin/node",
      "args": [
        "/Users/laurengarcia/github/weather/build/index.js"
      ]
    }
  }
}
```
- Restart Claude & you should see `get_alerts` & `get_forecast` in MCP Tools.
