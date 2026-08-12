# Daily Multi-Horizon Stock Scanner — 2026-08-12

**Model:** 1.5.1-nokey-shared-pullback

## Interpretation

There is deliberately no single fixed investment horizon:

- **Short:** approximately 1–20 trading days
- **Swing:** approximately 1–3 months
- **Medium:** approximately 3–12 months
- **Long:** approximately 12–36 months

`consensus_score` is only a descriptive median of those horizon scores, not a universal buy signal.

## Market regime

- **EUROPE:** 83.5/100
- **US:** 85.1/100

Market regime is kept separate from company quality; it is intended for later exposure/position-sizing research, not to rewrite a company's quality score.

## Top eligible names

|   rank | symbol    | name                                                   | region   |   pullback_from_20d_high |   ret_5d |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------------------------------------|:---------|-------------------------:|---------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MSFT      | Microsoft Corporation                                  | US       |                     0.03 |     0.01 |             62.97 |         76.51 |         70.05 |          55.89 |        54.26 |           51.09 |             54.97 |                       94.28 |             63.5  |         6.85 |             90.38 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      2 | AVGO      | Broadcom Inc.                                          | US       |                     0.03 |    -0.01 |             62.08 |         60.89 |         54.52 |          63.28 |        63.32 |           72.46 |             59.78 |                       95.01 |             51.83 |         7.9  |             89.81 |                         86.25 |                 85.08 | long               |                 nan |                   nan |                  nan |
|      3 | AMZN      | Amazon.com, Inc.                                       | US       |                     0.06 |    -0.02 |             59.17 |         64.67 |         60.78 |          57.56 |        49.13 |           47.42 |             64.17 |                       89.91 |             37.51 |         6.98 |             89.85 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      4 | MA        | Mastercard Incorporated                                | US       |                     0.03 |    -0.02 |             54.09 |         57.32 |         56.97 |          49.37 |        51.22 |           76.59 |             52.33 |                       96.92 |             18.68 |         3.56 |             84.12 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      5 | NOVN.SW   | Novartis AG                                            | EUROPE   |                     0.05 |    -0    |             52.99 |         48.78 |         51.84 |          54.14 |        57.85 |           42.03 |             46.12 |                       80.33 |             76.75 |         1.94 |             88.7  |                         91.25 |                 83.54 | long               |                 nan |                   nan |                  nan |
|      6 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |                     0.08 |    -0.06 |             52.33 |         47.4  |         52.88 |          51.78 |        53.8  |           28.81 |             55.35 |                       76.23 |             80.8  |         4.37 |             88.21 |                         91.25 |                 83.54 | long               |                 nan |                   nan |                  nan |
|      7 | V         | Visa Inc.                                              | US       |                     0.03 |    -0.02 |             51.66 |         51.41 |         58.01 |          51.92 |        51.38 |           69.69 |             50.54 |                       97.11 |             29.33 |         2.97 |             84.14 |                         91.25 |                 85.08 | swing              |                 nan |                   nan |                  nan |
|      8 | AAPL      | Apple Inc.                                             | US       |                     0.11 |    -0.03 |             50.8  |         40.51 |         48.32 |          53.29 |        55.01 |           49.64 |             32.91 |                       94.05 |             62.17 |         4    |             90.35 |                         91.25 |                 85.08 | long               |                 nan |                   nan |                  nan |
|      9 | GOOGL     | Alphabet Inc.                                          | US       |                     0.09 |    -0.05 |             50.01 |         42.51 |         43.35 |          57.95 |        56.66 |           69.79 |             71.41 |                       95.51 |             30.1  |         6.22 |             90.52 |                         91.25 |                 85.08 | medium             |                 nan |                   nan |                  nan |
|     10 | NOVO-B.CO | Novo Nordisk A/S                                       | EUROPE   |                     0.11 |     0.02 |             45.38 |         41.65 |         42.38 |          48.38 |        55.09 |           48.52 |             47.12 |                       79.75 |             78.8  |         6.58 |             88.63 |                         91.25 |                 83.54 | long               |                 nan |                   nan |                  nan |
|     11 | NESN.SW   | Nestlé S.A.                                            | EUROPE   |                     0.08 |    -0.03 |             43.46 |         37.8  |         43.68 |          44.2  |        43.25 |           18.47 |             58.77 |                       88.45 |             67.37 |         2.8  |             89.68 |                         91.25 |                 83.54 | medium             |                 nan |                   nan |                  nan |
|     12 | NFLX      | Netflix, Inc.                                          | US       |                     0.03 |     0    |             41.78 |         47.27 |         28.68 |          36.29 |        48.38 |           60.04 |             37.35 |                       96.34 |             63.03 |         7.04 |             90.62 |                         91.25 |                 85.08 | long               |                 nan |                   nan |                  nan |
|     13 | MC.PA     | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |                     0.08 |    -0.03 |             36.59 |         31.78 |         34.79 |          38.39 |        47.22 |           32.39 |             48.84 |                       82.41 |             79.7  |         5.73 |             87.98 |                         83.75 |                 83.54 | long               |                 nan |                   nan |                  nan |
|     14 | COST      | Costco Wholesale Corporation                           | US       |                     0.03 |     0.01 |             34.89 |         46.23 |         34.15 |          33.86 |        35.63 |           38.15 |             43.55 |                       94.51 |             31.23 |         3.68 |             89.75 |                         86.25 |                 85.08 | short              |                 nan |                   nan |                  nan |

## Event watch

Upcoming earnings close enough to overwhelm the normal factor model are shown separately.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name                    | region   |   pullback_from_20d_high |   ret_5d |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|-------------------------:|---------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MSFT     | Microsoft Corporation   | US       |                     0.03 |     0.01 |             62.97 |         76.51 |         70.05 |          55.89 |        54.26 |           51.09 |             54.97 |                       94.28 |             63.5  |         6.85 |             90.38 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      2 | AVGO     | Broadcom Inc.           | US       |                     0.03 |    -0.01 |             62.08 |         60.89 |         54.52 |          63.28 |        63.32 |           72.46 |             59.78 |                       95.01 |             51.83 |         7.9  |             89.81 |                         86.25 |                 85.08 | long               |                 nan |                   nan |                  nan |
|      3 | AMZN     | Amazon.com, Inc.        | US       |                     0.06 |    -0.02 |             59.17 |         64.67 |         60.78 |          57.56 |        49.13 |           47.42 |             64.17 |                       89.91 |             37.51 |         6.98 |             89.85 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      4 | MA       | Mastercard Incorporated | US       |                     0.03 |    -0.02 |             54.09 |         57.32 |         56.97 |          49.37 |        51.22 |           76.59 |             52.33 |                       96.92 |             18.68 |         3.56 |             84.12 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      5 | NOVN.SW  | Novartis AG             | EUROPE   |                     0.05 |    -0    |             52.99 |         48.78 |         51.84 |          54.14 |        57.85 |           42.03 |             46.12 |                       80.33 |             76.75 |         1.94 |             88.7  |                         91.25 |                 83.54 | long               |                 nan |                   nan |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                    | region   |   pullback_from_20d_high |   ret_5d |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|-------------------------:|---------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MSFT     | Microsoft Corporation   | US       |                     0.03 |     0.01 |             62.97 |         76.51 |         70.05 |          55.89 |        54.26 |           51.09 |             54.97 |                       94.28 |             63.5  |         6.85 |             90.38 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      2 | AVGO     | Broadcom Inc.           | US       |                     0.03 |    -0.01 |             62.08 |         60.89 |         54.52 |          63.28 |        63.32 |           72.46 |             59.78 |                       95.01 |             51.83 |         7.9  |             89.81 |                         86.25 |                 85.08 | long               |                 nan |                   nan |                  nan |
|      3 | AMZN     | Amazon.com, Inc.        | US       |                     0.06 |    -0.02 |             59.17 |         64.67 |         60.78 |          57.56 |        49.13 |           47.42 |             64.17 |                       89.91 |             37.51 |         6.98 |             89.85 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      4 | MA       | Mastercard Incorporated | US       |                     0.03 |    -0.02 |             54.09 |         57.32 |         56.97 |          49.37 |        51.22 |           76.59 |             52.33 |                       96.92 |             18.68 |         3.56 |             84.12 |                         91.25 |                 85.08 | short              |                 nan |                   nan |                  nan |
|      5 | NOVN.SW  | Novartis AG             | EUROPE   |                     0.05 |    -0    |             52.99 |         48.78 |         51.84 |          54.14 |        57.85 |           42.03 |             46.12 |                       80.33 |             76.75 |         1.94 |             88.7  |                         91.25 |                 83.54 | long               |                 nan |                   nan |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.88
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.86

High correlation does not automatically mean a factor is wrong. It warns that the model may be counting the same underlying information more than once.

## Hard filters

- Market cap >= €1,000,000,000
- Price >= €5.0
- Median 20-day turnover >= €10,000,000
- Price history >= 230 observations
- Data confidence >= 55/100
- Maximum weekday-only stale-price lag: 3 business days
- Recent pullback gate: ON; when ON, price must be between 1.5% and 12.0% below its 20-day high, 5d return <= 2.0%, and 20d return >= -15.0%.

## Important remaining limitations

This live-forward scanner stores what it knew on each run. A historical backtest still needs genuine point-in-time historical constituents, delisted names, and information-availability timestamps. Re-downloading today's revised fundamentals for 2018 is not a valid point-in-time backtest.

`financials-lite` and `reit-lite` are deliberately conservative sector adaptations. A production bank model should use banking-specific capital/credit metrics; a production REIT model should use FFO/AFFO and NAV-style valuation.

Going-concern/accounting-restatement/legal-risk detection is not hard-coded from free text yet. Those require filing/news parsing with reliable timestamps.

The weekday stale-price check avoids weekend mistakes but is not yet exchange-holiday-aware.
