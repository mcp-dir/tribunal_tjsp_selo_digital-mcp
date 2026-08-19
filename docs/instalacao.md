# Instalação detalhada

Tribunal TJSP: Selo Digital é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tjsp_selo_digital`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tjsp_selo_digital` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tjsp_selo_digital` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tjsp_selo_digital` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tjsp_selo_digital` (ou `servers.tribunal_tjsp_selo_digital` no VS Code) do config do cliente e reinicie.
