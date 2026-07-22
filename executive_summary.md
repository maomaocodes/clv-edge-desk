# Expected CLV Consensus Dashboard - 2026-07-21

## Executive Read

- Consensus rows scored: 149
- Shadow watch candidates: 4
- Threshold: 0.36
- Training CLV rows: 419
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Soccer Total - Over 3 (0.3693 expected positive-CLV probability, clv_shadow_watch, FC Thun vs Dinamo Zagreb, TBD)
- #2 MLB Total - Over 9.5 (0.3645 expected positive-CLV probability, clv_shadow_watch, Oakland Athletics @ Arizona Diamondbacks, 21:40)
- #3 MLB Total - Over 12.5 (0.3643 expected positive-CLV probability, clv_shadow_watch, Washington Nationals @ Colorado Rockies, 20:40)
- #4 MLB Total - Under 9.5 (0.364 expected positive-CLV probability, clv_shadow_watch, Oakland Athletics @ Arizona Diamondbacks, 21:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
