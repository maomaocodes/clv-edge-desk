# Expected CLV Consensus Dashboard - 2026-08-28

## Executive Read

- Consensus rows scored: 280
- Shadow watch candidates: 6
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 8 (0.3759 expected positive-CLV probability, clv_shadow_watch, LA vs Detroit, TBD)
- #2 MLB Total - Over 8 (0.3758 expected positive-CLV probability, clv_shadow_watch, Chicago White Sox @ Minnesota Twins, 20:10)
- #3 MLB Prop - Luis Castillo Under 5.5 Hits Allowed (0.3712 expected positive-CLV probability, clv_shadow_watch, Chicago White Sox @ Minnesota Twins, 20:10)
- #4 MLB Total - Over 8.5 (0.3675 expected positive-CLV probability, clv_shadow_watch, Chicago White Sox @ Minnesota Twins, 20:10)
- #5 MLB Prop - Reid Detmers Under 6.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Los Angeles Angels, 21:38)
- #6 MLB Prop - Quinn Matthews Over 5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Chicago White Sox @ Minnesota Twins, 20:10)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
