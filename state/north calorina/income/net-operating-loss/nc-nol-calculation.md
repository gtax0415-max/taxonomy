---
type: deduction
category: net-operating-loss
jurisdiction: NC
tax_year: "2026"
source_doc: Completed Form D-400 with Schedule S and Schedule A / federal Schedule D (Lines 7 and 15) / federal Form 461 (excess business loss) / records separating business from nonbusiness income, deductions, capital gains, and capital losses / Schedule PN for part-year and nonresidents
form: Form D-400
line: "9"
via:
  - Form NC-NOL, Part 1, Line 24 (NC NOL for the year) → carried to next year's Form NC-NOL, Part 2B, Column A
---
# North Carolina NOL Calculation (Form NC-NOL, Part 1)
## Description
Determines whether you have an NC NOL for the year. The NC NOL is the amount by which BUSINESS deductions exceed income, measured under the Internal Revenue Code with North Carolina adjustments, and then stripped of items that cannot create a loss.
## Items that cannot create an NC NOL (G.S. 105-153.5A(a), as rewritten for 2026)
- Capital losses in excess of capital gains
- The IRC 1202 exclusion for qualified small business stock
- Nonbusiness deductions in excess of nonbusiness income
- The NC NOL deduction itself
- The IRC 199A qualified business income deduction
- The North Carolina CHILD DEDUCTION (which is why D-400 Line 10b never enters Line 1g)
## Item that IS fully allowed (new statutory text for 2026)
- A federal EXCESS BUSINESS LOSS under IRC 461(l) is fully allowed as a State NOL. This is why the federal excess business loss added back as Other Income is subtracted on Line 1f
## Line flow
| Line | Entry |
|---|---|
| 1a | Federal AGI (D-400, Line 6) |
| 1b | Additions (D-400, Line 7) |
| 1c | 1a + 1b |
| 1d | Deductions from federal AGI (D-400, Line 9) |
| 1e | NC standard or itemized deduction (D-400, Line 11) |
| 1f | Excess business loss included as Other Income on the federal return |
| 1g | 1d + 1e + 1f |
| 1 | 1c − 1g |
| 2 / 3 | Nonbusiness capital losses / nonbusiness capital gains (gains without the 1202 exclusion) |
| 4 / 5 | Excess nonbusiness capital loss / excess nonbusiness capital gain |
| 6 | Nonbusiness deductions |
| 7 | Nonbusiness income other than capital gains |
| 8 | 5 + 7 |
| 9 | Excess of Line 6 over Line 8 — added back |
| 10 | Excess of Line 8 over Line 6, not more than Line 5 |
| 11 / 12 | Business capital losses / business capital gains (without the 1202 exclusion) |
| 13 | 10 + 12 |
| 14 | 11 − 13 (not below zero) |
| 15 | 4 + 14 |
| 16a-16c | Net short-term (Sch. D Line 7) + net long-term (Sch. D Line 15); if a loss, enter as positive on Line 16 |
| 17 | IRC 1202 exclusion |
| 18 | 16 − 17 (not below zero) |
| 19 | Smaller of Line 16 or $3,000 ($1,500 MFS) |
| 20 / 21 | Excess of 18 over 19 / excess of 19 over 18 |
| 22 | 15 − 20 (or Line 15 if Lines 16-21 were skipped) |
| 23 | NC NOL deduction for prior-year losses (added back) |
| 24 | 1 + 9 + 17 + 21 + 22 + 23. If NEGATIVE, that is the NC NOL |
Skip Lines 16-21 if there is no net capital loss on Line 16c and no 1202 exclusion; carry Line 15 to Line 22.
## Business versus nonbusiness — the classification that drives the result
| Nonbusiness deductions (Line 6) | Business deductions (NOT on Line 6) |
|---|---|
| IRA and self-employed retirement plan contributions | Deductible part of self-employment tax |
| HSA deduction | Self-employed health insurance |
| The NC standard or itemized deduction from Line 1e | Rental losses |
| Bailey, uniformed services retirement, and Social Security subtractions | Loss on business real estate or depreciable property |
| G.S. 105-153.5(c3) deduction for nonbusiness PTE income | Share of partnership or S corporation business loss |
| | Section 1244 and small business stock ordinary losses |
| | Expense reduced by a federal credit (Schedule S Line 29) |
| Nonbusiness income (Line 7) | Business income (NOT on Line 7) |
|---|---|
| Taxable IRA distributions, pensions, annuities | Wages and salaries |
| Dividends and investment interest | Self-employment income |
| Share of nonbusiness PTE income | Unemployment compensation |
| Nonbusiness additions, e.g. student loan discharge add-back | Rental income |
| | Ordinary gain on business property |
| | Share of PTE business income, and business-related additions (e.g., bonus, Section 179, and domestic R&E add-backs) |
Federal itemized deductions that North Carolina does not allow are NOT nonbusiness deductions here — use only the North Carolina amount.
## Part-year residents and nonresidents
| NC-NOL line | Enter |
|---|---|
| 1a | Schedule PN, Line 16, Column B |
| 1b | Schedule PN, Line 18, Column B |
| 1d | Schedule PN, Line 20, Column B |
| 1e | Schedule PN, Line 24 (taxable percentage) × D-400, Line 11 |
| 1f | Excess business loss included in Schedule PN, Line 15, Column B |
| 19 | $3,000 ($1,500 MFS) × Schedule PN, Line 24, then the smaller of Line 16 or that number |
On Lines 2, 3, 6, 7, 11, 12, 16a, 16b, and 17, include only amounts in Schedule PN, Column B.
## Estates and trusts
Line 1a is Form D-407, Line 1 plus the charitable deduction, income distribution deduction, and exemption from Form 1041; Lines 1b, 1d, 1f, 16a, and 16b come from D-407 and Form 1041, excluding anything on D-407, Line 6.
## Required Information
- Completed D-400 and schedules
- Business/nonbusiness split of every income and deduction item
- Federal Schedule D and Form 461
## Questions
- Which of your losses come from a trade or business, including rentals and pass-throughs?
- Did you have capital losses, and were they business or investment?
- Did you exclude gain under IRC 1202?
## Common Errors
- Classifying rental losses or self-employment tax as nonbusiness
- Counting the full capital loss rather than the $3,000 limited amount
- Letting the standard deduction create or enlarge an NOL
- Using federal itemized deductions North Carolina does not allow
## Prompt
- Do I have a North Carolina net operating loss?
- How do I fill out Form NC-NOL Part 1?
