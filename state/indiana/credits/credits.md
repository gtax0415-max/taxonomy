---
type: credit
category: credits
jurisdiction: IN
tax_year: 2026
form: IT-40
line: "12, 13, 14"
via:
  - Schedule 5, Lines 1-12 → Schedule 5, Line 13 → IT-40, Line 12
  - Schedule 6, Lines 1-7 → Schedule 6, Line 8 → IT-40, Line 13
  - IT-40, Line 12 + Line 13 → IT-40, Line 14 (Indiana Credits) → compared with Line 15 (Indiana Taxes) → Line 16 overpayment or Line 23 balance due
routing:
  - "Credit can be refunded (elderly, EIC, Lake County, EDGE, EDGE-R, refundable headquarters relocation, adoption) → Schedule 5"
  - "Credit only reduces tax (offset credit) → Schedule 6"
  - "Offset credit against county tax (local taxes paid outside Indiana, CRED, other local) → Schedule 6, Lines 1-3, limited to IT-40, Line 9"
  - "Offset credit against state tax (college, other states, line 6 codes, Schedule IN-OCC) → Schedule 6, Lines 4-7, limited to IT-40, Line 8"
see_also:
  - credits/schedule-5/schedule-5.md
  - credits/schedule-6/schedule-6.md
  - credits/schedule-6/combined-limitations.md
  - payments/payments.md
  - tax-computation/tax-computation.md
---
# Credits (Form IT-40, Lines 12-14; Schedules 5 and 6)
## Description
Indiana claims credits on two schedules. Schedule 5, Credits, holds the payments (withholding, pass through entity tax, estimated tax) and the credits that can be refunded. Its total (Schedule 5, line 13) goes to IT-40, line 12. Schedule 6, Offset Credits, holds the credits that "cannot be refunded; their purpose is to help reduce your state and/or county tax amounts due." Its total (Schedule 6, line 8) goes to IT-40, line 13. IT-40, line 14 adds lines 12 and 13 (Indiana Credits) and compares them with line 15 (Indiana Taxes, the line 11 total of state tax, county tax and other taxes). If line 14 is equal to or more than line 15 the difference is an overpayment (line 16); otherwise the shortfall is the amount due (line 23).

Indiana does not reduce tax by credits on a separate line before payments. Refundable and offset credits are both added on line 14, so the refundable / nonrefundable distinction is enforced by the limits on Schedule 6, not by the order of the IT-40 lines.
## How the lines flow
```
Schedule 5 (refundable credits and payments)
  Line 1   Indiana state tax withheld (Schedule IN-W, line 26)           payments/
  Line 2   Indiana county tax withheld (Schedule IN-W, line 27)          payments/
  Line 3   Pass Through Entity Tax Credit (Schedule IN K-1)              payments/
  Line 4   Estimated tax paid, including Form IT-9 extension payment     payments/
  Line 5   Unified tax credit for the elderly
  Line 6   Earned income credit (Schedule IN-EIC, line A-3)
  Line 7   Lake County residential income tax credit
  Line 8   EDGE credit (Schedule IN-EDGE, line 19)
  Line 9   EDGE-R credit (Schedule IN-EDGE-R, line 19)
  Line 10  Headquarters relocation credit (refundable portion)
  Line 11  Adoption credit (Adoption Credit Worksheet, line 47)
  Line 12  Reserved for future use
  Line 13  Total Credits → IT-40, line 12

Schedule 6 (offset credits)
  Line 1   Credit for local taxes paid outside Indiana     ┐ combined, not more than
  Line 2   Community revitalization enhancement district  │ county tax, IT-40 line 9
  Line 3   Other local credits (none currently)           ┘
  Line 4   College credit (Schedule CC-40)                 ┐
  Line 5   Credit for taxes paid to other states           │ combined, not more than
  Line 6   Other credits (name and 3-digit code, 6a-6d)     │ state AGI tax, IT-40 line 8
  Line 7   Schedule IN-OCC, line 8                         ┘
  Line 8   Total Offset Credits → IT-40, line 13

IT-40 line 14 = line 12 + line 13 (Indiana Credits)
```
## Combined Limitations and order of application (booklet pages 36-37 and 47)
1. Restriction for Certain Tax Credits - Limited to One per Project. A taxpayer may not be granted more than one credit for the same project. The credits covered are the alternative fuel vehicle manufacturer credit (845), community revitalization enhancement district credit (Schedule 6 line 2 and code 808), enterprise zone investment cost credit (813), Hoosier business investment credit (820), industrial recovery credit (824) and the venture capital investment credit (835). Apply this restriction first.
2. Combined Limitation on Schedule 6, lines 1 through 3: combined, not more than the county tax on IT-40, line 9. Order of Application: first use the credits that cannot be carried over and applied against county tax in another year, so the credit for local taxes paid outside Indiana first, then the community revitalization enhancement district credit. Any CRED credit cut off here can be used against state tax under line 6 (code 808).
3. Combined Limitation on Schedule 6, lines 4 through 7: combined, not more than the state adjusted gross income tax on IT-40, line 8, including credits carried from Schedule IN-OCC to line 7. Reduce the last entry. The booklet's example keeps the credit that cannot be carried over (Indiana529) whole and reduces the one that carries forward (industrial recovery).
4. Schedule 5 credits have no tax limit; any excess over tax is refunded through IT-40, line 16.

See credits/schedule-6/combined-limitations.md for the worked examples.
## Refundable and offset credits
| Credit | Schedule, line | Refundable |
|---|---|---|
| Unified tax credit for the elderly | 5, line 5 | yes |
| Indiana earned income credit | 5, line 6 | yes |
| Lake County residential income tax credit | 5, line 7 | yes |
| EDGE | 5, line 8 | yes |
| EDGE-R | 5, line 9 | yes |
| Headquarters relocation credit, refundable portion | 5, line 10 | yes (the part IEDC rules refundable) |
| Adoption credit | 5, line 11 | yes |
| Credit for local taxes paid outside Indiana | 6, line 1 | no, county tax only |
| Community revitalization enhancement district credit | 6, line 2 | no, county tax first; remainder under line 6 (808) |
| Other local credits | 6, line 3 | no (none currently available) |
| College credit | 6, line 4 | no |
| Credit for taxes paid to other states | 6, line 5 | no |
| Line 6 coded credits (for example 837 Indiana529, 861 educator) | 6, line 6 | no |
| Schedule IN-OCC credits (for example 849 school scholarship) | 6, line 7 | no |
## 2026 points
- State rate 2.95% for 2026 (the 2025 IT-40, line 8 prints 3%). The rate enters the Schedule 6 Combined Limitation through IT-40, line 8 and the Group A worksheet, line B (credit for taxes paid to other states).
- Indiana529 credit (837): from 2026, 20% of all contributions, with no higher education and K-12 split (SEA 453).
- Adoption credit: only Indiana residents qualify (SEA 243, retroactive to 2022).
- ABLE credit (872): a qualified ABLE rollover contribution under IRC 530A(d)(4)(B) is not a contribution (SEA 243).
- Employer child care expenditure credit (876), health reimbursement arrangement credit (878), redevelopment (863), venture capital (835) and affordable and workforce housing (871) changed for 2026; see each file.
## Files in this folder
- credits.md - this index (IT-40, lines 12-14)
- schedule-5/schedule-5.md - index, Schedule 5, lines 1-13
  - schedule-5/unified-tax-credit-for-the-elderly.md - line 5
  - schedule-5/earned-income-credit.md - line 6; Schedule IN-EIC
  - schedule-5/lake-county-residential-income-tax-credit.md - line 7
  - schedule-5/edge-credit.md - line 8; Schedule IN-EDGE
  - schedule-5/edge-retention-credit.md - line 9; Schedule IN-EDGE-R
  - schedule-5/headquarters-relocation-credit-refundable.md - line 10
  - schedule-5/adoption-credit.md - line 11; Adoption Credit Worksheet lines 1-47
- schedule-6/schedule-6.md - index, Schedule 6, lines 1-8, with the list of every three-digit code
  - schedule-6/combined-limitations.md - the one-per-project restriction and both Combined Limitations
  - schedule-6/local-taxes-paid-outside-indiana.md - line 1
  - schedule-6/community-revitalization-enhancement-district-credit.md - line 2
  - schedule-6/other-local-credits.md - line 3
  - schedule-6/college-credit.md - line 4; Schedule CC-40
  - schedule-6/credit-for-taxes-paid-to-other-states.md - line 5
  - schedule-6/schedule-in-occ.md - line 7
  - one file per three-digit credit code (line 6 or Schedule IN-OCC), listed in schedule-6/schedule-6.md
## Questions
- Did you have Indiana state or county tax withheld, or make estimated payments? (payments/)
- Were you or your spouse 65 or older with federal AGI under $10,000 (2025 amount; confirm against the 2026 form)?
- Did you claim the federal earned income credit or the federal adoption credit?
- Do you own and pay property tax on a home in Lake County, Indiana?
- Did you pay income tax to another state or to a non-Indiana locality?
- Did you give to an Indiana college, contribute to Indiana529 or an Indiana ABLE account, or buy classroom supplies as an Indiana public school educator?
- Did you receive a Schedule IN K-1 or an IEDC, IHCDA or DOR certificate showing a credit?
## Prompt
- Which Indiana credits are refundable?
- Why was my Indiana credit for taxes paid to another state cut down?
- Where do I put the Indiana529 credit?
