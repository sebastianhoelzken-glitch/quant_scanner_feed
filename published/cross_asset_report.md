# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **47.25243755858142**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | EURCHF | 81.25 | long | 0.52% | 1.66% | 2.44% |
| 2 | GBPJPY | 79.00 | long | 0.77% | -1.22% | 1.29% |
| 3 | AUDUSD | 73.00 | long | 0.87% | 1.69% | -0.06% |
| 4 | USDCHF | 71.42 | long | 0.20% | 0.19% | 2.51% |
| 5 | GBPUSD | 69.62 | long | 0.41% | 0.74% | 1.17% |
| 6 | EURJPY | 56.04 | long | 0.70% | -0.51% | 0.06% |
| 7 | EURUSD | 46.67 | neutral | 0.33% | 1.46% | -0.06% |
| 8 | USDJPY | 46.21 | neutral | 0.37% | -1.95% | 0.12% |
| 9 | USDCAD | 30.00 | short | -0.58% | -1.23% | 0.74% |
| 10 | EURGBP | 17.62 | short | -0.08% | 0.72% | -1.22% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.190% | 51.05 | neutral | -2.0 |
| 2 | US5Y | 4.380% | 47.17 | neutral | 5.0 |
| 3 | DE2Y | 2.800% | 45.91 | neutral | 2.0 |
| 4 | US3M | 3.870% | 45.28 | neutral | 1.0 |
| 5 | DE10Y | 3.200% | 43.35 | bearish_duration | 7.0 |
| 6 | US10Y | 4.720% | 42.67 | bearish_duration | 12.0 |
| 7 | DE5Y | 2.930% | 42.58 | bearish_duration | 7.0 |
| 8 | DE30Y | 3.730% | 39.34 | bearish_duration | 9.0 |
| 9 | US10Y_REAL | 2.440% | 36.80 | bearish_duration | 9.0 |
| 10 | US5Y_REAL | 2.130% | 36.66 | bearish_duration | 8.0 |
| 11 | US30Y | 5.310% | 33.59 | bearish_duration | 20.0 |
| 12 | US30Y_REAL | 3.060% | 30.22 | bearish_duration | 15.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 53.0 | 14.0 |
| US_5s30s | 93.0 | 15.0 |
| US_3m10y | 85.0 | 11.0 |
| DE_2s10s | 40.0 | 5.0 |
| US_DE_2Y | 139.0 | -4.0 |
| US_DE_10Y | 152.0 | 5.0 |

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
