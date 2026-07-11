# Expected CLV Consensus Dashboard - 2026-07-10

## Executive Read

- Consensus rows scored: 204
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 419
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Prop - Eduardo Rodriguez Under 4.5 Strikeouts (0.3873 expected positive-CLV probability, clv_shadow_watch, Arizona Diamondbacks @ Los Angeles Dodgers, 22:10)
- #2 MLB Total - Under 8.5 (0.3643 expected positive-CLV probability, clv_shadow_watch, Arizona Diamondbacks @ Los Angeles Dodgers, 22:10)
- #3 Soccer Prop - Lamine Yamal 2+ Shots On Goal (0.3603 expected positive-CLV probability, clv_shadow_watch, Lamine Yamal, TBD)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
