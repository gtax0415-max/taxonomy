---
type: income-allocation
category: sourcing
jurisdiction: michigan
tax_year: 2026
source_doc: Business sales records (Michigan sales and total sales); FEDERAL Schedule K-1, Schedules C, E, F
form: MI-1040H
line: "12"
via:
  - MI-1040H, Line 12 (income) → Schedule 1, Line 13 (residents)
  - MI-1040H, Line 12 (loss) → Schedule 1, Line 4 (residents)
  - MI-1040H, Line 12 → Schedule NR, Column C (nonresidents, part-year)
  - MI-1040H, Line 8 percentage → MI-461 Column C; FTE add-back and refund subtraction; decoupling adjustments
---
# Schedule of Apportionment (MI-1040H)
## Description
When a business's income is taxable both in Michigan and in another state (or country), the business income is divided using a single SALES FACTOR. The out-of-state share is subtracted (income) or added back (loss).
## How it works
1. Line 6 Michigan sales ÷ Line 7 total sales = Line 8 apportionment percentage
2. Line 10 business income subject to apportionment × Line 8 = Michigan share (Line 11)
3. Line 12 = Line 10 − Line 11 = income or loss attributable to other states
## Sourcing sales
- Tangible property: Michigan if delivered to a Michigan purchaser (other than the U.S. government). THROWBACK: sales shipped from Michigan to a state that cannot tax the seller (P.L. 86-272 standard) are Michigan sales. No water's edge for individual income tax
- Services and other: Michigan if performed in Michigan, or if performed in several states but most cost of performance is in Michigan
- Special formulas exist for transportation companies
## Taxable in another state?
Yes if the other state imposes a net income tax, franchise tax measured by net income, franchise tax for doing business, or corporate stock tax on the taxpayer — or has jurisdiction to do so under P.L. 86-272, whether or not it actually does.
## What goes on Line 10
- Include ordinary, portfolio (interest, dividends, capital gains from the entity), and all other business income from the activity
- Exclude amounts already apportioned on MI-461 and business capital gains apportioned on MI-1040D/MI-461
- Exclude guaranteed payments (not business income in Michigan)
## Combined (unitary) apportionment
Taxpayers may elect annually to combine apportionment for commonly controlled entities that are unitary (Malpass v. Department of Treasury, 2013): check Box 5, write "Unitary", list entities in Part 3, eliminate intercompany sales, and attach a statement explaining control, functional integration, centralized management, economies of scale, and mutual interdependence. If elected, it must be used for every unitary group.
## Multiple forms
Use one MI-1040H per business activity. Residents do NOT net multiple forms: total the losses to Schedule 1 Line 4 and the income to Line 13. Nonresidents net all forms into Schedule NR Column C.
## Required Information
- Michigan and total sales for each entity
- Business income included in AGI from each entity (K-1 lines)
- Whether the entity has nexus in other states
## Questions
- Does your business sell to customers outside Michigan, and is it taxable in those states?
- Do you own several related businesses under common control?
## Common Errors
- Including guaranteed payments on Line 10
- Netting losses and income from multiple MI-1040H forms (residents)
- Ignoring throwback sales
## Prompt
- My S corporation sells in several states. How much is Michigan income?
