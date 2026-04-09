# pawn_loan_activity

Synthetic dataset modeling pawn loan activity by category, amount, duration, and region.

Full dataset index: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/README.md

## Latest Version

- Version: `2026-04-09`
- Scenario: `baseline`
- Row count: `13675`
- Realism score: `1.0`
- Summary: Synthetic pawn loan records tie collateral mix, loan sizing, durations, and repayment behavior together across New York regions. This build contains 13,675 rows under the baseline scenario.

## Key Observations

- Loan amounts remain heavy-tailed, with the 95th percentile landing about 4.90x the median ticket size.
- Repeat customers default at 4.3% versus 5.3% for non-repeat borrowers.
- Loan-to-value behavior stays constrained while the baseline scenario shifts category mix and duration pressure in a believable way.

## Available Versions

- `2026-04-09` | `baseline` | GitHub: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/datasets/pawn_loan_activity/2026-04-09/README.md
- `2026-04-09_test1` | `baseline` | GitHub: pending
- `2026-04-08` | `baseline` | GitHub: pending
- `refchecker_test_01` | `baseline` | GitHub: pending
- `2026-04-04` | `baseline` | GitHub: https://github.com/empirgold-ctrl/pawn-datasets-research/blob/main/datasets/pawn_loan_activity/2026-04-04/README.md
