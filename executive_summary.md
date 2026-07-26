# Expected CLV Consensus Dashboard - 2026-07-26

## Executive Read

- Consensus rows scored: 99
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 420
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Over 10 (0.3714 expected positive-CLV probability, clv_shadow_watch, Arizona Diamondbacks @ Washington Nationals, 13:35)
- #2 MLB Total - Over 8.5 (0.3654 expected positive-CLV probability, clv_shadow_watch, Atlanta Braves @ Baltimore Orioles, 13:35)
- #3 MLB Total - Under 8.5 (0.3654 expected positive-CLV probability, clv_shadow_watch, Los Angeles Angels @ San Francisco Giants, 16:05)
- #4 MLB Total - Under 8.5 (0.3654 expected positive-CLV probability, clv_shadow_watch, Cincinnati Reds @ St. Louis Cardinals, 14:15)
- #5 MLB Total - Under 7.5 (0.3648 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Texas Rangers, 14:35)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
