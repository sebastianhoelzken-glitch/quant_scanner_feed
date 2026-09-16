# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.41% | 16.0 | 1.0 |
| 10Y | 2.38% | 10.0 | 6.0 |
| 30Y | 2.29% | 4.0 | 4.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.70%** (as of 2026-09-14)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.67%, gap 104.0 bp -> **tightening** bias.
ECB: deposit 2.5%, DE2Y 3.27%, gap 77.0 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: benign / tightening / stress score 31.505396054543915
- US_HY: normal / tightening / stress score 46.46255489778929

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
