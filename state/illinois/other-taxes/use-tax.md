---
type: other-tax
category: other-taxes
jurisdiction: IL
tax_year: 2026
source_doc: Receipts or order histories for internet, mail-order, and out-of-state purchases showing whether sales tax was charged and at what rate / for the estimate method, federal AGI from IL-1040 Line 1 / the completed UT Worksheet (keep with records; IDOR may request it)
form: Form IL-1040
line: "21"
via:
  - Purchases with no or under-collected sales tax → UT Worksheet (actual) or UT Table (estimate by AGI) → IL-1040 Line 21 → Line 23 → Line 24 total tax
  - Liability over $600 ($1,200 joint) → Form ST-44 instead, and Line 21 shows zero
---
# Illinois Use Tax — Line 21
## Description
The sales tax you owe as the BUYER when the seller did not collect Illinois tax, or collected less than the Illinois rate — internet orders, mail order, and purchases made while traveling, brought back for use in Illinois. It is reported on the income tax return purely for convenience. Line 21 is MANDATORY: enter zero if you owe nothing, but never leave it blank, or the return is treated as incomplete. IDOR audits use tax from U.S. Customs and other states' data, and a blank line is a flag.
## Rates for 2026
| Purchase | Rate | Line |
|---|---|---|
| General merchandise (electronics, clothing, furniture, jewelry, software, books) | 6.25% | UT Worksheet 1a/1b |
| Qualifying food, non-prescription drugs, medical appliances | 1% | UT Worksheet 2a/2b |
These are the STATE use tax rates; local sales taxes are not part of the individual use tax. (Illinois's 1% state grocery tax was repealed effective January 1, 2026 for retail sales, with municipalities allowed to impose a local 1% replacement; check whether the 2026 UT Worksheet still carries the 1% food line — as of the 2025 instructions it does.)
## When you owe it
All three: the item is taxable in Illinois, you used or consumed it in Illinois, and the seller either collected no sales tax or collected at a rate below 6.25% (1% for food and drugs). IDOR's own examples: a computer bought online with no tax → 6.25%; jewelry bought on vacation in Georgia with 4% Georgia tax → the 2.25% difference; cheese by mail from Wisconsin with no tax → 1%.
## Credit for tax paid to another state
UT Worksheet Line 4 subtracts sales tax paid to another STATE on the same items. Do not include an item at all if the other state's tax was 6.25% or more (1% for food); exclude it rather than netting. Sales tax paid to another COUNTRY does not count — an item bought abroad with VAT is fully subject to Illinois use tax.
## Two ways to compute
1. UT WORKSHEET, actual purchases: 1a total general merchandise × 6.25%; 2a total food/drugs × 1%; add; subtract other-state tax on those items; enter the result (not below zero). Use this whenever you have records, and always when you had MAJOR purchases even if other records are incomplete (actual cost of the major items plus an estimate of the rest)
2. UT TABLE, estimate by federal AGI, only if you had NO major purchases and no receipts:
| AGI (IL-1040 Line 1) | Use tax |
|---|---|
| $0 – $10,000 | $3 |
| $10,001 – $20,000 | $8 |
| $20,001 – $30,000 | $13 |
| $30,001 – $40,000 | $18 |
| $40,001 – $50,000 | $23 |
| $50,001 – $75,000 | $31 |
| $75,001 – $100,000 | $44 |
| Above $100,000 | AGI × 0.05% (0.0005) |
The table is a safe harbor for small, unrecorded purchases; it does not cover a $4,000 online purchase you know about.
## The $600 / $1,200 threshold
If the year's use tax exceeds $600 ($1,200 married filing jointly), you must file Form ST-44, Illinois Use Tax Return, and pay there — not on Line 21. Do not report on both. At 6.25% that is $9,600 of untaxed purchases ($19,200 joint).
## Notes
- Line 21 CANNOT be changed on Form IL-1040-X. A missed or wrong use tax entry is corrected with Form ST-44, not an amended income tax return
- Since 2021 most large online retailers and marketplaces collect Illinois tax at the destination rate under the Leveling the Playing Field law, so Line 21 has shrunk for most filers; purchases from small out-of-state sellers, private-party out-of-state sales, and foreign purchases remain the usual sources
- Vehicles, boats, and aircraft bought out of state are NOT reported here; they use Form RUT-25 / RUT-50 at titling
- Cigarettes bought online are separately subject to Cigarette Use Tax
- Because Line 21 comes after the credits, nonrefundable credits cannot absorb it
- Penalties and interest apply to unreported use tax found on audit
## Required Information
- Untaxed or under-taxed purchases by category (general vs. food/drug), with any other-state tax paid
- Federal AGI if using the table
- Whether the total exceeds $600 / $1,200
## Questions
- Did you buy anything online, by mail, or out of state this year where no Illinois tax was charged?
- Was sales tax charged at less than 6.25%, and by which state?
- Do you have receipts, or should we estimate from the table?
- Does the total exceed $600 ($1,200 joint)?
## Common Errors
- Leaving Line 21 blank
- Using the AGI table while sitting on a known large purchase
- Claiming foreign VAT as "tax paid to another state"
- Reporting more than $600 / $1,200 on Line 21 instead of on ST-44
- Trying to fix Line 21 on an IL-1040-X
- Reporting a vehicle purchase here instead of on RUT-25
## Prompt
- Do I have to fill in the use tax line on my Illinois return?
- I bought a laptop online and was not charged tax, what do I owe Illinois?
- How much is Illinois use tax if I just estimate it?
- I paid 4% sales tax in another state, do I still owe Illinois?
