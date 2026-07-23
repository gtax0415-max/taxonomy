# taxonomy

A structured reference of common U.S. federal taxpayer situations, organized by how each item flows to Form 1040. Built for routing a taxpayer's own words ("I got a 1099-NEC", "I sold my house") to the rules that apply.

## Structure

GitHub lists folders alphabetically. The logical order, following the return itself, is:

1. **filing-status/** — the five statuses and their eligibility tests. Determines the standard deduction, bracket widths, and most thresholds
2. **income/** — income by type, routed to the Form 1040 line it lands on
3. **deductions/** — adjustments to income, standard versus itemized, QBI, Schedule 1-A, and Schedule C business expenses
4. **credits/** — refundable and nonrefundable credits

```
federal/
├── filing-status/   single, married filing jointly, married filing separately,
│                    head of household, qualifying surviving spouse
├── income/          wages, interest, dividends, capital-gains, business,
│                    rental-royalty, pass-through, retirement, social-security,
│                    unemployment, farming, other-income
├── deductions/      adjustments, standard, itemized, qbi, schedule-1-a,
│                    business-expenses
└── credits/         family-dependent, income-based, education, energy-home,
                     retirement-savings, health-insurance, foreign-tax
```

## File naming convention

Files are named by **what the taxpayer receives or experiences**, not by the form a preparer fills out.

**Form-named** — a third party sends the taxpayer a document, so the form is the natural entry point. A person says "I got a 1099-NEC."
`1099-nec.md`, `1099-k.md`, `1099-r.md`, `ssa-1099.md`, `w-2g.md`, `schedule-k1.md`

**Concept-named** — no document arrives, or the form is one the preparer computes. A person says "I sold business equipment," never "I filed Form 4797."
`sale-of-business-property.md` (Form 4797), `installment-sales.md` (Form 6252), `nondeductible-ira-basis.md` (Form 8606), `passive-activity-limits.md` (Form 8582), `home-sale.md` (Section 121), `cash-income.md`, `home-office.md`, `student-loan-interest.md`

This one rule explains why most **income** files are form-named (documents arrive) while most **deduction** files are concept-named (they usually do not).

**Box-named** — used inside `income/wages/`, and for boxes on one form that route to different Form 1040 lines.
`box-1a-w2-wages.md`, `box-1c-unreported-tips.md`, `box-5-section-199a.md`

## Frontmatter fields

| Field | Meaning |
|---|---|
| `type` | `income`, `deduction`, `credit`, or `filing-status` |
| `category` | the folder's subject, matching the folder name |
| `source_doc` | the document the taxpayer **receives or maintains**, with box or line numbers where they exist |
| `form` / `line` | the destination on Form 1040 |
| `via` | the route from source to destination, including any forms the preparer computes |
| `routing` | used when the same source can flow to different destinations |
| `refundable` | credits only: `yes`, `no`, or `partially` |
| `included_in` | for a box whose amount is a subset of another box |
| `see_also` | a pointer to the fuller entry when one topic is split across folders |

### What belongs in `source_doc`

Only what the taxpayer **receives from a third party** or **maintains as substantiation**:
- Received: Form W-2, Form 1099-*, Form 1098-*, Form 5498, Schedule K-1, Form 1095-A
- Maintained: mileage logs, receipts, participation time logs, depreciation workpapers

**Not** in `source_doc`: forms the preparer computes. Form 4562, Form 8829, Form 4952, Form 4684, Form 8283, Form 8839, and Schedule SE all belong in `via`.

One exception: a **prior-year** form kept as a carryforward record is a genuine source, because it is the only evidence of a figure the current return depends on. Prior-year Form 8606 (IRA basis) and prior-year Form 8582 (suspended passive losses) both qualify.

Every box and line reference names its form: `Form 1099-R Box 1`, `Form 1040 Line 4a` — never a bare `Box 1`.

## Body sections

`## Description`, `## Notes`, `## Required Information`, `## Questions`, `## Common Errors`, `## Prompt`

`## Prompt` holds example first-person statements a taxpayer might make, which is what the routing matches against. Many files add a `## Box-to-line mapping` section.

## Tax year

Figures reflect **tax year 2026** where amounts are year-specific, with 2025 shown for comparison when the two differ. Amounts come from IRS Revenue Procedure 2025-32 and IRS releases; where the IRS has not yet published a complete table, the file says so and points to the primary source rather than estimating.

Provisions from the **One Big Beautiful Bill Act** (OBBBA, enacted July 4, 2025) are flagged where they changed prior law. Several are significant for 2026:
- Child Tax Credit made permanent at $2,200; SALT cap raised to $40,400; new Schedule 1-A deductions for tips, overtime, car loan interest, and seniors
- Residential energy credits (Sections 25C and 25D) and clean vehicle credits **terminated**
- The enhanced Premium Tax Credit **expired**, restoring the 400%-of-poverty cliff
- New Form W-2 Box 12 codes TA, TP, and TT; new Form 1098-VLI; new Trump Accounts under Section 530A

## Coverage

96 files. Not yet covered: additional taxes on Schedule 2 (AMT, net investment income tax, additional Medicare tax), payments and estimated tax, filing procedure, and state taxes.
