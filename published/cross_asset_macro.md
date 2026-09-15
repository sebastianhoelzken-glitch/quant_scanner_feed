# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.40% | 16.0 | 1.0 |
| 10Y | 2.37% | 10.0 | 6.0 |
| 30Y | 2.29% | 4.0 | 5.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.72%** (as of 2026-09-11)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.65%, gap 102.00000000000004 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 3.25%, gap 100.0 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 38.240973271441426
- US_HY: normal / stable / stress score 45.47097505471254

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
