# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.40% | 15.0 | -7.0 |
| 10Y | 2.37% | 8.0 | 2.0 |
| 30Y | 2.29% | 4.0 | 3.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.68%** (as of 2026-09-04)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.39%, gap 75.99999999999997 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 3.01%, gap 75.99999999999997 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 47.01406247814117
- US_HY: normal / stable / stress score 49.572475953370244

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
