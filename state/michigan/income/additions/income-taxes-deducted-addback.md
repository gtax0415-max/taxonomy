---
type: addition
category: additions
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Schedule 1 (Form 1040), deductible part of self-employment tax; Michigan Schedule FTE (Form 6072) Line 3; Schedule NR Line 13 Column B (nonresidents)
form: Michigan Schedule 1
line: "2"
direction: add
via:
  - Schedule 1, Line 2 → Schedule 1, Line 9 → MI-1040, Line 11
  - Form 6072, Line 3 → Schedule 1, Line 2 (flow-through entity tax share)
---
# Add-back of Income Taxes Deducted in AGI (including SE tax and FTE tax)
## Description
Michigan does not allow a deduction for taxes on or measured by income. When such a tax reduced federal AGI, it is added back.
## What is added
1. The FEDERAL deduction for one-half of self-employment tax (residents: the full federal deduction)
2. Other taxes on or measured by income, to the extent they reduced AGI
3. The owner's share of Michigan flow-through entity (FTE) tax paid and deducted by an electing partnership or S corporation — Form 6072, Line 3. If the flow-through income was apportioned on MI-1040H, apply the Line 8 apportionment percentage to that share. See credits/business-flow-through/flow-through-entity-tax-credit.md
## Nonresidents and part-year residents
Enter the portion of Schedule NR, Line 13, Column B that relates to the self-employment tax deduction and other income taxes. The SE tax deduction is apportioned by the ratio of Michigan self-employment income to total self-employment income.
## Exception
If an electing flow-through entity files a Composite Return (Form 807) that includes the owner, the FTE addition is reported on the composite return, not here.
## Required Information
- Federal SE tax deduction (Schedule 1 of Form 1040)
- Form 6072 Line 3 and Form 6074 if tiered
- MI-1040H apportionment percentage if applicable
## Questions
- Are you self-employed?
- Did any partnership or S corporation you own pay the Michigan FTE tax?
## Common Errors
- Forgetting the SE tax add-back
- Omitting the FTE add-back while claiming the FTE credit
- Not applying the apportionment percentage to an apportioned FTE share
## Prompt
- Why is my self-employment tax deduction added back in Michigan?
