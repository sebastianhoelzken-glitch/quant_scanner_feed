# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **51.98031567769789**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 94.00 | long | 1.03% | 2.13% | 3.10% |
| 2 | EURCHF | 89.50 | long | 0.33% | 0.79% | 2.21% |
| 3 | USDCHF | 77.88 | long | 0.12% | 0.15% | 1.53% |
| 4 | GBPUSD | 65.04 | long | 0.11% | 0.34% | 1.36% |
| 5 | EURUSD | 52.58 | neutral | 0.21% | 0.64% | 0.67% |
| 6 | EURGBP | 50.04 | neutral | 0.10% | 0.30% | -0.68% |
| 7 | USDCAD | 34.88 | short | -0.60% | -0.95% | -1.24% |
| 8 | GBPJPY | 26.62 | short | -3.56% | -2.75% | -2.58% |
| 9 | EURJPY | 23.25 | short | -3.46% | -2.46% | -3.24% |
| 10 | USDJPY | 15.38 | short | -3.66% | -3.08% | -3.89% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.960% | 49.05 | neutral | -4.0 |
| 2 | US30Y | 5.250% | 45.46 | neutral | 0.0 |
| 3 | US10Y_REAL | 2.430% | 45.29 | neutral | 0.0 |
| 4 | US5Y_REAL | 2.170% | 42.88 | bearish_duration | 1.0 |
| 5 | US3M | 3.940% | 40.47 | bearish_duration | 5.0 |
| 6 | US10Y | 4.800% | 40.15 | bearish_duration | 8.0 |
| 7 | US2Y | 4.390% | 39.03 | bearish_duration | 14.0 |
| 8 | US5Y | 4.570% | 36.01 | bearish_duration | 16.0 |
| 9 | DE2Y | 3.010% | 33.02 | bearish_duration | 19.0 |
| 10 | DE30Y | 3.850% | 32.57 | bearish_duration | 16.0 |
| 11 | DE10Y | 3.390% | 31.16 | bearish_duration | 19.0 |
| 12 | DE5Y | 3.140% | 29.26 | bearish_duration | 21.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 41.0 | -6.0 |
| US_5s30s | 68.0 | -16.0 |
| US_3m10y | 86.0 | 3.0 |
| DE_2s10s | 38.0 | 0.0 |
| US_DE_2Y | 138.0 | -2.0 |
| US_DE_10Y | 141.0 | -9.0 |

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
