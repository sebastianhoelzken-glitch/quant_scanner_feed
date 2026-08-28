# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **59.03970751999593**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 81.25 | long | 1.18% | 3.00% | 0.23% |
| 2 | EURCHF | 79.00 | long | 0.46% | 0.56% | 2.72% |
| 3 | GBPJPY | 74.88 | long | 0.07% | -0.77% | 0.81% |
| 4 | GBPUSD | 69.25 | long | -0.33% | 1.44% | 0.87% |
| 5 | USDCHF | 63.83 | long | 0.77% | -0.90% | 2.73% |
| 6 | EURUSD | 57.62 | long | -0.31% | 1.47% | -0.01% |
| 7 | EURJPY | 55.00 | long | 0.09% | -0.74% | -0.07% |
| 8 | USDJPY | 49.29 | neutral | 0.40% | -2.18% | -0.06% |
| 9 | USDCAD | 47.33 | neutral | 0.72% | -1.26% | 0.29% |
| 10 | EURGBP | 35.04 | short | 0.02% | 0.03% | -0.87% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.920% | 49.44 | neutral | -6.0 |
| 2 | US30Y | 5.190% | 48.29 | neutral | -2.0 |
| 3 | US10Y_REAL | 2.340% | 47.64 | neutral | -7.0 |
| 4 | US2Y | 4.200% | 47.27 | neutral | -3.0 |
| 5 | US10Y | 4.670% | 47.08 | neutral | -1.0 |
| 6 | US5Y | 4.380% | 46.40 | neutral | 0.0 |
| 7 | US3M | 3.840% | 46.04 | neutral | 2.0 |
| 8 | US5Y_REAL | 2.070% | 43.08 | bearish_duration | -7.0 |
| 9 | DE2Y | 2.850% | 42.71 | bearish_duration | 5.0 |
| 10 | DE5Y | 2.970% | 42.13 | bearish_duration | 5.0 |
| 11 | DE10Y | 3.250% | 40.46 | bearish_duration | 7.0 |
| 12 | DE30Y | 3.750% | 39.34 | bearish_duration | 8.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 47.0 | 2.0 |
| US_5s30s | 81.0 | -2.0 |
| US_3m10y | 83.0 | -3.0 |
| DE_2s10s | 40.0 | 2.0 |
| US_DE_2Y | 135.0 | -8.0 |
| US_DE_10Y | 142.0 | -8.0 |

## Provider status

```json
{
  "ecb_USD": {
    "status": "ok",
    "rows": 302
  },
  "ecb_GBP": {
    "status": "ok",
    "rows": 302
  },
  "ecb_JPY": {
    "status": "ok",
    "rows": 302
  },
  "ecb_CHF": {
    "status": "ok",
    "rows": 302
  },
  "ecb_AUD": {
    "status": "ok",
    "rows": 302
  },
  "ecb_CAD": {
    "status": "ok",
    "rows": 302
  },
  "us_treasury_nominal": {
    "status": "ok",
    "source": "US Treasury official XML year feed",
    "series": [
      "US10Y",
      "US2Y",
      "US30Y",
      "US3M",
      "US5Y"
    ]
  },
  "us_treasury_real": {
    "status": "ok",
    "source": "US Treasury official XML year feed",
    "series": [
      "US10Y_REAL",
      "US30Y_REAL",
      "US5Y_REAL"
    ]
  },
  "bundesbank_DE2Y": {
    "status": "ok",
    "rows": 300
  },
  "bundesbank_DE5Y": {
    "status": "ok",
    "rows": 300
  },
  "bundesbank_DE10Y": {
    "status": "ok",
    "rows": 300
  },
  "bundesbank_DE30Y": {
    "status": "ok",
    "rows": 300
  }
}
```
