# gold_price_vs_pawn_activity

Synthetic time-series linking gold price movements to pawn loan volume and average ticket size.

Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md

## Latest Version

- Version: `2026-04-05`
- Scenario: `high_gold_price_cycle`
- Row count: `833`
- Realism score: `1.0`
- Summary: Synthetic daily gold-linked lending data tracks how price movement, jewelry exposure, loan volume, and repayment behavior move together over time. This build contains 833 rows under the high gold price cycle scenario.

## Key Observations

- Gold prices keep a directional time-series trend instead of flat noise, with a time correlation of 0.98.
- Average jewelry loan amounts move with gold prices, with a modeled correlation of 0.93.
- This build contributes 833 daily observations so macro shifts can be studied without losing regional variation.

## Available Versions

- `2026-04-05` | `high_gold_price_cycle` | GitHub: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/datasets/gold_price_vs_pawn_activity/2026-04-05/README.md
