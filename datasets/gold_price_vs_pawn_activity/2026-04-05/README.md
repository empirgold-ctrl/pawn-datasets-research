# gold_price_vs_pawn_activity

Synthetic time-series linking gold price movements to pawn loan volume and average ticket size.

Scenario: `high_gold_price_cycle`

Synthetic dataset for research and modeling. No real customer-level data included.

King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## What This Dataset Shows

Synthetic daily gold-linked lending data tracks how price movement, jewelry exposure, loan volume, and repayment behavior move together over time. This build contains 833 rows under the high gold price cycle scenario.

## Modeling Narrative

During periods of rising gold prices, jewelry-related loan values and metal-linked activity rise without making overall demand cartoonish.

## Key Observations

- Gold prices keep a directional time-series trend instead of flat noise, with a time correlation of 0.98.
- Average jewelry loan amounts move with gold prices, with a modeled correlation of 0.93.
- This build contributes 833 daily observations so macro shifts can be studied without losing regional variation.

## Versioning

- Version: `2026-04-05`
- Canonical hash: `3a2c5110046b1adfe91bed462790a7ff2d95040e230b944263814af29f3e06d5`
- Row count: `833`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`

## Related Datasets

- `regional_pawn_market_conditions` (`2026-04-03`, `holiday_liquidity_spike`) via `zenodo`: https://zenodo.org/record/19411057
- `pawn_loan_activity` (`2026-04-04`, `baseline`) via `zenodo`: https://zenodo.org/record/19411864
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19429678
- Zenodo record: https://zenodo.org/record/19429678
- OpenML dataset record: https://www.openml.org/d/47168
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-gold-price-vs-pawn-activity
