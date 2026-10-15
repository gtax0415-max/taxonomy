---
type: credit
category: retirement-income
jurisdiction: UT
tax_year: 2026
source_doc: Form SSA-1099 for each spouse / 2026 federal Form 1040 line 6b (taxable Social Security) and line 2a (tax-exempt interest) / Form 1099-INT or 1099-DIV showing non-Utah municipal bond interest
form: Form TC-40
line: "21"
refundable: no
via:
  - Federal 1040 line 6b and MAGI → Social Security Credit worksheet (TC-150) → TC-40_A, Part 1 (code AN005PT) → Form TC-40, line 21
---
# Social Security Benefits Credit
## Description
Credit equal to Utah tax on taxable Social Security benefits (retirement, disability, survivor), phased out above an income threshold (UCA §59-10-1042).

## Amount
1. Taxable Social Security from 1040 line 6b (1040-NR: Schedule NEC line 8)
2. Minus any Social Security included in Native American income (SU002PT), Railroad Retirement (SU003PT) or Social Security repayment subtractions
3. × 4.45%
4. MAGI = TC-40 line 4 − AD007PT + 1040 line 2a
5. Threshold:
   - Married filing separately (and 1040-NR married): $45,000
   - Single: $54,000
   - Married filing jointly, qualifying surviving spouse, head of household: $90,000
6. Credit = line 3 − 2.5% × (MAGI − threshold), not below zero

## Eligibility
- Taxable Social Security in federal AGI
- Neither spouse claims the Retirement Credit (AN003PT)

## Notes
- DRAFT CONFLICT: the 9/29/26 TC-150 worksheet line 2 names the Social Security repayment subtraction as "SU028PT", but the 10/5/26 instructions code it SU014PT. Use SU014PT
- Can be claimed along with the Military Retirement Credit
- No carryforward

## Required Information
- SSA-1099, 1040 line 6b, MAGI inputs

## Questions
- Do you receive Social Security retirement, disability or survivor benefits?
- Is any of it taxable federally?

## Common Errors
- Using gross benefits instead of the taxable amount
- Using 4.5% (2025)
- Combining with the Retirement Credit
- Not backing out RRB Tier 1 amounts already subtracted

## Prompt
- Does Utah tax my Social Security?
