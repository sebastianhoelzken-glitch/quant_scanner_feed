# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: SUPPORTIVE
Context score: **61.893617878423804**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 80.12 | long | -0.23% | 0.51% | 2.95% |
| 2 | AUDUSD | 79.00 | long | 1.54% | 3.52% | 0.20% |
| 3 | GBPUSD | 77.12 | long | 0.55% | 2.57% | 1.51% |
| 4 | GBPJPY | 76.75 | long | 0.54% | -0.32% | 1.39% |
| 5 | EURUSD | 64.38 | long | 0.55% | 2.54% | 0.21% |
| 6 | EURJPY | 59.50 | long | 0.54% | -0.35% | 0.09% |
| 7 | USDCHF | 50.33 | neutral | -0.78% | -1.98% | 2.73% |
| 8 | USDJPY | 44.42 | short | -0.01% | -2.82% | -0.12% |
| 9 | USDCAD | 44.33 | short | -0.07% | -1.72% | 0.42% |
| 10 | EURGBP | 28.21 | short | 0.01% | -0.03% | -1.28% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.920% | 49.44 | neutral | -6.0 |
| 2 | US10Y_REAL | 2.340% | 48.36 | neutral | -7.0 |
| 3 | US2Y | 4.190% | 47.95 | neutral | -3.0 |
| 4 | US30Y | 5.180% | 47.87 | neutral | -2.0 |
| 5 | US10Y | 4.660% | 46.71 | neutral | -1.0 |
| 6 | DE2Y | 2.790% | 46.40 | neutral | 2.0 |
| 7 | US5Y | 4.370% | 45.88 | neutral | 0.0 |
| 8 | US5Y_REAL | 2.060% | 45.16 | neutral | -7.0 |
| 9 | DE5Y | 2.920% | 44.64 | bearish_duration | 4.0 |
| 10 | US3M | 3.850% | 44.26 | bearish_duration | 2.0 |
| 11 | DE10Y | 3.200% | 43.22 | bearish_duration | 7.0 |
| 12 | DE30Y | 3.710% | 41.93 | bearish_duration | 10.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 47.0 | 2.0 |
| US_5s30s | 81.0 | -2.0 |
| US_3m10y | 81.0 | -3.0 |
| DE_2s10s | 41.0 | 5.0 |
| US_DE_2Y | 140.0 | -5.0 |
| US_DE_10Y | 146.0 | -8.0 |

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
