# Playwriter Session Cloud

Playwriter Session Cloud is a hosted remote MCP for AI agent browser MCP session.

This repository is a public documentation project for Playwriter Session Cloud. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://playwritermcp.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=playwritermcp_public_docs&utm_content=readme_home
- Pricing: https://playwritermcp.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=playwritermcp_public_docs&utm_content=readme_pricing
- Checkout: https://playwritermcp.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=playwritermcp_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://playwritermcp.clauxel.com/mcp
- Server card: https://playwritermcp.clauxel.com/server-card.json
- Registry name: `com.clauxel.playwritermcp/playwritermcp-mcp`
- Tools: `session_open`, `run_stateful_snippet`, `read_page_state`, `export_session_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: session_open
- MCP tool: run_stateful_snippet
- MCP tool: read_page_state
- MCP tool: export_session_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
