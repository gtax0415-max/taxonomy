---
type: income
category: income
jurisdiction: AR
tax_year: 2026
source_doc: Form 1099-B and brokerage statements / Form 1099-DIV box 2a / federal Schedule D and Form 8949 as filed / basis and depreciation records for sold property / capital loss carryover from the prior year / Forms 3921, 6781 and 6252 as filed
form: Form AR1000F
line: "14"
via:
  - Federal Schedule D → AR1000D, lines 1–12 → Form AR1000F, line 14 → line 23
---
# Capital Gains and Losses
## Description
Arkansas starts from federal Schedule D, adjusts for depreciation differences, and taxes only half of net long-term gain. Net capital gain above $10 million is exempt. Short-term gain is taxed in full.

## Notes
- Net long-term gain: 50% exclusion (only 50% is taxed)
- Net capital gain over $10,000,000: excess exempt (AR1000D line 7b caps the gain at $10,000,000)
- Short-term gain: taxed in full
- Net loss limit: $3,000 ($1,500 per taxpayer for Status 4 or 5); the unused loss carries forward
- Adjust for federal/Arkansas depreciation and pass-through entity tax differences on AR1000D lines 2, 5, and 10
- Status 4: each spouse's AR1000D line 12 goes to their own column
- Arkansas has no alternative minimum tax: exercising an incentive stock option (Form 3921) creates no Arkansas income until the shares are sold
- Character follows the federal return: Section 1256 contracts keep the 60% long-term / 40% short-term split (Form 6781), capital gain distributions (Form 1099-DIV box 2a) are long-term, and an installment sale reports the year's gain from federal Form 6252
- Stock compensation (RSUs, ESPP) uses the corrected basis from the broker's supplemental statement, so income already in W-2 wages is not taxed twice
- No change for 2026

## Required Information
- Federal Schedule D and Form 8949
- Depreciation differences for sold business or rental property
- Arkansas capital loss carryover

## Questions
- Did you sell stock, funds, crypto, or property in 2026?
- Were the gains long-term or short-term?
- Do you have a capital loss carryover?
- Did you sell property depreciated differently for Arkansas?

## Common Errors
- Forgetting the 50% long-term exclusion
- Using the federal $3,000 loss limit for Status 4/5 filers ($1,500 each)
- Skipping depreciation differences on sold property
- Applying the exclusion to short-term gain
- Using the understated Form 1099-B basis for RSU shares

## Prompt
- I sold stock I held for three years.
- I have a capital loss carryover.
