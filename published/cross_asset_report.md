# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **58.799843704022905**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | GBPUSD | 79.38 | long | 0.55% | 2.38% | 1.48% |
| 2 | AUDUSD | 79.00 | long | 0.51% | 2.31% | 0.44% |
| 3 | EURCHF | 78.62 | long | -0.29% | 0.84% | 2.28% |
| 4 | GBPJPY | 76.38 | long | 0.49% | -0.44% | 1.29% |
| 5 | EURUSD | 71.12 | long | 0.61% | 2.41% | 0.23% |
| 6 | EURJPY | 63.62 | long | 0.55% | -0.41% | 0.04% |
| 7 | USDCHF | 52.21 | neutral | -0.89% | -1.54% | 2.05% |
| 8 | USDJPY | 36.08 | short | -0.06% | -2.76% | -0.19% |
| 9 | USDCAD | 22.88 | short | -0.07% | -1.81% | 0.11% |
| 10 | EURGBP | 19.88 | short | 0.06% | 0.03% | -1.23% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US10Y_REAL | 2.380% | 50.90 | neutral | -6.0 |
| 2 | US3M | 3.870% | 50.45 | neutral | -9.0 |
| 3 | US5Y_REAL | 2.090% | 50.35 | neutral | -13.0 |
| 4 | US2Y | 4.240% | 49.16 | neutral | -7.0 |
| 5 | US30Y_REAL | 2.970% | 48.41 | neutral | 2.0 |
| 6 | US5Y | 4.410% | 46.21 | neutral | 1.0 |
| 7 | US10Y | 4.700% | 46.04 | neutral | 5.0 |
| 8 | US30Y | 5.230% | 44.86 | bearish_duration | 11.0 |
| 9 | DE2Y | 2.840% | 39.98 | bearish_duration | 5.0 |
| 10 | DE5Y | 2.970% | 36.65 | bearish_duration | 9.0 |
| 11 | DE10Y | 3.240% | 35.82 | bearish_duration | 11.0 |
| 12 | DE30Y | 3.750% | 33.54 | bearish_duration | 13.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 46.0 | 12.0 |
| US_5s30s | 82.0 | 10.0 |
| US_3m10y | 83.0 | 14.0 |
| DE_2s10s | 40.0 | 6.0 |
| US_DE_2Y | 140.0 | -12.0 |
| US_DE_10Y | 146.0 | -6.0 |

## Provider status

```json
{
  "ecb_USD": {
    "status": "ok",
    "rows": 300
  },
  "ecb_GBP": {
    "status": "ok",
    "rows": 300
  },
  "ecb_JPY": {
    "status": "ok",
    "rows": 300
  },
  "ecb_CHF": {
    "status": "ok",
    "rows": 300
  },
  "ecb_AUD": {
    "status": "ok",
    "rows": 300
  },
  "ecb_CAD": {
    "status": "ok",
    "rows": 300
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
    "rows": 298
  },
  "bundesbank_DE5Y": {
    "status": "ok",
    "rows": 298
  },
  "bundesbank_DE10Y": {
    "status": "ok",
    "rows": 298
  },
  "bundesbank_DE30Y": {
    "status": "ok",
    "rows": 298
  }
}
```
