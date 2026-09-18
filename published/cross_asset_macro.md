# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.32% | 4.0 | 1.0 |
| 10Y | 2.33% | 3.0 | 7.0 |
| 30Y | 2.25% | -0.0 | 5.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.71%** (as of 2026-09-15)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.67%, gap 104.0 bp -> **tightening** bias.
ECB: deposit 2.5%, DE2Y 3.26%, gap 75.99999999999997 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: benign / tightening / stress score 28.536953148065002
- US_HY: normal / tightening / stress score 41.24257372455024

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
