---
type: income
category: capital-gains
jurisdiction: wisconsin
tax_year: 2026
form_basis: "Schedule WD, I-070i (R. 05-25) and instructions I-170 (R. 10-25); Schedule SB line 5 and Schedule AD line 2 instructions (2025)"
source_doc: Federal Schedule D / Form 8949 / Form 4797 (and a recomputed "Wisconsin" 4797 if basis differs) / Forms 2439, 4684, 6252, 6781, 8824 / Schedules K-1 and Wisconsin 2K-1, 3K-1, 5K-1 / 1099-B / 1099-DIV Box 2a / 2025 Wisconsin Schedule WD (carryovers) / Schedules T, QI, CG
form: Wisconsin Form 1
line: "4 or 6"
via:
  - "Form 1: Schedule WD Part IV → line 29c or 29h to Schedule AD, Line 2 (addition) / line 29d or 29g to Schedule SB, Line 5 (subtraction)"
  - "Capital gain distributions only, no Wisconsin carryover: 30% of the distribution → Schedule SB, Line 5 (no WD needed; Form 1 only)"
  - "Form 1NPR: Schedule WD line 27 or 28 → Form 1NPR, Line 7, Column B (skip Part IV)"
---
# Wisconsin Capital Gains and Losses (Schedule WD)
## Description
Wisconsin recomputes capital gains and losses on Schedule WD. The two big differences from federal: a 30% exclusion of net long-term gain (60% for farm assets), and Wisconsin's own capital loss limit and carryovers.
## Structure
| Part | Lines | Content |
|---|---|---|
| I — short-term | 1a-8 | Schedule D lines 1a-3; Forms 6252, 4684, 6781, 8824; K-1s (line 5); Schedule T adjustment (line 6); 2025 WISCONSIN short-term carryover (line 7) |
| II — long-term | 9a-17 | Schedule D lines 8a-10; Form 4797 Part I, Forms 2439, 6252, 4684, 6781, 8824 (line 12); K-1s (line 13); capital gain distributions (line 14); Schedule T (line 15); Schedule QI exclusion (line 15a, negative); 2025 WISCONSIN long-term carryover (line 16) |
| III — summary | 18-28 | Net gain or loss; exclusion; loss limit |
| IV — Form 1 adjustment | 29a-29h | Compare federal and Wisconsin results → AD line 2 or SB line 5 |
| V — carryovers | 30-39 | Short-term (line 34) and long-term (line 39) carryover to 2027 (on the 2026 schedule) |
## Exclusion (Part III)
- Line 19: smaller of net long-term gain (line 17) or total net gain (line 18)
- Line 20: 30% of line 19
- Lines 21-25: for FARM assets (livestock, farm equipment, farm real property, farm depreciable property used in farming), an additional 30% of the farm share → total 60% exclusion. Excludes depreciation recapture and other ordinary income; woodland not usable for farming does not qualify; trees other than fruit/nut trees are not agricultural commodities
- Line 27: Wisconsin taxable net gain = line 18 − exclusion
## Loss limit (line 28)
Net capital loss deductible against other income is the SMALLEST of: the net loss, $3,000 ($1,500 if married and not filing jointly), or Wisconsin ordinary income (Form 1 line 7 without capital items; zero if negative). The rest carries forward indefinitely as short-term (line 34) and long-term (line 39) Wisconsin carryovers.
## Items requiring adjustment from federal Schedule D
- Use WISCONSIN carryovers, not federal; combine carryovers when switching to a joint return; separate filers and surviving spouses use only their share (title before the marital property law applied, classification after)
- Carryovers may need reduction for excluded discharge-of-indebtedness income
- Nonresidents: only Wisconsin-source gains (Wisconsin land, buildings, machinery; ISO/ESPP stock gains attributable to Wisconsin services; Wisconsin K-1 items). Stock sales, nonbusiness bad debts, and worthless securities while a nonresident are NOT Wisconsin-source. Part-year residents: all gains while resident plus Wisconsin-source while nonresident
- Federal S corporation that elected out of Wisconsin tax-option status: exclude its gains/losses
- Entity-level tax election entities: exclude their 5K-1/3K-1 gains and losses entirely (and do not also remove them on AD 29/31, SB 46/48)
- Basis differences: principal residence — compute gain with Wisconsin basis directly; other capital assets — federal gain plus Schedule T adjustment (lines 6/15); Form 4797 property acquired 2014 or later — recompute a "Wisconsin" Form 4797. Differences from IRC conformity or different elections go on Schedule I instead
- Qualified Wisconsin business: reinvested (deferred) gain is excluded via Schedule CG; sales use Schedule QI (line 15a) and T
- Wisconsin QOF subtraction is NOT taken on WD (Schedule SB line 49)
- Exchange of marital property by a surviving spouse/distributee under sec. 766.31(3)(b)3 is excluded
- Lump-sum distributions on federal Form 4972 can never be capital gain for Wisconsin
## Part IV — Form 1 routing (all amounts positive)
| Federal result | Wisconsin result | Entry |
|---|---|---|
| Gain | Larger gain | 29c → Schedule AD line 2 |
| Gain | Smaller gain | 29d → Schedule SB line 5 |
| Loss | Larger loss | 29g → Schedule SB line 5 |
| Loss | Smaller loss | 29h → Schedule AD line 2 |
| Gain | Loss | 29d + 29g → Schedule SB line 5 |
| Loss | Gain | 29c + 29h → Schedule AD line 2 |
If Schedule I changed capital gains (line 1e or 2c), use those amounts instead of Form 1040 line 7.
## 2026 parameters
30% / 60% exclusion and $3,000 / $1,500 loss limit — statutory, unchanged. Use 2025 Schedule WD lines 34 and 39 as the 2026 carryovers in.
## Interactions
- Schedule OS uses the Wisconsin-taxable (70% / 40%) gain
- NOL1/NOL2 add back the exclusion; homestead (Schedule H line 11d) and farmland preservation (Schedule FC line 9d) add it to household income
## Questions
- Did you sell stock, real estate, or farm assets in 2026? Which were farm assets?
- Do you have Wisconsin (not federal) capital loss carryovers from 2025?
- Were you a nonresident for any part of the year?
## Common Errors
- Using federal carryovers
- Claiming a federal-size loss when Wisconsin ordinary income is lower
- Taking 60% on non-farm or woodland gains, or on recapture
- Including entity-level-taxed K-1 gains
## Prompt
- How much of my capital gain is taxed in Wisconsin?
- I have a capital loss carryover. How much can I use in Wisconsin?
