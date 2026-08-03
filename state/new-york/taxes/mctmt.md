---
type: tax
category: mctmt
jurisdiction: MCTMT
source_doc: Federal Schedule SE (Form 1040), Part 1, line 6 (net earnings from self-employment) / Form IT-204-IP lines 29b and 29c (partnership Zone 1 and Zone 2 allocation percentages) / Form IT-203-A if business is carried on both inside and outside a zone
form: Form IT-201
line: "54a, 54b, 54c, 54d, 54e"
refundable: no
via:
  - Federal Schedule SE → allocation by zone → Form IT-201, Lines 54a and 54b → tax at Lines 54c and 54d → total at Line 54e
routing:
  - "Zone 1 net earnings → Form IT-201, Line 54a → tax at 0.60% → Line 54c"
  - "Zone 2 net earnings → Form IT-201, Line 54b → tax at 0.34% → Line 54d"
  - "START-UP NY participants → Form IT-6-SNY lines 5 and 10 → Form IT-201, Lines 54a and 54b"
---
# Metropolitan Commuter Transportation Mobility Tax (MCTMT)
## Description
A tax on SELF-EMPLOYMENT EARNINGS in the twelve-county Metropolitan Commuter Transportation District. Employees do not pay it on wages — the employer-side MCTMT is a separate payroll tax. This line is only for self-employed individuals, partners, and LLC members.
## The threshold DOUBLED AND A HALF for 2026
| Tax year | Threshold per zone |
|---|---|
| 2025 | $50,000 |
| 2026 | $150,000 |
Confirmed from Form IT-2105-I (2026). This is a large change and it removes most small self-employed filers from the tax entirely. Anyone applying 2025 logic to a 2026 return will overstate the liability substantially.
The threshold is computed PER INDIVIDUAL and PER ZONE, even on a joint return.
## The two zones
| Zone | Counties | Rate |
|---|---|---|
| ZONE 1 | New York (Manhattan), Bronx, Kings (Brooklyn), Queens, Richmond (Staten Island) | 0.60% |
| ZONE 2 | Rockland, Nassau, Suffolk, Orange, Putnam, Dutchess, Westchester | 0.34% |
Each zone has its OWN threshold. You can owe in both, one, or neither. Exceeding the threshold in Zone 1 does not pull Zone 2 earnings into tax.
## Worked example, 2025 rules
Net earnings of $110,000 in the district: $40,000 to Zone 1, $70,000 to Zone 2.
- Zone 1: $40,000 is below the $50,000 threshold. EXEMPT. Nothing on line 54a
- Zone 2: $70,000 exceeds the threshold. $70,000 × 0.0034 = $238 on line 54d
Under 2026 rules with a $150,000 threshold, neither zone would be taxed at all.
## Joint returns
Each spouse tests each threshold SEPARATELY. Then:
- If BOTH spouses individually exceed the Zone 1 threshold, add the two bases and enter the combined total on line 54a
- If EITHER spouse is at or below the threshold in a zone, that spouse's base is EXCLUDED from that line entirely
The IT-201 instructions give the example: one spouse with $75,000 in Zone 1 and $45,000 in Zone 2, the other with $51,000 in Zone 1 and $54,000 in Zone 2. Both exceed Zone 1, so $126,000 goes on line 54a. Only the second spouse exceeds Zone 2, so only their $54,000 goes on line 54b.
## Allocation
- PARTNERS: use the allocation percentage the partnership reports on Form IT-204-IP, line 29b for Zone 1 and line 29c for Zone 2. Multiply your net partnership income by that percentage. Compute separately for each partnership
- ALL OTHERS, entirely inside a zone: all net earnings are allocated to that zone
- ALL OTHERS, business both inside and outside a zone: complete Form IT-203-A, Business Allocation Schedule. Or, if your books and records fairly show earnings from activity in the zone, use them
The Form IT-203-A formula averages three percentages — property, payroll, and gross income. Real property rental income and gains are NOT allocated; they are sourced entirely to where the property sits.
## Net earnings from self-employment
Generally federal Schedule SE, Part 1, line 6, per source.
Certain employment is treated as a trade or business under IRC 1402 and IS included: services by a U.S. citizen employed by a foreign government, the United Nations, or an international organization; services by a church employee where the church elected exemption from employer Social Security and Medicare; and qualified services by a minister, a member of a religious order who has not taken a vow of poverty, or a Christian Science practitioner or reader.
If your earnings are NOT subject to federal self-employment tax — nonresident noncitizens, for example — compute them on Schedule SE AS IF they were.
## The limited partner trap
An individual is NOT treated as a limited partner for the IRC 1402(a)(13) exclusion if they directly or indirectly take part in the control, or participate in the management or operations, of the partnership such that they are not a passive investor. Title and characterization in the partnership agreement do not control. Tax Law 800(e).
A partner labeled "limited" in the agreement who actually runs the business must include their distributive share.
## No credits, no exemptions
NO TAX CREDIT MAY BE USED TO OFFSET THE MCTMT, and no exemption in any other New York law applies — with one exception, START-UP NY earnings. This is why the MCTMT can be owed by someone whose income tax has been fully eliminated by credits.
The only offset is the claim of right credit, which is netted against the tax rather than claimed against it.
## START-UP NY
Approved businesses and their partners complete Form IT-6-SNY. Enter total Zone 1 earnings on line 1 and Zone 2 on line 6; the tax-free area amounts are excluded, and the results from lines 5 and 10 go to Form IT-201 lines 54a and 54b. Those amounts MAY BE $50,000 OR LESS after the exclusion, which is the one situation where a sub-threshold figure legitimately appears on those lines.
## Estimated payments
MCTMT must be included in estimated tax payments, in column D of the Form IT-2105 worksheet, if you expect to owe ANY amount. There is no $300 de minimis rule for the MCTMT the way there is for the state, city, and Yonkers columns.
## Required Information
- Net earnings from self-employment per source, from Schedule SE
- Zone allocation percentages from each partnership, Form IT-204-IP lines 29b and 29c
- Where business activity is physically carried on
- Property, payroll, and gross income figures if Form IT-203-A is needed
- Each spouse's figures separately, on a joint return
## Questions
- Do you have self-employment income, or a K-1 from a partnership or LLC?
- Where is the business activity carried on — the five boroughs, the seven suburban counties, or outside?
- Do your net earnings exceed the threshold in either zone, tested individually?
- Are you a partner who participates in management despite a limited partner title?
- Are you applying the 2025 or the 2026 threshold?
## Common Errors
- Applying the 2025 $50,000 threshold to a 2026 return, when it is $150,000
- Combining both spouses' earnings before testing the threshold
- Combining Zone 1 and Zone 2 earnings to reach a single threshold
- Including W-2 wages, which are not subject to the individual MCTMT
- Attempting to offset the MCTMT with a tax credit
- Excluding a distributive share as a limited partner while actively managing the business
## Prompt
- I am self-employed in Brooklyn, do I owe the MCTMT?
- What is the MCTMT threshold for 2026?
- My K-1 shows a Zone 1 allocation percentage.
