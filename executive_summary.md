# Expected CLV Consensus Dashboard - 2026-09-01

## Executive Read

- Consensus rows scored: 134
- Shadow watch candidates: 22
- Threshold: 0.36
- Training CLV rows: 428
- Refresh command: `venv/bin/python scripts/render_expected_clv_consensus_dashboard.py --consensus data/consensus/consensus_latest.csv --training-end-date 2026-06-29 --public-static`
- Output is advisory only; verify live price/line movement before any decision.

## Top CLV Thesis Candidates

- #1 Soccer BTTS - Both Teams to Score & Over 4.5 (0.3803 expected positive-CLV probability, clv_shadow_watch, KR Reykjavik vs Vikingur, TBD)
- #2 MLB Total - Over 7.5 (0.3784 expected positive-CLV probability, clv_shadow_watch, San Francisco Giants @ Pittsburgh Pirates, 18:40)
- #3 MLB Total - Under 7.5 (0.3755 expected positive-CLV probability, clv_shadow_watch, Seattle Mariners @ Boston Red Sox, 18:45)
- #4 MLB Total - Under 7.5 (0.373 expected positive-CLV probability, clv_shadow_watch, San Francisco Giants @ Pittsburgh Pirates, 18:40)
- #5 MLB Total - Under 7.5 (0.373 expected positive-CLV probability, clv_shadow_watch, New York Yankees @ Los Angeles Angels, 21:38)
- #6 MLB Total - Under 7.5 (0.3728 expected positive-CLV probability, clv_shadow_watch, Oakland Athletics @ Texas Rangers, 20:05)
- #7 MLB Prop - Michael McGreevey Over 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, St. Louis Cardinals @ Los Angeles Dodgers, 22:10)
- #8 MLB Prop - Robert Gasser Under 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Milwaukee Brewers @ Chicago Cubs, 19:40)
- #9 MLB Prop - Michael McGreevey (STL) Over 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, St. Louis Cardinals @ Los Angeles Dodgers, 22:10)
- #10 MLB Prop - Spencer Arrighetti Over 4.5 Hits Allowed (0.3603 expected positive-CLV probability, clv_shadow_watch, Toronto Blue Jays @ Cleveland Guardians, 18:40)
- #11 MLB Prop - Robert Gasser (MIL) Under 15.5 Outs (0.3603 expected positive-CLV probability, clv_shadow_watch, Milwaukee Brewers @ Chicago Cubs, 19:40)
- #12 MLB Prop - Spencer Arrighetti (TOR) Over 4.5 Hits Allowed (0.3603 expected positive-CLV probability, clv_shadow_watch, Toronto Blue Jays @ Cleveland Guardians, 18:40)

## Rules Of Use

- Treat this as a shadow decision aid, not an auto-bet list.
- Prefer candidates only when current odds still match or beat the listed entry and the market has not moved against the pick.
- Do not chase started/stale rows.
- If no candidate clears the threshold, the actionable decision is to pass or monitor.
