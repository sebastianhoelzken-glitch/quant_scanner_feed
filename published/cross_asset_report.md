# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **46.05353654023191**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 82.38 | long | 0.46% | 1.76% | 2.62% |
| 2 | USDCHF | 74.42 | long | 0.18% | 0.59% | 3.09% |
| 3 | AUDUSD | 71.12 | long | 0.59% | 1.53% | -0.49% |
| 3 | GBPUSD | 71.12 | long | 0.65% | 0.74% | 0.97% |
| 5 | GBPJPY | 57.46 | long | 1.08% | -1.33% | 0.90% |
| 6 | USDJPY | 47.71 | neutral | 0.43% | -2.06% | -0.06% |
| 7 | EURUSD | 47.42 | neutral | 0.28% | 1.15% | -0.46% |
| 8 | USDCAD | 42.83 | short | -0.96% | -1.05% | 0.86% |
| 9 | EURJPY | 42.46 | short | 0.71% | -0.93% | -0.52% |
| 10 | EURGBP | 17.25 | short | -0.37% | 0.41% | -1.41% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.170% | 48.38 | neutral | -1.0 |
| 2 | DE10Y | 3.160% | 47.94 | neutral | 3.0 |
| 3 | DE2Y | 2.780% | 47.48 | neutral | 1.0 |
| 4 | DE5Y | 2.890% | 46.86 | neutral | 4.0 |
| 5 | DE30Y | 3.680% | 46.39 | neutral | 4.0 |
| 6 | US3M | 3.860% | 44.97 | bearish_duration | 1.0 |
| 7 | US5Y | 4.360% | 43.28 | bearish_duration | 8.0 |
| 8 | US10Y | 4.680% | 40.19 | bearish_duration | 13.0 |
| 9 | US10Y_REAL | 2.410% | 35.45 | bearish_duration | 10.0 |
| 10 | US30Y | 5.250% | 33.79 | bearish_duration | 19.0 |
| 11 | US5Y_REAL | 2.120% | 33.45 | bearish_duration | 11.0 |
| 12 | US30Y_REAL | 3.000% | 32.50 | bearish_duration | 13.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 51.0 | 14.0 |
| US_5s30s | 89.0 | 11.0 |
| US_3m10y | 82.0 | 12.0 |
| DE_2s10s | 38.0 | 2.0 |
| US_DE_2Y | 139.0 | -2.0 |
| US_DE_10Y | 152.0 | 10.0 |

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
