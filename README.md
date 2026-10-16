# Aus Tax Tracker MCP

Connect your AI assistant to [Aus Tax Tracker](https://taxtracker.au) to log and look up Australian work-related deductions: expenses and receipts, car trips, work-from-home days and assets.

This repository holds setup files only. The server is hosted at:

```
https://taxtracker.au/api/mcp
```

It is a remote MCP server (Streamable HTTP) that signs in with OAuth. There are no API keys. When you connect, your browser shows a code; open the Aus Tax Tracker iPhone app and approve the request if you started it and the code matches. You can disconnect an assistant at any time from the app.

## Install

**Cursor** — install the plugin from this repository, or add to `~/.cursor/mcp.json`:

```json
{ "mcpServers": { "aus-tax-tracker": { "url": "https://taxtracker.au/api/mcp" } } }
```

**Gemini CLI**

```
gemini extensions install https://github.com/laurence-presland/aus-tax-tracker-mcp
```

**Claude, ChatGPT and other assistants** — add a custom connector with the URL above.

## Support

Email support@taxtracker.au or visit https://taxtracker.au/support.

## Licence

MIT. See [LICENSE](LICENSE).
