# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: SUPPORTIVE
Context score: **61.500076204078724**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | GBPUSD | 80.88 | long | 1.00% | 2.05% | 0.95% |
| 2 | GBPJPY | 77.88 | long | 0.64% | -0.89% | 0.84% |
| 3 | EURUSD | 73.38 | long | 1.27% | 2.54% | 0.33% |
| 4 | EURJPY | 68.50 | long | 0.91% | -0.42% | 0.22% |
| 5 | EURCHF | 65.42 | long | -0.43% | 0.41% | 2.57% |
| 6 | AUDUSD | 64.75 | long | 0.77% | 1.62% | -0.88% |
| 7 | USDCHF | 51.83 | neutral | -1.68% | -2.08% | 2.24% |
| 8 | USDJPY | 43.21 | short | -0.36% | -2.88% | -0.10% |
| 9 | EURGBP | 40.67 | short | 0.27% | 0.48% | -0.61% |
| 10 | USDCAD | 21.00 | short | -1.28% | -2.16% | -0.31% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US2Y | 4.190% | 52.91 | neutral | -18.0 |
| 2 | US10Y_REAL | 2.350% | 51.02 | neutral | -8.0 |
| 3 | US5Y_REAL | 2.050% | 49.52 | neutral | -12.0 |
| 4 | US3M | 3.870% | 48.90 | neutral | -8.0 |
| 5 | US30Y_REAL | 2.950% | 47.45 | neutral | 0.0 |
| 6 | US5Y | 4.390% | 47.41 | neutral | -7.0 |
| 7 | US10Y | 4.690% | 46.30 | neutral | -2.0 |
| 8 | US30Y | 5.230% | 43.79 | bearish_duration | 6.0 |
| 9 | DE2Y | 2.860% | 40.16 | bearish_duration | -1.0 |
| 10 | DE5Y | 2.990% | 36.51 | bearish_duration | 3.0 |
| 11 | DE10Y | 3.260% | 34.01 | bearish_duration | 7.0 |
| 12 | DE30Y | 3.760% | 30.75 | bearish_duration | 10.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 50.0 | 16.0 |
| US_5s30s | 84.0 | 13.0 |
| US_3m10y | 82.0 | 6.0 |
| DE_2s10s | 40.0 | 8.0 |
| US_DE_2Y | 133.0 | -17.0 |
| US_DE_10Y | 143.0 | -9.0 |

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
