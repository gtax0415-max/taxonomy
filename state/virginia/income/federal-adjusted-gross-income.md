---
type: income
category: federal-starting-point
jurisdiction: VA
tax_year: 2026
source_doc: Completed federal income tax return (Form 1040) showing federal adjusted gross income / for Filing Status 3 after a joint federal return, each spouse's own wages, interest, business, gains, pensions, rents and other income and adjustments
form: Form 760
line: "1, 3"
via:
  - Federal return adjusted gross income → Form 760, Line 1 → Line 3 (Line 1 + Line 2 additions) → Line 9 VAGI
routing:
  - "Filing Status 1 or 2 → the federal AGI from the federal return (joint federal AGI for Filing Status 2)"
  - "Filing Status 3 → only the federal AGI attributable to you"
see_also:
  - income/income.md
  - income/additions/additions.md
  - income/subtractions/subtractions.md
  - filing/filing-status.md
  - tax-computation/spouse-tax-adjustment.md
---
# Federal Adjusted Gross Income (Form 760, Lines 1 and 3)
## Description
Form 760, Line 1 is the starting point of the Virginia return: the adjusted gross income from the federal return. It is federal adjusted gross income, NOT federal taxable income; the federal standard or itemized deduction and other below-the-line federal deductions are not taken here. Line 3 adds Line 1 and the Schedule ADJ additions on Line 2, giving the total before Virginia subtractions.
## Line 1: what to enter
- Enter the federal adjusted gross income from your federal return.
- Filing Status 3 (married filing separately): enter only the amount of income attributable to you. If a joint federal return was filed, split federal AGI between the spouses item by item; the Worksheet for Determining Separate Virginia Adjusted Gross Income (Step 1) lists the pieces: wages; taxable interest and dividends; taxable state and local refunds; business income; capital and other gains or losses; taxable pensions, annuities and IRA distributions; rents, royalties, partnerships, estates and trusts; other income (farm income, taxable Social Security); less adjustments to gross income. The two columns must total the joint federal AGI.
- One resident and one nonresident spouse who do not make the joint residency election: the resident files Filing Status 3 and reports only the resident's share.
- Round to whole dollars (under 50 cents down, 50 to 99 cents up).
- A negative federal AGI is entered as a loss; the draft form carries a "loss" marker at this line.
## Line 3
Line 3 = Line 1 + Line 2 (additions from Schedule ADJ, Line 3). If there are no additions, Line 3 equals Line 1.
## Why the starting figure matters beyond Line 1
- The age deduction worksheet starts from federal AGI (combined for married taxpayers, whatever the filing status), adjusted for conformity additions and subtractions and reduced by taxable Social Security and Tier 1 benefits
- Separate federal AGI for each spouse feeds the Spouse Tax Adjustment Worksheet (Filing Status 2)
- Separate federal AGI shares allocate dependent exemptions and itemized deductions between spouses on Filing Status 3
## Conformity
Virginia's fixed conformity date is December 31, 2025, and Virginia conforms to most 2025 H.R. 1 provisions affecting federal AGI. Where Virginia does not conform (bonus depreciation, certain business expensing provisions, section 179 amounts above the Virginia limits), the difference is fixed on Schedule ADJ as a conformity addition (Line 2a) or subtraction (Line 6a), not by changing Line 1.
## Questions
- What is the adjusted gross income on your federal return (not taxable income)?
- Did you file a joint federal return but want to file separately in Virginia?
- If so, whose name is on each W-2, 1099, account and business?
- Did you amend your federal return or get an IRS change after filing?
## Common Errors
- Entering federal taxable income instead of federal adjusted gross income
- Filing Status 3 filer entering the whole joint federal AGI
- Adjusting Line 1 for nonconformity items instead of using Schedule ADJ
- Forgetting to amend the Virginia return after a federal AGI change
## Prompt
- Which number from my federal return goes on line 1 of the Virginia 760?
- We filed jointly federally; how do we split our income for separate Virginia returns?
- My federal AGI is negative this year because of a business loss.
