# Environment Configuration

Copy `.env.example` to `.env` and fill in the values needed for your local bot. Never commit the populated `.env` file.

| Variable | Purpose |
| --- | --- |
| `TELEGRAM_BOT_TOKEN` | Required Telegram bot credential. |
| `TELEGRAM_OWNER_ID` | Optional owner restriction for a private bot. |
| `MINIMAX_API_KEY` | Required MiniMax API credential for model reasoning. |
| `MINIMAX_MODEL` | Model identifier; the template uses `MiniMax-M1`. |
| `EDGE_THRESHOLD` | Minimum estimated edge, in percentage points, before a recommendation is shown. |
| `PAPER_BANKROLL` | Starting virtual balance for paper-trade tracking, in USD. |
| `DEFAULT_TIMEZONE` | Timezone used for scheduled or time-based behavior. |
| `LLM_TIMEOUT_MS` | Model request timeout in milliseconds. |

See [README.md](README.md) for installation and startup. The configuration is for analysis and paper trading only; it does not authorize or configure live trades.