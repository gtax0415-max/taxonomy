---
type: income
category: business
jurisdiction: new-jersey
tax_year: 2026
source_doc: Schedule NJ-K-1 (Form CBT-100S) / Schedule PTE-K-1 (BAIT share) / federal Schedule K-1 (Form 1120-S) plus GIT-9S Reconciliation Worksheet B (or B-Liquidated) if no NJ-K-1
form: Form NJ-1040
line: "22"
via:
  - Schedule NJ-K-1 → Schedule NJ-BUS-1, Part III, Line 4 → Form NJ-1040, Line 22
  - Schedule PTE-K-1 BAIT share → Schedule NJ-BUS-1, Part III, Line 5 → Form NJ-1040, Line 63
routing:
  - "No NJ-K-1 received → complete GIT-9S Worksheet B and enclose the federal K-1"
  - "Part III Line 4 is a net loss → make NO entry on Line 22; usable loss may enter the Alternative Business Calculation"
---
# Net Pro Rata Share of S Corporation Income (Schedule NJ-BUS-1, Part III)
## Description
The shareholder's pro rata share of S corporation income or USABLE loss, whether or not distributed, computed under New Jersey rules. All S corporations are netted within this category.
## Notes
- Use the NJ-K-1 amount; NJ usable loss can differ from the federal loss
- Selling S corporation stock requires NJ adjusted basis on Schedule NJ-DOP
- BAIT share → Part III, Line 5 → Line 63
- Part-year residents: prorate by days of residence in the entity's fiscal year
- See GIT-9S, Income From S Corporations
## Required Information
- Schedule NJ-K-1 for each S corporation (or federal K-1 plus GIT-9S Worksheet B)
- Schedule PTE-K-1
- NJ stock basis records
## Questions
- Did each S corporation give you a Schedule NJ-K-1?
- Did any S corporation elect the BAIT?
## Common Errors
- Using federal K-1 income or loss
- Offsetting an S corporation loss against partnership income or wages
## Prompt
- I own an S corporation.
