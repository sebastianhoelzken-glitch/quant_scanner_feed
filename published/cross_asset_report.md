# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **56.89465008182274**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 84.25 | long | 0.37% | 2.52% | 0.18% |
| 2 | GBPJPY | 78.62 | long | 0.08% | 0.85% | 0.78% |
| 3 | GBPUSD | 74.50 | long | -0.54% | 1.20% | 0.82% |
| 4 | EURCHF | 73.75 | long | 0.12% | 0.64% | 2.35% |
| 5 | USDCHF | 60.08 | long | 0.60% | -0.72% | 2.40% |
| 6 | EURJPY | 59.50 | long | 0.14% | 1.03% | -0.09% |
| 7 | EURUSD | 55.38 | long | -0.48% | 1.38% | -0.05% |
| 8 | USDJPY | 54.54 | neutral | 0.62% | -0.34% | -0.04% |
| 9 | USDCAD | 40.58 | short | 0.83% | -1.33% | 0.12% |
| 10 | EURGBP | 31.29 | short | 0.06% | 0.17% | -0.86% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.960% | 49.77 | neutral | -7.0 |
| 2 | US30Y | 5.220% | 49.70 | neutral | -5.0 |
| 3 | US10Y | 4.730% | 46.06 | neutral | -2.0 |
| 4 | US10Y_REAL | 2.420% | 43.73 | bearish_duration | -5.0 |
| 5 | US5Y | 4.480% | 41.35 | bearish_duration | 3.0 |
| 6 | DE2Y | 2.860% | 39.43 | bearish_duration | 8.0 |
| 7 | US2Y | 4.340% | 38.92 | bearish_duration | 6.0 |
| 8 | US3M | 3.900% | 38.37 | bearish_duration | 7.0 |
| 9 | DE5Y | 2.990% | 36.91 | bearish_duration | 9.0 |
| 10 | US5Y_REAL | 2.180% | 35.92 | bearish_duration | -1.0 |
| 11 | DE10Y | 3.270% | 35.47 | bearish_duration | 11.0 |
| 12 | DE30Y | 3.770% | 34.50 | bearish_duration | 12.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 39.0 | -8.0 |
| US_5s30s | 74.0 | -8.0 |
| US_3m10y | 83.0 | -9.0 |
| DE_2s10s | 41.0 | 3.0 |
| US_DE_2Y | 148.0 | -2.0 |
| US_DE_10Y | 146.0 | -13.0 |

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
