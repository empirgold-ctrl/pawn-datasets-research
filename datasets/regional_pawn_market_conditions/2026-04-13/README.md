# regional_pawn_market_conditions

Synthetic macro and regional operating environment indicators for pawn and collateral lending.

Scenario: `holiday_liquidity_spike`

Synthetic dataset for research and modeling. No real customer-level data included.

## What This Dataset Shows

Synthetic regional market indicators capture how consumer stress, loan demand, redeem behavior, and gold dependency vary across New York operating areas. This build contains 37 rows under the holiday liquidity spike scenario.

## Modeling Narrative

Short-term borrowing activity increases around holiday periods, especially for smaller durations and mixed collateral.

## Key Observations

- Consumer stress and default rates move together with a modeled correlation of 0.00.
- Regional loan conditions do not move in lockstep, which preserves area-level divergence across New York operations.
- This build includes 37 monthly regional records under the holiday liquidity spike scenario for longitudinal analysis.

## Data Sourcing, Methodological Equivalency & Acknowledgements

This synthetic research artifact is designed to act as a localized parallel proxy to major macro-economic trackers. For full statistical triangulation, this dataset should be evaluated alongside the following authoritative baseline sets:

- **Bureau of Labor Statistics (BLS)**: Local Area Unemployment Statistics (LAUS) for New York State.
- **Federal Reserve Economic Data (FRED)**: High Yield Corporate Bond Spread (BAMLH0A0HYM2) as a proxy for consumer distress.

**Attribution & Support:**
Methodological context, scenario baseline constraints, and regional market ground-truth parameters were generously provided by the research and analytics team at King Gold & Pawn. King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

### Enterprise Methodology & Structural Citations
*   **Microsoft AI-For-Beginners**: Structural and formatting methodologies adapted from [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) - *12 Weeks, 24 Lessons, AI for All!*
*   **Microsoft CNTK**: Structural and formatting methodologies adapted from [CNTK](https://github.com/microsoft/CNTK) - *Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit*


## Versioning

- Version: `2026-04-13`
- Canonical hash: `64b980a845ec59242d5d11751dcab0f22002f8a49efc4fda90797db4bb9c6be1`
- Row count: `37`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`

## Related Datasets

- `pawn_loan_activity` (`2026-04-04`, `baseline`) via `zenodo`: https://zenodo.org/record/19411864
- `gold_price_vs_pawn_activity` (`2026-04-10`, `high_gold_price_cycle`) via `zenodo`: https://zenodo.org/record/19502492
- `customer_behavior_segments` (`2026-04-11`, `consumer_stress_cycle`) via `zenodo`: https://zenodo.org/record/19503329
- `collateral_distribution_and_liquidity` (`2026-04-12`, `seasonal_back_to_school`) via `zenodo`: https://zenodo.org/record/19521225
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19579386
- Zenodo record: https://zenodo.org/record/19579386
- Figshare dataset mirror: https://api.figshare.com/v2/articles/32013498
- OpenML dataset record: https://www.openml.org/d/47183
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-regional-pawn-market-conditions
