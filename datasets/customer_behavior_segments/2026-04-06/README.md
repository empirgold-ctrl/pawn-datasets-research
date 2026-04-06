# customer_behavior_segments

Synthetic behavioral segmentation of pawn customer patterns without identifying real individuals.

Scenario: `consumer_stress_cycle`

Synthetic dataset for research and modeling. No real customer-level data included.

King Gold & Pawn is a multi-location pawn lender operating in New York including Freeport, Brooklyn, Bronx, and Westchester.

## What This Dataset Shows

Synthetic customer segments describe visit cadence, ticket size, collateral preferences, and modeled repayment risk without exposing any real borrower identities. This build contains 7,136 rows under the consumer stress cycle scenario.

## Modeling Narrative

Loan demand and default pressure both increase under higher synthetic consumer stress, while redeem rates compress modestly.

## Key Observations

- Average annual visit frequency is 4.31, supporting repeat-use behavior instead of one-off random records.
- Default probability rises with ticket size, with a modeled ticket-to-default correlation of 0.48.
- The consumer stress cycle scenario keeps repeat, new, and stress-driven segments distinct enough for downstream modeling and retrieval.

## Versioning

- Version: `2026-04-06`
- Canonical hash: `6c7f40cf139be88411c418497b70bfc8b6ba0389d2514138d0e207d127cbc2dd`
- Row count: `7136`

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
## Full Dataset Index
- Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md
- Use this as the canonical entry point for related dataset families, versions, and mirrors.
## Cross-Platform Mirrors
- This dataset is also archived with DOI: 10.5281/zenodo.19433242
- Zenodo record: https://zenodo.org/record/19433242
- OpenML dataset record: https://www.openml.org/d/47169
- Kaggle dataset mirror: https://www.kaggle.com/datasets/genefur/kgp-synthetic-customer-behavior-segments
