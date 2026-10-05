---
type: income
jurisdiction: MA
tax_year: 2026
category: interest-dividends
source_doc: Form 1099-INT Box 1, Box 3 (U.S. Treasury interest), Box 8 (tax-exempt interest) / Form 1099-DIV Box 1a, Box 3 (nondividend distributions), Box 12 (exempt-interest dividends) / federal Form 1040 Lines 2a, 2b, 3b / U.S. Schedule B / Schedule K-1 interest and dividends / Schedule E-2 and E-3 Lines 9-10
form: Massachusetts Form 1
line: "20"
rate: "5.0% (Part A)"
via:
  - Federal Form 1040 Lines 2a + 2b + U.S. Schedule B Line 6 → Massachusetts Schedule B, Part 1 → Part 3, Line 38 → Form 1, Line 20
routing:
  - "Federal TAX-EXEMPT interest (1040 Line 2a) is INCLUDED in Schedule B, Line 1 — out-of-state munis are taxable"
  - "U.S. Treasury / agency interest and Massachusetts municipal interest → exclude on Schedule B, Line 6a with statement"
  - "Interest and dividends taxed directly to a Massachusetts trust or estate (Form 2) → exclude on Line 6a"
  - "Massachusetts bank interest → Line 5 (subtracted; already on Form 1, Line 5)"
  - "Interest/dividends from partnerships, S corps, trusts → pulled out of Schedule E and reported here"
  - "Interest/dividends from a business → NOT on Schedule C; report on Schedule B, Line 3"
---
# Interest and Dividends (Schedule B, Part 1)
## Description
All interest other than Massachusetts bank interest, plus all ordinary dividends, reported on Schedule B and taxed at 5.0% as Part A income. Flows to Form 1, Line 20.
## Schedule B, Part 1 flow
1. Total interest (federal Form 1040 Lines 2a AND 2b — tax-exempt and taxable)
2. Total ordinary dividends (U.S. Schedule B, Part II, Line 6, or 1040 Line 3b)
3. Other interest and dividends not included above (statement) — including business-related interest and dividends removed from Schedule C or Schedule E
4. Total
5. Less Massachusetts bank interest (Form 1, Line 5)
6a. Less interest on U.S. and Massachusetts obligations and amounts taxed to Massachusetts trusts and estates (statement)
6b. Part-year/nonresident adjustment
7-9. Less allowable trade or business deductions from Schedule C-2 → subtotal (Line 9)
Part 3 then applies up to $2,000 of short-term losses and up to $2,000 of long-term losses, then excess exemptions, and Line 38 → Form 1, Line 20.
## Federal vs. Massachusetts
| Item | Federal | Massachusetts |
|---|---|---|
| Out-of-state state and municipal bond interest | Exempt | TAXABLE |
| Massachusetts state and municipal bond interest | Exempt | Exempt |
| U.S. Treasury bills, notes, bonds, savings bonds | Taxable | EXEMPT |
| Qualified dividends | Preferential rate | Ordinary 5.0% |
| Exempt-interest dividends from muni funds | Exempt | Taxable except the Massachusetts-source portion |
## Losses against interest and dividends
- Up to $2,000 of short-term capital loss (Schedule B, Line 20)
- Up to $2,000 of long-term capital loss (Schedule B, Line 32 / Schedule D, Line 16)
## Excess exemptions
If exemptions exceed 5.0% income after deductions (Form 1, Line 18 > Line 17), the excess reduces interest, dividends and 8.5%/12% income (Schedule B, Line 36), then long-term gains (Schedule D, Line 20). Not available to married filing separately.
## Notes
- Distributions that are returns of capital and dividends taxed to Massachusetts trusts require Schedule B even if nothing else does
- Section 965 inclusions go to Schedule B (see Schedule FCI), not Schedule X
- Interest on federal and Massachusetts tax refunds is taxable here; the refunds themselves are not income
## Required Information
- All Forms 1099-INT and 1099-DIV, including tax-exempt and Treasury boxes
- Fund statements showing the U.S.-government and Massachusetts-source percentages of fund dividends
- K-1 interest and dividends
## Questions
- Do you own municipal bonds or muni funds? Which states issued them?
- Do you own Treasury bills, notes, savings bonds, or a government bond fund?
- Do you have capital losses that could offset up to $2,000 of interest and dividends?
## Common Errors
- Starting from federal TAXABLE interest only and missing out-of-state municipal interest
- Taxing U.S. Treasury interest
- Not applying the government-obligation percentage for mutual funds
- Leaving business interest on Schedule C
## Prompt
- Do I pay Massachusetts tax on my muni bond fund?
- I have Treasury bills. Are they taxed in Massachusetts?
- Where do dividends go on the Massachusetts return?
