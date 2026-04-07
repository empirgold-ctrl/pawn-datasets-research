# collateral_distribution_and_liquidity

Synthetic category-level view of collateral mix, value bands, and liquidity characteristics.

Scenario: `seasonal_back_to_school`

Synthetic dataset for research and modeling. No real customer-level data included.

King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## What This Dataset Shows

Synthetic collateral mix data shows how value, liquidity, and seasonality differ across core pawn inventory categories and subcategories. This build contains 48 rows under the seasonal back to school scenario.

## Modeling Narrative

Electronics and smaller-ticket demand shift seasonally as late-summer and early-fall liquidity needs rise.

## Key Observations

- Collateral shares normalize to 100.00% of total inventory, keeping the mix internally consistent.
- Jewelry and many electronics rows retain higher liquidity scores than tools or miscellaneous collateral, which preserves realistic resale asymmetry.
- The seasonal back to school scenario keeps both mid-value and high-value subcategories in the same bundle so analysts can see meaningful spread instead of flat averages.

## Versioning

- Version: `2026-04-07`
- Canonical hash: `1b60966a65a39597fc1424a8735d57b871eae25b44aa734e0a602c35c91bab08`
- Row count: `48`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`

## Related Datasets

- `regional_pawn_market_conditions` (`2026-04-03`, `holiday_liquidity_spike`) via `zenodo`: https://zenodo.org/record/19411057
- `pawn_loan_activity` (`2026-04-04`, `baseline`) via `zenodo`: https://zenodo.org/record/19411864
- `gold_price_vs_pawn_activity` (`2026-04-05`, `high_gold_price_cycle`) via `zenodo`: https://zenodo.org/record/19429678
- `customer_behavior_segments` (`2026-04-06`, `consumer_stress_cycle`) via `zenodo`: https://zenodo.org/record/19433262
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19446296
- Zenodo record: https://zenodo.org/record/19446296
- OpenML dataset record: https://www.openml.org/d/47172
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-collateral-liquidity
