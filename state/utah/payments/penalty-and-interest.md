---
type: payment
category: payments
jurisdiction: UT
tax_year: 2026
source_doc: Filing date and payment dates / prepayment records (withholding, TC-546 payments, refunds applied) for the extension prepayment test
form: Form TC-40
line: "37"
via:
  - Not computed on the return (firm policy 2026-10-06) → line 37 left blank → Tax Commission bills the taxpayer
---
# Penalty and Interest
## Description
Utah charges penalties for late filing, late payment, underpaying an extension prepayment, and failing to file information returns (UCA §59-1-401), plus interest on unpaid tax. Computed under Pub 58, Utah Interest and Penalties.

## Status for 2026 — not supported
NOT SUPPORTED — firm policy 2026-10-06: line 37 is left blank and the Tax Commission bills any penalty and interest. Kept so the product can warn the taxpayer when a penalty is likely.

## When to warn
- Return filed after October 15, 2027, or after April 15, 2027 without enough prepayment
- Balance due not paid by April 15, 2027
- EXTENSION PREPAYMENT PENALTY: 2% of the unpaid tax per month of the extension period if less than 90% of 2026 tax (or 100% of 2025 liability) was prepaid by April 15, 2027
- If the return is not filed by the extension due date, regular failure-to-file and pay penalties apply as if there were no extension

## Notes
- No late-filing penalty (including on amended returns) when there is no tax due
- Interest runs from April 15, 2027 until paid. The 2027 interest rate is not yet published (shown as "XX" in the 10/5/26 draft instructions)

## Required Information
- Date the return will be filed
- Dates and amounts of payments made by April 15, 2027 (withholding, prepayments, 2025 refund applied)
- 2025 Utah tax liability, for the 100% safe harbor

## Questions
- Are you filing after April 15, 2027?
- How much did you prepay by April 15, 2027?

## Common Errors
- Assuming an extension avoids interest
- Expecting a late-filing penalty on a refund return

## Prompt
- I'm filing late. Will Utah charge a penalty?
