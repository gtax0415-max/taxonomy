---
type: deduction
category: index
jurisdiction: NYS
form: Form IT-201
line: "34, 36"
---
# New York Deductions
## Description
New York runs its own deduction system on top of a federal starting point. It has its own standard deduction, its own itemized deduction rules frozen at pre-2018 federal law, and its own dependent exemption. The gap between federal and New York treatment here is wider than in any other part of the return.
## Folders
- standard/ — New York standard deduction table
- itemized/ — Form IT-196, computed under 2017 federal rules
- exemptions/ — dependent exemption, $1,000 per dependent
- subtractions/ — items removed from federal AGI before deductions apply
- conformity.md — what New York does and does not follow from federal law
## Where deductions sit on Form IT-201
```
Line 19   Federal AGI                    ← the starting point
Lines 20-23  New York additions
Lines 25-31  New York SUBTRACTIONS       ← subtractions/
Line 33   New York AGI (NYAGI)
Line 34   Standard OR itemized deduction ← standard/ and itemized/
Line 35   Line 33 minus line 34
Line 36   Dependent exemption            ← exemptions/
Lines 37-38  Taxable income
```
Two things follow from this order. Subtractions reduce NYAGI, which means they ALSO loosen the itemized deduction limitations that key off NYAGI. And the dependent exemption comes AFTER the deduction, so it is available whether you itemize or not.
## The decoupling that matters most
YOU CAN ITEMIZE FOR NEW YORK EVEN IF YOU TOOK THE FEDERAL STANDARD DEDUCTION. This has been true since 2018 and it is the most valuable and most missed fact in this folder.
Two forces make it common:
- The New York standard deduction is far smaller than the federal one. For 2026 New York gives a married couple $16,050 against the federal $32,200-ish figure. The bar to clear is much lower
- New York itemized deductions are computed under 2017 federal rules, so items the TCJA killed are still deductible for New York: unreimbursed employee expenses, tax preparation fees, investment expenses, non-disaster casualty losses, and state and local taxes without the federal cap
A New York homeowner with property taxes, mortgage interest, and union dues can easily clear $16,050 for New York while taking the federal standard deduction.
## 2026 amounts
| Item | 2026 | Source |
|---|---|---|
| Standard deduction, single | $8,000 | Form IT-2105-I (2026) |
| Standard deduction, married filing jointly | $16,050 | Form IT-2105-I (2026) |
| Dependent exemption | $1,000 per dependent | Form IT-2105-I (2026) |
| Pension and annuity exclusion | $20,000 | 2025 figure used as proxy |
| 529 contribution subtraction | $5,000 / $10,000 joint | 2025 figure used as proxy |
Itemized deduction thresholds and the Form IT-196 limitation figures are indexed and shift slightly each year. Where a 2026 figure was not published, the 2025 figure is carried forward and labeled in the individual file.
## Context: 2026 rate cut
New York cut its bracket rates for 2026 — the bottom brackets fall from 4.00%, 4.50%, 5.25%, 5.50%, and 6.00% to 3.90%, 4.40%, 5.15%, 5.40%, and 5.90%. Lower rates mean every deduction in this folder is worth slightly LESS in 2026 than the same deduction was in 2025. Relevant when deciding whether to accelerate a deductible expense into 2025 or defer it.
## Related
- Federal deductions — see federal/deductions/
- Where an expense can be either a deduction or a credit, both paths are documented — see state/new-york/credits/education/college-tuition-credit.md
## Questions
- Did you itemize on your federal return, and does that change what you should do for New York?
- Do you own a home in New York, or pay large state and local taxes?
- Do you have unreimbursed employee expenses, which are deductible for New York but not federally?
- Is your New York AGI over $100,000, which triggers the itemized deduction limitation?
## Prompt
- What deductions can I take in New York?
- I took the standard deduction federally, should I itemize for New York?
- Does New York follow the federal SALT cap?
