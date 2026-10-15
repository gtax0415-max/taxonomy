---
type: payment
category: amount-owed
jurisdiction: CO
tax_year: 2026
source_doc: None — computed from the return (net tax less payments and credits, plus any penalty and interest)
form: Form DR 0104
line: "47"
via:
  - Line 23 net tax − Line 39 payments and credits → Line 43 → + Lines 44–46 → Line 47
routing:
  - "Line 39 greater than line 23 → overpayment; see overpayment-and-refund"
  - "Filed on time, enough paid during the year → line 47 = line 43"
  - "Late filing or late payment → add penalty and interest on lines 44 and 45"
  - "Estimated tax penalty → line 46"
see_also:
  - tax-computation/delinquent-payment-penalty.md
  - tax-computation/delinquent-payment-interest.md
  - tax-computation/estimated-tax-penalty-dr0204.md
---
# Net Tax Due and Amount You Owe
## Description
When net tax (line 23) is more than payments and credits (line 39), the difference is the tax due. Penalty, interest and any estimated tax penalty are added to get the amount owed.

## Amount
- Line 43 = line 23 − line 39
- Line 47 = lines 43 + 44 + 45 + 46

## Notes
- Payment for 2026 is due April 15, 2027
- Pay online through Revenue Online (a fee may apply), by check with the return, or with a payment voucher for an e-filed return; a payment plan can be set up once billed
- Checks are payable to "Colorado Department of Revenue," with the SSN or ITIN and "2026 DR 0104" on the memo line; the State may convert a check to a one-time electronic debit
- Example: line 23 $3,480, line 39 $2,900 → line 43 $580; estimated tax penalty $12 → line 47 $592

## Required Information
- Net tax and total payments from the return
- Any penalty and interest
- Payment method

## Questions
- Will you owe tax for 2026, and how will you pay?
- Are you filing after April 15, 2027?

## Common Errors
- Leaving the estimated tax penalty out of line 47
- Writing the wrong year on the check memo

## Prompt
- How do I pay what I owe on my Colorado return?
