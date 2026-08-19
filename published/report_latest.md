# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-19

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

- **EUROPE:** 89.2/100
- **OTHER:** 72.4/100
- **US:** 85.0/100

## Main multi-horizon ranking

|   rank | symbol    | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC       | MPC                        | US       |               88.79 |             80.65 |         81.77 |         82.24 |          79.53 |        76.45 |           84.24 |             59.54 |             61.38 |         3.94 |             67.5  | swing              |              nan    |                 -0.87 |                  nan |
|      2 | HALO      | HALO                       | US       |               10.28 |             79.53 |         85.76 |         82.88 |          75.15 |        76.18 |           86.41 |             68.53 |             60.91 |         5.47 |             66.48 | short              |              nan    |                  0.83 |                  nan |
|      3 | PBF       | PBF                        | US       |                7.7  |             78.86 |         83.3  |         82.19 |          75.54 |        72.13 |           51.05 |             56.5  |             93.17 |         7    |             67.05 | short              |                1.2  |                 -2.75 |                  nan |
|      4 | SSABBH.HE | SSABBH.HE                  | EUROPE   |                9.52 |             78.36 |         74.9  |         75.11 |          81.61 |        84.03 |           74.11 |            nan    |             98.49 |         3.27 |             62.84 | long               |              nan    |                 -1.17 |                  nan |
|      5 | RMAX      | RMAX                       | US       |                0.65 |             78.03 |         86    |         86.21 |          70.05 |        60.25 |           20.7  |             91.13 |             87.65 |         7.16 |             67.05 | swing              |                1.09 |                 -1.77 |                  nan |
|      6 | PSX       | PSX                        | US       |               84.28 |             77.66 |         79.17 |         79.37 |          76.14 |        74.31 |           79.11 |             54.56 |             65.36 |         3.32 |             67.5  | swing              |                1.42 |                nan    |                  nan |
|      7 | CRGY      | CRGY                       | US       |                4.4  |             76.98 |         81.67 |         68.64 |          74.57 |        79.39 |           70.87 |             83.23 |             97.09 |         5.99 |             67.05 | short              |              nan    |                nan    |                  nan |
|      8 | U         | U                          | US       |               17.76 |             76.98 |         86.18 |         87.11 |          67.77 |        51.35 |           46.33 |             97.08 |             22.08 |         8.28 |             67.5  | swing              |                0.76 |                  0.43 |                  nan |
|      9 | HPE       | HPE                        | US       |               63.67 |             76.96 |         73.45 |         82.43 |          80.47 |        73.07 |           71.58 |             72.9  |             58.64 |         6.77 |             65.68 | swing              |               -3.55 |                 -1.85 |                  nan |
|     10 | NTAP      | NTAP                       | US       |               34.68 |             76.8  |         79.48 |         80.34 |          74.12 |        66.87 |           86.78 |             51.64 |             27.27 |         6.16 |             65.45 | swing              |                0.69 |                 -0.73 |                  nan |
|     11 | CCC       | CCC                        | US       |                3.63 |             76.41 |         82.3  |         79.9  |          72.82 |        72.91 |           86.72 |             79.22 |             60.49 |         7.92 |             66.02 | short              |                4.02 |                  1.66 |                  nan |
|     12 | BAX       | BAX                        | US       |               11.58 |             76.38 |         75.93 |         83.7  |          76.82 |        74.71 |           76.51 |             97.57 |             63.26 |         5.89 |             66.02 | swing              |                0.17 |                  0.58 |                  nan |
|     13 | ZD        | ZD                         | US       |                1.63 |             75.99 |         73.38 |         82.69 |          78.61 |        73.25 |           52.38 |             88.7  |             88.28 |         5.39 |             67.05 | swing              |              nan    |                 -1.81 |                  nan |
|     14 | RNW       | RNW                        | US       |                2.15 |             75.71 |         76.23 |         75.19 |          73.62 |        78.26 |           84.08 |             84.33 |             81.63 |         6.19 |             65.68 | long               |               -0.43 |                  1.21 |                  nan |
|     15 | PARR      | Par Pacific Holdings, Inc. | US       |                3.48 |             75.32 |         69.32 |         74.95 |          78.38 |        75.68 |           81.06 |             65.13 |             68.07 |         6.66 |             85.72 | medium             |               -5.5  |                  0.02 |                  nan |
|     16 | DHT       | DHT                        | US       |                2.69 |             75.08 |         77.26 |         70.3  |          72.9  |        77.45 |           88.24 |             42.89 |             73.7  |         4.2  |             67.5  | long               |                0.95 |                  0.12 |                  nan |
|     17 | TKA.DE    | TKA.DE                     | EUROPE   |                8.25 |             75.06 |         77.37 |         74.68 |          75.44 |        72.86 |          nan    |             83.96 |             59.16 |         6.49 |             64.66 | short              |               -1.64 |                 -0.55 |                  nan |
|     18 | SBLK      | SBLK                       | US       |                2.9  |             75.03 |         80.74 |         71.95 |          72.84 |        77.22 |           74.29 |             59.05 |             87.73 |         3.82 |             67.16 | short              |              nan    |                nan    |                  nan |
|     19 | NNBR      | NNBR                       | US       |                0.27 |             74.91 |         79.19 |         83.26 |          70.62 |        53.2  |           37.06 |             87.85 |             31.36 |         9.01 |             66.48 | swing              |               -1.67 |                 -0.98 |                  nan |
|     20 | BCRX      | BCRX                       | US       |                2.14 |             74.84 |         56.46 |         70.7  |          78.99 |        80.35 |           85.22 |             94.05 |             76.78 |         5.75 |             66.59 | long               |              nan    |                  2.76 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE      | StoneCo Ltd.               | OTHER    |                1.82 |                  77.27 |                    74.1  |                 73.71 |              73.11 |                75.15 |                   24.85 |           86.96 |             39.5  |       0.685 |         nan |       nan |        1.54 |         3.91 |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW   | BB Biotech AG              | EUROPE   |                3.2  |                  73.25 |                    73.98 |                 75.66 |              74.25 |                86.65 |                   13.35 |           83.33 |             59.09 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS  | SHELL.AS                   | EUROPE   |              219.53 |                  67.33 |                    71.77 |                 73.47 |              67.9  |                78.74 |                   21.26 |           93.93 |             52.49 |     nan     |         nan |       nan |      nan    |         9.95 |         10.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)            | EUROPE   |               62.74 |                  79.99 |                    71.21 |                 67.97 |              74.38 |                60.45 |                   39.55 |           56.18 |             59.11 |       0.035 |         nan |       nan |       16.12 |        13.66 |         19.32 |        1.42 |                 nan |              nan |                  12 |                  0.63 |
|            4 | MOMO      | Hello Group Inc.           | OTHER    |                0.73 |                  76.43 |                    70.78 |                 69.44 |              73.54 |                71.53 |                   28.47 |           63.46 |             56.38 |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.6  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | PARR      | Par Pacific Holdings, Inc. | US       |                3.48 |                  69.87 |                    70.14 |                 71.74 |              69.14 |                68.42 |                   31.58 |           81.06 |             65.13 |       0.02  |         nan |       nan |        3.92 |         6.81 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | AMCX      | AMC Global Media Inc.      | US       |                0.43 |                  73.8  |                    69.59 |                 67.91 |              74.34 |                74.22 |                   25.78 |           47.17 |             78.5  |       2.038 |         nan |       nan |        7.01 |         4.31 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE   | PAH3.DE                    | EUROPE   |                8.31 |                  63.32 |                    68.87 |                 70.61 |              68.24 |                79.23 |                   20.77 |          nan    |             83.84 |     nan     |         nan |       nan |      nan    |         1.84 |         87.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | IHS       | IHS Holding Limited        | OTHER    |                2.43 |                  73.82 |                    68.43 |                 68.25 |              72.52 |                61.55 |                   38.45 |           53.42 |             82.94 |      -0.125 |         nan |       nan |        7.07 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | 0Q2N.IL   | K+S Aktiengesellschaft     | OTHER    |                2.89 |                  70.18 |                    68.38 |                 67.22 |              70.09 |                69.73 |                   30.27 |           60.4  |            nan    |       0.256 |         nan |       nan |        1.54 |       nan    |          2.69 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | NWL.MI    | NewPrinces S.p.A.          | EUROPE   |                0.67 |                  67.55 |                    67.65 |                 69.44 |              67.72 |                74.86 |                   25.14 |           77.61 |             56.09 |       0.995 |         nan |       nan |        5.26 |      -118.24 |          2.08 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | HMC       | Honda Motor Company, Ltd.  | OTHER    |               35.8  |                  60.43 |                    67.29 |                 71.08 |              65.7  |                76.47 |                   23.53 |           79.13 |             84.25 |       0.04  |         nan |       nan |        7.16 |         6.44 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BP        | BP                         | US       |               96.52 |                  57.73 |                    67.09 |                 70.23 |              62.91 |                78.57 |                   21.43 |           86.65 |             72.05 |     nan     |         nan |       nan |      nan    |         9.81 |         20.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE    | VOW.DE                     | EUROPE   |               37.3  |                  68.21 |                    66.92 |                 66.51 |              67.07 |                64.5  |                   35.5  |          nan    |             63.43 |     nan     |         nan |       nan |      nan    |         2.74 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE   | VOW3.DE                    | EUROPE   |               36.59 |                  69.15 |                    66.63 |                 65.88 |              66.9  |                61.47 |                   38.53 |          nan    |             60.51 |     nan     |         nan |       nan |      nan    |         3.1  |          7    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                        | US       |               14.91 |                  59.12 |                    66.6  |                 69.12 |              62.73 |                76.94 |                   23.06 |           85.99 |             63.18 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                        | US       |              116.48 |                  63.22 |                    66.53 |                 67.64 |              64.21 |                72.52 |                   27.48 |           79.43 |             56.38 |     nan     |         nan |       nan |      nan    |        10.07 |         14.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | UNIT      | Uniti Group Inc.           | US       |                2.08 |                  80.26 |                    66.43 |                 63.26 |              68.74 |                44.43 |                   55.57 |           64.17 |             29.55 |      -0.107 |         nan |       nan |        9.09 |       -13.96 |          2.57 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           12 | GSL       | Global Ship Lease Inc New  | OTHER    |                1.34 |                  68.84 |                    65.99 |                 65.95 |              66.06 |                70.76 |                   29.24 |           74.86 |             37.6  |       0.083 |         nan |       nan |        3.73 |         4.88 |          4.23 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR   | BIRG.IR                    | EUROPE   |               18.13 |                  58.61 |                    65.56 |                 68.09 |              60.02 |                77.07 |                   22.93 |           96.92 |             39.49 |     nan     |         nan |       nan |      nan    |        10.53 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | BION.SW   | BB Biotech AG                                          | EUROPE   |                3.2  |                  73.25 |                    73.98 |                 75.66 |              74.25 |                86.65 |                   13.35 |           83.33 |             59.09 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            1 | STNE      | StoneCo Ltd.                                           | OTHER    |                1.82 |                  77.27 |                    74.1  |                 73.71 |              73.11 |                75.15 |                   24.85 |           86.96 |             39.5  |       0.685 |         nan |       nan |        1.54 |         3.91 |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                                               | EUROPE   |              219.53 |                  67.33 |                    71.77 |                 73.47 |              67.9  |                78.74 |                   21.26 |           93.93 |             52.49 |     nan     |         nan |       nan |      nan    |         9.95 |         10.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.48 |                  69.87 |                    70.14 |                 71.74 |              69.14 |                68.42 |                   31.58 |           81.06 |             65.13 |       0.02  |         nan |       nan |        3.92 |         6.81 |          4.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | HMC       | Honda Motor Company, Ltd.                              | OTHER    |               35.8  |                  60.43 |                    67.29 |                 71.08 |              65.7  |                76.47 |                   23.53 |           79.13 |             84.25 |       0.04  |         nan |       nan |        7.16 |         6.44 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE   | PAH3.DE                                                | EUROPE   |                8.31 |                  63.32 |                    68.87 |                 70.61 |              68.24 |                79.23 |                   20.77 |          nan    |             83.84 |     nan     |         nan |       nan |      nan    |         1.84 |         87.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                                                     | US       |               96.52 |                  57.73 |                    67.09 |                 70.23 |              62.91 |                78.57 |                   21.43 |           86.65 |             72.05 |     nan     |         nan |       nan |      nan    |         9.81 |         20.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | NWL.MI    | NewPrinces S.p.A.                                      | EUROPE   |                0.67 |                  67.55 |                    67.65 |                 69.44 |              67.72 |                74.86 |                   25.14 |           77.61 |             56.09 |       0.995 |         nan |       nan |        5.26 |      -118.24 |          2.08 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            4 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.73 |                  76.43 |                    70.78 |                 69.44 |              73.54 |                71.53 |                   28.47 |           63.46 |             56.38 |       0.573 |         nan |       nan |       -5.15 |         5.36 |          8.6  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN       | BEN                                                    | US       |               14.91 |                  59.12 |                    66.6  |                 69.12 |              62.73 |                76.94 |                   23.06 |           85.99 |             63.18 |     nan     |         nan |       nan |      nan    |        10.76 |         23.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | IHS       | IHS Holding Limited                                    | OTHER    |                2.43 |                  73.82 |                    68.43 |                 68.25 |              72.52 |                61.55 |                   38.45 |           53.42 |             82.94 |      -0.125 |         nan |       nan |        7.07 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR   | BIRG.IR                                                | EUROPE   |               18.13 |                  58.61 |                    65.56 |                 68.09 |              60.02 |                77.07 |                   22.93 |           96.92 |             39.49 |     nan     |         nan |       nan |      nan    |        10.53 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.74 |                  79.99 |                    71.21 |                 67.97 |              74.38 |                60.45 |                   39.55 |           56.18 |             59.11 |       0.035 |         nan |       nan |       16.12 |        13.66 |         19.32 |        1.42 |                 nan |              nan |                  12 |                  0.63 |
|            6 | AMCX      | AMC Global Media Inc.                                  | US       |                0.43 |                  73.8  |                    69.59 |                 67.91 |              74.34 |                74.22 |                   25.78 |           47.17 |             78.5  |       2.038 |         nan |       nan |        7.01 |         4.31 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY       | BMY                                                    | US       |              116.48 |                  63.22 |                    66.53 |                 67.64 |              64.21 |                72.52 |                   27.48 |           79.43 |             56.38 |     nan     |         nan |       nan |      nan    |        10.07 |         14.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | 0Q2N.IL   | K+S Aktiengesellschaft                                 | OTHER    |                2.89 |                  70.18 |                    68.38 |                 67.22 |              70.09 |                69.73 |                   30.27 |           60.4  |            nan    |       0.256 |         nan |       nan |        1.54 |       nan    |          2.69 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | CRGY      | CRGY                                                   | US       |                4.4  |                  58.34 |                    64.8  |                 66.97 |              62.95 |                70.14 |                   29.86 |           70.87 |             83.23 |     nan     |         nan |       nan |      nan    |         6.03 |        161.88 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                                    | US       |                2.69 |                  62.23 |                    65.44 |                 66.91 |              61.59 |                69.42 |                   30.58 |           88.24 |             42.89 |     nan     |         nan |       nan |      nan    |        10.27 |          6.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.58 |                  58.63 |                    65.07 |                 66.83 |              63.89 |                74.59 |                   25.41 |           67.54 |             82.46 |       0.027 |         nan |       nan |      nan    |       nan    |          3.78 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | PAA       | PAA                                                    | US       |               14.74 |                  58.43 |                    64.54 |                 66.62 |              60.29 |                75.1  |                   24.9  |           88.04 |             47.02 |     nan     |         nan |       nan |      nan    |        12.55 |         20.33 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.58 |                     0.09 |    -0.06 |      0.17 |                  69.9  |                        82.28 |         75.93 |         83.7  |          76.82 |        74.71 |           76.51 |             97.57 |         5.89 |
|               2 | BCRX     | BCRX     | US       |                2.14 |                     0.08 |    -0.06 |      0.03 |                  70.91 |                        77.14 |         56.46 |         70.7  |          78.99 |        80.35 |           85.22 |             94.05 |         5.75 |
|               3 | ZETA     | ZETA     | US       |                6.07 |                     0.05 |    -0.04 |      0.32 |                  80.25 |                        75.37 |         80.2  |         81.58 |          67.45 |        53.54 |           49.2  |             84.69 |         7.49 |
|               4 | SNOW     | SNOW     | US       |               97.35 |                     0.04 |    -0.03 |      0.19 |                  69.46 |                        75.23 |         74.82 |         84.22 |          67.97 |        47.61 |           42.78 |             94.29 |         8.85 |
|               5 | SYENS.BR | SYENS.BR | EUROPE   |                8.2  |                     0.02 |    -0.02 |      0.16 |                  56.82 |                        74.61 |         77.97 |         73.56 |          63.42 |        59.25 |           68.13 |             89.79 |         5.02 |
|               6 | PLTR     | PLTR     | US       |              355.89 |                     0.04 |    -0.02 |      0.29 |                  68.29 |                        74.57 |         77.83 |         66.05 |          58.13 |        54.94 |           89.72 |             49.82 |         8.33 |
|               7 | GENI     | GENI     | US       |                1.8  |                     0.1  |    -0.03 |      0.14 |                  52.27 |                        74.36 |         72.23 |         77.78 |          71.31 |        72.7  |           64.82 |             97.81 |         9.07 |
|               8 | HPE      | HPE      | US       |               63.67 |                     0.09 |     0    |      0.17 |                  48.93 |                        73.81 |         73.45 |         82.43 |          80.47 |        73.07 |           71.58 |             72.9  |         6.77 |
|               9 | NET      | NET      | US       |               92.64 |                     0.09 |    -0.02 |      0.11 |                  54.28 |                        73.72 |         74.55 |         80.11 |          70.05 |        52.6  |           57.63 |             93.32 |         6.79 |
|              10 | JHX      | JHX      | US       |               14.68 |                     0.07 |    -0.07 |      0.17 |                  82.97 |                        73.4  |         72.12 |         75.05 |          63.83 |        59.62 |           58.08 |             78.74 |         6.84 |
|              11 | QNST     | QNST     | US       |                1.03 |                     0.06 |    -0.01 |      0.28 |                  71.41 |                        73.19 |         80.89 |         75.94 |          69.51 |        71.41 |           84.02 |             34.87 |         7.81 |
|              12 | PANW     | PANW     | US       |              263.26 |                     0.06 |    -0.03 |      0.09 |                  77.34 |                        73.14 |         67.71 |         78.28 |          70.25 |        52.72 |           57.02 |             73.27 |         6.54 |
|              13 | GL9.IR   | GL9.IR   | EUROPE   |                5.5  |                     0.05 |    -0.03 |      0    |                  79.4  |                        72.89 |         48.16 |         63.98 |          73.87 |        70.14 |           97.84 |             62.82 |         2.23 |
|              14 | NWL      | NWL      | US       |                2.18 |                     0.07 |    -0.03 |      0.13 |                  73.96 |                        72.84 |         70.98 |         81.53 |          69.52 |        64.82 |           33.35 |             95.38 |         8.04 |
|              15 | OKTA     | OKTA     | US       |               21.6  |                     0.07 |    -0.04 |      0.02 |                  73.25 |                        72.76 |         55.17 |         75.64 |          71.74 |        59.74 |           66.83 |             70.6  |         7.45 |
|              16 | GH       | GH       | US       |               18.55 |                     0.05 |    -0.03 |      0.05 |                  76.61 |                        72.57 |         61.34 |         77.05 |          76.44 |        72.2  |           62.37 |             67.19 |         6.75 |
|              17 | TGB      | TGB      | US       |                2.64 |                     0.05 |    -0.05 |      0.08 |                  84.28 |                        72.38 |         71.6  |         72.09 |          69.94 |        69.12 |           55.96 |             83.35 |         7.5  |
|              18 | CRWD     | CRWD     | US       |              187.18 |                     0.06 |    -0.04 |      0.11 |                  81.04 |                        72.2  |         66.67 |         77.92 |          67.55 |        46.42 |           41.52 |             85.18 |         6.68 |
|              19 | TIC      | TIC      | US       |                1.75 |                     0.12 |    -0.12 |      0.33 |                  61.22 |                        71.74 |         73.98 |         60.51 |          57.72 |        59.65 |           56.1  |             95.63 |         7.7  |
|              20 | RAND.AS  | RAND.AS  | EUROPE   |                6.75 |                     0.02 |    -0.02 |      0.21 |                  55.98 |                        71.69 |         73.58 |         76.85 |          66.68 |        64.28 |           83.34 |             54.68 |         6.72 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4595.03 |             63.15 |         63.77 |         55.35 |          62.53 |        65.28 |           94.07 |             59.65 |             32.27 |         5.47 |             89.53 | long               |                1.35 |                 -0.22 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.83 |             59.34 |         53.89 |         59.47 |          59.21 |        66.19 |           59.85 |             49.08 |             81.17 |         8.34 |             85.47 | long               |               -3.69 |                 -0.25 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.21 |             56.88 |         57.49 |         61.34 |          56.27 |        49.32 |           49.34 |             49.22 |             33.17 |         4.75 |             81.91 | swing              |                2.96 |                nan    |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1560.83 |             52.43 |         38.18 |         45.95 |          58.91 |        60.79 |           81.87 |             63    |             32.82 |         6.04 |             89.81 | long               |               -1.72 |                 -0.18 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             48.81 |         40.04 |         42.9  |          54.72 |        64.89 |           85.08 |             42.98 |             55.73 |         3.88 |             75.81 | long               |               -1.37 |                 -0.02 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.28 |             43.04 |         39.34 |         40.55 |          45.53 |        48.94 |           40.38 |             60.98 |             66.81 |         5.88 |             80.44 | long               |              nan    |                 -1.75 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.74 |             41.53 |         42.68 |         32.26 |          40.38 |        47.33 |           51.97 |             68.01 |             49.64 |         7.01 |             77.1  | long               |                0.19 |                  1.65 |                  nan |
|    nan | ATHM     | Autohome Inc.                                        | OTHER    |                2.18 |             40.25 |         41.45 |         48.51 |          39.05 |        36.27 |           32.89 |             31.4  |             36.79 |         8.5  |             78.73 | swing              |                0.54 |                 -0.17 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.27 |             39.8  |         29.12 |         36.28 |          43.31 |        56.86 |           52.87 |             41.49 |             86.27 |         7.07 |             78.43 | long               |               -4.94 |                  0.38 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.89 |             39.13 |         31.38 |         35.18 |          43.07 |        54.67 |           52.15 |             46.99 |             75.19 |         6.13 |             78.58 | long               |               -7    |                  0.22 |                  nan |
|    nan | WB       | Weibo Corporation                                    | OTHER    |                1.61 |             36.06 |         30.87 |         30.71 |          41.26 |        58.21 |           68.2  |             24.46 |             78.81 |         8.5  |             81.52 | long               |                0.48 |                 -0.12 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.86 |             32.09 |         25.49 |         22.29 |          38.69 |        51.26 |           74.28 |             19.38 |             44.44 |         8.98 |             78.45 | long               |               -2.67 |                 -0.19 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.26 |             28.67 |         33.17 |         25.28 |          26.93 |        30.4  |           34.09 |             38.83 |             27.82 |         6.63 |             76.54 | short              |              nan    |                  1.64 |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.81 |             27.65 |         49.93 |         22.87 |          23.47 |        31.83 |           29.35 |             26.74 |             50    |         8.5  |             76.14 | short              |               -5.08 |                  0.41 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    155 | ARGX.BR  | ARGX.BR  | EUROPE   |               54.1  |             64.71 |         80.19 |         66.76 |          62.66 |        60.43 |           94.72 |             44.11 |              8.45 |         5.77 |             67.5  | short              |              nan    |                  5.35 |                  nan |
|    574 | HFG.DE   | HFG.DE   | EUROPE   |                0.43 |             46.64 |         31.78 |         40.99 |          52.29 |        69.32 |          nan    |             95.02 |             82.8  |         6.99 |             64.66 | long               |                1.95 |                  3.02 |                  nan |
|    279 | KLAC     | KLAC     | US       |              219.72 |             59.67 |         39.99 |         53.79 |          68.99 |        65.55 |           95.71 |             56.87 |             12.89 |         8.14 |             65.45 | medium             |               -0.98 |                  2.96 |                  nan |
|    334 | GSK      | GSK      | US       |               88.44 |             57.9  |         58.43 |         48.2  |          57.36 |        67.76 |           70.4  |             55.29 |             71.53 |         2.92 |             66.48 | long               |                4.91 |                  2.93 |                  nan |
|    643 | STLAM.MI | STLAM.MI | EUROPE   |               16.5  |             40.5  |         30.85 |         37.75 |          43.26 |        49.92 |           17.37 |             86.51 |             90.68 |         6.87 |             66.48 | long               |                1.3  |                  2.86 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    449 | RBI.VI   | RBI.VI | EUROPE   |               20.47 |             52.97 |         64.01 |         58.03 |          47.92 |        41.28 |           11.51 |              9.6  |             68.33 |         3.66 |             66.14 | short              |                1.47 |                 -6.33 |                  nan |
|    387 | ABCL     | ABCL   | US       |                2.94 |             55.57 |         75.16 |         65.5  |          45.64 |        34.19 |            8.59 |             10.57 |             45.67 |         9.04 |             63.64 | short              |                0.71 |                 -6.08 |                  nan |
|    623 | WNC      | WNC    | US       |                0.42 |             43    |         34.02 |         48.46 |          42.04 |        43.97 |           13.81 |              9.11 |             80.31 |         7.49 |             66.48 | swing              |               -1.6  |                 -5.75 |                  nan |
|    488 | BNP.PA   | BNP.PA | EUROPE   |              119.9  |             50.81 |         52.73 |         54.5  |          48.9  |        47.9  |           25.94 |             18.96 |             74.51 |         2.51 |             67.5  | swing              |               -1.07 |                 -5.65 |                  nan |
|    586 | ABSI     | ABSI   | US       |                1.31 |             45.94 |         44.83 |         56.35 |          47.05 |        30.46 |            2.99 |             16.16 |             31.01 |         9.07 |             63.64 | swing              |               -7.45 |                 -5.52 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90

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
- Excluded by hard/data filters: **289**
- Event watch (otherwise eligible): **14**
- Final eligible: **697**
- Eligible change vs previous stored run: **-5**

Top exclusion categories:
- liquidity: 234
- price: 178
- market_cap: 161
- price_history: 21
- data_confidence: 17
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| HPE | 9 |  | 8 |  | 2 | main,pullback |
| PARR | 15 | 5 |  | 3 | 1 | value,quality_value |
| BION.SW | 46 | 2 |  | 1 | 1 | value,quality_value |
| AMCX | 62 | 6 | 76 | 9 | 1 | value,quality_value |
| HMC | 78 | 10 |  | 4 | 1 | value,quality_value |
| 0Q2N.IL | 311 | 8 |  | 10 | 1 | value,quality_value |
| IHS | 347 | 7 |  | 7 | 1 | value,quality_value |
| VOLV-B.ST | 410 | 3 | 239 | 8 | 1 | value,quality_value |
| NWL.MI | 523 | 9 | 229 | 5 | 1 | value,quality_value |
| MOMO | 563 | 4 | 272 | 6 | 1 | value,quality_value |
| STNE | 651 | 1 |  | 2 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| HALO | 2 |  |  |  | 1 | main |
| PBF | 3 |  |  |  | 1 | main |
| SSABBH.HE | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **10** (MPC, HALO, PBF, SSABBH.HE, RMAX, PSX, CRGY, U, HPE, NTAP)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (ZETA, SYENS.BR, HPE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MOMO | value+pullback | 68.65 | 76.43 | 65.05 | 63.46 | 56.38 | 71.53 | 47.06 |
| 2 | NWL.MI | value+pullback | 66.22 | 67.55 | 54.91 | 77.61 | 56.09 | 74.86 | 49.20 |
| 3 | VOLV-B.ST | value+pullback | 65.65 | 79.99 | 60.89 | 56.18 | 59.11 | 60.45 | 54.58 |
| 4 | AMCX | value+pullback | 65.44 | 73.80 | 54.11 | 47.17 | 78.50 | 74.22 | 70.58 |
| 5 | ETG | value+pullback | 64.46 | 58.63 | 54.29 | 67.54 | 82.46 | 74.59 | 62.38 |
| 6 | MSFT | value+pullback | 62.83 | 58.21 | 79.51 | 58.33 | 64.51 | 51.46 | 58.27 |
| 7 | ALL-PH | value+pullback | 62.79 | 62.31 | 70.91 | 68.62 | 42.64 | 59.09 | 43.95 |
| 8 | PBR-A | value+pullback | 61.80 | 73.63 | 59.31 | 54.53 | 68.29 | 49.39 | 58.33 |
| 9 | MFA | value+pullback | 61.37 | 57.89 | 61.83 | 79.81 | 36.89 | 64.42 | 44.43 |
| 10 | ONIT | value+pullback | 60.60 | 70.91 | 68.82 | 61.00 | 44.93 | 42.37 | 44.29 |
| 11 | 0Q2N.IL | value+pullback | 60.47 | 70.18 | 45.65 | 60.40 |  | 69.73 | 58.43 |
| 12 | WKC | value+pullback | 60.32 | 59.34 | 47.36 | 61.36 | 74.45 | 70.15 | 67.36 |
| 13 | CHTR | value+pullback | 59.60 | 66.48 | 85.49 | 50.65 | 40.98 | 32.93 | 44.95 |
| 14 | TV | value+pullback | 58.68 | 69.44 | 64.48 | 44.85 | 31.55 | 59.25 | 41.44 |
| 15 | PBR | value+pullback | 58.35 | 61.62 | 63.15 | 54.53 | 62.40 | 48.30 | 57.56 |
| 16 | LKFT.AS | value+pullback | 58.01 | 61.61 | 65.95 | 52.07 | 45.91 | 53.19 | 39.56 |
| 17 | BION.SW | value | 57.71 | 73.25 | 33.02 | 83.33 | 59.09 | 86.65 | 71.93 |
| 18 | GL9.IR | pullback | 57.71 | 42.75 | 79.40 | 97.84 | 62.82 | 84.52 | 67.06 |
| 19 | BYD | value+pullback | 57.34 | 60.74 | 44.93 | 78.88 | 40.86 | 59.84 | 49.25 |
| 20 | AF.PA | value+pullback | 57.17 | 68.80 | 65.86 | 43.35 | 56.91 | 39.36 | 49.38 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 67.0 | 0 / 10 |
| Top 25 | 24/25 | 24/25 | 24/25 | 22/25 | 0/25 | 66.6 | 4 / 21 |
| Top 50 | 48/50 | 47/50 | 48/50 | 43/50 | 0/50 | 67.0 | 12 / 38 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=1, mid_5_20b=4, large_20_100b=4
