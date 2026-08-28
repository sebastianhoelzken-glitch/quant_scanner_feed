# Cross-Asset Macro Decomposition

Status: **complete**

## Breakeven inflation

| Tenor | Level | 20d bp | 63d bp |
|---:|---:|---:|---:|
| 5Y | 2.31% | 7.0 | -23.0 |
| 10Y | 2.33% | 6.0 | -6.0 |
| 30Y | 2.27% | 4.0 | -1.0 |

## NY Fed ACM term premium

10Y ACM term premium: **0.75%** (as of 2026-08-26)

## Policy-path proxies

Fed: EFFR 3.63%, US2Y 4.2%, gap 57.00000000000003 bp -> **tightening** bias.
ECB: deposit 2.25%, DE2Y 2.85%, gap 60.00000000000001 bp -> **tightening** bias.

These are sovereign front-end proxies, not meeting-by-meeting OIS/futures probabilities.

## Credit stress

- US_IG: normal / tightening / stress score 44.31801330142982
- US_HY: normal / tightening / stress score 43.625942193167305

Credit stress uses transparent liquid-market ETF relative-performance proxies; it is not OAS and no proprietary OAS level is redistributed.

## Interpretation guardrail

All forward-looking statements are conditional diagnostics, not point forecasts. Real yields, inflation compensation, term premium, policy expectations and credit stress can move for overlapping reasons and are not treated as independent causal variables.
