---
type: deduction
category: subtractions
jurisdiction: michigan
tax_year: 2026
source_doc: Loss-year MI-1040, Schedule 1, and Schedule MI-1045; FEDERAL Form 1040 and Schedules 1, A, B, C, D, E, F, Forms 4797, 4835, 172, 461, and K-1s; prior MI-461 excess business loss
form: Schedule MI-1045 (loss year); Form 5674 (deduction year); Form 5603 (farming carryback)
line: "Schedule 1 Line 30"
via:
  - Schedule MI-1045, Line 19 (loss year) → Michigan NOL carryforward
  - MI-461, Line 10, Column E (prior year) → Group 2 NOL
  - Form 5674 → Schedule 1, Line 30 → MI-1040, Line 13
  - Farming NOL carryback → Form 5603 (refund request; do not amend the MI-1040)
---
# Michigan Net Operating Loss Deduction
## Description
Michigan computes its NOL independently of the federal NOL, starting from federal AGI (not taxable income) and removing income and loss attributable to other states and severance-taxed oil, gas, and mineral activity. The federal NOL deduction is added back on Schedule 1 Line 7; the Michigan NOL is deducted on Line 30.
## Computing the loss (Schedule MI-1045, filed with the LOSS-year return)
1. Start with MI-1040 Line 10 AGI; apply the Schedule 1 additions and subtractions listed on the form (Lines 3-12)
2. Line 14: if zero or greater, no Michigan NOL
3. Modifications: add back excess nonbusiness deductions (Part 2), excess capital loss (from federal Form 172), and Michigan-sourced adjustments (SE tax deduction, SE health insurance, educator/moving expenses, PA 24 decoupling items)
4. Line 19 = Michigan NOL available to carry
## Groups and limits
| Group | Loss years | Deduction limit |
|---|---|---|
| Group 1 | 2017 and earlier | Pre-TCJA rules |
| Group 2 CARES | 2018-2020 | 80% of Michigan taxable income before exemptions and previously claimed NOLs (from 2021) |
| Group 2 TCJA | 2021 and later | 80% of Michigan taxable income before exemptions and previously claimed NOLs; carried forward indefinitely |
Farming NOLs may be carried back 2 years (Form 5603 — see ../../payments-and-filing/amended-and-carryback/farming-loss-carryback.md) unless the carryback is waived on MI-1045 (irrevocable). Michigan excess business losses from MI-461 become Group 2 TCJA NOLs in the following year.
## Rules
- Must be claimed in consecutive years; carryover is reduced by amounts absorbed in intervening years, including closed years (Treasury may redetermine closed-year income)
- Refund claims based on an NOL must be within the four-year statute of limitations
- Nonresidents and part-year residents: only Michigan-sourced income or loss creates a Michigan NOL; put the federal NOL in Schedule NR Line 11 Column C and claim the Michigan NOL on Schedule 1 Line 30
## Required Information
- Loss-year MI-1045 and all loss-year federal schedules
- Treasury's Michigan NOL Carryover Worksheet (tracking by year and group)
- Form 5674 for the current year
## Questions
- In which year did the loss arise, and was it Michigan-sourced?
- Is any of the loss from farming?
- Did you have a Michigan excess business loss on MI-461 last year?
## Common Errors
- Using the federal NOL amount for Michigan
- Skipping a year in the carryforward chain
- Not applying the 80% limit to Group 2 NOLs
- Amending the MI-1040 for a farming carryback instead of filing Form 5603
## Prompt
- I had a business loss last year. Can I use it on my Michigan return?
