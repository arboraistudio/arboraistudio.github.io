---
name: compare-arbor-pricing
description: Read and compare Arbor AI Studio package pricing by region without inventing recurring fees, discounts, or implementation scope.
---

# Compare Arbor AI Studio Pricing

## When to Use This Skill

Use this skill when a user asks what Arbor AI Studio costs, wants to compare
packages, or needs the displayed price for Bangladesh, Singapore, or another
supported currency.

## Canonical Source

Fetch https://arboraistudio.com/pricing.md before answering. The HTML pricing page
at https://arboraistudio.com/pricing/ is canonical for customers, while the
Markdown file is the machine-readable representation generated from the same
pricing data.

## Rules

1. Use the region or currency the user explicitly provides. Ask when it is unclear.
2. Describe displayed package prices as one-time setup prices.
3. Do not add a monthly fee unless the current pricing source explicitly includes one.
4. Preserve custom quotes as custom quotes.
5. Mention separate third-party or WhatsApp/API costs when the selected package does.
6. Explain that final scope and price must be confirmed with Arbor AI Studio.
7. Do not convert currencies or promise exchange-rate equivalence unless the user asks
   for an explicitly labelled estimate using a current exchange-rate source.

## Response Format

Provide a compact comparison with:

- Package name.
- Displayed regional setup price.
- Included capabilities most relevant to the user's request.
- Separately billed third-party costs, when stated.
- Canonical pricing link and contact link.

This skill is read-only. It cannot purchase a package, reserve a price, submit a
lead, or approve an implementation on the user's behalf.
