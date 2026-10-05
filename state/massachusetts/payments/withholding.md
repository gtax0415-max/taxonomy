---
type: payment
jurisdiction: MA
tax_year: 2026
category: payments
source_doc: Form W-2 Box 17 (state = MA) / Forms 1099-R, 1099-INT, 1099-DIV, 1099-G, 1099-MISC/NEC with Massachusetts withholding / Form LOA / Form PWH-WA / Form W-2G / Massachusetts Form 2G / Massachusetts Schedules 2K-1, 3K-1, SK-1 (pass-through withholding) / Form NRW (real estate withholding)
form: Massachusetts Form 1 / Schedule 62-WH
line: "38a, 38b, 38c, 50"
via:
  - W-2 Box 17 → Form 1, Line 38a
  - 1099, LOA, PWH-WA → Schedule 62-WH Part 1, Line 5 → Form 1, Line 38b
  - W-2G, 2G, Massachusetts K-1s (2K-1, 3K-1, SK-1) → Schedule 62-WH Part 2, Line 5 → Form 1, Line 38c
  - Form NRW → Schedule 62-WH Part 3, Line 5 → Form 1, Line 50
routing:
  - "Withholding from W-2 → Line 38a; enclose W-2s"
  - "Withholding on any 1099 → Schedule 62-WH required"
  - "Pass-through entity withholding on a Massachusetts K-1 → Schedule 62-WH Part 2 (separate from the PTE excise CREDIT, which goes on Schedule CMS)"
  - "Real estate sale withholding (Form NRW) → Line 50 via Schedule 62-WH Part 3"
  - "More than four forms in a part → Schedule 62-WH continuation sheet"
---
# Massachusetts Income Tax Withholding (Lines 38 and 50; Schedule 62-WH)
## Description
Massachusetts income tax withheld during the year is claimed as a payment. W-2 withholding goes directly on Line 38a; every other kind requires Schedule 62-WH, which identifies each payer by name, ID and amount.
## Schedule 62-WH parts
| Part | Sources | Form 1 line |
|---|---|---|
| 1 | Forms 1099 (retirement, interest, dividends, unemployment, other), LOA (lottery), PWH-WA (pass-through withholding agreements) | 38b |
| 2 | Forms W-2G, Massachusetts 2G, Massachusetts K-1s (2K-1, 3K-1, SK-1) | 38c |
| 3 | Forms NRW — withholding on sales of Massachusetts real estate | 50 |
## Real estate sale withholding (new)
For closings on or after November 1, 2025, sales of Massachusetts real estate with a gross sales price of $1,000,000 or more are subject to withholding on the gross sales price, or on the seller's estimated net gain if elected. Many exemptions apply — including sales by Massachusetts residents — but reporting requirements apply to all sellers. The seller reports the gain on the return for the year of sale and claims the withholding on Line 50 (Form 1-NR/PY, Line 54). Non-resident trusts are also covered. See 830 CMR 62B.2.4.
## Notes
- Withholding is treated as paid evenly through the year for the M-2210 calculation unless actual dates are shown
- PTE withholding (tax withheld by a pass-through entity on a nonresident member) is NOT the 90% PTE excise credit — both may appear on a K-1, but they go to different places
- Excess PFML contributions are not withholding — see excess-pfml-contributions.md
- Enclose every W-2, 1099, W-2G, K-1 and NRW showing Massachusetts withholding; missing documents delay processing
## Questions
- Which of your forms show Massachusetts income tax withheld?
- Did a partnership or S corporation withhold Massachusetts tax for you?
- Did you sell Massachusetts real estate for $1,000,000 or more?
## Common Errors
- Including withholding for another state
- Claiming 1099 withholding without Schedule 62-WH
- Confusing K-1 withholding with the PTE excise credit
## Prompt
- My 1099-R shows Massachusetts tax withheld.
- Massachusetts withheld tax when I sold my house.
