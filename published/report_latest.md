# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-20

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

- **EUROPE:** 88.8/100
- **OTHER:** 77.1/100
- **US:** 87.0/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HALO      | HALO      | US       |               10.55 |             80.57 |         85.98 |         84.53 |          76.61 |        75.25 |           86.04 |             69.1  |             57.58 |         5.53 |             66.48 | short              |                0.77 |                  1.05 |                  nan |
|      2 | BAX       | BAX       | US       |               11.89 |             78.87 |         81.31 |         84.24 |          76.43 |        74.85 |           78.08 |             97.93 |             61.23 |         5.89 |             66.02 | swing              |                2.49 |                  1.13 |                  nan |
|      3 | AKER.OL   | Aker ASA  | EUROPE   |                9.74 |             78.65 |         81.37 |         74.05 |          80.26 |        77.05 |           90.89 |             79.8  |             54.1  |         3.53 |             74.34 | short              |               19.56 |                 -0.65 |                  nan |
|      4 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.46 |             78.32 |         72.03 |         75.1  |          81.55 |        83.12 |           69.53 |            nan    |            100    |         3.34 |             62.84 | long               |                2.1  |                 -1.03 |                  nan |
|      5 | PBF       | PBF       | US       |                7.57 |             77.94 |         80.46 |         81.05 |          75.43 |        71.89 |           50.86 |             56.93 |             92.46 |         7.04 |             67.05 | swing              |               -0.95 |                 -2.95 |                  nan |
|      6 | CRGY      | CRGY      | US       |                4.56 |             77.77 |         81.49 |         70.56 |          75.61 |        79.92 |           71.52 |             83.58 |             96.34 |         6.09 |             67.05 | short              |              nan    |                nan    |                  nan |
|      7 | RMAX      | RMAX      | US       |                0.69 |             77.61 |         85.52 |         86.75 |          69.7  |        59.37 |           20.73 |             90.88 |             84.15 |         7.23 |             67.05 | swing              |              nan    |                 -1.8  |                  nan |
|      8 | TWST      | TWST      | US       |                7.71 |             77.51 |         87.79 |         84.6  |          70.41 |        50.76 |           47.12 |             77.74 |              7.96 |         6.99 |             64.66 | short              |              nan    |                 -0.69 |                  nan |
|      9 | BCRX      | BCRX      | US       |                2.22 |             77.13 |         61.6  |         74.52 |          79.74 |        79.92 |           85.21 |             94.04 |             73.2  |         5.83 |             66.59 | long               |                2.54 |                  3.18 |                  nan |
|     10 | PSX       | PSX       | US       |               83.89 |             77.05 |         77.74 |         78.26 |          76.36 |        74.52 |           80.9  |             54.38 |             63.84 |         3.41 |             67.5  | swing              |               -0.46 |                 -1    |                  nan |
|     11 | CCC       | CCC       | US       |                3.78 |             77.02 |         83.22 |         80.87 |          73.18 |        72.32 |           87.14 |             80.41 |             57.1  |         7.88 |             66.02 | short              |                0.33 |                  1.78 |                  nan |
|     12 | HPE       | HPE       | US       |               60.76 |             77    |         62    |         80.91 |          80.71 |        73.3  |           71.43 |             74.09 |             59.22 |         6.8  |             65.68 | swing              |               -2.21 |                 -1.82 |                  nan |
|     13 | U         | U         | US       |               17.9  |             76.51 |         85.56 |         87.32 |          67.47 |        50.83 |           45.06 |             96.84 |             21.94 |         8.3  |             67.5  | swing              |               -0.1  |                  0.33 |                  nan |
|     14 | PGEN      | PGEN      | US       |                2.21 |             76.06 |         89.66 |         83.41 |          68.71 |        52.85 |           67.6  |            nan    |              1.87 |         7.63 |             62.84 | short              |                3.55 |                  2.23 |                  nan |
|     15 | AUTL      | AUTL      | US       |                0.58 |             76.03 |         88.72 |         80.48 |          68.39 |        71.58 |           57.44 |             56.08 |             99.5  |         7.83 |             63.64 | short              |                4.53 |                 -1.66 |                  nan |
|     16 | SBLK      | SBLK      | US       |                2.91 |             75.63 |         78.91 |         71.57 |          73.44 |        77.83 |           76.1  |             59.37 |             87.32 |         3.86 |             67.16 | short              |                0.74 |                nan    |                  nan |
|     17 | ZETA      | ZETA      | US       |                6.2  |             75.3  |         84.59 |         83.16 |          67.44 |        53.04 |           48.12 |             84.73 |             24.74 |         7.48 |             67.05 | short              |                1.08 |                 -1.03 |                  nan |
|     18 | GENI      | GENI      | US       |                1.86 |             75.23 |         78.67 |         78.01 |          70.61 |        72.45 |           65.82 |             97.2  |             83.79 |         9.09 |             67.5  | short              |                3.37 |                  0.04 |                  nan |
|     19 | GH        | GH        | US       |               18.93 |             75.13 |         67    |         79.28 |          77.53 |        72.74 |           62.59 |             69.22 |            nan    |         6.8  |             62.73 | swing              |              nan    |                 -1.81 |                  nan |
|     20 | FLYW      | FLYW      | US       |                1.98 |             75.1  |         75.8  |         76.2  |          74.4  |        69.32 |           71.78 |             75.79 |             56.58 |         5.89 |             67.05 | swing              |              nan    |                  0.62 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.26 |                  72.57 |                    73.9  |                 75.83 |              73.71 |                87.03 |                   12.97 |           85.71 |             57.96 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.89 |                  77.2  |                    73.52 |                 73.11 |              72.36 |                72.08 |                   27.92 |           87.42 |             38.02 |       0.621 |         nan |       nan |        1.61 |         4.07 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              220.39 |                  66.6  |                    71.01 |                 72.68 |              67.23 |                77.97 |                   22.03 |           92.6  |             52.43 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | AKER.OL  | Aker ASA                                               | EUROPE   |                9.74 |                  61.81 |                    70.25 |                 73.64 |              65.84 |                74.21 |                   25.79 |           90.89 |             79.8  |       0.114 |         nan |       nan |        5.31 |        54.78 |          3.77 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft                                 | OTHER    |                3    |                  69.62 |                    69.58 |                 69.14 |              70.33 |                73.2  |                   26.8  |           65.85 |            nan    |       0.247 |         nan |       nan |        1.54 |       nan    |          2.79 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.34 |                  68.27 |                    69.29 |                 70.95 |              68.15 |                69.77 |                   30.23 |           80.43 |             64.36 |       0.021 |         nan |       nan |        3.78 |         6.53 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.49 |                  63.54 |                    69.03 |                 70.76 |              68.4  |                79.14 |                   20.86 |          nan    |             84.06 |     nan     |         nan |       nan |      nan    |         1.88 |         89.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              224.79 |                  67.46 |                    68.73 |                 68.13 |              67.04 |                71.4  |                   28.6  |           74.57 |             56.14 |       0.051 |         nan |       nan |       12.54 |        17.89 |         20.78 |        1.78 |                 nan |              nan |                  12 |                  0.63 |
|            7 | IHS      | IHS Holding Limited                                    | OTHER    |                2.43 |                  72.27 |                    68.29 |                 68.77 |              71.37 |                61.35 |                   38.65 |           58.43 |             82.88 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.66 |                  67.55 |                    67.54 |                 69.3  |              67.61 |                74.7  |                   25.3  |           77.61 |             55.3  |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | SAP.DE   | SAP SE                                                 | EUROPE   |              214.57 |                  66.16 |                    67.5  |                 66.82 |              65.06 |                70.24 |                   29.76 |           77.36 |             47.78 |       0.042 |         nan |       nan |       18.14 |        22.21 |         27.83 |        1.8  |                 nan |              nan |                  12 |                  0.63 |
|          nan | VOW.DE   | VOW.DE                                                 | EUROPE   |               38.02 |                  68.41 |                    66.98 |                 66.55 |              67.13 |                64.02 |                   35.98 |          nan    |             63.5  |     nan     |         nan |       nan |      nan    |         2.79 |          7.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | RCI      | Rogers Communications Inc.                             | OTHER    |               17.04 |                  67.17 |                    66.8  |                 66.46 |              63.17 |                59.75 |                   40.25 |           84.78 |             40.54 |       0.277 |         nan |       nan |        7.32 |        10.43 |          4.44 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                                    | US       |               14.91 |                  58.52 |                    66.75 |                 69.52 |              62.5  |                78.03 |                   21.97 |           87.97 |             63.26 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                                                | EUROPE   |               37.52 |                  69.3  |                    66.72 |                 65.99 |              67    |                61.2  |                   38.8  |          nan    |             60.83 |     nan     |         nan |       nan |      nan    |         3.18 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                                    | US       |              119.27 |                  62.9  |                    66.63 |                 67.92 |              63.94 |                73.04 |                   26.96 |           81.59 |             55.11 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | UNIT     | Uniti Group Inc.                                       | US       |                2.17 |                  80.26 |                    66.56 |                 63.47 |              68.73 |                44.59 |                   55.41 |           65.19 |             29.1  |      -0.103 |         nan |       nan |        9.16 |       -14.55 |          2.58 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           12 | DXC      | DXC Technology Company                                 | US       |                1.5  |                  83.62 |                    66.48 |                 60.82 |              71.98 |                46.27 |                   53.73 |           44.31 |             34.46 |       0.506 |         nan |       nan |        3.09 |         3.67 |         14.28 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                                                | EUROPE   |               17.53 |                  60.3  |                    66.36 |                 68.62 |              61.18 |                76.53 |                   23.47 |           96.08 |             39.9  |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.76 |                  56.4  |                    65.88 |                 70.37 |              63.22 |                78.98 |                   21.02 |           82.19 |             83.97 |       0.041 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.26 |                  72.57 |                    73.9  |                 75.83 |              73.71 |                87.03 |                   12.97 |           85.71 |             57.96 |       0.807 |         nan |       nan |      nan    |       -84.38 |          2.26 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | AKER.OL  | Aker ASA                                               | EUROPE   |                9.74 |                  61.81 |                    70.25 |                 73.64 |              65.84 |                74.21 |                   25.79 |           90.89 |             79.8  |       0.114 |         nan |       nan |        5.31 |        54.78 |          3.77 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.89 |                  77.2  |                    73.52 |                 73.11 |              72.36 |                72.08 |                   27.92 |           87.42 |             38.02 |       0.621 |         nan |       nan |        1.61 |         4.07 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              220.39 |                  66.6  |                    71.01 |                 72.68 |              67.23 |                77.97 |                   22.03 |           92.6  |             52.43 |     nan     |         nan |       nan |      nan    |         9.98 |         10.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.34 |                  68.27 |                    69.29 |                 70.95 |              68.15 |                69.77 |                   30.23 |           80.43 |             64.36 |       0.021 |         nan |       nan |        3.78 |         6.53 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.49 |                  63.54 |                    69.03 |                 70.76 |              68.4  |                79.14 |                   20.86 |          nan    |             84.06 |     nan     |         nan |       nan |      nan    |         1.88 |         89.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.76 |                  56.4  |                    65.88 |                 70.37 |              63.22 |                78.98 |                   21.02 |           82.19 |             83.97 |       0.041 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                                                    | US       |               14.91 |                  58.52 |                    66.75 |                 69.52 |              62.5  |                78.03 |                   21.97 |           87.97 |             63.26 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.66 |                  67.55 |                    67.54 |                 69.3  |              67.61 |                74.7  |                   25.3  |           77.61 |             55.3  |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft                                 | OTHER    |                3    |                  69.62 |                    69.58 |                 69.14 |              70.33 |                73.2  |                   26.8  |           65.85 |            nan    |       0.247 |         nan |       nan |        1.54 |       nan    |          2.79 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | IHS      | IHS Holding Limited                                    | OTHER    |                2.43 |                  72.27 |                    68.29 |                 68.77 |              71.37 |                61.35 |                   38.65 |           58.43 |             82.88 |      -0.115 |         nan |       nan |        7.47 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                                                | EUROPE   |               17.53 |                  60.3  |                    66.36 |                 68.62 |              61.18 |                76.53 |                   23.47 |           96.08 |             39.9  |     nan     |         nan |       nan |      nan    |        10.17 |         13.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MC.PA    | LVMH Moët Hennessy - Louis Vuitton, Société Européenne | EUROPE   |              224.79 |                  67.46 |                    68.73 |                 68.13 |              67.04 |                71.4  |                   28.6  |           74.57 |             56.14 |       0.051 |         nan |       nan |       12.54 |        17.89 |         20.78 |        1.78 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                                    | US       |              119.27 |                  62.9  |                    66.63 |                 67.92 |              63.94 |                73.04 |                   26.96 |           81.59 |             55.11 |     nan     |         nan |       nan |      nan    |        10.31 |         14.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                                                   | US       |                4.56 |                  58.65 |                    65.16 |                 67.37 |              63.25 |                70.39 |                   29.61 |           71.52 |             83.58 |     nan     |         nan |       nan |      nan    |         6.26 |        167.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | SDF.DE   | K+S Aktiengesellschaft        N                        | EUROPE   |                2.72 |                  61.81 |                    65.03 |                 67.25 |              62.87 |                71.14 |                   28.86 |           81.71 |             55.59 |       0.126 |         nan |       nan |        1.92 |        15.36 |          2.57 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            9 | SAP.DE   | SAP SE                                                 | EUROPE   |              214.57 |                  66.16 |                    67.5  |                 66.82 |              65.06 |                70.24 |                   29.76 |           77.36 |             47.78 |       0.042 |         nan |       nan |       18.14 |        22.21 |         27.83 |        1.8  |                 nan |              nan |                  12 |                  0.63 |
|          nan | VOW.DE   | VOW.DE                                                 | EUROPE   |               38.02 |                  68.41 |                    66.98 |                 66.55 |              67.13 |                64.02 |                   35.98 |          nan    |             63.5  |     nan     |         nan |       nan |      nan    |         2.79 |          7.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | RCI      | Rogers Communications Inc.                             | OTHER    |               17.04 |                  67.17 |                    66.8  |                 66.46 |              63.17 |                59.75 |                   40.25 |           84.78 |             40.54 |       0.277 |         nan |       nan |        7.32 |        10.43 |          4.44 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SBLK     | SBLK                                                   | US       |                2.91 |                  61.9  |                    65.05 |                 66.18 |              62.98 |                69.32 |                   30.68 |           76.1  |             59.37 |     nan     |         nan |       nan |      nan    |         8.48 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.89 |                     0.06 |    -0.01 |      0.22 |                  70.9  |                        83.06 |         81.31 |         84.24 |          76.43 |        74.85 |           78.08 |             97.93 |         5.89 |
|               2 | BCRX     | BCRX     | US       |                2.22 |                     0.05 |    -0.05 |      0.04 |                  81.5  |                        80.64 |         61.6  |         74.52 |          79.74 |        79.92 |           85.21 |             94.04 |         5.83 |
|               3 | NTAP     | NTAP     | US       |               32.96 |                     0.06 |    -0.04 |      0.16 |                  78.14 |                        76.49 |         68.42 |         77.85 |          75.17 |        68.35 |           88.16 |             54.74 |         6.24 |
|               4 | HPE      | HPE      | US       |               60.76 |                     0.11 |    -0.1  |      0.1  |                  63.73 |                        75.41 |         62    |         80.91 |          80.71 |        73.3  |           71.43 |             74.09 |         6.8  |
|               5 | GENI     | GENI     | US       |                1.86 |                     0.07 |     0.02 |      0.21 |                  55.24 |                        75.37 |         78.67 |         78.01 |          70.61 |        72.45 |           65.82 |             97.2  |         9.09 |
|               6 | SNOW     | SNOW     | US       |               97.28 |                     0.04 |    -0.02 |      0.21 |                  65.85 |                        74.71 |         73.93 |         84.1  |          68.21 |        47.72 |           42.93 |             94.65 |         8.8  |
|               7 | SMWB     | SMWB     | US       |                0.64 |                     0.07 |    -0.05 |      0.33 |                  74.13 |                        74.63 |         75.34 |         83.65 |          63.86 |        44.69 |           35.74 |             96.96 |         9.39 |
|               8 | BFLY     | BFLY     | US       |                2.11 |                     0.05 |    -0.03 |      0.39 |                  79.25 |                        73.06 |         74.72 |         81.07 |          70.06 |        51.52 |           47.33 |             74.45 |         8.4  |
|               9 | SYENS.BR | SYENS.BR | EUROPE   |                8.22 |                     0.02 |    -0    |      0.16 |                  51.4  |                        73.02 |         77.99 |         73.23 |          63.1  |        58.13 |           64.61 |             89.29 |         5.07 |
|              10 | ZETA     | ZETA     | US       |                6.2  |                     0.03 |     0.01 |      0.43 |                  51.68 |                        72.38 |         84.59 |         83.16 |          67.44 |        53.04 |           48.12 |             84.73 |         7.48 |
|              11 | QNST     | QNST     | US       |                1.04 |                     0.04 |     0.01 |      0.35 |                  59.99 |                        72.18 |         82.56 |         76.01 |          68.7  |        70.49 |           84.6  |             33.21 |         7.8  |
|              12 | KRMN     | KRMN     | US       |                6.66 |                     0.06 |    -0.06 |      0.23 |                  82.92 |                        72.16 |         63.88 |         46.7  |          51.54 |        56.07 |           88.62 |             67.03 |         8.74 |
|              13 | JHX      | JHX      | US       |               15.14 |                     0.03 |    -0.02 |      0.22 |                  60.55 |                        72.14 |         77.64 |         78.92 |          65.47 |        59.91 |           58.15 |             79.81 |         6.75 |
|              14 | KRX.IR   | KRX.IR   | EUROPE   |               17.83 |                     0.02 |    -0.02 |      0.33 |                  53.46 |                        71.93 |         78.22 |         70.86 |          63.96 |        63.07 |           97.55 |             35.28 |         5.16 |
|              15 | OKTA     | OKTA     | US       |               21.2  |                     0.09 |    -0.04 |      0.03 |                  62.05 |                        71.66 |         53.73 |         75.5  |          72.32 |        60.67 |           69.06 |             71.9  |         7.49 |
|              16 | TGB      | TGB      | US       |                2.68 |                     0.04 |    -0.03 |      0.12 |                  70.04 |                        71.56 |         74.66 |         73.7  |          70.24 |        69.11 |           55.77 |             83.82 |         7.5  |
|              17 | GH       | GH       | US       |               18.93 |                     0.03 |    -0.01 |      0.07 |                  58.8  |                        71.36 |         67    |         79.28 |          77.53 |        72.74 |           62.59 |             69.22 |         6.8  |
|              18 | NWL      | NWL      | US       |                2.27 |                     0.03 |     0    |      0.14 |                  56.25 |                        70.97 |         75.27 |         83.59 |          69.84 |        63.99 |           32.07 |             95.5  |         8.02 |
|              19 | GL9.IR   | GL9.IR   | EUROPE   |                5.38 |                     0.07 |    -0.05 |     -0.02 |                  73.26 |                        70.96 |         42.43 |         62.08 |          73.83 |        70.59 |           97.55 |             62.77 |         2.34 |
|              20 | PANW     | PANW     | US       |              253.21 |                     0.09 |    -0.07 |      0.07 |                  68.77 |                        70.68 |         59.56 |         76.36 |          69.85 |        51.9  |           54.98 |             74.57 |         6.56 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             62.97 |         73.29 |         69.71 |          56.24 |        51.24 |           51.25 |             48.79 |             53.85 |         8.21 |             86.86 | short              |                0.34 |                 -1.52 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4550.76 |             58.72 |         56.43 |         53.45 |          61.01 |        62.86 |           91.47 |             58.9  |             27.31 |         5.48 |             89.53 | long               |               -4.16 |                 -1.06 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.14 |             56.96 |         69.64 |         56.92 |          57    |        53.91 |           51.42 |             83.44 |             29.56 |         5.96 |             77.94 | short              |                3.35 |                  0.48 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.85 |             55.34 |         45.6  |         56.26 |          54.42 |        57.5  |           47.66 |             47.94 |             67.95 |         8.34 |             85.47 | long               |               -3.64 |                 -0.85 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |             50.31 |         42.91 |         45.55 |          55.08 |        64.03 |           83.47 |             42.28 |             54.17 |         3.89 |             75.81 | long               |                1.85 |                  0.1  |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1489.3  |             50.17 |         32.08 |         42.84 |          57.5  |        59.38 |           81.77 |             62.28 |             27.77 |         6.08 |             89.81 | long               |               -2.63 |                 -0.88 |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.                              | US       |                3.42 |             47.32 |         46.23 |         46.67 |          47.97 |        59.47 |           60.51 |             44.4  |             78.48 |         7.41 |             87.87 | long               |              nan    |                  0.26 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.72 |         39.91 |         42.29 |          51.14 |        63.68 |           63.39 |             55.45 |             88.3  |         4.27 |             82.14 | long               |               -0.19 |                  0.07 |                  nan |
|    nan | ATHM     | Autohome Inc.                                        | OTHER    |                2.24 |             44.94 |         50.54 |         50.49 |          39.38 |        36.76 |           32.5  |             30.07 |             39.87 |         8.5  |             78.73 | short              |                2.48 |                  0.47 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.77 |             43.29 |         52.31 |         34.19 |          39.99 |        46.6  |           50.53 |             67.58 |             48.67 |         7    |             77.1  | short              |                1.59 |                  1.54 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.93 |             40.47 |         42.21 |         27.08 |          38.72 |        50.13 |           73.91 |             18.62 |             39.33 |         8.98 |             78.45 | long               |                7.83 |                  1.28 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.9  |             37.76 |         28.86 |         34.09 |          41.42 |        53.03 |           44.78 |             46.03 |             81.26 |         6.14 |             78.58 | long               |               -1.18 |                 -0.13 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.24 |             37.38 |         26.19 |         34.06 |          40.69 |        54.09 |           42.08 |             40.28 |             93.85 |         7.1  |             78.43 | long               |               -0.98 |                 -0.16 |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.82 |             27.58 |         49.19 |         22.58 |          23.41 |        31.76 |           30.06 |             26.63 |             49.43 |         8.5  |             76.14 | short              |               -3.16 |                  0.24 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.76 |             27.55 |         44.02 |         25.53 |          25.99 |        29.1  |           35.27 |             38.06 |             24.52 |         6.7  |             76.54 | short              |              nan    |                  0.92 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    560 | HFG.DE   | HFG.DE | EUROPE   |                0.42 |             48.08 |         32.27 |         42.32 |          53.84 |        71.62 |          nan    |             96.23 |             85.28 |         7.03 |             64.66 | long               |                3.63 |                  3.6  |                  nan |
|    392 | TEM      | TEM    | US       |                9.54 |             55.25 |         77.14 |         63.99 |          46.51 |        35.29 |           31.11 |             80.9  |              5.72 |         9.02 |             63.64 | short              |               13.15 |                  3.59 |                  nan |
|    305 | HIMS     | HIMS   | US       |                6.26 |             58.45 |         57.04 |         69.21 |          59.86 |        42.89 |           37.07 |             95.62 |             16.64 |         9.42 |             67.5  | swing              |                6.62 |                  3.23 |                  nan |
|      9 | BCRX     | BCRX   | US       |                2.22 |             77.13 |         61.6  |         74.52 |          79.74 |        79.92 |           85.21 |             94.04 |             73.2  |         5.83 |             66.59 | long               |                2.54 |                  3.18 |                  nan |
|    335 | BBIO     | BBIO   | US       |               14.17 |             57.32 |         56.97 |         60.55 |          57.68 |        50.7  |           68.75 |             48.42 |              1.52 |         4.71 |             65.57 | swing              |                2.33 |                  3.1  |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    510 | RBI.VI   | RBI.VI | EUROPE   |               20.34 |             50.28 |         51.98 |         55.84 |          48.58 |        42.63 |           11.23 |              9.37 |             71.97 |         3.8  |             66.14 | swing              |               -0.18 |                 -6.41 |                  nan |
|    592 | NBIS     | NBIS   | US       |               52.57 |             46.22 |         47.34 |         45.09 |          50.85 |        44.27 |           54.86 |              1.09 |             20.65 |         8.87 |             64.66 | medium             |               -7.93 |                 -6.36 |                  nan |
|    645 | GLE.PA   | GLE.PA | EUROPE   |               56.46 |             41.49 |         34.38 |         43.43 |          41.71 |        41.26 |            6.14 |             23.6  |             77.26 |         3.77 |             67.5  | swing              |                1.55 |                 -6.14 |                  nan |
|    564 | BNP.PA   | BNP.PA | EUROPE   |              117.03 |             48.02 |         42.06 |         51.95 |          48.44 |        47.6  |           21.81 |             18.73 |             77.48 |         2.63 |             67.5  | swing              |                0.67 |                 -5.86 |                  nan |
|    358 | ABCL     | ABCL   | US       |                3.36 |             56.59 |         75.04 |         66.74 |          46.45 |        33.96 |            9.77 |             12.41 |             40.8  |         9.01 |             63.64 | short              |                1.22 |                 -5.85 |                  nan |

## Duplicate-security checks

- TEK.L duplicates HEADL.XC (security_id=ISIN:PLCTHQM00018)

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
- Excluded by hard/data filters: **282**
- Event watch (otherwise eligible): **15**
- Final eligible: **703**
- Eligible change vs previous stored run: **+2**

Top exclusion categories:
- liquidity: 231
- price: 173
- market_cap: 154
- price_history: 20
- data_confidence: 17
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 3 | 3 |  | 2 | 2 | main,value,quality_value |
| BAX | 2 |  | 1 |  | 2 | main,pullback |
| BCRX | 9 |  | 2 |  | 2 | main,pullback |
| BION.SW | 25 | 1 |  | 1 | 1 | value,quality_value |
| PARR | 43 | 5 | 57 | 4 | 1 | value,quality_value |
| 0Q2N.IL | 201 | 4 |  | 7 | 1 | value,quality_value |
| IHS | 319 | 7 |  | 8 | 1 | value,quality_value |
| NWL.MI | 563 | 8 | 187 | 6 | 1 | value,quality_value |
| MC.PA | 639 | 6 | 248 | 9 | 1 | value,quality_value |
| STNE | 662 | 2 |  | 3 | 1 | value,quality_value |
| HALO | 1 |  |  |  | 1 | main |
| SSABBH.HE | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |
| CRGY | 6 |  |  |  | 1 | main |
| RMAX | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (HALO, PBF, CRGY, RMAX, PSX)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SYENS.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MC.PA | value+pullback | 68.92 | 67.46 | 70.40 | 74.57 | 56.14 | 71.40 | 41.98 |
| 2 | NWL.MI | value+pullback | 67.91 | 67.55 | 62.11 | 77.61 | 55.30 | 74.70 | 48.04 |
| 3 | ETG | value+pullback | 63.15 | 58.08 | 52.24 | 66.73 | 79.56 | 73.48 | 60.53 |
| 4 | PARR | value+pullback | 61.52 | 68.27 | 34.36 | 80.43 | 64.36 | 69.77 | 72.11 |
| 5 | CNC | value+pullback | 61.14 | 71.70 | 72.51 | 37.54 | 65.41 | 46.65 | 57.49 |
| 6 | MSFT | value+pullback | 60.01 | 58.21 | 68.20 | 58.86 | 63.76 | 51.43 | 58.71 |
| 7 | VOLV-B.ST | value+pullback | 59.87 | 66.78 | 53.64 | 56.26 | 57.91 | 60.99 | 52.16 |
| 8 | ORCL | value+pullback | 59.73 | 69.90 | 73.72 | 47.83 | 57.04 | 37.26 | 41.18 |
| 9 | WKC | value+pullback | 59.71 | 57.82 | 50.60 | 58.15 | 73.99 | 67.95 | 66.39 |
| 10 | BCRX | pullback | 58.78 | 53.24 | 81.50 | 85.21 | 94.04 | 81.10 | 77.13 |
| 11 | ALL-PH | value+pullback | 58.19 | 61.90 | 55.82 | 67.80 | 39.85 | 57.56 | 43.97 |
| 12 | BION.SW | value | 57.83 | 72.57 | 30.95 | 85.71 | 57.96 | 87.03 | 74.17 |
| 13 | NOKIA.HE | value+pullback | 57.59 | 60.83 | 63.43 | 48.37 | 41.90 | 60.17 | 49.29 |
| 14 | DXC | value+pullback | 57.40 | 83.62 | 51.85 | 44.31 | 34.46 | 46.27 | 53.54 |
| 15 | PKX | value+pullback | 57.28 | 55.29 | 42.26 | 71.63 | 67.41 | 63.20 | 58.17 |
| 16 | TV | value+pullback | 57.08 | 60.81 | 77.79 | 49.00 | 30.95 | 44.73 | 37.37 |
| 17 | ONIT | value+pullback | 56.44 | 73.21 | 51.12 | 60.10 | 43.84 | 41.48 | 42.03 |
| 18 | GL9.IR | pullback | 56.05 | 43.29 | 73.26 | 97.55 | 62.77 | 84.14 | 66.34 |
| 19 | AKER.OL | value | 55.00 | 61.81 | 38.59 | 90.89 | 79.80 | 74.21 | 78.65 |
| 20 | BAX | pullback | 54.96 | 48.38 | 70.90 | 78.08 | 97.93 | 78.68 | 78.87 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 66.8 | 5 / 5 |
| Top 25 | 24/25 | 23/25 | 24/25 | 21/25 | 0/25 | 67.0 | 11 / 14 |
| Top 50 | 47/50 | 47/50 | 49/50 | 43/50 | 0/50 | 67.0 | 19 / 31 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=6, large_20_100b=1
