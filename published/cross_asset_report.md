# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **28.295901593760995**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 94.38 | long | 1.54% | 3.19% | 2.04% |
| 2 | EURCHF | 85.75 | long | 0.36% | 1.43% | 2.26% |
| 3 | USDCAD | 75.25 | long | 1.30% | 1.63% | -1.17% |
| 4 | AUDUSD | 69.92 | long | -0.99% | 0.11% | 1.50% |
| 5 | EURGBP | 53.04 | neutral | -0.10% | 0.12% | -0.74% |
| 6 | GBPUSD | 37.12 | short | -1.06% | -1.83% | 0.96% |
| 7 | EURUSD | 32.25 | short | -1.16% | -1.71% | 0.22% |
| 8 | USDJPY | 27.00 | short | 0.98% | -1.93% | -3.76% |
| 9 | GBPJPY | 26.62 | short | -0.09% | -3.73% | -2.83% |
| 10 | EURJPY | 19.50 | short | -0.19% | -3.61% | -3.55% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y | 5.290% | 41.35 | bearish_duration | 10.0 |
| 2 | US30Y_REAL | 3.040% | 37.16 | bearish_duration | 10.0 |
| 3 | DE30Y | 3.880% | 33.34 | bearish_duration | 12.0 |
| 4 | US10Y | 4.940% | 29.62 | bearish_duration | 29.0 |
| 5 | US10Y_REAL | 2.610% | 25.45 | bearish_duration | 26.0 |
| 6 | US5Y | 4.780% | 23.56 | bearish_duration | 43.0 |
| 7 | US2Y | 4.670% | 20.27 | bearish_duration | 48.0 |
| 8 | DE10Y | 3.530% | 18.83 | bearish_duration | 27.0 |
| 9 | US3M | 4.120% | 18.56 | bearish_duration | 26.0 |
| 10 | US5Y_REAL | 2.460% | 13.95 | bearish_duration | 39.0 |
| 11 | DE5Y | 3.350% | 10.76 | bearish_duration | 36.0 |
| 12 | DE2Y | 3.260% | 10.07 | bearish_duration | 40.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 27.0 | -19.0 |
| US_5s30s | 51.0 | -33.0 |
| US_3m10y | 82.0 | 3.0 |
| DE_2s10s | 27.0 | -13.0 |
| US_DE_2Y | 141.0 | 8.0 |
| US_DE_10Y | 141.0 | -2.0 |

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
