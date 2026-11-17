# LETLOTLO

**Digital Finance & Transaction Management Platform**

LETLOTLO is a simulated financial platform designed to demonstrate how digital financial institutions manage customers, wallets, financial transactions, and accounting records.

The project focuses on backend engineering, database design, transaction processing, and financial accounting principles through a practical implementation of a wallet-based financial system.

## Project Objectives

- Implement secure customer registration and authentication.
- Develop digital wallet management.
- Simulate deposits, withdrawals, and wallet-to-wallet transfers.
- Implement double-entry bookkeeping.
- Automatically generate journal entries for financial transactions.
- Maintain accurate general ledger records.
- Ensure financial transaction consistency and data integrity.

## Technology Stack

| Component | Technology |
|---|---|
| Backend | Java 21, Spring Boot |
| Frontend | Angular |
| Database | PostgreSQL |
| ORM | Spring Data JPA / Hibernate |
| Security | Spring Security |
| Build Tool | Gradle |
| Containerization | Docker |

## Core Features

- Customer management
- Authentication and authorization
- Digital wallet management
- Simulated deposits and withdrawals
- Wallet-to-wallet transfers
- Transaction history and references
- Chart of accounts
- Automatic journal entry generation
- Double-entry bookkeeping
- General ledger
- Transaction validation and overdraft prevention
- ACID transaction management
- Idempotency and duplicate transaction prevention
- Audit logging
- Customer account statements
- Financial dashboard

## Financial Model

LETLOTLO uses a double-entry accounting model.

Every financial transaction generates corresponding debit and credit entries, ensuring that:

**Total Debits = Total Credits**

The system maintains accounting records alongside wallet balances to demonstrate how financial transactions are recorded and tracked.

## Project Scope

LETLOTLO is an educational and portfolio project. All financial transactions are simulated. It does not process real money, connect to banking infrastructure, or provide actual financial services.

## Project Status

<badge color="warning">In development</badge>

The project is being developed incrementally, starting with the core wallet and transaction processing functionality before expanding into accounting and financial reporting.

## License

To be determined.
