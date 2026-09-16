# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **36.311938535422414**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 90.25 | long | 0.17% | 0.37% | 2.42% |
| 2 | USDCHF | 89.88 | long | 0.82% | 0.69% | 1.73% |
| 3 | AUDUSD | 66.54 | long | -1.23% | 0.20% | 1.73% |
| 4 | USDCAD | 64.67 | long | 0.83% | 0.33% | -1.46% |
| 5 | GBPUSD | 62.42 | long | -0.46% | -0.31% | 1.93% |
| 6 | EURGBP | 42.83 | short | -0.19% | -0.01% | -1.22% |
| 7 | EURUSD | 39.46 | short | -0.65% | -0.32% | 0.68% |
| 8 | GBPJPY | 28.50 | short | -0.00% | -3.25% | -1.83% |
| 9 | USDJPY | 25.50 | short | 0.46% | -2.94% | -3.68% |
| 10 | EURJPY | 19.12 | short | -0.19% | -3.25% | -3.03% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y | 5.360% | 35.04 | bearish_duration | 5.0 |
| 2 | US30Y_REAL | 3.070% | 34.99 | bearish_duration | 1.0 |
| 3 | DE30Y | 3.910% | 25.20 | bearish_duration | 14.0 |
| 4 | US10Y_REAL | 2.620% | 21.33 | bearish_duration | 18.0 |
| 5 | US10Y | 5.000% | 20.47 | bearish_duration | 28.0 |
| 6 | US3M | 4.110% | 16.79 | bearish_duration | 24.0 |
| 7 | US5Y_REAL | 2.420% | 15.69 | bearish_duration | 29.0 |
| 8 | US2Y | 4.670% | 13.85 | bearish_duration | 48.0 |
| 9 | US5Y | 4.830% | 12.81 | bearish_duration | 45.0 |
| 10 | DE10Y | 3.560% | 10.49 | bearish_duration | 31.0 |
| 11 | DE2Y | 3.270% | 7.20 | bearish_duration | 44.0 |
| 12 | DE5Y | 3.360% | 5.93 | bearish_duration | 39.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 33.0 | -20.0 |
| US_5s30s | 53.0 | -40.0 |
| US_3m10y | 89.0 | 4.0 |
| DE_2s10s | 29.0 | -13.0 |
| US_DE_2Y | 140.0 | 4.0 |
| US_DE_10Y | 144.0 | -2.0 |

## Provider status

```json
{
  "ecb_USD": {
    "status": "ok",
    "rows": 301
  },
  "ecb_GBP": {
    "status": "ok",
    "rows": 301
  },
  "ecb_JPY": {
    "status": "ok",
    "rows": 301
  },
  "ecb_CHF": {
    "status": "ok",
    "rows": 301
  },
  "ecb_AUD": {
    "status": "ok",
    "rows": 301
  },
  "ecb_CAD": {
    "status": "ok",
    "rows": 301
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
    "rows": 299
  },
  "bundesbank_DE5Y": {
    "status": "ok",
    "rows": 299
  },
  "bundesbank_DE10Y": {
    "status": "ok",
    "rows": 299
  },
  "bundesbank_DE30Y": {
    "status": "ok",
    "rows": 299
  }
}
```
