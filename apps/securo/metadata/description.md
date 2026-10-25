# Securo

Securo is an open-source personal finance manager that runs on **your** server, so your financial data never leaves your infrastructure.

## Features

- Multi-account management with running balances
- Transactions with search, filters and CSV export
- File import (OFX, QIF, CAMT, CSV)
- Auto-categorization rules, recurring transactions and budgets
- Goals and savings targets, asset valuation, net worth reports
- Bank sync through Enable Banking (about 2500 European banks) and other providers
- Multi-currency with automatic FX conversion
- Multi-user, TOTP two-factor auth and optional OIDC login

## First start

Open the app and create your account. The first start runs the database migrations, so it can take a minute.

## Optional configuration

- **Passkeys** need the app to be exposed on a domain over HTTPS.
- **Enable Banking**: drop your PEM key in `app-data/securo/data/secrets/`.
