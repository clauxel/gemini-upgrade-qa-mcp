# Gemini Upgrade QA MCP

Catch Gemini model upgrade regressions before they reach customers.

Paid remote MCP for Gemini upgrade evals, prompt regression checks, model output diffs, blocking rules, and eval receipts.

## Public Endpoints

- Website: https://geminiupgradeqa.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://geminiupgradeqa.clauxel.com/mcp
- Server card: https://geminiupgradeqa.clauxel.com/server-card.json
- Registry name: `com.clauxel.geminiupgradeqa/geminiupgradeqa-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `run_gemini_upgrade_eval`
- `compare_prompt_outputs`
- `detect_model_regression`
- `issue_upgrade_receipt`
- `export_eval_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://geminiupgradeqa.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://geminiupgradeqa.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://geminiupgradeqa.clauxel.com/server-card.json
- MCP endpoint: https://geminiupgradeqa.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
