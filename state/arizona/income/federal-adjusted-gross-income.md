---
type: income
category: federal-agi
jurisdiction: AZ
tax_year: 2026
source_doc: Forms W-2 Box 1, 1099 (INT, DIV, B, R, NEC, MISC, K, G), SSA-1099 and Schedule K-1 / records of federal adjustments (for example Form 5498-SA HSA contributions, Form 1098-E student loan interest)
form: Form 140
line: "12"
via:
  - U.S. Form 1040 adjusted gross income → Form 140, line 12 → line 14 → line 19
routing:
  - "No federal return required → still complete a 2026 federal return to find federal AGI"
  - "Federal AGI over $75,000 ($150,000 joint) → estimated payments for 2027 may be required"
  - "Federal AGI is also the base for the Dependent Tax Credit phase-out and the Increased Excise Tax Credit limit"
see_also:
  - income/income.md
  - filing/federal-conformity-and-2026-law.md
  - payments/estimated-tax-payments.md
  - credits/dependent-tax-credit.md
  - credits/increased-excise-tax-credit.md
---
# Federal Adjusted Gross Income (Form 140, Line 12)
## Description
Enter federal adjusted gross income from the 2026 federal return. Complete the federal return first; if you are not filing a federal return, complete one anyway to determine federal AGI. For a full-year resident, federal AGI is Arizona gross income. Use federal AGI, not federal taxable income.
## Uses of line 12
- Starting point for Arizona taxable income (lines 12 to 45)
- Dependent Tax Credit phase-out: reduced when line 12 is more than $200,000 (single, head of household, married filing separate) or $400,000 (married filing joint) (statutory, unchanged for 2026)
- Increased Excise Tax Credit: line 12 of $25,000 or less (joint or head of household) or $12,500 or less (single or separate) (statutory, unchanged for 2026)
- Estimated payments: if line 12 is more than $75,000 ($150,000 joint), 2027 estimated payments may be required
## Conformity
Arizona follows the Internal Revenue Code as of January 1, 2026 (HB 4168, Laws 2026, Chapter 140, signed June 13, 2026). The 2025 booklet warned that its forms assumed adoption of federal changes; for 2026 the conformity law was enacted before the forms are published.
## Example
Federal Form 1040 shows wages $72,000, taxable interest $500 and an IRA deduction of $3,000: federal AGI $69,500 → line 12 = $69,500.
## Notes
- Form 140 line, box and page item references follow the 2025 Form 140; ADOR had not released the 2026 Form 140 when this was revised, so confirm them against it
## Required Information
- The completed 2026 federal Form 1040 (adjusted gross income line)
- Any amended federal return
## Questions
- What is the adjusted gross income on your 2026 federal return?
- Did you amend the federal return after filing?
## Common Errors
- Entering federal taxable income instead of federal AGI
- Starting the Arizona return before the federal return is final
## Prompt
- What number from my federal return starts the Arizona return?
