---
type: income
category: addition
jurisdiction: VA
tax_year: 2026
source_doc: Form 1099-R reporting the lump-sum distribution / federal Form 4972 (Tax on Lump-Sum Distributions) showing the 20% capital gain election and/or 10-year averaging option
form: Schedule ADJ
line: "2b-2c, code 12"
via:
  - Schedule ADJ, Line 2b or 2c (code 12) → Schedule ADJ, Line 3 → Form 760, Line 2
routing:
  - "Two or fewer addition codes → Schedule ADJ, Lines 2b-2c"
  - "More than two addition codes → Schedule ADJS, Lines 1-10 (total on ADJS Line 11), included in Schedule ADJ, Line 3; fill in the Schedule ADJ oval and enclose ADJS"
---
# Lump-Sum Distribution Income (Schedule ADJ, Lines 2b-2c, code 12)
## Description
A lump-sum distribution from a qualified retirement plan that is taxed on federal Form 4972 using the 20% capital gain election, the 10-year averaging option, or both is taxed outside federal adjusted gross income. Virginia adds the taxable portion back using addition code 12, computed on a three-line table in the instructions.
## Who has it
Only taxpayers who received a lump-sum distribution from a qualified retirement plan AND used the 20% capital gain election, the 10-year averaging option, or both on federal Form 4972. A distribution taxed in the ordinary way is already in federal AGI and needs no addition.
## Computation table
| Line | Entry |
|---|---|
| 1 | Total amount of distribution subject to federal tax (ordinary income and capital gain) |
| 2 | Total federal minimum distribution allowance, federal death benefit exclusion and federal estate tax exclusion |
| 3 | Line 1 minus Line 2 → enter on Schedule ADJ, Line 2b or 2c with code 12 |
## Questions
- Did you receive your entire balance from a retirement plan in one payment?
- Did you (or your preparer) use Form 4972 for the 20% capital gain or 10-year averaging treatment?
- Did the federal computation include a minimum distribution allowance, death benefit exclusion or estate tax exclusion?
## Common Errors
- Skipping the addition because the distribution does not appear in federal AGI
- Adding back the full distribution without subtracting the Line 2 allowances and exclusions
- Making the addition for a distribution that was taxed normally on the federal return
## Prompt
- I took a lump sum from my old pension and used 10-year averaging federally.
