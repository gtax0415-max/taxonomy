---
type: tax
category: tax-computation
jurisdiction: AR
tax_year: 2026
source_doc: Total income from all sources, taxable or not (W-2s, 1099s, SSA-1099, RRB-1099, and other income records) / number of dependents
form: Form AR1000F
line: "26, 27, 29"
via:
  - AGI (line 25) → Low Income Tax Table for the filing status and dependents → Form AR1000F, line 29 (line 27 = 0)
---
# Low Income Tax Tables
## Description
Tax tables for lower-income filers with the standard deduction built in, which give a lower tax than the Regular table.

## Amounts
Tables and 2025 income limits (2026 tables not yet published):
- Status 1 (single): $17,500
- Status 2 (married filing jointly), one or no dependents: $29,000
- Status 2, two or more dependents: $36,100
- Status 3 or 6, one or no dependents: $25,300
- Status 3 or 6, two or more dependents: see the printed table
- 2026: the 2025 printed tables are carried until DFA publishes the 2026 tables (template Update Log)

## Eligibility
- TOTAL income from all sources, taxable or not (including Social Security), must be within the limit
- Married couples must file Status 2
- Not available when claiming the military pay, military retirement, or $6,000 retirement exemption (the taxpayer may give up the exemption to qualify)
- Not available when itemizing; line 27 is zero

## Required Information
- Total income from all sources, including nontaxable income
- Filing status and number of dependents
- Whether a military or retirement exemption is claimed

## Questions
- What is your total income from all sources, including Social Security?
- Do you claim the military or retirement exemption?
- How many dependents do you have?

## Common Errors
- Testing only Arkansas AGI instead of all income
- Using a low income table with itemized deductions or with Status 4/5
- Not comparing: giving up the retirement exemption can sometimes lower the tax

## Prompt
- My income is low. Is there a special Arkansas tax table?
- Can I use the low income tax table with Social Security income?
