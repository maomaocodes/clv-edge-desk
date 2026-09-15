# Expected CLV Consensus Dashboard - 2026-09-15

## Executive Read

- Consensus rows scored: 109
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Over 11.5 (0.3726 expected positive-CLV probability, clv_shadow_watch, San Diego Padres @ Colorado Rockies, 20:40)
- #2 MLB Prop - Ryan Johnson (LAA) Under 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Los Angeles Angels, 21:38)
- #3 MLB Prop - Patrick Sandoval (BOS) Under 16.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Boston Red Sox @ Texas Rangers, 20:05)
- #4 MLB Prop - Martin Perez (ATL) Under 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Atlanta Braves @ Chicago Cubs, 19:40)
- #5 MLB Prop - Kevin Gausman (CHC) Over 17.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Atlanta Braves @ Chicago Cubs, 19:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
