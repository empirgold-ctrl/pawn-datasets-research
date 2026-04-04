# pawn_loan_activity

Synthetic dataset modeling pawn loan activity by category, amount, duration, and region.

Scenario: `baseline`

Synthetic dataset for research and modeling. No real customer-level data included.

King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## What This Dataset Shows

Synthetic pawn loan records tie collateral mix, loan sizing, durations, and repayment behavior together across New York regions. This build contains 12,344 rows under the baseline scenario.

## Modeling Narrative

Baseline operating conditions with steady category mix, realistic outliers, and moderate seasonal movement.

## Key Observations

- Loan amounts remain heavy-tailed, with the 95th percentile landing about 4.72x the median ticket size.
- Repeat customers default at 2.3% versus 8.1% for non-repeat borrowers.
- Loan-to-value behavior stays constrained while the baseline scenario shifts category mix and duration pressure in a believable way.

## Versioning

- Version: `2026-04-04`
- Canonical hash: `ecf983e9fc2d2dafc1bacfbfe9ccc05b189703fd251d3592453fd0527e2c867c`
- Row count: `12344`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`

## Related Datasets

- `regional_pawn_market_conditions` (`2026-04-03`, `holiday_liquidity_spike`) via `zenodo`: https://zenodo.org/record/19411057
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19411864
- Zenodo record: https://zenodo.org/record/19411864
- OpenML dataset record: https://www.openml.org/d/47167
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-pawn-loan-activity-open
