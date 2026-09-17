---
type: income
category: index
jurisdiction: IL
tax_year: 2026
form: Form IL-1040
line: "1, 2, 3, 4"
---
# Illinois Income — Index (IL-1040 Step 2)
## Description
Master index for IL-1040 Step 2, Lines 1-4: how Illinois builds TOTAL INCOME from federal AGI. Illinois has no standard deduction and no itemized deductions; income is federal AGI plus two categories of ADDITIONS. The deductions that follow (Step 3, Lines 5-7) are in the parallel deductions/ folder, and the exemption allowance (Step 4, Line 10) is here because it is the last stop before the rate is applied.
## Step 2 — Income
| Line | Item | File |
|---|---|---|
| 1 | Federal adjusted gross income (Form 1040 Line 11) | federal-agi.md |
| 2 | Federally tax-exempt interest and dividend income (Form 1040 Line 2a) | federally-tax-exempt-interest-and-dividends.md |
| 3 | Other additions (Schedule M Step 2, Line 12) | additions/ |
| 4 | Total income = 1 + 2 + 3 | — |
## The full flow to tax
| Line | What it is | Where |
|---|---|---|
| 4 | Total income | this folder |
| 5-7 | Retirement income, Illinois overpayment, Schedule M subtractions | deductions/ |
| 8 | Total subtractions | deductions/ |
| 9 | BASE INCOME = 4 − 8, not below zero | — |
| 10 | Exemption allowance ($2,925 per person for 2026; zero above $500,000 joint / $250,000 other federal AGI) | exemption-allowance.md |
| 11 | NET INCOME = 9 − 10, not below zero; nonresidents and part-year residents from Schedule NR Line 51 | — |
| 12 | Tax = 4.95% × Line 11 | — |
## Folders and files
- federal-agi.md — Line 1, including the NOL and Allocation Worksheet rules
- federally-tax-exempt-interest-and-dividends.md — Line 2, the addition that applies to the most filers
- additions/ — Line 3: every Schedule M Step 2 item
- exemption-allowance.md — Line 10
- not-allowed.md — what people try to subtract and cannot
- ../deductions/ — Lines 5-7 (Step 3)
## 2026 parameters
- Rate 4.95%, unchanged since 2017
- Exemption allowance $2,925 (Bulletin FY 2026-15; $2,850 for 2025); age 65 and blindness add-ons $1,000 each
- Exemption cliff $500,000 joint / $250,000 other federal AGI
## What changed for 2026
- NEW ADDITION on Line 3: federally excluded Qualified Small Business Stock gain (IRC Section 1202) for tax years ending on or after December 31, 2026 (PA 104-0468, Bulletin FY 2027-01) — see additions/other-additions.md
- The Schedule M Line 11 PTE tax add-back's original sunset (tax years beginning before January 1, 2026) is superseded by the continued PTE election; expect it on the 2026 Schedule M
- Federal OBBBA below-the-line deductions (tips, overtime, seniors, car-loan interest) do not touch federal AGI and therefore do not reduce Illinois income
## Who must file, 2026 (from the IL-1040 general information)
- Resident required to file federally, or with base income above the $2,925 exemption
- Resident claimed as someone's dependent with base income over $2,925, or wanting a refund of withholding (a child's Form 8814 income reported by the parent does not count)
- Part-year resident with income from any source while a resident or Illinois-source income while not
- Nonresident with Illinois base income above the Schedule NR exemption, or wanting a refund of withholding (employer letter required)
- Reciprocal-state residents (IA, KY, MI, WI) working in Illinois file only for non-wage Illinois income or a refund
- Anyone wanting back withholding, estimated payments, or pass-through withholding must file regardless
## Related
- Every IL-1040 line mapped to its file — see state/illinois/il-1040-line-map.md
- Filing status, residency, and Schedule NR — see state/illinois/filing/filing.md
- Deductions — see state/illinois/deductions/deductions.md
- Credits, which come after net income — see state/illinois/credits/illinois-credits.md
- Other taxes added after the credits (Lines 20-22) — see state/illinois/other-taxes/other-taxes.md
