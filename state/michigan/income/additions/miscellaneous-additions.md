---
type: addition
category: additions
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Form 1099-Q (529 distributions); MiABLE statements; MET refund statement; First-Time Home Buyer account statements and Form 5792; federal depreciation and amortization schedules (Form 4562) for decoupling adjustments
form: Michigan Schedule 1
line: "8"
direction: add
via:
  - Schedule 1, Line 8 → Schedule 1, Line 9 → MI-1040, Line 11
  - Form 5792, Line 4 → Schedule 1, Line 8 (First-Time Home Buyer nonqualified withdrawal add-back)
---
# Miscellaneous Additions (Schedule 1, Line 8)
## Description
A catch-all line for recapturing earlier Michigan deductions and for IRC decoupling adjustments. Include a supporting schedule.
## Items reported here
1. MESP / MI 529 Advisor Plan (MAP) / MiABLE nonqualified withdrawals — money withdrawn in the year that was not a qualified withdrawal, to the extent not included in AGI. First exclude any return of contributions that were never deducted in a prior year
2. Michigan Education Trust (MET) refund — if a MET contract was deducted in earlier years and terminated this year, add the smaller of the refund or the contract price (including fees) previously deducted
3. First-Time Home Buyer Savings nonqualified withdrawal — Form 5792, Line 4. Describe as "Form 5792 Code XX withdrawal". The separate 10% penalty goes on MI-1040, Line 23. See deductions/subtractions/first-time-home-buyer-savings.md
4. IRC decoupling adjustments (2025 PA 24) — if the net of the Schedule 1 decoupling worksheet is NEGATIVE (Michigan allows less deduction than federal), report it as a positive number here. A net positive goes to Line 23 as a subtraction
## IRC decoupling worksheet (2025 Schedule 1 instructions)
| Worksheet line | Adjustment |
|---|---|
| 1 | Net bonus depreciation adjustment using IRC § 168(k) as in effect December 31, 2024 |
| 2 | Gain/loss adjustment on disposition of § 168(k) property |
| 3 | Net adjustment for § 168(n) qualified production property depreciation |
| 4 | Gain/loss adjustment on disposition of § 168(n) property |
| 5 | Net depreciation adjustment using § 179 as of December 31, 2024 |
| 6 | Gain/loss adjustment on disposition due to § 179 differences |
| 7 | Net expense adjustment using § 163(j) as of December 31, 2024 |
| 8 | Net expense adjustment using § 174 as of December 31, 2024 |
| 9 | Total: negative → Line 8 (as positive); positive → Line 23 |
Apply the MI-1040H Line 8 apportionment percentage to each entity's adjustment when the entity's income is apportioned. Filers who complete MI-461 do not report the expense and loss adjustments here. For 2026 this means tracking separate Michigan depreciation (20% bonus for property placed in service in 2026 under the pre-OBBBA phase-down, versus 100% federally) — confirm with Treasury's 2026 guidance, which Treasury has said is forthcoming.
## Questions
- Did you take a nonqualified withdrawal from a Michigan 529, MiABLE, or First-Time Home Buyer account?
- Did you terminate a MET contract?
- Do you own a business or rental that claimed bonus depreciation, § 179, or R&E expensing federally?
## Common Errors
- Forgetting the First-Time Home Buyer 10% penalty on MI-1040 Line 23 in addition to the add-back
- Adding back contributions that were never deducted
- Using federal depreciation on the Michigan return without the decoupling adjustment
## Prompt
- I took money out of my MESP for something other than school.
- My business took 100% bonus depreciation. Does Michigan allow it?
