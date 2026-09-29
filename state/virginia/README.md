---
type: index
category: index
jurisdiction: VA
tax_year: 2026
form: Form 760
line: "-"
---
# Virginia Individual Income Tax - Taxonomy (Tax Year 2026)

One markdown file per attribute of the Virginia resident return (Form 760), with YAML frontmatter (type, category, jurisdiction, tax_year, source_doc, form, line, refundable for credits, via, routing, see_also) and standard sections (Description, topical sections, Questions, Common Errors, Prompt). Each folder has an index file named after the folder that explains how its lines flow and lists every file in it. Virginia starts from federal adjusted gross income, so the taxonomy follows Form 760 in return order: filing, income, deductions, credits, tax computation, payments, contributions.

Top-level folders (full Form 760 coverage, in return order):
- filing/ - who must file, residency and choosing Form 760, 760PY or 763, filing status, due dates and extensions, amended returns, header ovals, locality code, dependent oval, health coverage consent (Schedule HCI), signatures, preparer section and filing election codes (11 files)
- income/ - federal adjusted gross income (Line 1) and the adjustments to reach Virginia adjusted gross income (Lines 2-9): Schedule ADJ additions and subtractions, the age deduction, Social Security, state refunds (2 files plus additions/ with 12 and subtractions/ with 31)
- deductions/ - itemized deductions (Virginia Schedule A) or standard deduction, exemptions, Schedule ADJ deductions; Lines 10-15 (2 files plus exemptions/ with 3, itemized/ with 7 and schedule-adj/ with 21)
- credits/ - Credit for Low-Income Individuals and Virginia Earned Income Credit (Line 23), credit for tax paid to another state (Line 24), Schedule CR credits (Line 25) (1 file plus income-based/ with 3, other-state-tax/ with 1 and schedule-cr/ with 39 in seven category folders)
- tax-computation/ - tax rate schedule (Line 16), Spouse Tax Adjustment (Line 17), net tax (Line 18), addition to tax for underpaid estimated tax (Form 760C and 760F), penalties and interest (Schedule ADJ Lines 18-21, Form 760 Line 32), consumer's use tax (Line 33) (7 files)
- payments/ - withholding, estimated, prior year and extension payments (Lines 19a-22), tax owed or overpayment (Lines 27-28), credit to next year (Line 29), Line 34, amount you owe and payment options (Line 35), refund and direct deposit (Line 36) (8 files)
- contributions-checkoffs/ - Schedule VAC: Commonwealth Savers contributions (Line 30) and voluntary contributions to listed organizations, library and public school foundations (Line 31) (2 files)

## Full Form 760 coverage map
| Form 760 | Attribute | Folder |
|---|---|---|
| Header | Residency, filing status, federal head of household oval, ovals, locality code, amended reason code, Schedule HCI consent, exemption boxes | filing/ (exemptions in deductions/exemptions/) |
| Line 1 | Federal adjusted gross income | income/ |
| Lines 2-3 | Additions (Schedule ADJ Lines 1-3, Schedule ADJS) | income/additions/ |
| Lines 4-8 | Age deduction, Social Security and Tier 1, state refund, Schedule ADJ subtractions | income/subtractions/ |
| Line 9 | Virginia adjusted gross income and the filing threshold | income/, filing/filing-requirements.md |
| Lines 10-11 | Itemized (Virginia Schedule A) or standard deduction | deductions/ |
| Line 12 | Exemptions (Sections A and B) | deductions/exemptions/ |
| Line 13 | Schedule ADJ deductions (codes 101-119, 199) | deductions/schedule-adj/ |
| Lines 14-15 | Total deductions, Virginia taxable income | deductions/ |
| Lines 16-18 | Tax, Spouse Tax Adjustment, net tax | tax-computation/ |
| Lines 19a-22 | Withholding, estimated, prior year overpayment, extension payments | payments/ |
| Lines 23-26 | Income-based credit, other state credit, Schedule CR, total payments and credits | credits/ |
| Lines 27-29 | Tax you owe, overpayment, credit to 2027 | payments/ |
| Lines 30-31 | Schedule VAC contributions | contributions-checkoffs/ |
| Line 32 | Addition to tax, penalty and interest | tax-computation/ |
| Line 33 | Consumer's use tax | tax-computation/ |
| Lines 34-36 | Total, amount you owe, refund and direct deposit | payments/ |
| Page 2 footer | Preparer authorization, 1099-G, signatures, ID Theft PIN, filing election, PTIN | filing/ |

Sources: the 2026 Form 760 instructions (draft of September 17, 2026) and the 2026 draft Form 760, Schedule ADJ, ADJS, Virginia Schedule A, Schedule CR, OSC, VAC, VACS and HCI, all early-release drafts not for filing. Form 760C and Form 760F have no 2026 draft; files relying on the 2025 forms say so and should be confirmed against the 2026 forms.

## 2026 figures used across the taxonomy
| Item | 2026 | File |
|---|---|---|
| Filing threshold (VAGI) | $11,950 Filing Status 1 or 3; $23,900 Filing Status 2 | filing/filing-requirements.md |
| Due date | May 1, 2027 (July 1, 2027 if overseas); automatic 6-month extension | filing/due-dates-and-extensions.md |
| Tax rates | 2% to $3,000; 3% to $5,000; 5% to $17,000; 5.75% over $17,000 | tax-computation/tax-rate-schedule.md |
| Standard deduction | $8,750 Filing Status 1 or 3; $17,500 Filing Status 2 | deductions/standard-deduction.md |
| Exemptions | $930 personal and dependent; $800 each 65 or older and blind | deductions/exemptions/ |
| Age deduction | up to $12,000 each, born on or before January 1, 1962; income limit $50,000 single, $75,000 married | income/subtractions/age-deduction.md |
| Spouse Tax Adjustment | up to $259 | tax-computation/spouse-tax-adjustment.md |
| Virginia Earned Income Credit | 20% of the federal credit, refundable | credits/income-based/virginia-earned-income-credit.md |
| Credit for Low-Income Individuals | $300 per exemption | credits/income-based/low-income-individuals-credit.md |
| Estimated tax underpayment threshold | $1,000 (was $150) | tax-computation/addition-to-tax-underpayment.md |
| Itemized deduction limitation thresholds | $408,900 joint; $374,800 head of household; $340,750 single; $204,450 separate | deductions/itemized/itemized-deduction-limitation.md |
| Consumer's use tax | 5.3%, 6%, 6.3% or 7% by locality; 1% on food and hygiene products | tax-computation/consumer-use-tax.md |

## What changed for 2026
- IRC conformity: fixed conformity date of December 31, 2025, conforming to most of 2025 H.R. 1; deconformity continues for bonus depreciation and certain business provisions; section 179 conformity adjustments may be needed (income/additions/conformity-additions.md, income/subtractions/conformity-subtractions.md)
- New subtraction for IRC 280E-disallowed expenses of a Virginia-licensed cannabis business (income/subtractions/cannabis-business-expenses.md)
- Eligible educator deduction reinstated (deduction code 118; it was not available for 2025)
- Wildlife Corridor Grant Fund added to Schedule VAC (code 21)
- Estimated tax underpayment threshold raised from $150 to $1,000
- Credit changes: Motion Picture Production extended to January 1, 2031; Pass-Through Entity Elective Tax credit sunset eliminated; Major Business Facility Job and Worker Training expired July 1, 2025; Qualified Equity and Subordinated Debt and Communities of Opportunity expired January 1, 2026 (carryovers remain)

## Key rules that cross folders
- Standard or itemized must match the federal return; if one spouse itemizes, the other must too
- The age deduction bars the disability subtraction, the Credit for Low-Income Individuals and the refundable Virginia Earned Income Credit; the Low-Income credit bars the 65 or older and blind exemptions
- Nonrefundable credits in total cannot exceed Form 760, Line 18
- Lines 29-33 come out of an overpayment first (Line 34)

## Items to confirm before filing
- Form 760C and Form 760F rules, installment exceptions and the daily addition to tax rate (2025 forms; 2026 forms not yet released)
- Any conformity changes made by the 2027 General Assembly Session
- All figures, which come from early-release drafts
