# transactionsync

# TransactionSync

A personal finance budgeting tool for tracking household spending against monthly budgets.

## Overview

TransactionSync is a single-user, offline personal finance application designed to help manage family budgets by importing and categorizing bank and credit card transactions.

## Purpose

This tool helps track spending across multiple accounts and categories, comparing actual expenses against a predefined monthly budget to provide visibility into household finances.

## Features

- **Transaction Import**: Import transactions from bank and credit card CSV exports
- **Budget Tracking**: Define monthly budget limits by category
- **Automated Categorization**: YAML-based rules for automatic transaction categorization
- **Terminal Interface**: Clean CLI and TUI for easy interaction
- **Offline Operation**: All data stored locally with no cloud dependencies

## Technical Details

- **Language**: Python
- **Storage**: SQLite (local database)
- **Interface**: Command-line (CLI) and Terminal UI (TUI) using Textual
- **Configuration**: YAML-based categorization rules
- **Data Sources**: CSV exports from financial institutions (American Express, Chase, etc.)

## Data Privacy

TransactionSync is designed with privacy in mind:

- **Local-only storage**: All data remains on your personal computer
- **No network transmission**: Operates entirely offline
- **No cloud sync**: Data never leaves your device
- **Single-user**: Designed for personal/family use only
- **Plaid Integration**: Uses Plaid API for optional transaction retrieval (personal use only)

## Use Case

This is a personal project developed for individual/family budgeting purposes. It is not a commercial application and does not serve multiple users or collect data from others.

## Plaid Integration

TransactionSync integrates with Plaid to optionally retrieve transaction data directly from financial institutions for the developer's personal accounts. This integration:

- Accesses only the developer's own financial data
- Processes data transiently for budgeting analysis
- Does not share data with third parties
- Complies with Plaid's Developer Policy and End User Privacy Policy

## Contact

For questions about this project: medoror@gmail.com

## License

Personal use only - not licensed for commercial distribution.

---

*This application is registered with Plaid for personal financial data access in compliance with OAuth institution requirements.*
