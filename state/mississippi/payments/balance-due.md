---
type: payment
category: payments
jurisdiction: MS
tax_year: 2026
source_doc: Computed from the return; no separate source document (underlying Forms W-2, 1099, and payment records)
form: Form 80-105
line: "35, 37"
via:
  - Line 23 (total tax) − Line 28 (total payments) → Line 35 balance due
  - Line 35 + Line 36 (interest and penalty) → Line 37 total due
---
# Balance Due
## Description
When total tax exceeds total payments, the difference is the balance due. Interest and penalty on line 36 are added to reach the total due.
## Rules
- Due April 15, 2027 for the 2026 return, even if an extension to file is granted
- Pay online through TAP, or by check or money order payable to the Department of Revenue with Form 80-106
- Balances under $1.00 need not be paid
- A taxpayer who cannot pay may request an installment agreement (requested with Form 71-661; not prepared in this system)
- Interest and penalty are not computed in this system (see interest-and-penalty.md)
## Example (2026)
- Total tax $2,000, payments $1,500 → balance due $500
## Required Information
- Lines 23 and 28
## Questions
- Can you pay the balance by April 15, 2027?
## Common Errors
- Assuming an extension delays payment
- Sending cash or omitting the voucher
## Prompt
- I owe Mississippi tax. How do I pay?
