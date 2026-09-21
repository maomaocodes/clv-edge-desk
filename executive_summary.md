# Expected CLV Consensus Dashboard - 2026-09-21

## Executive Read

- Consensus rows scored: 76
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 NFL Prop - Davante Adams Anytime Touchdown Scorer (0.3768 expected positive-CLV probability, clv_shadow_watch, New York Giants @ Los Angeles Rams, 20:15)
- #2 NFL Total - Over 47.5 (0.3636 expected positive-CLV probability, clv_shadow_watch, New York Giants @ Los Angeles Rams, 20:15)
- #3 NFL Total - Under 48 (0.3632 expected positive-CLV probability, clv_shadow_watch, New York Giants @ Los Angeles Rams, 20:15)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
