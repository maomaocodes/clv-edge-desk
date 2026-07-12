# Expected CLV Consensus Dashboard - 2026-07-12

## Executive Read

- Consensus rows scored: 126
- Shadow watch candidates: 3
- Threshold: 0.36
- Training CLV rows: 419
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Soccer BTTS - Both Teams to Score & Over 2.5 Goals (0.3902 expected positive-CLV probability, clv_shadow_watch, Brann vs Start, TBD)
- #2 MLB Prop - Trevor McDonald Over 4.5 Strikeouts (0.3618 expected positive-CLV probability, clv_shadow_watch, Colorado Rockies @ San Francisco Giants, 16:05)
- #3 MLB Prop - Emmet Sheehan Under 5.5 Strikeouts (0.3618 expected positive-CLV probability, clv_shadow_watch, Arizona Diamondbacks @ Los Angeles Dodgers, 16:10)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
