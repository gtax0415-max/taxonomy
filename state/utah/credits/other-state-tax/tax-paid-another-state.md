---
type: credit
category: other-state-tax
jurisdiction: UT
tax_year: 2026
source_doc: Signed copy of the other state's 2026 income tax return as filed (actual tax liability) / 2026 federal Form 1040 (AGI line 11a) / W-2s and K-1s showing income taxed by the other state
form: Form TC-40
line: "23"
refundable: no
via:
  - Other state's return → TC-40_S (one per state) → total of line 7 → TC-40_A, Part 3 (code NN008PT) → Form TC-40, line 23
---
# Credit for Income Tax Paid to Another State
## Description
Prevents double tax when a Utah resident's income is also taxed by another state, D.C., or a U.S. possession (UCA §59-10-1003).

## Amount (TC-40_S, per state)
1. Federal AGI taxed by both Utah and the other state
2. Federal AGI (TC-40 line 2)
3. Line 1 ÷ line 2, 4 decimals, max 1.0000
4. Utah income tax (TC-40 line 20)
5. Limit = line 4 × line 3
6. Actual income tax paid to the other state on that income
7. Credit = lesser of line 5 or line 6
- Total line 7 for all states → NN008PT

## Eligibility
- Utah residents and part-year residents only; nonresidents do not qualify
- Individual INCOME tax only; not sales, local or foreign country taxes
- Tax paid by a pass-through entity counts only if that income is in Utah taxable income

## Notes
- Use the other state's actual LIABILITY from its filed return, not the withholding on the W-2
- Part-year residents rarely qualify and must prorate
- No carryforward
- Foreign taxes never qualify

## Required Information
- Other state's return, income taxed by both

## Questions
- Did you pay income tax to another state on income Utah also taxes?
- Have you filed that state's return?

## Common Errors
- Using W-2 withholding as the tax paid
- Claiming the full other-state tax instead of the limited amount
- Claiming sales or local taxes
- Nonresidents claiming it

## Prompt
- I live in Utah but worked in Idaho and paid Idaho tax.
