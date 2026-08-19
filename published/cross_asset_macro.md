# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.27% | -1.0 | -42.0 |
| 10Y | 2.30% | 4.0 | -18.0 |
| 30Y | 2.25% | 3.0 | -7.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.89%** (as of 2026-08-17)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.19%, gap 56.00000000000005 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.85%, gap 60.00000000000001 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 63.59683338219867
- US_HY: normal / widening / stress score 56.20802060126664

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
