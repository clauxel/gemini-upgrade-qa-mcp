# Troubleshooting

## Public Website Does Not Load

Check the clean homepage first:

- https://geminiupgradeqa.clauxel.com/

Then use the tracked documentation link:

- https://geminiupgradeqa.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=troubleshooting_home

## Checkout Link Fails

Use the public checkout route and avoid adding private account information to GitHub issues.

- https://geminiupgradeqa.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=troubleshooting_checkout

## MCP Request Fails

- Confirm the endpoint is exactly `https://geminiupgradeqa.clauxel.com/mcp`.
- Confirm the request is POST JSON-RPC.
- Confirm the bearer token is stored in the MCP client secret mechanism, not in public files.
