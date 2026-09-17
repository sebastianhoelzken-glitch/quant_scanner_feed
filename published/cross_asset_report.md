# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **31.574790158206586**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 88.38 | long | 0.48% | 0.50% | 2.17% |
| 2 | USDCHF | 87.25 | long | 1.48% | 1.09% | 1.55% |
| 3 | AUDUSD | 75.54 | long | -1.28% | 0.80% | 1.68% |
| 4 | USDCAD | 60.54 | long | 1.24% | 0.49% | -1.50% |
| 5 | GBPUSD | 50.71 | neutral | -0.80% | -0.74% | 1.68% |
| 6 | EURGBP | 42.08 | short | -0.18% | 0.15% | -1.05% |
| 7 | EURUSD | 41.33 | short | -0.99% | -0.59% | 0.61% |
| 8 | GBPJPY | 26.62 | short | 0.35% | -3.26% | -2.22% |
| 9 | USDJPY | 25.50 | short | 1.16% | -2.54% | -3.83% |
| 10 | EURJPY | 22.88 | short | 0.16% | -3.11% | -3.25% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y | 5.350% | 35.00 | bearish_duration | 7.0 |
| 2 | US30Y_REAL | 3.090% | 31.03 | bearish_duration | 6.0 |
| 3 | DE30Y | 3.910% | 25.56 | bearish_duration | 13.0 |
| 4 | US10Y | 5.010% | 19.10 | bearish_duration | 30.0 |
| 5 | US10Y_REAL | 2.680% | 15.22 | bearish_duration | 27.0 |
| 6 | US3M | 4.140% | 13.57 | bearish_duration | 28.0 |
| 7 | DE10Y | 3.560% | 11.64 | bearish_duration | 30.0 |
| 8 | US5Y | 4.860% | 10.68 | bearish_duration | 49.0 |
| 9 | US2Y | 4.740% | 10.12 | bearish_duration | 55.0 |
| 10 | US5Y_REAL | 2.510% | 9.92 | bearish_duration | 41.0 |
| 11 | DE2Y | 3.260% | 8.92 | bearish_duration | 41.0 |
| 12 | DE5Y | 3.370% | 6.13 | bearish_duration | 39.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 27.0 | -25.0 |
| US_5s30s | 49.0 | -42.0 |
| US_3m10y | 87.0 | 2.0 |
| DE_2s10s | 30.0 | -11.0 |
| US_DE_2Y | 148.0 | 14.0 |
| US_DE_10Y | 145.0 | 6.0 |

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
