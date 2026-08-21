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

- **EUROPE:** 86.5/100
- **OTHER:** 74.2/100
- **US:** 83.8/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC    | US       |               86.18 |             79.76 |         79.63 |         81.16 |          79.88 |        76.91 |           85.79 |             61.02 |             61.27 |         4.1  |             67.5  | swing              |              nan    |                 -0.09 |                  nan |
|      2 | CRGY     | CRGY   | US       |                4.65 |             78.07 |         82.81 |         73.04 |          75.99 |        80.15 |           72.51 |             83.54 |             95.88 |         6.22 |             67.05 | short              |                2.62 |                nan    |                  nan |
|      3 | BAX      | BAX    | US       |               11.7  |             77.93 |         79.53 |         83.27 |          76.33 |        74.69 |           78.74 |             96.61 |             61.71 |         5.99 |             66.02 | swing              |               14.04 |                 -0.17 |                  nan |
|      4 | PGEN     | PGEN   | US       |                2.28 |             77.57 |         91.71 |         85.16 |          69.99 |        52.6  |           67.37 |            nan    |              1.85 |         7.71 |             62.84 | short              |                5.79 |                  2.35 |                  nan |
|      5 | PSX      | PSX    | US       |               82.43 |             76.94 |         78.53 |         78.08 |          75.8  |        74.16 |           80.37 |             53.15 |             64.83 |         3.46 |             67.5  | short              |                1.93 |                nan    |                  nan |
|      6 | CCC      | CCC    | US       |                3.76 |             76.88 |         82.86 |         80.81 |          72.95 |        72.08 |           86.86 |             80.02 |             57.48 |         7.95 |             66.02 | short              |                2.8  |                  0.41 |                  nan |
|      7 | GH       | GH     | US       |               19.3  |             76.38 |         75.69 |         80.04 |          77.07 |        71.93 |           62.37 |             68.4  |            nan    |         6.51 |             62.73 | swing              |               14.12 |                  0.54 |                  nan |
|      8 | HPE      | HPE    | US       |               60    |             76.38 |         60.98 |         80.1  |          80.08 |        72.69 |           70.57 |             73.37 |             59.63 |         6.85 |             65.68 | swing              |                2.07 |                 -0.97 |                  nan |
|      9 | TALO     | TALO   | US       |                2.54 |             76.3  |         83.86 |         75.87 |          76.73 |        74.38 |           69.54 |             91.65 |             67.85 |         5.58 |             67.5  | short              |                3.74 |                nan    |                  nan |
|     10 | U        | U      | US       |               17.55 |             76.12 |         85.08 |         86.32 |          67.15 |        50.35 |           45.17 |             96.49 |             20.65 |         8.37 |             67.5  | swing              |                2.47 |                  0.04 |                  nan |
|     11 | FRO      | FRO    | US       |                8.31 |             75.96 |         75.05 |         73.49 |          76.87 |        77.11 |           85.53 |             63.2  |             65.14 |         5.24 |             67.5  | long               |              nan    |                  0.42 |                  nan |
|     12 | HAE      | HAE    | US       |                4.22 |             75.65 |         81.63 |         82.48 |          69.68 |        57.69 |           52.94 |             69.13 |             35.98 |         6.57 |             66.14 | swing              |              nan    |                nan    |                  nan |
|     13 | TWST     | TWST   | US       |                7.32 |             75.6  |         85.69 |         81.76 |          69.44 |        50.2  |           47.57 |             74.46 |              7.9  |         7.04 |             64.66 | short              |                1    |                  0.14 |                  nan |
|     14 | GENI     | GENI   | US       |                1.82 |             75.42 |         79.4  |         78.65 |          70.56 |        72.2  |           66.01 |             96.73 |             82.81 |         9.13 |             67.5  | short              |               13.53 |                 -0.45 |                  nan |
|     15 | NIQ      | NIQ    | US       |                4.59 |             75.36 |         85.47 |         86.42 |          65.25 |        54.48 |           37.91 |             95.76 |             50.68 |         9.05 |             66.02 | swing              |              nan    |                  0.02 |                  nan |
|     16 | FLYW     | FLYW   | US       |                1.95 |             75.32 |         78.76 |         76.84 |          73.8  |        69.4  |           72.01 |             75.54 |             58.09 |         5.97 |             67.05 | short              |                2.66 |                  0.58 |                  nan |
|     17 | DHT      | DHT    | US       |                2.73 |             75.14 |         77.74 |         70.39 |          72.84 |        77.43 |           89.26 |             43.7  |             72.02 |         4.29 |             67.5  | short              |                2.29 |                  0.79 |                  nan |
|     18 | SBLK     | SBLK   | US       |                2.88 |             74.79 |         76.73 |         70.36 |          72.86 |        77.79 |           75.23 |             59.81 |             89.1  |         3.9  |             67.16 | long               |                0.9  |                nan    |                  nan |
|     19 | SM       | SM     | US       |                7.67 |             74.54 |         76.98 |         67.76 |          72.1  |        79    |           82.18 |             40.92 |             96.45 |         7.03 |             66.48 | long               |                3.52 |                  0.71 |                  nan |
|     20 | BFLY     | BFLY   | US       |                2.09 |             74.3  |         79.32 |         80.27 |          69.29 |        50.83 |           46.74 |             73.24 |             12.1  |         8.43 |             63.64 | swing              |                6.15 |                  0.19 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                           | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                  | EUROPE   |                3.26 |                  76.12 |                    75.65 |                 77.11 |              76.21 |                86.75 |                   13.25 |           84.64 |             57.92 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc. | US       |                0.59 |                  70.74 |                    74.23 |                 77.11 |              73.18 |                82.96 |                   17.04 |           87.49 |             73.08 |       0.178 |         nan |       nan |        4.21 |         2.81 |          5.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE      | StoneCo Ltd.                   | OTHER    |                1.81 |                  77.2  |                    73.56 |                 73.16 |              72.4  |                72.22 |                   27.78 |           87.42 |             38.23 |       0.645 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PARR      | Par Pacific Holdings, Inc.     | US       |                3.11 |                  71.87 |                    71.22 |                 72.51 |              70.69 |                69.64 |                   30.36 |           80.43 |             64.12 |       0.023 |         nan |       nan |        3.6  |         6.13 |          4.53 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                       | EUROPE   |              222.26 |                  65.32 |                    70.47 |                 72.4  |              66.31 |                78.35 |                   21.65 |           93.92 |             51.82 |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | 0Q2N.IL   | K+S Aktiengesellschaft         | OTHER    |                3.02 |                  73.06 |                    70.2  |                 68.71 |              72.36 |                69.53 |                   30.47 |           60.4  |            nan    |       0.246 |         nan |       nan |        1.54 |       nan    |          2.81 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | NWL.MI    | NewPrinces S.p.A.              | EUROPE   |                0.66 |                  71.08 |                    70.01 |                 71.59 |              70.51 |                76.35 |                   23.65 |           79.08 |             55.9  |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | VOLV-B.ST | AB Volvo (publ)                | EUROPE   |               62.36 |                  77.65 |                    69.64 |                 66.53 |              72.4  |                59.95 |                   40.05 |           56.18 |             57    |       0.035 |         nan |       nan |       16.11 |        13.65 |         19.3  |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAH3.DE   | PAH3.DE                        | EUROPE   |                8.5  |                  63.54 |                    68.98 |                 70.71 |              68.35 |                78.89 |                   21.11 |          nan    |             84.02 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS       | IHS Holding Limited            | OTHER    |                2.42 |                  71.89 |                    68.33 |                 68.93 |              71.23 |                62.26 |                   37.74 |           59.36 |             82.65 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | DXC       | DXC Technology Company         | US       |                1.46 |                  83.49 |                    68.13 |                 63.1  |              72.95 |                51.46 |                   48.54 |           49.83 |             35.68 |       0.513 |         nan |       nan |        3.07 |         3.62 |         14.66 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY       | BMY                            | US       |              114.56 |                  62.78 |                    66.8  |                 68.19 |              64.09 |                73.38 |                   26.62 |           81.64 |             56.78 |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE    | VOW.DE                         | EUROPE   |               37.92 |                  68.06 |                    66.8  |                 66.43 |              66.93 |                64.15 |                   35.85 |          nan    |             63.8  |     nan     |         nan |       nan |      nan    |         2.79 |          7.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | UNIT      | Uniti Group Inc.               | US       |                2.09 |                  80.26 |                    66.63 |                 63.56 |              68.79 |                44.64 |                   55.36 |           65.19 |             29.68 |      -0.106 |         nan |       nan |        9.11 |       -14.17 |          2.69 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BEN       | BEN                            | US       |               14.78 |                  58.02 |                    66.54 |                 69.41 |              62.19 |                78.17 |                   21.83 |           88.25 |             63.44 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE   | VOW3.DE                        | EUROPE   |               37.32 |                  68.81 |                    66.31 |                 65.6  |              66.57 |                60.9  |                   39.1  |          nan    |             60.65 |     nan     |         nan |       nan |      nan    |         3.16 |          7.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | GSL       | Global Ship Lease Inc New      | OTHER    |                1.34 |                  68.84 |                    66.17 |                 66.23 |              66.04 |                71.05 |                   28.95 |           76.3  |             36.8  |       0.083 |         nan |       nan |        3.74 |         4.89 |          4.24 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT       | DHT                            | US       |                2.73 |                  62.04 |                    65.67 |                 67.29 |              61.64 |                70.01 |                   29.99 |           89.26 |             43.7  |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | RCI       | Rogers Communications Inc.     | OTHER    |               16.82 |                  65.72 |                    65.65 |                 65.24 |              62.1  |                59.46 |                   40.54 |           82.51 |             40.79 |     nan     |         nan |       nan |        7.3  |        10.33 |          4.44 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SBLK      | SBLK                           | US       |                2.88 |                  63.18 |                    65.64 |                 66.55 |              63.88 |                68.95 |                   31.05 |           75.23 |             59.81 |     nan     |         nan |       nan |      nan    |         8.44 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                                          | EUROPE   |                3.26 |                  76.12 |                    75.65 |                 77.11 |              76.21 |                86.75 |                   13.25 |           84.64 |             57.92 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  70.74 |                    74.23 |                 77.11 |              73.18 |                82.96 |                   17.04 |           87.49 |             73.08 |       0.178 |         nan |       nan |        4.21 |         2.81 |          5.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE      | StoneCo Ltd.                                           | OTHER    |                1.81 |                  77.2  |                    73.56 |                 73.16 |              72.4  |                72.22 |                   27.78 |           87.42 |             38.23 |       0.645 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.11 |                  71.87 |                    71.22 |                 72.51 |              70.69 |                69.64 |                   30.36 |           80.43 |             64.12 |       0.023 |         nan |       nan |        3.6  |         6.13 |          4.53 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                                               | EUROPE   |              222.26 |                  65.32 |                    70.47 |                 72.4  |              66.31 |                78.35 |                   21.65 |           93.92 |             51.82 |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NWL.MI    | NewPrinces S.p.A.                                      | EUROPE   |                0.66 |                  71.08 |                    70.01 |                 71.59 |              70.51 |                76.35 |                   23.65 |           79.08 |             55.9  |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | PAH3.DE   | PAH3.DE                                                | EUROPE   |                8.5  |                  63.54 |                    68.98 |                 70.71 |              68.35 |                78.89 |                   21.11 |          nan    |             84.02 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                                                    | US       |               14.78 |                  58.02 |                    66.54 |                 69.41 |              62.19 |                78.17 |                   21.83 |           88.25 |             63.44 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | IHS       | IHS Holding Limited                                    | OTHER    |                2.42 |                  71.89 |                    68.33 |                 68.93 |              71.23 |                62.26 |                   37.74 |           59.36 |             82.65 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | 0Q2N.IL   | K+S Aktiengesellschaft                                 | OTHER    |                3.02 |                  73.06 |                    70.2  |                 68.71 |              72.36 |                69.53 |                   30.47 |           60.4  |            nan    |       0.246 |         nan |       nan |        1.54 |       nan    |          2.81 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | KDP       | KDP                                                    | US       |               36.91 |                  55.27 |                    64.97 |                 68.29 |              60.28 |                76.75 |                   23.25 |           87.59 |             66.71 |     nan     |         nan |       nan |      nan    |        12.49 |         31.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                                                    | US       |              114.56 |                  62.78 |                    66.8  |                 68.19 |              64.09 |                73.38 |                   26.62 |           81.64 |             56.78 |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                                                | EUROPE   |               17.78 |                  58.2  |                    65.14 |                 67.68 |              59.56 |                76.49 |                   23.51 |           96.72 |             38.86 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY      | CRGY                                                   | US       |                4.65 |                  58.6  |                    65.31 |                 67.62 |              63.25 |                70.6  |                   29.4  |           72.51 |             83.54 |     nan     |         nan |       nan |      nan    |         6.43 |        172.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                                    | US       |                8.31 |                  57.05 |                    64.64 |                 67.41 |              60.45 |                72.51 |                   27.49 |           85.53 |             63.2  |     nan     |         nan |       nan |      nan    |        11.02 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                                    | US       |                2.73 |                  62.04 |                    65.67 |                 67.29 |              61.64 |                70.01 |                   29.99 |           89.26 |             43.7  |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.56 |                  58.33 |                    64.99 |                 66.82 |              63.75 |                74.71 |                   25.29 |           67.61 |             83.11 |       0.028 |         nan |       nan |      nan    |       nan    |          3.73 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SBLK      | SBLK                                                   | US       |                2.88 |                  63.18 |                    65.64 |                 66.55 |              63.88 |                68.95 |                   31.05 |           75.23 |             59.81 |     nan     |         nan |       nan |      nan    |         8.44 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.36 |                  77.65 |                    69.64 |                 66.53 |              72.4  |                59.95 |                   40.05 |           56.18 |             57    |       0.035 |         nan |       nan |       16.11 |        13.65 |         19.3  |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|           19 | HMC       | Honda Motor Company, Ltd.                              | OTHER    |               36.24 |                  54.23 |                    62.45 |                 66.53 |              60.12 |                70.43 |                   29.57 |           75.88 |             83.91 |       0.04  |         nan |       nan |        7.16 |         6.57 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.7  |                     0.07 |    -0.02 |      0.22 |                  69.42 |                        82.29 |         79.53 |         83.27 |          76.33 |        74.69 |           78.74 |             96.61 |         5.99 |
|               2 | GENI     | GENI     | US       |                1.82 |                     0.05 |     0    |      0.23 |                  69.29 |                        77.8  |         79.4  |         78.65 |          70.56 |        72.2  |           66.01 |             96.73 |         9.13 |
|               3 | WDAY     | WDAY     | US       |               41.75 |                     0.04 |    -0.04 |      0.54 |                  77.06 |                        76.87 |         78.49 |         77.2  |          65.94 |        62.6  |           74.92 |             73.85 |         8.47 |
|               4 | RBRK     | RBRK     | US       |               17.19 |                     0.07 |    -0.07 |      0.34 |                  81.3  |                        76.86 |         74.76 |         81    |          64.69 |        47.45 |           53.81 |             89.35 |         8.14 |
|               5 | NTAP     | NTAP     | US       |               32.41 |                     0.07 |    -0.06 |      0.17 |                  79.55 |                        76.04 |         67.81 |         77    |          74.47 |        67.8  |           88.82 |             52.3  |         6.33 |
|               6 | SNOW     | SNOW     | US       |               95.39 |                     0.05 |    -0.05 |      0.21 |                  80.22 |                        76    |         71.48 |         82.86 |          67.15 |        46.78 |           42.49 |             93.58 |         8.87 |
|               7 | ZETA     | ZETA     | US       |                5.95 |                     0.06 |    -0.06 |      0.44 |                  85.32 |                        75.66 |         78.35 |         81.2  |          66.95 |        52.62 |           47.84 |             84.62 |         7.59 |
|               8 | SYENS.BR | SYENS.BR | EUROPE   |                8.08 |                     0.04 |    -0.01 |      0.13 |                  64.27 |                        75.24 |         75.86 |         71.38 |          63.66 |        60.08 |           71.06 |             89.71 |         5.1  |
|               9 | HPE      | HPE      | US       |               60    |                     0.12 |    -0.12 |      0.11 |                  62.33 |                        74.52 |         60.98 |         80.1  |          80.08 |        72.69 |           70.57 |             73.37 |         6.85 |
|              10 | BCRX     | BCRX     | US       |                2.11 |                     0.09 |    -0.02 |      0.03 |                  54.98 |                        74.25 |         58.13 |         69.89 |          77.88 |        80.24 |           85.18 |             93.46 |         5.93 |
|              11 | SMWB     | SMWB     | US       |                0.62 |                     0.09 |    -0.09 |      0.35 |                  74    |                        74.03 |         73.75 |         82.65 |          63.35 |        44.2  |           35.96 |             96.13 |         9.45 |
|              12 | MPC      | MPC      | US       |               86.18 |                     0.02 |     0.01 |      0.15 |                  46.29 |                        73.84 |         79.63 |         81.16 |          79.88 |        76.91 |           85.79 |             61.02 |         4.1  |
|              13 | PLTR     | PLTR     | US       |              358.1  |                     0.03 |    -0.03 |      0.41 |                  62.48 |                        73.7  |         77.51 |         66.42 |          58.55 |        55.3  |           90.71 |             49.52 |         8.4  |
|              14 | KRX.IR   | KRX.IR   | EUROPE   |               18.12 |                     0.03 |    -0.02 |      0.34 |                  61.51 |                        72.83 |         78.3  |         68.64 |          62.52 |        61.6  |           95.73 |             35.35 |         5.25 |
|              15 | DK       | DK       | US       |                3.36 |                     0.06 |    -0.06 |     -0.01 |                  84.46 |                        72.8  |         56.39 |         76.15 |          72.96 |        60.51 |           55.04 |             73.61 |         6.66 |
|              16 | JHX      | JHX      | US       |               14.93 |                     0.03 |    -0.03 |      0.16 |                  65.82 |                        72.06 |         74.99 |         77.31 |          68.24 |        60.66 |           58.02 |             79.54 |         6.49 |
|              17 | TPG      | TPG      | US       |               17.25 |                     0.06 |    -0.06 |      0.24 |                  86.6  |                        71.72 |         73.46 |         69.03 |          58.69 |        55.41 |           52.27 |             77    |         6.42 |
|              18 | GL9.IR   | GL9.IR   | EUROPE   |                5.35 |                     0.07 |    -0.06 |     -0    |                  77.21 |                        71.7  |         43.35 |         62.21 |          73.7  |        70.2  |           97.93 |             62.83 |         2.35 |
|              19 | COUR     | COUR     | US       |                1.44 |                     0.05 |     0.01 |      0.09 |                  67.33 |                        71.6  |         66.88 |         62.38 |          63.58 |        73.02 |           68.02 |             96.37 |         8.19 |
|              20 | NTNX     | NTNX     | US       |               15.36 |                     0.02 |    -0.02 |      0.26 |                  58.5  |                        71.56 |         71.39 |         75.41 |          64.51 |        55.67 |           77.45 |             63.92 |         7.08 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4499.25 |             59.3  |         56.88 |         53.79 |          61.73 |        63.95 |           92.81 |             61.8  |             28.11 |         5.56 |             89.48 | long               |                1.85 |                 -0.91 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.13 |             57.64 |         73.17 |         57.65 |          57.64 |        55.02 |           50.64 |             83.53 |             32.07 |         5.93 |             77.94 | short              |                1.52 |                  0.53 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.68 |             51.8  |         33.48 |         50.53 |          53.06 |        57.71 |           55.63 |             48.65 |             63.55 |         8.42 |             85.47 | long               |               -1.62 |                 -1.57 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1483.58 |             49.9  |         32.41 |         42.48 |          57.32 |        59.64 |           82.27 |             62.28 |             28.41 |         6.11 |             89.81 | long               |               -0.4  |                 -0.88 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             48.98 |         41.49 |         43.76 |          54.21 |        64.65 |           84.96 |             43.01 |             55.32 |         3.89 |             75.81 | long               |               -0.83 |                 -0.42 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.72 |             44.39 |         39.29 |         40.01 |          48.77 |        60.62 |           58.87 |             56.01 |             86.74 |         4.25 |             82.14 | long               |               -2.59 |                 -0.47 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.27 |             39.05 |         31.86 |         35.52 |          42.58 |        46.84 |           40.38 |             60.32 |             65.74 |         5.93 |             80.44 | long               |              nan    |                 -1.83 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.89 |             37.88 |         29.78 |         34.1  |          41.67 |        53.28 |           48.14 |             46.26 |             78.26 |         6.24 |             78.58 | long               |                0.63 |                 -0.23 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             37.77 |         37.88 |         30.18 |          37.66 |        43.9  |           45.96 |             67.34 |             48.67 |         7.06 |             77.1  | long               |               -6.66 |                  0.14 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.19 |             37.55 |         25.98 |         33.44 |          41.66 |        56.07 |           49.06 |             40.77 |             92.35 |         7.14 |             78.43 | long               |                0.77 |                 -0.27 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.86 |             32.6  |         29.61 |         21.92 |          35.59 |        47.21 |           66.77 |             18.85 |             42.38 |         9.03 |             78.45 | long               |               -6.84 |                 -0.53 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.85 |             30.16 |         48.76 |         28.91 |          28.49 |        31.41 |           35.32 |             38.8  |             25.78 |         6.76 |             76.54 | short              |                7.05 |                  0.64 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                            | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    188 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.78 |             62.84 |         66.96 |         53.85 |          60.31 |        65.37 |           82.71 |             54.77 |             50.76 |         4.36 |             82    | short              |               -0.78 |                  2.55 |                  nan |
|      4 | PGEN     | PGEN                            | US       |                2.28 |             77.57 |         91.71 |         85.16 |          69.99 |        52.6  |           67.37 |            nan    |              1.85 |         7.71 |             62.84 | short              |                5.79 |                  2.35 |                  nan |
|    334 | TEM      | TEM                             | US       |               10.3  |             57.18 |         80.56 |         67.03 |          47.33 |        35.34 |           30.69 |             79.78 |              4.94 |         9.12 |             63.64 | short              |                4.93 |                  2.07 |                  nan |
|    198 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3.02 |             62.5  |         70.44 |         50.71 |          57.97 |        67.02 |           60.4  |            nan    |             83.51 |         4.5  |             67.39 | short              |               -2.54 |                  1.97 |                  nan |
|    117 | LLY      | Eli Lilly and Company           | US       |              950.58 |             66.18 |         66.41 |         65.95 |          66.62 |        61.6  |           83.83 |             64.35 |             17.4  |         4.31 |             89.59 | medium             |               -2.8  |                  1.59 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    453 | TKA.DE    | TKA.DE    | EUROPE   |                7.88 |             52.34 |         51.99 |         48.99 |          52.7  |        59.77 |          nan    |             18.77 |             65.84 |         6.6  |             64.66 | long               |              -24.02 |                 -5.1  |                  nan |
|    214 | AKER.OL   | AKER.OL   | EUROPE   |                9.85 |             61.99 |         78.88 |         66.33 |          57.64 |        38.89 |           34.41 |            nan    |             12.73 |         3.89 |             65.68 | short              |              -16.38 |                 -3.66 |                  nan |
|    571 | FOSL      | FOSL      | US       |                0.28 |             46.67 |         69.01 |         53.65 |          39.69 |        33.46 |            8.04 |              2.66 |             49.63 |         8.12 |             63.18 | short              |              -15.4  |                 -3.24 |                  nan |
|    630 | INDU-A.ST | INDU-A.ST | EUROPE   |               20.29 |             42.95 |         36.98 |         44.09 |          48.15 |        41.81 |           38.62 |            nan    |             26.24 |         1.78 |             65.68 | medium             |              -15.05 |                 -3.23 |                  nan |
|    458 | REPL      | REPL      | US       |                1.13 |             52.25 |         68.35 |         60.38 |          44.13 |        27.31 |            3.29 |             27    |             15.31 |         9.91 |             62.61 | short              |               -7.58 |                 -2.96 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **283**
- Event watch (otherwise eligible): **12**
- Final eligible: **705**
- Eligible change vs previous stored run: **+11**

Top exclusion categories:
- liquidity: 230
- price: 169
- market_cap: 157
- price_history: 20
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BAX | 3 |  | 1 |  | 2 | main,pullback |
| HPE | 8 |  | 9 |  | 2 | main,pullback |
| BION.SW | 26 | 1 |  | 1 | 1 | value,quality_value |
| PARR | 42 | 4 |  | 4 | 1 | value,quality_value |
| IRWD | 127 | 2 | 35 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 198 | 5 |  | 7 | 1 | value,quality_value |
| IHS | 306 | 8 |  | 6 | 1 | value,quality_value |
| VOLV-B.ST | 430 | 7 | 263 | 9 | 1 | value,quality_value |
| NWL.MI | 581 | 6 | 188 | 5 | 1 | value,quality_value |
| STNE | 673 | 3 |  | 3 | 1 | value,quality_value |
| MPC | 1 |  | 12 |  | 1 | main |
| CRGY | 2 |  |  |  | 1 | main |
| PGEN | 4 |  |  |  | 1 | main |
| PSX | 5 |  |  |  | 1 | main |
| CCC | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (CRGY, PGEN, PSX, CCC, GH, HPE, TALO, U)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (SYENS.BR, HPE, BCRX)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 74.90 | 71.08 | 83.41 | 79.08 | 55.90 | 76.35 | 45.90 |
| 2 | IRWD | value+pullback | 73.59 | 70.74 | 61.38 | 87.49 | 73.08 | 82.96 | 65.72 |
| 3 | ETG | value+pullback | 65.07 | 58.33 | 56.72 | 67.61 | 83.11 | 74.71 | 62.48 |
| 4 | VOLV-B.ST | value+pullback | 62.53 | 77.65 | 52.48 | 56.18 | 57.00 | 59.95 | 53.29 |
| 5 | MSFT | value+pullback | 61.94 | 58.21 | 74.85 | 60.70 | 63.03 | 51.79 | 58.63 |
| 6 | DXC | value+pullback | 61.79 | 83.49 | 61.62 | 49.83 | 35.68 | 51.46 | 53.63 |
| 7 | MFA | value+pullback | 61.43 | 57.65 | 63.80 | 80.59 | 33.74 | 63.61 | 44.56 |
| 8 | CNC | value+pullback | 61.39 | 67.21 | 75.73 | 43.86 | 63.95 | 46.61 | 59.09 |
| 9 | ORCL | value+pullback | 60.29 | 69.90 | 75.23 | 49.33 | 56.15 | 37.49 | 40.95 |
| 10 | WKC | value+pullback | 58.98 | 57.82 | 47.71 | 58.15 | 73.99 | 67.94 | 66.20 |
| 11 | ALL-PH | value+pullback | 58.94 | 61.89 | 57.83 | 67.39 | 42.01 | 58.04 | 45.51 |
| 12 | KYN | value+pullback | 58.78 | 59.80 | 46.38 | 53.56 | 83.11 | 64.50 | 60.44 |
| 13 | BION.SW | value | 58.67 | 76.12 | 37.64 | 84.64 | 57.92 | 86.75 | 73.81 |
| 14 | ONIT | value+pullback | 57.87 | 70.86 | 60.49 | 59.75 | 43.94 | 40.68 | 43.64 |
| 15 | CNXC | value+pullback | 57.70 | 78.52 | 64.61 | 46.15 | 31.37 | 39.66 | 45.59 |
| 16 | TV | value+pullback | 57.17 | 59.62 | 79.62 | 47.40 | 31.32 | 45.70 | 36.04 |
| 17 | GL9.IR | pullback | 57.14 | 41.23 | 77.21 | 97.93 | 62.83 | 84.34 | 66.20 |
| 18 | LKFT.AS | value+pullback | 56.76 | 70.58 | 57.94 | 51.09 | 18.99 | 57.68 | 41.68 |
| 19 | CHTR | value+pullback | 55.98 | 55.83 | 82.24 | 54.67 | 39.89 | 32.40 | 42.48 |
| 20 | CION | value+pullback | 55.21 | 59.81 | 70.43 | 33.18 | 58.52 | 44.15 | 50.83 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 9/10 | 8/10 | 0/10 | 66.5 | 2 / 8 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 66.6 | 5 / 20 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 66.5 | 14 / 36 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=3, large_20_100b=3
