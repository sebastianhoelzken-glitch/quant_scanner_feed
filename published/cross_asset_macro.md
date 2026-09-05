# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.37% | 15.0 | -11.0 |
| 10Y | 2.35% | 10.0 | -1.0 |
| 30Y | 2.28% | 5.0 | 1.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.72%** (as of 2026-09-02)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.37%, gap 74.00000000000003 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.96%, gap 71.0 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 52.03984138772989
- US_HY: normal / tightening / stress score 48.398890982503104

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
