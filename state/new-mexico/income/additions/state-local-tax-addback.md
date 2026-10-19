---
type: addition
category: additions
jurisdiction: NM
tax_year: 2026
source_doc: Form 1040 Schedule A as filed (lines 5a, 5b, 5c, 5d, 5e and 17) and Form 1040 standard deduction amount / Form W-2 box 17 and estimated-tax payment records (state income tax) or sales tax records
form: Form PIT-1
line: "10"
via:
  - Schedule A Line 5a share of Line 5e, limited to itemized deductions over the standard deduction (PIT-1 worksheet) → PIT-1, Line 10 → PIT-1, Line 17
---
# State and Local Tax Addback (Line 10)
## Description
New Mexico lets itemizers subtract their federal itemized deductions, but not the state and local income or general sales tax included in them. That part is added back on PIT-1 line 10 (not on PIT-ADJ).

## Amount (PIT-1 line 10 worksheet)
- Find the income or sales tax share of the SALT actually deducted: Schedule A line 5e × (line 5a ÷ line 5d)
- Limit it to the amount by which total itemized deductions exceed the standard deduction you could have taken
- Zero if you took the federal standard deduction
- Real estate and personal property taxes (lines 5b and 5c) are NOT added back

## Example (2026, single)
Line 5a $12,000 income tax, 5b $6,000 property tax, 5d $18,000, 5e $18,000 (under the cap); itemized total $30,000; standard deduction $16,100.
- Share: $18,000 × 12,000/18,000 = $12,000
- Limit: $30,000 − $16,100 = $13,900
- Addback: $12,000

## Why it matters more in 2026
H.R.1 raised the federal SALT cap to $40,400 for 2026, reduced (not below $10,000) for modified AGI above $505,000 ($20,200 and $252,500 married filing separately). More New Mexico itemizers now deduct substantial state income tax federally, so this addback grows. The cap reaches line 10 through Schedule A line 5e.

## Status for 2026
No change to the New Mexico rule from the 2026 legislative session. Confirm the worksheet on the 2026 PIT-1.

## Required Information
- Schedule A lines 5a–5e and 17
- Standard deduction for the filing status
- Whether income tax or sales tax was elected on line 5a

## Questions
- Did you itemize on your federal return?
- Did you deduct state income tax or general sales tax?
- Was your SALT deduction limited by the federal cap?

## Common Errors
- Adding back property taxes
- Adding back the full line 5a amount when the cap limited line 5e
- Skipping the itemized-over-standard limit
- Making the addition when the standard deduction was used

## Prompt
- I itemized and deducted my New Mexico income tax.
- Do I have to add back state taxes I deducted federally?
