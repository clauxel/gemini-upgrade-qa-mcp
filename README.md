# Gemini Upgrade QA MCP

Catch Gemini model upgrade regressions before they reach customers.

Gemini Upgrade QA is a paid remote MCP for Gemini upgrade evals, prompt regression checks, model output diffs, blocking rules, and eval receipts.

This is a public documentation project for Gemini Upgrade QA MCP. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://geminiupgradeqa.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=readme_primary_home
- Pricing: https://geminiupgradeqa.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=readme_pricing
- Checkout: https://geminiupgradeqa.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://geminiupgradeqa.clauxel.com/mcp
- Server card: https://geminiupgradeqa.clauxel.com/server-card.json
- Registry name: `com.clauxel.geminiupgradeqa/geminiupgradeqa-mcp`
- Tools: `run_gemini_upgrade_eval`, `compare_prompt_outputs`, `detect_model_regression`, `issue_upgrade_receipt`, `export_eval_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

AI platform teams, prompt owners, QA leads, and release engineers.

## Capabilities

- upgrade eval runner
- prompt output comparison
- regression detection
- blocking rules
- eval receipt export

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
