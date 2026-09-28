---
type: credit
category: business-flow-through
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Schedule K-1 (Form 1065 or 1120-S) notes, or the Michigan Flow-Through Entity Tax Information Report (Direct Members), or the Indirect Share for Direct Members Report for tiered credits
form: Form MI-1040
line: "30"
refundable: yes
via:
  - Form 6074 (tiered / indirect credits only) → Form 6072, Part 2
  - Form 6072 (Michigan Schedule FTE), Line 5 → MI-1040, Line 30
routing:
  - "Credit → Form 6072 Line 5 → MI-1040 Line 30 (refundable)"
  - "Share of FTE tax deducted in arriving at federal AGI → Form 6072 Line 3 → Michigan Schedule 1, Line 2 (ADDITION)"
  - "Share of FTE tax refund included in federal AGI → Form 6072 Line 4 → Michigan Schedule 1, Line 16 (SUBTRACTION)"
---
# Flow-Through Entity Tax Credit (Form 6072, Michigan Schedule FTE)
## Description
Refundable credit for an owner's allocated share of Michigan FTE tax paid by an electing partnership or S corporation under Part 4 of the Michigan Income Tax Act. It is Michigan's pass-through entity tax (PTET) response to the federal SALT deduction cap: the entity deducts the tax federally, and the owner takes a Michigan credit for it.
## How it works
1. The electing entity files Form 5772 and allocates tax to members on Form 5774
2. The entity reports each member's share of credit, SALT deducted, and refunds (K-1 notes or Michigan FTE Tax Information Report)
3. The owner reports each credit on a SEPARATE row of Form 6072: Part 1 for directly owned entities, Part 2 for indirectly owned (tiered) entities, supported by Form 6074
4. Line 5 total credit → MI-1040 Line 30. Line 3 SALT addition → Schedule 1 Line 2. Line 4 refund subtraction → Schedule 1 Line 16
## The three numbers every credit carries
| Column (Part 1 / Part 2) | What it is | Where it goes |
|---|---|---|
| D and E / G | Credit: prior-year late-funded (D) or current-year timely-funded (E) | Form 6072 Line 5 → MI-1040 Line 30 |
| F / H | Share of FTE tax the entity DEDUCTED, reducing federal AGI | Line 3 → Schedule 1 Line 2, added back |
| G / I | Share of FTE tax REFUND the entity received, included in federal AGI | Line 4 → Schedule 1 Line 16, subtracted |
The addition prevents a double benefit: the tax was already deducted federally, so Michigan adds it back before allowing the credit.
## Timing — the credit funding deadline
- For entity tax years beginning on or after January 1, 2024: the credit funding deadline is the due date of the entity's annual FTE return, INCLUDING extensions
- For entity tax years beginning before 2024: the 15th day of the 3rd month after year end
- For a 2026 MI-1040: claim the share of tax from the entity's tax year ending with or within 2026 that was PAID by the funding deadline (Column E)
- Tax paid after the deadline is NOT claimed in 2026; it becomes a "late-funded credit" claimed in the owner's tax year in which the entity's later tax year (when it paid) ends. Report it in Column D on its own row with the original entity year end
- A late-funded credit can be claimed even if the owner is no longer a member
- The credit cannot be claimed until the credit-generating entity has FILED its annual FTE return; claims ahead of that return, or against a return with errors, will be denied or delayed
## Tiered (indirect) credits
- A chain such as Filer → Entity F → Entity D → Entity A (the credit-generating entity, or CGE) is an INDIRECT credit
- Each distinct chain of ownership to a CGE is a SEPARATE credit, numbered sequentially in Part 2 Column A, with its own Form 6074 table
- Form 6074 lists the CGE on the first row, each tier below with its percentage of the next tier's credit, and the filer on the last row. Part 2 Columns G-I come from that last row
- Part 2 Columns E-F name the entity immediately below the CGE (the recipient on the CGE's Form 5774)
- Intermediate entities (including trusts and estates) must pass the information through even if they did not elect
## 2026 notes
- Form 6072 (Rev. 09-25) states it applies to 2025 and future tax years; use the 2026 revision once published
- An entity's FTE election lasts three tax years, so an owner who received a credit in 2024 or 2025 will often receive one for 2026
- Joint filers: report the primary filer's and spouse's credits on SEPARATE rows, even from the same entity
- Fiscal-year entities: the "same tax year" is the entity year ending with or within the owner's 2026 calendar year
## Federal interaction
- The FTE tax is deducted at the ENTITY level on the federal return, so it reduces the owner's federal AGI rather than counting against the owner's federal SALT itemized deduction cap. That federal deduction is exactly why Michigan requires the Schedule 1 addition
- An entity refund of FTE tax increases federal income; Michigan lets the owner subtract it
## Eligibility
- Direct or indirect member (shareholder, partner, LLC member) of an electing flow-through entity
- Entity was a partnership or S corporation for federal purposes (not a publicly traded partnership, not a C corporation, not an insurance company)
- Entity filed its FTE return and paid the tax
- Not needed on a Composite Return (Form 807)
## Required Information
- For each entity and each tax year: entity name, FEIN, tax year end (MM-YY)
- Credit amount split between timely-funded and late-funded
- Share of FTE tax deducted (SALT) and share of refunds in income
- For tiered credits: full chain of entities, FEINs, and percentages (Form 6074)
- Copy of each Schedule K-1 with notes or the Michigan FTE Tax Information Report
## Questions
- Did any partnership or S corporation you own elect into the Michigan FTE tax?
- Do you own it directly, or through another entity?
- Was the tax paid by the entity's return due date (including extensions)?
- Do you have credits from an earlier year that the entity paid late?
- Did the entity deduct the FTE tax or receive an FTE refund on its federal return?
## Common Errors
- Claiming a credit before the entity has filed its FTE return
- Claiming late-paid tax in the current year instead of as a late-funded credit
- Forgetting the Schedule 1 addition for FTE tax deducted
- Combining two ownership chains to the same CGE into one row
- Combining spouses' credits on one row
- Filing Form 6072 without the K-1 notes or FTE information report
## Prompt
- My K-1 says the partnership paid Michigan flow-through entity tax.
- I own an S corp that elected the Michigan FTE tax.
- How do I claim my share of the entity-level tax?
