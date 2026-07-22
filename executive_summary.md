# Expected CLV Consensus Dashboard - 2026-07-22

## Executive Read

- Consensus rows scored: 119
- Shadow watch candidates: 5
- Threshold: 0.36
- Training CLV rows: 419
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Prop - William Contreras HR (0.3795 expected positive-CLV probability, clv_shadow_watch, New York Mets @ Milwaukee Brewers, 14:10)
- #2 MLB Prop - Esmerlyn Valdez HR (0.3795 expected positive-CLV probability, clv_shadow_watch, Pittsburgh Pirates @ New York Yankees, 13:05)
- #3 MLB Prop - Ben Rice HR (0.3795 expected positive-CLV probability, clv_shadow_watch, Pittsburgh Pirates @ New York Yankees, 13:05)
- #4 MLB Total - Over 11.5 (0.3713 expected positive-CLV probability, clv_shadow_watch, Washington Nationals @ Colorado Rockies, 15:10)
- #5 MLB Total - Under 7.5 (0.3643 expected positive-CLV probability, clv_shadow_watch, New York Mets @ Milwaukee Brewers, 14:10)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
