# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **31.998447605116905**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 83.50 | long | 0.61% | 2.34% | 1.07% |
| 2 | EURCHF | 81.62 | long | 0.07% | 0.81% | 2.41% |
| 3 | AUDUSD | 76.67 | long | 0.11% | -0.34% | 3.45% |
| 4 | USDCAD | 66.62 | long | 0.84% | 1.12% | -1.61% |
| 5 | EURGBP | 51.54 | neutral | 0.21% | 0.27% | -0.45% |
| 6 | USDJPY | 40.58 | short | 1.76% | -1.17% | -2.73% |
| 7 | GBPUSD | 36.75 | short | -0.74% | -1.76% | 1.78% |
| 8 | EURUSD | 33.38 | short | -0.53% | -1.49% | 1.32% |
| 9 | GBPJPY | 31.88 | short | 1.01% | -2.90% | -1.00% |
| 10 | EURJPY | 26.62 | short | 1.22% | -2.64% | -1.45% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y | 5.290% | 44.28 | bearish_duration | 2.0 |
| 2 | US30Y_REAL | 3.020% | 43.89 | bearish_duration | 2.0 |
| 3 | DE30Y | 3.800% | 42.74 | bearish_duration | 5.0 |
| 4 | US10Y | 4.960% | 32.91 | bearish_duration | 22.0 |
| 5 | US10Y_REAL | 2.620% | 30.66 | bearish_duration | 22.0 |
| 6 | DE10Y | 3.460% | 28.57 | bearish_duration | 22.0 |
| 7 | US5Y | 4.830% | 24.36 | bearish_duration | 40.0 |
| 8 | US3M | 4.170% | 19.39 | bearish_duration | 29.0 |
| 9 | DE5Y | 3.300% | 19.07 | bearish_duration | 33.0 |
| 10 | US2Y | 4.760% | 18.45 | bearish_duration | 52.0 |
| 11 | DE2Y | 3.230% | 18.17 | bearish_duration | 39.0 |
| 12 | US5Y_REAL | 2.500% | 17.60 | bearish_duration | 41.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 20.0 | -30.0 |
| US_5s30s | 46.0 | -38.0 |
| US_3m10y | 79.0 | -7.0 |
| DE_2s10s | 23.0 | -17.0 |
| US_DE_2Y | 153.0 | 13.0 |
| US_DE_10Y | 150.0 | 4.0 |

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
