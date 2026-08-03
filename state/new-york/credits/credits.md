---
type: credit
category: index
form: Form IT-201
line: "40, 41, 42, 48, 53, 63-71"
---
# New York State Credits
## Description
Personal income tax credits administered by the New York State Department of Taxation and Finance. New York layers four taxing jurisdictions on one return — New York State, New York City, Yonkers, and the MCTMT — so several credits exist in parallel versions that share a single claim form but land on different lines of Form IT-201.
## Folders
- education/ — college tuition credit
- energy-home/ — solar, geothermal, clean heating fuel
- family-dependent/ — Empire State child credit, child and dependent care, household credit
- health-care/ — long-term care insurance, nursing home assessment
- income-based/ — earned income credit, noncustodial parent EIC
- new-york-city/ — NYC-only credits (school tax, income tax elimination, UBT)
- other-jurisdiction/ — resident credit for taxes paid to another state or a Canadian province
- property-housing/ — real property tax credit, STAR, historic homeownership rehabilitation
- civic-volunteer/ — volunteer firefighters and ambulance workers, organ donation
- business-incentive/ — PTET and the ESD-certified program credits
- legacy-carryover/ — credits that generate nothing new but still absorb prior-year carryforwards
## One addition to the federal schema
Every New York credit file carries a `jurisdiction:` key in its frontmatter — `NYS`, `NYC`, `Yonkers`, or `MCTMT`. The federal files do not need this. Some credits carry more than one value where a single form produces both a state and a city credit.
## How credits route on Form IT-201
New York does not use a Schedule 3 equivalent. Credits reach the return three ways:
1. DIRECTLY on a numbered IT-201 line — the high-volume individual credits (lines 63 through 71)
2. THROUGH Form IT-201-ATT — everything else. Nonrefundable state credits total to line 42; NYC nonrefundable credits to line 53; refundable credits to line 71
3. NOT ON THE RETURN AT ALL — STAR arrives as a separate check or direct deposit, and the NYC school tax credit can be claimed on standalone Form NYC-210 by someone who files no return
## Refundable vs nonrefundable
New York marks refundability on its credit tables with two keys: Α means the credit can be refunded even with no tax owed, and Β means you can claim it without filing a return at all. Only three credits carry both: the real property tax credit, the NYC school tax credit (fixed amount), and STAR.
## What changed for 2025
- EMPIRE STATE CHILD CREDIT decoupled from the federal child tax credit and tripled for young children: $1,000 per child under 4, $330 per child 4 through 16. The 4-through-16 amount rises to $500 for 2026
- NEW YORK CITY INCOME TAX ELIMINATION CREDIT created for tax years beginning on or after January 1, 2025 (Form IT-270)
- INFLATION REFUND CHECKS were mailed in fall 2025. These are not a credit — if the amount landed in federal AGI it comes back out as a subtraction on IT-201 line 25
- MCTMT restructured into two zones with separate rates and separate $50,000 thresholds
## What changes for 2026
- NYS EARNED INCOME CREDIT rate rises from 30% to 45% of the federal EIC for tax years beginning on or after January 1, 2026
- EMPIRE STATE CHILD CREDIT for children 4 through 16 rises from $330 to $500
## Related
- Federal credits, which many New York credits are computed from — see federal/credits/credits.md
- New York additions — see state/new-york/income/additions/
- New York subtractions — see state/new-york/deductions/subtractions/
## Questions
- Were you a full-year New York State resident, a part-year resident, or a nonresident?
- Did you live in New York City or Yonkers during any part of the year?
- Which federal credits did you claim, since several New York credits are a percentage of the federal amount?
## Prompt
- What New York credits can I claim?
- I live in NYC and want to know what city credits I qualify for.
- I moved into New York halfway through the year.
