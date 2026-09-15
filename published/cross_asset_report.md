# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **35.4562082028429**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 95.12 | long | 0.89% | 0.81% | 2.94% |
| 2 | EURCHF | 88.75 | long | 0.28% | 0.45% | 2.59% |
| 3 | AUDUSD | 66.92 | long | -1.18% | 0.06% | 0.98% |
| 4 | USDCAD | 66.17 | long | 0.48% | 0.20% | -0.89% |
| 5 | GBPUSD | 58.29 | long | -0.27% | -0.48% | 0.66% |
| 6 | EURGBP | 42.46 | short | -0.34% | 0.11% | -1.00% |
| 7 | EURUSD | 42.08 | short | -0.61% | -0.36% | -0.35% |
| 8 | USDJPY | 27.00 | short | -0.13% | -2.94% | -3.60% |
| 9 | GBPJPY | 25.12 | short | -0.40% | -3.40% | -2.96% |
| 10 | EURJPY | 17.25 | short | -0.74% | -3.29% | -3.93% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 3.050% | 34.47 | bearish_duration | 5.0 |
| 2 | US30Y | 5.340% | 33.98 | bearish_duration | 9.0 |
| 3 | DE30Y | 3.900% | 23.74 | bearish_duration | 17.0 |
| 4 | US10Y_REAL | 2.600% | 22.74 | bearish_duration | 19.0 |
| 5 | US10Y | 4.970% | 21.15 | bearish_duration | 29.0 |
| 6 | US5Y_REAL | 2.400% | 17.59 | bearish_duration | 28.0 |
| 7 | US3M | 4.110% | 15.87 | bearish_duration | 25.0 |
| 8 | US2Y | 4.650% | 14.55 | bearish_duration | 48.0 |
| 9 | US5Y | 4.800% | 14.36 | bearish_duration | 44.0 |
| 10 | DE10Y | 3.530% | 9.29 | bearish_duration | 33.0 |
| 11 | DE2Y | 3.250% | 6.70 | bearish_duration | 45.0 |
| 12 | DE5Y | 3.330% | 5.38 | bearish_duration | 40.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 32.0 | -19.0 |
| US_5s30s | 54.0 | -35.0 |
| US_3m10y | 86.0 | 4.0 |
| DE_2s10s | 28.0 | -12.0 |
| US_DE_2Y | 140.0 | 1.0 |
| US_DE_10Y | 144.0 | -8.0 |

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
