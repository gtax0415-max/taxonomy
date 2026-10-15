---
type: payment
category: payments
jurisdiction: UT
tax_year: 2026
source_doc: Utah Schedule K-1 from the partnership, LLC, S corporation or trust (box A EIN, box B name, Utah withholding paid on your behalf)
form: Form TC-40
line: "30b"
via:
  - Utah Schedule K-1 → TC-40_W, Part 2 (one entry per K-1) → Form TC-40, line 30b → line 30 → line 35
---
# Pass-through Entity Withholding
## Description
Credit for Utah income tax a pass-through entity (partnership, LLC, LLP, S corporation or trust) withheld or paid on the owner's behalf under the mandatory withholding rules (UCA §59-10-1103).

## Fields per K-1 (TC-40_W, Part 2)
1. Entity EIN (Utah K-1 box A)
2. Entity name (Utah K-1 box B)
3. Utah withholding tax paid by the entity
- Up to four K-1s per TC-40_W

## Notes
- DIFFERENT from the elective pass-through entity tax: elective tax paid at the entity level is an addition (AD012PT) plus a nonrefundable credit (NN006PC), not withholding
- Mineral production withholding reported on a Utah K-1 also goes in Part 2
- Do not attach K-1s; keep them

## Required Information
- Each Utah Schedule K-1 showing Utah withholding

## Questions
- Do you own an interest in a partnership, S corporation, LLC or trust that withheld Utah tax for you?
- Did the entity instead elect to pay entity-level tax?

## Common Errors
- Entering elective entity-level tax as withholding
- Using the federal K-1 instead of the Utah K-1
- Omitting the EIN

## Prompt
- My partnership withheld Utah tax for me on my K-1.
