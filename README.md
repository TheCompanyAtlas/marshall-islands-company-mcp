# Marshall Islands Company Registry MCP

Search Marshall Islands entities by name or business registration number. Many are offshore ship-owning and holding companies, which makes this useful for maritime and sanctions due diligence.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/company/marshall-islands
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month

## Marshall Islands data coverage

- Company ids are `MH` + the business registration number
- Company name and active / inactive status

## Example prompts

- *"Is there a Marshall Islands company called 'Ocean Star Shipping'?"*
- *"Look up this Marshall Islands registration number"*
- *"Find Marshall Islands companies with 'Maritime' in the name"*

## Tools

| Tool | Description |
|---|---|
| `MarshallIslands_search_companies` | Search companies in the Marshall Islands registry by name or id |
| `MarshallIslands_get_company` | Full company profile by id (the `MH` prefix is optional) |

## Keywords

Marshall Islands company search, RMI company registry, ship-owning company lookup, offshore company search, maritime due diligence
