# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **50.45907382523075**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 95.50 | long | 1.08% | 2.17% | 2.70% |
| 2 | EURCHF | 83.50 | long | -0.21% | 0.41% | 2.03% |
| 3 | GBPUSD | 74.50 | long | 0.61% | 0.29% | 1.21% |
| 4 | EURUSD | 73.00 | long | 0.64% | 0.93% | 0.73% |
| 5 | USDCHF | 59.71 | long | -0.85% | -0.52% | 1.28% |
| 6 | EURGBP | 55.29 | long | 0.03% | 0.63% | -0.47% |
| 7 | USDCAD | 30.75 | short | -1.12% | -1.13% | -1.57% |
| 8 | GBPJPY | 26.62 | short | -3.38% | -3.38% | -3.16% |
| 9 | EURJPY | 23.25 | short | -3.35% | -2.77% | -3.62% |
| 10 | USDJPY | 15.38 | short | -3.96% | -3.66% | -4.32% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.980% | 45.34 | neutral | -2.0 |
| 2 | US30Y | 5.280% | 42.13 | bearish_duration | 4.0 |
| 3 | US10Y_REAL | 2.460% | 41.33 | bearish_duration | 3.0 |
| 4 | US5Y_REAL | 2.200% | 39.69 | bearish_duration | 4.0 |
| 5 | US3M | 3.950% | 39.17 | bearish_duration | 6.0 |
| 6 | US10Y | 4.830% | 37.23 | bearish_duration | 13.0 |
| 7 | US2Y | 4.430% | 35.75 | bearish_duration | 21.0 |
| 8 | US5Y | 4.610% | 33.13 | bearish_duration | 22.0 |
| 9 | DE30Y | 3.830% | 30.67 | bearish_duration | 18.0 |
| 10 | DE2Y | 3.030% | 27.66 | bearish_duration | 24.0 |
| 11 | DE10Y | 3.390% | 27.50 | bearish_duration | 23.0 |
| 12 | DE5Y | 3.150% | 24.91 | bearish_duration | 26.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 40.0 | -8.0 |
| US_5s30s | 67.0 | -18.0 |
| US_3m10y | 88.0 | 7.0 |
| DE_2s10s | 36.0 | -1.0 |
| US_DE_2Y | 140.0 | -1.0 |
| US_DE_10Y | 144.0 | -8.0 |

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
