# Expected CLV Consensus Dashboard - 2026-08-03

## Executive Read

- Consensus rows scored: 166
- Shadow watch candidates: 4
- Threshold: 0.36
- Training CLV rows: 425
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Soccer Prop - Mladost Under 0.5 Team Goals (0.3853 expected positive-CLV probability, clv_shadow_watch, Železničar vs Mladost, TBD)
- #2 MLB Total - Over 9 (0.3761 expected positive-CLV probability, clv_shadow_watch, Washington Nationals @ Philadelphia Phillies, 18:40)
- #3 MLB Total - Under 9 (0.3695 expected positive-CLV probability, clv_shadow_watch, Toronto Blue Jays @ Houston Astros, 20:10)
- #4 MLB Total - Under 11.5 (0.3686 expected positive-CLV probability, clv_shadow_watch, Tampa Bay Rays @ Colorado Rockies, 20:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
