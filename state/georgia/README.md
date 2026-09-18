---
type: index
jurisdiction: GA
form: Form 500
tax_year: "2026"
---
# Georgia Individual Income Tax — Taxonomy (Tax Year 2026)

Mirrors the federal/New York per-item file format: one markdown file per item with YAML frontmatter (type, category, jurisdiction, source_doc, form, line, refundable/schedule, via, routing) and standard sections (Description, Amount/What is added/subtracted, Eligibility, Required Information, Questions, Common Errors, Prompt). Georgia's Form 500 is the analogue of New York's Form IT-201.

Branches (full Form 500 return coverage):
- filing/ — filing status, residency (full-year / part-year / nonresident + Schedule 3), filing requirements, amended returns (Form 500X)
- income/ — Schedule 1 income adjustments (additions/subtractions from federal AGI); Form 500 Lines 8–10
- deductions/ — standard vs. itemized deduction, dependent exemption, Georgia NOL; Form 500 Lines 11–15
- tax-computation/ — the 4.99% flat rate (Line 16), total credits and balance (Lines 22–23)
- credits/ — the Georgia tax credit taxonomy; Form 500 Lines 17–21
- payments-withholding/ — withholding, estimated tax (500ES), extensions (IT-303/IT-560), penalties & interest (500 UET), refund & direct deposit, surplus refund
- contributions-checkoffs/ — voluntary Checkoff Georgia donation funds that reduce a refund

## Full Form 500 coverage map
| Form 500 | Attribute | Branch |
|---|---|---|
| Status / residency | Who must file, status, full/part-year/nonresident, Schedule 3, 500X | filing/ |
| Line 8 | Federal AGI (start point) | income/ |
| Line 9 | Schedule 1 additions/subtractions | income/ |
| Line 10 | Georgia AGI | income/ |
| Lines 11–12 | Standard vs. itemized deduction | deductions/ |
| Line 14 | Dependent exemption | deductions/ |
| Line 15 | Taxable income + Georgia NOL (80% limit) | deductions/ |
| Line 16 | Tax (× 4.99% for 2026) | tax-computation/ |
| Lines 17–21 | Credits (Low Income, Other State, Itemizer, IND-CR, Schedule 2) | credits/ |
| Lines 22–23 | Total credits used and balance | tax-computation/ |
| Payments | Withholding, estimated tax, extension payments | payments-withholding/ |
| Penalties | Late-file/pay, estimated underpayment (500 UET), interest | payments-withholding/ |
| Refund | Refund, direct deposit, surplus refund | payments-withholding/ |
| Donations | Checkoff Georgia voluntary funds | contributions-checkoffs/ |

Sources: 2025 IT-511 Instructions Booklet (structure and the credit/adjustment items, which carry into 2026), updated for the confirmed tax-year-2026 changes in HB 463 (Georgia Economic Growth and Tax Relief Act of 2026, signed May 11, 2026) and the Georgia DOR Tax Credits / Repealed Tax Credits pages. The 2026 IT-511 booklet was not yet published when this was compiled, so 2026-specific FORM LINE placements (e.g., the new overtime/tips exclusions) are flagged "verify" and should be confirmed against the 2026 booklet when released.

## 2026 tax parameters (HB 463)
| Parameter | 2025 | 2026 | In this taxonomy? |
|---|---|---|---|
| Flat income tax rate | 5.19% | **4.99%** | Tax-computation branch (not yet built); noted in income.md |
| Standard deduction (single/HOH/MFS) | $12,000 | **$15,000** | deductions/items/standard-deduction.md |
| Standard deduction (MFJ) | $24,000 | **$30,000** | deductions/items/standard-deduction.md |
| Dependent exemption (per dependent) | $4,000 | **$5,000** | deductions/items/dependent-exemption.md |
| Retirement exclusion 62–64 | $35,000 | $35,000 (unchanged; →stays) | subtractions/retirement-income-exclusion.md |
| Retirement exclusion 65+ | $65,000 | $65,000 (unchanged in 2026; **$70,000 in 2027**) | subtractions/retirement-income-exclusion.md |
| Overtime exclusion | none | **up to $1,750 (TY2026–2028)** | subtractions/overtime-compensation-exclusion.md (NEW) |
| Cash tips exclusion | none | **up to $1,750 (TY2026–2028)** | subtractions/cash-tips-exclusion.md (NEW) |
| IRC conformity date | Jan 1, 2025 | **Jan 1, 2026** | income.md |
| SALT deduction cap | $10,000 | $10,000 (Georgia did not adopt federal increase) | deductions/items/itemized-deductions.md |
| Child & Dependent Care Credit | 50% of federal | 50% of federal (unchanged) | credits/family-dependent/ |
| Repealed credits (business) | — | **114, 131, 119, 147, 148/160, alt-fuel, teleworking** repealed 1/1/2026 | credits/business-passthrough.md |
| New business credit | — | **162 Employer Childcare Expense** begins TY2026 | credits/business-passthrough.md |

The flat rate continues stepping down 0.125%/year toward a 3.99% floor from 2027, subject to revenue triggers; standard deduction and dependent exemption also step up annually from 2027. None of the HB 463 credit repeals affect the individual-facing Line 17–20 credit files — all repealed items are business/Series 100 credits indexed in business-passthrough.md.

Credit code numbers and conformity items change annually — confirm against the current-year booklet.

## Income branch (income/)
Georgia starts from federal AGI (Form 500, Line 8), adjusts on Schedule 1, and lands Georgia AGI on Line 10.
| Schedule 1 | Direction | Folder | Count |
|---|---|---|---|
| Lines 1–6 | Additions to federal AGI | income/additions/ | 10 items |
| Lines 7–13 | Subtractions from federal AGI | income/subtractions/ | 16 items |
| Line 14 | Net adjustment → Form 500, Line 9 | income.md | — |

The Retirement Income Exclusion (up to $65,000 at 65+, $35,000 at 62–64) and the Military Retirement Income Exclusion (up to $35,000 under 62) are the dominant subtractions. Part-year and nonresident filers skip Form 500 Lines 9–14 and route adjustments through Schedule 3 instead.

## Credits branch (credits/)

## How Georgia's shape differs from federal / New York
- NO state earned income credit (New York gives 30%–45% of federal; Georgia gives a small fixed-table Low Income Credit instead)
- NO premium tax credit, NO long-term care insurance credit, NO nursing home assessment credit
- Georgia's "health" credits are health-care WORKFORCE credits (rural physicians/dentists, clinical preceptors)
- Three credits are claimed directly on Form 500 lines with no code (Low Income L17, Other State L18, Eligible Itemizer L19)

## Form 500 credit stacking order
| Line | Credit type | Folder |
|---|---|---|
| 17 | Low Income Credit | income-based/ |
| 18 | Other State(s) Tax Credit | income-based/ |
| 19 | Georgia Eligible Itemizer Credit (new 2025) | income-based/ |
| 20 | Series 200 individual credits (IND-CR Summary Worksheet) | family-dependent/, health-care/, housing-accessibility/, military-public-service/, disaster-relief/, education-workforce/ |
| 21 | Series 100 credits (Schedule 2); refundable on Schedule 2B | donation-contribution/, business-passthrough.md |

Universal cap: total credits used from Low Income + Other State + all IND-CRs + all Schedule 2s cannot exceed Form 500, Line 16 tax liability. Any return with a Series 100 credit must be filed electronically. Only Timber (145/155) is refundable.

## Categories
- income-based.md — Low Income (211), Other State (210), Eligible Itemizer
- family-dependent.md — Child & Dependent Care (202), Foster Adoption 2008–2020 (208), Foster Adoption 2021+ (213), Qualifying Child (215, verify)
- health-care.md — Qualified Caregiving Expense (204), Rural Physicians (207), Community Preceptor (212), Rural Health Care Professional (154)
- housing-accessibility.md — Disabled Person Home (201), Eligible Single-Family Residence (209, legacy)
- military-public-service.md — National Guard/Air National Guard (203)
- disaster-relief.md — Disaster Assistance (206)
- education-workforce.md — Teacher Recruitment & Retention (214)
- donation-contribution.md — QEE (125), RHO (136), QED/PEACH (140), QLED (150), QFCD (151)
- business-passthrough.md — index of all remaining Series 100 credits and refundable Timber credits

## Items to verify before filing
- Code 215 Qualifying Child Credit: first effective year, refundability, and form/line routing (listed by DOR, not in the 2025 IND-CR series)
- Exact list of credits repealed 1/1/2026 under the Georgia Economic Growth and Tax Relief Act of 2026
- Current-year contribution limits and statewide caps for the donation credits
- Current-year carryforward periods for the 2025 replacement codes (155, 157–161)
