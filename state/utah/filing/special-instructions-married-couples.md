---
type: filing
category: filing
jurisdiction: UT
tax_year: 2026
source_doc: 2026 federal Form 1040 filed jointly / each spouse's residency facts (driver's license, voter registration, days in Utah) / each spouse's share of income (W-2s, 1099s, K-1s)
form: Form TC-40
line: "Page 1, Filing Status (Special instructions)"
via:
  - Federal joint return + spouses with different Utah residency → "(Special instructions)" box on Form TC-40, page 1 → separate Utah returns
---
# Special Instructions for Married Couples
## Description
Covers married couples who filed a JOINT federal return but whose Utah situations differ, chiefly one spouse a full-year Utah resident and the other a full-year nonresident. In that case the couple may file separate Utah returns, dividing the joint federal figures between the spouses.

## Status for 2026 — out of scope
OUT OF SCOPE — team decision 2026-09-30: full-year residents with Utah income only. Kept for routing: marking "(Special instructions)", or a joint return with one spouse not a full-year Utah resident, should stop the flow and flag the return.

## Notes
- Mark "(Special instructions)" for filing status on page 1
- Related domicile rule: a spouse is NOT pulled into Utah domicile if both spouses filed MFS federally, or if the other spouse's domicile rests on Test 2 and the conditions in residency.md are met
- Nonresident military spouses use subtraction SU011PT instead

## Unverified
The step-by-step allocation method in the 2026 instructions could not be retrieved (it sits past the portion of the draft booklet available to us). Confirm against the "Special Instructions for Married Couples" section of the 2026 TC-40 instructions before relying on the details above.

## Required Information
- Joint federal return
- Each spouse's residency status and dates for 2026
- Each spouse's share of income, deductions and credits

## Questions
- Did you file a joint federal return?
- Was one spouse a Utah resident all year and the other a nonresident all year?

## Common Errors
- Filing a normal joint Utah return without TC-40_B for the nonresident spouse
- Using this method for part-year situations it does not cover

## Prompt
- I live in Utah but my husband lives in another state; we file jointly federally.
