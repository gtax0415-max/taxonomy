---
type: income-adjustment
category: sourcing
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Form 8949, Schedule D, Form 4797 (and Forms 2439, 4684, 6252, 6781, 8824); Schedule K-1 capital gain lines; property acquisition dates and locations
form: MI-8949, MI-1040D, MI-4797
line: "Schedule 1 Lines 3, 5, 12, 23"
via:
  - MI-8949, Lines 2 and 4 → MI-1040D, Lines 1 and 6
  - MI-1040D, Line 12 gain — Column F (federal) → Schedule 1, Line 12 (subtract); Column G (Michigan) → Schedule 1, Line 3 (add)
  - MI-1040D, Line 13 loss — Column F → Schedule 1, Line 5 (add, as positive); Column G → Schedule 1, Line 23 (subtract, as positive)
  - MI-4797, Line 18b — federal gain → Schedule 1 Line 12; federal loss → Line 5; Michigan gain → Line 3; Michigan loss → Line 23
  - Nonresidents and part-year residents → Schedule NR, Line 8
---
# Capital Gain and Business Property Adjustments (MI-8949, MI-1040D, MI-4797)
## Description
These forms swap the federal gain or loss out of income and swap in the portion Michigan can tax. They are used ONLY when a gain or loss is attributable to:
1. Property located in other states (nonbusiness real or tangible property), or otherwise subject to Michigan's allocation rules
2. Periods before October 1, 1967 (Section 271 election)
3. The sale or exchange of U.S. obligations Michigan cannot tax (MI-8949 and MI-1040D)
Business gains subject to APPORTIONMENT go on MI-1040H or MI-461, not here.
## How the swap works
Federal column (D/F) is removed and Michigan column (E/G) is added. Example: a $50,000 federal gain on a Florida condo, $0 Michigan → subtract $50,000 on Line 12, add $0 on Line 3.
## What Michigan taxes (Michigan column)
- Real property located in Michigan
- Tangible personal property located in Michigan at sale, or owned by a Michigan resident and not taxable where located
- Intangible property sold by a Michigan resident
- NOT taxable: gains on nonbusiness property in another state; gains on non-taxable U.S. obligations (enter zero); losses on these are not deductible
## Section 271 (pre-October 1, 1967)
Michigan column = federal gain × months held after September 30, 1967 ÷ total months held. Exclude the first month if acquired after the 15th and the last month if sold on or before the 15th. Pre-1967 installment sales: Michigan column is zero. Capital gain distributions and § 402 lump-sum treatment do not qualify.
## Loss limit and carryovers
Net capital loss is limited to $3,000 ($1,500 married filing separately) in each column. MI-1040D Part 4 computes separate federal and Michigan carryovers to 2027. In Part 4 Line 16, Column G uses MI-1040 Line 12 minus Line 13.
## MI-4797 Part 3
Depreciation recapture (§§ 1245, 1250, 1252, 1254, 1255) is apportioned by the Section 271 percentage on Lines 19-26.
## Required Information
- Federal Form 8949 / Schedule D / Form 4797 detail
- Location of each property, acquisition and sale dates
- Whether the item is business (apportion) or nonbusiness (allocate)
## Questions
- Did you sell property located outside Michigan?
- Did you own the asset before October 1, 1967?
- Did you sell U.S. Treasury securities at a gain or loss?
## Common Errors
- Using MI-1040D for apportioned business gains
- Deducting a loss on out-of-state nonbusiness property
- Using the federal capital loss carryover for Michigan
## Prompt
- I sold a rental property in Arizona. Does Michigan tax the gain?
