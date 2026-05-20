# Evaluation Guide

Use this page to evaluate whether Gemini Upgrade QA MCP fits a real workflow.

## What To Test

- Gemini 2.5 upgrade eval MCP
- Gemini prompt regression check
- Gemini model release gate
- AI model upgrade QA

## Expected Evidence

- Submit baseline prompt set, target Gemini model, quality rules, and release context.
- Compare current and target outputs against expected behavior.
- Flag regressions, policy drift, and owner-review needs.
- Return upgrade verdict JSON and archive eval receipts.

## Risk Checks

- Keep customer prompts redacted in public examples.
- Use representative test sets before model changes.
- Treat model score differences as review triggers.

## Buyer Path

Default plan: Team.

Tracked checkout link:

- https://geminiupgradeqa.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=geminiupgradeqa_public_docs&utm_content=evaluation_checkout
