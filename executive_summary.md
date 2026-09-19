# Expected CLV Consensus Dashboard - 2026-09-18

## Executive Read

- Consensus rows scored: 126
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Prop - Tyler Glasnow Over 16.5 Pitch Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, San Francisco Giants @ Los Angeles Dodgers, 22:15)
- #2 MLB Prop - Gerrit Cole Over 15.5 Pitch Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Arizona Diamondbacks, 21:40)
- #3 MLB Prop - Connor Prielipp Over 14.5 Pitch Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Minnesota Twins @ Los Angeles Angels, 21:38)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
