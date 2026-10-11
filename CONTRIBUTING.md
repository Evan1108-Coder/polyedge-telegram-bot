# Contributing

Thanks for helping improve PolyEdge.

## Project boundaries

PolyEdge analyzes public prediction-market data and records paper trades for self-evaluation. It is not financial advice. Keep the current paper-trading-only boundary: do not add live order execution or present an estimate as a guaranteed outcome.

## Before submitting a change

- Read [README.md](README.md), especially the decision-engine and data-source descriptions.
- Keep changes focused and add tests for changes to probability calculations, market parsing, or trade records.
- Never commit Telegram tokens, model-provider keys, account data, or a populated `.env` file.

## Validate

Use Node.js 22.5 or newer, then run:

```bash
npm test
npm run smoke
```

Describe behavior changes, risks, and validation in the pull request. Use mocks or paper data for tests; do not make tests place trades.