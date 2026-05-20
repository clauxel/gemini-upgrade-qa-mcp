# Workflow

Gemini Upgrade QA is a paid remote MCP for Gemini upgrade evals, prompt regression checks, model output diffs, blocking rules, and eval receipts.

## Repeatable Flow

1. Submit baseline prompt set, target Gemini model, quality rules, and release context.
2. Compare current and target outputs against expected behavior.
3. Flag regressions, policy drift, and owner-review needs.
4. Return upgrade verdict JSON and archive eval receipts.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
