---
type: addition
category: state-income-tax-addback
jurisdiction: CO
tax_year: 2026
source_doc: Federal Schedule A as filed (line 5a state income tax; line 5e capped SALT; total itemized deductions) / Forms W-2 box 17 and state estimated payment records / Colorado K-1 statement showing the owner's share of state income tax deducted by the entity
form: Form DR 0104
line: "2"
via:
  - Schedule A state income tax (limited) + K-1 state income tax share → Form DR 0104, Line 2 → Line 10; also reduces the Line 4 addback
routing:
  - "Itemizer who deducted state income tax → add back, limited as below"
  - "Deducted general sales tax instead → no addback"
  - "Partner or S corporation shareholder → add the K-1 state income tax share (not limited)"
  - "Standard deduction → $0"
see_also:
  - income/additions/standard-itemized-deduction-addback.md
  - income/subtractions/state-income-tax-refund.md
---
# State Income Tax Addback
## Description
Colorado does not allow a deduction for state income taxes. Itemizers add back the state income tax deducted on Schedule A, and pass-through owners add back their share of state income tax the entity deducted.

## Amount
- Schedule A part: the lesser of the state income tax deducted or the amount by which itemized deductions exceed the standard deduction otherwise allowed
- When the federal SALT deduction was capped, state income tax counts last: the addback is the capped SALT deduction minus the other state and local taxes (property tax, etc.)
- 2026 federal SALT cap: $40,400 ($20,200 separate), reduced by 30% of modified AGI over $505,000 ($252,500 separate), but not below $10,000 ($5,000)
- K-1 part: the full share shown

## Notes
- Example: joint itemizers, state income tax $18,000, property tax $9,000 (SALT $27,000, under the cap), itemized deductions $45,000, standard deduction $32,200 → lesser of $18,000 or $12,800 = $12,800

## Required Information
- Schedule A amounts
- Standard deduction for the filing status
- K-1 state tax share

## Questions
- Did you itemize and deduct state income tax?
- Did a partnership or S corporation deduct state income tax for you?

## Common Errors
- Adding back sales tax or property tax
- Adding back more than itemized deductions exceed the standard deduction

## Prompt
- Why do I add back my state income tax in Colorado?
