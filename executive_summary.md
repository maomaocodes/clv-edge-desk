# Expected CLV Consensus Dashboard - 2026-08-19

## Executive Read

- Consensus rows scored: 214
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Champions League BTTS - Both Teams to Score & Over 3.5 Goals (0.3803 expected positive-CLV probability, clv_shadow_watch, NEC vs Bodo/Glimt, TBD)
- #2 Champions League BTTS - Both Teams to Score & Over 3.5 (0.3803 expected positive-CLV probability, clv_shadow_watch, NEC vs Bodo/Glimt, TBD)
- #3 MLB Prop - Shohei Ohtani Over 0.5 HR (0.3698 expected positive-CLV probability, clv_shadow_watch, Los Angeles Dodgers @ Colorado Rockies, 20:40)
- #4 MLB Total - Under 7.5 (0.3605 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Milwaukee Brewers, 19:40)
- #5 MLB Prop - Logan Gilbert Under 6.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Milwaukee Brewers, 19:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
