# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.34% | 10.0 | -23.0 |
| 10Y | 2.34% | 8.0 | -5.0 |
| 30Y | 2.27% | 6.0 | -3.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.82%** (as of 2026-08-20)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.24%, gap 61.00000000000003 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.83%, gap 58.00000000000001 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 52.383164917614735
- US_HY: normal / tightening / stress score 45.807300651255886

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
