---
type: income
category: add-back
jurisdiction: IN
tax_year: 2026
source_doc: Federal Schedules C, E and F (taxes and licenses lines) / federal Form 8829 / federal Schedule K-1 and the entity's statement of state income tax or pass-through entity tax deducted
form: Schedule 1
line: "1"
via:
  - State-level taxes based on or measured by income deducted on federal Schedules C, C-EZ, E or F (including through K-1s and Form 8829) → Schedule 1, Line 1 → Line 7 → Form IT-40, Line 2
  - Refund of a previously added-back tax → Schedule 1, Line 1 as a negative entry
routing:
  - "No federal Schedule C, E or F → leave line 1 blank"
  - "State income tax or state-level PTET deducted in figuring federal AGI → add back"
  - "Property taxes → not added back"
  - "Wagering taxes, taxable year beginning in 2026 or later → 0% add-back (phase-out complete)"
  - "Refund of an added-back tax received → report on line 1 as a deduction (negative)"
see_also:
  - income/add-backs/add-backs.md
  - payments/pass-through-entity-tax-credit.md
  - income/add-backs/excess-business-loss-modification-151.md
---
# Tax Add-Back (Schedule 1, Line 1)
## Description
On federal Schedules C, C-EZ, E and F (sole proprietorship, farm, rental, partnership, S corporation, and trust and estate income or loss) a business may deduct taxes. Taxes that are based on or measured by income and levied at a state level by any U.S. state must be added back for Indiana. If you did not complete federal Schedule C, E or F, do not complete this line.
## What is added back
- State-level taxes based on or measured by income (Indiana or any other state) deducted on Schedules C, E or F.
- State-level pass through entity taxes (PTET) deducted in determining federal AGI, including PTET passed through on a federal K-1.
- Amounts flowing to Schedules C, E or F from other forms: partnership income from a federal Schedule K-1 (Form 1065) on Schedule E, or Form 8829 expenses on Schedule C.
## What is not added back
| Item | Reason |
|---|---|
| Property taxes | Not a tax based on or measured by income |
| Wagering taxes for a taxable year beginning in 2026 or later | Phase-out complete; no add-back required |
| Taxes deducted as itemized deductions on federal Schedule A | Not part of federal AGI |
## Wagering tax phase-out
The percentage of wagering taxes added back depends on the first day of the taxable year: 2020 - 75%; 2021 - 62.5%; 2022 - 50%; 2023 - 37.5%; 2024 - 25.0%; 2025 - 12.5%; 2026 and later - no add-back. The 2025 booklet example: an owner of 10% of a casino with a $1,000,000 share of wagering taxes added back $125,000 for 2025. For 2026 the same owner adds back $0.
## PTET refunds
If you later receive a refund of a tax you added back, report the refund on line 1 as a deduction (a negative entry). PTET paid on your behalf by an electing Indiana entity is claimed as a credit on Schedule 5, line 3 (see payments/pass-through-entity-tax-credit.md).
## Excess business loss interaction
If part of the deduction was disallowed under IRC 461(l), report the add-back in full and use code 151 to deduct the portion included in the disallowed loss (see excess-business-loss-modification-151.md).
## Example
Ana's S corporation elected Indiana PTET and deducted $3,000 of PTET attributable to her share; her K-1 income on Schedule E is net of it. Ana adds back $3,000 on Schedule 1, line 1 and claims the PTET credited to her on Schedule 5, line 3.
## Questions
- Do you have federal Schedules C, E or F, or K-1s flowing to them?
- Did any business or pass-through entity deduct state income taxes or PTET?
- Did you receive a refund of a state income tax or PTET that you added back before?
- Do you own an interest in a casino or other entity paying wagering taxes?
## Common Errors
- Adding back property taxes
- Adding back state income tax claimed as a federal itemized deduction
- Still adding back wagering taxes for 2026
- Missing PTET buried in a K-1 amount on Schedule E
## Prompt
- My partnership paid pass through entity tax. Do I add it back in Indiana?
- Do I add back property tax on my rental?
