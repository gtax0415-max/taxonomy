---
type: tax-computation
category: late-payment-interest
jurisdiction: CO
tax_year: 2026
source_doc: Payment confirmations or canceled checks showing the date and amount of each payment / DOR billing or deficiency notice, if received
form: Form DR 0104
line: "45"
via:
  - Unpaid tax after April 15, 2027 × interest rate × days late / 365 → Line 45 → Line 47
routing:
  - "Paid by April 15, 2027 → $0"
  - "Paid late before DOR issues a notice of deficiency (or within 30 days after one) → discounted rate"
  - "Otherwise → regular rate"
see_also:
  - tax-computation/delinquent-payment-penalty.md
  - tax-computation/estimated-tax-penalty-dr0204.md
---
# Delinquent Payment Interest
## Description
Interest on tax paid after the April 15 due date. It runs even when the return is filed on extension or the filer was abroad.

## Amount
Colorado interest rates by calendar year (DOR Tax Topics: Penalties and Interest):

| Year | Discounted rate | Regular rate |
|---|---|---|
| 2025 | 9% | 12% |
| 2026 | 8% | 11% |
| 2027 | 7% | 10% |

- A 2026 balance accrues interest from April 15, 2027, so the 2027 rates apply: 7% discounted, 10% regular
- The discounted rate applies when the tax is paid before a deficiency notice, which is usually the case when the filer pays with a late return

## Notes
- Example: $2,000 paid 90 days after April 15, 2027, before any notice → $2,000 × 7% × 90 / 365 = $35 (at the regular 10% rate: $49)

## Required Information
- Unpaid tax, payment date, and whether a notice was issued

## Questions
- When will you pay any balance due?
- Have you received a notice from DOR?

## Common Errors
- Assuming the filing extension stops interest
- Using the regular rate when the discounted rate applies, or the reverse

## Prompt
- How much interest does Colorado charge on late tax?
