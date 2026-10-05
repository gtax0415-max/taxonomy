---
type: payment
jurisdiction: MA
tax_year: 2026
category: payments
source_doc: Forms W-2 (Box 14 PFML; Boxes 3 and 5 wages) from each employer / Forms 1099-MISC showing PFML withheld / self-employed opt-in PFML contribution records
form: Massachusetts Form 1
line: "49"
via:
  - Line 49 Excess PFML Contributions Worksheet → Form 1, Line 49 → Line 51
routing:
  - "Two or more employers withheld PFML and combined wages exceeded the wage cap → may have an excess"
  - "Only ONE employer over-withheld → get the refund from the employer, not on Line 49"
  - "1099-MISC worker with PFML withheld on gross receipts, or self-employed opt-in paying on gross instead of net → may have an excess"
  - "Joint return → compute each spouse separately and add"
---
# Excess Paid Family and Medical Leave Contributions (Line 49)
## Description
Refund of Paid Family and Medical Leave (PFML) contributions withheld above the annual maximum — typically when several employers each withheld up to the cap. It is treated as a payment. It is NOT the PFML amount on your W-2.
## Caps
| Item | 2025 | 2026 |
|---|---|---|
| Wage cap (Social Security wage base) | $176,100 | $184,500 |
| Employee W-2 / 1099-MISC rate | 0.46% | 0.46% (DFML 2026 rate sheet) |
| Maximum employee contribution | $810.06 | $848.70 |
| Self-employed opt-in rate | 0.88% | 0.88% |
| Self-employed opt-in maximum | $1,549.68 | $1,623.60 |
2026 caution: the FY2026 supplemental budget (St. 2026, c. 101) changed how the family and medical contributions are split between employers and employees for 2026. Use the 2026 Form 1, Line 49 worksheet for the final employee maximum.
## Worksheet (2025 version)
1. Combined W-2 PFML wages (greater of Box 3 or Box 5, reduced for wages not subject to PFML), capped at the wage base
2. Line 1 × 0.0046
3. Lesser of 1099-MISC worker net income or (cap − Line 1)
4. Line 3 × 0.0046
5. Lesser of self-employed opt-in net income or (cap − Lines 1 + 3)
6. Line 5 × 0.0088
7. Total required (Lines 2 + 4 + 6)
8. Actual PFML withheld/contributed (no single employer over the maximum)
9. Excess = Line 8 − Line 7 → Form 1, Line 49
## Related
- PFML benefits are income — income/other-income/pfml-distributions.md
## Questions
- Did you have more than one Massachusetts employer in 2026?
- Were your combined wages over $184,500?
- Are you a 1099 worker or self-employed person who paid PFML?
## Common Errors
- Entering the W-2 PFML amount on Line 49
- Claiming an excess caused by a single employer
- Self-employed computing on gross instead of net earnings
## Prompt
- I had two jobs and both took out PFML.
