---
type: deduction
category: conformity
jurisdiction: NYS
source_doc: Form IT-201, Line 19 (federal AGI, the starting point) / federal Form 1040 and Schedules 1, 1-A, and A / New York Tax Law Article 22
form: Form IT-201
line: "19"
refundable: n/a
via:
  - Federal Form 1040, Line 11 (federal AGI) → Form IT-201, Line 19
---
# Conformity: What New York Follows and What It Does Not
## Description
New York starts from FEDERAL ADJUSTED GROSS INCOME, not federal taxable income. That single design choice determines which federal deductions reach a New York return and which never do. This file exists because the question "does New York allow the federal X deduction" almost always has the same answer, and the answer depends on WHERE X sits on the federal return.
## The rule that answers most questions
| Where the federal deduction sits | Reaches New York? |
|---|---|
| ABOVE the line — Schedule 1, Part II adjustments | YES, automatically. It is already inside federal AGI |
| BELOW the line — Schedule A itemized deductions | NO. New York computes its own on Form IT-196 |
| BELOW the line — standard deduction | NO. New York has its own, much smaller |
| BELOW the line — QBI, Schedule 1-A deductions | NO. Nothing carries them into New York |
Above-the-line adjustments need no New York file at all. Student loan interest, HSA contributions, self-employed health insurance, educator expenses, IRA deductions, and the self-employment tax deduction all reduce federal AGI, so New York inherits them without doing anything.
## Federal deductions that get NOTHING from New York
### Qualified business income (QBI, IRC 199A)
Taken after AGI on the federal return. It never touches federal AGI, so it never reaches New York. A New York business owner with a $50,000 QBI deduction pays New York tax on the full amount. There is no state analogue and no workaround. This is one of the largest single federal-state gaps for pass-through owners.
### Overtime premium deduction (OBBBA)
New York did NOT conform. Overtime premium pay is fully taxable for New York even though up to $12,500 (single) or $25,000 (joint) is deductible federally for 2025 through 2028.
### The federal standard deduction
Irrelevant to New York entirely. See standard/.
## Qualified tips: changed for 2026
New York did NOT conform for 2025 — tips were fully taxable for New York even after the federal deduction existed. New York's enacted 2026 budget adopted a state-level tips deduction beginning with tax years starting January 1, 2026, amending Tax Law Section 612.
For a tipped worker this means:
- 2025 return: federal deduction yes, New York deduction NO
- 2026 return: both
Because this was enacted very recently, confirm the final cap, phase-out, and definition of qualified tips against the 2026 Form IT-201 instructions before relying on it. The state version was drafted to mirror the federal one but is not identical.
## Static conformity
New York is a STATIC conformity state. It does not automatically adopt federal changes as they are enacted; the legislature must act. This is why the 2025 and 2026 answers differ for tips, and why they may differ again for overtime if Albany acts later.
Practical consequence: when a new federal deduction appears, the default New York answer is NO until legislation says otherwise. Do not assume flow-through.
## The itemized deduction freeze
New York itemized deductions are computed under the federal rules AS THEY EXISTED BEFORE the Tax Cuts and Jobs Act — that is, 2017 law. This cuts in New York's favor. Deductions the TCJA eliminated federally are still alive for New York. See itemized/.
## Required Information
- Federal Form 1040 and all schedules, to identify where each deduction sits
- Whether a deduction reduced federal AGI or was taken after AGI
- For 2026, whether the New York tips deduction applies
## Questions
- Which federal deductions did you claim, and were they above or below the line?
- Do you have a QBI deduction, which New York does not allow?
- Do you earn tips or overtime premium pay?
- Are you working from a prior-year return where the New York answer has since changed?
## Common Errors
- Assuming the federal QBI deduction reduces New York income
- Assuming tips or overtime are exempt for New York because they are federally
- Applying the 2026 New York tips rule to a 2025 return
- Re-entering above-the-line adjustments as New York subtractions, double-counting them
- Assuming New York adopts a new federal provision automatically
## Prompt
- Does New York follow the federal tax law?
- I have a QBI deduction, does it help my New York return?
- Are my tips taxed by New York?
