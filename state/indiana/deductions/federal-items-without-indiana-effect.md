---
type: deduction
category: federal-items-without-indiana-effect
jurisdiction: IN
tax_year: 2026
source_doc: Federal Form 1040 or 1040-SR (AGI line and the deductions below it) / federal Schedule A / federal Schedule 1-A
form: Form IT-40
line: "1"
via:
  - Federal Form 1040, line 11 (federal AGI) → Form IT-40, Line 1
  - Federal deductions taken after line 11 → no Indiana effect
routing:
  - "Federal standard deduction or itemized deductions (Schedule A) → no Indiana deduction"
  - "Qualified business income deduction (IRC 199A) → no Indiana deduction"
  - "Federal senior deduction (P.L. 119-21) → no Indiana deduction; see the Indiana age 65 exemptions"
  - "Federal non-itemizer charitable deduction (P.L. 119-21) → no Indiana deduction"
  - "Federal qualified tips, overtime or car loan interest deduction (Schedule 1-A) → separate 2026-only Indiana deductions on Schedule 2, line 11"
  - "Recovered itemized deduction reported as federal other income → Schedule 2, line 3 or code 616"
see_also:
  - deductions/deductions.md
  - deductions/schedule-2/qualified-tips-deduction.md
  - deductions/schedule-2/qualified-overtime-deduction.md
  - deductions/schedule-2/qualified-passenger-vehicle-loan-interest-deduction.md
  - deductions/schedule-2/recovery-of-deductions-616.md
  - deductions/schedule-2/state-tax-refund.md
  - deductions/exemptions/age-65-or-blind-exemption.md
---
# Federal Items Without Indiana Effect (Form IT-40, Line 1)
## Description
Form IT-40, line 1 is federal adjusted gross income from federal Form 1040 or 1040-SR, line 11 (2025 form line; confirm the line on the 2026 federal form). Everything the federal return subtracts after AGI to reach federal taxable income stays on the federal return. Indiana replaces those items with its own Schedule 2 deductions and Schedule 3 exemptions.
For 2026 Indiana conforms to the Internal Revenue Code as in effect on January 1, 2026 (SEA 243; the 2025 booklet used January 1, 2023), so federal AGI on line 1 reflects the P.L. 119-21 changes that work through AGI. Bonus depreciation is still added back, and a new modification applies to qualified production property (IRC 168(n)); those are Schedule 1 add-backs, outside this folder.
## Federal items that do not reach Indiana
| Federal item | Where on the federal return | Indiana treatment |
|---|---|---|
| Standard deduction | Form 1040, below AGI | None. Indiana has no standard deduction; it uses Schedule 3 exemptions |
| Itemized deductions (Schedule A): mortgage interest, state and local taxes, medical, charitable, casualty, other | Below AGI | None. Indiana allows only its own items: the renter's deduction (Schedule 2, line 1) and homeowner's property tax deduction (line 2) |
| Qualified business income deduction (IRC 199A) | Below AGI | None |
| Senior deduction (P.L. 119-21) | Federal Schedule 1-A, below AGI | None. Indiana gives a $1,000 age 65 exemption and an income-tested $500 additional age 65 exemption (2025 amount; confirm against the 2026 form) on Schedule 3 |
| Charitable deduction for non-itemizers (P.L. 119-21) | Below AGI | None |
| Qualified tips, qualified overtime, qualified passenger vehicle loan interest | Federal Schedule 1-A, below AGI | Indiana enacted matching deductions for 2026 only (IC 6-3-2-31, -32, -33) on Schedule 2, line 11; code to be assigned on the 2026 form |
## Related rules
- Recoveries: if a prior-year itemized deduction is recovered and reported as federal income, Indiana takes it back out: state tax refunds on Schedule 2, line 3; other recovered itemized deductions with code 616.
- Repayments of previously taxed income: federally an itemized deduction or credit, but Indiana allows a Schedule 2 deduction (code 630) whether or not the taxpayer itemizes.
- NOLs: for 2021 and later, itemized deductions are not permitted in figuring an Indiana net operating loss; federal standard or itemized deductions that increase a federal NOL must be removed (pro forma federal Form 172).
## Example
A single filer has federal AGI of $80,000 (2025 amount; confirm against the 2026 form), takes the federal standard deduction and a $3,000 QBI deduction, and claims $4,000 of qualified overtime on Schedule 1-A. Form IT-40, line 1 is $80,000. The standard deduction and QBI have no Indiana effect. The $4,000 overtime deduction is entered on Schedule 2, line 11 (2026 only).
## Questions
- What is your federal AGI (Form 1040, line 11)?
- Did you itemize, and did you recover any itemized deduction this year?
- Did you claim any Schedule 1-A deductions (tips, overtime, car loan interest, senior)?
## Common Errors
- Entering federal taxable income instead of federal AGI on line 1
- Deducting mortgage interest, property tax in full, or charitable gifts because they were itemized federally
- Assuming the federal senior deduction carries to Indiana
- Omitting the 2026-only tips, overtime and car loan interest deductions because they are below the federal AGI line
## Prompt
- Does my federal standard deduction carry over to Indiana?
- Can I deduct my charitable donations on my Indiana return?
- Does Indiana allow the new federal senior deduction?
