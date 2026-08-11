# Expected CLV Consensus Dashboard - 2026-08-10

## Executive Read

- Consensus rows scored: 144
- Shadow watch candidates: 4
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 8.5 (0.373 expected positive-CLV probability, clv_shadow_watch, HOU vs SF, 20:45)
- #2 MLB Total - Over 9.5 (0.373 expected positive-CLV probability, clv_shadow_watch, Tampa Bay Rays @ Oakland Athletics, 21:40)
- #3 MLB Total - Under 7 (0.3728 expected positive-CLV probability, clv_shadow_watch, Milwaukee Brewers @ San Diego Padres, 21:40)
- #4 MLB Total - Over 10 (0.3726 expected positive-CLV probability, clv_shadow_watch, Tampa Bay Rays @ Oakland Athletics, 21:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
