# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.30% | 4.0 | -22.0 |
| 10Y | 2.31% | 3.0 | -7.0 |
| 30Y | 2.26% | 2.0 | -2.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.75%** (as of 2026-08-26)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.34%, gap 71.0 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.86%, gap 60.999999999999986 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 46.16247554260354
- US_HY: normal / tightening / stress score 42.93679601136543

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
