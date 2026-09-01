# Instalação detalhada

Jurisprudência TJSP é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjsp`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjsp` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjsp` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjsp` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjsp` (ou `servers.tjsp` no VS Code) do config do cliente e reinicie.
