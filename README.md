# The Marketing Vault — Cursor plugin

Connects Cursor to [The Marketing Vault](https://marketerprompts.com) over MCP so you can
research, write, and refine marketing assets with your own business context, ICP, and
brand voice — without leaving the editor.

## Install

Install from the Cursor marketplace, or add the MCP server manually:

```json
{
  "mcpServers": {
    "the-marketing-vault": {
      "url": "https://agsuleyeonapmldynizb.supabase.co/functions/v1/mcp"
    }
  }
}
```

On first use Cursor opens an OAuth consent screen. Sign in with your Marketing Vault
account and approve. Every request runs as you, so you only ever see your own data.

An account is required — free and paid plans both work. Tool runs count against your
plan's run allowance, same as in the app.

## Tools

| Tool | What it does |
| --- | --- |
| `list_businesses` | Businesses in your workspace |
| `get_customer_profile` | Saved ICP + brand voice for a business |
| `list_marketing_tools` | Browse/search the tool library |
| `run_marketing_tool` | Run a tool with your business context |
| `list_saved_outputs` | Recent outputs from your library |
| `save_output` | Save a result back to your library |

## Privacy

OAuth 2.1 with per-user tokens. No service keys, no shared credentials, row-level
security on every query. Prompt internals are not exposed.

Support: dpope@beknownonline.com
