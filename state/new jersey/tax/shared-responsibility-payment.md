---
type: tax
category: health-coverage
jurisdiction: new-jersey
tax_year: 2026
source_doc: Forms 1095-A, 1095-B and 1095-C / health coverage exemption approval letter (exemption number) / income documents for every household member (Forms W-2 and 1099)
form: Form NJ-1040
line: "53a, 53b, 53c"
via:
  - Schedule NJ-HCC + Worksheet L → Form NJ-1040, Line 53c (fill in the NJ-HCC oval)
  - Uninsured on the filing date → Line 53a oval + NJ-EZ Enroll form
  - Request Get Covered NJ help → Line 53b oval
routing:
  - "Line 29 at or below the filing threshold ($10,000 / $20,000) → no SRP; skip Line 53c"
  - "Can be claimed as someone else's dependent → no SRP; Schedule NJ-HCC Part I only (Yes oval)"
  - "Everyone covered all year (or exempt) → no SRP; Schedule NJ-HCC Part I only, fill in the oval"
  - "Any month without coverage or exemption → Schedule NJ-HCC Part II + Worksheet L"
  - "Filled in 53a AND 53b (and Yes on NJ-EZ Enroll Step 3), then enrolls and keeps coverage → SRP waived; make no entry on 53c"
---
# Health Coverage Mandate and Shared Responsibility Payment (Lines 53a–53c)
## Description
New Jersey requires residents who must file (and everyone in their tax household) to have minimum essential health coverage every month, unless exempt. A household that goes without coverage owes a SHARED RESPONSIBILITY PAYMENT (SRP) on Line 53c, added to tax. The SRP is subject to the same penalties and interest as income tax.
## Lines 53a and 53b (coverage status on the FILING DATE)
- 53a: fill in if anyone in the tax household is uninsured NOW; enclose the NJ-EZ Enroll form
- 53b: fill in to let Get Covered New Jersey use return data to help enroll; if they enroll and keep coverage for the rest of the year, the SRP is waived
## Tax household
Taxpayer, spouse (joint), a claimed domestic partner, claimed dependents, and anyone who COULD be claimed as a dependent.
## Minimum essential coverage
Marketplace plans; qualifying individual plans; grandfathered plans; most employer plans, retiree plans, and COBRA; Medicare Part A; most Medicaid; CHIP; coverage on a parent's plan; most student plans; Peace Corps; certain VA coverage; most TRICARE; DoD NAF; Refugee Medical Assistance. Coverage for any part of a month counts for the whole month. Short-term plans do NOT qualify.
## Exemptions
Income- and health-care-related, group membership, incarceration, living abroad, and hardship exemptions — apply through the NJ Insurance Mandate Coverage Exemption Application to get an exemption number for Schedule NJ-HCC.
## Worksheet L — the calculation
1. HOUSEHOLD INCOME = NJ-1040 Line 27 + Line 16b of the taxpayer and all dependents (including estimated income of non-filing dependents). Do not use federal income
2. INCOME PERCENTAGE AMOUNT = (household income − filing threshold of $10,000 or $20,000) × 2.5%
3. FLAT AMOUNT = $695 per adult (18+) + $347.50 per child under 18, capped at $2,085 per household. Partial-year: $57.92 per adult-month and $28.96 per child-month uncovered
4. Take the GREATER of the flat amount or the income percentage amount (prorated for months uncovered)
5. CAP = statewide average annual BRONZE plan premium × household members (maximum five)
## 2026 parameters
- $695 / $347.50 / $2,085 flat amounts and the 2.5% rate are set by statute — unchanged for 2026
- The BRONZE CAP is updated annually. For 2025 it was $4,908 per person ($24,540 for five or more). The 2026 figure had not been published in the instructions yet — use the 2026 Worksheet L or the Division's 2026 SRP estimator
- A child under 18 on January 1, 2026 is treated as under 18 all year
## Part-year residents
Only months of NJ residency count; the threshold test uses FULL-YEAR income.
## Required Information
- Monthly coverage for every household member (Forms 1095)
- Exemption numbers
- Household income (Line 27 + Line 16b for all members)
- Ages on January 1, 2026
## Questions
- Did everyone in your household have health coverage every month of 2026?
- Is anyone uninsured right now?
- Do you have a coverage exemption number?
- What is your household's total income, including dependents?
## Common Errors
- Using federal AGI for household income
- Omitting dependents' income
- Forgetting Schedule NJ-HCC when everyone was covered (Part I and the oval are still required)
- Assuming short-term health plans satisfy the mandate
- Missing the waiver by not filling in both 53a and 53b
## Prompt
- I didn't have health insurance for six months in 2026.
- What is the New Jersey health insurance penalty?
