# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **49.60145294666909**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | GBPJPY | 83.50 | long | -0.32% | 2.47% | 0.60% |
| 2 | EURCHF | 77.12 | long | 0.15% | 0.60% | 2.28% |
| 3 | AUDUSD | 76.75 | long | 0.01% | 2.22% | 0.01% |
| 4 | USDCHF | 71.79 | long | 0.74% | 0.07% | 2.44% |
| 5 | EURJPY | 63.62 | long | -0.20% | 2.48% | -0.24% |
| 6 | USDJPY | 60.54 | long | 0.38% | 1.95% | -0.08% |
| 7 | GBPUSD | 58.67 | long | -0.70% | 0.51% | 0.69% |
| 8 | USDCAD | 42.83 | short | 0.26% | -1.01% | 0.21% |
| 9 | EURUSD | 31.21 | short | -0.58% | 0.53% | -0.15% |
| 10 | EURGBP | 29.79 | short | 0.11% | 0.02% | -0.84% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US3M | 3.910% | 43.49 | bearish_duration | 0.0 |
| 2 | US30Y | 5.250% | 42.92 | bearish_duration | 2.0 |
| 3 | US30Y_REAL | 2.990% | 42.05 | bearish_duration | 0.0 |
| 4 | US10Y | 4.750% | 40.89 | bearish_duration | 5.0 |
| 5 | US2Y | 4.340% | 38.79 | bearish_duration | 9.0 |
| 6 | US5Y | 4.490% | 38.65 | bearish_duration | 9.0 |
| 7 | US10Y_REAL | 2.440% | 38.35 | bearish_duration | 1.0 |
| 8 | US5Y_REAL | 2.180% | 35.59 | bearish_duration | 1.0 |
| 9 | DE2Y | 2.920% | 33.68 | bearish_duration | 16.0 |
| 10 | DE30Y | 3.790% | 31.89 | bearish_duration | 14.0 |
| 11 | DE5Y | 3.050% | 31.08 | bearish_duration | 16.0 |
| 12 | DE10Y | 3.310% | 31.04 | bearish_duration | 16.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 41.0 | -4.0 |
| US_5s30s | 76.0 | -7.0 |
| US_3m10y | 84.0 | 5.0 |
| DE_2s10s | 39.0 | 0.0 |
| US_DE_2Y | 142.0 | -7.0 |
| US_DE_10Y | 144.0 | -11.0 |

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
