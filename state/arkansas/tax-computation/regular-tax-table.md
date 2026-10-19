---
type: tax
category: tax-computation
jurisdiction: AR
tax_year: 2026
source_doc: Computed from net taxable income on line 28 (no separate source document)
form: Form AR1000F
line: "29"
via:
  - Line 25 − line 27 → line 28 (net taxable income) → Regular Tax Table → Form AR1000F, line 29
---
# Regular Income Tax Table
## Description
The tax table for everyone not using a Low Income Tax Table. Required when itemizing.

## Amounts
2026 rates (Acts 1 and 2 of the 2026 First Extraordinary Session, amending Ark. Code 26-51-201):
Net taxable income $94,700 or less:
- $0 – $5,599: 0%
- $5,600 – $11,199: 2%
- $11,200 – $15,999: 3%
- $16,000 – $26,399: 3.4%
- $26,400 – $94,700: 3.7% (2025: 3.9%)

Net taxable income over $94,700:
- 2% on the first $4,700, 3.7% on the rest
- $94,701 – $97,600: subtract a bracket adjustment of $290 down to $10 (falling $10 per $100 band)
- $97,601 and over: no adjustment

## Notes
- Indexed annually under Ark. Code 26-51-201(d) (3% cap); the statute lists the brackets above, and DFA's 2026 withholding formula uses them. Confirm whether DFA indexes them again for 2026
- The table uses $100 rows; tax is figured at the middle of each row for income up to $100,000
- Over $100,000: the tax equals 3.7% of net taxable income minus $79.90 (about $3,620 at $100,000, plus 3.7% of the excess); the 2025 table printed $3,809 + 3.9% of the excess
- Status 4: each column uses the table separately (see combined-tax-status-4.md)

## Required Information
- Net taxable income on line 28 (each column for Status 4)
- Filing status (Status 4 uses each column)

## Questions
- What is your net taxable income?
- Are you itemizing (Regular table required)?
- Is your income over $94,700?

## Common Errors
- Using 3.9% for 2026
- Using the 2025 "$3,809 + 3.9%" formula above $100,000
- Skipping the bracket adjustment between $94,701 and $97,600

## Prompt
- What is the Arkansas income tax rate for 2026?
- How much Arkansas tax do I owe on $60,000 of taxable income?
