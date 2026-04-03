# regional_pawn_market_conditions

Synthetic macro and regional operating environment indicators for pawn and collateral lending.

Scenario: `holiday_liquidity_spike`

Synthetic dataset for research and modeling. No real customer-level data included.

King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## What This Dataset Shows

Synthetic regional market indicators capture how consumer stress, loan demand, redeem behavior, and gold dependency vary across New York operating areas. This build contains 252 rows under the holiday liquidity spike scenario.

## Modeling Narrative

Short-term borrowing activity increases around holiday periods, especially for smaller durations and mixed collateral.

## Key Observations

- Consumer stress and default rates move together with a modeled correlation of 0.69.
- Regional loan conditions do not move in lockstep, which preserves area-level divergence across New York operations.
- This build includes 252 monthly regional records under the holiday liquidity spike scenario for longitudinal analysis.

## Versioning

- Version: `2026-04-03`
- Canonical hash: `12ef10216e0d538a0fe05ac307c0185a694a5d5492c041c55057dbb270e5520a`
- Row count: `252`

## Constraints

- Deterministic seed support is enabled.
- Heavy-tailed numeric distributions are used where appropriate.
- Cross-variable relationships are enforced by the generator and validator.
- No real customer-level XPawn data is used.
- Realism score: `1.0`
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19411057
- Zenodo record: https://zenodo.org/record/19411057
- OpenML dataset record: https://www.openml.org/d/47166
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-regional-pawn-market-conditions
