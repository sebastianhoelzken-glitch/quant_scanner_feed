# Daily Multi-Horizon Stock Scanner — 2026-08-12

**Model:** 1.5.0-nokey-shared

## Interpretation

There is deliberately no single fixed investment horizon:

- **Short:** approximately 1–20 trading days
- **Swing:** approximately 1–3 months
- **Medium:** approximately 3–12 months
- **Long:** approximately 12–36 months

`consensus_score` is only a descriptive median of those horizon scores, not a universal buy signal.

## Market regime

- **EUROPE:** 86.2/100
- **OTHER:** 95.8/100
- **US:** 81.4/100

Market regime is kept separate from company quality; it is intended for later exposure/position-sizing research, not to rewrite a company's quality score.

## Top eligible names

|   rank | symbol    | name                         | region   |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-----------------------------|:---------|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SU.PA     | Schneider Electric S.E.      | EUROPE   |             69.53 |         81.33 |         74.9  |          64.16 |        55.1  |           43.37 |             74.96 |                       88.59 |             47.58 |         5.46 |             89.69 |                         91.25 |                 86.22 | short              |                 nan |                   nan |                  nan |
|      2 | ASML.AS   | ASML Holding N.V.            | EUROPE   |             67.86 |         62.06 |         70.75 |          73.61 |        64.97 |           65.7  |             78.55 |                       87.66 |             43.78 |         7.49 |             89.58 |                         91.25 |                 86.22 | medium             |                 nan |                   nan |                  nan |
|      3 | NVDA      | NVIDIA Corporation           | US       |             66.61 |         68.33 |         60.31 |          64.9  |        68.94 |           90.22 |             51.71 |                       92.75 |             55    |         6.92 |             89.54 |                         86.25 |                 81.36 | long               |                 nan |                   nan |                  nan |
|      4 | LLY       | Eli Lilly and Company        | US       |             65.68 |         65.38 |         70.05 |          65.98 |        59.02 |           74.28 |             58.06 |                       88.01 |             21.39 |         5.25 |             89.62 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |
|      5 | JPM       | JP Morgan Chase & Co.        | US       |             65.52 |         65.98 |         73.63 |          65.05 |        63.68 |           47.91 |             71.71 |                       75.25 |             79.89 |         3    |             81.83 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |
|      6 | AVGO      | Broadcom Inc.                | US       |             64.58 |         65.68 |         57.73 |          65.06 |        64.11 |           72.46 |             59.78 |                       95.01 |             51.83 |         7.9  |             89.81 |                         86.25 |                 81.36 | short              |                 nan |                   nan |                  nan |
|      7 | MSFT      | Microsoft Corporation        | US       |             63.36 |         77.32 |         70.34 |          56.39 |        54.75 |           51.09 |             54.97 |                       94.28 |             63.5  |         6.95 |             90.38 |                         91.25 |                 81.36 | short              |                 nan |                   nan |                  nan |
|      8 | AMD       | Advanced Micro Devices, Inc. | US       |             61.54 |         43.34 |         62.79 |          71.52 |        60.29 |           51.45 |             77.94 |                       90.29 |             43.83 |         9.11 |             89.9  |                         91.25 |                 81.36 | medium             |                 nan |                   nan |                  nan |
|      9 | AMZN      | Amazon.com, Inc.             | US       |             61.05 |         70.8  |         63.97 |          58.13 |        48.76 |           47.42 |             64.17 |                       89.91 |             35.76 |         6.98 |             89.85 |                         91.25 |                 81.36 | short              |                 nan |                   nan |                  nan |
|     10 | AIR.PA    | Airbus SE                    | EUROPE   |             59.44 |         70.36 |         67.77 |          51.11 |        47.74 |           41.32 |             38.15 |                       77.35 |             49.77 |         5.55 |             88.34 |                         91.25 |                 86.22 | short              |                 nan |                   nan |                  nan |
|     11 | SAP.DE    | SAP SE                       | OTHER    |             56.44 |         76.4  |         59.36 |          45.63 |        53.53 |           44.2  |             39.29 |                       83.89 |             86.67 |         7.77 |             89.13 |                         91.25 |                 95.76 | short              |                 nan |                   nan |                  nan |
|     12 | MA        | Mastercard Incorporated      | US       |             54    |         57.52 |         56.78 |          49.23 |        51.22 |           76.59 |             52.33 |                       96.92 |             18.68 |         3.56 |             84.12 |                         91.25 |                 81.36 | short              |                 nan |                   nan |                  nan |
|     13 | VOLV-B.ST | AB Volvo (publ)              | EUROPE   |             52.69 |         47.54 |         53.58 |          52.01 |        53.38 |           28.81 |             55.35 |                       76.23 |             79.08 |         4.37 |             88.21 |                         91.25 |                 86.22 | swing              |                 nan |                   nan |                  nan |
|     14 | V         | Visa Inc.                    | US       |             51.91 |         52.01 |         57.87 |          51.82 |        51.28 |           69.69 |             50.54 |                       97.11 |             29.33 |         2.97 |             84.14 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |
|     15 | AAPL      | Apple Inc.                   | US       |             51.67 |         41.56 |         49.36 |          53.98 |        55.6  |           49.64 |             33.36 |                       94.47 |             62.17 |         3.91 |             90.4  |                         91.25 |                 81.36 | long               |                 nan |                   nan |                  nan |
|     16 | NOVN.SW   | Novartis AG                  | EUROPE   |             51.46 |         44.59 |         49.61 |          53.32 |        57.34 |           42.03 |             46.12 |                       80.33 |             77.2  |         1.94 |             88.7  |                         91.25 |                 86.22 | long               |                 nan |                   nan |                  nan |
|     17 | GOOGL     | Alphabet Inc.                | US       |             49.88 |         42.59 |         43.13 |          57.87 |        56.62 |           69.79 |             71.41 |                       95.51 |             30.1  |         6.22 |             90.52 |                         91.25 |                 81.36 | medium             |                 nan |                   nan |                  nan |
|     18 | NESN.SW   | Nestlé S.A.                  | EUROPE   |             43.98 |         37.67 |         44.08 |          44.74 |        43.88 |           18.47 |             58.77 |                       88.45 |             67.37 |         2.8  |             89.68 |                         91.25 |                 86.22 | medium             |                 nan |                   nan |                  nan |
|     19 | NOVO-B.CO | Novo Nordisk A/S             | EUROPE   |             43.85 |         40.36 |         40.38 |          47.31 |        54.46 |           48.52 |             47.12 |                       79.75 |             78.8  |         6.58 |             88.63 |                         91.25 |                 86.22 | long               |                 nan |                   nan |                  nan |
|     20 | NFLX      | Netflix, Inc.                | US       |             41.31 |         46.5  |         28.37 |          36.12 |        48.48 |           60.04 |             37.35 |                       96.34 |             63.03 |         7.04 |             90.62 |                         91.25 |                 81.36 | long               |                 nan |                   nan |                  nan |

## Event watch

Upcoming earnings close enough to overwhelm the normal factor model are shown separately.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name                    | region   |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SU.PA    | Schneider Electric S.E. | EUROPE   |             69.53 |         81.33 |         74.9  |          64.16 |        55.1  |           43.37 |             74.96 |                       88.59 |             47.58 |         5.46 |             89.69 |                         91.25 |                 86.22 | short              |                 nan |                   nan |                  nan |
|      2 | ASML.AS  | ASML Holding N.V.       | EUROPE   |             67.86 |         62.06 |         70.75 |          73.61 |        64.97 |           65.7  |             78.55 |                       87.66 |             43.78 |         7.49 |             89.58 |                         91.25 |                 86.22 | medium             |                 nan |                   nan |                  nan |
|      3 | NVDA     | NVIDIA Corporation      | US       |             66.61 |         68.33 |         60.31 |          64.9  |        68.94 |           90.22 |             51.71 |                       92.75 |             55    |         6.92 |             89.54 |                         86.25 |                 81.36 | long               |                 nan |                   nan |                  nan |
|      4 | LLY      | Eli Lilly and Company   | US       |             65.68 |         65.38 |         70.05 |          65.98 |        59.02 |           74.28 |             58.06 |                       88.01 |             21.39 |         5.25 |             89.62 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |
|      5 | JPM      | JP Morgan Chase & Co.   | US       |             65.52 |         65.98 |         73.63 |          65.05 |        63.68 |           47.91 |             71.71 |                       75.25 |             79.89 |         3    |             81.83 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                    | region   |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   estimate_confidence_score |   valuation_score |   risk_score |   data_confidence |   information_freshness_score |   market_regime_score | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|----------------------------:|------------------:|-------------:|------------------:|------------------------------:|----------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SU.PA    | Schneider Electric S.E. | EUROPE   |             69.53 |         81.33 |         74.9  |          64.16 |        55.1  |           43.37 |             74.96 |                       88.59 |             47.58 |         5.46 |             89.69 |                         91.25 |                 86.22 | short              |                 nan |                   nan |                  nan |
|      2 | ASML.AS  | ASML Holding N.V.       | EUROPE   |             67.86 |         62.06 |         70.75 |          73.61 |        64.97 |           65.7  |             78.55 |                       87.66 |             43.78 |         7.49 |             89.58 |                         91.25 |                 86.22 | medium             |                 nan |                   nan |                  nan |
|      3 | NVDA     | NVIDIA Corporation      | US       |             66.61 |         68.33 |         60.31 |          64.9  |        68.94 |           90.22 |             51.71 |                       92.75 |             55    |         6.92 |             89.54 |                         86.25 |                 81.36 | long               |                 nan |                   nan |                  nan |
|      4 | LLY      | Eli Lilly and Company   | US       |             65.68 |         65.38 |         70.05 |          65.98 |        59.02 |           74.28 |             58.06 |                       88.01 |             21.39 |         5.25 |             89.62 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |
|      5 | JPM      | JP Morgan Chase & Co.   | US       |             65.52 |         65.98 |         73.63 |          65.05 |        63.68 |           47.91 |             71.71 |                       75.25 |             79.89 |         3    |             81.83 |                         91.25 |                 81.36 | swing              |                 nan |                   nan |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.94
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.89

High correlation does not automatically mean a factor is wrong. It warns that the model may be counting the same underlying information more than once.

## Hard filters

- Market cap >= €1,000,000,000
- Price >= €5.0
- Median 20-day turnover >= €10,000,000
- Price history >= 230 observations
- Data confidence >= 55/100
- Maximum weekday-only stale-price lag: 3 business days

## Important remaining limitations

This live-forward scanner stores what it knew on each run. A historical backtest still needs genuine point-in-time historical constituents, delisted names, and information-availability timestamps. Re-downloading today's revised fundamentals for 2018 is not a valid point-in-time backtest.

`financials-lite` and `reit-lite` are deliberately conservative sector adaptations. A production bank model should use banking-specific capital/credit metrics; a production REIT model should use FFO/AFFO and NAV-style valuation.

Going-concern/accounting-restatement/legal-risk detection is not hard-coded from free text yet. Those require filing/news parsing with reliable timestamps.

The weekday stale-price check avoids weekend mistakes but is not yet exchange-holiday-aware.
