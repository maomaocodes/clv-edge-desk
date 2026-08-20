# Expected CLV Consensus Dashboard - 2026-08-20

## Executive Read

- Consensus rows scored: 130
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 7.5 (0.3728 expected positive-CLV probability, clv_shadow_watch, Nationals vs Rangers, TBD)
- #2 MLB Prop - Peter Lambert Over 5.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Los Angeles Angels @ Houston Astros, 20:10)
- #3 MLB Prop - Gage Jump Over 4.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Oakland Athletics @ Kansas City Royals, 14:10)
- #4 MLB Prop - Grant Holmes Over 4.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Atlanta Braves @ Chicago White Sox, 14:10)
- #5 MLB Prop - Gerrit Cole Under 4.5 Hits Allowed (0.3603 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Baltimore Orioles, 18:35)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
