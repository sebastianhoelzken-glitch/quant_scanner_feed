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

- **EUROPE:** 79.6/100
- **OTHER:** 70.6/100
- **US:** 81.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |             74.04 |         73.59 |         74.5  |          77.64 |        72.39 |           73.91 |             71.66 |             60.14 |         6.79 |             85.65 | medium             |               -0.49 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |             71.85 |         74.53 |         65.02 |          70.21 |        73.49 |           70.94 |             64.91 |             76.7  |         5.08 |             84.89 | short              |               -0.47 |                   nan |                  nan |
|      3 | SM       | SM Energy Company                                      | US       |                6.68 |             68.18 |         68.48 |         61.8  |          67.89 |        71.42 |           79.13 |             51.78 |             74.29 |         6.71 |             87.81 | long               |               -0.52 |                   nan |                  nan |
|      4 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |             67.65 |         65.9  |         54.96 |          69.4  |        80.89 |           91.54 |             64.5  |             77.54 |         6.57 |             82.86 | long               |              nan    |                   nan |                  nan |
|      5 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.15 |             67.49 |         77.72 |         69.8  |          65.18 |        63.76 |           68.84 |             72.05 |             49.15 |         4.62 |             89.69 | short              |               -0.12 |                   nan |                  nan |
|      6 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              606.19 |             67.34 |         58.32 |         65.76 |          74.09 |        68.92 |           86.3  |             75.21 |             25.85 |         5.99 |             89.58 | medium             |                3.4  |                   nan |                  nan |
|      7 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.2  |             66.56 |         68.71 |         64.86 |          61.6  |        68.25 |           86.34 |             72.62 |             56.83 |         3.83 |             78.07 | short              |               -0.15 |                   nan |                  nan |
|      8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |             66.43 |         67.25 |         69.65 |          65.61 |        61.78 |           42.97 |             70.1  |             82.89 |         7.6  |             85.14 | swing              |               -0.25 |                   nan |                  nan |
|      9 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.59 |             65.98 |         73.75 |         68.45 |          63.51 |        59.8  |           61.68 |             54.41 |             57.4  |         7.34 |             75.57 | short              |                0.52 |                   nan |                  nan |
|     10 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.48 |             65.41 |         66.61 |         64.21 |          70.27 |        59.57 |           73.08 |             79.52 |             17.04 |         6.23 |             61.74 | medium             |               -1.49 |                   nan |                  nan |
|     11 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.06 |         76.62 |         69.61 |          60.51 |        56.01 |           59.63 |             55.01 |             41.75 |         5.98 |             79.32 | short              |                0.14 |                   nan |                  nan |
|     12 | LLY      | Eli Lilly and Company                                  | US       |              942.65 |             64.74 |         65.57 |         63.91 |          65.56 |        62.58 |           84.42 |             59.6  |             23.54 |         4.18 |             89.62 | short              |               -2.47 |                   nan |                  nan |
|     13 | AMZN     | Amazon.com, Inc.                                       | US       |             2497.43 |             63.86 |         63.75 |         59.35 |          63.97 |        64.02 |           81.16 |             62.93 |             41.83 |         5.73 |             89.85 | long               |               -0.26 |                   nan |                  nan |
|     14 | KELYA    | Kelly Services, Inc.                                   | US       |                0.46 |             63.47 |         67.89 |         75.1  |          59.06 |        48.72 |           19.26 |             64.6  |             65.52 |         6.32 |             85.62 | swing              |               -0.28 |                   nan |                  nan |
|     15 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |             63.36 |         67.69 |         64.81 |          61.91 |        59.72 |           67.19 |             79.77 |             37.98 |         2.9  |             64.78 | short              |               -1.08 |                   nan |                  nan |
|     16 | SAP.DE   | SAP SE                                                 | EUROPE   |              205.15 |             63.29 |         77.17 |         61.22 |          56.66 |        65.35 |           73.48 |             51.33 |             72.95 |         6.49 |             89.13 | short              |                5.14 |                   nan |                  nan |
|     17 | PEO      | Adams Natural Resources Fund, Inc.                     | US       |                0.67 |             62.9  |         72.08 |         64.8  |          60.99 |        53.94 |           62.54 |             79.52 |             19.26 |         2.02 |             68.24 | short              |               -1.08 |                   nan |                  nan |
|     18 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.89 |             62.71 |         68.33 |         66.51 |          58.91 |        50.82 |           48.9  |             79.77 |             29.89 |         2.14 |             62.78 | short              |               -1    |                   nan |                  nan |
|     19 | WKC      | World Kinect Corporation                               | US       |                1.64 |             62.67 |         56.57 |         70.24 |          67.08 |        58.26 |           46.33 |             71.54 |             53.57 |         4.87 |             84.31 | swing              |               -0.81 |                   nan |                  nan |
|     20 | KYN      | Kayne Anderson Energy Infrastructure Fund, Inc.        | US       |                2.16 |             62.07 |         67.09 |         62.5  |          61.65 |        59.21 |           53.67 |             79.77 |             54.7  |         1.82 |             67.28 | short              |               -1.31 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |                  66.36 |                    70.9  |                 74.2  |              68.36 |                78.5  |                   21.5  |           91.54 |             64.5  |       0.171 |         nan |       nan |        4.33 |         2.93 |          5.47 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | SAP.DE   | SAP SE                                                 | EUROPE   |              205.15 |                  73.38 |                    70.89 |                 69.28 |              70.19 |                67.92 |                   32.08 |           73.48 |             51.33 |       0.044 |         nan |       nan |       17.17 |        21.24 |         26.57 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|            3 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |                  73.69 |                    70.34 |                 70.88 |              71.85 |                68.34 |                   31.66 |           70.94 |             64.91 |       0.08  |         nan |       nan |        3.2  |         8.87 |          4.77 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            4 | SM       | SM Energy Company                                      | US       |                6.68 |                  72.05 |                    70.14 |                 69.79 |              68.83 |                65.42 |                   34.58 |           79.13 |             51.78 |       0.191 |         nan |       nan |        4.53 |         4.44 |          5.77 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.1  |              72.5  |                67.85 |                   32.15 |           60    |             71.38 |       0.519 |         nan |       nan |        6.42 |         7.64 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            6 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |                  67.07 |                    68.09 |                 69.61 |              67.7  |                68.02 |                   31.98 |           73.91 |             71.66 |       0.021 |         nan |       nan |        3.81 |         5.88 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  69.21 |                    67.94 |                 69.37 |              66.83 |                70.17 |                   29.83 |           84.58 |             43.72 |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  73.8  |                    67.65 |                 65.16 |              72.98 |                71.31 |                   28.69 |           42.97 |             70.1  |       2.071 |         nan |       nan |        6.98 |         4.25 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            9 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.46 |                    67.08 |                 67.6  |              70.08 |                61.31 |                   38.69 |           56.9  |             83.15 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.32 |                 67.43 |              67.37 |                70.53 |                   29.47 |           70.78 |             57    |       0.969 |         nan |       nan |        5.3  |      -121.42 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | AVGO     | Broadcom Inc.                                          | US       |             1714.69 |                  57.41 |                    66.2  |                 66.76 |              61.8  |                77.79 |                   22.21 |           78.23 |             64.68 |       0.014 |         nan |       nan |       48.11 |        21.3  |         69.46 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           12 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |                  60.8  |                    65.85 |                 67.19 |              65.03 |                73.77 |                   26.23 |           67.19 |             79.77 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           13 | UNIT     | Uniti Group Inc.                                       | US       |                2    |                  73.45 |                    64.87 |                 62.93 |              65.52 |                53.4  |                   46.6  |           69.33 |             30.21 |      -0.112 |         nan |       nan |        9.02 |       -13.39 |          2.41 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           14 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.77 |                  59.32 |                    64.51 |                 65.98 |              58.22 |                62.9  |                   37.1  |           94.29 |             41.87 |     nan     |         nan |       nan |        7.28 |        10.28 |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           15 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.96 |                  61.35 |                    63.91 |                 66.76 |              61.12 |                64.19 |                   35.81 |           85.75 |             53.92 |     nan     |         nan |       nan |        3.7  |         9.9  |         28.69 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           16 | FVRR     | Fiverr International Ltd.                              | OTHER    |                0.27 |                  76.82 |                    63.71 |                 59.92 |              66.26 |                49.61 |                   50.39 |           59.52 |             20.2  |       0.27  |         nan |       nan |        1.25 |         6.61 |         10.69 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           17 | KYN      | Kayne Anderson Energy Infrastructure Fund, Inc.        | US       |                2.16 |                  62.69 |                    63.24 |                 63.16 |              64.59 |                63.78 |                   36.22 |           53.67 |             79.77 |       0.006 |         nan |       nan |      nan    |         5.12 |          5.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           18 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  59.59 |                    62.26 |                 63.94 |              60.34 |                75.77 |                   24.23 |           80.26 |             37.97 |       0.073 |         nan |       nan |        6.43 |         9.42 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|          nan | UTG      | Reaves Utility Income Fund                             | US       |                3.17 |                  58.13 |                    62.22 |                 63.71 |              61.25 |                63.59 |                   36.41 |           64.33 |             79.52 |       0.003 |         nan |       nan |      nan    |       nan    |          2.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           19 | BYD      | Boyd Gaming Corporation                                | US       |                5.22 |                  61.98 |                    62.18 |                 61.62 |              58.92 |                59.21 |                   40.79 |           77.54 |             36.42 |       0.047 |         nan |       nan |        7.64 |        10.69 |          3.68 |        3.03 |                 nan |              nan |                  11 |                  0.58 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |                  66.36 |                    70.9  |                 74.2  |              68.36 |                78.5  |                   21.5  |           91.54 |             64.5  |       0.171 |         nan |       nan |        4.33 |         2.93 |          5.47 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |                  73.69 |                    70.34 |                 70.88 |              71.85 |                68.34 |                   31.66 |           70.94 |             64.91 |       0.08  |         nan |       nan |        3.2  |         8.87 |          4.77 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            4 | SM       | SM Energy Company                                      | US       |                6.68 |                  72.05 |                    70.14 |                 69.79 |              68.83 |                65.42 |                   34.58 |           79.13 |             51.78 |       0.191 |         nan |       nan |        4.53 |         4.44 |          5.77 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            6 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |                  67.07 |                    68.09 |                 69.61 |              67.7  |                68.02 |                   31.98 |           73.91 |             71.66 |       0.021 |         nan |       nan |        3.81 |         5.88 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  69.21 |                    67.94 |                 69.37 |              66.83 |                70.17 |                   29.83 |           84.58 |             43.72 |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            2 | SAP.DE   | SAP SE                                                 | EUROPE   |              205.15 |                  73.38 |                    70.89 |                 69.28 |              70.19 |                67.92 |                   32.08 |           73.48 |             51.33 |       0.044 |         nan |       nan |       17.17 |        21.24 |         26.57 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.1  |              72.5  |                67.85 |                   32.15 |           60    |             71.38 |       0.519 |         nan |       nan |        6.42 |         7.64 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            9 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.46 |                    67.08 |                 67.6  |              70.08 |                61.31 |                   38.69 |           56.9  |             83.15 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.32 |                 67.43 |              67.37 |                70.53 |                   29.47 |           70.78 |             57    |       0.969 |         nan |       nan |        5.3  |      -121.42 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |                  60.8  |                    65.85 |                 67.19 |              65.03 |                73.77 |                   26.23 |           67.19 |             79.77 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           20 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.2  |                  49.84 |                    62.1  |                 67.09 |              57.77 |                81.24 |                   18.76 |           86.34 |             72.62 |     nan     |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   7 |                  0.37 |
|           15 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.96 |                  61.35 |                    63.91 |                 66.76 |              61.12 |                64.19 |                   35.81 |           85.75 |             53.92 |     nan     |         nan |       nan |        3.7  |         9.9  |         28.69 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                                          | US       |             1714.69 |                  57.41 |                    66.2  |                 66.76 |              61.8  |                77.79 |                   22.21 |           78.23 |             64.68 |       0.014 |         nan |       nan |       48.11 |        21.3  |         69.46 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           14 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.77 |                  59.32 |                    64.51 |                 65.98 |              58.22 |                62.9  |                   37.1  |           94.29 |             41.87 |     nan     |         nan |       nan |        7.28 |        10.28 |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|            8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  73.8  |                    67.65 |                 65.16 |              72.98 |                71.31 |                   28.69 |           42.97 |             70.1  |       2.071 |         nan |       nan |        6.98 |         4.25 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           18 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  59.59 |                    62.26 |                 63.94 |              60.34 |                75.77 |                   24.23 |           80.26 |             37.97 |       0.073 |         nan |       nan |        6.43 |         9.42 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|          nan | UTG      | Reaves Utility Income Fund                             | US       |                3.17 |                  58.13 |                    62.22 |                 63.71 |              61.25 |                63.59 |                   36.41 |           64.33 |             79.52 |       0.003 |         nan |       nan |      nan    |       nan    |          2.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           17 | KYN      | Kayne Anderson Energy Infrastructure Fund, Inc.        | US       |                2.16 |                  62.69 |                    63.24 |                 63.16 |              64.59 |                63.78 |                   36.22 |           53.67 |             79.77 |       0.006 |         nan |       nan |      nan    |         5.12 |          5.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           13 | UNIT     | Uniti Group Inc.                                       | US       |                2    |                  73.45 |                    64.87 |                 62.93 |              65.52 |                53.4  |                   46.6  |           69.33 |             30.21 |      -0.112 |         nan |       nan |        9.02 |       -13.39 |          2.41 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           25 | STNG     | Scorpio Tankers Inc.                                   | OTHER    |                3.3  |                  55.02 |                    60.98 |                 62.72 |              56.05 |                69.16 |                   30.84 |           86.41 |             39.91 |       0.071 |         nan |       nan |        3.37 |        13.14 |          4.62 |        2.46 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                     | US       |             2497.43 |                     0.06 |    -0.02 |      0.05 |                  74.14 |                        68.67 |         63.75 |         59.35 |          63.97 |        64.02 |           81.16 |             62.93 |         5.73 |
|               2 | ALL      | The Allstate Corporation                             | US       |               56.04 |                     0.07 |    -0.03 |      0.07 |                  71.17 |                        66.02 |         59.83 |         64.76 |          61.85 |        55.59 |           68.32 |             62    |         3.05 |
|               3 | CLW      | Clearwater Paper Corporation                         | US       |                0.31 |                     0.05 |    -0.03 |      0.43 |                  77.38 |                        65.28 |         69.18 |         64.14 |          51.96 |        51.63 |           49.66 |             61.02 |         6.87 |
|               4 | SLDE     | Slide Insurance Holdings, Inc.                       | US       |                2.12 |                     0.05 |     0.01 |      0.06 |                  66.69 |                        65.21 |         63.76 |         61.18 |          61.18 |        60.84 |           76.03 |             54.19 |         5.82 |
|               5 | WKC      | World Kinect Corporation                             | US       |                1.64 |                     0.08 |    -0.04 |      0    |                  65.5  |                        64.94 |         56.57 |         70.24 |          67.08 |        58.26 |           46.33 |             71.54 |         4.87 |
|               6 | MSFT     | Microsoft Corporation                                | US       |             3167.57 |                     0.03 |     0.01 |      0.24 |                  50.49 |                        63.9  |         72.93 |         63.1  |          53.24 |        51.99 |           54.76 |             59.41 |         5.74 |
|               7 | AMCX     | AMC Global Media Inc.                                | US       |                0.42 |                     0.02 |    -0.02 |      0.11 |                  57.98 |                        62.63 |         67.25 |         69.65 |          65.61 |        61.78 |           42.97 |             70.1  |         7.6  |
|               8 | LNC      | Lincoln National Corporation                         | US       |                7.31 |                     0.06 |    -0.06 |      0.08 |                  84.16 |                        62.46 |         63.49 |         64.19 |          56.56 |        56.62 |           44.18 |             59.38 |         4.71 |
|               9 | DSX      | Diana Shipping Inc.                                  | OTHER    |                0.26 |                     0.07 |    -0.07 |      0.13 |                  83.06 |                        62.43 |         58.7  |         46.2  |          54.68 |        59.4  |           60.31 |             57.12 |         4.61 |
|              10 | AVGO     | Broadcom Inc.                                        | US       |             1714.69 |                     0.03 |    -0.01 |      0.06 |                  55.29 |                        62.35 |         57.42 |         53.23 |          61.35 |        61.58 |           78.23 |             64.68 |         6.18 |
|              11 | MA       | Mastercard Incorporated                              | US       |              424.76 |                     0.03 |    -0.02 |      0.05 |                  61.17 |                        61.51 |         57.95 |         55.81 |          51.26 |        48.99 |           71.6  |             60.3  |         3.18 |
|              12 | V        | Visa Inc.                                            | US       |              581.31 |                     0.03 |    -0.02 |      0.01 |                  60.82 |                        61.11 |         54.02 |         57.43 |          54.06 |        49.61 |           68.4  |             63.93 |         2.88 |
|              13 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.61 |                     0.07 |     0    |     -0.03 |                  60.61 |                        60.65 |         45.96 |         57.99 |          65.79 |        62.19 |           64.49 |             64.46 |         5.09 |
|              14 | KELYA    | Kelly Services, Inc.                                 | US       |                0.46 |                     0.04 |     0.01 |      0.08 |                  59.78 |                        60.06 |         67.89 |         75.1  |          59.06 |        48.72 |           19.26 |             64.6  |         6.32 |
|              15 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0.01 |                  47.53 |                        58.41 |         52.41 |         56.18 |          57.87 |        57.17 |           56.28 |             79.52 |         1.88 |
|              16 | GOOGL    | Alphabet Inc.                                        | US       |             3639.61 |                     0.09 |    -0.05 |     -0.07 |                  64.17 |                        57.97 |         40.94 |         42.89 |          59.01 |        59.14 |           81.74 |             70.33 |         4.91 |
|              17 | LYFT     | Lyft, Inc.                                           | US       |                5.44 |                     0.05 |     0.01 |      0.02 |                  68.9  |                        57.11 |         56.69 |         52.18 |          51.05 |        56.16 |           52.48 |             52.88 |         7.98 |
|              18 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.02 |     -0.05 |                  73.03 |                        56.33 |         39.6  |         43.81 |          53.55 |        63.67 |           84.58 |             43.72 |         4.17 |
|              19 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                     0.11 |    -0.08 |     -0.08 |                  58.81 |                        55.73 |         39.14 |         48.41 |          54.53 |        63.27 |           60    |             71.38 |         6.58 |
|              20 | NFLX     | Netflix, Inc.                                        | US       |              267.68 |                     0.03 |     0    |      0.01 |                  53.62 |                        55.47 |         49.96 |         34.6  |          42.78 |        51.84 |           75    |             49.64 |         5.79 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4701.84 |             64.47 |         65.43 |         57.72 |          63.5  |        66.7  |           92.75 |             60.81 |             39    |         5.55 |             89.54 | long               |               -1.07 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.11 |             40.85 |         25.53 |         33.88 |          47.82 |        64.26 |           77.48 |             48.82 |             78.83 |         8.5  |             82.99 | long               |               -1.15 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.65 |             38.91 |         36.22 |         31.38 |          41.6  |        58.62 |           72    |             25.03 |             75.22 |         4.98 |             81.52 | long               |                0.37 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             38.91 |         29.54 |         35.1  |          42.72 |        54.14 |           50.26 |             47.6  |             77.74 |         6.27 |             78.58 | long               |               -1.39 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.33 |             38.67 |         31.42 |         35.95 |          41.4  |        54.21 |           47.64 |             41.85 |             85.58 |         8.5  |             78.43 | long               |               -1.29 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.92 |             37.55 |         38.13 |         22.27 |          36.98 |        47.63 |           64.09 |             19.57 |             42.67 |         9.09 |             77.55 | long               |               -1.25 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.47 |         44.24 |         23.94 |          29.57 |        37.37 |           38.42 |             38.21 |             48.67 |         7.15 |             75.4  | short              |               -0.44 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             27.57 |         57.23 |         23.66 |          22.82 |        31.47 |           21.62 |             27.3  |             59.43 |         7.77 |             75.24 | short              |               -0.42 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.6  |             26.29 |         32.48 |         23.71 |          24.76 |        27.83 |           25.61 |             36.97 |             32.3  |         7.04 |             73.61 | short              |               -2.99 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.96
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
- Excluded by hard/data filters: **887**
- Event watch (otherwise eligible): **9**
- Final eligible: **104**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- market_cap: 862
- liquidity: 217
- price: 149
- data_confidence: 46
- price_history: 19
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AMCX | 8 | 8 | 7 | 15 | 3 | main,value,pullback |
| PARR | 1 | 6 |  | 4 | 2 | main,value,quality_value |
| TNK | 2 | 3 |  | 2 | 2 | main,value,quality_value |
| SM | 3 | 4 |  | 3 | 2 | main,value,quality_value |
| IRWD | 4 | 1 |  | 1 | 2 | main,value,quality_value |
| SAP.DE | 16 | 2 |  | 6 | 1 | value,quality_value |
| IHS | 32 | 9 |  | 8 | 1 | value,quality_value |
| MAGN | 53 | 5 | 19 | 7 | 1 | value,quality_value |
| NWL.MI | 59 | 10 |  | 9 | 1 | value,quality_value |
| IRS | 64 | 7 | 18 | 5 | 1 | value,quality_value |
| SU.PA | 5 | 28 |  | 23 | 1 | main |
| ASML.AS | 6 | 60 |  | 33 | 1 | main |
| HMC | 7 | 20 |  | 11 | 1 | main |
| RMAX | 9 | 23 |  | 24 | 1 | main |
| TWN | 10 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)
