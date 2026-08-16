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

- **EUROPE:** 90.7/100
- **OTHER:** 76.6/100
- **US:** 87.6/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               67.4  |             81.06 |         81.74 |         85.29 |          80.38 |        72.89 |           71.83 |             72.53 |             57.82 |         6.7  |             65.68 | swing              |               -5.05 |                   nan |                  nan |
|      2 | MPC       | MPC       | US       |               86.53 |             80.34 |         80.7  |         81.46 |          79.99 |        77.87 |           85.63 |             60.12 |             64.91 |         3.83 |             67.5  | swing              |               -4.2  |                   nan |                  nan |
|      3 | AKER.OL   | Aker ASA  | EUROPE   |                9.75 |             80.28 |         83.89 |         76.75 |          81.37 |        79.19 |           87.33 |             81.74 |             63.77 |         3.38 |             74.34 | short              |               -1.65 |                   nan |                  nan |
|      4 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.73 |             79.56 |         77.2  |         78.12 |          81.01 |        83.33 |           72.04 |            nan    |             98.4  |         3.26 |             62.84 | long               |               -3.93 |                   nan |                  nan |
|      5 | FSLY      | FSLY      | US       |                4.13 |             79.06 |         86.9  |         84.32 |          73.81 |        54.37 |           43.48 |             99.04 |             16.86 |         8.37 |             67.5  | short              |               -1.77 |                   nan |                  nan |
|      6 | BAX       | BAX       | US       |               11.98 |             78.86 |         78.87 |         86.22 |          78.85 |        75.99 |           78.32 |             97.47 |             65.54 |         5.77 |             66.02 | swing              |                5.64 |                   nan |                  nan |
|      7 | CLMT      | CLMT      | US       |                3.64 |             78.18 |         83.52 |         83.14 |          73.21 |        53.55 |           51.68 |             92.53 |              5.8  |         4.42 |             66.59 | short              |               -1.35 |                   nan |                  nan |
|      8 | TKA.DE    | TKA.DE    | EUROPE   |                8.6  |             77.89 |         82.69 |         79.38 |          76.39 |        72.26 |          nan    |             83.73 |             57.47 |         6.32 |             64.66 | short              |                0.95 |                   nan |                  nan |
|      9 | GENI      | GENI      | US       |                2.02 |             77.85 |         86.51 |         82.65 |          72.82 |        73.05 |           66.48 |             97.71 |             82.85 |         9.31 |             67.5  | short              |                2.8  |                   nan |                  nan |
|     10 | PBF       | PBF       | US       |                7.38 |             77.74 |         80.8  |         80.08 |          75.39 |        72.63 |           51.98 |             55.78 |             94.26 |         6.97 |             67.05 | short              |              -14.96 |                   nan |                  nan |
|     11 | HALO      | HALO      | US       |                9.71 |             77.71 |         78.36 |         78.61 |          74.49 |        77.06 |           86.55 |             68.07 |             65.35 |         5.32 |             66.48 | swing              |                2.4  |                   nan |                  nan |
|     12 | NTAP      | NTAP      | US       |               35.23 |             77.07 |         79.19 |         81.4  |          74.94 |        68.38 |           88.6  |             52.05 |             30.3  |         6.13 |             65.45 | swing              |               -3.37 |                   nan |                  nan |
|     13 | NET       | NET       | US       |               97.48 |             76.91 |         82.34 |         82.74 |          71.47 |        53.73 |           59.47 |             93.13 |              1.83 |         6.71 |             67.5  | swing              |                2.08 |                   nan |                  nan |
|     14 | ZETA      | ZETA      | US       |                6.28 |             76.81 |         87.72 |         84.25 |          69.37 |        55.3  |           50.74 |             84.34 |             27.28 |         7.54 |             67.05 | short              |               -3.62 |                   nan |                  nan |
|     15 | CRDO      | CRDO      | US       |               42.01 |             76.77 |         76.8  |         76.75 |          77.45 |        68.96 |           93.35 |             67.35 |             18.04 |         8.88 |             67.5  | medium             |                1.43 |                   nan |                  nan |
|     16 | DELL      | DELL      | US       |              274.92 |             76.41 |         78.93 |         80.56 |          73.9  |        63.77 |           70.98 |             54.7  |             33.43 |         7.63 |             66.59 | swing              |               -7.38 |                   nan |                  nan |
|     17 | RMAX      | RMAX      | US       |                0.6  |             76.32 |         82.67 |         83.11 |          69.98 |        61.21 |           21.91 |             91.08 |             90.97 |         7.06 |             67.05 | swing              |              -10.27 |                   nan |                  nan |
|     18 | ZD        | ZD        | US       |                1.65 |             76.12 |         68.86 |         81.64 |          78.79 |        73.45 |           53.26 |             88.31 |             87.73 |         5.19 |             67.05 | swing              |               -8.65 |                   nan |                  nan |
|     19 | U         | U         | US       |               17.64 |             75.86 |         83.94 |         86.57 |          67.79 |        52.34 |           47.72 |             96.87 |             24.96 |         8.23 |             67.5  | swing              |                1.01 |                   nan |                  nan |
|     20 | STX       | STX       | US       |              191.26 |             75.86 |         82.96 |         73.78 |          77.95 |        70.59 |           84.91 |             68.55 |             35.42 |         7.3  |             67.5  | short              |               -0.34 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.27 |                    74.47 |                 76.67 |              74.39 |                79.63 |                   20.37 |           83.15 |             73.09 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    74.03 |                 73.62 |              73.05 |                75.12 |                   24.88 |           86.96 |             38.94 |       0.622 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.12 |                  73.29 |                    74    |                 75.67 |              74.24 |                86.66 |                   13.34 |           83.54 |             58.72 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    73.05 |                 75.45 |              69.99 |                72.52 |                   27.48 |           87.33 |             81.74 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.49 |                  72.12 |                    71.78 |                 73.39 |              71.23 |                69.04 |                   30.96 |           81.06 |             68.74 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              215.21 |                  67.13 |                    71.52 |                 73.18 |              67.71 |                78.53 |                   21.47 |           93.32 |             52.41 |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.43 |                    70.8  |                 69.46 |              73.55 |                71.54 |                   28.46 |           63.46 |             56.5  |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            7 | AMCX     | AMC Global Media Inc.                                | US       |                0.44 |                  73.8  |                    69.55 |                 67.86 |              74.31 |                74.17 |                   25.83 |           47.17 |             78.25 |       1.969 |         nan |       nan |        7.08 |         4.47 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            8 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.85 |                  69.79 |                    69.4  |                 68.69 |              70.57 |                73.68 |                   26.32 |           63.71 |            nan    |       0.26  |         nan |       nan |        1.54 |       nan    |          2.66 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | PAH3.DE  | PAH3.DE                                              | EUROPE   |                8.46 |                  63.86 |                    69.23 |                 70.9  |              68.62 |                79.3  |                   20.7  |          nan    |             83.61 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  71.28 |                    69.09 |                 70.27 |              68.38 |                70.85 |                   29.15 |           84.43 |             43.02 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           10 | AVGO     | Broadcom Inc.                                        | US       |             1620.83 |                  59.62 |                    68.36 |                 69.18 |              63.68 |                79.33 |                   20.67 |           82.97 |             64.77 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                                  | US       |              113.03 |                  64.38 |                    67.7  |                 68.85 |              65.21 |                73.68 |                   26.32 |           81.75 |             55.9  |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  67.55 |                    67.69 |                 69.5  |              67.76 |                74.9  |                   25.1  |           77.61 |             56.42 |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | IHS      | IHS Holding Limited                                  | OTHER    |                2.44 |                  73.72 |                    67.62 |                 67.18 |              72.05 |                59.19 |                   40.81 |           50.61 |             83.18 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           13 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               35.53 |                  60.43 |                    67.3  |                 71.11 |              65.71 |                76.45 |                   23.55 |           79.13 |             84.44 |       0.041 |         nan |       nan |        7.16 |         6.37 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW.DE   | VOW.DE                                               | EUROPE   |               37.62 |                  68.26 |                    66.99 |                 66.58 |              67.14 |                64.75 |                   35.25 |          nan    |             63.37 |     nan     |         nan |       nan |      nan    |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                  | US       |               14.91 |                  58.99 |                    66.99 |                 69.69 |              62.81 |                78    |                   22    |           87.96 |             63.01 |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               17.82 |                  60.59 |                    66.56 |                 68.78 |              61.4  |                76.79 |                   23.21 |           96.26 |             39.52 |     nan     |         nan |       nan |      nan    |        10.34 |         14    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                                              | EUROPE   |               36.96 |                  69.01 |                    66.54 |                 65.8  |              66.81 |                61.59 |                   38.41 |          nan    |             60.36 |     nan     |         nan |       nan |      nan    |         3.13 |          7.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD      | Ironwood Pharmaceuticals, Inc.                       | US       |                0.62 |                  73.27 |                    74.47 |                 76.67 |              74.39 |                79.63 |                   20.37 |           83.15 |             73.09 |       0.171 |         nan |       nan |        4.32 |         2.93 |          5.46 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW   | BB Biotech AG                                        | EUROPE   |                3.12 |                  73.29 |                    74    |                 75.67 |              74.24 |                86.66 |                   13.34 |           83.54 |             58.72 |       0.844 |         nan |       nan |      nan    |       -80.73 |          2.16 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | AKER.OL   | Aker ASA                                             | EUROPE   |                9.75 |                  67.72 |                    73.05 |                 75.45 |              69.99 |                72.52 |                   27.48 |           87.33 |             81.74 |       0.113 |         nan |       nan |        5.32 |        54.86 |          3.78 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE      | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.27 |                    74.03 |                 73.62 |              73.05 |                75.12 |                   24.88 |           86.96 |             38.94 |       0.622 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | PARR      | Par Pacific Holdings, Inc.                           | US       |                3.49 |                  72.12 |                    71.78 |                 73.39 |              71.23 |                69.04 |                   30.96 |           81.06 |             68.74 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                                             | EUROPE   |              215.21 |                  67.13 |                    71.52 |                 73.18 |              67.71 |                78.53 |                   21.47 |           93.32 |             52.41 |     nan     |         nan |       nan |      nan    |         9.72 |          9.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | HMC       | Honda Motor Company, Ltd.                            | OTHER    |               35.53 |                  60.43 |                    67.3  |                 71.11 |              65.71 |                76.45 |                   23.55 |           79.13 |             84.44 |       0.041 |         nan |       nan |        7.16 |         6.37 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE   | PAH3.DE                                              | EUROPE   |                8.46 |                  63.86 |                    69.23 |                 70.9  |              68.62 |                79.3  |                   20.7  |          nan    |             83.61 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  71.28 |                    69.09 |                 70.27 |              68.38 |                70.85 |                   29.15 |           84.43 |             43.02 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN       | BEN                                                  | US       |               14.91 |                  58.99 |                    66.99 |                 69.69 |              62.81 |                78    |                   22    |           87.96 |             63.01 |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI    | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  67.55 |                    67.69 |                 69.5  |              67.76 |                74.9  |                   25.1  |           77.61 |             56.42 |       0.974 |         nan |       nan |        5.32 |      -120.77 |          2.12 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | MOMO      | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.43 |                    70.8  |                 69.46 |              73.55 |                71.54 |                   28.46 |           63.46 |             56.5  |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           10 | AVGO      | Broadcom Inc.                                        | US       |             1620.83 |                  59.62 |                    68.36 |                 69.18 |              63.68 |                79.33 |                   20.67 |           82.97 |             64.77 |       0.015 |         nan |       nan |       45.5  |        20.12 |         65.39 |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                                  | US       |              113.03 |                  64.38 |                    67.7  |                 68.85 |              65.21 |                73.68 |                   26.32 |           81.75 |             55.9  |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                                              | EUROPE   |               17.82 |                  60.59 |                    66.56 |                 68.78 |              61.4  |                76.79 |                   23.21 |           96.26 |             39.52 |     nan     |         nan |       nan |      nan    |        10.34 |         14    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | 0Q2N.IL   | K+S Aktiengesellschaft                               | OTHER    |                2.85 |                  69.79 |                    69.4  |                 68.69 |              70.57 |                73.68 |                   26.32 |           63.71 |            nan    |       0.26  |         nan |       nan |        1.54 |       nan    |          2.66 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO       | FRO                                                  | US       |                7.95 |                  59.39 |                    65.88 |                 68.29 |              62.08 |                72.6  |                   27.4  |           85.18 |             62.53 |     nan     |         nan |       nan |      nan    |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | AMCX      | AMC Global Media Inc.                                | US       |                0.44 |                  73.8  |                    69.55 |                 67.86 |              74.31 |                74.17 |                   25.83 |           47.17 |             78.25 |       1.969 |         nan |       nan |        7.08 |         4.47 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT       | DHT                                                  | US       |                2.73 |                  62.99 |                    66.13 |                 67.57 |              62.32 |                70.13 |                   29.87 |           88.77 |             43.37 |     nan     |         nan |       nan |      nan    |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           28 | INDU-C.ST | AB Industrivärden (publ)                             | EUROPE   |               20.37 |                  48.01 |                    62.54 |                 67.4  |              56.88 |                78.55 |                   21.45 |           87.02 |             81.74 |       0.176 |         nan |       nan |        3.58 |       nan    |          3.57 |        5.47 |                 nan |              nan |                   9 |                  0.47 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX       | BAX                      | US       |               11.98 |                     0.06 |    -0.03 |      0.18 |                  78.19 |                        85.12 |         78.87 |         86.22 |          78.85 |        75.99 |           78.32 |             97.47 |         5.77 |
|               2 | HALO      | HALO                     | US       |                9.71 |                     0.04 |    -0.04 |      0.27 |                  76.17 |                        78.25 |         78.36 |         78.61 |          74.49 |        77.06 |           86.55 |             68.07 |         5.32 |
|               3 | CCC       | CCC                      | US       |                3.56 |                     0.02 |     0.01 |      0.15 |                  47.72 |                        76.01 |         75.67 |         78.85 |          72.76 |        74.29 |           87.53 |             79.52 |         7.76 |
|               4 | TIC       | TIC                      | US       |                1.86 |                     0.07 |    -0.02 |      0.44 |                  70.44 |                        75.53 |         78.43 |         64.79 |          59.19 |        60.88 |           57.17 |             95.42 |         7.61 |
|               5 | AMRX      | AMRX                     | US       |                5.48 |                     0.05 |     0    |      0.02 |                  67.42 |                        75.04 |         61.25 |         73.23 |          76.08 |        75.48 |           93.59 |             63.98 |         4.32 |
|               6 | TGB       | TGB                      | US       |                2.65 |                     0.05 |     0    |      0.23 |                  68.72 |                        73.41 |         78.57 |         65.78 |          67.34 |        68.45 |           56.53 |             83.37 |         7.53 |
|               7 | SNOW      | SNOW                     | US       |               98.83 |                     0.03 |    -0    |      0.22 |                  53.69 |                        73.13 |         75.33 |         84.37 |          68.3  |        48.2  |           43.72 |             94.34 |         8.83 |
|               8 | PLTR      | PLTR                     | US       |              362.56 |                     0.03 |     0.01 |      0.31 |                  50.53 |                        73.11 |         79.86 |         66.7  |          58.48 |        55.3  |           90.3  |             50.24 |         8.28 |
|               9 | OKTA      | OKTA                     | US       |               22.21 |                     0.05 |    -0.01 |     -0.01 |                  68.58 |                        72.76 |         56.09 |         76.2  |          72.77 |        61.52 |           69.43 |             69.88 |         7.44 |
|              10 | GH        | GH                       | US       |               18.29 |                     0.07 |    -0.07 |      0.01 |                  82.98 |                        72.36 |         50.81 |         74.36 |          76.18 |        72.47 |           63.36 |             67.11 |         6.72 |
|              11 | CLOV      | CLOV                     | US       |                2.12 |                     0.04 |    -0.03 |     -0    |                  71.14 |                        72.16 |         50.49 |         73.55 |          73.91 |        57.64 |           54.99 |             91.45 |         8.44 |
|              12 | AXTI      | AXTI                     | US       |                4.64 |                     0.08 |    -0.08 |      0.78 |                  79.23 |                        72.09 |         73.52 |         60.23 |          68.88 |        55.06 |           54.76 |             83.25 |         9.76 |
|              13 | PENN      | PENN                     | US       |                2.19 |                     0.11 |    -0.07 |     -0.09 |                  53.82 |                        71.27 |         38.25 |         68.54 |          75.29 |        72.62 |           78.5  |             88.19 |         6.54 |
|              14 | ELF       | ELF                      | US       |                4.68 |                     0.07 |    -0.07 |      0.24 |                  81.45 |                        71.24 |         67.36 |         71.85 |          58.09 |        51.76 |           59.81 |             74.22 |         8.21 |
|              15 | METSB.HE  | METSB.HE                 | EUROPE   |                1.09 |                     0.06 |     0.01 |      0.23 |                  63.05 |                        70.75 |         79.43 |         65.9  |          56.55 |        54.81 |           46.26 |             82.17 |         4.3  |
|              16 | QNST      | QNST                     | US       |                1.02 |                     0.07 |    -0.03 |      0.22 |                  70.17 |                        70.73 |         76.17 |         75.07 |          69.82 |        71.99 |           84.64 |             34.58 |         7.8  |
|              17 | GL9.IR    | GL9.IR                   | EUROPE   |                5.61 |                     0.03 |    -0.03 |      0.01 |                  65.7  |                        70.5  |         50.59 |         63.55 |          73.57 |        70.23 |           97.61 |             62.29 |         2.19 |
|              18 | INDU-C.ST | AB Industrivärden (publ) | EUROPE   |               20.37 |                     0.08 |    -0.06 |     -0    |                  74.54 |                        70.36 |         45.52 |         59.04 |          68.89 |        69.61 |           87.02 |             81.74 |         2.44 |
|              19 | DSFIR.AS  | DSFIR.AS                 | EUROPE   |               22.13 |                     0.05 |    -0.05 |      0.04 |                  80.21 |                        70.28 |         56.67 |         70.74 |          64.05 |        54.32 |           63.06 |             68.43 |         5.44 |
|              20 | CART      | CART                     | US       |                9.81 |                     0.03 |    -0.03 |      0.07 |                  64.85 |                        70.19 |         65.47 |         72.34 |          69.85 |        70.24 |           72.29 |             65.54 |         5.48 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4727.73 |             63.76 |         66.74 |         56.6  |          62.34 |        65.18 |           94.57 |             59.79 |             30.53 |         5.4  |             89.53 | short              |               -0.25 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.89 |             59.65 |         58.58 |         60.72 |          56.88 |        61.85 |           56.13 |             48.95 |             71.96 |         8.3  |             85.47 | long               |                0.05 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.19 |             53.75 |         52.35 |         58.98 |          55.16 |        49.48 |           49.34 |             49.07 |             34.6  |         4.73 |             81.91 | swing              |                0.32 |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.39 |             45.57 |         34.75 |         42.33 |          48.8  |        61.54 |           65.22 |             45.41 |             78.89 |         7.41 |             87.87 | long               |               -0.45 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             43.72 |         51.74 |         49.25 |          38.19 |        35.73 |           32.89 |             28.7  |             36.79 |         5.9  |             78.55 | short              |                1.11 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.9  |             39.04 |         26.12 |         35.01 |          43.06 |        54.67 |           50.26 |             46.89 |             77.74 |         6.14 |             78.58 | long               |                0.63 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.3  |             38.9  |         28.86 |         36    |          41.79 |        54.55 |           47.64 |             41.37 |             85.58 |         7.13 |             78.43 | long               |                0.73 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             37.08 |         40.53 |         25.62 |          33.62 |        43.37 |           51.97 |             37.94 |             49.64 |         7.02 |             76.3  | long               |                1.47 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.83 |         32.33 |         31.45 |          41.33 |        58.48 |           68.2  |             24.74 |             78.81 |         4.7  |             81.52 | long               |               -0.41 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             35.25 |         31.13 |         23.42 |          39.36 |        51.98 |           74.28 |             19.72 |             44.44 |         8.99 |             78.45 | long               |                1.19 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.43 |             27.93 |         29.57 |         23.86 |          26.29 |        29.58 |           34.09 |             39.17 |             26.04 |         6.82 |             76.54 | long               |                4.98 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             27.88 |         53.23 |         23.74 |          23.7  |        32.02 |           29.35 |             27.02 |             50    |         7.67 |             76.14 | short              |                1.5  |                   nan |                  nan |

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
- Excluded by hard/data filters: **279**
- Event watch (otherwise eligible): **12**
- Final eligible: **709**
- Eligible change vs previous stored run: **+5**

Top exclusion categories:
- liquidity: 225
- price: 170
- market_cap: 152
- price_history: 20
- data_confidence: 16
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 3 | 4 |  | 3 | 2 | main,value,quality_value |
| BAX | 6 |  | 1 |  | 2 | main,pullback |
| PARR | 21 | 5 |  | 5 | 1 | value,quality_value |
| BION.SW | 88 | 3 |  | 2 | 1 | value,quality_value |
| IRWD | 124 | 1 | 37 | 1 | 1 | value,quality_value |
| AVGO | 417 | 10 | 85 | 10 | 1 | value,quality_value |
| IRS | 496 | 9 | 149 | 7 | 1 | value,quality_value |
| MOMO | 587 | 6 | 211 | 9 | 1 | value,quality_value |
| STNE | 653 | 2 |  | 4 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MPC | 2 |  |  |  | 1 | main |
| SSABBH.HE | 4 |  |  |  | 1 | main |
| FSLY | 5 |  |  |  | 1 | main |
| CLMT | 7 |  |  |  | 1 | main |
| TKA.DE | 8 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **1** (TKA.DE)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | AVGO | value+pullback | 72.24 | 59.62 | 78.27 | 82.97 | 64.77 | 79.33 | 54.28 |
| 2 | IRS | value+pullback | 71.08 | 71.28 | 74.23 | 84.43 | 43.02 | 70.85 | 51.03 |
| 3 | IRWD | value+pullback | 70.90 | 73.27 | 52.87 | 83.15 | 73.09 | 79.63 | 66.66 |
| 4 | MOMO | value+pullback | 70.16 | 76.43 | 71.01 | 63.46 | 56.50 | 71.54 | 46.74 |
| 5 | GSL | value+pullback | 65.80 | 65.19 | 70.66 | 73.91 | 37.15 | 68.88 | 59.24 |
| 6 | 0Q2N.IL | value+pullback | 64.55 | 69.79 | 57.28 | 63.71 |  | 73.68 | 52.50 |
| 7 | PBR-A | value+pullback | 63.42 | 73.63 | 65.72 | 54.53 | 68.45 | 49.41 | 55.22 |
| 8 | VOLV-B.ST | value+pullback | 63.38 | 72.97 | 65.36 | 50.75 | 58.86 | 58.25 | 52.92 |
| 9 | MTRX | value+pullback | 62.64 | 70.82 | 60.49 | 58.80 | 60.86 | 56.82 | 48.18 |
| 10 | ACCO | value+pullback | 61.99 | 69.13 | 51.24 | 71.74 | 49.90 | 63.48 | 58.62 |
| 11 | ALL-PH | value+pullback | 60.76 | 61.72 | 65.08 | 67.98 | 41.10 | 58.33 | 43.40 |
| 12 | CNXC | value+pullback | 60.62 | 83.95 | 70.58 | 45.11 | 31.59 | 39.32 | 39.40 |
| 13 | BHF | value+pullback | 60.13 | 71.19 | 55.64 | 52.41 | 41.27 | 64.39 | 42.89 |
| 14 | WKC | value+pullback | 59.73 | 60.34 | 43.77 | 61.36 | 74.51 | 70.18 | 67.10 |
| 15 | MFA | value+pullback | 59.30 | 58.61 | 53.52 | 78.94 | 37.05 | 63.97 | 45.11 |
| 16 | AF.PA | value+pullback | 59.12 | 67.98 | 77.15 | 39.08 | 56.94 | 39.43 | 50.47 |
| 17 | ONIT | value+pullback | 57.85 | 70.79 | 58.20 | 60.47 | 45.38 | 42.26 | 46.13 |
| 18 | BION.SW | value | 57.72 | 73.29 | 40.38 | 83.54 | 58.72 | 86.66 | 68.70 |
| 19 | PBR | value+pullback | 56.95 | 61.62 | 57.68 | 54.53 | 62.23 | 48.22 | 54.28 |
| 20 | BAX | pullback | 56.82 | 48.53 | 78.19 | 78.32 | 97.47 | 78.87 | 78.86 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 10/10 | 8/10 | 0/10 | 66.8 | 9 / 1 |
| Top 25 | 24/25 | 24/25 | 25/25 | 23/25 | 0/25 | 67.0 | 21 / 4 |
| Top 50 | 49/50 | 47/50 | 49/50 | 45/50 | 0/50 | 66.9 | 43 / 7 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=5, large_20_100b=2
