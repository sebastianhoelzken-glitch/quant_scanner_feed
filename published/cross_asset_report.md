# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **49.2477951064709**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 92.50 | long | 0.12% | 2.32% | 2.02% |
| 2 | EURCHF | 89.88 | long | 0.44% | 0.62% | 2.16% |
| 3 | USDCHF | 71.79 | long | 0.62% | -0.13% | 1.73% |
| 4 | GBPUSD | 61.67 | long | -0.39% | 0.60% | 0.94% |
| 5 | EURUSD | 60.17 | long | -0.18% | 0.75% | 0.42% |
| 6 | EURGBP | 51.92 | neutral | 0.21% | 0.16% | -0.51% |
| 7 | USDCAD | 28.88 | short | -0.39% | -1.50% | -0.87% |
| 8 | GBPJPY | 28.12 | short | -2.53% | -0.73% | -1.52% |
| 9 | EURJPY | 24.38 | short | -2.33% | -0.57% | -2.03% |
| 10 | USDJPY | 19.88 | short | -2.15% | -1.32% | -2.44% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.960% | 44.49 | bearish_duration | 0.0 |
| 2 | US3M | 3.910% | 42.65 | bearish_duration | 4.0 |
| 3 | US10Y_REAL | 2.430% | 42.26 | bearish_duration | 3.0 |
| 4 | US30Y | 5.240% | 42.07 | bearish_duration | 5.0 |
| 5 | US5Y_REAL | 2.170% | 41.29 | bearish_duration | 4.0 |
| 6 | US2Y | 4.370% | 38.86 | bearish_duration | 18.0 |
| 7 | US10Y | 4.780% | 38.18 | bearish_duration | 13.0 |
| 8 | US5Y | 4.540% | 36.02 | bearish_duration | 19.0 |
| 9 | DE2Y | 2.960% | 30.27 | bearish_duration | 20.0 |
| 10 | DE30Y | 3.820% | 30.22 | bearish_duration | 17.0 |
| 11 | DE10Y | 3.340% | 30.06 | bearish_duration | 19.0 |
| 12 | DE5Y | 3.090% | 27.41 | bearish_duration | 21.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 41.0 | -5.0 |
| US_5s30s | 70.0 | -14.0 |
| US_3m10y | 87.0 | 9.0 |
| DE_2s10s | 38.0 | -1.0 |
| US_DE_2Y | 141.0 | -2.0 |
| US_DE_10Y | 144.0 | -6.0 |

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
