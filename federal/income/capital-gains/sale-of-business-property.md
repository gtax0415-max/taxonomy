---
type: income
category: capital-gains
source_doc: Closing statements and bills of sale / Form 1099-B or Form 1099-S (gross proceeds) / depreciation schedules and fixed asset records
form: Form 1040
line: "7, 8"
via:
  - Form 4797 → Schedule 1, Line 4 (ordinary gains/losses) → Form 1040, Line 8
  - Form 4797 net Section 1231 gain → Schedule D → Form 1040, Line 7
routing:
  - "Depreciation recapture (Sections 1245, 1250) → ordinary income → Schedule 1 Line 4 → Form 1040 Line 8"
  - "Net Section 1231 GAIN → treated as long-term capital gain → Schedule D → Form 1040 Line 7"
  - "Net Section 1231 LOSS → ordinary loss → Schedule 1 Line 4 → Form 1040 Line 8"
---
# Form 4797 — Sales of Business Property
## Description
Reports gains and losses from selling or disposing of property used in a trade or business — equipment, vehicles, buildings, farm machinery, breeding livestock, and rental real estate. About 3.36 million returns file it (IRS SOI, TY 2022), reporting roughly $121 billion.
## The key concept: Section 1231's "best of both worlds"
Section 1231 property is depreciable business property and business real estate held MORE THAN ONE YEAR. It gets asymmetric treatment:
- A NET GAIN is treated as LONG-TERM CAPITAL GAIN — taxed at favorable capital gains rates, routed through Schedule D to Form 1040 Line 7
- A NET LOSS is treated as an ORDINARY LOSS — fully deductible against ordinary income, routed through Schedule 1 Line 4 to Form 1040 Line 8
This is more favorable than either pure capital or pure ordinary treatment.
## Depreciation recapture — the catch
Before Section 1231 treatment applies, prior depreciation is "recaptured" as ORDINARY income:
- Section 1245 (equipment, machinery, vehicles): gain up to the total depreciation taken is ordinary income
- Section 1250 (buildings): unrecaptured Section 1250 gain is taxed at a maximum 25% rate
- Only the gain ABOVE the recapture amount gets Section 1231 capital treatment
This is the flip side of the depreciation deductions taken while the asset was in service — see federal/deductions/business-expenses/depreciation.md
## The five-year lookback
If you had net Section 1231 LOSSES in the previous five years that were deducted as ordinary losses, a current-year net Section 1231 GAIN is treated as ORDINARY income to that extent. This prevents converting ordinary losses into capital gains.
## Structure of the form
- Part I: Section 1231 property held more than one year
- Part II: ordinary gains and losses (including property held one year or less)
- Part III: recapture under Sections 1245, 1250, 1252, 1254, 1255
- Part IV: recapture under Sections 179 and 280F when business use drops to 50% or less
## Required Information
- Description of the property and dates acquired and sold
- Gross sales price (Form 1099-B or Form 1099-S if issued)
- Original cost and improvements
- Total depreciation or Section 179 taken
- Any prior-year unrecaptured net Section 1231 losses
## Questions
- Did you sell or dispose of business equipment, vehicles, buildings, or rental property?
- How long did you hold the property (more or less than one year)?
- How much depreciation or Section 179 did you claim on it?
- Did you have Section 1231 losses in any of the prior five years?
- Did business use of a Section 179 asset drop below 50%?
## Common Errors
- Reporting the sale of business assets on Schedule D as an ordinary capital transaction, bypassing recapture
- Forgetting depreciation recapture entirely and treating the whole gain as capital
- Reporting farm machinery or breeding livestock sales on Schedule F instead of Form 4797
- Missing the five-year Section 1231 loss lookback
- Ignoring Section 179 or listed-property recapture when business use falls to 50% or less
## Prompt
- I sold equipment I used in my business.
- I sold a rental property this year.
- I sold farm machinery and breeding cattle.
- I traded in a work truck I had depreciated.
