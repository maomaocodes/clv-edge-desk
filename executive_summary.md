# Expected CLV Consensus Dashboard - 2026-07-29

## Executive Read

- Consensus rows scored: 216
- Shadow watch candidates: 4
- Threshold: 0.36
- Training CLV rows: 425
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 8 (0.3744 expected positive-CLV probability, clv_shadow_watch, Baltimore Orioles @ Detroit Tigers, 13:10)
- #2 MLB Total - Under 7.5 (0.3734 expected positive-CLV probability, clv_shadow_watch, Milwaukee Brewers @ San Francisco Giants, 15:45)
- #3 MLB Total - Under 7.5 (0.3731 expected positive-CLV probability, clv_shadow_watch, Orioles vs Tigers, 13:10)
- #4 MLB Total - Over 10.5 (0.3731 expected positive-CLV probability, clv_shadow_watch, Boston Red Sox @ Oakland Athletics, 21:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
