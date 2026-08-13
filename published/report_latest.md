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

- **EUROPE:** 82.4/100
- **OTHER:** 70.8/100
- **US:** 82.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.43 |             75.55 |         74.89 |         76.21 |          78.42 |        72.87 |           73.91 |             71.88 |             60.14 |         6.84 |             85.65 | medium             |                1.02 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |             71.09 |         78.46 |         68.7  |          70.2  |        71.99 |           70.94 |             65.12 |             70.45 |         5.14 |             84.89 | short              |               -1.23 |                   nan |                  nan |
|      3 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |             68.97 |         72.64 |         71.66 |          66.29 |        62.14 |           42.97 |             70.08 |             82.89 |         7.61 |             85.14 | short              |                2.29 |                   nan |                  nan |
|      4 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.49 |             68.08 |         70.74 |         65.54 |          70.63 |        59.96 |           73.08 |             80.01 |             17.04 |         6.32 |             61.74 | short              |                1.18 |                   nan |                  nan |
|      5 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.24 |             67.64 |         77.55 |         69.9  |          65.38 |        63.95 |           68.84 |             72.06 |             49.15 |         4.68 |             89.69 | short              |                0.02 |                   nan |                  nan |
|      6 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.59 |             67.57 |         75.29 |         70.67 |          64.48 |        60.05 |           61.68 |             54.85 |             57.4  |         7.31 |             75.57 | short              |                2.11 |                   nan |                  nan |
|      7 | SM       | SM Energy Company                                      | US       |                6.61 |             67.05 |         65.89 |         60.44 |          68.22 |        72.65 |           79.13 |             52.33 |             77.86 |         6.73 |             87.81 | long               |               -1.65 |                   nan |                  nan |
|      8 | DAC      | Danaos Corporation                                     | OTHER    |                2.24 |             66.58 |         70.13 |         65.67 |          67.49 |        65.35 |           74.57 |             54.93 |             48.48 |         3.36 |             83.35 | short              |                1    |                   nan |                  nan |
|      9 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.48 |         69.92 |         70.3  |          61.04 |        56.45 |           59.63 |             55.3  |             41.75 |         6.01 |             79.32 | swing              |                0.56 |                   nan |                  nan |
|     10 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.09 |             65.27 |         60.58 |         66.37 |          71.36 |        64.17 |           69.78 |             75.62 |             31.13 |         6.05 |             89.58 | medium             |                1.32 |                   nan |                  nan |
|     11 | WKC      | World Kinect Corporation                               | US       |                1.65 |             64.62 |         61.54 |         71.4  |          67.71 |        58.77 |           46.33 |             72.59 |             53.57 |         4.94 |             84.31 | swing              |                1.14 |                   nan |                  nan |
|     12 | HQL      | HQL                                                    | US       |                0.56 |             64.52 |         74.85 |         69.34 |          59.7  |        47.18 |           47.82 |            nan    |             24.53 |         2.32 |             59.6  | short              |               -0.03 |                   nan |                  nan |
|     13 | SLDE     | Slide Insurance Holdings, Inc.                         | US       |                2.16 |             63.94 |         63.8  |         64.5  |          64.08 |        61.95 |           76.03 |             54.22 |             40.12 |         5.77 |             80.19 | swing              |                2.12 |                   nan |                  nan |
|     14 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |             63.75 |         68.67 |         65.22 |          62.29 |        59.74 |           67.19 |             80.26 |             36.61 |         2.89 |             64.78 | short              |               -0.69 |                   nan |                  nan |
|     15 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.03 |             63.7  |         64.64 |         62.77 |          60.51 |        67.6  |           84.06 |             72.78 |             58.07 |         3.86 |             78.07 | long               |               -3.01 |                   nan |                  nan |
|     16 | CEF      | CEF                                                    | OTHER    |                7.13 |             63.63 |         73.14 |         40.09 |          54.11 |        84.54 |          nan    |            nan    |            100    |         5.29 |             55.57 | long               |               -2.1  |                   nan |                  nan |
|     17 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.9  |             63.5  |         69.21 |         67.47 |          59.54 |        51.24 |           48.9  |             80.26 |             29.89 |         2.14 |             62.78 | short              |               -0.21 |                   nan |                  nan |
|     18 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |             63.4  |         56.75 |         55.54 |          70.05 |        82.27 |           91.54 |             64.59 |             83.05 |         6.49 |             82.86 | long               |              nan    |                   nan |                  nan |
|     19 | CNC      | Centene Corporation                                    | US       |               28.52 |             63.4  |         64.14 |         62.65 |          65.77 |        60.25 |           50.47 |             57.6  |             64.79 |         5.89 |             88.46 | medium             |               -0.38 |                   nan |                  nan |
|     20 | LLY      | Eli Lilly and Company                                  | US       |              944.44 |             63.05 |         63.39 |         62.7  |          65.49 |        62.61 |           84.42 |             60.03 |             24.52 |         4.21 |             89.62 | medium             |               -4.16 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  70.16 |                    73.09 |                 76.02 |              71.22 |                79.16 |                   20.84 |           91.54 |             64.59 |       0.178 |         nan |       nan |        4.33 |         2.81 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | SM       | SM Energy Company                                      | US       |                6.61 |                  73.62 |                    71.06 |                 70.58 |              70.03 |                65.49 |                   34.51 |           79.13 |             52.33 |       0.193 |         nan |       nan |        4.53 |         4.39 |          5.69 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            3 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.14 |                 69.17 |              72.56 |                67.99 |                   32.01 |           60    |             71.72 |       0.527 |         nan |       nan |        6.42 |         7.53 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  68.9  |                    68.33 |                 69.88 |              67.17 |                73.11 |                   26.89 |           85.22 |             43.98 |     nan     |         nan |       nan |        3.93 |       161.1  |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.43 |                  67.07 |                    68.11 |                 69.64 |              67.72 |                68.01 |                   31.99 |           73.91 |             71.88 |       0.021 |         nan |       nan |        3.81 |         5.98 |          4.5  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |                  73.8  |                    67.65 |                 65.16 |              72.98 |                71.3  |                   28.7  |           42.97 |             70.08 |       2.009 |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            7 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.18 |                    67.42 |                 68.11 |              70.2  |                63.05 |                   36.95 |           58.39 |             83.18 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |                  66.86 |                    66.6  |                 67.84 |              66.95 |                68.32 |                   31.68 |           70.94 |             65.12 |       0.077 |         nan |       nan |        3.2  |         9.17 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            9 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.31 |                 67.42 |              67.35 |                70.5  |                   29.5  |           70.78 |             56.93 |       0.967 |         nan |       nan |        5.3  |      -121.71 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO     | Broadcom Inc.                                          | US       |             1746.85 |                  57.41 |                    66.18 |                 66.75 |              61.79 |                77.74 |                   22.26 |           78.23 |             64.64 |       0.013 |         nan |       nan |       48.11 |        21.71 |         70.78 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           11 | UNIT     | Uniti Group Inc.                                       | US       |                2.03 |                  73.45 |                    65.14 |                 63.2  |              65.84 |                55.08 |                   44.92 |           69.33 |             30.35 |      -0.11  |         nan |       nan |        9.02 |       -13.58 |          2.51 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           12 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.9  |                  59.32 |                    64.57 |                 66.05 |              58.28 |                63.05 |                   36.95 |           94.29 |             42.18 |     nan     |         nan |       nan |        7.28 |        10.35 |          4.42 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           13 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.31 |                  65.09 |                    64.16 |                 64.6  |              63.58 |                70.98 |                   29.02 |           75    |             39.43 |       0.085 |         nan |       nan |        3.57 |         4.75 |          4.07 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           14 | EMBC     | Embecta Corp.                                          | US       |                0.25 |                  69.81 |                    63.48 |                 62.25 |              64.74 |                54.18 |                   45.82 |           62.51 |             47.22 |       0.475 |         nan |       nan |        5.53 |         2.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           15 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.87 |                  61.48 |                    63.36 |                 66.02 |              60.8  |                61.88 |                   38.12 |           83.88 |             54.01 |     nan     |         nan |       nan |        3.7  |         9.85 |         28.39 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           16 | FVRR     | Fiverr International Ltd.                              | OTHER    |                0.27 |                  76.82 |                    63.22 |                 59.24 |              65.75 |                48.89 |                   51.11 |           59.52 |             16.33 |       0.27  |         nan |       nan |        1.25 |         6.62 |         10.7  |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           17 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.53 |                  68.06 |                    63.19 |                 63.39 |              63.85 |                46.84 |                   53.16 |           64.49 |             64.11 |       0.061 |         nan |       nan |        1.68 |         8.48 |          1.25 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           18 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  55.41 |                    62.92 |                 64.97 |              61.36 |                74.63 |                   25.37 |           67.19 |             80.26 |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           19 | MSFT     | Microsoft Corporation                                  | US       |             3186.73 |                  64.66 |                    62.63 |                 60.21 |              62.21 |                50.52 |                   49.48 |           54.76 |             65.63 |       0.004 |         nan |       nan |       19.09 |        21.04 |         27.58 |        1.61 |                 nan |              nan |                  12 |                  0.63 |
|           20 | CNC      | Centene Corporation                                    | US       |               28.52 |                  67.05 |                    61.96 |                 58.89 |              62.99 |                49.74 |                   50.26 |           50.47 |             57.6  |       0.293 |         nan |       nan |        4.84 |        12.57 |        nan    |        1.17 |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  70.16 |                    73.09 |                 76.02 |              71.22 |                79.16 |                   20.84 |           91.54 |             64.59 |       0.178 |         nan |       nan |        4.33 |         2.81 |          5.23 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | SM       | SM Energy Company                                      | US       |                6.61 |                  73.62 |                    71.06 |                 70.58 |              70.03 |                65.49 |                   34.51 |           79.13 |             52.33 |       0.193 |         nan |       nan |        4.53 |         4.39 |          5.69 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            4 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  68.9  |                    68.33 |                 69.88 |              67.17 |                73.11 |                   26.89 |           85.22 |             43.98 |     nan     |         nan |       nan |        3.93 |       161.1  |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.43 |                  67.07 |                    68.11 |                 69.64 |              67.72 |                68.01 |                   31.99 |           73.91 |             71.88 |       0.021 |         nan |       nan |        3.81 |         5.98 |          4.5  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.14 |                 69.17 |              72.56 |                67.99 |                   32.01 |           60    |             71.72 |       0.527 |         nan |       nan |        6.42 |         7.53 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            7 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.18 |                    67.42 |                 68.11 |              70.2  |                63.05 |                   36.95 |           58.39 |             83.18 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |                  66.86 |                    66.6  |                 67.84 |              66.95 |                68.32 |                   31.68 |           70.94 |             65.12 |       0.077 |         nan |       nan |        3.2  |         9.17 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            9 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.31 |                 67.42 |              67.35 |                70.5  |                   29.5  |           70.78 |             56.93 |       0.967 |         nan |       nan |        5.3  |      -121.71 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO     | Broadcom Inc.                                          | US       |             1746.85 |                  57.41 |                    66.18 |                 66.75 |              61.79 |                77.74 |                   22.26 |           78.23 |             64.64 |       0.013 |         nan |       nan |       48.11 |        21.71 |         70.78 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           12 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.9  |                  59.32 |                    64.57 |                 66.05 |              58.28 |                63.05 |                   36.95 |           94.29 |             42.18 |     nan     |         nan |       nan |        7.28 |        10.35 |          4.42 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           15 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.87 |                  61.48 |                    63.36 |                 66.02 |              60.8  |                61.88 |                   38.12 |           83.88 |             54.01 |     nan     |         nan |       nan |        3.7  |         9.85 |         28.39 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           29 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.03 |                  48.04 |                    60.51 |                 65.47 |              56.17 |                79.46 |                   20.54 |           84.06 |             72.78 |     nan     |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   7 |                  0.37 |
|            6 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |                  73.8  |                    67.65 |                 65.16 |              72.98 |                71.3  |                   28.7  |           42.97 |             70.08 |       2.009 |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           18 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  55.41 |                    62.92 |                 64.97 |              61.36 |                74.63 |                   25.37 |           67.19 |             80.26 |       0.027 |         nan |       nan |      nan    |       nan    |          3.83 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           13 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.31 |                  65.09 |                    64.16 |                 64.6  |              63.58 |                70.98 |                   29.02 |           75    |             39.43 |       0.085 |         nan |       nan |        3.57 |         4.75 |          4.07 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           31 | ORC      | Orchid Island Capital, Inc.                            | US       |                1.14 |                  54.56 |                    60.3  |                 63.61 |              55.62 |                69.06 |                   30.94 |           91.35 |             39.1  |     nan     |         nan |       nan |      nan    |         6.4  |          3.78 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           22 | INVA     | Innoviva, Inc.                                         | US       |                1.31 |                  58.49 |                    61.7  |                 63.51 |              59.59 |                75.8  |                   24.2  |           80.26 |             38.36 |       0.073 |         nan |       nan |        6.43 |         9.44 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           17 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.53 |                  68.06 |                    63.19 |                 63.39 |              63.85 |                46.84 |                   53.16 |           64.49 |             64.11 |       0.061 |         nan |       nan |        1.68 |         8.48 |          1.25 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           11 | UNIT     | Uniti Group Inc.                                       | US       |                2.03 |                  73.45 |                    65.14 |                 63.2  |              65.84 |                55.08 |                   44.92 |           69.33 |             30.35 |      -0.11  |         nan |       nan |        9.02 |       -13.58 |          2.51 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | UTG      | Reaves Utility Income Fund                             | US       |                3.17 |                  57.06 |                    61.49 |                 63.14 |              60.34 |                62.56 |                   37.44 |           64.33 |             80.01 |       0.003 |         nan |       nan |      nan    |       nan    |          2.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                 | US       |             2492.68 |                     0.06 |    -0.02 |      0.07 |                  73.86 |                        69.08 |         64.53 |         58.34 |          62.93 |        62.25 |           81.16 |             63.32 |         5.79 |
|               2 | ALL      | The Allstate Corporation                         | US       |               56.44 |                     0.06 |    -0.06 |      0.07 |                  84.17 |                        68.32 |         59.12 |         65.36 |          62.58 |        56.74 |           68.32 |             62.31 |         3.07 |
|               3 | HRTG     | Heritage Insurance Holdings, Inc.                | US       |                0.85 |                     0.06 |    -0.06 |      0.24 |                  84.33 |                        68.02 |         69.92 |         70.3  |          61.04 |        56.45 |           59.63 |             55.3  |         6.01 |
|               4 | IRWD     | Ironwood Pharmaceuticals, Inc.                   | US       |                0.59 |                     0.06 |    -0.03 |      0.07 |                  73.81 |                        67.44 |         56.75 |         55.54 |          70.05 |        82.27 |           91.54 |             64.59 |         6.49 |
|               5 | HMC      | Honda Motor Company, Ltd.                        | OTHER    |               35.03 |                     0.02 |     0.01 |      0.08 |                  44.82 |                        66.77 |         64.64 |         62.77 |          60.51 |        67.6  |           84.06 |             72.78 |         3.86 |
|               6 | WKC      | World Kinect Corporation                         | US       |                1.65 |                     0.07 |     0    |      0.01 |                  59.26 |                        64.74 |         61.54 |         71.4  |          67.71 |        58.77 |           46.33 |             72.59 |         4.94 |
|               7 | MSFT     | Microsoft Corporation                            | US       |             3186.73 |                     0.02 |    -0.01 |      0.24 |                  51.31 |                        64.37 |         71.74 |         66.09 |          55.94 |        53.34 |           54.76 |             65.63 |         5.76 |
|               8 | CLW      | Clearwater Paper Corporation                     | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.79 |                        64.36 |         67.56 |         64.66 |          52.53 |        51.33 |           46.5  |             61.11 |         6.86 |
|               9 | SLDE     | Slide Insurance Holdings, Inc.                   | US       |                2.16 |                     0.03 |     0.01 |      0.04 |                  54.85 |                        63.82 |         63.8  |         64.5  |          64.08 |        61.95 |           76.03 |             54.22 |         5.77 |
|              10 | LNC      | Lincoln National Corporation                     | US       |                7.35 |                     0.05 |    -0.05 |      0.06 |                  83.86 |                        63.49 |         63.49 |         66.23 |          57.85 |        56.64 |           44.18 |             59.76 |         4.72 |
|              11 | DSX      | Diana Shipping Inc.                              | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  55.47 |                        62.29 |         66.61 |         50.61 |          56.34 |        60.74 |           60.31 |             57.38 |         4.66 |
|              12 | YPF      | YPF Sociedad Anónima                             | OTHER    |               16.53 |                     0.08 |    -0.02 |      0    |                  64.25 |                        61.7  |         45.3  |         59.09 |          67.5  |        66.96 |           64.49 |             64.11 |         5.88 |
|              13 | MA       | Mastercard Incorporated                          | US       |              424.12 |                     0.03 |    -0.03 |      0.01 |                  64.42 |                        61.07 |         54.54 |         56.16 |          51.97 |        49.45 |           71.6  |             60.07 |         3.24 |
|              14 | PKX      | POSCO Holdings Inc.                              | OTHER    |               14.87 |                     0.02 |     0.02 |      0.11 |                  47.06 |                        60.99 |         58.1  |         36.33 |          49.77 |        62.24 |           83.88 |             54.01 |         6.13 |
|              15 | V        | Visa Inc.                                        | US       |              581.47 |                     0.03 |    -0.03 |     -0.01 |                  61.27 |                        60.3  |         50.59 |         56.96 |          53.73 |        49.5  |           68.4  |             59.67 |         2.91 |
|              16 | GSL      | Global Ship Lease Inc New                        | OTHER    |                1.31 |                     0.05 |    -0.02 |      0.01 |                  74.13 |                        59.29 |         54.51 |         53.75 |          62.48 |        69.07 |           75    |             39.43 |         3.81 |
|              17 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund | US       |                0.78 |                     0.03 |     0    |     -0.01 |                  53.88 |                        59.07 |         48.9  |         55.45 |          57.86 |        57.48 |           56.28 |             80.01 |         1.89 |
|              18 | GOOGL    | Alphabet Inc.                                    | US       |             3660.93 |                     0.08 |    -0.03 |     -0.02 |                  62.7  |                        58.61 |         44.61 |         44.11 |          59.81 |        59.34 |           81.74 |             70.34 |         4.92 |
|              19 | KELYA    | Kelly Services, Inc.                             | US       |                0.47 |                     0.03 |     0    |      0.02 |                  53.11 |                        58.35 |         61.59 |         73.63 |          59.38 |        48.5  |           19.26 |             64.76 |         6.36 |
|              20 | AMD      | Advanced Micro Devices, Inc.                     | US       |              699.21 |                     0.11 |     0.01 |     -0.01 |                  36.64 |                        58.14 |         46.81 |         58.25 |          69.24 |        59.44 |           64.84 |             70.35 |         7.3  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4714.22 |             65.34 |         68.22 |         57.81 |          63.63 |        67.04 |           92.75 |             61.98 |             39    |         5.59 |             89.56 | short              |               -0.2  |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.87 |             61.87 |         61.52 |         62.22 |          59.25 |        65.11 |           55.86 |             49.68 |             79.92 |         8.44 |             85.47 | long               |               -1.32 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.13 |             42.88 |         27.17 |         37.14 |          48.62 |        64.39 |           77.48 |             49.27 |             78.83 |         8.5  |             82.99 | long               |                0.87 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               34.15 |             42.72 |         35.65 |         38.41 |          47.03 |        52.54 |           57.54 |             51.26 |             58.33 |         8.5  |             83.72 | long               |              -11.01 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1    |             41.12 |         51.61 |         39.94 |          36.65 |        42.29 |           28.96 |             29.25 |             63.85 |         4.55 |             74.95 | short              |                0.43 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.92 |             38.5  |         27.5  |         34.37 |          42.64 |        53.97 |           52.15 |             48    |             75.19 |         6.27 |             78.58 | long               |               -1.79 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             38.16 |         30.02 |         34.48 |          41.84 |        55.04 |           52.87 |             42.14 |             83.19 |         7.23 |             78.43 | long               |               -1.8  |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             37.3  |         38.48 |         22.5  |          36.13 |        47.13 |           64.09 |             19.75 |             42.67 |         9.1  |             77.55 | long               |               -1.5  |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.23 |         31.21 |         29.47 |          41.26 |        58.3  |           72    |             25.21 |             75.22 |         4.91 |             81.52 | long               |               -2.31 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.43 |         39.08 |         23.36 |          29.57 |        37.29 |           38.42 |             38.27 |             48.67 |         7.14 |             75.4  | short              |               -0.48 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.87 |             27.92 |         58.26 |         24.22 |          22.96 |        31.62 |           21.62 |             27.44 |             59.43 |         7.79 |             75.24 | short              |               -0.07 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.43 |             26.14 |         27.84 |         22.61 |          24.45 |        27.97 |           24.14 |             37.19 |             35.81 |         6.94 |             73.61 | long               |               -3.15 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **868**
- Event watch (otherwise eligible): **12**
- Final eligible: **120**
- Eligible change vs previous stored run: **+16**

Top exclusion categories:
- market_cap: 840
- liquidity: 219
- price: 146
- data_confidence: 43
- price_history: 21
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 5 |  | 4 | 2 | main,value,quality_value |
| TNK | 2 | 8 |  | 7 | 2 | main,value,quality_value |
| SM | 7 | 2 |  | 2 | 2 | main,value,quality_value |
| IRWD | 18 | 1 | 4 | 1 | 2 | value,pullback,quality_value |
| AMCX | 3 | 6 |  | 13 | 2 | main,value |
| HRTG | 9 | 63 | 3 | 57 | 2 | main,pullback |
| AVGO | 24 | 10 |  | 9 | 1 | value,quality_value |
| IHS | 50 | 7 |  | 6 | 1 | value,quality_value |
| MAGN | 64 | 3 |  | 5 | 1 | value,quality_value |
| NWL.MI | 69 | 9 |  | 8 | 1 | value,quality_value |
| IRS | 77 | 4 | 21 | 3 | 1 | value,quality_value |
| TWN | 4 |  |  |  | 1 | main |
| SU.PA | 5 | 30 |  | 25 | 1 | main |
| RMAX | 6 | 23 |  | 26 | 1 | main |
| DAC | 8 | 34 |  | 21 | 1 | main |

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
| 1 | IRWD | value+pullback | 75.52 | 70.16 | 73.81 | 91.54 | 64.59 | 79.16 | 63.40 |
| 2 | IRS | value+pullback | 70.23 | 68.90 | 71.02 | 85.22 | 43.98 | 73.11 | 49.40 |
| 3 | GSL | value+pullback | 67.45 | 65.09 | 74.13 | 75.00 | 39.43 | 70.98 | 58.50 |
| 4 | INVA | value+pullback | 65.28 | 58.49 | 66.78 | 80.26 | 38.36 | 75.80 | 41.79 |
| 5 | YPF | value+pullback | 61.93 | 68.06 | 64.25 | 64.49 | 64.11 | 46.84 | 63.03 |
| 6 | BHF | value+pullback | 60.93 | 68.11 | 61.66 | 51.65 | 44.05 | 64.66 | 45.50 |
| 7 | AF.PA | value+pullback | 60.76 | 67.40 | 82.00 | 39.08 | 61.67 | 40.06 | 51.93 |
| 8 | PKX | value+pullback | 60.57 | 61.48 | 47.06 | 83.88 | 54.01 | 61.88 | 53.94 |
| 9 | LNC | value+pullback | 59.82 | 56.82 | 83.86 | 44.18 | 59.76 | 46.04 | 60.67 |
| 10 | ALL-PH | value+pullback | 59.65 | 61.05 | 60.85 | 68.32 | 40.03 | 59.33 | 45.84 |
| 11 | BYD | value+pullback | 58.03 | 57.97 | 52.92 | 77.54 | 38.67 | 59.59 | 48.17 |
| 12 | MAU.PA | value+pullback | 57.50 | 61.42 | 59.57 | 58.70 | 52.66 | 50.54 | 50.78 |
| 13 | MSFT | value+pullback | 57.11 | 64.66 | 51.31 | 54.76 | 65.63 | 50.52 | 61.01 |
| 14 | MTRX | value+pullback | 56.55 | 71.83 | 52.39 | 35.27 | 59.97 | 53.07 | 45.34 |
| 15 | CHTR | value+pullback | 55.44 | 64.45 | 68.91 | 54.24 | 40.04 | 33.68 | 45.24 |
| 16 | AAPL | value+pullback | 55.03 | 62.22 | 47.38 | 58.97 | 50.67 | 53.06 | 51.29 |
| 17 | TV | value+pullback | 54.27 | 61.08 | 45.91 | 48.91 | 61.70 | 54.79 | 51.09 |
| 18 | SM | value | 52.29 | 73.62 | 59.40 | 79.13 | 52.33 | 65.49 | 67.05 |
| 19 | PARR | value | 52.00 | 67.07 | 37.98 | 73.91 | 71.88 | 68.01 | 75.55 |
| 20 | MAGN | value | 51.92 | 73.82 | 33.91 | 60.00 | 71.72 | 67.99 | 51.76 |
