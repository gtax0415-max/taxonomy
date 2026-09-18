---
type: income
category: index
jurisdiction: OH
tax_year: 2026
form: Form IT 1040
line: "1, 2a, 2b, 3"
source_doc: Federal Form 1040, 1040-SR, or 1040-NR, line 11a / Ohio Schedule of Adjustments supporting statements
---
# Ohio Income — Index
## Description
Ohio starts from federal adjusted gross income and rebuilds Ohio AGI on the Ohio Schedule of Adjustments. Additions land on IT 1040 line 2a (Schedule of Adjustments line 12). Deductions land on IT 1040 line 2b (Schedule of Adjustments line 47). Ohio AGI is line 3.

There is no Ohio standard deduction and no Ohio itemized-deduction schedule. Almost every Ohio-only income adjustment is a Schedule of Adjustments line.

## The flow to Ohio AGI
| IT 1040 line | Item | File |
|---|---|---|
| 1 | Federal AGI (Form 1040 / 1040-SR / 1040-NR, line 11a) | federal-agi.md |
| 2a | Schedule of Adjustments additions (schedule line 12) | additions/ |
| 2b | Schedule of Adjustments deductions (schedule line 47) | ../deductions/ |
| 3 | Ohio AGI = 1 + 2a − 2b | — |
| 4 | Personal and dependent exemptions | ../deductions/exemptions/exemptions.md |
| 5 | Ohio taxable income = 3 − 4 | — |
| 6 | Taxable business income (Schedule of Business Income Part 3) | business-income/ |
| 7 | Taxable nonbusiness income = 5 − 6 | — |

Business income is pulled out of that stack, deducted up to $250,000 on Schedule of Adjustments line 13, and any leftover business income is taxed at a flat 3% on IT 1040 line 8b. Line 7 carries the rest to the nonbusiness bracket on line 8a. MAGI for credits and exemptions is Ohio AGI plus that business income deduction. See modified-adjusted-gross-income.md.

## Folders and files
- federal-agi.md — IT 1040 line 1
- additions/ — Schedule of Adjustments lines 1–11
- business-income/ — Schedule of Business Income and the $250,000 deduction
- modified-adjusted-gross-income.md — Ohio AGI plus the business income deduction
- ../deductions/ — Schedule of Adjustments lines 13–46 and the exemption on IT 1040 line 4
- ../credits/ — applied after tax is computed

## What changed for 2026
- Nonbusiness tax is $332 plus 2.75% of the amount over $26,050 (H.B. 96, R.C. 5747.02(A)(3)(c)). The first $26,050 is still taxed at 0%. Business income above the deduction stays 3%
- New capital-gain deduction for qualifying Ohio VCOC interests, R.C. 5747.01(A)(35)(a), for taxable years beginning in or after 2026. Recapture is an addition if the Director of Development certifies noncompliance, R.C. 5747.01(A)(35)(b)
- New qualifying capital-gain deduction on the sale of an ownership interest in a business, R.C. 5747.01(A)(34) and R.C. 5747.79, also first available in 2026. The deduction is the lesser of the qualifying capital gain from each entity or the deductible payroll attributable to that entity, aggregated across entities. Enacted in H.B. 110 (2021) with a five-year delayed effective date, same as the VCOC deduction
- Ordering rule: when either capital gain is business income, deduct it under (A)(34) or (A)(35) BEFORE the $250,000 business income deduction in (A)(28). R.C. 5747.01(A)(34) and (A)(35)(d)
- Exemption and joint-filing-credit MAGI cliff drops from $750,000 to $500,000. R.C. 5747.025(A), 5747.05(E)
- Inflation indexing of the brackets and the personal exemption stays suspended for 2026. H.B. 96, Section 757.120(A). The exemption tiers hold at $2,400 / $2,150 / $1,900 and the $26,050 threshold does not move
- Pregnancy resource center deduction continues. R.C. 5747.01(A)(44) has no sunset; the 2025 booklet's "on or after September 30, 2025 and before January 1, 2026" window was just the enactment date through the end of the 2025 tax year
- 2026 IT 1040 booklet not published as of September 2026; Schedule of Adjustments line numbers above are from the 2025 schedule

## Verify when the 2026 booklet ships
- Whether federal AGI is still line 11a of the 2026 Form 1040
- Printed Schedule of Adjustments line numbers for both new capital-gain deductions and the VCOC recapture

## Related
- Credits — see state/ohio/credits/ohio-credits.md
- New York income — see state/new-york/income/income.md
- Illinois income — see state/illinois/income/illinois-income.md
