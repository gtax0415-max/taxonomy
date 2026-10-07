---
type: credit
category: credit-limitation
jurisdiction: AZ
tax_year: 2026
source_doc: Completed Form 140 (lines 46, 49, 50) / each credit form's available credit / Form 301-SBI, line 63 if the small business income election was made
form: Form 301, Form 140
line: "Form 301 24, 25, 26, 31, 32, 33, 57, 58, 59, 60; Form 140 51"
refundable: no
via:
  - Form 140, line 46 → Form 301, line 26; + recapture (line 30) → line 31; - Family Income and Dependent Tax Credits (line 32) → line 33 (limit)
  - Credits used, lines 34 to 56 → line 58; + Form 301-SBI, line 63 (line 59) → line 60 (not more than line 33) → Form 140, line 51
routing:
  - "Total of credits wanted exceeds line 33 → use credits that cannot be carried over first, then those with limited carryover; the Form 309 credit last"
  - "Small business income election with unused Form 301-SBI credits → line 59"
see_also:
  - credits/nonrefundable-credits-form-301/nonrefundable-credits-form-301.md
  - tax-computation/balance-of-tax.md
  - credits/nonrefundable-credits-form-301/taxes-paid-to-another-state-309.md
---
# Application of Nonrefundable Credits (Form 301, Lines 24 to 26, 31 to 33 and 57 to 60; Form 140, Line 51)
## Description
Form 301, Part 1 totals the credits available (line 25 = lines 1 through 23, column (c); line 24 is reserved). Part 2 limits the credits used to the tax left after the Family Income Tax Credit and the Dependent Tax Credit:
| Line | Entry |
|---|---|
| 26 | Tax from Form 140, line 46 (Form 140PY or 140NR line 56; Form 140X line 37) |
| 31 | Line 26 + line 30 (recapture) |
| 32 | Family Income Tax Credit (Form 140, line 50) + Dependent Tax Credit (line 49) |
| 33 | Line 31 - line 32, not less than 0 |
| 57 | Reserved |
| 58 | Credits used, lines 34 through 56 |
| 59 | Credits used from Form 301-SBI, line 63 |
| 60 | Line 58 + line 59, not more than line 33 → Form 140, line 51 (Form 140PY line 61; Form 140NR line 60; Form 140X line 41) |
## Choosing which credits to use
Each line 34 to 56 cannot exceed the matching Part 1, column (c). Consider each credit's limits and carryforward: credits with no carryover (Form 309, Form 340) are lost if unused, Form 338 carries three years, Form 308-I fifteen years, and most others five years. For the Form 309 credit, Arizona requires all other credits to be applied first.
## Example
Form 140, line 46 $1,445; no recapture; Dependent Tax Credit $250: line 33 = $1,195. Available: QCO $1,009, STO $1,570. Use QCO $1,009 (line 39) and STO $186 (line 41); line 58 = line 60 = $1,195 → Form 140, line 51; the STO balance of $1,384 carries forward.
## Notes
- For 2026 the Dependent Tax Credit rises to $125 per dependent under 17 (Laws 2026, Chapter 140), which increases line 32 and lowers the line 33 limit
- 2026 is the last year for Form 340 donations and for Form 315 carryovers from 2021, so use them before credits with longer carryforwards
- Form 301 line numbers follow the 2025 Form 301; ADOR had not released the 2026 Form 301 when this was revised, so confirm line numbers against it
## Required Information
- Form 140, line 46 (tax), line 47 (recapture), line 49 (Dependent Tax Credit) and line 50 (Family Income Tax Credit)
- Form 301, Part 1, column (c) for every credit
- Form 301-SBI, line 63 if the small business income election was made
## Questions
- What is your tax before credits, and which credits and carryovers are available?
## Common Errors
- Entering credits on line 60 above line 33
- Using carryforward credits ahead of credits that would otherwise expire
## Prompt
- How do I decide which Arizona credits to use first?
