# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-13

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

- **EUROPE:** 86.2/100
- **OTHER:** 71.5/100
- **US:** 83.3/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.47 |             78.64 |         78.6  |         78.69 |          79.36 |        73.74 |           74.28 |             71.76 |             60.67 |         6.8  |             85.65 | medium             |                4.11 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |             71.53 |         79.08 |         69.04 |          70.65 |        72.41 |           75.87 |             64.53 |             64.46 |         5.13 |             84.89 | short              |               -0.79 |                   nan |                  nan |
|      3 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.48 |             69.04 |         71.19 |         66.9  |          71.96 |        61.02 |           73.07 |             83.18 |             17.4  |         6.34 |             61.74 | medium             |                2.14 |                   nan |                  nan |
|      4 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |             68.9  |         72.4  |         71.63 |          66.16 |        62.06 |           42.97 |             69.78 |             82.89 |         7.64 |             85.14 | short              |                2.22 |                   nan |                  nan |
|      5 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.79 |             68.55 |         78.8  |         70.43 |          66.66 |        65.53 |           79.78 |             71.1  |             39.85 |         4.66 |             89.69 | short              |                0.93 |                   nan |                  nan |
|      6 | SM       | SM Energy Company                                      | US       |                6.64 |             68.53 |         68.29 |         62.19 |          68.77 |        73.2  |           79.89 |             50.72 |             77.5  |         6.71 |             87.81 | long               |               -0.18 |                   nan |                  nan |
|      7 | DAC      | Danaos Corporation                                     | OTHER    |                2.24 |             68.48 |         69.31 |         64.98 |          68.29 |        68.68 |           77.72 |             53.83 |             59.85 |         3.29 |             83.35 | short              |                2.9  |                   nan |                  nan |
|      8 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.58 |             67.07 |         73.34 |         69.21 |          64.94 |        61.36 |           66.6  |             53.41 |             56.51 |         7.31 |             75.57 | short              |                1.62 |                   nan |                  nan |
|      9 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.16 |             66.49 |         74    |         67.02 |          65.96 |        61.21 |          nan    |             58.28 |             50    |         2.08 |             70.75 | short              |               -5.86 |                   nan |                  nan |
|     10 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.59 |         70.21 |         70.7  |          60.98 |        56.29 |           58.13 |             54.81 |             41.93 |         5.96 |             79.32 | swing              |                0.67 |                   nan |                  nan |
|     11 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |             65.46 |         69.95 |         67.28 |          63.64 |        61.17 |           65.95 |             83.46 |             40.39 |         2.88 |             64.78 | short              |                1.02 |                   nan |                  nan |
|     12 | HQL      | HQL                                                    | US       |                0.56 |             65.15 |         75.52 |         69.87 |          60.42 |        48.06 |           47.48 |            nan    |             26    |         2.28 |             59.6  | short              |                0.6  |                   nan |                  nan |
|     13 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.9  |             65.03 |         70.5  |         69.4  |          60.65 |        52.1  |           47.53 |             83.46 |             31.78 |         2.07 |             62.78 | short              |                1.32 |                   nan |                  nan |
|     14 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.32 |             64.97 |         61.28 |         66.73 |          70.74 |        63.21 |           67.19 |             75.02 |             31.64 |         6.06 |             89.58 | medium             |                1.02 |                   nan |                  nan |
|     15 | WKC      | World Kinect Corporation                               | US       |                1.65 |             64.61 |         61.45 |         71.72 |          67.77 |        59.13 |           44.59 |             71.21 |             56.33 |         4.91 |             84.31 | swing              |                1.13 |                   nan |                  nan |
|     16 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.03 |             64.13 |         64.74 |         63.53 |          62.17 |        71.97 |           84.06 |             72.31 |             74.84 |         3.84 |             81.07 | long               |               -2.57 |                   nan |                  nan |
|     17 | CNC      | Centene Corporation                                    | US       |               28.4  |             63.92 |         64.8  |         63.03 |          65.7  |        60.17 |           50.47 |             57.16 |             64.79 |         5.88 |             88.46 | medium             |                0.13 |                   nan |                  nan |
|     18 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.53 |             63.71 |         46.82 |         60.11 |          67.91 |        67.32 |           65.74 |             63.67 |             63.25 |         5.82 |             84.57 | medium             |                1.41 |                   nan |                  nan |
|     19 | PEO      | Adams Natural Resources Fund, Inc.                     | US       |                0.67 |             63.65 |         71.81 |         65.38 |          61.93 |        55.01 |           60.98 |             83.18 |             20.57 |         2.06 |             68.24 | short              |               -0.32 |                   nan |                  nan |
|     20 | SLDE     | Slide Insurance Holdings, Inc.                         | US       |                2.16 |             63.64 |         63.43 |         64.57 |          63.85 |        61.93 |           74.53 |             52.7  |             41.47 |         5.77 |             80.19 | swing              |                1.82 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.69 |                  86.11 |                    73.32 |                 68.89 |              78.28 |                58.03 |                   41.97 |           50.76 |             58.31 |       0.035 |         nan |       nan |       16.23 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  70.16 |                    73.01 |                 75.9  |              71.13 |                79.09 |                   20.91 |           91.54 |             63.86 |       0.179 |         nan |       nan |        4.33 |         2.8  |          5.22 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.74 |                  77.66 |                    71.02 |                 69.13 |              74.59 |                72.97 |                   27.03 |           59.72 |             55.39 |       0.572 |         nan |       nan |       -5.14 |         5.38 |          8.62 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            4 | SM        | SM Energy Company                                      | US       |                6.64 |                  71.59 |                    70.15 |                 69.87 |              68.7  |                67.15 |                   32.85 |           79.89 |             50.72 |       0.192 |         nan |       nan |        4.53 |         4.41 |          5.71 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            5 | GSL       | Global Ship Lease Inc New                              | OTHER    |                1.32 |                  75.82 |                    69.45 |                 68.65 |              70.8  |                68.87 |                   31.13 |           73.91 |             38.11 |       0.085 |         nan |       nan |        3.57 |         4.76 |          4.07 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|            6 | MAGN      | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.11 |              72.51 |                67.9  |                   32.1  |           60    |             71.36 |       0.529 |         nan |       nan |        6.42 |         7.5  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            7 | YPF       | YPF Sociedad Anónima                                   | OTHER    |               16.53 |                  75.02 |                    69.01 |                 68.43 |              70.8  |                57.9  |                   42.1  |           65.74 |             63.67 |       0.061 |         nan |       nan |        1.68 |         8.47 |          1.25 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            8 | IHS       | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.53 |                    68.9  |                 70.07 |              71.05 |                66.52 |                   33.48 |           63.66 |             82.93 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | TNK       | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |                  64.95 |                    67.86 |                 69.75 |              67.47 |                79.19 |                   20.81 |           75.87 |             64.53 |       0.077 |         nan |       nan |        3.2  |         9.17 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           10 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.47 |                  66.02 |                    67.86 |                 69.53 |              67.3  |                69.94 |                   30.06 |           74.28 |             71.76 |       0.021 |         nan |       nan |        3.81 |         6.05 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | AMCX      | AMC Global Media Inc.                                  | US       |                0.43 |                  73.8  |                    67.6  |                 65.1  |              72.93 |                71.22 |                   28.78 |           42.97 |             69.78 |       2.008 |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           12 | DAC       | Danaos Corporation                                     | OTHER    |                2.24 |                  63.21 |                    65.78 |                 67.63 |              64.91 |                77.91 |                   22.09 |           77.72 |             53.83 |       0.002 |         nan |       nan |        3.74 |         5.81 |          4.82 |        0.12 |                 nan |              nan |                  11 |                  0.58 |
|           13 | AVGO      | Broadcom Inc.                                          | US       |             1741.47 |                  57.41 |                    65.59 |                 65.87 |              61.47 |                76.86 |                   23.14 |           76.2  |             63.06 |       0.014 |         nan |       nan |       48.11 |        21.62 |         70.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           14 | HMC       | Honda Motor Company, Ltd.                              | OTHER    |               35.03 |                  57.02 |                    65.39 |                 69.43 |              62.57 |                79.4  |                   20.6  |           84.06 |             72.31 |       0.042 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|           15 | UNIT      | Uniti Group Inc.                                       | US       |                2.03 |                  73.26 |                    65.21 |                 63.38 |              65.73 |                55.37 |                   44.63 |           70.29 |             30.21 |      -0.11  |         nan |       nan |        9.02 |       -13.61 |          2.52 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           16 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  57.45 |                    64.03 |                 65.85 |              62.9  |                73.27 |                   26.73 |           65.95 |             83.46 |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           17 | RCI       | Rogers Communications Inc.                             | OTHER    |               16.95 |                  58.34 |                    63.66 |                 65    |              57.44 |                63.15 |                   36.85 |           92.66 |             40.77 |       0.279 |         nan |       nan |        7.28 |        10.37 |          4.43 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           18 | MTRX      | Matrix Service Company                                 | US       |                0.29 |                  74.83 |                    63.13 |                 60.4  |              69.35 |                53.1  |                   46.9  |           39.57 |             59.14 |       0.302 |         nan |       nan |      -46.91 |        16.86 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|           19 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  59.16 |                    62.57 |                 64.94 |              59.91 |                72    |                   28    |           83.95 |             43.54 |       0.094 |         nan |       nan |        3.93 |       159.75 |          4.66 |        2.73 |                 nan |              nan |                  12 |                  0.63 |
|           20 | EMBC      | Embecta Corp.                                          | US       |                0.25 |                  68.19 |                    62.47 |                 61.35 |              63.45 |                54.07 |                   45.93 |           62.51 |             46.19 |       0.471 |         nan |       nan |        5.53 |         2.94 |          3.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  70.16 |                    73.01 |                 75.9  |              71.13 |                79.09 |                   20.91 |           91.54 |             63.86 |       0.179 |         nan |       nan |        4.33 |         2.8  |          5.22 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | IHS       | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.53 |                    68.9  |                 70.07 |              71.05 |                66.52 |                   33.48 |           63.66 |             82.93 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | SM        | SM Energy Company                                      | US       |                6.64 |                  71.59 |                    70.15 |                 69.87 |              68.7  |                67.15 |                   32.85 |           79.89 |             50.72 |       0.192 |         nan |       nan |        4.53 |         4.41 |          5.71 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            9 | TNK       | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |                  64.95 |                    67.86 |                 69.75 |              67.47 |                79.19 |                   20.81 |           75.87 |             64.53 |       0.077 |         nan |       nan |        3.2  |         9.17 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           10 | PARR      | Par Pacific Holdings, Inc.                             | US       |                3.47 |                  66.02 |                    67.86 |                 69.53 |              67.3  |                69.94 |                   30.06 |           74.28 |             71.76 |       0.021 |         nan |       nan |        3.81 |         6.05 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | HMC       | Honda Motor Company, Ltd.                              | OTHER    |               35.03 |                  57.02 |                    65.39 |                 69.43 |              62.57 |                79.4  |                   20.6  |           84.06 |             72.31 |       0.042 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|            3 | MOMO      | Hello Group Inc.                                       | OTHER    |                0.74 |                  77.66 |                    71.02 |                 69.13 |              74.59 |                72.97 |                   27.03 |           59.72 |             55.39 |       0.572 |         nan |       nan |       -5.14 |         5.38 |          8.62 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            6 | MAGN      | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.11 |              72.51 |                67.9  |                   32.1  |           60    |             71.36 |       0.529 |         nan |       nan |        6.42 |         7.5  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            1 | VOLV-B.ST | AB Volvo (publ)                                        | EUROPE   |               62.69 |                  86.11 |                    73.32 |                 68.89 |              78.28 |                58.03 |                   41.97 |           50.76 |             58.31 |       0.035 |         nan |       nan |       16.23 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            5 | GSL       | Global Ship Lease Inc New                              | OTHER    |                1.32 |                  75.82 |                    69.45 |                 68.65 |              70.8  |                68.87 |                   31.13 |           73.91 |             38.11 |       0.085 |         nan |       nan |        3.57 |         4.76 |          4.07 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|            7 | YPF       | YPF Sociedad Anónima                                   | OTHER    |               16.53 |                  75.02 |                    69.01 |                 68.43 |              70.8  |                57.9  |                   42.1  |           65.74 |             63.67 |       0.061 |         nan |       nan |        1.68 |         8.47 |          1.25 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           12 | DAC       | Danaos Corporation                                     | OTHER    |                2.24 |                  63.21 |                    65.78 |                 67.63 |              64.91 |                77.91 |                   22.09 |           77.72 |             53.83 |       0.002 |         nan |       nan |        3.74 |         5.81 |          4.82 |        0.12 |                 nan |              nan |                  11 |                  0.58 |
|           13 | AVGO      | Broadcom Inc.                                          | US       |             1741.47 |                  57.41 |                    65.59 |                 65.87 |              61.47 |                76.86 |                   23.14 |           76.2  |             63.06 |       0.014 |         nan |       nan |       48.11 |        21.62 |         70.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           16 | ETG       | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  57.45 |                    64.03 |                 65.85 |              62.9  |                73.27 |                   26.73 |           65.95 |             83.46 |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           11 | AMCX      | AMC Global Media Inc.                                  | US       |                0.43 |                  73.8  |                    67.6  |                 65.1  |              72.93 |                71.22 |                   28.78 |           42.97 |             69.78 |       2.008 |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           17 | RCI       | Rogers Communications Inc.                             | OTHER    |               16.95 |                  58.34 |                    63.66 |                 65    |              57.44 |                63.15 |                   36.85 |           92.66 |             40.77 |       0.279 |         nan |       nan |        7.28 |        10.37 |          4.43 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           19 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  59.16 |                    62.57 |                 64.94 |              59.91 |                72    |                   28    |           83.95 |             43.54 |       0.094 |         nan |       nan |        3.93 |       159.75 |          4.66 |        2.73 |                 nan |              nan |                  12 |                  0.63 |
|           31 | ORC       | Orchid Island Capital, Inc.                            | US       |                1.15 |                  55.19 |                    60.86 |                 64.22 |              56.05 |                69.5  |                   30.5  |           93.03 |             37.99 |     nan     |         nan |       nan |      nan    |         6.42 |          3.8  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           30 | PKX       | POSCO Holdings Inc.                                    | OTHER    |               14.87 |                  57.51 |                    60.99 |                 63.97 |              57.75 |                61.54 |                   38.46 |           83.88 |             52.63 |     nan     |         nan |       nan |        3.7  |         9.84 |         28.36 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | UTG       | Reaves Utility Income Fund                             | US       |                3.17 |                  58.68 |                    62.39 |                 63.85 |              61.66 |                61.59 |                   38.41 |           62.89 |             83.18 |       0.003 |         nan |       nan |      nan    |       nan    |          2.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ALL      | The Allstate Corporation                         | US       |               56.56 |                     0.06 |    -0.06 |      0.07 |                  84.7  |                        68.3  |         60.17 |         66.28 |          62.55 |        56.73 |           66.36 |             61.18 |         3.08 |
|               2 | HRTG     | Heritage Insurance Holdings, Inc.                | US       |                0.85 |                     0.06 |    -0.06 |      0.24 |                  83.68 |                        67.75 |         70.21 |         70.7  |          60.98 |        56.29 |           58.13 |             54.81 |         5.96 |
|               3 | AMZN     | Amazon.com, Inc.                                 | US       |             2494.42 |                     0.06 |    -0.02 |      0.07 |                  73.23 |                        67.25 |         62.88 |         56.08 |          60.12 |        58.48 |           77.39 |             62.29 |         5.83 |
|               4 | IRWD     | Ironwood Pharmaceuticals, Inc.                   | US       |                0.59 |                     0.07 |    -0.03 |      0.07 |                  72.81 |                        66.94 |         56.27 |         55.41 |          69.85 |        82.16 |           91.54 |             63.86 |         6.43 |
|               5 | HMC      | Honda Motor Company, Ltd.                        | OTHER    |               35.03 |                     0.02 |     0.01 |      0.08 |                  45.4  |                        66.84 |         64.74 |         63.53 |          62.17 |        71.97 |           84.06 |             72.31 |         3.84 |
|               6 | CLW      | Clearwater Paper Corporation                     | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  81.01 |                        64.62 |         68.05 |         64.2  |          50.98 |        47.64 |           46.5  |             60.94 |         6.88 |
|               7 | WKC      | World Kinect Corporation                         | US       |                1.65 |                     0.07 |     0    |      0.01 |                  58.81 |                        64.28 |         61.45 |         71.72 |          67.77 |        59.13 |           44.59 |             71.21 |         4.91 |
|               8 | SLDE     | Slide Insurance Holdings, Inc.                   | US       |                2.16 |                     0.04 |     0    |      0.04 |                  59.02 |                        63.95 |         63.43 |         64.57 |          63.85 |        61.93 |           74.53 |             52.7  |         5.77 |
|               9 | LNC      | Lincoln National Corporation                     | US       |                7.37 |                     0.05 |    -0.05 |      0.06 |                  84.05 |                        63.22 |         64.14 |         66.86 |          57.91 |        57.05 |           42.02 |             58.52 |         4.69 |
|              10 | MSFT     | Microsoft Corporation                            | US       |             3189.27 |                     0.02 |    -0.01 |      0.24 |                  52.27 |                        62.57 |         71.02 |         64.74 |          54.46 |        53.24 |           52.68 |             57.89 |         5.73 |
|              11 | YPF      | YPF Sociedad Anónima                             | OTHER    |               16.53 |                     0.07 |    -0.02 |      0.01 |                  65.4  |                        62.56 |         46.82 |         60.11 |          67.91 |        67.32 |           65.74 |             63.67 |         5.82 |
|              12 | DSX      | Diana Shipping Inc.                              | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  57.27 |                        61.7  |         65.38 |         49.08 |          55.47 |        60.71 |           60    |             56.14 |         4.64 |
|              13 | MA       | Mastercard Incorporated                          | US       |              423.99 |                     0.03 |    -0.03 |      0.01 |                  65.65 |                        61.02 |         54.67 |         56.67 |          51.91 |        49.5  |           70.51 |             58.26 |         3.19 |
|              14 | PKX      | POSCO Holdings Inc.                              | OTHER    |               14.87 |                     0.03 |     0.01 |      0.11 |                  50.7  |                        60.98 |         57.4  |         35.66 |          49.22 |        61.9  |           83.88 |             52.63 |         6.16 |
|              15 | V        | Visa Inc.                                        | US       |              581.44 |                     0.03 |    -0.03 |     -0.01 |                  62.01 |                        60.16 |         50.75 |         57.51 |          53.63 |        49.5  |           67.1  |             57.84 |         2.87 |
|              16 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund | US       |                0.78 |                     0.02 |     0.01 |     -0.01 |                  49.65 |                        59.8  |         52.52 |         58.15 |          59.17 |        58.39 |           54.01 |             83.18 |         1.86 |
|              17 | GSL      | Global Ship Lease Inc New                        | OTHER    |                1.32 |                     0.05 |    -0.01 |      0.01 |                  72.48 |                        58.64 |         54.54 |         53.26 |          62.66 |        71.39 |           73.91 |             38.11 |         3.78 |
|              18 | AMD      | Advanced Micro Devices, Inc.                     | US       |              696.41 |                     0.11 |     0.01 |     -0.02 |                  36.12 |                        58.34 |         46.84 |         59.52 |          69.98 |        60.33 |           60.79 |             73.36 |         7.34 |
|              19 | KELYA    | Kelly Services, Inc.                             | US       |                0.47 |                     0.03 |     0.01 |      0.02 |                  51.69 |                        57.97 |         61.86 |         73.24 |          59.46 |        49.87 |           19.7  |             64.38 |         6.34 |
|              20 | GOOGL    | Alphabet Inc.                                    | US       |             3655.41 |                     0.09 |    -0.04 |     -0.03 |                  61.48 |                        57.81 |         43.6  |         43.56 |          59.45 |        59.18 |           81.74 |             69.63 |         4.92 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation    | US       |             4715.21 |             65.61 |         68    |         57.53 |          63.38 |        67.83 |           91.85 |             58.81 |             44.38 |         5.64 |             89.54 | short              |                0.07 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation    | US       |                1.87 |             59.32 |         58.8  |         59.83 |          57.71 |        64.71 |           55.68 |             47.85 |             84.26 |         8.45 |             85.47 | long               |               -3.87 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.          | OTHER    |               34.09 |             42.45 |         35.73 |         38.2  |          46.7  |        52.42 |           57.54 |             49.96 |             58.9  |         8.5  |             86.72 | long               |              -11.29 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.          | OTHER    |                2.12 |             41.26 |         26.43 |         36.83 |          45.69 |        60.67 |           59.48 |             47.91 |             89.87 |         8.5  |             85.99 | long               |               -0.75 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group     | OTHER    |                0.92 |             38.81 |         28.38 |         34.8  |          42.81 |        53.97 |           53.59 |             47.1  |             72.7  |         6.27 |             78.58 | long               |               -1.49 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.   | OTHER    |                1.31 |             37.86 |         29.9  |         34.34 |          41.38 |        54.58 |           51.44 |             41    |             83.47 |         7.18 |             78.43 | long               |               -2.1  |                   nan |                  nan |
|    nan | WB       | Weibo Corporation     | OTHER    |                1.63 |             35.75 |         30.85 |         29.44 |          40.64 |        57.52 |           69.08 |             24.58 |             76.09 |         4.92 |             81.52 | long               |               -2.79 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.          | OTHER    |               10.43 |             24.78 |         27.54 |         21.97 |          23.45 |        26.11 |           24.14 |             36.27 |             29.49 |         6.95 |             76.61 | short              |               -4.51 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp. | OTHER    |                0.86 |             21.77 |         58.31 |         22.84 |          17.71 |        20.7  |            8.62 |             27.05 |             36.29 |         7.78 |             75.24 | short              |               -6.21 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.95
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.95
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.91

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
- Excluded by hard/data filters: **874**
- Event watch (otherwise eligible): **9**
- Final eligible: **117**
- Eligible change vs previous stored run: **+13**

Top exclusion categories:
- market_cap: 838
- liquidity: 196
- price: 115
- data_confidence: 42
- price_history: 20
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 10 |  | 5 | 2 | main,value,quality_value |
| TNK | 2 | 9 |  | 4 | 2 | main,value,quality_value |
| SM | 6 | 4 |  | 3 | 2 | main,value,quality_value |
| IRWD | 24 | 2 | 4 | 1 | 2 | value,pullback,quality_value |
| HRTG | 10 | 60 | 2 | 52 | 2 | main,pullback |
| HMC | 16 | 14 | 5 | 6 | 1 | pullback,quality_value |
| IHS | 38 | 8 |  | 2 | 1 | value,quality_value |
| GSL | 39 | 5 | 17 | 10 | 1 | value,quality_value |
| VOLV-B.ST | 55 | 1 | 24 | 9 | 1 | value,quality_value |
| MAGN | 66 | 6 |  | 8 | 1 | value,quality_value |
| MOMO | 90 | 3 | 32 | 7 | 1 | value,quality_value |
| TWN | 3 |  |  |  | 1 | main |
| AMCX | 4 | 11 |  | 15 | 1 | main |
| SU.PA | 5 | 28 |  | 20 | 1 | main |
| DAC | 7 | 12 |  | 12 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 75.18 | 70.16 | 72.81 | 91.54 | 63.86 | 79.09 | 63.06 |
| 2 | GSL | value+pullback | 69.54 | 75.82 | 72.48 | 73.91 | 38.11 | 68.87 | 58.60 |
| 3 | VOLV-B.ST | value+pullback | 68.44 | 86.11 | 70.20 | 50.76 | 58.31 | 58.03 | 54.10 |
| 4 | MOMO | value+pullback | 67.75 | 77.66 | 61.42 | 59.72 | 55.39 | 72.97 | 45.29 |
| 5 | YPF | value+pullback | 66.66 | 75.02 | 65.40 | 65.74 | 63.67 | 57.90 | 63.71 |
| 6 | IRS | value+pullback | 66.38 | 59.16 | 69.12 | 83.95 | 43.54 | 72.00 | 49.23 |
| 7 | INVA | value+pullback | 65.72 | 58.49 | 69.31 | 80.26 | 36.87 | 75.59 | 41.29 |
| 8 | HMC | value+pullback | 64.17 | 57.02 | 45.40 | 84.06 | 72.31 | 79.40 | 64.13 |
| 9 | BHF | value+pullback | 60.70 | 69.07 | 61.84 | 49.98 | 42.62 | 63.81 | 45.93 |
| 10 | ALL-PH | value+pullback | 60.09 | 61.25 | 62.68 | 66.36 | 42.11 | 59.40 | 46.27 |
| 11 | PKX | value+pullback | 60.08 | 57.51 | 50.70 | 83.88 | 52.63 | 61.54 | 53.31 |
| 12 | LNC | value+pullback | 59.58 | 58.08 | 84.05 | 42.02 | 58.52 | 44.93 | 61.02 |
| 13 | BYD | value+pullback | 58.48 | 57.00 | 52.37 | 82.83 | 35.64 | 61.48 | 47.40 |
| 14 | MTRX | value+pullback | 57.93 | 74.83 | 52.04 | 39.57 | 59.14 | 53.10 | 45.52 |
| 15 | MSFT | value+pullback | 55.87 | 64.66 | 52.27 | 52.68 | 57.89 | 48.59 | 59.60 |
| 16 | CHTR | value+pullback | 54.39 | 64.45 | 65.62 | 54.24 | 38.32 | 33.39 | 45.22 |
| 17 | AAPL | value+pullback | 53.31 | 60.17 | 46.79 | 55.59 | 48.70 | 51.77 | 50.73 |
| 18 | TNK | value | 53.16 | 64.95 | 30.95 | 75.87 | 64.53 | 79.19 | 71.53 |
| 19 | KELYA | value+pullback | 52.88 | 70.82 | 51.69 | 19.70 | 64.38 | 46.60 | 60.66 |
| 20 | IHS | value | 52.31 | 70.53 | 34.54 | 63.66 | 82.93 | 66.52 | 58.75 |
