# Cross-Asset Daily Context

**Model:** 0.1-cross-asset-context
**Semantics:** diagnostic-only; stock Exact scores/ranks are unchanged.

## Equity context: NEUTRAL
Context score: **44.527385996701376**

## FX ranking

| Rank | Pair | Score | Signal | 5d | 20d | 63d |
|---:|:---|---:|:---|---:|---:|---:|
| 1 | USDCHF | 86.12 | long | 1.26% | 0.64% | 3.26% |
| 2 | EURCHF | 81.25 | long | 0.47% | 0.85% | 2.71% |
| 3 | AUDUSD | 78.62 | long | -0.52% | 1.36% | 0.09% |
| 4 | USDJPY | 60.54 | long | 0.33% | 1.27% | -0.17% |
| 5 | GBPJPY | 58.96 | long | -0.75% | 1.31% | -0.05% |
| 6 | USDCAD | 58.67 | long | 0.45% | -0.87% | 0.31% |
| 7 | EURJPY | 55.29 | long | -0.45% | 1.48% | -0.70% |
| 8 | GBPUSD | 44.79 | short | -1.08% | 0.03% | 0.12% |
| 9 | EURGBP | 33.92 | short | 0.30% | 0.17% | -0.65% |
| 10 | EURUSD | 29.33 | short | -0.78% | 0.21% | -0.53% |

## Rates / duration ranking

| Rank | Instrument | Yield | Score | Signal | 20d bp |
|---:|:---|---:|---:|:---|---:|
| 1 | US30Y_REAL | 2.980% | 39.32 | bearish_duration | 2.0 |
| 2 | US3M | 3.920% | 39.17 | bearish_duration | 3.0 |
| 3 | US30Y | 5.270% | 35.84 | bearish_duration | 10.0 |
| 4 | US10Y_REAL | 2.450% | 35.06 | bearish_duration | 4.0 |
| 5 | US5Y_REAL | 2.190% | 33.25 | bearish_duration | 4.0 |
| 6 | US10Y | 4.790% | 32.95 | bearish_duration | 16.0 |
| 7 | US2Y | 4.390% | 30.91 | bearish_duration | 21.0 |
| 8 | US5Y | 4.540% | 30.79 | bearish_duration | 21.0 |
| 9 | DE2Y | 3.010% | 20.12 | bearish_duration | 29.0 |
| 10 | DE30Y | 3.850% | 19.16 | bearish_duration | 24.0 |
| 11 | DE10Y | 3.390% | 17.35 | bearish_duration | 29.0 |
| 12 | DE5Y | 3.130% | 17.30 | bearish_duration | 30.0 |

## Curves / sovereign spreads

| Spread | Value bp | 20d bp |
|:---|---:|---:|
| US_2s10s | 40.0 | -5.0 |
| US_5s30s | 73.0 | -11.0 |
| US_3m10y | 87.0 | 13.0 |
| DE_2s10s | 38.0 | 0.0 |
| US_DE_2Y | 138.0 | -8.0 |
| US_DE_10Y | 140.0 | -13.0 |

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
