---
type: payment
category: payments
jurisdiction: UT
tax_year: 2026
source_doc: Forms W-2 (boxes a, b, c, 15, 16, 17) / Forms 1099 with Utah state withholding (1099-R, 1099-MISC, 1099-NEC, 1099-G, etc.), including 1099-MISC mineral production withholding
form: Form TC-40
line: "30a"
via:
  - W-2 / 1099 → TC-40_W, Part 1 (one entry per form) → Form TC-40, line 30a → line 30 → line 35
---
# Utah Withholding from W-2s and 1099s
## Description
Credit for Utah income tax withheld by employers and payers. Each form with Utah withholding is listed on TC-40_W, Part 1; the total goes on line 30a.

## Fields per form (TC-40_W, Part 1)
1. Employer/payer ID number (W-2 box b, or 1099 payer TIN)
2. Utah withholding ID (W-2 box 15 or 1099): 14 characters, ending in WTH or WMP, no hyphens
3. Employer/payer name and address (W-2 box c)
4. "X" if the form is a 1099
5. Employee's/recipient's SSN (W-2 box a)
6. Utah wages or income (W-2 box 16)
7. Utah withholding (W-2 box 17)
- Up to four forms per TC-40_W; use more TC-40_Ws if needed

## Notes
- List ONLY forms showing Utah withholding
- Mineral production withholding from 1099-MISC goes in Part 1; mineral production withholding from Utah K-1s goes in Part 2
- Do NOT attach W-2s or 1099s; keep them. Missing or incomplete TC-40_W delays processing and may cause the credit to be denied
- 2026 line number: 30a (2025 return used a different line)

## Required Information
- Every W-2 and 1099 with Utah withholding

## Questions
- Do you have W-2s or 1099s showing Utah tax withheld?
- Any withholding from a pension, IRA, unemployment, or oil and gas royalties?

## Common Errors
- Entering a withholding ID with hyphens or the wrong length
- Including another state's withholding
- Including forms with no Utah withholding
- Attaching W-2s instead of completing TC-40_W

## Prompt
- I have two W-2s and a 1099-R with Utah tax withheld.
