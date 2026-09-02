# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **45.46943779318975**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | GBPJPY | 85.00 | long | -0.16% | 2.39% | 0.77% |
| 2 | USDCHF | 81.25 | long | 0.98% | 0.15% | 2.91% |
| 3 | EURCHF | 79.38 | long | 0.35% | 0.80% | 2.47% |
| 4 | USDJPY | 71.42 | long | 0.58% | 1.75% | 0.23% |
| 5 | EURJPY | 69.62 | long | -0.04% | 2.41% | -0.20% |
| 6 | AUDUSD | 68.88 | long | -0.17% | 1.56% | -0.02% |
| 7 | GBPUSD | 51.92 | neutral | -0.74% | 0.63% | 0.54% |
| 8 | USDCAD | 37.96 | short | 0.20% | -1.23% | -0.07% |
| 9 | EURGBP | 29.79 | short | 0.12% | 0.02% | -0.97% |
| 10 | EURUSD | 28.96 | short | -0.62% | 0.65% | -0.43% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US3M | 3.920% | 39.49 | bearish_duration | 3.0 |
| 2 | US30Y_REAL | 2.980% | 38.63 | bearish_duration | 2.0 |
| 3 | US30Y | 5.270% | 35.50 | bearish_duration | 9.0 |
| 4 | US10Y_REAL | 2.440% | 34.04 | bearish_duration | 4.0 |
| 5 | US5Y_REAL | 2.180% | 32.51 | bearish_duration | 4.0 |
| 6 | US10Y | 4.790% | 31.71 | bearish_duration | 16.0 |
| 7 | US2Y | 4.390% | 30.55 | bearish_duration | 19.0 |
| 8 | DE2Y | 2.970% | 30.39 | bearish_duration | 19.0 |
| 9 | US5Y | 4.550% | 28.64 | bearish_duration | 22.0 |
| 10 | DE5Y | 3.090% | 27.89 | bearish_duration | 19.0 |
| 11 | DE10Y | 3.360% | 26.28 | bearish_duration | 20.0 |
| 12 | DE30Y | 3.840% | 26.05 | bearish_duration | 18.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 40.0 | -3.0 |
| US_5s30s | 72.0 | -13.0 |
| US_3m10y | 87.0 | 13.0 |
| DE_2s10s | 39.0 | 1.0 |
| US_DE_2Y | 142.0 | -0.0 |
| US_DE_10Y | 143.0 | -4.0 |

## Provider status

```json
{
  "ecb_USD": {
    "status": "ok",
    "rows": 301
  },
  "ecb_GBP": {
    "status": "ok",
    "rows": 301
  },
  "ecb_JPY": {
    "status": "ok",
    "rows": 301
  },
  "ecb_CHF": {
    "status": "ok",
    "rows": 301
  },
  "ecb_AUD": {
    "status": "ok",
    "rows": 301
  },
  "ecb_CAD": {
    "status": "ok",
    "rows": 301
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
    "rows": 299
  },
  "bundesbank_DE5Y": {
    "status": "ok",
    "rows": 299
  },
  "bundesbank_DE10Y": {
    "status": "ok",
    "rows": 299
  },
  "bundesbank_DE30Y": {
    "status": "ok",
    "rows": 299
  }
}
```
