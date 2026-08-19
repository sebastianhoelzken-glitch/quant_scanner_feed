# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **50.253222989083525**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 85.00 | long | 0.59% | 1.59% | 2.85% |
| 2 | USDCHF | 81.62 | long | 0.28% | 0.20% | 3.06% |
| 3 | GBPJPY | 76.00 | long | 0.51% | -0.95% | 1.14% |
| 4 | AUDUSD | 69.25 | long | 0.67% | 1.37% | -0.23% |
| 5 | GBPUSD | 66.25 | long | 0.19% | 0.93% | 0.79% |
| 6 | EURJPY | 63.62 | long | 0.63% | -0.51% | 0.15% |
| 7 | USDJPY | 48.46 | neutral | 0.31% | -1.87% | 0.35% |
| 8 | EURUSD | 47.79 | neutral | 0.31% | 1.38% | -0.20% |
| 9 | USDCAD | 38.71 | short | -0.46% | -1.42% | 0.75% |
| 10 | EURGBP | 27.46 | short | 0.12% | 0.45% | -0.98% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.190% | 51.57 | neutral | -7.0 |
| 2 | US5Y | 4.370% | 49.03 | neutral | 0.0 |
| 3 | US3M | 3.860% | 47.20 | neutral | -1.0 |
| 4 | US10Y | 4.710% | 44.50 | bearish_duration | 8.0 |
| 5 | US10Y_REAL | 2.410% | 42.32 | bearish_duration | 4.0 |
| 6 | DE2Y | 2.850% | 42.06 | bearish_duration | 4.0 |
| 7 | US5Y_REAL | 2.100% | 41.93 | bearish_duration | 1.0 |
| 8 | DE5Y | 2.980% | 38.66 | bearish_duration | 6.0 |
| 9 | US30Y | 5.280% | 38.01 | bearish_duration | 15.0 |
| 10 | DE10Y | 3.260% | 37.07 | bearish_duration | 9.0 |
| 11 | US30Y_REAL | 3.030% | 35.07 | bearish_duration | 12.0 |
| 12 | DE30Y | 3.780% | 30.65 | bearish_duration | 12.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 52.0 | 15.0 |
| US_5s30s | 91.0 | 15.0 |
| US_3m10y | 85.0 | 9.0 |
| DE_2s10s | 41.0 | 5.0 |
| US_DE_2Y | 134.0 | -16.0 |
| US_DE_10Y | 145.0 | -5.0 |

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
