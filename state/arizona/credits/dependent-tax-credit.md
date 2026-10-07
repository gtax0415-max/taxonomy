---
type: credit
category: dependent-credit
jurisdiction: AZ
tax_year: 2026
source_doc: Social Security cards or ITIN letters and birth certificates for each dependent (age at the end of 2026) / Forms W-2 Box 1, 1099 and SSA-1099 and other income records (for the AGI phase-out)
form: Form 140
line: "49"
refundable: no
via:
  - Box 10a x $125 + box 10b x $25 → Table I, line 3 → Table II (phase-out test) → Table III or IV with Table V → Form 140, line 49 → line 52; also Form 301, line 32
routing:
  - "Single, head of household or married filing separate with federal AGI over $200,000 → Table III"
  - "Married filing joint with federal AGI over $400,000 → Table IV"
  - "Excess over the limit greater than $19,000 → no credit"
  - "Person claimed on line 40 or 41 → not counted"
  - "Dependent means a federal dependent; a student released for a federal education credit may still be counted"
see_also:
  - filing/dependent-information.md
  - tax-computation/balance-of-tax.md
  - deductions/exemptions/qualifying-parents-grandparents.md
---
# Dependent Tax Credit (Form 140, Line 49)
## Description
A nonrefundable credit for each qualifying dependent (an individual who qualifies as a dependent for federal purposes):
| Dependent's age at the end of 2026 | 2025 | 2026 |
|---|---|---|
| Under 17 (box 10a) | $100 | $125 |
| 17 or older (box 10b) | $25 | $25 |

The credit is reduced for single, head of household and married filing separate filers whose federal AGI (line 12) is more than $200,000, and for married filing joint filers whose federal AGI is more than $400,000 (phase-out unchanged for 2026). The $125 amount comes from HB 4168 (Laws 2026, Chapter 140), signed June 13, 2026 and retroactive to January 1, 2026. It cannot reduce tax below zero and has no carryover.
## Worksheet
- Table I: line 1 = box 10a count x $125 (2026; $100 on the 2025 table); line 2 = box 10b count x $25; line 3 = credit before adjustment.
- Table II: is federal AGI more than $200,000 (single, separate, head of household) or $400,000 (joint)? If no, enter Table I, line 3 on line 49.
- Table III (single, married filing separate, head of household) or Table IV (married filing joint): 1 federal AGI; 2 limit $200,000 or $400,000; 3 line 1 - line 2 (if more than $19,000, stop: no credit); 4 Table I, line 3; 5 Table V decimal; 6 line 4 x line 5 → line 49.
## Table V
| Line 3 excess | Decimal | Line 3 excess | Decimal |
|---|---|---|---|
| $1 - 1,000 | .95 | $10,001 - 11,000 | .45 |
| $1,001 - 2,000 | .90 | $11,001 - 12,000 | .40 |
| $2,001 - 3,000 | .85 | $12,001 - 13,000 | .35 |
| $3,001 - 4,000 | .80 | $13,001 - 14,000 | .30 |
| $4,001 - 5,000 | .75 | $14,001 - 15,000 | .25 |
| $5,001 - 6,000 | .70 | $15,001 - 16,000 | .20 |
| $6,001 - 7,000 | .65 | $16,001 - 17,000 | .15 |
| $7,001 - 8,000 | .60 | $17,001 - 18,000 | .10 |
| $8,001 - 9,000 | .55 | $18,001 - 19,000 | .05 |
| $9,001 - 10,000 | .50 | $19,001 and over | .00 |
## Surviving spouse
A spouse who died during the year is treated as married at the close of the year if the survivor would have been considered married on the date of death.
## Examples
- Married filing joint, federal AGI $150,000, children 8 and 15, and a 19-year-old dependent: $125 x 2 + $25 x 1 = $275 → line 49 = $275 (no reduction).
- Head of household, federal AGI $203,500, two children under 17: Table I $250; Table III excess $3,500 → Table V .80 → $250 x .80 = $200.
## Notes
- Applied before Form 301 credits: it reduces the Form 301, line 33 limit through line 32
- Form 140 line numbers follow the 2025 Form 140; confirm them against the 2026 Form 140 when ADOR releases it
## Required Information
- Each dependent's name, SSN and age at the end of 2026
- Federal AGI (Form 140, line 12)
- Filing status
## Questions
- How many federal dependents are under 17 and how many 17 or older at the end of 2026?
- What is your federal AGI?
## Common Errors
- Using $100 instead of the 2026 $125
- Applying the joint $400,000 limit to a head of household
- Counting a parent claimed in box 11a or an Other Exemption person
## Prompt
- How much is the Arizona dependent credit for 2026?
