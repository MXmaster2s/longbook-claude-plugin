# longbook for Claude

longbook's prompts as Claude skills, with the longbook connector bundled. Generated from the
prompt catalogue (contract revision 39); do not edit by hand.

## Install

In Claude Code or the Claude desktop app:

```
/plugin marketplace add MXmaster2s/longbook-claude-plugin
/plugin install longbook@longbook
```

Then sign in to the longbook connector with your longbook account when Claude asks.

## Skills

- **longbook-setup**: Sets up the user's longbook, their record of subscriptions, bills, rent, salaries, loans and other commitments, from bank and card statements; adds later statements, categorises it, and completes a month so longbook can draw its report.
- **longbook-keep-current**: Keeps the user's longbook current: this month's invoices, bills and money in from their email, a daily email round, invoices and receipts kept as files, and a new commitment or expense.
- **longbook-answers**: Answers questions about the user's bills, subscriptions, payments and spending from their longbook, even when they do not name longbook: what is due next or this week, what is coming in the next 30 days, what a month cost, and what renews this year.
- **longbook-reports**: Asks longbook to draw a report over the days, accounts, people or categories the user chooses, or for a trip.
- **longbook-housekeeping**: Tidies the user's longbook (doubled charges, bank-style names, odd categories) and sets up a morning brief of what is due.
- **longbook-from-email**: Finds subscriptions, expenses, invoices, insurances, purchases, bills, loans and EMIs, travel bookings or money in in the user's email, and adds them to their longbook.

Each skill names its prompts and asks the longbook server for the procedure with
`read_guide`, so the steps are always the server's current ones.
