---
type: credit
jurisdiction: Minnesota
tax_year: 2026
category: other
aliases: ["Deduction for Repaying Taxed Income", "Repaying Taxed Income Deduction", "Claim of Right"]
source_doc: Proof of repayment (amount, date, original tax year) / recomputed prior-year Minnesota return without the repaid income
form: Form M1
line: "22 (credit) / via Schedule M1SA (deduction)"
refundable: yes (credit option)
via:
  - Credit option — recomputed prior-year tax → Schedule M1REF, Line 11 → Form M1, Line 22
  - Deduction option — Schedule M1SA, Line 26 → Schedule M1SA, Line 29 → Form M1, Line 4
routing:
  - "Repayment in the SAME year the income was received → no Minnesota adjustment (may affect the federal return)"
  - "Repayment in a later year of $3,000 or less → itemized deduction on Schedule M1SA, Line 26 only (must itemize)"
  - "Repayment in a later year over $3,000 → choose the M1SA deduction OR the claim-of-right credit on Schedule M1REF Line 11"
federal_counterpart: "IRC section 1341 claim of right (federal Schedule A or Schedule 3 credit)"
---
# Repaying Taxed Income (Claim of Right) — Deduction or Credit
## Description
Relief for repaying, in 2026, income that was taxed in an earlier year because the taxpayer appeared to have an unrestricted right to it — for example, repaid unemployment benefits, employer-provided disability benefits, or a clawed-back bonus. Revenue lists this as the "Deduction for Repaying Taxed Income," but for repayments over $3,000 there is also a refundable CREDIT option.
## The two options
1. DEDUCTION: an itemized deduction on Schedule M1SA, Line 26 (Other Miscellaneous Deductions), available only if Minnesota itemized deductions are claimed. On the 2026 Schedule M1SA, Line 26 sits OUTSIDE the 2% floor (only Line 23 unreimbursed employee expenses is reduced by 2% of AGI on Line 24). The 2026 Schedule M1REF instructions and Revenue's web page still describe a 2% floor — a conflict to resolve against the final instructions
2. CREDIT (repayments over $3,000 only): recompute Minnesota tax for the original year without the repaid income. The credit is the difference between the original-year tax with and without the income. Refundable, on Schedule M1REF, Line 11 (2026 line number)
Pick whichever is worth more. Minnesota still allows miscellaneous itemized deductions subject to the 2% floor, unlike the federal return.
## Line-number note
Revenue's general web page still cites older line numbers (M1SA line 24, M1REF line 10). Use the 2026 schedules: M1REF Line 11 for the credit and M1SA Line 26 for the deduction.
## Required Information
- Documentation of the repayment (amount, date, which year's income)
- Recomputed prior-year Minnesota return (credit option)
- Other miscellaneous itemized deductions and federal AGI (deduction option)
## Questions
- Did you pay back in 2026 income you reported in an earlier year? How much?
- Do you itemize on your Minnesota return?
## Common Errors
- Claiming the credit for a repayment of $3,000 or less
- Taking the deduction without itemizing
- Not attaching the recomputed return for the credit
## Prompt
- I had to pay back unemployment I received last year.
- My employer made me repay a bonus from last year.
