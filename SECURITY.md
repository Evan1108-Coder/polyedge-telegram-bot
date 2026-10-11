# Security Policy

PolyEdge uses Telegram and model-provider credentials and stores a local paper-trading ledger. Keep credentials and user data private.

## Reporting a vulnerability

Do not post exploitable details in a public issue. Use GitHub's private vulnerability reporting for this repository if enabled. Otherwise, contact the repository owner privately through GitHub. Include the affected commit or version, impact, and minimal reproduction steps; do not include live credentials or personal data.

## Safe handling

- Keep `.env`, local databases, and logs out of Git.
- Restrict bot access with the owner setting when appropriate.
- Rotate any credential that may have been exposed.
- The bot is paper-trading software; do not treat its output as financial advice.