# Expected CLV Consensus Dashboard - 2026-07-30

## Executive Read

- Consensus rows scored: 209
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 425
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Total - Under 7 (0.3736 expected positive-CLV probability, clv_shadow_watch, Miami Marlins @ New York Mets, 19:10)
- #2 MLB Total - Under 10 (0.3735 expected positive-CLV probability, clv_shadow_watch, Boston Red Sox @ Oakland Athletics, 21:40)
- #3 Tennis Total - Over 21 (0.3645 expected positive-CLV probability, clv_shadow_watch, Anastasia Potapova vs Diana Shnaider, 18:00)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
