# Instalação detalhada

Conector MCP.AI para Dock é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_dock`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_dock` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_dock` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_dock` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.dock` (ou `servers.dock` no VS Code) do config do cliente e reinicie.
