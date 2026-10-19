---
type: payment
category: payments
jurisdiction: AR
tax_year: 2026
source_doc: Forms W-2 (box 17 Arkansas income tax) / Forms W-2G (box 15) / Forms 1099-R (box 14), 1099-NEC/MISC (state withholding box) / Arkansas AR K-1 or AR1099PT showing tax withheld or paid for the owner
form: Form AR1000F
line: "39A, 39B"
via:
  - W-2 / W-2G Arkansas withholding → Form AR1000F, line 39A → line 44
  - 1099-R / 1099-PT / AR K-1 withholding → Form AR1000F, line 39B → line 44
---
# Arkansas Income Tax Withheld
## Description
Arkansas income tax withheld during 2026, split between wage and gambling withholding (39A) and withholding on retirement, pass-through, and other 1099 income (39B).

## Notes
- Line 39A: Arkansas tax withheld on W-2s and W-2Gs; attach them
- Line 39B: Arkansas tax withheld on 1099-Rs, 1099-PTs, and AR K-1s; attach them
- Only ARKANSAS withholding; other states' withholding is not entered
- 2026 withholding reflects the 3.7% top rate from pay period 15, 2026 onward

## Required Information
- Every W-2, W-2G, 1099, and AR K-1 with Arkansas withholding
- Status 4: withholding split by spouse

## Questions
- Do you have W-2s, W-2Gs, or 1099s showing Arkansas tax withheld?
- Did a pass-through entity pay Arkansas tax for you?
- Was Arkansas tax withheld from a pension or IRA?

## Common Errors
- Entering federal or another state's withholding
- Putting 1099-R withholding on 39A
- Missing a W-2G

## Prompt
- How much Arkansas tax was withheld from my pay?
- Where do I enter Arkansas tax withheld on my pension?
