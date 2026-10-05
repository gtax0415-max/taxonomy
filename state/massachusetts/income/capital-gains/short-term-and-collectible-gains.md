---
type: income
jurisdiction: MA
tax_year: 2026
category: capital-gains
source_doc: Form 1099-B / Form 8949 / U.S. Schedule D Lines 1-5 column h / U.S. Form 4797 (business property held one year or less) / Massachusetts Schedule D Line 12 (collectibles) / prior-year Massachusetts Schedule B Line 40
form: Massachusetts Form 1
line: "23a, 23b"
rate: "8.5% short-term; 12% collectibles and pre-1996 installment sales"
via:
  - U.S. Schedule D Lines 1-5 → Massachusetts Schedule B, Part 2 (Lines 10-28) → Part 3, Line 39 → Form 1, Line 23a (× 8.5%)
  - Massachusetts Schedule D Line 12 → Schedule B, Line 11 → Taxable Capital Gains Worksheet → Form 1, Line 23b (× 12%)
routing:
  - "Net short-term loss → up to $2,000 against interest and dividends (Line 20); remainder against long-term gains (Line 22) or carryover (Line 23 → Line 40)"
  - "Collectible gains → 50% long-term gains deduction (Line 27) before the 12% rate"
---
# Short-Term Capital Gains and Long-Term Collectible Gains (Schedule B, Part 2)
## Description
Short-term capital gains (assets held one year or less) are taxed at 8.5%. Long-term gains on collectibles and pre-1996 installment sales are taxed at 12%, after a 50% long-term gains deduction — an effective 6%.
## Rates
- Short-term capital gains: 8.5% (reduced from 12% beginning 2023)
- Collectibles (IRC 408(m): art, rugs, antiques, metals, gems, stamps, alcoholic beverages, certain coins) and pre-1996 installment sales: 12%, with 50% deduction
- Short-term gain on business property held one year or less (U.S. Form 4797): included here
## Flow
10. Massachusetts short-term gains (U.S. Schedule D Lines 1-5)
11. Long-term collectibles and pre-1996 installment gains (from Schedule D, Line 12)
12. Short-term business property gains (Form 4797)
13-15. Combine; part-year adjustment; Schedule C-2 deductions
16-18. Short-term losses, business property losses, prior short-term carryover
19-23. Net; up to $2,000 against interest and dividends; against long-term gains; carryover
24-28. Short-term and collectible gains; long-term losses applied; 50% long-term gains deduction (collectibles); result
39. Taxable 8.5% and 12% gains → Form 1, Line 23a (or split via the Taxable Capital Gains Worksheet when collectibles exist)
## Notes
- Crypto held one year or less is short-term at 8.5%
- Short-term carryovers go to next year's Schedule B, Line 18
- Excess exemptions can reduce 8.5%/12% income (Schedule B, Line 36)
## Required Information
- Forms 1099-B and 8949 short-term sections
- Identification of collectibles
- Form 4797 short-term business property
- Prior-year Schedule B, Line 40 carryover
## Questions
- Did you sell anything you held one year or less?
- Did you sell any collectibles?
- Do you have a Massachusetts short-term loss carryover?
## Common Errors
- Taxing short-term gains at 5.0%
- Taxing collectibles at 12% without the 50% deduction
- Not carrying the short-term loss to Schedule B, Line 40
## Prompt
- I day-trade stocks. How is that taxed in Massachusetts?
- I sold some gold coins.
