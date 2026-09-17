---
type: credit
category: other-state-tax
jurisdiction: IL
tax_year: 2026
source_doc: The tax return you FILED with the other state (required — the credit is allowed only if you filed a required return there, and the figures come from that return) / Publication 111-C formula for that state to convert its tax to the Schedule CR figure / W-2 state and local wage boxes / local return or W-2 for city or county tax / employer letter on letterhead if Illinois wages on the W-2 are wrong / Schedule K-1-P or K-1-T for pass-through income and PTE tax paid on your behalf / Schedule NR Column B for part-year residents
form: Form IL-1040
line: "15"
refundable: no
via:
  - Schedule CR, Steps 2-4 (non-Illinois portion of base income → decimal) → Step 6 (lesser of other-state tax or decimal × Illinois tax) → Form IL-1040, Line 15
routing:
  - "Full-year resident → Schedule CR Steps 2, 3, 4, 6 → IL-1040 Line 15"
  - "Part-year resident → Schedule CR Steps 2-4 from Schedule NR Column B, plus Step 5, resident-period income only → IL-1040 Line 15"
  - "Nonresident → no Schedule CR; use Schedule NR to exclude non-Illinois income"
---
# Credit for Tax Paid to Other States
## Description
Nonrefundable credit for Illinois residents (and part-year residents, for the resident period) who paid income tax to another state or to one of its cities or counties on income that Illinois also taxes. The credit is the LESSER of the tax actually paid elsewhere and the Illinois tax attributable to the same income, so a filer working in a higher-tax state gets a credit capped at Illinois's 4.95% on the double-taxed income, never a refund of the excess.
## Amount — how Schedule CR computes it
1. Steps 2 and 3 rebuild Illinois base income in two columns: Column A is the total from the federal return (or Schedule NR Column B for part-year residents); Column B is the NON-ILLINOIS portion, line by line, under Illinois sourcing rules
2. Step 4 divides the Column B total by the Column A total to get the Schedule CR DECIMAL — the share of your base income that other states may tax
3. Step 6, Line 51: enter the income tax paid to all other states and localities, AFTER the other state's own credits (except credits for payments you actually made), computed with the Publication 111-C formula for that state
4. Credit = the lesser of Line 51 and (decimal × Illinois tax). Nonrefundable, no carryforward
The decimal, not the other state's own apportionment, controls. Income the other state taxes but Illinois sources to Illinois — nonbusiness interest and dividends, IRA and pension distributions, gains on intangibles — never enters Column B and never produces a credit, even if the other state taxed it.
## What taxes qualify
- Income taxes paid to another U.S. state, the District of Columbia, Puerto Rico, a U.S. territory or possession, or a political subdivision (county, city, local) of any of these
- The tax must be of a kind deductible as state and local income tax on federal Schedule A, whether or not you itemized. An alternative minimum tax measured by income may qualify
- Tax paid on your behalf by withholding or on a composite return counts, but only if you are the person legally liable for it
- Your allocable share of a pass-through entity tax paid to another state that IDOR has determined is substantially similar to Illinois's PTE tax (IITA Section 201(p)) — see the State Reference Chart on IDOR's site. The share is the entity's tax to that state × your share of the entity's income apportioned there ÷ the entity's total income apportioned there
## What does not qualify
- Federal tax, foreign country tax, and foreign subdivision tax
- Interest and penalties, even on an income tax
- Tax on income that is not included on IL-1040 Line 11
- Tax withheld but not actually owed — Line 51 uses the tax from the other state's RETURN, not the W-2, unless a local government does not require a return
- Tax you could have recovered but did not: a filer who never files the other state's return has no credit, because the credit requires a filed return
## What goes in Column B (non-Illinois) — the lines that matter to individuals
- Line 1 wages: wages NOT shown as Illinois wages on the W-2. Exclude wages taxed by another state that are also shown as Illinois wages, and exclude Iowa, Kentucky, Michigan, and Wisconsin wages — unless a city or county there taxed them
- Lines 2, 3, 9, 10, 14: nonbusiness interest, dividends, IRA distributions, pensions, and Social Security are Illinois income. Zero in Column B (only BUSINESS interest and dividends apportioned outside Illinois qualify)
- Line 6 business income, Line 12 farm income: zero if the business was entirely in Illinois, all of it if entirely outside, or the IAF Worksheet (sales inside ÷ sales everywhere) if both
- Line 7 capital gains: gains on real or tangible property located outside Illinois. Gains on stocks and other intangibles are Illinois-sourced and excluded; gains on partnership or S corporation interests follow the entity's three-year average apportionment
- Line 11 rents, royalties, K-1 income: real estate outside Illinois, tangible property to the extent used outside Illinois, and pass-through amounts per the PST Worksheet using the Schedule K-1-P or K-1-T apportionment decimal
- Line 13 unemployment: from any state other than Illinois
- Line 15 other income: only other states' gambling, sports wagering, and lottery winnings, NOL carryforwards, and recoveries of prior-year deductions allocated to other states
- Adjustments (Lines 18-31) follow the income they relate to: educator and reservist expenses in proportion to non-Illinois compensation; self-employment tax, SEP/SIMPLE, and self-employed health insurance by the non-Illinois self-employment (NSE) decimal; IRA deduction by the non-Illinois earned-income ratio; HSA, alimony paid, student loan interest, and Archer MSA in full
## The reciprocal states — Iowa, Kentucky, Michigan, Wisconsin
Wages, salaries, tips, and other employee compensation earned there by an Illinois resident are not taxable by that state. If tax was withheld, file that state's nonresident return for a refund and give the employer Form IL-W-5-NR; Schedule CR may NOT be used. But:
- Cities and counties in those states are not bound by the agreements. Tax paid to a Kentucky city on those wages IS creditable — attach the local return or W-2 showing local wages
- Non-wage income (business income, rentals, gains on real property) from those states is outside the agreements and can produce a credit
- If one of those states treats you as ITS resident under its law while Illinois treats you as an Illinois resident, you may claim credit for that state's tax — attach the out-of-state returns
Check the box on Line 50 for the state whenever you claim a credit involving any of the four.
## Part-year residents
Column A comes from Schedule NR Column B, stripped of anything from the nonresident period. Step 5 must be completed. Line 51 includes only the other state's tax on income earned WHILE an Illinois resident: prorate the other state's tax by resident-period income ÷ total income taxed by that state. IDOR's own example: a couple moves from Indiana to Illinois in April, earns $54,000 in Indiana wages all year of which $40,500 falls in the Illinois-resident period, and paid $1,000 of Indiana tax — Line 51 is $1,000 × 40,500 ÷ 54,000 = $750.
## Notes
- Compute one Schedule CR combining all states; Line 51 is the total tax to all other states and localities
- Other states' tax may not be computed the way Illinois computes it; Publication 111-C gives the form, line, additions, and subtractions to use for each state to get the comparable figure
- If a joint federal return is split into separate Illinois returns, Column A carries only your share from the Allocation Worksheet
- Military pay in Column B, Line 1 must also be subtracted on Line 39 (and on Schedule M)
- A later amendment of the other state's return that changes the tax requires Form IL-1040-X
- For 2026, Public Act 104-0468's QSBS gain add-back raises Illinois base income (Column A) for anyone with a federal Section 1202 exclusion; the gain is on an intangible and stays out of Column B, which shrinks the decimal
## Required Information
- Each other state's filed return, with the Publication 111-C conversion
- W-2 state and local boxes; local return if claiming local tax
- Federal return line amounts for Column A, or Schedule NR Column B if part-year
- Illinois sourcing facts for each non-wage item: where real property sits, where a business's sales are, K-1-P/K-1-T apportionment decimals
- Illinois tax from IL-1040 before credits
- Residency dates if part-year
## Questions
- Which state or locality taxed the income, did you file its return, and what was the tax after that state's credits?
- Is any of it wages from Iowa, Kentucky, Michigan, or Wisconsin — and was there a city or county tax on top?
- Is the double-taxed income wages, business income, real property gains, or rents — or is it interest, dividends, retirement, or stock gains that Illinois sources to Illinois regardless?
- Were you an Illinois resident for the whole year?
- Did a partnership or S corporation pay another state's PTE tax on your behalf?
## Common Errors
- Claiming credit for Wisconsin, Iowa, Kentucky, or Michigan WAGES instead of recovering the withholding — while missing that the local tax on those same wages IS creditable
- Putting nonbusiness interest, dividends, pensions, or stock gains in Column B because the other state taxed them
- Entering W-2 withholding on Line 51 instead of the tax from the other state's return after its credits
- Skipping the Publication 111-C formula and using the other state's raw tax line
- Claiming the full tax paid to a higher-rate state rather than the decimal-limited Illinois amount
- Filing Schedule CR as a nonresident, or including nonresident-period income as a part-year resident
- Not filing the other state's return at all, which forfeits the credit
- Including interest or penalties, or foreign taxes
## Prompt
- I live in Illinois and work in St. Louis, do I get a credit for Missouri tax and the St. Louis earnings tax?
- I paid Indiana income tax on rental property, can Illinois credit that?
- I live in Chicago and work in Wisconsin, why did they withhold Wisconsin tax?
- Kentucky says I am a resident but so does Illinois, what do I do?
