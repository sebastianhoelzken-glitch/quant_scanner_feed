# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.37% | 18.0 | -15.0 |
| 10Y | 2.35% | 12.0 | -4.0 |
| 30Y | 2.29% | 7.0 | 1.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.73%** (as of 2026-08-28)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.39%, gap 75.99999999999997 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.97%, gap 72.00000000000001 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 53.13073811383263
- US_HY: normal / tightening / stress score 46.09626822988195

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
