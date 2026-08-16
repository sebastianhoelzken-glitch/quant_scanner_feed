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

- **EUROPE:** 89.5/100
- **OTHER:** 76.6/100
- **US:** 86.6/100

## Main multi-horizon ranking

|   rank | symbol    | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | SSABBH.HE | SSABBH.HE                  | EUROPE   |                9.73 |             81.94 |         77.2  |         78.51 |          85.37 |        92.82 |          nan    |            nan    |             98.61 |         3.33 |             60    | long               |               -1.56 |                   nan |                  nan |
|      2 | HPE       | HPE                        | US       |               67.18 |             81.27 |         81.87 |         85.68 |          80.67 |        73.01 |           71.48 |             73.53 |             58.08 |         6.74 |             65.68 | swing              |               -4.84 |                   nan |                  nan |
|      3 | MPC       | MPC                        | US       |               89.66 |             80.48 |         80.83 |         81.76 |          80.13 |        77.37 |           84.52 |             61.73 |             63.64 |         3.89 |             67.5  | swing              |               -4.06 |                   nan |                  nan |
|      4 | BAX       | BAX                        | US       |               11.94 |             79.18 |         79.15 |         86.52 |          79.22 |        76.16 |           77.64 |             97.95 |             66.22 |         5.8  |             66.02 | swing              |                5.97 |                   nan |                  nan |
|      5 | CLN.SW    | CLN.SW                     | EUROPE   |                3.84 |             79.05 |         86.23 |         85.15 |          72.94 |        63.75 |          nan    |             88.33 |             44.52 |         4.85 |             64.66 | short              |                2.42 |                   nan |                  nan |
|      6 | FSLY      | FSLY                       | US       |                4.12 |             78.74 |         86.73 |         84.25 |          73.23 |        53.2  |           40.73 |             99.04 |             16.37 |         8.4  |             67.5  | short              |               -2.09 |                   nan |                  nan |
|      7 | PARR      | Par Pacific Holdings, Inc. | US       |                3.48 |             78.36 |         73.9  |         76.82 |          81.22 |        79.9  |           83.7  |             69.14 |             76.33 |         6.64 |             85.6  | medium             |                2.45 |                   nan |                  nan |
|      8 | CLMT      | CLMT                       | US       |                3.62 |             78.14 |         83.56 |         83.27 |          73.01 |        52.81 |           49.94 |             93.14 |              5.21 |         4.47 |             66.59 | short              |               -1.39 |                   nan |                  nan |
|      9 | PBF       | PBF                        | US       |                7.36 |             78.07 |         81.06 |         80.52 |          75.63 |        72.49 |           51.29 |             57.16 |             93.9  |         6.99 |             67.05 | short              |              -14.62 |                   nan |                  nan |
|     10 | GENI      | GENI                       | US       |                2.01 |             78.07 |         86.59 |         83.07 |          73.06 |        72.97 |           65.73 |             99.04 |             82.9  |         9.33 |             67.5  | short              |                3.02 |                   nan |                  nan |
|     11 | MU        | MU                         | US       |              948.25 |             78.04 |         72.48 |         72.38 |          83.6  |        85.09 |           95.42 |             59.81 |             77.08 |         8.08 |             67.5  | long               |               -0.39 |                   nan |                  nan |
|     12 | TKA.DE    | TKA.DE                     | EUROPE   |                8.6  |             77.85 |         82.58 |         79.21 |          76.5  |        71.81 |          nan    |             84.84 |             56.6  |         6.38 |             64.66 | short              |                0.92 |                   nan |                  nan |
|     13 | BWIN      | BWIN                       | US       |                2.64 |             77.54 |         79.74 |         86.04 |          75.34 |        68.42 |           63.61 |             94.71 |             63.3  |         8.14 |             67.5  | swing              |              nan    |                   nan |                  nan |
|     14 | CRDO      | CRDO                       | US       |               41.88 |             77.13 |         77.01 |         77.24 |          77.73 |        68.68 |           92.52 |             69.07 |             17.07 |         8.9  |             67.5  | medium             |                1.78 |                   nan |                  nan |
|     15 | NET       | NET                        | US       |               97.16 |             77.12 |         82.53 |         82.98 |          71.72 |        53.57 |           58.44 |             93.74 |              1.75 |         6.73 |             67.5  | swing              |                2.29 |                   nan |                  nan |
|     16 | ZETA      | ZETA                       | US       |                6.3  |             76.99 |         87.68 |         84.51 |          69.47 |        54.81 |           49.15 |             85.38 |             26.64 |         7.59 |             67.05 | short              |               -3.44 |                   nan |                  nan |
|     17 | PSX       | PSX                        | US       |               80.55 |             76.95 |         77.85 |         78.1  |          76.06 |        75.36 |           79.07 |             55.6  |             69.52 |         3.35 |             67.5  | swing              |               -5.1  |                   nan |                  nan |
|     18 | NTAP      | NTAP                       | US       |               35.06 |             76.81 |         79    |         81.48 |          74.61 |        67.25 |           85.61 |             53.19 |             29.53 |         6.16 |             65.45 | swing              |               -3.63 |                   nan |                  nan |
|     19 | DELL      | DELL                       | US       |              274.03 |             76.4  |         78.92 |         80.92 |          73.89 |        63.22 |           69.7  |             56.2  |             32.33 |         7.66 |             66.59 | swing              |               -7.39 |                   nan |                  nan |
|     20 | RMAX      | RMAX                       | US       |                0.6  |             76.33 |         82.51 |         83.27 |          70.16 |        61.01 |           20.61 |             91.7  |             91.17 |         7.05 |             67.05 | swing              |              -10.26 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.2  |                    73.95 |                 73.7  |              72.81 |                72.8  |                   27.2  |           87.42 |             41.26 |       0.624 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.48 |                  75.05 |                    73.61 |                 75.21 |              73.12 |                67.62 |                   32.38 |           83.7  |             69.14 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  77.5  |                    72.05 |                 70.9  |              74.74 |                72.8  |                   27.2  |           65.4  |             58.32 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE  | PAH3.DE                                              | EUROPE   |                8.46 |                  63.29 |                    69.08 |                 70.89 |              68.41 |                79.87 |                   20.13 |          nan    |             84.72 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  71.11 |                    68.77 |                 69.96 |              68.07 |                69.34 |                   30.66 |           83.92 |             43.88 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               15.32 |                  62.05 |                    68.58 |                 73.14 |              64.58 |                72.59 |                   27.41 |           96.32 |             68.34 |     nan     |         nan |       nan |        3.7  |        10.16 |         29.45 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            6 | INVA     | Innoviva, Inc.                                       | US       |                1.32 |                  68.86 |                    68.49 |                 69.42 |              68.19 |                81.19 |                   18.81 |           81.02 |             39.99 |       0.072 |         nan |       nan |        6.57 |         9.59 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            7 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras                 | OTHER    |               95.07 |                  79.16 |                    67.99 |                 65.85 |              72.88 |                49.92 |                   50.08 |           49.57 |             68.96 |       0.166 |         nan |       nan |        1.72 |         6.53 |          4.06 |        4.02 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                                  | US       |              112.67 |                  64.84 |                    67.46 |                 68.34 |              65.47 |                72.57 |                   27.43 |           78.74 |             57.28 |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE   | VOW.DE                                               | EUROPE   |               37.62 |                  68    |                    67.24 |                 67.01 |              67.33 |                65.82 |                   34.18 |          nan    |             65.22 |     nan     |         nan |       nan |      nan    |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                  | US       |               14.87 |                  58.4  |                    66.83 |                 69.65 |              62.64 |                78.32 |                   21.68 |           87.5  |             64.98 |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                                              | EUROPE   |               36.96 |                  68.65 |                    66.62 |                 66.03 |              66.83 |                62.32 |                   37.68 |          nan    |             61.85 |     nan     |         nan |       nan |      nan    |         3.13 |          7.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                  | US       |                2.72 |                  62.94 |                    66.26 |                 67.75 |              62.46 |                70.4  |                   29.6  |           88.62 |             44.77 |     nan     |         nan |       nan |      nan    |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | UNIT     | Uniti Group Inc.                                     | US       |                2.1  |                  80.26 |                    66.19 |                 62.88 |              68.82 |                43.99 |                   56.01 |           62    |             31.07 |      -0.106 |         nan |       nan |        9.1  |       -14.1  |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|            9 | WKC      | World Kinect Corporation                             | US       |                1.6  |                  64.75 |                    66.09 |                 67.44 |              66.66 |                69.82 |                   30.18 |           66.52 |             74.7  |       0.063 |         nan |       nan |        7.07 |        14.11 |        nan    |        1.32 |                 nan |              nan |                  11 |                  0.58 |
|           10 | CNXC     | Concentrix Corporation                               | US       |                1.29 |                  80.54 |                    66.04 |                 62.77 |              69.23 |                44.02 |                   55.98 |           59.83 |             33.13 |       0.519 |         nan |       nan |        5.29 |         2.06 |        nan    |        0.32 |                 nan |              nan |                  11 |                  0.58 |
|          nan | FRO      | FRO                                                  | US       |                7.93 |                  59.45 |                    65.99 |                 68.4  |              62.34 |                72.68 |                   27.32 |           84.3  |             64.5  |     nan     |         nan |       nan |      nan    |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | AMCX     | AMC Global Media Inc.                                | US       |                0.44 |                  66.35 |                    65.81 |                 65.32 |              68.53 |                72.1  |                   27.9  |           51.88 |             77.84 |       1.969 |         nan |       nan |        7.08 |         4.47 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                                 | US       |              215.86 |                  68.28 |                    65.53 |                 64.78 |              64.86 |                64.17 |                   35.83 |           72.79 |             41.52 |     nan     |         nan |       nan |      nan    |        10.26 |         10.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.55 |                  57.46 |                    65.36 |                 68.83 |              63.17 |                80.19 |                   19.81 |           79.57 |             73.68 |       0.076 |         nan |       nan |        3.48 |         9.33 |          5.02 |        1.1  |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.48 |                  75.05 |                    73.61 |                 75.21 |              73.12 |                67.62 |                   32.38 |           83.7  |             69.14 |       0.02  |         nan |       nan |        3.91 |         6.71 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | STNE     | StoneCo Ltd.                                           | OTHER    |                2.01 |                  77.2  |                    73.95 |                 73.7  |              72.81 |                72.8  |                   27.2  |           87.42 |             41.26 |       0.624 |         nan |       nan |        1.55 |         4.09 |          3.59 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               15.32 |                  62.05 |                    68.58 |                 73.14 |              64.58 |                72.59 |                   27.41 |           96.32 |             68.34 |     nan     |         nan |       nan |        3.7  |        10.16 |         29.45 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            3 | MOMO     | Hello Group Inc.                                       | OTHER    |                0.73 |                  77.5  |                    72.05 |                 70.9  |              74.74 |                72.8  |                   27.2  |           65.4  |             58.32 |       0.574 |         nan |       nan |       -5.15 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.46 |                  63.29 |                    69.08 |                 70.89 |              68.41 |                79.87 |                   20.13 |          nan    |             84.72 |     nan     |         nan |       nan |      nan    |         1.87 |         89.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  71.11 |                    68.77 |                 69.96 |              68.07 |                69.34 |                   30.66 |           83.92 |             43.88 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.68 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                                    | US       |               14.87 |                  58.4  |                    66.83 |                 69.65 |              62.64 |                78.32 |                   21.68 |           87.5  |             64.98 |     nan     |         nan |       nan |      nan    |        10.72 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | INVA     | Innoviva, Inc.                                         | US       |                1.32 |                  68.86 |                    68.49 |                 69.42 |              68.19 |                81.19 |                   18.81 |           81.02 |             39.99 |       0.072 |         nan |       nan |        6.57 |         9.59 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|           12 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.55 |                  57.46 |                    65.36 |                 68.83 |              63.17 |                80.19 |                   19.81 |           79.57 |             73.68 |       0.076 |         nan |       nan |        3.48 |         9.33 |          5.02 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                                    | US       |                7.93 |                  59.45 |                    65.99 |                 68.4  |              62.34 |                72.68 |                   27.32 |           84.3  |             64.5  |     nan     |         nan |       nan |      nan    |        10.43 |         10.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                                    | US       |              112.67 |                  64.84 |                    67.46 |                 68.34 |              65.47 |                72.57 |                   27.43 |           78.74 |             57.28 |     nan     |         nan |       nan |      nan    |         9.73 |         14.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                    | US       |                2.72 |                  62.94 |                    66.26 |                 67.75 |              62.46 |                70.4  |                   29.6  |           88.62 |             44.77 |     nan     |         nan |       nan |      nan    |        10.46 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.98 |                  52.56 |                    64.19 |                 67.6  |              60.6  |                81.49 |                   18.51 |           78.36 |             80.93 |     nan     |         nan |       nan |      nan    |       nan    |          4.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | WKC      | World Kinect Corporation                               | US       |                1.6  |                  64.75 |                    66.09 |                 67.44 |              66.66 |                69.82 |                   30.18 |           66.52 |             74.7  |       0.063 |         nan |       nan |        7.07 |        14.11 |        nan    |        1.32 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW.DE   | VOW.DE                                                 | EUROPE   |               37.62 |                  68    |                    67.24 |                 67.01 |              67.33 |                65.82 |                   34.18 |          nan    |             65.22 |     nan     |         nan |       nan |      nan    |         2.76 |          7.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.61 |                  59.24 |                    65.31 |                 66.97 |              64.17 |                74.45 |                   25.55 |           67.86 |             81.18 |       0.027 |         nan |       nan |      nan    |       nan    |          3.8  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | NAT      | NAT                                                    | US       |                1.23 |                  54.94 |                    63.8  |                 66.72 |              60.3  |                74.32 |                   25.68 |           79.2  |             73.65 |     nan     |         nan |       nan |      nan    |        17.89 |         25.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY                                                    | US       |               50.41 |                  55.74 |                    63.66 |                 66.47 |              59.4  |                72.96 |                   27.04 |           84.94 |             61.37 |     nan     |         nan |       nan |      nan    |        14.83 |         17.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              172.24 |                  55.65 |                    65.04 |                 66.34 |              60.5  |                76.32 |                   23.68 |           79.24 |             66.93 |       0.031 |         nan |       nan |       22.16 |        25.39 |         36.09 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU       | MU                                                     | US       |              948.25 |                  50.88 |                    61.99 |                 66.34 |              55.35 |                70.75 |                   29.25 |           95.42 |             59.81 |     nan     |         nan |       nan |      nan    |         6.27 |         21.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.94 |                     0.06 |    -0.03 |      0.18 |                  78.19 |                        85.21 |         79.15 |         86.52 |          79.22 |        76.16 |           77.64 |             97.95 |         5.8  |
|               2 | METSB.HE | METSB.HE | EUROPE   |                1.09 |                     0.06 |     0.01 |      0.23 |                  63.05 |                        82.21 |         83.06 |         70.54 |          68.91 |        73.88 |           93.75 |             83.15 |         4.34 |
|               3 | CCC      | CCC      | US       |                3.55 |                     0.02 |     0.01 |      0.15 |                  47.72 |                        76.23 |         76.24 |         79.26 |          73.05 |        74.3  |           86.56 |             80.87 |         7.81 |
|               4 | AMRX     | AMRX     | US       |                5.46 |                     0.05 |     0    |      0.02 |                  67.42 |                        75.51 |         61.99 |         73.91 |          76.63 |        75.65 |           92.76 |             65.94 |         4.39 |
|               5 | TGB      | TGB      | US       |                2.64 |                     0.05 |     0    |      0.23 |                  68.72 |                        73.53 |         78.8  |         66.41 |          67.78 |        68.43 |           55.77 |             84.48 |         7.56 |
|               6 | SNOW     | SNOW     | US       |               98.51 |                     0.03 |    -0    |      0.22 |                  53.69 |                        73.45 |         75.52 |         84.74 |          68.8  |        48.39 |           43.82 |             95.07 |         8.83 |
|               7 | PLTR     | PLTR     | US       |              361.39 |                     0.03 |     0.01 |      0.31 |                  50.53 |                        73.27 |         80.09 |         67.09 |          58.75 |        55.24 |           89.88 |             51.14 |         8.32 |
|               8 | OKTA     | OKTA     | US       |               22.34 |                     0.05 |    -0.01 |     -0.01 |                  68.58 |                        73    |         56.45 |         76.68 |          72.95 |        61.11 |           68.33 |             71.36 |         7.49 |
|               9 | GH       | GH       | US       |               18.23 |                     0.07 |    -0.07 |      0.01 |                  82.98 |                        72.88 |         51.44 |         75.04 |          76.76 |        72.65 |           62.93 |             68.83 |         6.76 |
|              10 | AXTI     | AXTI     | US       |                4.63 |                     0.08 |    -0.08 |      0.78 |                  79.23 |                        72.07 |         73.6  |         60.35 |          68.8  |        54.59 |           53.77 |             84.24 |         9.77 |
|              11 | CLOV     | CLOV     | US       |                2.11 |                     0.04 |    -0.03 |     -0    |                  71.14 |                        72.07 |         50.77 |         73.71 |          73.8  |        57.04 |           53.74 |             91.94 |         8.48 |
|              12 | PENN     | PENN     | US       |                2.18 |                     0.11 |    -0.07 |     -0.09 |                  53.82 |                        71.54 |         38.45 |         69.04 |          75.87 |        72.9  |           78.05 |             88.93 |         6.59 |
|              13 | ERO      | ERO      | US       |                3.05 |                     0.07 |    -0.01 |      0.4  |                  62.8  |                        71.52 |         75.74 |         62.95 |          68.99 |        78.91 |           83.23 |             50.54 |         7.41 |
|              14 | ELF      | ELF      | US       |                4.66 |                     0.07 |    -0.07 |      0.24 |                  81.45 |                        71.2  |         67.38 |         72.14 |          57.97 |        50.96 |           57.91 |             75.57 |         8.21 |
|              15 | CART     | CART     | US       |                9.78 |                     0.03 |    -0.03 |      0.07 |                  64.85 |                        69.77 |         65.65 |         72.62 |          69.63 |        68.99 |           68.14 |             67.39 |         5.52 |
|              16 | BEN      | BEN      | US       |               14.87 |                     0.05 |     0    |      0.04 |                  69.06 |                        69.73 |         61.62 |         64.24 |          74.16 |        78.81 |           87.5  |             64.98 |         3.11 |
|              17 | AVTR     | AVTR     | US       |                7.98 |                     0.05 |     0.01 |      0.23 |                  66.28 |                        69.66 |         78.72 |         81.57 |          63.45 |        51.22 |           20.38 |             99.04 |         7.56 |
|              18 | EXLS     | EXLS     | US       |                4.6  |                     0.03 |    -0    |      0.24 |                  57.5  |                        69.65 |         73.37 |         65.55 |          60.12 |        65.42 |           80.65 |             54.75 |         6.96 |
|              19 | COUR     | COUR     | US       |                1.32 |                     0.06 |    -0.01 |      0.04 |                  66.32 |                        69.63 |         59.03 |         62.74 |          64.8  |        73.8  |           68.27 |             97.71 |         8.25 |
|              20 | CRWD     | CRWD     | US       |              190.89 |                     0.04 |     0.01 |      0.07 |                  56.9  |                        68.83 |         67.54 |         78.78 |          67.91 |        46.29 |           40.16 |             85.8  |         6.69 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.              | US       |                0.79 |             64.83 |         70.18 |         70.81 |          59.47 |        53.77 |           65.23 |             51.79 |             38.59 |         8.21 |             86.86 | swing              |               -5.76 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.61 |         58.99 |         61.06 |          56.8  |        60.23 |           55.94 |             50.13 |             64.95 |         8.32 |             87.57 | swing              |                0.01 |                   nan |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.18 |             54.79 |         53.19 |         59.67 |          56.4  |        50.21 |           53.29 |             51.91 |             30.4  |         4.68 |             82.25 | swing              |                1.36 |                   nan |                  nan |
|    nan | BBWI     | Bath & Body Works, Inc.      | US       |                3.38 |             46.4  |         35.32 |         42.9  |          49.89 |        61.94 |           72.83 |             47.12 |             69.57 |         7.42 |             87.87 | long               |                0.38 |                   nan |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.26 |             44.07 |         52.24 |         49.64 |          38.5  |        35.5  |           32.89 |             30.98 |             35.56 |         5.84 |             78.55 | short              |                1.47 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.33 |         25.5  |         34.19 |          42.47 |        53.79 |           49.56 |             48.66 |             77.92 |         6.14 |             78.58 | long               |               -0.07 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.29 |             37.93 |         28.11 |         34.63 |          41.23 |        54.91 |           50.29 |             38.42 |             87.5  |         7.07 |             78.48 | long               |               -0.24 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.76 |             37.82 |         41.44 |         26.23 |          34.2  |        44.02 |           52.35 |             38.85 |             50.46 |         6.98 |             76.3  | long               |                2.22 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             37.69 |         32.83 |         32.03 |          42.54 |        60.15 |           72.15 |             26.03 |             79.37 |         4.68 |             81.52 | long               |                0.45 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             35.96 |         31.75 |         24.09 |          40.17 |        53.02 |           73.79 |             20.48 |             47.71 |         9.03 |             78.45 | long               |                1.91 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             30.8  |         54.04 |         24.95 |          25.82 |        35.79 |           31.96 |             28.18 |             58.86 |         7.64 |             76.14 | short              |                4.42 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
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
- Excluded by hard/data filters: **294**
- Event watch (otherwise eligible): **11**
- Final eligible: **695**
- Eligible change vs previous stored run: **-9**

Top exclusion categories:
- liquidity: 232
- price: 175
- market_cap: 151
- price_history: 24
- data_confidence: 20
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 7 | 2 |  | 1 | 2 | main,value,quality_value |
| BAX | 4 |  | 1 |  | 2 | main,pullback |
| WKC | 78 | 9 | 35 | 8 | 1 | value,quality_value |
| PKX | 232 | 5 |  | 3 | 1 | value,quality_value |
| IRS | 461 | 4 | 115 | 5 | 1 | value,quality_value |
| MOMO | 540 | 3 | 164 | 4 | 1 | value,quality_value |
| INVA | 579 | 6 |  | 6 | 1 | value,quality_value |
| STNE | 620 | 1 |  | 2 | 1 | value,quality_value |
| SSABBH.HE | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| MPC | 3 |  |  |  | 1 | main |
| CLN.SW | 5 |  |  |  | 1 | main |
| FSLY | 6 |  |  |  | 1 | main |
| CLMT | 8 |  |  |  | 1 | main |
| PBF | 9 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (AXTI)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MOMO | value+pullback | 71.21 | 77.50 | 71.01 | 65.40 | 58.32 | 72.80 | 47.51 |
| 2 | IRS | value+pullback | 70.73 | 71.11 | 74.23 | 83.92 | 43.88 | 69.34 | 51.61 |
| 3 | GSL | value+pullback | 66.58 | 67.11 | 70.66 | 73.91 | 38.65 | 69.14 | 59.73 |
| 4 | PBR-A | value+pullback | 64.49 | 79.16 | 65.72 | 49.57 | 68.96 | 49.92 | 55.91 |
| 5 | CNXC | value+pullback | 62.90 | 80.54 | 70.58 | 59.83 | 33.13 | 44.02 | 42.97 |
| 6 | CLW | value+pullback | 62.55 | 58.92 | 78.34 | 47.39 | 65.32 | 58.26 | 59.19 |
| 7 | WKC | value+pullback | 61.78 | 64.75 | 43.77 | 66.52 | 74.70 | 69.82 | 70.28 |
| 8 | ALL-PH | value+pullback | 61.16 | 62.35 | 65.08 | 67.68 | 43.99 | 58.18 | 44.82 |
| 9 | BHF | value+pullback | 60.00 | 69.56 | 55.64 | 52.66 | 43.26 | 64.98 | 44.30 |
| 10 | MTRX | value+pullback | 59.40 | 70.29 | 60.49 | 41.74 | 61.81 | 53.74 | 46.11 |
| 11 | MFA | value+pullback | 58.71 | 58.82 | 49.63 | 78.75 | 39.20 | 64.60 | 46.24 |
| 12 | PBR | value+pullback | 57.66 | 65.45 | 57.68 | 49.57 | 63.87 | 48.92 | 55.08 |
| 13 | ONIT | value+pullback | 57.30 | 70.12 | 58.20 | 58.91 | 46.39 | 41.19 | 46.96 |
| 14 | BAX | pullback | 56.72 | 48.41 | 78.19 | 77.64 | 97.95 | 78.65 | 79.18 |
| 15 | AF.PA | value+pullback | 56.05 | 69.99 | 77.15 | 46.85 | 15.89 | 35.73 | 42.80 |
| 16 | PARR | value | 55.51 | 75.05 | 57.96 | 83.70 | 69.14 | 67.62 | 78.36 |
| 17 | METSB.HE | pullback | 55.11 | 52.82 | 63.05 | 93.75 | 83.15 | 84.83 | 72.21 |
| 18 | STNE | value | 54.96 | 77.20 | 34.72 | 87.42 | 41.26 | 72.80 | 41.89 |
| 19 | PKX | value | 54.41 | 62.05 | 32.60 | 96.32 | 68.34 | 72.59 | 61.87 |
| 20 | MAGN | value+pullback | 54.31 | 58.92 | 47.38 | 54.04 | 39.19 | 63.81 | 43.31 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 8/10 | 9/10 | 10/10 | 8/10 | 1/10 | 66.8 | 10 / 0 |
| Top 25 | 22/25 | 24/25 | 24/25 | 21/25 | 1/25 | 67.0 | 22 / 3 |
| Top 50 | 45/50 | 48/50 | 48/50 | 42/50 | 1/50 | 66.7 | 38 / 12 |

Top-10 market-cap mix: small_1_5b=5, mid_5_20b=3, large_20_100b=2
Top-10 sparse-data names: SSABBH.HE (missing quality,revisions; conf=60.0)
