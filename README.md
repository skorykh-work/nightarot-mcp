# Nightarot MCP server

Free tarot tools for AI assistants. A remote, read-only MCP server: no account, no API key, nothing is stored.

Endpoint: https://nightarot.com/mcp (Streamable HTTP)

Tools: draw_tarot_cards (one card, three cards, Celtic Cross), get_tarot_card_meaning (all 78 cards, upright and reversed), get_daily_tarot_card, yes_or_no_tarot.

Languages: en, ru, es, pt, de, fr, it, pl, tr, id, uk.

Site: https://nightarot.com
Docs: https://nightarot.com/en/blog/nightarot-tarot-mcp-server
Registry name: io.github.skorykh-work/nightarot

Try it: send {"jsonrpc":"2.0","id":1,"method":"tools/list"} as a POST with content-type application/json to https://nightarot.com/mcp

For reflection and entertainment. Limit: 20 requests a minute per address. License: MIT.
