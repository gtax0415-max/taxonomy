---
type: income
category: pass-through
source_doc: Schedule K-1 (Form 1065 / Form 1120-S / Form 1041)
form: Form 1040
line: "8"
via:
  - Schedule E, Part II (ordinary business income from partnership / S-corp)
  - Separately stated items flow to their own schedules (see routing)
routing:
  - "Ordinary business income (loss) → Schedule E, Part II → Schedule 1, Line 5 → Form 1040, Line 8"
  - "Interest income → treated like interest → Form 1040, Line 2b (see income/interest)"
  - "Ordinary dividends → treated like dividends → Form 1040, Line 3b; qualified portion → Line 3a (see income/dividends)"
  - "Net capital gain (loss) → Schedule D → Form 1040, Line 7 (see income/capital-gains)"
  - "Section 199A / QBI info → Form 8995 → Form 1040, Line 13 (QBI deduction)"
---
# Schedule K-1
## Description
Reports a partner's or shareholder's share of income, deductions, and credits from a partnership (Form 1065), S-corporation (Form 1120-S), or estate/trust (Form 1041). A single K-1 is not one income type — it bundles several, and each separately stated item flows to a different place on the return.
## How the pieces flow
- Ordinary business income (loss): the main pass-through amount; goes to Schedule E, Part II, then to Line 8. May qualify for the QBI deduction. Partnership income can be subject to self-employment tax; S-corp shareholder income generally is not.
- Interest income: behaves like any interest — reported on Form 1040, Line 2b. See income/interest.
- Dividends: behave like any dividends — ordinary on Line 3b, qualified on Line 3a. See income/dividends.
- Capital gains: flow through Schedule D to Form 1040, Line 7. See income/capital-gains.
- Section 199A dividends / QBI: feed the QBI deduction on Form 8995 → Form 1040, Line 13.
## Required Information
- Entity name and EIN
- Partner/shareholder identifying information
- Ordinary business income (loss)
- Each separately stated item (interest, dividends, capital gains, Section 179, 199A, etc.)
## Questions
- Did you receive a Schedule K-1 from a partnership, S-corporation, or trust?
- Do you actively participate in the entity, or is it a passive investment?
- Which separately stated items appear on the K-1 (interest, dividends, capital gains)?
## Common Errors
- Entering only the ordinary income and missing separately stated investment items
- Not routing interest/dividends/capital gains to their proper lines
- Misclassifying passive vs. active participation
- Missing the QBI deduction on qualifying pass-through income
## Prompt
- I received a Schedule K-1 from a partnership I am part of.
- I got a K-1 from my S-corporation.
- I co-founded a company and received a K-1 with business income and some investment items.
