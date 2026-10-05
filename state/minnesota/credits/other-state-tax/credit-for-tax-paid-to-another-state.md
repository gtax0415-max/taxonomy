---
type: credit
jurisdiction: Minnesota
tax_year: 2026
category: other-state-tax
source_doc: Other state's (or DC / Canadian province's) filed income tax return and proof of tax paid / Form W-2 Box 15–17 for other-state wages and withholding / Schedule K-1 state allocations
form: Form M1
line: "16"
refundable: no
via:
  - Schedule M1CR → Schedule M1C, Line 3 → Form M1, Line 16
routing:
  - "Tax paid to any state other than Wisconsin, DC, or a Canadian province or territory → Schedule M1CR → Schedule M1C Line 3"
  - "Tax paid to Wisconsin → Schedule M1RCR (partly refundable) — see credit-for-tax-paid-to-wisconsin.md"
  - "183-day statutory resident domiciled elsewhere → Schedule M1CR, with a statement from the home state confirming it allows no credit for Minnesota tax"
federal_counterpart: federal/credits/foreign-tax/foreign-tax-credit.md
---
# Credit for Income Tax Paid to Another State (Schedule M1CR)
## Description
Nonrefundable credit for a Minnesota resident (full- or part-year) who paid income tax to another state on income Minnesota also taxed. Prevents double taxation, much like the federal Foreign Tax Credit.
## How it works
The credit is generally the SMALLER of:
1. The income tax actually paid to the other jurisdiction on the double-taxed income, or
2. The Minnesota tax attributable to that income (Minnesota tax × the share of income taxed by both)
Unused credit does NOT carry over.
## What counts as "another state"
- Any U.S. state
- The District of Columbia
- A CANADIAN PROVINCE or territory
NOT a foreign country's national tax, a U.S. city or local income tax, or a federal tax.
## Key eligibility rules
- Minnesota resident for all or part of 2026, and the income was earned or received while a Minnesota resident
- The same income was taxed by both Minnesota and the other jurisdiction
- 183-DAY RULE: someone domiciled elsewhere but taxed as a Minnesota resident (183+ days in Minnesota plus an abode) can claim the credit only with a statement from the home state's tax department that they cannot get a credit there for Minnesota tax
- NO DOUBLE DIP with the federal Foreign Tax Credit: taxes paid to a Canadian province that were included in a federal Form 1116 credit cannot also be used here
## Federal interaction
- The federal Schedule A deduction for state income tax is capped (SALT cap). That does not affect this credit
- Minnesota conforms to the federal PTE-tax treatment through AGI; PTE taxes paid by an entity to another state are handled under the Minnesota PTE regime, not here
## Required Information
- Copy of the other state's return and proof of tax paid
- Income taxed by both jurisdictions
- Minnesota tax before credits
- Home-state statement if a 183-day resident
## Questions
- Which state, DC, or Canadian province taxed your income in 2026, and how much tax did you pay?
- Was that income earned while you were a Minnesota resident?
- Did you claim a federal foreign tax credit for Canadian provincial tax?
- Are you domiciled in another state but in Minnesota 183+ days?
## Common Errors
- Claiming tax WITHHELD instead of the final tax liability on the other state's return
- Claiming city or local income tax
- Using Canadian provincial tax already used for the federal foreign tax credit
- Claiming credit for income earned while a nonresident of Minnesota
- Using Schedule M1CR for Wisconsin tax (use M1RCR)
## Prompt
- I paid income tax to Iowa and Minnesota on the same wages.
- I have a rental property in another state and paid tax there.
