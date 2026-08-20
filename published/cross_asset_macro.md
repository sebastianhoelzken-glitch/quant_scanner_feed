# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.28% | -2.0 | -38.0 |
| 10Y | 2.30% | 2.0 | -19.0 |
| 30Y | 2.25% | 3.0 | -9.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.87%** (as of 2026-08-18)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.19%, gap 56.00000000000005 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.85%, gap 60.00000000000001 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: stressed / tightening / stress score 70.75427807709542
- US_HY: normal / stable / stress score 52.30351564332493

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
