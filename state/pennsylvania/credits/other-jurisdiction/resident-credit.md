---
type: credit
category: other-jurisdiction
jurisdiction: PA
source_doc: A COPY OF THE INCOME TAX RETURN FILED WITH THE OTHER STATE — mandatory, and W-2s and K-1s do NOT substitute for it / Forms W-2 showing compensation the other state taxed, or a statement showing how it was determined / PA Schedules RK-1 plus the Statement of Resident Credits for Owners of a Pass-Through Entity / the other state's apportionment schedule where the W-2 and the return disagree / the other state's domicile rule, law, or regulations if interest or dividend income is claimed
form: PA-40
line: "22"
refundable: no
via:
  - PA-40/PA-41 Schedule G-L, Section I line 6 → PA-40, Line 22
routing:
  - "Individual taxpayer → PA Schedule G-L → PA-40, Line 22"
  - "Estate or trust → PA Schedule G-L → PA-41, Line 15"
  - "PA S corporation shareholder's share → PA-20S/PA-65 Schedule RK-1, Line 8 → the owner's Schedule G-L"
  - "OUT-OF-STATE CREDIT (entity-level tax paid by a PA S corporation) → RK-1 Line 9 → Schedule G-L, NOT Schedule OC"
---
# Resident Credit for Tax Paid to Another State (PA Schedule G-L)
## Description
Relief from double taxation, authority 72 P.S. Section 7314. The computation is far more mechanical than most states' — it is done CLASS BY CLASS, ONE SCHEDULE PER STATE, AND ONE SCHEDULE PER SPOUSE.
## The credit is the LOWER of
1. The TAX DUE TO THE OTHER STATE as adjusted, or
2. PA classified taxable income earned in the other state x 3.07%
Because PA's rate is 3.07%, limb 2 binds almost always. The excess is lost and does not carry forward.
## Section I is computed CLASS BY CLASS
Lines 2a through 2j list the PA income classes, and each is tested separately:
| Line | Class |
|---|---|
| 2a | Compensation |
| 2b | Unreimbursed business expenses |
| 2c | NET compensation |
| 2d | Interest |
| 2e | Dividends |
| 2f | Net income or loss from business, profession, or farm |
| 2g | Gain or loss from sale, exchange, or disposition of property |
| 2h | Income or loss from rents, royalties, patents, and copyrights |
| 2i | Estate or trust income |
| 2j | Gambling and lottery winnings |
- COLUMN A: amount of that class subject to tax in PA per the PA return
- COLUMN B: amount of that class subject to tax in the other state, PER THAT STATE'S RULES
- COLUMN C: THE LESSER OF A OR B
Line 3 totals Column C for lines 2c through 2j. A class where the other state taxed MORE than PA does is capped at the PA figure — you cannot net a high-tax class against a low-tax one.
## Section III: the adjusted tax paid calculation
Easy to miss and it reduces the credit. If the income you can actually count (Section I line 3) is LESS than the total income the other state taxed, the tax paid must be scaled down proportionally:
```
III-1  Section I, Column C, Line 3
III-2  Sum of Section I, Column B, Lines 2c through 2j
III-3  Line 1 divided by Line 2, to SIX DECIMAL PLACES
       If this equals 1.000000, STOP — enter 0 on Section I line 4d
III-4  1.000000 minus Line 3, to six decimal places
III-5  Line 4 x Section I line 4c → Section I, Line 4d
```
Section I then runs: 4a tax due or assessed, 4b tax paid, 4c THE LESSER OF 4a OR 4b, 4d the Section III adjustment, 4e adjusted tax paid. Line 5 is line 3 x 3.07%. LINE 6 IS THE LESSER OF 4e OR 5.
## Separate schedules: per state AND per spouse
- ONE SCHEDULE G-L PER STATE. You may NOT add the income and tax across states onto one schedule; each state's credit must be verified separately
- MARRIED FILING JOINTLY CANNOT CLAIM THE CREDIT JOINTLY FOR ANY CLASS OF INCOME. Separate Schedules G-L must be prepared for taxpayer and for spouse, each reporting only the income attributable to the name at the top
- The same income CANNOT be taxable in more than one other state
- With MULTIPLE Schedules G-L you must also perform a SECONDARY CALCULATION outside the individual state computations, confirming that total income subject to tax across all states in a class does not exceed the PA income in that class
## Section II is mandatory
The sources-and-amounts worksheet must be completed to show income subject to tax by source and class for each state, EVEN IF THERE IS ONLY ONE SOURCE.
## Documentation — the credit is disallowed without the other state's RETURN
Submit with the PA-40 or PA-41:
- Copies of Schedule G-L for EACH state
- COPIES OF THE INCOME TAX RETURNS FILED WITH THE OTHER STATES
- Forms W-2 showing compensation the other state taxed, or a statement of how it was determined
- PA Schedules RK-1 with the statement of the shareholder's proportionate share by class, tax paid, and credit
- A partnership or LLC statement of the partner's proportionate share by class
- THE OTHER STATE'S DOMICILE RULE, LAW, OR REGULATIONS if interest or dividend income is claimed
AN INCOME TAX RETURN MEANS AN ACTUAL RETURN FILED IN THAT STATE showing the income subject to tax and the tax computed on it. W-2s, Schedule K-1s, and withholding documents DO NOT COUNT as the return.
Where a W-2 shows a different figure than the return, attach the other state's apportionment schedule. IF THE W-2 AMOUNT IS GREATER than the amount reported as subject to tax on the other state's return, THE RETURN AMOUNT MUST BE USED.
The Department may later require checks, money orders, composite returns, or entity returns.
## What "state" means here
Any state or commonwealth of the United States, the DISTRICT OF COLUMBIA, the COMMONWEALTH OF PUERTO RICO, and ANY TERRITORY OR POSSESSION of the United States.
NOT a foreign government. NOT any local tax subdivision within a state.
Act 2013-52, effective January 1, 2014, eliminated the credit for foreign taxes. A PA resident taxed by Canada or the UK gets a federal foreign tax credit and nothing from Pennsylvania.
## Resident credit versus OUT-OF-STATE CREDIT
Two different things, on two different RK-1 lines:
| | Resident credit | Out-of-state credit |
|---|---|---|
| What | Tax paid on a composite return filed for owners | Tax paid AT THE PA S CORPORATION ENTITY LEVEL to another state |
| RK-1 line | LINE 8 | LINE 9 |
| Where claimed | Schedule G-L | SCHEDULE G-L, NOT Schedule OC |
The Schedule OC instructions carry an explicit caution: an Out of State Credit appearing on RK-1 Line 9 goes to SCHEDULE G-L. Putting it on Schedule OC is a common and rejected error.
LINE 8 MUST NOT BE USED FOR AN ENTITY LEVEL TAX. Several states impose an ELT on pass-through entities following the federal Tax Cuts and Jobs Act; see Department Answer ID 3618 for the treatment.
The RK-1 credit is computed the same way: THE LESSER OF THE ACTUAL TAX PAID OR 3.07% of the total income taxed in the other state. The entity must supply a statement breaking down states, PA income class, tax paid, and credit, with the entity name, FEIN, tax year, owner names, and owner tax IDs. If a composite return was filed, the entity must submit copies of the out-of-state returns.
C CORPORATION OWNERS CANNOT CLAIM CREDIT FOR TAXES PAID TO OTHER STATES.
## Estates and trusts: the credit stops at the entity
An estate or trust MAY earn a resident credit, but IT MAY NOT PASS THAT CREDIT THROUGH to a Pennsylvania resident beneficiary — even where the underlying income IS distributed to them. Estates and trusts are NOT pass-through entities for PA personal income tax purposes.
So a beneficiary receiving distributed income that was taxed by another state gets no relief. The credit dies with the fiduciary return.
## Grantor trusts
PA does NOT follow the federal grantor trust rules. Federally the income belongs to the settlor; for PA it is taxable to the TRUST. When a PA resident trust receives income sourced to a state using the federal base, PA taxes the trust and the other state taxes the settlor. Because they are DIFFERENT TAXPAYERS for PA purposes, NEITHER may claim the credit. The double tax is real and unrelieved.
## The six reciprocal states
INDIANA, MARYLAND, NEW JERSEY, OHIO, VIRGINIA, WEST VIRGINIA. No credit is granted for tax paid to these states on COMPENSATION, because they do not tax a PA resident's compensation. If tax was withheld anyway, the remedy is a NONRESIDENT REFUND CLAIM from that state, not a PA credit.
Reciprocity covers COMPENSATION ONLY. Business income, rental income, and gains from those states DO support a credit.
OHIO EXCEPTION: since January 1, 2004, compensation paid to a PA resident who is a 20 PERCENT SHAREHOLDER-EMPLOYEE of an Ohio S corporation for services in Ohio is NOT covered by reciprocity and CAN be taxed by Ohio. That filer does claim a PA credit.
## PA S corporation taxed as a C corporation elsewhere
Where another state treats a PA S corporation as a C corporation, the entity reports the lesser of the tax paid on apportioned income or the PA rate on PA-20S/PA-65 Schedule OC line 5, distributes it by ownership percentage on Schedule RK-1 line 9, and attaches a breakdown statement. Shareholders report it on Schedule G-L as an ordinary resident credit.
## Ordering
The resident credit is applied FIRST — before Tax Forgiveness and before any Schedule OC restricted credit. Schedule SP line 13 subtracts it explicitly before the forgiveness percentage is applied.
## Note on the Special Instructions
Individual taxpayers reporting an amount on PA-40 LINE 10, OTHER DEDUCTIONS, must follow the Special Instructions for Taxpayers Reporting Amounts on PA-40 Line 10 in addition to the Column A instructions for lines 2c through 2j.
## Required Information
- A complete copy of each other state's return as filed
- Income by CLASS subject to tax in PA and in the other state
- Tax due or assessed, and tax paid, in the other state
- The Section II source-by-source breakdown
- Separate figures for taxpayer and spouse
- RK-1 lines 8 and 9 and the accompanying statement, if from an entity
## Questions
- Which states taxed your income, and have you filed those returns?
- Which CLASSES of income did each state tax?
- Are you married, which requires separate Schedules G-L?
- Did the credit come through an RK-1, and is it on line 8 or line 9?
- Is the other state one of the six reciprocal states?
- Are you a beneficiary of an estate or trust that paid tax to another state?
## Common Errors
- Failing to attach the other state's RETURN, which causes disallowance; W-2s and K-1s do not substitute
- Combining multiple states onto one Schedule G-L
- Claiming the credit jointly instead of preparing separate schedules for each spouse
- Skipping the Section III adjusted-tax-paid calculation and overstating the credit
- Netting a high-tax class against a low-tax class instead of testing each separately
- Putting an RK-1 Line 9 out-of-state credit on Schedule OC instead of Schedule G-L
- Using Line 8 of the RK-1 for an entity level tax
- A beneficiary claiming a credit an estate or trust earned
- Claiming a credit for compensation earned in a reciprocal state instead of seeking a refund there
- Claiming a credit for foreign tax or for another state's local tax
## Prompt
- I live in PA and work in New Jersey.
- I paid Delaware tax on consulting income.
- My K-1 shows an out-of-state credit, where does it go?
