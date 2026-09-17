---
type: income
category: income
jurisdiction: IL
tax_year: 2026
source_doc: Federal Form 1040 or 1040-SR, Line 11 (adjusted gross income) / a PRO FORMA federal Form 1040 completed as a worksheet if you were not required to file federally / federal NOL computations and carryback/carryforward schedules / revised Schedule K-1-P for any partnership Administrative Adjustment Request / the Allocation Worksheet if a joint federal return is split into separate Illinois returns
form: Form IL-1040
line: "1"
via:
  - Federal Form 1040 Line 11 → IL-1040 Line 1
  - Joint federal return, separate Illinois returns → Allocation Worksheet Columns B and C → each spouse's IL-1040 Line 1
---
# Federal Adjusted Gross Income — Line 1
## Description
The starting point for everything. Illinois piggybacks on federal AGI: whatever the IRS taxed after above-the-line deductions is the base, and only the specific additions (Lines 2-3) and subtractions (Lines 5-7) move it. Because Illinois has no itemized or standard deduction, federal AGI — not federal taxable income — is the figure that matters, and every federal above-the-line deduction (HSA, IRA, student loan interest, self-employed health insurance, educator expenses) automatically reduces Illinois income while every federal below-the-line deduction (Schedule A, the standard deduction, QBI) does nothing.
## Amount
Federal Form 1040 or 1040-SR Line 11, as filed. If no federal return was required, complete a federal Form 1040 as a worksheet to derive AGI; the same pro forma return supports the expanded EITC.
## Net operating losses — the one place Illinois departs from the federal number
- A CURRENT-year federal NOL may be entered as a negative Line 1, reduced by any portion carried BACK to prior years
- An NOL CARRYFORWARD deducted federally is limited to the amount actually used against this year's federal taxable income. Any part still available to carry forward to next year must NOT reduce Line 1 — Illinois does not allow the same NOL twice
- Schedule CR Column A Line 15 follows the same rule for the credit computation
## Partnership Administrative Adjustment Requests
If a partnership filed a federal AAR (Form 8082) and elected to report the audit-year change on its CURRENT federal return, Illinois does not follow. The partnership must amend the audit year for Illinois, issue a revised K-1-P, and you must amend that prior Illinois year — then EXCLUDE the change from Line 1 in the current year so it is not taxed twice.
## Split returns — the Allocation Worksheet
Filing jointly for federal but separately for Illinois (injured spouse, or one resident and one nonresident spouse): do not recompute anything federally. Each line of the joint federal return — wages through other adjustments, Lines 1-29 of the worksheet — is divided between Columns B (primary) and C (spouse), and each spouse's share of Line 30 becomes their IL-1040 Line 1. Community-property rules from federal law govern the split. The election is available until the extended due date and is then irrevocable.
## Notes
- Passive activity losses are taken exactly as allowed federally; no Illinois refiguring
- Federal AGI drives three Illinois cliffs even though Illinois taxes base income: the $500,000 / $250,000 limits on the exemption allowance, the property tax credit, and the K-12 credit all test FEDERAL AGI from Line 1
- Federal changes (IRS adjustment or Form 1040-X) that alter AGI require Form IL-1040-X once final; for a federal refund, wait for IRS acceptance first
- 2026: the federal OBBBA changes (no tax on tips and overtime deductions, senior deduction, car-loan interest) are BELOW-the-line federal deductions and do not reduce federal AGI, so they do not reduce Illinois income — tips and overtime remain fully taxable in Illinois
## Required Information
- Form 1040 Line 11
- NOL detail: current-year loss, carryback, carryforward used and remaining
- Revised K-1-Ps from any AAR
- Allocation Worksheet if filing separately in Illinois
## Questions
- What is your federal AGI, or do we need a pro forma federal return?
- Do you have a federal NOL this year or an NOL carryforward not fully used?
- Did a partnership you own file an AAR?
- Did you file jointly federally but need separate Illinois returns?
## Common Errors
- Starting from federal taxable income instead of AGI
- Deducting an unused NOL carryforward on Line 1
- Recomputing federal items when splitting a joint return instead of allocating them
- Assuming the 2026 federal tips and overtime deductions reduce Illinois income
## Prompt
- Where does my Illinois return start, AGI or taxable income?
- I have a federal NOL carryforward, how does Illinois treat it?
- Does Illinois follow the new no-tax-on-tips rule?
