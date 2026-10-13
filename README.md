# Chatley AI — MCP server

Connect Claude, ChatGPT, Cursor or any MCP-compatible client to your [Chatley AI](https://chatley.ai) account. Review calls and transcripts, read analytics, and configure your AI voice agents — without opening the dashboard.

This repository holds listing information only. It contains no source code.

## Connect

- **Endpoint (Streamable HTTP):** `https://mcp.chatley.ai/mcp`
- **Authentication:** OAuth 2.1 with Dynamic Client Registration. Your client registers itself; there is no client ID or secret to copy. You sign in to Chatley and approve access.
- **Claude:** Settings → Connectors → Add custom connector → paste the endpoint.
- **Claude Code:** `claude mcp add --transport http chatley https://mcp.chatley.ai/mcp`

Tools you are not permitted to use do not appear in your client.

## Tools

See [docs/tools.md](docs/tools.md) for all 16 tools. Every tool carries MCP annotations (`title`, `readOnlyHint`, `destructiveHint`, `idempotentHint`, `openWorldHint`).

## Links

- Documentation: https://docs.chatley.ai/mcp
- Privacy Policy: https://chatley.ai/privacy-policy
- Terms of Service: https://chatley.ai/terms-of-service
- Support: support@chatley.ai <!-- TODO confirm support contact -->
- Security reports: security@chatley.ai <!-- TODO confirm security contact -->
