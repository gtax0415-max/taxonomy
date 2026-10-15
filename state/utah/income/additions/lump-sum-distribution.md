---
type: income
category: additions
jurisdiction: UT
tax_year: 2026
source_doc: Federal Form 4972 as filed (Part II line 6, Part III line 10) / Form 1099-R for the distribution (box 9a if shared)
form: Form TC-40
line: "3"
via:
  - Form 4972 → TC-40_A, Part 5 (code AD001PT) → Form TC-40, line 3
---
# Lump Sum Distribution
## Description
Utah addition for the part of a lump-sum distribution that was taxed separately on federal Form 4972 and therefore left out of federal AGI. Because Utah starts from federal AGI, income taxed under the special federal averaging or capital-gain election would otherwise escape Utah tax entirely.

## Amount
- Addition = Form 4972, Part II, line 6 + Form 4972, Part III, line 10
- SHARED DISTRIBUTION: multiply Form 4972, line 10 by the distribution percentage in Form 1099-R, box 9a, then add Form 4972, Part II, line 6
- Taxed at the 2026 Utah flat rate of 4.45% (down from 4.5% for 2025, SB 60)

## Eligibility
- Applies ONLY if federal Form 4972 was filed with the 2026 federal return
- Form 4972 is limited to plan participants born before January 2, 1936 (or their beneficiaries), so very few 2026 filers will have this addition
- A lump sum that was simply included in federal AGI (no Form 4972) needs no Utah addition

## Notes
- Nonresidents and part-year residents: the full addition goes in TC-40_B, line 15 column B; only the Utah-source portion goes in column A
- Keep Form 4972 and the 1099-R; do not attach them to the Utah return

## Required Information
- Federal Form 4972, Part II line 6 and Part III line 10
- Form 1099-R, including box 9a if the distribution was shared
- Residency status during the year of the distribution

## Questions
- Did you file federal Form 4972 for a lump-sum distribution?
- Was the distribution shared with other beneficiaries (Form 1099-R box 9a)?
- Were you a Utah resident when you received it?

## Common Errors
- Adding back a lump sum that was already included in federal AGI
- Using the full Form 4972 line 10 on a shared distribution instead of applying the box 9a percentage
- Entering only one of the two Form 4972 lines

## Prompt
- I used Form 4972 to tax a lump-sum pension distribution.
- My father's retirement plan paid me a lump sum and I used the special averaging method.
