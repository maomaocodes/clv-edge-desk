# Expected CLV Consensus Dashboard - 2026-08-31

## Executive Read

- Consensus rows scored: 252
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 8.5 (0.3755 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Arizona Diamondbacks, 21:40)
- #2 MLB Total - Under 8.5 (0.373 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Los Angeles Angels, 21:38)
- #3 MLB Total - Over 8.5 (0.373 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Arizona Diamondbacks, 21:40)
- #4 MLB Prop - Elmer Rodríguez Under 4.5 Hits Allowed (0.3603 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Los Angeles Angels, 21:38)
- #5 MLB Prop - Aaron Nola Under 17.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Arizona Diamondbacks, 21:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
