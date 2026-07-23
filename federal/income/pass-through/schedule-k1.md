---
type: income
category: pass-through
source_doc: Schedule K-1 (Form 1065) for partnerships, Schedule K-1 (Form 1120-S) for S-corporations, Schedule K-1 (Form 1041) for estates and trusts
form: Form 1040
line: "8"
via:
  - Partnership and S-corporation income → Schedule E, Part II → Schedule 1, Line 5 → Form 1040, Line 8
  - Estate and trust income → Schedule E, Part III → Schedule 1, Line 5 → Form 1040, Line 8
  - Separately stated items flow to their own schedules (see routing)
routing:
  - "Ordinary business income (loss), partnership or S-corp → Schedule E, Part II → Schedule 1, Line 5 → Form 1040, Line 8"
  - "Estate or trust income, Form 1041 K-1 Boxes 5-8 → Schedule E, Part III → Schedule 1, Line 5 → Form 1040, Line 8"
  - "Interest income → Form 1040, Line 2b (see federal/income/interest/)"
  - "Ordinary dividends → Form 1040, Line 3b; qualified portion → Line 3a (see federal/income/dividends/)"
  - "Net capital gain (loss) → Schedule D → Form 1040, Line 7 (see federal/income/capital-gains/)"
  - "Section 199A / QBI information → Form 8995 or 8995-A → Form 1040, Line 13 (see federal/deductions/qbi/qbi.md)"
---
# Schedule K-1
## Description
Reports your share of income, deductions, and credits from a pass-through entity. A single K-1 is not one income type — it bundles several, and each separately stated item keeps its character and flows to a different place on your return.
## Three different K-1s
The box numbers differ by entity type, so identify which form you received first:
- Schedule K-1 (Form 1065) — partnerships and LLCs taxed as partnerships. Schedule E, Part II
- Schedule K-1 (Form 1120-S) — S-corporations. Schedule E, Part II
- Schedule K-1 (Form 1041) — estates and trusts, issued to beneficiaries. Schedule E, Part III
## Form 1041 K-1 (estates and trusts) box mapping
- Box 1 — Interest income → Form 1040, Line 2b
- Box 2a — Ordinary dividends → Form 1040, Line 3b
- Box 2b — Qualified dividends → Form 1040, Line 3a
- Box 3 — Net short-term capital gain → Schedule D, Line 5
- Box 4a — Net long-term capital gain → Schedule D, Line 12
- Box 4b — 28% rate gain → 28% Rate Gain Worksheet → Schedule D, Line 18
- Box 4c — Unrecaptured Section 1250 gain → worksheet → Schedule D, Line 19
- Box 5 — Other portfolio and nonbusiness income → Schedule E, Part III
- Box 6 — Ordinary business income → Schedule E, Part III (also includes farming and fishing income, stated separately)
- Box 7 — Net rental real estate income → Schedule E, Part III
- Box 8 — Other rental income → Schedule E, Part III
- Box 11 code A — Section 67(e) excess deductions in the final year → Schedule 1, Line 24k
- Box 13 code B — backup withholding → payments section. Attach the K-1 to your return to claim it
- Box 14 code H — net investment income tax adjustment → Form 8960, Line 7
- Box 14 code I — Section 199A information, with an attached statement → Form 8995 or 8995-A
## Partnership and S-corporation QBI boxes
- Form 1065 K-1 Box 20 code Z — Section 199A information
- Form 1120-S K-1 Box 17 code V — Section 199A information
In all three K-1 types, the entity enters the code with an asterisk and attaches a SECTION 199A STATEMENT listing QBI, W-2 wages, UBIA of qualified property, REIT dividends, and PTP items. You need that statement, not just the box.
## Notes
- Partnership ordinary income can be subject to SELF-EMPLOYMENT TAX; S-corporation shareholder income generally is not
- Estate and trust distributions carry out income only up to distributable net income (DNI). Amounts the entity retains are taxed to the entity, not to you, and do not appear on your K-1
- Losses in Form 1041 K-1 Boxes 6 through 8 may be limited by the passive activity rules — see federal/income/rental-royalty/passive-activity-limits.md
- Estates and trusts may claim the QBI deduction at the ENTITY level for items they retain; only items allocated out appear on the beneficiary's K-1
## Schedule E parts, for reference
- Part I — rental real estate and royalties. See federal/income/rental-royalty/
- Part II — partnerships and S-corporations. This file
- Part III — estates and trusts. This file
- Part IV — Real Estate Mortgage Investment Conduits (REMICs), reported from Schedule Q (Form 1066). Very rare for individual filers and intentionally not covered in this taxonomy
## Required Information
- Which K-1 form it is (Form 1065, 1120-S, or 1041) and the entity name and EIN
- Every box with an amount, plus any attached statements
- The Section 199A statement, if QBI applies
- Whether you materially participate
## Questions
- Which type of entity issued the K-1 — a partnership, an S-corporation, or an estate or trust?
- Do you actively participate in the entity, or is it a passive investment?
- Which separately stated items appear (interest, dividends, capital gains, rental)?
- Was a Section 199A statement attached?
- Is this a final-year K-1 from an estate or trust (excess deductions may pass through)?
## Common Errors
- Entering only the ordinary income and missing separately stated investment items
- Not routing interest, dividends, and capital gains to their proper lines
- Using the wrong box numbers for the entity type (Form 1041 boxes differ from Form 1065 and 1120-S)
- Using only the K-1 box amount and ignoring the attached Section 199A statement
- Misclassifying passive versus active participation
- Missing backup withholding in Form 1041 K-1 Box 13 code B by not attaching the K-1
## Prompt
- I received a Schedule K-1 from a partnership I am part of.
- I got a K-1 from my S-corporation.
- I am a beneficiary of a trust and received a K-1.
- I inherited money and got a K-1 from the estate.
