# taxonomy

Taxonomy of common taxpayer attributes per IRS forms, organized by how income and deductions flow to Form 1040.

## Structure

```
federal/
├── income/       — income by type, routed to the Form 1040 line it lands on
├── deductions/   — adjustments, standard, itemized, QBI, Schedule 1-A, business expenses
└── credits/      — tax credits
```

## File naming convention

Files are named by **what the taxpayer receives or experiences**, not by the form a preparer fills out.

**Form-named** — when a third party sends the taxpayer a document, the form is the natural entry point. A person says "I got a 1099-NEC."
- `1099-nec.md`, `1099-k.md`, `1099-r.md`, `ssa-1099.md`, `w-2g.md`, `schedule-k1.md`

**Concept-named** — when no document arrives, or when the form is computed by the preparer. A person says "I sold business equipment," never "I filed Form 4797."
- `sale-of-business-property.md` (Form 4797), `installment-sales.md` (Form 6252), `nondeductible-ira-basis.md` (Form 8606), `passive-activity-limits.md` (Form 8582), `cash-income.md`, `home-office.md`, `student-loan-interest.md`

This is why most **income** files are form-named (documents arrive) while most **deduction** files are concept-named (they usually do not). Both follow the same rule.

**Box-named** — used inside `income/wages/` and for form boxes that route to different Form 1040 lines.
- `box-1a-w2-wages.md`, `box-1c-unreported-tips.md`

## Frontmatter fields

- `type` — income, deduction
- `category` — the folder's subject
- `source_doc` — the document the taxpayer **receives or maintains**, with box or line numbers where they exist. Forms the preparer computes (Form 4562, 8829, 4952, Schedule SE) belong in `via`, not here
- `form` / `line` — the destination on Form 1040
- `via` — the route from source to destination, including any computing forms
- `routing` — used when the same source can flow to different destinations

## Body sections

`## Description`, `## Notes`, `## Required Information`, `## Questions`, `## Common Errors`, `## Prompt` (example first-person user statements)

## Tax year

Figures reflect **tax year 2026** where amounts are year-specific, with 2025 shown for comparison when the two differ. Provisions from the One Big Beautiful Bill Act (OBBBA, enacted July 4, 2025) are noted where they changed prior law.
