# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: SUPPORTIVE
Context score: **61.29661653084061**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | AUDUSD | 82.00 | long | 0.59% | 2.65% | 0.48% |
| 2 | GBPUSD | 79.19 | long | 0.78% | 2.60% | 1.70% |
| 3 | EURCHF | 79.00 | long | -0.48% | 0.45% | 2.12% |
| 4 | GBPJPY | 76.56 | long | 0.49% | -0.33% | 1.55% |
| 5 | EURUSD | 64.19 | long | 0.74% | 2.60% | 0.39% |
| 6 | EURJPY | 59.31 | long | 0.45% | -0.33% | 0.25% |
| 7 | USDCHF | 52.58 | neutral | -1.21% | -2.09% | 1.72% |
| 8 | USDJPY | 44.79 | short | -0.29% | -2.85% | -0.14% |
| 9 | USDCAD | 38.33 | short | -0.10% | -1.76% | 0.04% |
| 10 | EURGBP | 19.88 | short | -0.04% | 0.00% | -1.29% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US10Y_REAL | 2.320% | 53.93 | neutral | -9.0 |
| 2 | US5Y_REAL | 2.040% | 51.69 | neutral | -15.0 |
| 3 | US2Y | 4.170% | 51.45 | neutral | -9.0 |
| 4 | US30Y_REAL | 2.920% | 50.83 | neutral | 0.0 |
| 5 | US10Y | 4.640% | 48.77 | neutral | 3.0 |
| 6 | US30Y | 5.170% | 47.97 | neutral | 8.0 |
| 7 | US5Y | 4.350% | 47.96 | neutral | 0.0 |
| 8 | US3M | 3.860% | 47.39 | neutral | -4.0 |
| 9 | DE2Y | 2.860% | 38.54 | bearish_duration | 10.0 |
| 10 | DE10Y | 3.240% | 37.93 | bearish_duration | 13.0 |
| 11 | DE5Y | 2.980% | 37.05 | bearish_duration | 12.0 |
| 12 | DE30Y | 3.750% | 35.46 | bearish_duration | 15.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 47.0 | 12.0 |
| US_5s30s | 82.0 | 8.0 |
| US_3m10y | 78.0 | 7.0 |
| DE_2s10s | 38.0 | 3.0 |
| US_DE_2Y | 131.0 | -19.0 |
| US_DE_10Y | 140.0 | -10.0 |

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
