# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **51.67548976393732**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 92.50 | long | 0.05% | 2.15% | 1.67% |
| 2 | EURCHF | 89.12 | long | 0.15% | 0.47% | 2.21% |
| 3 | USDCHF | 71.79 | long | 0.41% | -0.16% | 1.55% |
| 4 | GBPUSD | 60.54 | long | -0.62% | 0.22% | 1.01% |
| 5 | EURUSD | 60.17 | long | -0.26% | 0.63% | 0.65% |
| 6 | EURGBP | 54.54 | neutral | 0.37% | 0.41% | -0.35% |
| 7 | GBPJPY | 28.12 | short | -2.73% | -0.93% | -1.49% |
| 7 | USDCAD | 28.12 | short | -0.56% | -1.47% | -1.04% |
| 9 | EURJPY | 24.38 | short | -2.37% | -0.53% | -1.84% |
| 10 | USDJPY | 19.88 | short | -2.12% | -1.15% | -2.47% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US3M | 3.890% | 44.24 | bearish_duration | -1.0 |
| 2 | US30Y_REAL | 2.960% | 42.89 | bearish_duration | -2.0 |
| 3 | US30Y | 5.250% | 40.36 | bearish_duration | 3.0 |
| 4 | US10Y_REAL | 2.420% | 39.82 | bearish_duration | -1.0 |
| 5 | US5Y_REAL | 2.150% | 39.14 | bearish_duration | -2.0 |
| 6 | US2Y | 4.340% | 37.62 | bearish_duration | 9.0 |
| 7 | US10Y | 4.770% | 37.42 | bearish_duration | 8.0 |
| 8 | US5Y | 4.520% | 35.02 | bearish_duration | 12.0 |
| 9 | DE2Y | 2.980% | 27.69 | bearish_duration | 24.0 |
| 10 | DE30Y | 3.820% | 27.22 | bearish_duration | 20.0 |
| 11 | DE10Y | 3.360% | 24.73 | bearish_duration | 25.0 |
| 12 | DE5Y | 3.110% | 23.37 | bearish_duration | 26.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 43.0 | -1.0 |
| US_5s30s | 73.0 | -9.0 |
| US_3m10y | 88.0 | 9.0 |
| DE_2s10s | 38.0 | 1.0 |
| US_DE_2Y | 136.0 | -15.0 |
| US_DE_10Y | 141.0 | -17.0 |

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
