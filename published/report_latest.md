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

- **EUROPE:** 89.6/100
- **OTHER:** 70.8/100
- **US:** 83.5/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.52 |             79.92 |         80.17 |         79.67 |          80.18 |        75.63 |           75.36 |             71.78 |             66.83 |         6.71 |             85.65 | medium             |                5.38 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.49 |             73.77 |         79    |         70.4  |          72.72 |        74.81 |           74.41 |             72.44 |             71.04 |         5.04 |             84.89 | short              |                1.44 |                   nan |                  nan |
|      3 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.49 |             68.58 |         70.75 |         66.42 |          71.63 |        61.11 |           73.38 |             81.18 |             19.13 |         6.25 |             61.74 | medium             |                1.68 |                   nan |                  nan |
|      4 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.84 |             68.24 |         77.64 |         69.51 |          66.83 |        66.98 |           77.61 |             71.79 |             49.92 |         4.57 |             89.69 | short              |                0.63 |                   nan |                  nan |
|      5 | SM       | SM Energy Company                                      | US       |                6.62 |             67.97 |         66.72 |         61.53 |          69.22 |        74.19 |           80.8  |             51.61 |             80.33 |         6.64 |             87.81 | long               |               -0.74 |                   nan |                  nan |
|      6 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |             67.65 |         71.34 |         70.62 |          64.69 |        59.19 |           41.23 |             69.46 |             75.73 |         7.55 |             85.14 | short              |                0.97 |                   nan |                  nan |
|      7 | DAC      | Danaos Corporation                                     | OTHER    |                2.23 |             67.56 |         67.87 |         64.28 |          67.89 |        67.25 |           77.72 |             54.63 |             53.9  |         3.23 |             84.55 | medium             |                1.98 |                   nan |                  nan |
|      8 | HQH      | Abrdn Healthcare Investors                             | US       |                1.17 |             67.05 |         75.37 |         72.15 |          61.94 |        48.19 |           43.19 |             81.18 |             18.09 |         2.09 |             61.74 | short              |                4.99 |                   nan |                  nan |
|      9 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.58 |             66.9  |         73.06 |         69.33 |          64.48 |        60.11 |           61.68 |             55    |             57.81 |         7.26 |             75.57 | short              |                1.44 |                   nan |                  nan |
|     10 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.17 |             65.37 |         60.79 |         66.5  |          71.48 |        64.25 |           71.95 |             75.46 |             29.32 |         6.01 |             89.58 | medium             |                1.43 |                   nan |                  nan |
|     11 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.07 |         69.38 |         70.09 |          60.75 |        55.82 |           58.94 |             54.71 |             39.65 |         5.85 |             79.32 | swing              |                0.14 |                   nan |                  nan |
|     12 | CNC      | Centene Corporation                                    | US       |               28.52 |             65.06 |         64.53 |         65.06 |          69.56 |        65.06 |           56.91 |             64.06 |             69.12 |         5.77 |             88.46 | medium             |                1.28 |                   nan |                  nan |
|     13 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.72 |             64.87 |         48.54 |         61.22 |          68.95 |        68.53 |           67.12 |             64.38 |             64.52 |         5.72 |             84.57 | medium             |                2.57 |                   nan |                  nan |
|     14 | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.98 |             64.84 |         66.78 |         63.95 |          65.73 |        62.92 |           77.75 |             81.18 |             29.75 |         1.84 |             63.74 | short              |                2.52 |                   nan |                  nan |
|     15 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.91 |             64.8  |         70    |         68.8  |          60.8  |        52.84 |           50.03 |             81.44 |             32.2  |         2.08 |             62.78 | short              |                1.09 |                   nan |                  nan |
|     16 | WKC      | World Kinect Corporation                               | US       |                1.65 |             64.47 |         60.81 |         71.56 |          68.13 |        59.66 |           46.4  |             71.29 |             56.33 |         4.87 |             84.31 | swing              |                0.99 |                   nan |                  nan |
|     17 | AMZN     | Amazon.com, Inc.                                       | US       |             2481.77 |             64.41 |         63.11 |         58.71 |          65.7  |        67.74 |           89.57 |             62.73 |             45.17 |         5.72 |             89.85 | long               |                0.29 |                   nan |                  nan |
|     18 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |             64.37 |         68.78 |         65.69 |          63.04 |        60.82 |           67.46 |             81.44 |             38.45 |         2.84 |             64.78 | short              |               -0.07 |                   nan |                  nan |
|     19 | HMC      | Honda Motor Co., Ltd.                                  | OTHER    |               35.01 |             64.16 |         64.23 |         64.09 |          60.66 |        65.67 |           75    |             83.4  |             59.71 |         3.71 |             80.57 | long               |               -2.55 |                   nan |                  nan |
|     20 | LLY      | Eli Lilly and Company                                  | US       |              936.08 |             64.13 |         61.11 |         62.21 |          66.97 |        66.04 |           90.07 |             59.18 |             29.25 |         4.09 |             89.62 | medium             |               -3.08 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                                    | US       |                6.62 |                  78.03 |                    73.39 |                 72.6  |              72.8  |                63.65 |                   36.35 |           80.8  |             51.61 |       0.193 |         nan |       nan |        4.53 |         4.37 |          5.69 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            2 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.49 |                  69.42 |                    71.09 |                 72.79 |              71.72 |                80.52 |                   19.48 |           74.41 |             72.44 |       0.078 |         nan |       nan |        3.2  |         9.09 |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            3 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.32 |                  78.38 |                    70.99 |                 69.97 |              72.77 |                69.12 |                   30.88 |           73.91 |             38.99 |       0.085 |         nan |       nan |        3.57 |         4.76 |          4.11 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            4 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    70.39 |                 70.55 |              70.23 |                73.17 |                   26.83 |           70.87 |            nan    |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.52 |                  71.16 |                    70.31 |                 71.58 |              70.35 |                66.34 |                   33.66 |           75.36 |             71.78 |       0.02  |         nan |       nan |        3.81 |         6.13 |          4.76 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    69.15 |                 69.18 |              72.57 |                68.03 |                   31.97 |           60    |             71.73 |       0.529 |         nan |       nan |        6.42 |         7.5  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            7 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.72 |                  74.92 |                    69.03 |                 68.64 |              70.56 |                56.57 |                   43.43 |           67.12 |             64.38 |       0.061 |         nan |       nan |        1.68 |         8.56 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            8 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  68.64 |                    68.2  |                 69.8  |              66.98 |                72.85 |                   27.15 |           85.31 |             44.39 |     nan     |         nan |       nan |        3.93 |       160.66 |          4.69 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            9 | IHS      | IHS Holding Limited                                  | OTHER    |                2.45 |                  69.61 |                    68.04 |                 69.13 |              70.31 |                65.95 |                   34.05 |           61.75 |             83.16 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | INVA     | Innoviva, Inc.                                       | US       |                1.3  |                  66.84 |                    67.4  |                 68.84 |              66.08 |                78.47 |                   21.53 |           85.02 |             38.28 |       0.073 |         nan |       nan |        6.43 |         9.41 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           11 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.87 |                  66.69 |                    66.95 |                 69.43 |              64.76 |                63.19 |                   36.81 |           87.54 |             53.69 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.49 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           12 | AVGO     | Broadcom Inc.                                        | US       |             1734.23 |                  57.41 |                    66.7  |                 67.52 |              61.95 |                78.59 |                   21.41 |           80.74 |             64.73 |       0.014 |         nan |       nan |       48.11 |        21.52 |         70.17 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           13 | CNC      | Centene Corporation                                  | US       |               28.52 |                  69.74 |                    65.8  |                 63.43 |              66.47 |                54.73 |                   45.27 |           56.91 |             64.06 |       0.293 |         nan |       nan |        4.84 |        12.56 |        nan    |        0.91 |                 nan |              nan |                  10 |                  0.53 |
|           14 | UNIT     | Uniti Group Inc.                                     | US       |                2.06 |                  73.48 |                    65.17 |                 63.23 |              65.87 |                55.17 |                   44.83 |           69.33 |             30.35 |      -0.109 |         nan |       nan |        9.02 |       -13.75 |          2.54 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           15 | DAC      | Danaos Corporation                                   | OTHER    |                2.23 |                  61.65 |                    65.03 |                 67.08 |              63.91 |                78.11 |                   21.89 |           77.72 |             54.63 |       0.002 |         nan |       nan |        3.74 |         5.77 |          4.79 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           16 | RCI      | Rogers Communications Inc.                           | OTHER    |               16.95 |                  59.32 |                    64.6  |                 66.08 |              58.31 |                63.23 |                   36.77 |           94.29 |             42.22 |     nan     |         nan |       nan |        7.28 |        10.37 |          4.36 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           17 | SU.PA    | Schneider Electric S.E.                              | EUROPE   |              173.84 |                  53.98 |                    64.44 |                 65.97 |              59.85 |                76.69 |                   23.31 |           77.61 |             71.79 |       0.031 |         nan |       nan |       22.47 |        25.62 |         36.43 |        1.83 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                    | OTHER    |                0.98 |                  52.65 |                    64.12 |                 67.48 |              60.63 |                81.16 |                   18.84 |           77.75 |             81.18 |     nan     |         nan |       nan |      nan    |       nan    |          4.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | FVRR     | Fiverr International Ltd.                            | OTHER    |                0.27 |                  76.82 |                    63.69 |                 59.89 |              66.24 |                49.63 |                   50.37 |           59.52 |             19.98 |       0.265 |         nan |       nan |        1.25 |         6.74 |         10.89 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           19 | STNG     | Scorpio Tankers Inc.                                 | OTHER    |                3.41 |                  59.05 |                    63.13 |                 63.76 |              60.13 |                76.01 |                   23.99 |           79.55 |             39.32 |       0.069 |         nan |       nan |        3.37 |        13.53 |          4.89 |        2.46 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.49 |                  69.42 |                    71.09 |                 72.79 |              71.72 |                80.52 |                   19.48 |           74.41 |             72.44 |       0.078 |         nan |       nan |        3.2  |         9.09 |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            1 | SM       | SM Energy Company                                      | US       |                6.62 |                  78.03 |                    73.39 |                 72.6  |              72.8  |                63.65 |                   36.35 |           80.8  |             51.61 |       0.193 |         nan |       nan |        4.53 |         4.37 |          5.69 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            5 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.52 |                  71.16 |                    70.31 |                 71.58 |              70.35 |                66.34 |                   33.66 |           75.36 |             71.78 |       0.02  |         nan |       nan |        3.81 |         6.13 |          4.76 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  69.5  |                    70.39 |                 70.55 |              70.23 |                73.17 |                   26.83 |           70.87 |            nan    |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | GSL      | Global Ship Lease, Inc.                                | OTHER    |                1.32 |                  78.38 |                    70.99 |                 69.97 |              72.77 |                69.12 |                   30.88 |           73.91 |             38.99 |       0.085 |         nan |       nan |        3.57 |         4.76 |          4.11 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            8 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  68.64 |                    68.2  |                 69.8  |              66.98 |                72.85 |                   27.15 |           85.31 |             44.39 |     nan     |         nan |       nan |        3.93 |       160.66 |          4.69 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           11 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.87 |                  66.69 |                    66.95 |                 69.43 |              64.76 |                63.19 |                   36.81 |           87.54 |             53.69 |     nan     |         nan |       nan |        3.7  |         9.83 |         28.49 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            6 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.15 |                 69.18 |              72.57 |                68.03 |                   31.97 |           60    |             71.73 |       0.529 |         nan |       nan |        6.42 |         7.5  |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            9 | IHS      | IHS Holding Limited                                    | OTHER    |                2.45 |                  69.61 |                    68.04 |                 69.13 |              70.31 |                65.95 |                   34.05 |           61.75 |             83.16 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  66.84 |                    67.4  |                 68.84 |              66.08 |                78.47 |                   21.53 |           85.02 |             38.28 |       0.073 |         nan |       nan |        6.43 |         9.41 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            7 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.72 |                  74.92 |                    69.03 |                 68.64 |              70.56 |                56.57 |                   43.43 |           67.12 |             64.38 |       0.061 |         nan |       nan |        1.68 |         8.56 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           12 | AVGO     | Broadcom Inc.                                          | US       |             1734.23 |                  57.41 |                    66.7  |                 67.52 |              61.95 |                78.59 |                   21.41 |           80.74 |             64.73 |       0.014 |         nan |       nan |       48.11 |        21.52 |         70.17 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.98 |                  52.65 |                    64.12 |                 67.48 |              60.63 |                81.16 |                   18.84 |           77.75 |             81.18 |     nan     |         nan |       nan |      nan    |       nan    |          4.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | DAC      | Danaos Corporation                                     | OTHER    |                2.23 |                  61.65 |                    65.03 |                 67.08 |              63.91 |                78.11 |                   21.89 |           77.72 |             54.63 |       0.002 |         nan |       nan |        3.74 |         5.77 |          4.79 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           16 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.95 |                  59.32 |                    64.6  |                 66.08 |              58.31 |                63.23 |                   36.77 |           94.29 |             42.22 |     nan     |         nan |       nan |        7.28 |        10.37 |          4.36 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           17 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.84 |                  53.98 |                    64.44 |                 65.97 |              59.85 |                76.69 |                   23.31 |           77.61 |             71.79 |       0.031 |         nan |       nan |       22.47 |        25.62 |         36.43 |        1.83 |                 nan |              nan |                  12 |                  0.63 |
|           22 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |                  55.13 |                    63    |                 65.15 |              61.35 |                75.08 |                   24.92 |           67.46 |             81.44 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           34 | HMC      | Honda Motor Co., Ltd.                                  | OTHER    |               35.01 |                  48.67 |                    60.25 |                 64.77 |              57.31 |                77.4  |                   22.6  |           75    |             83.4  |     nan     |         nan |       nan |        7.16 |         6.27 |        nan    |        3.45 |                 nan |              nan |                  10 |                  0.53 |
|          nan | GGN      | GAMCO Global Gold, Natural Resources & Income Trust    | US       |                0.72 |                  48.96 |                    60.83 |                 64.28 |              57.47 |                78.32 |                   21.68 |           73.28 |             81.18 |     nan     |         nan |       nan |      nan    |       nan    |          2.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           26 | AMZN     | Amazon.com, Inc.                                       | US       |             2481.77 |                  50.79 |                    61.67 |                 64.19 |              54.28 |                63.52 |                   36.48 |           89.57 |             62.73 |       0.001 |         nan |       nan |       17.83 |        25.56 |         21.35 |        1.48 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                 | US       |             2481.77 |                     0.07 |    -0.03 |      0.06 |                  71.7  |                        69.64 |         63.11 |         58.71 |          65.7  |        67.74 |           89.57 |             62.73 |         5.72 |
|               2 | ALL      | The Allstate Corporation                         | US       |               56.63 |                     0.06 |    -0.06 |      0.07 |                  84.75 |                        68.95 |         59.75 |         66.34 |          62.88 |        56.44 |           67.87 |             63.25 |         2.98 |
|               3 | HRTG     | Heritage Insurance Holdings, Inc.                | US       |                0.85 |                     0.07 |    -0.07 |      0.23 |                  82.33 |                        67.39 |         69.38 |         70.09 |          60.75 |        55.82 |           58.94 |             54.71 |         5.85 |
|               4 | HMC      | Honda Motor Co., Ltd.                            | OTHER    |               35.01 |                     0.02 |     0.01 |      0.08 |                  46.85 |                        66.65 |         64.23 |         64.09 |          60.66 |        65.67 |           75    |             83.4  |         3.71 |
|               5 | CLW      | Clearwater Paper Corporation                     | US       |                0.31 |                     0.06 |    -0.04 |      0.34 |                  79.41 |                        64.84 |         67.5  |         64.41 |          53.09 |        52.33 |           50.18 |             60.94 |         6.81 |
|               6 | WKC      | World Kinect Corporation                         | US       |                1.65 |                     0.07 |     0    |      0.01 |                  58.77 |                        64.57 |         60.81 |         71.56 |          68.13 |        59.66 |           46.4  |             71.29 |         4.87 |
|               7 | AVGO     | Broadcom Inc.                                    | US       |             1734.23 |                     0.02 |    -0    |      0.12 |                  47.41 |                        64.43 |         62.92 |         55.96 |          61.86 |        61.49 |           80.74 |             64.73 |         6.1  |
|               8 | LLY      | Eli Lilly and Company                            | US       |              936.08 |                     0.02 |     0.02 |      0.04 |                  42.49 |                        64.37 |         61.11 |         62.21 |          66.97 |        66.04 |           90.07 |             59.18 |         4.09 |
|               9 | SLDE     | Slide Insurance Holdings, Inc.                   | US       |                2.16 |                     0.04 |     0    |      0.04 |                  59.43 |                        64.3  |         62.64 |         64.25 |          64.06 |        61.99 |           76.22 |             53.44 |         5.73 |
|              10 | LNC      | Lincoln National Corporation                     | US       |                7.44 |                     0.05 |    -0.04 |      0.07 |                  78.91 |                        64.12 |         65.2  |         67.86 |          58.99 |        57.38 |           45.39 |             61.85 |         4.58 |
|              11 | MSFT     | Microsoft Corporation                            | US       |             3180.5  |                     0.02 |    -0.01 |      0.23 |                  54.17 |                        64.01 |         70.71 |         64.43 |          54.61 |        52.31 |           58.4  |             59.03 |         5.63 |
|              12 | YPF      | YPF Sociedad Anónima                             | OTHER    |               16.72 |                     0.07 |    -0.01 |      0.01 |                  67.23 |                        63.78 |         48.54 |         61.22 |          68.95 |        68.53 |           67.12 |             64.38 |         5.72 |
|              13 | PKX      | POSCO Holdings Inc.                              | OTHER    |               14.87 |                     0.03 |     0.01 |      0.11 |                  50.62 |                        62.07 |         57.83 |         37.4  |          51.9  |        65.65 |           87.54 |             53.69 |         6.06 |
|              14 | DSX      | Diana Shipping Inc.                              | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  57.27 |                        61.83 |         65.19 |         49.74 |          56.35 |        61.93 |           60    |             57.65 |         4.52 |
|              15 | MA       | Mastercard Incorporated                          | US       |              426.88 |                     0.03 |    -0.03 |      0.02 |                  61.08 |                        61.21 |         55.45 |         57.39 |          52.91 |        50.38 |           71.73 |             60.05 |         3.08 |
|              16 | V        | Visa Inc.                                        | US       |              584.08 |                     0.02 |    -0.02 |     -0.01 |                  59.23 |                        60.45 |         51.1  |         57.89 |          54.42 |        50.35 |           68.34 |             59.7  |         2.79 |
|              17 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund | US       |                0.78 |                     0.02 |     0    |     -0.01 |                  50.76 |                        59.87 |         50.54 |         57.13 |          59.29 |        59.13 |           57.54 |             81.18 |         1.79 |
|              18 | AMD      | Advanced Micro Devices, Inc.                     | US       |              696.26 |                     0.11 |     0.01 |     -0.02 |                  36.14 |                        58.98 |         46.29 |         59.05 |          69.8  |        59.42 |           65.04 |             73.52 |         7.25 |
|              19 | GSL      | Global Ship Lease, Inc.                          | OTHER    |                1.32 |                     0.05 |    -0.02 |      0.01 |                  73.72 |                        58.49 |         53.61 |         52.72 |          61.71 |        68.78 |           73.91 |             38.99 |         3.69 |
|              20 | GOOGL    | Alphabet Inc.                                    | US       |             3668.02 |                     0.08 |    -0.03 |     -0.02 |                  62.48 |                        58.39 |         43.99 |         43.86 |          59.51 |        58.69 |           81.86 |             70.97 |         4.81 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation           | US       |                1.91 |             65.17 |         65.59 |         64.76 |          62.65 |        69.46 |           67.03 |             49.36 |             78.15 |         8.39 |             86.67 | long               |                1.98 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4729.57 |             63.56 |         68.46 |         57.7  |          62.46 |        64.66 |           91.3  |             60.55 |             32.73 |         5.56 |             89.54 | short              |               -1.98 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.16 |             42.95 |         27.41 |         37.04 |          48.86 |        64.94 |           79.4  |             48.91 |             78.93 |         8.5  |             82.99 | long               |                0.95 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             41.87 |         53.43 |         41.4  |          37.21 |        42.34 |           28.85 |             29.33 |             62.35 |         4.38 |             74.95 | short              |                1.18 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             38.9  |         29.67 |         34.95 |          42.84 |        56.31 |           55.74 |             42.31 |             82.73 |         7.1  |             78.43 | long               |               -1.06 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             37.49 |         28.29 |         34.92 |          40.05 |        51.77 |          nan    |             48.31 |             62.12 |         6.89 |             73.1  | long               |               -2.81 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             36.5  |         36.12 |         22.14 |          36.89 |        49.12 |           64.32 |             19.94 |             50.67 |         9.07 |             77.55 | long               |               -2.3  |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.62 |             35.41 |         29.47 |         29.16 |          41.34 |        58.32 |           72    |             25.02 |             75.22 |         4.87 |             81.52 | long               |               -3.13 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.78 |         39.48 |         23.27 |          29.81 |        37.76 |           39.66 |             38.37 |             49.29 |         7.04 |             75.4  | short              |               -0.13 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.87 |             29.77 |         58.38 |         24.61 |          24.58 |        34.92 |           25.2  |             27.69 |             67    |         7.71 |             75.24 | short              |                1.78 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.41 |             26.1  |         26.91 |         22.47 |          25.29 |        29.15 |           29.19 |             37.44 |             33.44 |         6.84 |             73.61 | long               |               -3.19 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.95
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.94
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
- Event watch (otherwise eligible): **11**
- Final eligible: **115**
- Eligible change vs previous stored run: **+11**

Top exclusion categories:
- market_cap: 852
- liquidity: 206
- price: 121
- data_confidence: 55
- price_history: 21
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 5 |  | 3 | 2 | main,value,quality_value |
| TNK | 2 | 2 |  | 1 | 2 | main,value,quality_value |
| SM | 5 | 1 |  | 2 | 2 | main,value,quality_value |
| IHS | 42 | 9 |  | 9 | 1 | value,quality_value |
| GSL | 45 | 3 | 19 | 5 | 1 | value,quality_value |
| MAGN | 66 | 6 |  | 8 | 1 | value,quality_value |
| IRS | 76 | 8 | 23 | 6 | 1 | value,quality_value |
| NWL.MI | 77 | 4 |  | 4 | 1 | value,quality_value |
| INVA | 91 | 10 | 30 | 10 | 1 | value,quality_value |
| TWN | 3 |  |  |  | 1 | main |
| SU.PA | 4 | 17 |  | 15 | 1 | main |
| AMCX | 6 | 23 |  | 30 | 1 | main |
| DAC | 7 | 15 |  | 13 | 1 | main |
| HQH | 8 |  |  |  | 1 | main |
| RMAX | 9 | 28 |  | 28 | 1 | main |

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
| 1 | GSL | value+pullback | 70.75 | 78.38 | 73.72 | 73.91 | 38.99 | 69.12 | 57.66 |
| 2 | IRS | value+pullback | 69.95 | 68.64 | 70.22 | 85.31 | 44.39 | 72.85 | 49.99 |
| 3 | INVA | value+pullback | 69.76 | 66.84 | 69.74 | 85.02 | 38.28 | 78.47 | 43.42 |
| 4 | YPF | value+pullback | 67.10 | 74.92 | 67.23 | 67.12 | 64.38 | 56.57 | 64.87 |
| 5 | SUZ | value+pullback | 64.42 | 58.39 | 70.98 | 70.51 | 46.38 | 69.75 | 39.87 |
| 6 | PKX | value+pullback | 63.80 | 66.69 | 50.62 | 87.54 | 53.69 | 63.19 | 54.87 |
| 7 | AVGO | value+pullback | 63.38 | 57.41 | 47.41 | 80.74 | 64.73 | 78.59 | 61.68 |
| 8 | CLW | value+pullback | 61.87 | 56.94 | 79.41 | 50.18 | 60.94 | 56.56 | 58.75 |
| 9 | BHF | value+pullback | 61.61 | 69.98 | 62.34 | 51.73 | 43.35 | 64.66 | 46.23 |
| 10 | ALL-PH | value+pullback | 61.19 | 61.37 | 65.90 | 67.87 | 42.48 | 59.36 | 45.48 |
| 11 | LNC | value+pullback | 58.90 | 56.34 | 78.91 | 45.39 | 61.85 | 46.41 | 62.10 |
| 12 | MTRX | value+pullback | 57.80 | 74.80 | 51.81 | 39.59 | 59.50 | 52.60 | 46.58 |
| 13 | MSFT | value+pullback | 57.70 | 64.66 | 54.17 | 58.40 | 59.03 | 50.50 | 59.52 |
| 14 | TNK | value | 55.34 | 69.42 | 30.95 | 74.41 | 72.44 | 80.52 | 73.77 |
| 15 | AAPL | value+pullback | 55.13 | 60.39 | 46.77 | 62.85 | 50.49 | 54.22 | 51.06 |
| 16 | TV | value+pullback | 54.85 | 61.08 | 48.45 | 48.91 | 61.20 | 54.82 | 50.56 |
| 17 | SM | value | 53.42 | 78.03 | 57.00 | 80.80 | 51.61 | 63.65 | 67.97 |
| 18 | PARR | value | 53.10 | 71.16 | 63.93 | 75.36 | 71.78 | 66.34 | 79.92 |
| 19 | KELYA | value+pullback | 52.80 | 71.06 | 50.26 | 20.27 | 64.06 | 47.37 | 61.41 |
| 20 | MAGN | value | 51.92 | 73.82 | 33.18 | 60.00 | 71.73 | 68.03 | 51.91 |
