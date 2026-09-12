# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: RESTRICTIVE
Context score: **35.33356278833594**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 91.38 | long | 0.75% | 0.43% | 2.48% |
| 2 | EURCHF | 89.50 | long | 0.49% | 0.65% | 2.46% |
| 3 | AUDUSD | 86.50 | long | -0.42% | 1.28% | 1.53% |
| 4 | GBPUSD | 58.67 | long | -0.16% | -0.21% | 0.75% |
| 5 | EURGBP | 55.67 | long | -0.10% | 0.43% | -0.76% |
| 6 | USDCAD | 54.54 | neutral | 0.42% | -0.12% | -1.12% |
| 7 | EURUSD | 45.46 | neutral | -0.26% | 0.22% | -0.02% |
| 8 | GBPJPY | 23.62 | short | -1.57% | -3.33% | -3.23% |
| 9 | USDJPY | 22.12 | short | -1.41% | -3.13% | -3.95% |
| 10 | EURJPY | 18.38 | short | -1.67% | -2.92% | -3.97% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y | 5.350% | 31.00 | bearish_duration | 14.0 |
| 2 | US30Y_REAL | 3.070% | 29.72 | bearish_duration | 10.0 |
| 3 | US10Y_REAL | 2.600% | 21.02 | bearish_duration | 21.0 |
| 4 | DE30Y | 3.900% | 20.33 | bearish_duration | 22.0 |
| 5 | US3M | 4.070% | 19.92 | bearish_duration | 20.0 |
| 6 | US10Y | 4.960% | 19.13 | bearish_duration | 33.0 |
| 7 | US5Y_REAL | 2.380% | 17.77 | bearish_duration | 27.0 |
| 8 | US2Y | 4.630% | 14.31 | bearish_duration | 48.0 |
| 9 | US5Y | 4.780% | 13.46 | bearish_duration | 46.0 |
| 10 | DE10Y | 3.510% | 9.48 | bearish_duration | 35.0 |
| 11 | DE2Y | 3.180% | 9.19 | bearish_duration | 40.0 |
| 12 | DE5Y | 3.290% | 6.20 | bearish_duration | 40.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 33.0 | -15.0 |
| US_5s30s | 57.0 | -32.0 |
| US_3m10y | 89.0 | 13.0 |
| DE_2s10s | 33.0 | -5.0 |
| US_DE_2Y | 145.0 | 6.0 |
| US_DE_10Y | 145.0 | -7.0 |

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
