# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **59.05087995396937**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 77.88 | long | -0.39% | 0.55% | 2.38% |
| 1 | GBPJPY | 77.88 | long | 0.68% | -0.71% | 1.06% |
| 3 | AUDUSD | 77.12 | long | 1.22% | 2.58% | 0.03% |
| 4 | GBPUSD | 76.00 | long | 0.88% | 2.49% | 1.39% |
| 5 | EURUSD | 72.62 | long | 1.14% | 2.83% | 0.56% |
| 6 | EURJPY | 69.62 | long | 0.94% | -0.39% | 0.24% |
| 7 | USDCHF | 51.83 | neutral | -1.52% | -2.22% | 1.81% |
| 8 | USDJPY | 39.83 | short | -0.20% | -3.13% | -0.32% |
| 9 | EURGBP | 28.21 | short | 0.26% | 0.33% | -0.82% |
| 10 | USDCAD | 16.50 | short | -0.97% | -2.46% | -0.52% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.240% | 48.44 | neutral | -9.0 |
| 2 | US3M | 3.880% | 48.29 | neutral | -8.0 |
| 3 | US5Y_REAL | 2.090% | 47.62 | neutral | -10.0 |
| 4 | US10Y_REAL | 2.400% | 46.93 | neutral | -3.0 |
| 5 | US5Y | 4.430% | 44.54 | bearish_duration | 0.0 |
| 6 | DE2Y | 2.830% | 43.26 | bearish_duration | -1.0 |
| 7 | US10Y | 4.740% | 42.42 | bearish_duration | 5.0 |
| 8 | US30Y_REAL | 3.000% | 42.08 | bearish_duration | 5.0 |
| 9 | US30Y | 5.270% | 40.43 | bearish_duration | 11.0 |
| 10 | DE5Y | 2.960% | 40.08 | bearish_duration | 1.0 |
| 11 | DE10Y | 3.240% | 37.09 | bearish_duration | 6.0 |
| 12 | DE30Y | 3.760% | 32.39 | bearish_duration | 10.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 50.0 | 14.0 |
| US_5s30s | 84.0 | 11.0 |
| US_3m10y | 86.0 | 13.0 |
| DE_2s10s | 41.0 | 7.0 |
| US_DE_2Y | 141.0 | -8.0 |
| US_DE_10Y | 150.0 | -1.0 |

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
