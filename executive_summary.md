# Expected CLV Consensus Dashboard - 2026-07-31

## Executive Read

- Consensus rows scored: 227
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 425
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Prop - Paul Skenes Over 7.5 Strikeouts (0.3909 expected positive-CLV probability, clv_shadow_watch, Pittsburgh Pirates @ Cincinnati Reds, 18:10)
- #2 MLB Total - Under 8.5 (0.3761 expected positive-CLV probability, clv_shadow_watch, Minnesota Twins @ Seattle Mariners, 22:10)
- #3 MLB Total - Under 7.5 (0.3695 expected positive-CLV probability, clv_shadow_watch, St. Louis Cardinals @ Toronto Blue Jays, 19:07)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
