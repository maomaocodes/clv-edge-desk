# Expected CLV Consensus Dashboard - 2026-07-26

## Executive Read

- Consensus rows scored: 150
- Shadow watch candidates: 7
- Threshold: 0.36
- Training CLV rows: 420
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Over 8.5 (0.3682 expected positive-CLV probability, clv_shadow_watch, Atlanta Braves @ Baltimore Orioles, 13:35)
- #2 MLB Total - Over 8 (0.368 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Philadelphia Phillies, 19:20)
- #3 MLB Total - Under 7.5 (0.3674 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Texas Rangers, 14:35)
- #4 MLB Total - Over 10 (0.3654 expected positive-CLV probability, clv_shadow_watch, Oakland Athletics @ Minnesota Twins, 14:10)
- #5 MLB Total - Under 8.5 (0.3654 expected positive-CLV probability, clv_shadow_watch, Cincinnati Reds @ St. Louis Cardinals, 14:15)
- #6 MLB Total - Under 8.5 (0.3654 expected positive-CLV probability, clv_shadow_watch, Los Angeles Angels @ San Francisco Giants, 16:05)
- #7 MLB Total - Under 9 (0.3651 expected positive-CLV probability, clv_shadow_watch, Los Angeles Dodgers @ New York Mets, 13:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
