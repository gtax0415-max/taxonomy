---
type: credit
category: offset-credit
jurisdiction: IN
tax_year: 2026
source_doc: W-2s or other withholding statements showing the non-Indiana locality tax, or a copy of the non-Indiana locality tax return / Schedule CT-40 (county rate, line 2) / IT-40, line 9
form: IT-40 Schedule 6
line: "1"
refundable: false
via:
  - Lesser of A (tax paid to the non-Indiana locality), B (income taxed by that locality x Schedule CT-40, Line 2 rate), C (IT-40, Line 9 county tax) → Schedule 6, Line 1 → Schedule 6, Line 8 → IT-40, Line 13
routing:
  - "No Indiana county tax on IT-40, Line 9 → no credit"
  - "Local tax refunded by the other locality, or that locality gave credit for Indiana county tax → no credit"
  - "Tax paid to another state (not a locality) → Schedule 6, Line 5 instead"
  - "Combined with Lines 2-3 above IT-40, Line 9 → apply this credit first, reduce CRED"
see_also:
  - credits/schedule-6/schedule-6.md
  - credits/schedule-6/combined-limitations.md
  - credits/schedule-6/credit-for-taxes-paid-to-other-states.md
  - tax-computation/tax-computation.md
---
# Credit for Local Taxes Paid Outside Indiana (IT-40 Schedule 6, Line 1)
## Description
If you figured county tax on IT-40, line 9, and also had to pay a local income tax outside Indiana, you may take a credit against your county tax. It applies only if the tax you paid outside Indiana was to another city, county, town or other local governmental entity, and that entity did not refund the tax or give you a credit for Indiana county tax. The credit reduces county tax only. You need both a county tax amount on IT-40, line 9 and a local income tax you had to pay outside Indiana.
## Worksheet
- A. Tax paid to the non-Indiana locality.
- B. Income taxed by the non-Indiana locality x the county rate from Schedule CT-40, line 2.
- C. Indiana county income tax on IT-40, line 9.

The credit is the lesser of A, B or C.
## Combined Limitation
Lines 1 through 3 together cannot be greater than IT-40, line 9. This credit cannot be carried over, so it is applied first, before the community revitalization enhancement district credit.
## Records
Enclose a copy of the W-2s or other withholding statements showing the non-Indiana locality tax withheld, or a copy of the non-Indiana locality's tax return.
## Example
Marion County resident (CT-40 line 2 rate .0202, the same on the 2025 chart and in Departmental Notice #1 for 2026) works in a city in another state that taxes $40,000 of wages and collects $600 of city tax. IT-40 line 9 is $1,100.
- A $600; B $40,000 x .0202 = $808; C $1,100 → credit $600.
## Questions
- Did you pay an income tax to a city, county or other locality outside Indiana?
- Did that locality refund it or give you a credit for Indiana county tax?
- How much income did the locality tax, and what is your Indiana county rate?
## Common Errors
- Claiming the other locality's tax as Indiana county withholding on Schedule 5, line 2
- Claiming state income tax of another state here instead of on line 5
- Omitting the W-2 or local return
- Using the state rate instead of the CT-40 county rate on line B
## Prompt
- I work in a city in another state that taxes my wages. Does Indiana give me a credit against county tax?
