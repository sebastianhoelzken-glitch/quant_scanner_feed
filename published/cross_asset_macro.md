# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.24% | -3.0 | -43.0 |
| 10Y | 2.27% | 3.0 | -20.0 |
| 30Y | 2.25% | 6.0 | -4.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.80%** (as of 2026-08-13)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.17%, gap 54.0 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.78%, gap 52.99999999999998 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 62.468543000250044
- US_HY: normal / tightening / stress score 45.885466826779115

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
