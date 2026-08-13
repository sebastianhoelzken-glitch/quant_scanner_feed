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

- **EUROPE:** 90.7/100
- **OTHER:** 75.6/100
- **US:** 82.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.44 |             74.5  |         73.59 |         74.47 |          78.79 |        74.52 |           80.43 |             72.33 |             61.3  |         6.79 |             85.65 | medium             |               -0.04 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.49 |             72.99 |         75.74 |         65.69 |          70.8  |        75.19 |           80.48 |             64.73 |             74.26 |         5.11 |             84.89 | short              |                0.67 |                   nan |                  nan |
|      3 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.59 |             68.11 |         74.66 |         70.9  |          65.33 |        61.26 |           60.89 |             55.16 |             59.72 |         7.34 |             75.57 | short              |                2.66 |                   nan |                  nan |
|      4 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |             67.9  |         69.2  |         70.34 |          66.59 |        63.03 |           45.42 |             70.68 |             83.4  |         7.62 |             85.14 | swing              |                1.22 |                   nan |                  nan |
|      5 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.76 |             67.42 |         77.18 |         68.59 |          66.01 |        66.24 |           79.78 |             67.5  |             45.85 |         4.63 |             89.65 | short              |               -0.2  |                   nan |                  nan |
|      6 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.48 |             67.29 |         69.06 |         65.52 |          70.79 |        59.51 |           72.85 |             82.33 |             14.74 |         6.25 |             61.74 | medium             |                0.39 |                   nan |                  nan |
|      7 | LLY      | Eli Lilly and Company                                  | US       |              946.93 |             66.89 |         67.15 |         66.62 |          69.09 |        66.63 |           90.09 |             66.25 |             26.15 |         4.24 |             89.59 | medium             |               -0.32 |                   nan |                  nan |
|      8 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.86 |             66.55 |         71.38 |         71.18 |          61.92 |        57.42 |           63.26 |             55.2  |             39.75 |         5.97 |             79.32 | short              |                1.63 |                   nan |                  nan |
|      9 | CNC      | Centene Corporation                                    | US       |               28.85 |             65.88 |         66.31 |         65.45 |          67.7  |        62.87 |           52.83 |             58.4  |             69.41 |         5.86 |             88.46 | medium             |                2.1  |                   nan |                  nan |
|     10 | DAC      | Danaos Corporation                                     | OTHER    |                2.23 |             65.39 |         67.38 |         64.57 |          66.22 |        64.16 |           62.61 |             55.51 |             59.95 |         3.25 |             83.35 | short              |               -0.19 |                   nan |                  nan |
|     11 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               34.99 |             65.33 |         66.76 |         64.69 |          60.76 |        65.97 |           80.87 |             73.24 |             51.44 |         3.78 |             78.07 | short              |               -1.38 |                   nan |                  nan |
|     12 | HQL      | HQL                                                    | US       |                0.56 |             64.47 |         73.94 |         69.35 |          59.6  |        46.58 |           49.33 |            nan    |             20.45 |         2.24 |             59.6  | short              |               -0.08 |                   nan |                  nan |
|     13 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |             64.32 |         69.06 |         65.73 |          62.91 |        60.34 |           69.26 |             82.6  |             34.78 |         2.85 |             64.78 | short              |               -0.12 |                   nan |                  nan |
|     14 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              605.42 |             64.13 |         56.96 |         64.55 |          70.56 |        63.71 |           67.04 |             75.98 |             33.96 |         6.05 |             89.58 | medium             |                0.18 |                   nan |                  nan |
|     15 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.89 |             64.07 |         68.96 |         67.91 |          60.23 |        51.76 |           51.1  |             82.6  |             27.55 |         2.06 |             62.78 | short              |                0.36 |                   nan |                  nan |
|     16 | CEF      | CEF                                                    | OTHER    |                7.16 |             63.79 |         73.23 |         40.45 |          54.35 |        84.6  |          nan    |            nan    |            100    |         5.24 |             55.57 | long               |               -1.93 |                   nan |                  nan |
|     17 | WKC      | World Kinect Corporation                               | US       |                1.64 |             62.98 |         57.01 |         68.56 |          66.88 |        59.07 |           49.73 |             71.71 |             55.2  |         4.88 |             84.31 | swing              |               -0.51 |                   nan |                  nan |
|     18 | AMZN     | Amazon.com, Inc.                                       | US       |             2506.8  |             62.97 |         64.11 |         58.72 |          63.07 |        62.87 |           80.87 |             63.9  |             40.1  |         5.77 |             89.85 | short              |               -1.15 |                   nan |                  nan |
|     19 | DSX      | Diana Shipping Inc.                                    | OTHER    |                0.27 |             61.95 |         63.93 |         50.85 |          59.96 |        68.46 |           66.72 |             57.55 |             75.77 |         4.56 |             79.77 | long               |                4.11 |                   nan |                  nan |
|     20 | AIR.PA   | Airbus SE                                              | EUROPE   |              169.89 |             61.59 |         68.3  |         64.8  |          58.15 |        58.39 |           67.39 |             53.78 |             46.7  |         4.6  |             88.34 | short              |               -0.08 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.49 |                  75.34 |                    74.65 |                 75.98 |              75.41 |                81.62 |                   18.38 |           80.48 |             64.73 |       0.078 |         nan |       nan |        3.2  |         9.07 |          4.88 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            2 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.44 |                  67.94 |                    70.43 |                 72.55 |              69.38 |                73.5  |                   26.5  |           80.43 |             72.33 |       0.021 |         nan |       nan |        3.81 |         5.99 |          4.65 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  78.79 |                    69.47 |                 66.76 |              75.01 |                62.31 |                   37.69 |           45.42 |             70.68 |       2.061 |         nan |       nan |        6.98 |         4.27 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            4 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.86 |                  69.76 |                    69.42 |                 71.83 |              67.57 |                66.09 |                   33.91 |           89.41 |             54.48 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.48 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.39 |                  73.82 |                    69.11 |                 69.14 |              72.52 |                67.84 |                   32.16 |           60    |             71.64 |       0.515 |         nan |       nan |        6.42 |         7.7  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            6 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.32 |                  73.09 |                    68.21 |                 67.19 |              70.08 |                75.35 |                   24.65 |           68.61 |             38.97 |       0.085 |         nan |       nan |        3.57 |         4.75 |          4.11 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  68.88 |                    67.6  |                 69.06 |              66.45 |                69.19 |                   30.81 |           84.32 |             44.04 |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            8 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  69.5  |                    67.01 |                 67.99 |              68.27 |                69.52 |                   30.48 |           70.87 |             57.14 |       0.96  |         nan |       nan |        5.3  |      -122.51 |          2.15 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | INVA     | Innoviva, Inc.                                         | US       |                1.31 |                  65.99 |                    66.71 |                 68.14 |              65.41 |                77.91 |                   22.09 |           83.8  |             38.76 |       0.073 |         nan |       nan |        6.43 |         9.45 |          4.85 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           10 | AVGO     | Broadcom Inc.                                          | US       |             1731.99 |                  57.41 |                    66.23 |                 66.81 |              61.84 |                77.81 |                   22.19 |           78.23 |             64.98 |       0.014 |         nan |       nan |       48.11 |        21.51 |         70.12 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           11 | STNG     | Scorpio Tankers Inc.                                   | OTHER    |                3.38 |                  60.84 |                    65.81 |                 67.08 |              62    |                79.03 |                   20.97 |           87.57 |             39.66 |       0.07  |         nan |       nan |        3.37 |        13.45 |          4.86 |        2.46 |                 nan |              nan |                  12 |                  0.63 |
|           12 | CNC      | Centene Corporation                                    | US       |               28.85 |                  71.33 |                    65.34 |                 62.12 |              66.86 |                53.7  |                   46.3  |           52.83 |             58.4  |       0.29  |         nan |       nan |        4.84 |        12.71 |        nan    |        1.17 |                 nan |              nan |                  10 |                  0.53 |
|           13 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  56.64 |                    64.83 |                 66.98 |              63.18 |                78.56 |                   21.44 |           69.26 |             82.6  |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           14 | UNIT     | Uniti Group Inc.                                       | US       |                2.01 |                  73.85 |                    64.7  |                 62.63 |              65.44 |                51.83 |                   48.17 |           68.89 |             29.36 |      -0.111 |         nan |       nan |        9.02 |       -13.46 |          2.49 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           15 | MTRX     | Matrix Service Company                                 | US       |                0.29 |                  76.21 |                    63.89 |                 60.98 |              70.43 |                53.47 |                   46.53 |           39.05 |             59.33 |       0.299 |         nan |       nan |      -46.91 |        17.01 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|           16 | ATNI     | ATN International, Inc.                                | US       |                0.42 |                  70.77 |                    63.47 |                 62.17 |              66.68 |                59.37 |                   40.63 |           55.41 |             50.43 |       0.247 |         nan |       nan |        5.43 |        29.33 |          3.07 |        5.35 |                 nan |              nan |                  12 |                  0.63 |
|           17 | BYD      | Boyd Gaming Corporation                                | US       |                5.25 |                  62.12 |                    63.37 |                 62.97 |              60.06 |                64.7  |                   35.3  |           79.13 |             36.86 |       0.047 |         nan |       nan |        7.64 |        10.75 |          3.7  |        3.03 |                 nan |              nan |                  11 |                  0.58 |
|           18 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.95 |                  57.02 |                    62.96 |                 64.4  |              56.72 |                63.55 |                   36.45 |           91.44 |             42.29 |     nan     |         nan |       nan |        7.28 |        10.38 |          4.43 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           19 | BHF      | Brighthouse Financial, Inc.                            | US       |                3    |                  68.94 |                    62.68 |                 60.83 |              65.84 |                65.51 |                   34.49 |           53.47 |             44.11 |       5.745 |         nan |       nan |      nan    |         2.99 |          4.77 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           20 | MFA      | MFA Financial, Inc.                                    | US       |                0.81 |                  61.48 |                    62.17 |                 62.87 |              59.5  |                64.41 |                   35.59 |           80.31 |             36.45 |     nan     |         nan |       nan |      nan    |         6.51 |          9.12 |        2.48 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.49 |                  75.34 |                    74.65 |                 75.98 |              75.41 |                81.62 |                   18.38 |           80.48 |             64.73 |       0.078 |         nan |       nan |        3.2  |         9.07 |          4.88 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            2 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.44 |                  67.94 |                    70.43 |                 72.55 |              69.38 |                73.5  |                   26.5  |           80.43 |             72.33 |       0.021 |         nan |       nan |        3.81 |         5.99 |          4.65 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.86 |                  69.76 |                    69.42 |                 71.83 |              67.57 |                66.09 |                   33.91 |           89.41 |             54.48 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.48 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.39 |                  73.82 |                    69.11 |                 69.14 |              72.52 |                67.84 |                   32.16 |           60    |             71.64 |       0.515 |         nan |       nan |        6.42 |         7.7  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  68.88 |                    67.6  |                 69.06 |              66.45 |                69.19 |                   30.81 |           84.32 |             44.04 |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            9 | INVA     | Innoviva, Inc.                                         | US       |                1.31 |                  65.99 |                    66.71 |                 68.14 |              65.41 |                77.91 |                   22.09 |           83.8  |             38.76 |       0.073 |         nan |       nan |        6.43 |         9.45 |          4.85 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            8 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  69.5  |                    67.01 |                 67.99 |              68.27 |                69.52 |                   30.48 |           70.87 |             57.14 |       0.96  |         nan |       nan |        5.3  |      -122.51 |          2.15 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.32 |                  73.09 |                    68.21 |                 67.19 |              70.08 |                75.35 |                   24.65 |           68.61 |             38.97 |       0.085 |         nan |       nan |        3.57 |         4.75 |          4.11 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           11 | STNG     | Scorpio Tankers Inc.                                   | OTHER    |                3.38 |                  60.84 |                    65.81 |                 67.08 |              62    |                79.03 |                   20.97 |           87.57 |             39.66 |       0.07  |         nan |       nan |        3.37 |        13.45 |          4.86 |        2.46 |                 nan |              nan |                  12 |                  0.63 |
|           13 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  56.64 |                    64.83 |                 66.98 |              63.18 |                78.56 |                   21.44 |           69.26 |             82.6  |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           10 | AVGO     | Broadcom Inc.                                          | US       |             1731.99 |                  57.41 |                    66.23 |                 66.81 |              61.84 |                77.81 |                   22.19 |           78.23 |             64.98 |       0.014 |         nan |       nan |       48.11 |        21.51 |         70.12 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|            3 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  78.79 |                    69.47 |                 66.76 |              75.01 |                62.31 |                   37.69 |           45.42 |             70.68 |       2.061 |         nan |       nan |        6.98 |         4.27 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           18 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.95 |                  57.02 |                    62.96 |                 64.4  |              56.72 |                63.55 |                   36.45 |           91.44 |             42.29 |     nan     |         nan |       nan |        7.28 |        10.38 |          4.43 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           26 | ORC      | Orchid Island Capital, Inc.                            | US       |                1.15 |                  55.01 |                    60.74 |                 64.1  |              55.91 |                69.48 |                   30.52 |           92.88 |             38.02 |     nan     |         nan |       nan |      nan    |         6.43 |          3.8  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           21 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.76 |                  48.88 |                    61.96 |                 64.02 |              56.28 |                79.66 |                   20.34 |           79.78 |             67.5  |       0.031 |         nan |       nan |       22.47 |        25.61 |         36.41 |        1.88 |                 nan |              nan |                  12 |                  0.63 |
|          nan | UTG      | Reaves Utility Income Fund                             | US       |                3.18 |                  54.56 |                    60.81 |                 62.98 |              59.18 |                64.75 |                   35.25 |           65.44 |             82.33 |       0.003 |         nan |       nan |      nan    |       nan    |          2.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           17 | BYD      | Boyd Gaming Corporation                                | US       |                5.25 |                  62.12 |                    63.37 |                 62.97 |              60.06 |                64.7  |                   35.3  |           79.13 |             36.86 |       0.047 |         nan |       nan |        7.64 |        10.75 |          3.7  |        3.03 |                 nan |              nan |                  11 |                  0.58 |
|           20 | MFA      | MFA Financial, Inc.                                    | US       |                0.81 |                  61.48 |                    62.17 |                 62.87 |              59.5  |                64.41 |                   35.59 |           80.31 |             36.45 |     nan     |         nan |       nan |      nan    |         6.51 |          9.12 |        2.48 |                 nan |              nan |                   9 |                  0.47 |
|           14 | UNIT     | Uniti Group Inc.                                       | US       |                2.01 |                  73.85 |                    64.7  |                 62.63 |              65.44 |                51.83 |                   48.17 |           68.89 |             29.36 |      -0.111 |         nan |       nan |        9.02 |       -13.46 |          2.49 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           29 | ARR      | ARMOUR Residential REIT, Inc.                          | US       |                2.05 |                  53.37 |                    60.43 |                 62.63 |              55.31 |                70.85 |                   29.15 |           87.15 |             41.31 |     nan     |         nan |       nan |      nan    |         5.69 |          3.79 |        2.97 |                 nan |              nan |                   8 |                  0.42 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | HRTG     | Heritage Insurance Holdings, Inc.                    | US       |                0.86 |                     0.05 |    -0.05 |      0.26 |                  82.57 |                        69.01 |         71.38 |         71.18 |          61.92 |        57.42 |           63.26 |             55.2  |         5.97 |
|               2 | AMZN     | Amazon.com, Inc.                                     | US       |             2506.8  |                     0.06 |    -0.02 |      0.07 |                  74.53 |                        68.99 |         64.11 |         58.72 |          63.07 |        62.87 |           80.87 |             63.9  |         5.77 |
|               3 | HMC      | Honda Motor Company, Ltd.                            | OTHER    |               34.99 |                     0.02 |     0.01 |      0.08 |                  46.56 |                        67.52 |         66.76 |         64.69 |          60.76 |        65.97 |           80.87 |             73.24 |         3.78 |
|               4 | CLW      | Clearwater Paper Corporation                         | US       |                0.31 |                     0.05 |    -0.03 |      0.43 |                  77.38 |                        65.53 |         68.85 |         64.26 |          52.54 |        52.78 |           51.21 |             61.74 |         6.89 |
|               5 | PEO      | Adams Natural Resources Fund, Inc.                   | US       |                0.65 |                     0.03 |     0.02 |      0.05 |                  48.6  |                        65.38 |         66.14 |         61.13 |          61.15 |        55.52 |           63.36 |             82.33 |         2.06 |
|               6 | DSX      | Diana Shipping Inc.                                  | OTHER    |                0.27 |                     0.05 |    -0.03 |      0.16 |                  75.21 |                        65.23 |         63.93 |         50.85 |          59.96 |        68.46 |           66.72 |             57.55 |         4.56 |
|               7 | AVGO     | Broadcom Inc.                                        | US       |             1731.99 |                     0.03 |    -0.01 |      0.11 |                  57.08 |                        63.81 |         59.71 |         55.48 |          62.08 |        62.48 |           78.23 |             64.98 |         6.21 |
|               8 | WKC      | World Kinect Corporation                             | US       |                1.64 |                     0.08 |    -0.01 |      0    |                  56.74 |                        63.5  |         57.01 |         68.56 |          66.88 |        59.07 |           49.73 |             71.71 |         4.88 |
|               9 | LNC      | Lincoln National Corporation                         | US       |                7.41 |                     0.05 |    -0.04 |      0.07 |                  79    |                        63.38 |         65.14 |         66.7  |          58.02 |        56.85 |           45.77 |             60.18 |         4.62 |
|              10 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.86 |                     0.03 |     0.01 |      0.11 |                  49.9  |                        62.63 |         58.18 |         37.5  |          52.5  |        66.97 |           89.41 |             54.48 |         6.12 |
|              11 | V        | Visa Inc.                                            | US       |              583.13 |                     0.03 |    -0.03 |     -0.01 |                  60.34 |                        61.65 |         52.52 |         58.32 |          55.09 |        50.64 |           68.72 |             64.67 |         2.8  |
|              12 | MA       | Mastercard Incorporated                              | US       |              425.56 |                     0.03 |    -0.02 |      0.02 |                  60.75 |                        61.28 |         56.67 |         57.04 |          52.57 |        50.2  |           72.5  |             60.99 |         3.13 |
|              13 | KELYA    | Kelly Services, Inc.                                 | US       |                0.47 |                     0.03 |    -0    |      0.01 |                  58.53 |                        59.02 |         61.87 |         73.18 |          59.96 |        50.89 |           19.82 |             64.58 |         6.32 |
|              14 | AMD      | Advanced Micro Devices, Inc.                         | US       |              699.15 |                     0.12 |    -0    |     -0.03 |                  33.62 |                        57.89 |         43.21 |         58.63 |          70.23 |        61    |           64.84 |             70.46 |         7.31 |
|              15 | GSL      | Global Ship Lease Inc New                            | OTHER    |                1.32 |                     0.05 |    -0.02 |      0.01 |                  73.93 |                        57.85 |         54.38 |         54.04 |          62.66 |        70.28 |           68.61 |             38.97 |         3.73 |
|              16 | GOOGL    | Alphabet Inc.                                        | US       |             3655.94 |                     0.09 |    -0.03 |     -0.03 |                  62    |                        57.63 |         42.43 |         43.55 |          59.08 |        58.87 |           79.65 |             70.81 |         4.88 |
|              17 | LYFT     | Lyft, Inc.                                           | US       |                5.41 |                     0.06 |     0.01 |      0.03 |                  64.75 |                        57.33 |         58.5  |         56.36 |          53.67 |        56.67 |           52.12 |             52.93 |         7.98 |
|              18 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.01 |     -0.03 |                  68.2  |                        57.02 |         42.51 |         46.64 |          55.06 |        64.77 |           84.32 |             44.04 |         4.15 |
|              19 | VOR      | Vor Biopharma Inc.                                   | US       |                1.18 |                     0.06 |    -0.06 |      0.28 |                  83.88 |                        56.67 |         54.98 |         59.15 |          47.59 |        40.72 |           36.43 |             48.18 |         9.09 |
|              20 | STNG     | Scorpio Tankers Inc.                                 | OTHER    |                3.38 |                     0.03 |     0.02 |     -0    |                  47.9  |                        55.91 |         50.52 |         45.93 |          61.77 |        69.85 |           87.57 |             39.66 |         4.81 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4722.65 |             66.11 |         68.85 |         59.72 |          64.54 |        67.69 |           92.27 |             62.11 |             39.44 |         5.61 |             89.56 | short              |                0.58 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.84 |             61.04 |         60.45 |         61.62 |          59.46 |        65.22 |           51.35 |             50.14 |             86.82 |         8.43 |             85.47 | long               |               -2.15 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               35.27 |             51.35 |         50.8  |         48.27 |          51.91 |        55.91 |           57.61 |             53    |             63.82 |         8.5  |             83.53 | long               |               -2.38 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             41.13 |         52.76 |         39.71 |          36.83 |        42.55 |           30.87 |             28.72 |             62.41 |         4.46 |             74.95 | short              |                0.44 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.12 |             39.95 |         24.09 |         34.38 |          45.53 |        61.27 |           61.38 |             49.39 |             91.54 |         8.5  |             82.99 | long               |               -2.05 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.94 |             38.53 |         29.68 |         34.73 |          42.33 |        53.37 |           49.21 |             48.54 |             77.5  |         6.26 |             78.58 | long               |               -1.77 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.32 |             38.07 |         31.31 |         34.81 |          41.33 |        54.73 |           50.18 |             42.06 |             86.67 |         8.5  |             78.43 | long               |               -1.89 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.64 |             36.89 |         33.99 |         29.43 |          39.79 |        56.41 |           66.89 |             24.22 |             76.67 |         4.9  |             81.52 | long               |               -1.65 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.41 |             28.33 |         30.85 |         25.04 |          26.36 |        30.3  |           24.32 |             36.52 |             38.96 |         6.94 |             73.61 | short              |               -0.96 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.96
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.94
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.90

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
- Excluded by hard/data filters: **888**
- Event watch (otherwise eligible): **9**
- Final eligible: **103**
- Eligible change vs previous stored run: **-1**

Top exclusion categories:
- market_cap: 867
- liquidity: 203
- price: 122
- data_confidence: 52
- price_history: 23
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 2 |  | 2 | 2 | main,value,quality_value |
| TNK | 2 | 1 |  | 1 | 2 | main,value,quality_value |
| PKX | 43 | 4 | 10 | 3 | 2 | value,pullback,quality_value |
| AMCX | 4 | 3 |  | 12 | 2 | main,value |
| HRTG | 8 | 60 | 1 | 49 | 2 | main,pullback |
| AVGO | 24 | 10 | 7 | 11 | 2 | value,pullback |
| GSL | 28 | 6 | 15 | 8 | 1 | value,quality_value |
| MAGN | 54 | 5 | 22 | 4 | 1 | value,quality_value |
| IRS | 61 | 7 | 18 | 5 | 1 | value,quality_value |
| NWL.MI | 64 | 8 |  | 7 | 1 | value,quality_value |
| INVA | 79 | 9 | 28 | 6 | 1 | value,quality_value |
| RMAX | 3 | 23 |  | 24 | 1 | main |
| SU.PA | 5 | 21 |  | 15 | 1 | main |
| TWN | 6 |  |  |  | 1 | main |
| LLY | 7 | 57 |  | 34 | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)
