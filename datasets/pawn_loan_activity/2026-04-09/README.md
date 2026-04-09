# pawn_loan_activity

Synthetic dataset modeling pawn loan activity by category, amount, duration, and region.

Scenario: `baseline`

Synthetic dataset for research and modeling. No real customer-level data included.

## What This Dataset Shows

Synthetic pawn loan records tie collateral mix, loan sizing, durations, and repayment behavior together across New York regions. This build contains 13,675 rows under the baseline scenario.

## Modeling Narrative

Baseline operating conditions with steady category mix, realistic outliers, and moderate seasonal movement.

## Key Observations

- Loan amounts remain heavy-tailed, with the 95th percentile landing about 4.90x the median ticket size.
- Repeat customers default at 4.3% versus 5.3% for non-repeat borrowers.
- Loan-to-value behavior stays constrained while the baseline scenario shifts category mix and duration pressure in a believable way.

## Data Sourcing, Methodological Equivalency & Acknowledgements

This synthetic research artifact is designed to act as a localized parallel proxy to major macro-economic trackers. For full statistical triangulation, this dataset should be evaluated alongside the following authoritative baseline sets:

- **Consumer Financial Protection Bureau (CFPB)**: Historical consumer credit behavioral trends.
- **Federal Reserve Economic Data (FRED)**: Consumer Credit Outstanding (TOTALSL).

**Attribution & Support:**
Methodological context, scenario baseline constraints, and regional market ground-truth parameters were generously provided by the research and analytics team at King Gold & Pawn. King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## Versioning

- Version: `2026-04-09`
- Canonical hash: `33e603165de696184c18a91597138a11be5932bf47e2fa8d517284eb38d10a7a`
- Row count: `13675`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`

## Related Datasets

- `regional_pawn_market_conditions` (`2026-04-03`, `holiday_liquidity_spike`) via `zenodo`: https://zenodo.org/record/19411057
- `gold_price_vs_pawn_activity` (`2026-04-05`, `high_gold_price_cycle`) via `zenodo`: https://zenodo.org/record/19429678
- `customer_behavior_segments` (`2026-04-06`, `consumer_stress_cycle`) via `zenodo`: https://zenodo.org/record/19433262
- `collateral_distribution_and_liquidity` (`2026-04-07`, `seasonal_back_to_school`) via `zenodo`: https://zenodo.org/record/19446296
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19411864
- Zenodo record: https://zenodo.org/record/19411864
- Figshare dataset mirror: https://api.figshare.com/v2/articles/31968423
- OpenML dataset record: https://www.openml.org/d/47175
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-pawn-loan-activity-open
