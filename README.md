# Finance Advisor

An AI-powered financial advisor and money manager for New Zealand. Connect your
bank accounts, see everything in one dashboard, get personalised advice, set
savings goals, and let routine tasks (bill payments, savings transfers) run on
their own, while you stay in control.

Based on my COMP806 architecture design report (AUT, year 3).

## The problem

Budgeting apps mostly record what you already spent. Robo-advisors focus on
long-term investing. Professional advice is expensive. Nothing combines
day-to-day tracking, personalised guidance and automation in one place.

## Planned features

- Link bank accounts, credit cards and investments (NZ open banking via Akahu)
- Consolidated dashboard: income, expenses, savings, debt
- AI spending analysis and recommendations
- Goals and budgets (e.g. saving for a house deposit)
- Automated bill payments and savings transfers (with user confirmation settings)
- Notifications and unusual-activity alerts

Out of scope: stock picking, speculative trading advice, replacing licensed
financial advisers.

## Tech stack

| Layer | Choice |
| --- | --- |
| Framework | Next.js (App Router) + React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Database | PostgreSQL |
| ORM | Prisma |
| AI | Claude API |
| Bank data | Akahu (NZ open banking), mocked during development |

## Quality goals

From the report: security, reliability, performance efficiency, functional
suitability and scalability.

## Getting started

```bash
npm install
npm run dev
```

Then open http://localhost:3000.
