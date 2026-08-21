# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-21

**Model:** 1.6.1-nokey-broad-value-corrguard

## Coverage architecture

- Discovery target: approximately **2,000** liquid US/European equities.
- Deep fundamental/analyst enrichment cap: **1,000** candidates per run.
- The deep shortlist is deliberately seeded by value, pullback, momentum and the manual watchlist; it is not simply the largest companies by market cap.
- Market cap hard floor after EUR normalization: **€250,000,000**.

## Interpretation

There is deliberately no single fixed investment horizon:

- **Short:** approximately 1–20 trading days
- **Swing:** approximately 1–3 months
- **Medium:** approximately 3–12 months
- **Long:** approximately 12–36 months

`consensus_score` is only a descriptive median. `undervaluation_score` is a separate value signal and never rewrites the four horizon alpha scores.

## Market regime

- **EUROPE:** 86.4/100
- **OTHER:** 76.1/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HQL      | HQL    | US       |                0.58 |             77.56 |         81.44 |         78.6  |          76.52 |        72.77 |          nan    |            nan    |             69.43 |         2.01 |             55.57 | short              |               12.02 |                  3.27 |                  nan |
|      2 | MPC      | MPC    | US       |               86.18 |             77.14 |         77.53 |         77.9  |          76.76 |        72.65 |           85.78 |             59.19 |             51.77 |         4.12 |             67.5  | swing              |              nan    |                 -0.62 |                  nan |
|      3 | BAX      | BAX    | US       |               11.7  |             75.73 |         77.85 |         80.83 |          73.6  |        69.95 |           77.23 |             99.02 |             50.5  |         6.04 |             66.02 | swing              |               11.84 |                 -0.61 |                  nan |
|      4 | U        | U      | US       |               17.55 |             74.75 |         83.64 |         84.39 |          65.85 |        48.53 |           46.17 |             99.02 |             16.63 |         8.38 |             67.5  | swing              |                1.1  |                 -0.24 |                  nan |
|      5 | PGEN     | PGEN   | US       |                2.28 |             74.59 |         89.53 |         81.77 |          67.4  |        50.25 |           66.38 |            nan    |              1.33 |         7.71 |             62.84 | short              |                2.81 |                  1.75 |                  nan |
|      6 | GH       | GH     | US       |               19.3  |             74.38 |         73.75 |         77.17 |          75    |        70.01 |           63.08 |             66.67 |            nan    |         6.54 |             62.73 | swing              |               12.12 |                  0.14 |                  nan |
|      7 | CRGY     | CRGY   | US       |                4.65 |             74.1  |         81.03 |         70.2  |          72.87 |        75.34 |           71.13 |             82.97 |             84.95 |         6.23 |             67.05 | short              |               -1.35 |                nan    |                  nan |
|      8 | TALO     | TALO   | US       |                2.54 |             73.93 |         82.39 |         73.67 |          74.2  |        69.96 |           69.09 |             92.52 |             55.84 |         5.6  |             67.5  | short              |                1.38 |                nan    |                  nan |
|      9 | AMCX     | AMCX   | US       |                0.43 |             73.93 |         81.15 |         79.09 |          68.77 |        61.86 |           23.51 |             89.46 |             92.26 |         6.82 |             67.05 | short              |                5.54 |                  0.34 |                  nan |
|     10 | CCC      | CCC    | US       |                3.76 |             73.78 |         80.9  |         77.67 |          69.89 |        67.59 |           86.91 |             79.17 |             46.76 |         7.98 |             66.02 | short              |               -0.3  |                 -0.21 |                  nan |
|     11 | PSX      | PSX    | US       |               82.43 |             73.75 |         76.51 |         74.86 |          72.64 |        69.68 |           80.37 |             51.35 |             54.35 |         3.48 |             67.5  | short              |               -1.26 |                nan    |                  nan |
|     12 | FRO      | FRO    | US       |                8.31 |             73.08 |         73.43 |         70.84 |          73.97 |        72.72 |           84.77 |             61.64 |             54.67 |         5.25 |             67.5  | medium             |              nan    |                 -0.16 |                  nan |
|     13 | TWST     | TWST   | US       |                7.32 |             73.07 |         83.65 |         78.89 |          67.24 |        47.97 |           47.8  |             73.16 |              5.48 |         7.05 |             64.66 | short              |               -1.53 |                 -0.36 |                  nan |
|     14 | HAE      | HAE    | US       |                4.22 |             73.04 |         79.51 |         79.28 |          66.8  |        54.13 |           52.89 |             67.28 |             29.34 |         6.6  |             66.14 | short              |              nan    |                nan    |                  nan |
|     15 | FLYW     | FLYW   | US       |                1.95 |             73.02 |         77.29 |         74.55 |          71.49 |        65.81 |           73.26 |             74.26 |             47.46 |         5.93 |             67.05 | short              |                0.36 |                  0.12 |                  nan |
|     16 | NIQ      | NIQ    | US       |                4.59 |             72.93 |         82.96 |         84    |          62.9  |        50.68 |           37.5  |             97.67 |             41.78 |         9.05 |             66.02 | swing              |              nan    |                 -0.47 |                  nan |
|     17 | HPE      | HPE    | US       |               60    |             72.91 |         59.02 |         77.01 |          77.3  |        68.8  |           72.21 |             71.94 |             48.97 |         6.87 |             65.68 | medium             |               -1.41 |                 -1.66 |                  nan |
|     18 | HQH      | HQH    | US       |                1.17 |             72.9  |         76.99 |         74.23 |          71.56 |        70.88 |          nan    |            nan    |             69.26 |         1.81 |             55.57 | short              |               10.92 |                  2.96 |                  nan |
|     19 | SM       | SM     | US       |                7.67 |             72.15 |         75.29 |         65.03 |          69.3  |        75.01 |           82.11 |             38.97 |             86.95 |         7.07 |             66.48 | short              |                1.13 |                  0.23 |                  nan |
|     20 | BFLY     | BFLY   | US       |                2.09 |             72.06 |         77.21 |         77.31 |          66.91 |        48.25 |           46.84 |             71.81 |              8.66 |         8.45 |             63.64 | swing              |                3.91 |                 -0.26 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                          | EUROPE   |              222.26 |                  66.6  |                    71.02 |                 72.74 |              66.98 |                77.93 |                   22.07 |           94.33 |             50    |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                             | US       |               99.94 |                  68.46 |                    70.24 |                 70.93 |              69.3  |                72.63 |                   27.37 |           74.35 |            nan    |     nan     |         nan |       nan |      nan    |         6.93 |          4.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE                           | EUROPE   |                8.5  |                  63.51 |                    68.82 |                 70.51 |              68.21 |                78.54 |                   21.46 |          nan    |             83.46 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.86 |                  79.59 |                    67.35 |                 64.96 |              71.89 |                49.07 |                   50.93 |           52.63 |             57.5  |       0.257 |         nan |       nan |        1.54 |         6.49 |          4.76 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|          nan | JD       | JD                                | US       |               34.02 |                  62.25 |                    67.03 |                 68.69 |              66.44 |                74.35 |                   25.65 |          nan    |             82.35 |     nan     |         nan |       nan |      nan    |         6.96 |         19.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                            | EUROPE   |               37.92 |                  68.14 |                    66.45 |                 65.95 |              66.64 |                63.06 |                   36.94 |          nan    |             62.25 |     nan     |         nan |       nan |      nan    |         2.79 |          7.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                               | US       |              114.56 |                  62.39 |                    65.86 |                 67.06 |              63.35 |                71.88 |                   28.12 |           79.88 |             54.9  |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                           | EUROPE   |               37.32 |                  68.77 |                    65.82 |                 64.96 |              66.13 |                59.67 |                   40.33 |          nan    |             58.82 |     nan     |         nan |       nan |      nan    |         3.16 |          7.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | SAP.DE   | SAP SE                            | EUROPE   |              214.27 |                  82.12 |                    65.44 |                 58.58 |              70.94 |                45    |                   55    |           37.23 |             37.14 |       0.042 |         nan |       nan |       18.12 |        22.18 |         27.83 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                           | EUROPE   |               17.78 |                  58.46 |                    65.09 |                 67.56 |              59.5  |                76.08 |                   23.92 |           97.07 |             37.13 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                               | US       |               14.78 |                  57    |                    65.08 |                 67.78 |              60.96 |                76.29 |                   23.71 |           85.61 |             61.89 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                               | US       |               15.04 |                  67.31 |                    64.2  |                 63.7  |              60.92 |                63.86 |                   36.14 |           89.53 |              9.68 |     nan     |         nan |       nan |      nan    |         7.49 |          5.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                              | US       |              221.33 |                  66.35 |                    64.14 |                 63.61 |              62.96 |                63.68 |                   36.32 |           74.45 |             37.25 |     nan     |         nan |       nan |      nan    |        10.62 |         10.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                               | US       |               36.91 |                  53.93 |                    63.96 |                 67.39 |              59.06 |                76.31 |                   23.69 |           87.74 |             64.95 |     nan     |         nan |       nan |      nan    |        12.49 |         31.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                             | EUROPE   |               19.66 |                  63.73 |                    63.91 |                 63.89 |              62.44 |                68.46 |                   31.54 |           74.41 |             42.28 |     nan     |         nan |       nan |      nan    |         8.68 |         11.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.        | US       |                3.11 |                  72.76 |                    63.65 |                 62.6  |              65.26 |                39.58 |                   60.42 |           61.15 |             57.52 |       0.023 |         nan |       nan |        3.6  |         6.13 |          4.53 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                               | US       |                8.31 |                  56.08 |                    63.65 |                 66.42 |              59.43 |                71.63 |                   28.37 |           84.77 |             61.64 |     nan     |         nan |       nan |      nan    |        11.02 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                | US       |               62.56 |                  59.28 |                    63.57 |                 65.09 |              59.41 |                72.93 |                   27.07 |           88.28 |             36.03 |     nan     |         nan |       nan |      nan    |        12.12 |         14.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                               | US       |                2.73 |                  58.76 |                    63.41 |                 65.35 |              58.99 |                69.25 |                   30.75 |           88.77 |             42.16 |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                              | US       |                4.65 |                  55.81 |                    63.28 |                 65.8  |              61.02 |                69.71 |                   30.29 |           71.13 |             82.97 |     nan     |         nan |       nan |      nan    |         6.43 |        172.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                          | EUROPE   |              222.26 |                  66.6  |                    71.02 |                 72.74 |              66.98 |                77.93 |                   22.07 |           94.33 |             50    |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                             | US       |               99.94 |                  68.46 |                    70.24 |                 70.93 |              69.3  |                72.63 |                   27.37 |           74.35 |            nan    |     nan     |         nan |       nan |      nan    |         6.93 |          4.13 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAH3.DE  | PAH3.DE                           | EUROPE   |                8.5  |                  63.51 |                    68.82 |                 70.51 |              68.21 |                78.54 |                   21.46 |          nan    |             83.46 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | JD       | JD                                | US       |               34.02 |                  62.25 |                    67.03 |                 68.69 |              66.44 |                74.35 |                   25.65 |          nan    |             82.35 |     nan     |         nan |       nan |      nan    |         6.96 |         19.61 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                               | US       |               14.78 |                  57    |                    65.08 |                 67.78 |              60.96 |                76.29 |                   23.71 |           85.61 |             61.89 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                           | EUROPE   |               17.78 |                  58.46 |                    65.09 |                 67.56 |              59.5  |                76.08 |                   23.92 |           97.07 |             37.13 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                               | US       |               36.91 |                  53.93 |                    63.96 |                 67.39 |              59.06 |                76.31 |                   23.69 |           87.74 |             64.95 |     nan     |         nan |       nan |      nan    |        12.49 |         31.35 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                               | US       |              114.56 |                  62.39 |                    65.86 |                 67.06 |              63.35 |                71.88 |                   28.12 |           79.88 |             54.9  |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                               | US       |                8.31 |                  56.08 |                    63.65 |                 66.42 |              59.43 |                71.63 |                   28.37 |           84.77 |             61.64 |     nan     |         nan |       nan |      nan    |        11.02 |         10.94 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                            | EUROPE   |               37.92 |                  68.14 |                    66.45 |                 65.95 |              66.64 |                63.06 |                   36.94 |          nan    |             62.25 |     nan     |         nan |       nan |      nan    |         2.79 |          7.25 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                              | US       |                4.65 |                  55.81 |                    63.28 |                 65.8  |              61.02 |                69.71 |                   30.29 |           71.13 |             82.97 |     nan     |         nan |       nan |      nan    |         6.43 |        172.63 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                               | US       |                2.73 |                  58.76 |                    63.41 |                 65.35 |              58.99 |                69.25 |                   30.75 |           88.77 |             42.16 |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ET       | ET                                | US       |               62.56 |                  59.28 |                    63.57 |                 65.09 |              59.41 |                72.93 |                   27.07 |           88.28 |             36.03 |     nan     |         nan |       nan |      nan    |        12.12 |         14.53 |         nan |                 nan |              nan |                   5 |                  0.26 |
|            1 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.86 |                  79.59 |                    67.35 |                 64.96 |              71.89 |                49.07 |                   50.93 |           52.63 |             57.5  |       0.257 |         nan |       nan |        1.54 |         6.49 |          4.76 |         nan |                 nan |              nan |                   9 |                  0.47 |
|          nan | VOW3.DE  | VOW3.DE                           | EUROPE   |               37.32 |                  68.77 |                    65.82 |                 64.96 |              66.13 |                59.67 |                   40.33 |          nan    |             58.82 |     nan     |         nan |       nan |      nan    |         3.16 |          7.14 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | GL9.IR   | GL9.IR                            | EUROPE   |                5.35 |                  41.83 |                    59.21 |                 64.87 |              51.25 |                83.51 |                   16.49 |           97.47 |             61.03 |     nan     |         nan |       nan |      nan    |        15.17 |         26.33 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | EVK.DE   | EVK.DE                            | EUROPE   |                8.6  |                  54.99 |                    62.23 |                 64.33 |              61.46 |                77.41 |                   22.59 |          nan    |             79.29 |     nan     |         nan |       nan |      nan    |        12.31 |         71    |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                              | US       |                2.88 |                  58.48 |                    62.65 |                 64.11 |              60.2  |                68.37 |                   31.63 |           75.44 |             57.84 |     nan     |         nan |       nan |      nan    |         8.44 |         11.83 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                             | EUROPE   |               19.66 |                  63.73 |                    63.91 |                 63.89 |              62.44 |                68.46 |                   31.54 |           74.41 |             42.28 |     nan     |         nan |       nan |      nan    |         8.68 |         11.15 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                               | US       |               86.18 |                  50.07 |                    60.38 |                 63.89 |              55.21 |                73.57 |                   26.43 |           85.78 |             59.19 |     nan     |         nan |       nan |      nan    |        11.12 |         12.52 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.7  |                     0.07 |    -0.02 |      0.22 |                  69.42 |                        81.13 |         77.85 |         80.83 |          73.6  |        69.95 |           77.23 |             99.02 |         6.04 |
|               2 | GENI     | GENI     | US       |                1.82 |                     0.05 |     0    |      0.23 |                  69.29 |                        77.05 |         77.72 |         76.15 |          67.89 |        67.66 |           64.71 |             99.02 |         9.14 |
|               3 | RBRK     | RBRK     | US       |               17.19 |                     0.07 |    -0.07 |      0.34 |                  81.3  |                        75.95 |         73.02 |         78.8  |          63.31 |        46.25 |           54.31 |             89.95 |         8.18 |
|               4 | SNOW     | SNOW     | US       |               95.39 |                     0.05 |    -0.05 |      0.21 |                  80.22 |                        75.33 |         69.79 |         80.8  |          65.95 |        45.72 |           43.24 |             94.98 |         8.89 |
|               5 | SYENS.BR | SYENS.BR | EUROPE   |                8.08 |                     0.04 |    -0.01 |      0.13 |                  64.27 |                        74.92 |         74.18 |         69.18 |          62.55 |        59.35 |           73.13 |             90.44 |         5.13 |
|               6 | WDAY     | WDAY     | US       |               41.75 |                     0.04 |    -0.04 |      0.54 |                  77.06 |                        74.82 |         76.15 |         73.71 |          62.21 |        57.52 |           71.71 |             72.3  |         8.5  |
|               7 | ZETA     | ZETA     | US       |                5.95 |                     0.06 |    -0.06 |      0.44 |                  85.32 |                        74.7  |         76.54 |         78.65 |          65.15 |        50.59 |           49.72 |             84.19 |         7.62 |
|               8 | NTAP     | NTAP     | US       |               32.41 |                     0.07 |    -0.06 |      0.17 |                  79.55 |                        74.34 |         65.55 |         73.96 |          71.97 |        64.97 |           89.3  |             50.49 |         6.34 |
|               9 | BCRX     | BCRX     | US       |                2.11 |                     0.09 |    -0.02 |      0.03 |                  54.98 |                        73.68 |         56.95 |         68.02 |          75.97 |        76.79 |           85.99 |             94.85 |         5.92 |
|              10 | HPE      | HPE      | US       |               60    |                     0.12 |    -0.12 |      0.11 |                  62.33 |                        73.09 |         59.02 |         77.01 |          77.3  |        68.8  |           72.21 |             71.94 |         6.87 |
|              11 | SMWB     | SMWB     | US       |                0.62 |                     0.09 |    -0.09 |      0.35 |                  74    |                        72.89 |         71.89 |         80.33 |          61.39 |        41.63 |           34.67 |             97.92 |         9.45 |
|              12 | PLTR     | PLTR     | US       |              358.1  |                     0.03 |    -0.03 |      0.41 |                  62.48 |                        72.41 |         75.59 |         63.7  |          56.51 |        53.53 |           90.41 |             47.79 |         8.42 |
|              13 | MPC      | MPC      | US       |               86.18 |                     0.02 |     0.01 |      0.15 |                  46.29 |                        71.93 |         77.53 |         77.9  |          76.76 |        72.65 |           85.78 |             59.19 |         4.12 |
|              14 | KRX.IR   | KRX.IR   | EUROPE   |               18.12 |                     0.03 |    -0.02 |      0.34 |                  61.51 |                        71.64 |         76.24 |         65.75 |          60.49 |        59.9  |           95.93 |             34.07 |         5.25 |
|              15 | DK       | DK       | US       |                3.36 |                     0.06 |    -0.06 |     -0.01 |                  84.46 |                        71.38 |         54.58 |         73.28 |          70.58 |        57.58 |           56.23 |             72.18 |         6.66 |
|              16 | COUR     | COUR     | US       |                1.44 |                     0.05 |     0.01 |      0.09 |                  67.33 |                        71.13 |         65.69 |         60.49 |          61.21 |        68.47 |           66.66 |             99.02 |         8.22 |
|              17 | TCPC     | TCPC     | US       |                0.29 |                     0.04 |    -0.04 |      0.29 |                  75.72 |                        71.04 |         71.44 |         59.55 |          55.07 |        59.68 |           49.1  |             94.24 |         6.98 |
|              18 | TPG      | TPG      | US       |               17.25 |                     0.06 |    -0.06 |      0.24 |                  86.6  |                        70.68 |         71.62 |         66.08 |          55.97 |        51.73 |           52.61 |             75.74 |         6.44 |
|              19 | NWL      | NWL      | US       |                2.11 |                     0.09 |    -0.06 |      0.15 |                  67.36 |                        70.66 |         63.35 |         77.3  |          67.4  |        61.78 |           37.19 |             96.45 |         8.2  |
|              20 | JHX      | JHX      | US       |               14.93 |                     0.03 |    -0.03 |      0.16 |                  65.82 |                        70.57 |         73.09 |         74.35 |          65.58 |        57.08 |           58.71 |             78.55 |         6.55 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4499.25 |             58.26 |         54.98 |         51.76 |          61.55 |        68.46 |           90.22 |             54.71 |             55    |         6.01 |             89.48 | long               |                0.81 |                 -1.11 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1483.58 |             45.99 |         28.39 |         37.97 |          54.01 |        60.7  |           72.46 |             50.61 |             56    |         6.55 |             89.81 | long               |               -4.3  |                 -1.66 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             44.22 |         38.64 |         40.4  |          48.04 |        57.11 |           61.11 |             39.53 |             66.03 |         3.95 |             75.81 | long               |               -5.59 |                 -1.37 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    518 | TLRY     | TLRY   | US       |                0.55 |             47.67 |         67.25 |         43.93 |          44.79 |        50.55 |           38.42 |             90.69 |             64.63 |         8.18 |             67.5  | short              |               17.84 |                  3.77 |                  nan |
|    511 | STLA     | STLA   | US       |               16.97 |             47.86 |         40.13 |         41.17 |          54.55 |        68.76 |           63.48 |             86.37 |             95.88 |         7.34 |             64.41 | long               |               16.53 |                  3.35 |                  nan |
|      1 | HQL      | HQL    | US       |                0.58 |             77.56 |         81.44 |         78.6  |          76.52 |        72.77 |          nan    |            nan    |             69.43 |         2.01 |             55.57 | short              |               12.02 |                  3.27 |                  nan |
|    608 | LI       | LI     | US       |               10.85 |             42.54 |         53.78 |         41.67 |          41.78 |        43.3  |           19.92 |             95.59 |             61.04 |         6.79 |             67.5  | short              |               19.43 |                  3.11 |                  nan |
|    581 | ALIT     | ALIT   | US       |                0.54 |             44.4  |         26.32 |         40.12 |          48.68 |        58.92 |           38.93 |             86.03 |             98.14 |         9.81 |             67.5  | long               |               16.01 |                  3.02 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    456 | TKA.DE    | TKA.DE    | EUROPE   |                7.88 |             49.91 |         49.84 |         45.9  |          49.97 |        56.66 |          nan    |             17.89 |             64.89 |         6.63 |             64.66 | long               |              -26.46 |                 -5.59 |                  nan |
|    702 | NWL.MI    | NWL.MI    | EUROPE   |                0.66 |             29.68 |         31.53 |         24.08 |          27.83 |        41.18 |           42.39 |              1.1  |             66.15 |         4.27 |             64.66 | long               |              -17.43 |                 -4.36 |                  nan |
|    211 | AKER.OL   | AKER.OL   | EUROPE   |                9.85 |             59.78 |         77.08 |         63.38 |          56.17 |        38.06 |           36.81 |            nan    |             11.87 |         3.88 |             65.68 | short              |              -18.59 |                 -4.1  |                  nan |
|    640 | KSS       | KSS       | US       |                1.68 |             40.89 |         23.97 |         40.39 |          41.4  |        52.99 |          nan    |              7.6  |             65.78 |         8.37 |             64.66 | long               |              -12.52 |                 -3.75 |                  nan |
|    636 | INDU-A.ST | INDU-A.ST | EUROPE   |               20.29 |             41.11 |         35.21 |         41.19 |          46.67 |        41.03 |           40.95 |            nan    |             25.59 |         1.8  |             65.68 | medium             |              -16.9  |                 -3.6  |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `relative_63d_rank` vs `sector_score`: r=0.94
- `ret_63d_rank` vs `sector_score`: r=0.94
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.89

High correlation does not automatically mean a factor is wrong. It warns that the model may be counting the same underlying information more than once.

## Hard filters

- Market cap >= €250,000,000
- Price >= €2.0
- Median 20-day turnover >= €1,000,000
- Price history >= 230 observations
- Data confidence >= 55/100
- Maximum weekday-only stale-price lag: 3 business days
- Global recent-pullback gate: **OFF** in v1.6; pullbacks have their own ranking.

## Value variables currently used when available

Forward/trailing P/E, earnings yields, EV/EBITDA, EV/EBIT, EBIT yield, EV/revenue, P/S, P/B, price/tangible-book, FCF yield, FCF/EV, CFO yield, PEG, forward-P/E-to-growth, shareholder/net-payout yield, dividend yield and net-cash yield. Value-trap protection separately uses ROIC/profitability/FCF quality, cash conversion, accruals, earnings stability, leverage, interest coverage, current/quick ratio, Altman-style Z score, revisions, dilution/SBC and risk.

## Important limitations

The discovery layer can consider ~2,000 names, but free public endpoints make full deep enrichment of every one of them unreliable/slow; the expensive factor model therefore runs on a diversified shortlist. A name outside that shortlist can be reconsidered on a later run as its price/value screen changes.

Historical self-valuation percentiles and a genuinely point-in-time historical DCF are **not** fabricated from today's revised fundamentals. Financials/insurers/REITs remain `lite` until sector-specific CET1/NIM/credit, solvency/combined-ratio, or FFO/AFFO/NAV metrics are available.


## Eligibility diagnostics

- Deep analyzed: **1000**
- Excluded by hard/data filters: **282**
- Event watch (otherwise eligible): **3**
- Final eligible: **715**
- Eligible change vs previous stored run: **+21**

Top exclusion categories:
- liquidity: 230
- price: 167
- market_cap: 156
- price_history: 20
- data_confidence: 16
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BAX | 3 |  | 1 |  | 2 | main,pullback |
| HRTG | 54 | 1 | 52 | 1 | 1 | value,quality_value |
| PARR | 62 | 3 |  | 2 | 1 | value,quality_value |
| JPM | 235 | 4 | 117 | 3 | 1 | value,quality_value |
| MSFT | 282 | 6 | 68 | 6 | 1 | value,quality_value |
| V | 309 | 7 |  | 5 | 1 | value,quality_value |
| SAP.DE | 347 | 2 |  | 4 | 1 | value,quality_value |
| NFLX | 615 | 8 |  | 8 | 1 | value,quality_value |
| ORCL | 644 | 5 | 274 | 10 | 1 | value,quality_value |
| HQL | 1 |  |  |  | 1 | main |
| MPC | 2 |  | 13 |  | 1 | main |
| U | 4 |  |  |  | 1 | main |
| PGEN | 5 |  |  |  | 1 | main |
| GH | 6 |  |  |  | 1 | main |
| CRGY | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (U, PGEN, GH, CRGY, TALO, CCC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (SYENS.BR, BCRX, HPE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | JPM | value+pullback | 62.82 | 64.05 | 69.18 | 55.26 | 58.89 | 60.66 | 58.71 |
| 2 | HRTG | value+pullback | 62.69 | 79.59 | 61.41 | 52.63 | 57.50 | 49.07 | 68.78 |
| 3 | MSFT | value+pullback | 59.40 | 58.21 | 74.85 | 51.09 | 58.85 | 48.38 | 57.02 |
| 4 | GL9.IR | pullback | 56.73 | 41.83 | 77.21 | 97.47 | 61.03 | 83.51 | 63.98 |
| 5 | ORCL | value+pullback | 55.78 | 69.90 | 75.23 | 35.14 | 45.58 | 30.86 | 40.42 |
| 6 | BAX | pullback | 54.50 | 47.04 | 69.42 | 77.23 | 99.02 | 78.31 | 75.73 |
| 7 | OUT1V.HE | pullback | 53.37 | 54.04 | 68.72 | 71.17 | 99.02 | 78.06 | 59.96 |
| 8 | ERBAG.PR | pullback | 52.90 | 36.31 | 62.62 | 94.46 |  | 90.38 | 65.41 |
| 9 | PDI | pullback | 52.62 | 56.69 | 84.60 |  |  | 94.85 | 29.43 |
| 10 | BCRX | pullback | 52.45 | 52.74 | 54.98 | 85.99 | 94.85 | 81.59 | 72.00 |
| 11 | AALB.AS | pullback | 52.00 | 46.94 | 80.61 | 74.96 | 62.99 | 71.51 | 60.96 |
| 12 | NTAP | pullback | 51.96 | 39.36 | 79.55 | 89.30 | 50.49 | 68.14 | 68.76 |
| 13 | MT.AS | pullback | 51.63 | 51.03 | 80.87 | 75.67 | 63.85 | 68.40 | 62.51 |
| 14 | AMV0.DE | pullback | 51.63 | 59.92 | 47.05 | 92.45 | 92.16 | 83.90 | 59.98 |
| 15 | MC.PA | value+pullback | 51.33 | 61.34 | 61.22 | 31.13 | 43.69 | 42.92 | 30.96 |
| 16 | GALD.SW | pullback | 51.22 | 31.20 | 78.50 | 78.35 | 55.64 | 71.41 | 49.53 |
| 17 | SYENS.BR | pullback | 51.14 | 44.68 | 64.27 | 73.13 | 90.44 | 75.30 | 65.86 |
| 18 | BEN | pullback | 51.04 | 57.00 | 66.99 | 85.61 | 61.89 | 76.29 | 67.36 |
| 19 | NOD.OL | pullback | 50.54 | 35.55 | 79.11 | 74.97 | 61.15 | 67.03 | 46.36 |
| 20 | COUR | pullback | 50.47 | 56.58 | 67.33 | 66.66 | 99.02 | 68.69 | 63.45 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 8/10 | 9/10 | 7/10 | 1/10 | 66.5 | 4 / 6 |
| Top 25 | 23/25 | 22/25 | 24/25 | 21/25 | 2/25 | 66.5 | 6 / 19 |
| Top 50 | 47/50 | 46/50 | 49/50 | 44/50 | 2/50 | 66.5 | 14 / 36 |

Top-10 market-cap mix: micro_250m_1b=2, small_1_5b=4, mid_5_20b=3, large_20_100b=1
Top-10 sparse-data names: HQL (missing quality,revisions; conf=55.6)
