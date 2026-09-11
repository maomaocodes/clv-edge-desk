# Expected CLV Consensus Dashboard - 2026-09-11

## Executive Read

- Consensus rows scored: 88
- Shadow watch candidates: 4
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 MLB Prop - Cade Cavalli Over 4.5 strikeouts (0.3698 expected positive-CLV probability, clv_shadow_watch, Los Angeles Angels @ Washington Nationals, 18:45)
- #2 MLB Prop - Drake Baldwin Over 0.5 Hits+Runs+RBI (0.3698 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Atlanta Braves, 19:15)
- #3 MLB Prop - Taj Bradley Over 3.5 strikeouts (0.3698 expected positive-CLV probability, clv_shadow_watch, Cleveland Guardians @ Minnesota Twins, 20:10)
- #4 MLB Total - Under 7.5 (0.3666 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Atlanta Braves, 19:15)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
