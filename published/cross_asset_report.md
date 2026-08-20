# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **57.11912544812481**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 86.88 | long | 0.38% | 1.45% | 3.10% |
| 2 | GBPUSD | 75.25 | long | 0.23% | 1.41% | 1.03% |
| 3 | GBPJPY | 73.75 | long | 0.22% | -1.07% | 1.00% |
| 4 | USDCHF | 68.42 | long | -0.13% | -0.28% | 3.01% |
| 5 | AUDUSD | 61.38 | long | 0.07% | 1.17% | -0.63% |
| 6 | EURUSD | 60.54 | long | 0.52% | 1.73% | 0.09% |
| 7 | EURJPY | 56.79 | long | 0.52% | -0.76% | 0.05% |
| 8 | USDJPY | 38.71 | short | -0.00% | -2.44% | -0.04% |
| 9 | USDCAD | 36.08 | short | -0.39% | -1.53% | 0.51% |
| 10 | EURGBP | 29.71 | short | 0.29% | 0.31% | -0.94% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.190% | 53.69 | neutral | -12.0 |
| 2 | US5Y | 4.350% | 52.76 | neutral | -6.0 |
| 3 | US10Y | 4.650% | 52.30 | neutral | -2.0 |
| 4 | US10Y_REAL | 2.350% | 51.45 | neutral | -4.0 |
| 5 | US30Y | 5.190% | 50.00 | neutral | 4.0 |
| 6 | US30Y_REAL | 2.940% | 49.46 | neutral | 1.0 |
| 7 | US3M | 3.860% | 47.05 | neutral | -3.0 |
| 8 | US5Y_REAL | 2.070% | 46.55 | neutral | -4.0 |
| 9 | DE2Y | 2.850% | 42.06 | bearish_duration | 4.0 |
| 10 | DE5Y | 2.980% | 38.66 | bearish_duration | 6.0 |
| 11 | DE10Y | 3.260% | 37.07 | bearish_duration | 9.0 |
| 12 | DE30Y | 3.780% | 30.65 | bearish_duration | 12.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 46.0 | 10.0 |
| US_5s30s | 84.0 | 10.0 |
| US_3m10y | 79.0 | 1.0 |
| DE_2s10s | 41.0 | 5.0 |
| US_DE_2Y | 134.0 | -16.0 |
| US_DE_10Y | 139.0 | -11.0 |

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
