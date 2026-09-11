# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **41.84266500027897**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 90.62 | long | 0.45% | 0.63% | 2.39% |
| 2 | AUDUSD | 88.75 | long | -0.12% | 1.89% | 1.67% |
| 3 | USDCHF | 81.62 | long | 0.44% | -0.08% | 2.31% |
| 4 | GBPUSD | 61.67 | long | 0.17% | 0.21% | 0.74% |
| 5 | EURGBP | 53.42 | neutral | -0.16% | 0.50% | -0.66% |
| 6 | EURUSD | 53.33 | neutral | 0.01% | 0.71% | 0.08% |
| 7 | USDCAD | 34.50 | short | 0.18% | -0.95% | -1.18% |
| 8 | GBPJPY | 26.25 | short | -1.01% | -3.03% | -3.04% |
| 9 | EURJPY | 22.50 | short | -1.17% | -2.55% | -3.68% |
| 10 | USDJPY | 16.50 | short | -1.18% | -3.23% | -3.75% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 3.050% | 36.54 | bearish_duration | 6.0 |
| 2 | US30Y | 5.370% | 33.31 | bearish_duration | 13.0 |
| 3 | US10Y_REAL | 2.550% | 31.21 | bearish_duration | 13.0 |
| 4 | US5Y_REAL | 2.290% | 30.45 | bearish_duration | 15.0 |
| 5 | US3M | 4.000% | 30.25 | bearish_duration | 13.0 |
| 6 | US10Y | 4.950% | 26.10 | bearish_duration | 27.0 |
| 7 | US2Y | 4.560% | 24.88 | bearish_duration | 36.0 |
| 8 | US5Y | 4.750% | 21.56 | bearish_duration | 37.0 |
| 9 | DE2Y | 3.060% | 20.22 | bearish_duration | 29.0 |
| 10 | DE30Y | 3.900% | 19.81 | bearish_duration | 24.0 |
| 11 | DE10Y | 3.450% | 17.43 | bearish_duration | 30.0 |
| 12 | DE5Y | 3.200% | 16.78 | bearish_duration | 31.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 39.0 | -9.0 |
| US_5s30s | 62.0 | -24.0 |
| US_3m10y | 95.0 | 14.0 |
| DE_2s10s | 39.0 | 1.0 |
| US_DE_2Y | 150.0 | 12.0 |
| US_DE_10Y | 150.0 | 2.0 |

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
