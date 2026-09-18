---
type: deduction
category: index
jurisdiction: OH
tax_year: 2026
form: Form IT 1040
line: "2b, 4"
source_doc: Federal Form 1040 and Schedules 1, C, D, E, F / contribution statements / military LES or 1099-R / medical receipts
---
# Ohio Deductions
## Description
Ohio does not run a New York-style deduction stack. There is no Ohio standard deduction and no Ohio itemized-deduction schedule. Almost every Ohio-only break that reduces income is a SUBTRACTION on the Ohio Schedule of Adjustments. Those subtractions come off federal AGI before exemptions and before tax.

The only deduction that sits after Ohio AGI is the personal and dependent exemption on IT 1040 line 4.

## Folders
- subtractions/ — Schedule of Adjustments lines 13-46, plus the two new 2026 capital-gain subtractions
- exemptions/ — personal and dependent exemption on IT 1040 line 4
- standard/ — EMPTY BY DESIGN. Ohio has no standard deduction
- itemized/ — EMPTY BY DESIGN. Ohio has no itemized deduction
- conformity.md — what Ohio follows and does not follow from federal law

## Where deductions sit on Form IT 1040
```
Line 1    Federal AGI                         ← starting point
Line 2a   Schedule of Adjustments ADDITIONS   ← state/ohio/income/additions/
Line 2b   Schedule of Adjustments DEDUCTIONS  ← subtractions/
Line 3    Ohio AGI
Line 4    Personal and dependent exemptions   ← exemptions/
Line 5    Ohio taxable income
```

Subtractions reduce Ohio AGI. That matters twice: it cuts the tax base, and it can change MAGI-based tests for exemptions and credits. MAGI is Ohio AGI PLUS the business income deduction, so taking the line 13 business income deduction does not lower MAGI.

## Allocation rule
Items on Schedule of Adjustments pages 19-20 that INCREASE income are additions. They live in state/ohio/income/additions/. Items on pages 20-26 that DECREASE income are deductions. They live here.

| Schedule of Adjustments | Taxonomy folder |
|---|---|
| Lines 1-11 additions | state/ohio/income/additions/ |
| Line 12 total additions → IT 1040 line 2a | state/ohio/income/ |
| Lines 13-46 deductions | state/ohio/deductions/subtractions/ |
| Line 47 total deductions → IT 1040 line 2b | this folder |
| Schedule of Business Income | state/ohio/income/business-income/ |

## 2026 amounts
| Item | 2026 | Source |
|---|---|---|
| Business income deduction | $250,000 / $125,000 MFS | R.C. 5747.01(A)(28); unchanged |
| 529 contribution | $4,000 per beneficiary | R.C. 5747.70; 2025 booklet figure, statute unchanged |
| STABLE / ABLE contribution | $4,000 per beneficiary | R.C. 5747.78; unchanged |
| Homebuyer Plus contribution | $5,000 per account ($10,000 joint), $25,000 lifetime | R.C. 5747.85 |
| Pregnancy resource center | $750 per taxpayer | R.C. 5747.01(A)(44); no 2025-only sunset in current statute |
| Ohio educator expenses | $300 per qualifying educator | R.C. 5747.01(A)(31) |
| Medical savings account deposits | $6,003 was the 2025 cap; 2026 CPI figure not published in a 2026 booklet | R.C. 5747.01(A)(13); cap set under R.C. 3924.66 |
| Organ donor expenses | $10,000 one-time | R.C. 5747.01(A)(22) |
| Qualifying capital gain, sale of a business interest | NEW: lesser of the gain from each entity or that entity's deductible payroll, aggregated | R.C. 5747.01(A)(34) and 5747.79, taxable years beginning in or after 2026 |
| Ohio VCOC capital gain | NEW: 100% Ohio-business slice / 50% other-business slice | R.C. 5747.01(A)(35), taxable years beginning in or after 2026 |
| Personal exemption | $2,400 / $2,150 / $1,900 / $0; MAGI cliff now $500,000 | R.C. 5747.025 as amended by H.B. 96. Indexing suspended for 2025 and 2026 by Section 757.120(A), so these amounts are fixed for 2026 |

Line numbers above are from the 2025 Schedule of Adjustments. Ohio has not published the 2026 IT 1040 booklet; the two new capital-gain subtractions will add or reuse lines when that booklet ships.

## Ordering rule for the 2026 capital-gain subtractions
When either new capital gain is business income, it comes off under (A)(34) or (A)(35) BEFORE the $250,000 business income deduction in (A)(28). R.C. 5747.01(A)(34) and (A)(35)(d). Only what survives enters the line 13 deduction, and only what survives that is taxed at 3%.

## Context: 2026 rate cut
For taxable years beginning in 2026, nonbusiness income is $332 plus 2.75% of the amount over $26,050. Business income above the deduction remains a flat 3%. A $1,000 subtraction saves about $27.50 of nonbusiness tax in 2026, less than it saved at the 2025 3.125% top rate.

## Related
- Additions — see state/ohio/income/additions/
- Credits after tax is computed — see state/ohio/credits/
- New York deductions, for a state-to-state comparison — see state/new-york/deductions/deductions.md

## Questions
- Do you have a Schedule of Adjustments deduction, or are you looking for a standard deduction Ohio does not have?
- Did you take the business income deduction, and do you know that MAGI adds it back?
- Do you have a 2026 capital gain from an Ohio venture capital operating company, or from selling an ownership interest in an Ohio-headquartered business?

## Prompt
- What deductions can I take in Ohio?
- Does Ohio have a standard deduction?
- Does Ohio tax Social Security?
