# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.41% | 18.0 | -3.0 |
| 10Y | 2.37% | 10.0 | 4.0 |
| 30Y | 2.30% | 6.0 | 4.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.76%** (as of 2026-09-08)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.43%, gap 79.99999999999999 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 3.03%, gap 77.99999999999999 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 41.99737596208133
- US_HY: normal / tightening / stress score 48.76083082650373

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
