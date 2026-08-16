# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-16

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

- **EUROPE:** 90.4/100
- **OTHER:** 76.5/100
- **US:** 87.1/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | JCAP      | JCAP      | US       |                1.19 |             81.91 |         84.42 |         80.97 |          76.21 |        82.85 |           86.83 |             84.84 |             83.28 |         5.32 |             65.45 | short              |                3.8  |                   nan |                  nan |
|      2 | HPE       | HPE       | US       |               67.18 |             81.21 |         81.81 |         85.38 |          80.61 |        73.21 |           73.04 |             72.32 |             57.31 |         6.68 |             65.68 | swing              |               -4.9  |                   nan |                  nan |
|      3 | AKER.OL   | Aker ASA  | EUROPE   |                9.75 |             80.3  |         83.78 |         76.79 |          81.41 |        79.18 |           87.33 |             81.55 |             63.77 |         3.39 |             74.34 | short              |               -1.63 |                   nan |                  nan |
|      4 | MPC       | MPC       | US       |               86.25 |             80.22 |         80.61 |         81.35 |          79.83 |        77.53 |           85.48 |             59.81 |             63.96 |         3.82 |             67.5  | swing              |               -4.32 |                   nan |                  nan |
|      5 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             79.73 |         77    |         78.21 |          81.24 |        83.61 |           72.3  |            nan    |             98.73 |         3.23 |             62.84 | long               |               -3.77 |                   nan |                  nan |
|      6 | FSLY      | FSLY      | US       |                4.12 |             79.21 |         86.99 |         84.44 |          73.98 |        54.59 |           44.3  |             99.04 |             16.46 |         8.36 |             67.5  | short              |               -1.62 |                   nan |                  nan |
|      7 | BAX       | BAX       | US       |               11.94 |             78.78 |         78.78 |         86.17 |          78.78 |        75.81 |           78.07 |             97.35 |             65.15 |         5.79 |             66.02 | swing              |                5.57 |                   nan |                  nan |
|      8 | CLMT      | CLMT      | US       |                3.62 |             78.3  |         83.48 |         83.23 |          73.38 |        53.84 |           52.51 |             92.3  |              5.75 |         4.4  |             66.59 | short              |               -1.23 |                   nan |                  nan |
|      9 | TKA.DE    | TKA.DE    | EUROPE   |                8.6  |             77.84 |         82.6  |         79.3  |          76.38 |        72.32 |          nan    |             83.39 |             57.64 |         6.33 |             64.66 | short              |                0.9  |                   nan |                  nan |
|     10 | PBF       | PBF       | US       |                7.36 |             77.77 |         80.78 |         80.12 |          75.42 |        72.71 |           52.23 |             55.6  |             94.29 |         6.97 |             67.05 | short              |              -14.93 |                   nan |                  nan |
|     11 | HALO      | HALO      | US       |                9.68 |             77.7  |         78.39 |         78.65 |          74.53 |        77.01 |           86.67 |             68.11 |             64.82 |         5.29 |             66.48 | swing              |                2.39 |                   nan |                  nan |
|     12 | GENI      | GENI      | US       |                2.01 |             77.66 |         86.47 |         82.53 |          72.65 |        72.79 |           66.12 |             97.59 |             82.48 |         9.31 |             67.5  | short              |                2.62 |                   nan |                  nan |
|     13 | NET       | NET       | US       |               97.16 |             77.01 |         82.44 |         82.8  |          71.58 |        53.84 |           59.78 |             92.9  |              1.82 |         6.72 |             67.5  | swing              |                2.18 |                   nan |                  nan |
|     14 | NTAP      | NTAP      | US       |               35.11 |             76.93 |         79.1  |         81.33 |          74.76 |        68.03 |           88.12 |             51.87 |             29.65 |         6.11 |             65.45 | swing              |               -3.51 |                   nan |                  nan |
|     15 | ZETA      | ZETA      | US       |                6.26 |             76.88 |         87.78 |         84.26 |          69.51 |        55.43 |           51.65 |             83.94 |             26.49 |         7.54 |             67.05 | short              |               -3.54 |                   nan |                  nan |
|     16 | CRDO      | CRDO      | US       |               41.88 |             76.79 |         76.8  |         76.78 |          77.42 |        68.81 |           93.19 |             67.39 |             17.7  |         8.87 |             67.5  | medium             |                1.44 |                   nan |                  nan |
|     17 | DELL      | DELL      | US       |              274.03 |             76.33 |         78.9  |         80.65 |          73.76 |        63.5  |           70.75 |             54.51 |             32.88 |         7.63 |             66.59 | swing              |               -7.46 |                   nan |                  nan |
|     18 | RMAX      | RMAX      | US       |                0.6  |             76.32 |         82.65 |         83.06 |          69.99 |        61.16 |           21.98 |             90.85 |             90.63 |         7.06 |             67.05 | swing              |              -10.27 |                   nan |                  nan |
|     19 | ZD        | ZD        | US       |                1.64 |             76    |         68.8  |         81.6  |          78.7  |        73.29 |           53.2  |             87.97 |             87.35 |         5.2  |             67.05 | swing              |               -8.77 |                   nan |                  nan |
|     20 | U         | U         | US       |               17.59 |             75.94 |         83.98 |         86.62 |          67.9  |        52.47 |           48.36 |             96.75 |             24.47 |         8.24 |             67.5  | swing              |                1.09 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.27 |                    74.47 |                 76.67 |              74.4  |                79.64 |                   20.36 |           83.15 |             73.08 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    74.03 |                 73.61 |              73.04 |                75.1  |                   24.9  |           86.96 |             38.89 |       0.624 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  73.29 |                    74    |                 75.68 |              74.25 |                86.68 |                   13.32 |           83.54 |             58.71 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    73.03 |                 75.41 |              69.96 |                72.48 |                   27.52 |           87.33 |             81.55 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    71.78 |                 73.38 |              71.23 |                69.04 |                   30.96 |           81.06 |             68.7  |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  66.9  |                    71.42 |                 73.12 |              67.55 |                78.64 |                   21.36 |           93.55 |             52.23 |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.43 |                    70.79 |                 69.45 |              73.55 |                71.54 |                   28.46 |           63.46 |             56.43 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            7 | AMCX     | AMC Global Media Inc.                                | US       |                0.44 |                  73.8  |                    69.55 |                 67.86 |              74.31 |                74.17 |                   25.83 |           47.17 |             78.26 |       1.969 |         nan |       nan |        7.08 |         4.47 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.85 |                  69.03 |                    69.25 |                 68.88 |              69.92 |                73.48 |                   26.52 |           65.85 |            nan    |       0.26  |         nan |       nan |        1.54 |       nan    |          2.66 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.28 |                    69.08 |                 70.26 |              68.37 |                70.83 |                   29.17 |           84.43 |             42.99 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE  | PAH3.DE                                              | EUROPE   |                8.46 |                  63.27 |                    68.76 |                 70.46 |              68.14 |                79.19 |                   20.81 |          nan    |             83.27 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO     | Broadcom Inc.                                        | US       |             1615.59 |                  59.62 |                    68.35 |                 69.17 |              63.67 |                79.3  |                   20.7  |           82.97 |             64.73 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.6  |                    67.7  |                 68.77 |              65.3  |                73.43 |                   26.57 |           81.31 |             55.72 |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  67.55 |                    67.69 |                 69.5  |              67.76 |                74.92 |                   25.08 |           77.61 |             56.4  |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.72 |                    67.62 |                 67.18 |              72.05 |                59.2  |                   40.8  |           50.61 |             83.14 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           13 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               35.41 |                  60.43 |                    67.3  |                 71.11 |              65.71 |                76.46 |                   23.54 |           79.13 |             84.42 |       0.041 |         nan |       nan |        7.16 |         6.37 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                                  | US       |               14.87 |                  59.56 |                    67.23 |                 69.82 |              63.17 |                77.89 |                   22.11 |           87.74 |             62.7  |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                                               | EUROPE   |               37.62 |                  68.36 |                    67    |                 66.56 |              67.16 |                64.66 |                   35.34 |          nan    |             63.06 |     nan     |         nan |       nan |      nan    |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                                              | EUROPE   |               36.96 |                  69.12 |                    66.54 |                 65.76 |              66.82 |                61.4  |                   38.6  |          nan    |             60.05 |     nan     |         nan |       nan |      nan    |         3.13 |          7.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | UNIT     | Uniti Group Inc.                                     | US       |                2.1  |                  80.26 |                    66.27 |                 63.02 |              68.71 |                44.15 |                   55.85 |           63.29 |             29.7  |      -0.106 |         nan |       nan |        9.1  |       -14.1  |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.27 |                    74.47 |                 76.67 |              74.4  |                79.64 |                   20.36 |           83.15 |             73.08 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  73.29 |                    74    |                 75.68 |              74.25 |                86.68 |                   13.32 |           83.54 |             58.71 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    73.03 |                 75.41 |              69.96 |                72.48 |                   27.52 |           87.33 |             81.55 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    74.03 |                 73.61 |              73.04 |                75.1  |                   24.9  |           86.96 |             38.89 |       0.624 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  72.12 |                    71.78 |                 73.38 |              71.23 |                69.04 |                   30.96 |           81.06 |             68.7  |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  66.9  |                    71.42 |                 73.12 |              67.55 |                78.64 |                   21.36 |           93.55 |             52.23 |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               35.41 |                  60.43 |                    67.3  |                 71.11 |              65.71 |                76.46 |                   23.54 |           79.13 |             84.42 |       0.041 |         nan |       nan |        7.16 |         6.37 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE  | PAH3.DE                                              | EUROPE   |                8.46 |                  63.27 |                    68.76 |                 70.46 |              68.14 |                79.19 |                   20.81 |          nan    |             83.27 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.28 |                    69.08 |                 70.26 |              68.37 |                70.83 |                   29.17 |           84.43 |             42.99 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                                  | US       |               14.87 |                  59.56 |                    67.23 |                 69.82 |              63.17 |                77.89 |                   22.11 |           87.74 |             62.7  |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  67.55 |                    67.69 |                 69.5  |              67.76 |                74.92 |                   25.08 |           77.61 |             56.4  |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.43 |                    70.79 |                 69.45 |              73.55 |                71.54 |                   28.46 |           63.46 |             56.43 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           10 | AVGO     | Broadcom Inc.                                        | US       |             1615.59 |                  59.62 |                    68.35 |                 69.17 |              63.67 |                79.3  |                   20.7  |           82.97 |             64.73 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.85 |                  69.03 |                    69.25 |                 68.88 |              69.92 |                73.48 |                   26.52 |           65.85 |            nan    |       0.26  |         nan |       nan |        1.54 |       nan    |          2.66 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.6  |                    67.7  |                 68.77 |              65.3  |                73.43 |                   26.57 |           81.31 |             55.72 |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                  | US       |                7.93 |                  59.85 |                    66.06 |                 68.39 |              62.35 |                72.44 |                   27.56 |           85.04 |             62.21 |     nan     |         nan |       nan |      nan    |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               17.82 |                  59.67 |                    65.92 |                 68.22 |              60.65 |                76.65 |                   23.35 |           96.11 |             38.99 |     nan     |         nan |       nan |      nan    |        10.34 |         14    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | AMCX     | AMC Global Media Inc.                                | US       |                0.44 |                  73.8  |                    69.55 |                 67.86 |              74.31 |                74.17 |                   25.83 |           47.17 |             78.26 |       1.969 |         nan |       nan |        7.08 |         4.47 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                                                  | US       |                2.72 |                  62.89 |                    65.98 |                 67.41 |              62.19 |                69.97 |                   30.03 |           88.6  |             43.08 |     nan     |         nan |       nan |      nan    |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.72 |                    67.62 |                 67.18 |              72.05 |                59.2  |                   40.8  |           50.61 |             83.14 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.94 |                     0.06 |    -0.03 |      0.18 |                  78.19 |                        85.03 |         78.78 |         86.17 |          78.78 |        75.81 |           78.07 |             97.35 |         5.79 |
|               2 | HALO     | HALO     | US       |                9.68 |                     0.04 |    -0.04 |      0.27 |                  76.17 |                        78.3  |         78.39 |         78.65 |          74.53 |        77.01 |           86.67 |             68.11 |         5.29 |
|               3 | CCC      | CCC      | US       |                3.55 |                     0.02 |     0.01 |      0.15 |                  47.72 |                        75.91 |         75.51 |         78.75 |          72.63 |        74.13 |           87.52 |             79.18 |         7.77 |
|               4 | TIC      | TIC      | US       |                1.86 |                     0.07 |    -0.02 |      0.44 |                  70.44 |                        75.57 |         78.41 |         64.83 |          59.21 |        60.88 |           57.49 |             95.31 |         7.62 |
|               5 | AMRX     | AMRX     | US       |                5.46 |                     0.05 |     0    |      0.02 |                  67.42 |                        74.95 |         61.32 |         73.17 |          75.98 |        75.34 |           93.44 |             63.78 |         4.35 |
|               6 | TGB      | TGB      | US       |                2.64 |                     0.05 |     0    |      0.23 |                  68.72 |                        73.37 |         78.49 |         65.79 |          67.3  |        68.35 |           56.84 |             83.03 |         7.52 |
|               7 | SNOW     | SNOW     | US       |               98.51 |                     0.03 |    -0    |      0.22 |                  53.69 |                        73.3  |         75.34 |         84.46 |          68.51 |        48.49 |           44.43 |             94.22 |         8.83 |
|               8 | PLTR     | PLTR     | US       |              361.39 |                     0.03 |     0.01 |      0.31 |                  50.53 |                        73.07 |         79.86 |         66.69 |          58.42 |        55.22 |           90.15 |             50.18 |         8.27 |
|               9 | OKTA     | OKTA     | US       |               22.14 |                     0.05 |    -0.01 |     -0.01 |                  68.58 |                        72.65 |         56.09 |         76.22 |          72.63 |        61.18 |           68.9  |             69.8  |         7.44 |
|              10 | GH       | GH       | US       |               18.23 |                     0.07 |    -0.07 |      0.01 |                  82.98 |                        72.57 |         50.9  |         74.5  |          76.39 |        72.82 |           63.97 |             67.15 |         6.73 |
|              11 | CLOV     | CLOV     | US       |                2.11 |                     0.04 |    -0.03 |     -0    |                  71.14 |                        72.25 |         50.55 |         73.62 |          73.98 |        57.71 |           55.44 |             91.22 |         8.43 |
|              12 | AXTI     | AXTI     | US       |                4.63 |                     0.08 |    -0.08 |      0.78 |                  79.23 |                        72.05 |         73.49 |         60.19 |          68.82 |        54.99 |           54.95 |             82.91 |         9.77 |
|              13 | ELF      | ELF      | US       |                4.66 |                     0.07 |    -0.07 |      0.24 |                  81.45 |                        71.47 |         67.33 |         71.86 |          58.27 |        52.08 |           61.15 |             74.01 |         8.21 |
|              14 | PENN     | PENN     | US       |                2.18 |                     0.11 |    -0.07 |     -0.09 |                  53.82 |                        71.11 |         38.1  |         68.44 |          75.2  |        72.42 |           78.17 |             87.85 |         6.55 |
|              15 | METSB.HE | METSB.HE | EUROPE   |                1.09 |                     0.06 |     0.01 |      0.23 |                  63.05 |                        70.85 |         79.44 |         65.84 |          56.58 |        54.92 |           47.07 |             81.71 |         4.27 |
|              16 | QNST     | QNST     | US       |                1.02 |                     0.07 |    -0.03 |      0.22 |                  70.17 |                        70.71 |         76.07 |         75.03 |          69.83 |        71.89 |           85.12 |             34.18 |         7.8  |
|              17 | DSFIR.AS | DSFIR.AS | EUROPE   |               22.13 |                     0.05 |    -0.05 |      0.04 |                  80.21 |                        70.53 |         56.93 |         70.91 |          64.26 |        54.48 |           63.87 |             68.47 |         5.45 |
|              18 | GL9.IR   | GL9.IR   | EUROPE   |                5.61 |                     0.03 |    -0.03 |      0.01 |                  65.7  |                        70.52 |         50.68 |         63.67 |          73.58 |        70.24 |           97.66 |             61.97 |         2.17 |
|              19 | CART     | CART     | US       |                9.78 |                     0.03 |    -0.03 |      0.07 |                  64.85 |                        70.05 |         65.2  |         72.28 |          69.69 |        69.89 |           71.78 |             65.46 |         5.51 |
|              20 | EXLS     | EXLS     | US       |                4.56 |                     0.03 |    -0    |      0.24 |                  57.5  |                        70    |         73.29 |         65.25 |          60.23 |        66.14 |           83.78 |             53.19 |         6.98 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4712.46 |             63.83 |         66.79 |         56.69 |          62.42 |        65.25 |           94.57 |             59.76 |             30.53 |         5.39 |             89.53 | short              |               -0.17 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.62 |         58.52 |         60.72 |          56.95 |        61.91 |           56.13 |             48.9  |             71.96 |         8.3  |             85.47 | long               |                0.02 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.18 |             53.83 |         52.46 |         59.05 |          55.19 |        49.51 |           49.34 |             49.08 |             34.6  |         4.72 |             81.91 | swing              |                0.39 |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.38 |             45.58 |         34.52 |         42.36 |          48.8  |        61.54 |           65.22 |             45.38 |             78.89 |         7.41 |             87.87 | long               |               -0.44 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             43.71 |         51.8  |         49.27 |          38.15 |        35.74 |           32.89 |             28.68 |             36.79 |         5.9  |             78.55 | short              |                1.1  |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             39.01 |         26.08 |         34.99 |          43.04 |        54.66 |           50.26 |             46.87 |             77.74 |         6.15 |             78.58 | long               |                0.61 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             38.88 |         28.86 |         36    |          41.77 |        54.54 |           47.64 |             41.34 |             85.58 |         7.13 |             78.43 | long               |                0.72 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             37.06 |         40.52 |         25.63 |          33.61 |        43.38 |           51.97 |             37.91 |             49.64 |         7.02 |             76.3  | long               |                1.46 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.87 |         32.43 |         31.47 |          41.3  |        58.48 |           68.2  |             24.69 |             78.81 |         4.68 |             81.52 | long               |               -0.38 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             35.26 |         31.13 |         23.42 |          39.39 |        52.03 |           74.28 |             19.71 |             44.44 |         8.99 |             78.45 | long               |                1.21 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             27.86 |         53.16 |         23.71 |          23.69 |        32.01 |           29.35 |             27.01 |             50    |         7.68 |             76.14 | short              |                1.48 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.4  |             26.97 |         29.4  |         23.6  |          25.55 |        28.4  |           31.16 |             39.19 |             26.04 |         6.82 |             76.54 | short              |                4.02 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
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
- Excluded by hard/data filters: **280**
- Event watch (otherwise eligible): **12**
- Final eligible: **708**
- Eligible change vs previous stored run: **+4**

Top exclusion categories:
- liquidity: 227
- price: 170
- market_cap: 152
- price_history: 21
- data_confidence: 17
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 3 | 4 |  | 3 | 2 | main,value,quality_value |
| BAX | 7 |  | 1 |  | 2 | main,pullback |
| PARR | 22 | 5 |  | 5 | 1 | value,quality_value |
| BION.SW | 91 | 3 |  | 2 | 1 | value,quality_value |
| IRWD | 127 | 1 | 38 | 1 | 1 | value,quality_value |
| AVGO | 413 | 10 | 83 | 10 | 1 | value,quality_value |
| IRS | 494 | 9 | 146 | 7 | 1 | value,quality_value |
| MOMO | 584 | 6 | 211 | 9 | 1 | value,quality_value |
| STNE | 649 | 2 |  | 4 | 1 | value,quality_value |
| JCAP | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| MPC | 4 |  |  |  | 1 | main |
| SSABBH.HE | 5 |  |  |  | 1 | main |
| FSLY | 6 |  |  |  | 1 | main |
| CLMT | 8 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **2** (JCAP, TKA.DE)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | AVGO | value+pullback | 72.23 | 59.62 | 78.27 | 82.97 | 64.73 | 79.30 | 54.31 |
| 2 | IRS | value+pullback | 71.07 | 71.28 | 74.23 | 84.43 | 42.99 | 70.83 | 51.06 |
| 3 | IRWD | value+pullback | 70.91 | 73.27 | 52.87 | 83.15 | 73.08 | 79.64 | 66.67 |
| 4 | MOMO | value+pullback | 70.15 | 76.43 | 71.01 | 63.46 | 56.43 | 71.54 | 46.74 |
| 5 | GSL | value+pullback | 65.80 | 65.19 | 70.66 | 73.91 | 37.11 | 68.89 | 59.39 |
| 6 | 0Q2N.IL | value+pullback | 64.60 | 69.03 | 57.28 | 65.85 |  | 73.48 | 52.65 |
| 7 | PBR-A | value+pullback | 63.43 | 73.63 | 65.72 | 54.53 | 68.44 | 49.44 | 55.23 |
| 8 | VOLV-B.ST | value+pullback | 63.38 | 72.97 | 65.36 | 50.75 | 58.85 | 58.28 | 53.02 |
| 9 | MTRX | value+pullback | 62.64 | 70.82 | 60.49 | 58.80 | 60.86 | 56.82 | 48.21 |
| 10 | ACCO | value+pullback | 61.99 | 69.13 | 51.24 | 71.74 | 49.84 | 63.46 | 58.66 |
| 11 | ALL-PH | value+pullback | 60.76 | 61.80 | 65.08 | 67.98 | 40.93 | 58.30 | 43.43 |
| 12 | CNXC | value+pullback | 60.62 | 83.95 | 70.58 | 45.11 | 31.56 | 39.31 | 39.42 |
| 13 | BHF | value+pullback | 60.13 | 71.19 | 55.64 | 52.41 | 41.25 | 64.40 | 42.96 |
| 14 | WKC | value+pullback | 59.74 | 60.34 | 43.77 | 61.36 | 74.51 | 70.21 | 67.15 |
| 15 | AF.PA | value+pullback | 59.12 | 67.98 | 77.15 | 39.08 | 56.90 | 39.42 | 50.48 |
| 16 | MFA | value+pullback | 58.33 | 58.61 | 49.63 | 78.94 | 37.01 | 64.00 | 45.24 |
| 17 | ONIT | value+pullback | 57.87 | 70.79 | 58.20 | 60.62 | 45.35 | 42.28 | 46.20 |
| 18 | BION.SW | value | 57.73 | 73.29 | 40.38 | 83.54 | 58.71 | 86.68 | 68.80 |
| 19 | PBR | value+pullback | 56.95 | 61.62 | 57.68 | 54.53 | 62.20 | 48.23 | 54.32 |
| 20 | BAX | pullback | 56.73 | 48.61 | 78.19 | 78.07 | 97.35 | 78.69 | 78.78 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 10/10 | 8/10 | 0/10 | 66.3 | 8 / 2 |
| Top 25 | 24/25 | 24/25 | 25/25 | 23/25 | 0/25 | 67.0 | 22 / 3 |
| Top 50 | 49/50 | 47/50 | 49/50 | 45/50 | 0/50 | 66.6 | 42 / 8 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=5, large_20_100b=2
