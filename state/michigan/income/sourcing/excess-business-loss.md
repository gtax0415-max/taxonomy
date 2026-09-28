---
type: income-allocation
category: sourcing
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Form 461 (Line 14 business income and loss, and the limitation); Schedule K-1s; FEDERAL Schedules C, E, F; Forms 4797, 4835; MI-1040H Line 8
form: MI-461 (Form 5595), continuation Form 5606
line: "9-10"
via:
  - MI-461, Line 9, Column F positive → Schedule 1, Line 13 (residents)
  - MI-461, Line 9, Column F negative → Schedule 1, Line 4 as positive (residents)
  - MI-461, Line 9, Columns D-F → Schedule NR, Line 11 (nonresidents); guaranteed payments → Schedule NR, Line 9
  - MI-461, Line 10, Column E → Michigan Group 2 NOL, deductible next year on Form 5674
---
# Michigan Excess Business Loss (MI-461)
## Description
When the FEDERAL excess business loss limit under IRC § 461(l) applies, MI-461 splits the federally allowed loss and the disallowed excess between Michigan and other states. The Michigan share of the excess becomes a Michigan NOL in the next year.
## 2026 figures
| Parameter | 2025 | 2026 |
|---|---|---|
| Federal allowable business loss — single or married filing separately | $313,000 | $256,000 |
| Federal allowable business loss — joint | $626,000 | $512,000 |
The 2026 thresholds DROPPED because the 2025 federal law (OBBBA) made § 461(l) permanent and reset its inflation base. MI-461 Line 5 uses the federal amount; confirm the 2026 MI-461 instructions.
## How it works
1. Table: every item in federal Form 461 Line 14, one row per entity (Column D federal, C apportionment %, E Michigan, F non-Michigan). Guaranteed payments are one combined row
2. Line 3 totals; Column D must equal federal Form 461 Line 14
3. Line 4 percentage of total loss by column (floored at 0%, capped at 100%)
4. Line 5 federal allowable loss spread by those percentages; Line 6 removes guaranteed payments
5. Lines 7-9 compute the apportioned allowable loss, with adjustments when one column is a gain
6. Line 10, Column E = Michigan excess business loss → Group 2 NOL next year
## Guaranteed payments
Not Michigan business income. Taxable to Michigan residents wherever earned; taxable to nonresidents for services in Michigan unless they live in a reciprocal state (IL, IN, KY, MN, OH, WI).
## Worked outcomes (2025 booklet examples)
- Heather (single, Michigan loss $235,000, other-state loss $115,000): Michigan allowable loss $260,148; add back $102,852 non-Michigan loss; Michigan NOL $24,852
- Joe (Michigan income $30,000, other-state loss $340,000): add back $335,000; no Michigan NOL
- Robert and Kelli (joint, Michigan loss $771,000, other-state income $49,000): subtract $49,000; Michigan NOL $96,000
## Required Information
- Federal Form 461 and all business schedules and K-1s
- MI-1040H for each apportioned entity
- Location and type of each business activity
## Questions
- Did you file federal Form 461 with a limitation?
- Which businesses are in Michigan, which elsewhere, and which in both?
## Common Errors
- Column D total not matching federal Form 461 Line 14
- Treating guaranteed payments as business income
- Reporting the same income or loss again on Schedule 1 or Schedule NR
- Using the 2025 $313,000 / $626,000 figures for 2026
## Prompt
- My business losses were limited on federal Form 461.
