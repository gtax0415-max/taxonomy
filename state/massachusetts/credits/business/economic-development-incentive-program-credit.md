---
type: credit
jurisdiction: MA
tax_year: 2026
category: business
source_doc: EACC credit certificate (certificate number and authorized amount) / EACC award letter / Massachusetts K-1 (Schedule 3K-1 or SK-1) for partners and shareholders
form: Massachusetts Form 1
line: "31, 47"
refundable: "if authorized, at 100%"
via:
  - Schedule EDIP → Schedule CMS, Section 1 (to offset tax) → Form 1, Line 31
  - Schedule EDIP → Schedule CMS, Section 2 (refund) → Form 1, Line 47
  - Massachusetts K-1 → Schedule CMS, Section 3 or 4 (no Schedule EDIP)
routing:
  - "Project certified after January 1, 2017 → skip to Schedule EDIP Line 11 and enter the EACC-authorized amount"
  - "Project certified before January 1, 2017 → Lines 1-5 (CEP, CEEP, CMRP) and/or Lines 6-10 (job creation)"
  - "Certificate issued before November 20, 2024 → credit type EDIPCR; on or after → EDICRD"
  - "Vacant storefront EDIP → credit type VACSTR, refundable at 100%"
---
# Economic Development Incentive Program Credit (Schedule EDIP)
## Description
Credit authorized by the Economic Assistance Coordinating Council (EACC) for taxpayers participating in certified economic development projects certified on or after January 1, 2010 (G.L. c. 62, § 6(g)). Refundable at 100% to the extent the EACC authorizes refundability.
## Calculation
- Post-2017 projects: the credit is the amount the EACC authorizes for the year (Line 11)
- Pre-2017 CEP/CEEP/CMRP: cost basis × EACC rate, limited to the award
- Pre-2017 job creation projects: new jobs × EACC rate, limited to the award (max $1,000,000); allowed only for the year AFTER the jobs are created (TIR 14-13)
- Line 12 refundable portion → Schedule CMS with the certificate number
## Key rules
- Certificate number is REQUIRED on Schedule CMS
- Partners and shareholders do NOT file Schedule EDIP; they report the K-1 credit on Schedule CMS
- Pre-2010 projects use Schedule EOAC
## Required Information
- Certificate number and EACC-authorized amount for 2026
- Project type and certification date
- K-1 with entity federal ID (if pass-through)
## Questions
- Do you have an EDIP certificate, and what amount is authorized for 2026?
- Is the credit authorized as refundable?
- Did it come to you on a Massachusetts K-1?
## Common Errors
- Omitting the certificate number
- Using the wrong credit type code (EDIPCR vs. EDICRD)
- Partners filing Schedule EDIP instead of reporting on Schedule CMS
## Prompt
- My company got an EDIP award.
