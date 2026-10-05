---
type: index
jurisdiction: MA
category: deductions
form: Massachusetts Form 1
tax_year: 2026
---
# Massachusetts Deductions and Exemptions (Form 1)
## Description
Root index for Massachusetts deductions and exemptions. The structure is very different from the federal return:
- There is NO standard deduction and NO itemized deduction schedule. Federal Schedule A does not carry over
- Instead, Massachusetts allows a closed list of deductions on Form 1, Lines 11-14 and Schedule Y (Line 15)
- Personal and dependent EXEMPTIONS (Line 2) play the role of the standard deduction
- Deductions and exemptions reduce only 5.0% Part B income; only EXCESS exemptions spill over to interest, dividends and capital gains
## Line numbers
From the 2025 Form 1 and Schedule Y. Re-check against the 2026 forms when released.
## Order of computation
1. Line 10 Total 5.0% income
2. Lines 11-15 deductions → Line 16 total
3. Line 17 = Line 10 − Line 16 (not less than 0)
4. Line 18 exemptions (from Line 2g)
5. Line 19 = Line 17 − Line 18 (not less than 0); excess exemptions → Schedule B Line 36 / Schedule D Line 20
## Where each deduction lands
| Line | Deduction | File |
|---|---|---|
| 2a-2d | Personal, dependent, age 65, blindness exemptions | exemptions/personal-and-dependent-exemptions.md |
| 2e | Medical and dental exemption | exemptions/medical-dental-exemption.md |
| 2f | Adoption agency fee exemption | exemptions/adoption-agency-fee-exemption.md |
| 11a/11b | Social Security, Medicare, railroad, U.S. or Massachusetts retirement contributions | adjustments/retirement-contributions-deduction.md |
| 14 | Rental deduction | adjustments/rental-deduction.md |
| 15 | Schedule Y other deductions | schedule-y/schedule-y.md |
| — | Schedule C-2 excess business deductions | business/excess-business-deductions-schedule-c-2.md |
## Federal deductions with NO Massachusetts equivalent (2026)
- Standard deduction; itemized deductions for taxes, mortgage interest, casualty losses, miscellaneous
- IRA, SEP, SIMPLE, Keogh contribution deductions (Massachusetts taxes them; distributions recover basis)
- QBI deduction (Section 199A)
- P.L. 119-21 deductions: tips, overtime, car loan interest, senior deduction (TIR 26-4: not adopted)
- Federal non-itemizer charitable deduction ($1,000/$2,000) — Massachusetts has its own charitable deduction for everyone
## Mapping from federal files
| Federal file | Massachusetts treatment |
|---|---|
| federal/deductions/adjustments/hsa.md | Schedule Y, Line 8 — schedule-y/hsa.md |
| federal/deductions/adjustments/self-employed-health-insurance.md | Schedule Y, Line 7 — schedule-y/self-employed-health-insurance.md |
| federal/deductions/itemized/medical-expenses.md | Exemption, Line 2e — only if itemized federally |
| federal/deductions/itemized/charitable | Schedule Y, Line 9c — no itemizing required |
## Related
- Income: massachusetts/income/income.md
- Credits: massachusetts/credits/credits.md
