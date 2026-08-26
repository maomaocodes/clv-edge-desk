# Expected CLV Consensus Dashboard - 2026-08-25

## Executive Read

- Consensus rows scored: 243
- Shadow watch candidates: 9
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Champions League BTTS - Both Teams to Score and Over 3.5 (0.3803 expected positive-CLV probability, clv_shadow_watch, Bodo Glimt vs NEC Nijmegen, TBD)
- #2 MLB Total - Over 8 (0.3755 expected positive-CLV probability, clv_shadow_watch, Cincinnati Reds @ San Francisco Giants, 21:45)
- #3 MLB Total - Under 7.5 (0.373 expected positive-CLV probability, clv_shadow_watch, Cleveland Guardians @ Los Angeles Angels, 21:38)
- #4 MLB Total - Over 9.5 (0.3726 expected positive-CLV probability, clv_shadow_watch, Minnesota Twins @ Oakland Athletics, 21:40)
- #5 MLB Prop - Gavin Williams Over 7.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Cleveland Guardians @ Los Angeles Angels, 21:38)
- #6 MLB Prop - Aaron Nola Under 5.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Philadelphia Phillies @ Seattle Mariners, 21:40)
- #7 MLB Prop - Walbert Urena Over 4.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Cleveland Guardians @ Los Angeles Angels, 21:38)
- #8 MLB Prop - Brandon Pfaadt Under 4.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Chicago Cubs @ Arizona Diamondbacks, 21:40)
- #9 MLB Prop - Adrian Houser Over 3.5 Strikeouts (0.3603 expected positive-CLV probability, clv_shadow_watch, Cincinnati Reds @ San Francisco Giants, 21:45)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
