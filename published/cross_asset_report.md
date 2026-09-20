# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **22.72450757568441**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 90.62 | long | 1.27% | 3.28% | 1.96% |
| 2 | EURCHF | 82.00 | long | 0.12% | 1.17% | 2.57% |
| 3 | USDCAD | 73.00 | long | 1.10% | 1.97% | -1.25% |
| 4 | AUDUSD | 72.54 | long | -0.73% | -0.67% | 2.65% |
| 5 | EURGBP | 52.29 | neutral | 0.08% | 0.25% | -0.37% |
| 6 | USDJPY | 48.46 | neutral | 2.50% | -0.51% | -2.26% |
| 7 | GBPUSD | 33.00 | short | -1.21% | -2.28% | 0.97% |
| 8 | GBPJPY | 27.38 | short | 1.26% | -2.78% | -1.31% |
| 9 | EURUSD | 26.62 | short | -1.14% | -2.04% | 0.60% |
| 10 | EURJPY | 23.25 | short | 1.33% | -2.54% | -1.67% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | DE30Y | 3.850% | 36.97 | bearish_duration | 9.0 |
| 2 | US30Y | 5.340% | 36.42 | bearish_duration | 11.0 |
| 3 | US30Y_REAL | 3.090% | 31.51 | bearish_duration | 14.0 |
| 4 | US10Y | 5.010% | 24.48 | bearish_duration | 32.0 |
| 5 | DE10Y | 3.500% | 23.22 | bearish_duration | 26.0 |
| 6 | US3M | 4.140% | 20.26 | bearish_duration | 27.0 |
| 7 | US10Y_REAL | 2.680% | 19.58 | bearish_duration | 33.0 |
| 8 | US5Y | 4.860% | 18.54 | bearish_duration | 47.0 |
| 9 | US2Y | 4.760% | 16.19 | bearish_duration | 57.0 |
| 10 | DE5Y | 3.330% | 13.38 | bearish_duration | 37.0 |
| 11 | DE2Y | 3.250% | 12.59 | bearish_duration | 42.0 |
| 12 | US5Y_REAL | 2.550% | 10.99 | bearish_duration | 50.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 25.0 | -25.0 |
| US_5s30s | 48.0 | -36.0 |
| US_3m10y | 87.0 | 5.0 |
| DE_2s10s | 25.0 | -16.0 |
| US_DE_2Y | 151.0 | 10.0 |
| US_DE_10Y | 151.0 | 1.0 |

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
