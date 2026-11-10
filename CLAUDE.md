@AGENTS.md

# Finance Advisor

AI financial advisor and money manager for New Zealand, built from the owner's
COMP806 architecture report. See README.md for the idea and stack.

## How to work on this repo

- The owner is building this step by step so the commit history shows steady
  progress. Do one roadmap step at a time, keep each change small, and commit
  per step. Don't build ahead.
- Explain each step and get a go-ahead before running it.
- Never add Co-Authored-By or "Generated with Claude" lines to commits or
  PRs. Commits are authored by the owner only.
- Never move real money. Bank access and payments go through a provider
  interface with a mock implementation; Akahu comes later.

## Stack

Next.js (App Router) + TypeScript + Tailwind, PostgreSQL + Prisma, Claude API
for recommendations.

## Roadmap

1. Database: add Prisma + PostgreSQL, models for User, Account, Transaction.
2. Mock bank provider with sample NZ accounts and seed data.
3. Dashboard page showing balances and recent transactions.
4. Spending categories and simple monthly summary.
5. Goals and budgets.
6. AI recommendations (Claude API).
7. Simulated bill payments and savings transfers.
8. Notifications and unusual-activity alerts.
9. Auth and user consent for linking accounts.
10. Real bank data via Akahu.
