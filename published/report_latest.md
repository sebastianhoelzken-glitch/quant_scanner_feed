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

- **EUROPE:** 77.3/100
- **OTHER:** 71.9/100
- **US:** 85.5/100

## Main multi-horizon ranking

|   rank | symbol   | name                              | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.        | US       |                3.5  |             77.4  |         77.78 |         77.01 |          77.89 |        72.2  |           73.91 |             72.71 |             60.14 |         6.75 |             85.65 | medium             |                2.86 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.               | OTHER    |                2.51 |             70.4  |         77.72 |         67.43 |          69.33 |        71.46 |           70.94 |             65.64 |             70.45 |         5.03 |             84.89 | short              |               -1.93 |                   nan |                  nan |
|      3 | AMCX     | AMC Global Media Inc.             | US       |                0.43 |             69    |         72.21 |         71.41 |          66.59 |        62.81 |           46.76 |             70.29 |             81    |         7.57 |             85.14 | short              |                2.32 |                   nan |                  nan |
|      4 | VSXY     | Victorias Secret & Co.            | US       |                6.32 |             68.54 |         64.84 |         75.08 |          72.24 |        63.08 |           59.82 |             70.05 |             41.22 |         7.83 |             86.67 | swing              |              -20.26 |                   nan |                  nan |
|      5 | FTNT     | Fortinet, Inc.                    | US       |              104.12 |             68.49 |         63.57 |         73.41 |          73.62 |        63.23 |           75    |             68.33 |             27.28 |         4.57 |             90.46 | medium             |              -17.43 |                   nan |                  nan |
|      6 | ALKS     | Alkermes plc                      | OTHER    |                7.25 |             68.38 |         47.46 |         63.1  |          73.66 |        76.07 |           87.61 |             51.72 |             69.9  |         5.37 |             82.6  | long               |              nan    |                   nan |                  nan |
|      7 | SU.PA    | Schneider Electric S.E.           | EUROPE   |              173.84 |             68.02 |         78.79 |         70.02 |          66.03 |        63.94 |           78.58 |             72.38 |             34.99 |         4.65 |             89.69 | short              |                0.41 |                   nan |                  nan |
|      8 | KELYA    | Kelly Services, Inc.              | US       |                0.47 |             67.12 |         64.15 |         77.25 |          68.77 |        65.48 |           48.12 |             65.23 |             88    |         6.25 |             85.62 | swing              |                3.37 |                   nan |                  nan |
|      9 | SM       | SM Energy Company                 | US       |                6.58 |             66.43 |         65.83 |         59.48 |          67.03 |        71.59 |           79.13 |             51.54 |             77.86 |         6.64 |             87.81 | long               |               -2.27 |                   nan |                  nan |
|     10 | TWN      | The Taiwan Fund, Inc.             | US       |                0.48 |             66.09 |         68.7  |         63.49 |          69.51 |        58.78 |           72.66 |             81.28 |             16.4  |         6.3  |             61.74 | medium             |               -0.81 |                   nan |                  nan |
|     11 | BLMN     | Bloomin' Brands, Inc.             | US       |                0.82 |             66.06 |         71.07 |         67.66 |          63.91 |        64.46 |           54.49 |             51.07 |             78.42 |         7.72 |             87.69 | short              |              -15.33 |                   nan |                  nan |
|     12 | RMAX     | RE/MAX Holdings, Inc.             | US       |                0.58 |             65.57 |         72.07 |         67.99 |          63.15 |        59.12 |           59.6  |             53.35 |             59.85 |         7.22 |             75.57 | short              |                0.11 |                   nan |                  nan |
|     13 | ASML.AS  | ASML Holding N.V.                 | EUROPE   |              618.17 |             65.06 |         60.65 |         65.18 |          71.91 |        64.94 |           83.26 |             75.53 |             18.81 |         6.05 |             89.58 | medium             |                1.11 |                   nan |                  nan |
|     14 | DAC      | Danaos Corporation                | OTHER    |                2.25 |             64.75 |         69.26 |         64.51 |          64.98 |        61.82 |           65.85 |             54.11 |             49.11 |         3.25 |             83.35 | short              |               -0.83 |                   nan |                  nan |
|     15 | NNBR     | NN, Inc.                          | US       |                0.26 |             64.7  |         63.92 |         72.4  |          65.49 |        55.94 |           55.41 |             58.36 |             38.33 |         7.55 |             83.65 | swing              |              -22.4  |                   nan |                  nan |
|     16 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.85 |             64.37 |         68.87 |         68.96 |          59.87 |        55.26 |           60.28 |             55.96 |             39.77 |         5.88 |             79.32 | swing              |               -0.55 |                   nan |                  nan |
|     17 | ETSY     | Etsy, Inc.                        | US       |                6.34 |             64.28 |         46.34 |         67.04 |          67.32 |        61.53 |           74.12 |             60.69 |             37.95 |         7.23 |             87.01 | medium             |               -9.9  |                   nan |                  nan |
|     18 | WKC      | World Kinect Corporation          | US       |                1.65 |             63.57 |         60.5  |         69.92 |          66.65 |        57.86 |           46.33 |             73.01 |             53.57 |         4.91 |             84.31 | swing              |                0.09 |                   nan |                  nan |
|     19 | BAX      | Baxter International Inc.         | US       |               12.08 |             63.44 |         72.63 |         69.1  |          57.77 |        55.27 |           58.85 |             55.56 |             46.63 |         5.49 |             88.65 | short              |              -12.39 |                   nan |                  nan |
|     20 | IRWD     | Ironwood Pharmaceuticals, Inc.    | US       |                0.59 |             62.99 |         55.9  |         55.39 |          70.07 |        82.6  |           90.2  |             65.29 |             85.58 |         6.46 |             82.86 | long               |              nan    |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.59 |                  71.02 |                    73.48 |                 76.21 |              71.95 |                79.4  |                   20.6  |           90.2  |             65.29 |       0.179 |         nan |       nan |        4.33 |         2.8  |          5.22 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | 0QXR.IL  | Stellantis N.V.                                      | OTHER    |               25.94 |                  72.53 |                    72.89 |                 73.5  |              71.9  |                69.39 |                   30.61 |           77.72 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            3 | SM       | SM Energy Company                                    | US       |                6.58 |                  73.62 |                    70.98 |                 70.46 |              69.94 |                65.46 |                   34.54 |           79.13 |             51.54 |       0.194 |         nan |       nan |        4.53 |         4.34 |          5.65 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            4 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.55 |                    70.88 |                 73.03 |              70.78 |                83.46 |                   16.54 |           82.77 |             56.77 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               40.41 |                  65.03 |                    70.18 |                 72.11 |              67.58 |                77.76 |                   22.24 |           81.46 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            6 | MTRX     | Matrix Service Company                               | US       |                0.29 |                  74.09 |                    69.61 |                 70.32 |              71.16 |                65.26 |                   34.74 |           72.34 |             60.69 |       0.301 |         nan |       nan |      -46.91 |        16.88 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|            7 | ALKS     | Alkermes plc                                         | OTHER    |                7.25 |                  67.83 |                    68.65 |                 71.73 |              67.87 |                76.99 |                   23.01 |           87.61 |             51.72 |       0.018 |         nan |       nan |       32.82 |        27.26 |        127.77 |        1.96 |                 nan |              nan |                  10 |                  0.53 |
|            8 | AMCX     | AMC Global Media Inc.                                | US       |                0.43 |                  74.57 |                    68.23 |                 66.06 |              73.04 |                68.45 |                   31.55 |           46.76 |             70.29 |       2.01  |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.5  |                  67.07 |                    68.23 |                 69.81 |              67.85 |                68.25 |                   31.75 |           73.91 |             72.71 |       0.02  |         nan |       nan |        3.81 |         6.09 |          4.73 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.9  |                  67    |                    68.2  |                 71.06 |              65.59 |                66.27 |                   33.73 |           91.37 |             54.21 |     nan     |         nan |       nan |        3.7  |         9.85 |         28.4  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           11 | UNIT     | Uniti Group Inc.                                     | US       |                2.04 |                  80.26 |                    67.89 |                 65.12 |              69.81 |                50.14 |                   49.86 |           67.97 |             29.9  |      -0.11  |         nan |       nan |        9.02 |       -13.67 |          2.46 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           12 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.79 |                    67.42 |                 68.68 |              66.6  |                70.56 |                   29.44 |           82.29 |             43.77 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.71 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           13 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  66.86 |                    66.69 |                 67.95 |              67.04 |                68.53 |                   31.47 |           70.94 |             65.64 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           14 | INVA     | Innoviva, Inc.                                       | US       |                1.31 |                  65.48 |                    66.38 |                 67.82 |              64.97 |                78.13 |                   21.87 |           83.97 |             37.61 |       0.073 |         nan |       nan |        6.43 |         9.43 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           15 | IHS      | IHS Holding Limited                                  | OTHER    |                2.45 |                  68.69 |                    65.75 |                 66.39 |              68.48 |                59.4  |                   40.6  |           56.28 |             83.3  |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           16 | AVGO     | Broadcom Inc.                                        | US       |             1740.2  |                  53.89 |                    65.32 |                 66.76 |              59.58 |                79.83 |                   20.17 |           83.64 |             64.14 |       0.014 |         nan |       nan |       48.11 |        21.59 |         70.4  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           17 | KELYA    | Kelly Services, Inc.                                 | US       |                0.47 |                  72.98 |                    65.1  |                 63.14 |              69.25 |                56.58 |                   43.42 |           48.12 |             65.23 |       0.137 |         nan |       nan |        8.88 |         8.63 |        nan    |        1.13 |                 nan |              nan |                  11 |                  0.58 |
|           18 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.56 |                  70.73 |                    64.92 |                 62.87 |              65.61 |                61.54 |                   38.46 |           65.61 |             36.07 |       0.386 |         nan |       nan |       13.79 |         3.11 |          6.99 |        0.7  |                 nan |              nan |                  12 |                  0.63 |
|           19 | FVRR     | Fiverr International Ltd.                            | OTHER    |                0.27 |                  76.97 |                    64.37 |                 60.7  |              66.77 |                52.39 |                   47.61 |           61.27 |             19.23 |       0.268 |         nan |       nan |        1.25 |         6.66 |         10.77 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           20 | GENI     | Genius Sports Limited                                | OTHER    |                1.86 |                  68.4  |                    64.09 |                 64.17 |              67.27 |                55.8  |                   44.2  |           52.21 |             79.79 |       0.075 |         nan |       nan |      -38.55 |         7.23 |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.59 |                  71.02 |                    73.48 |                 76.21 |              71.95 |                79.4  |                   20.6  |           90.2  |             65.29 |       0.179 |         nan |       nan |        4.33 |         2.8  |          5.22 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | 0QXR.IL  | Stellantis N.V.                                        | OTHER    |               25.94 |                  72.53 |                    72.89 |                 73.5  |              71.9  |                69.39 |                   30.61 |           77.72 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            4 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  69.55 |                    70.88 |                 73.03 |              70.78 |                83.46 |                   16.54 |           82.77 |             56.77 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | 0P6O.IL  | Volkswagen AG                                          | OTHER    |               40.41 |                  65.03 |                    70.18 |                 72.11 |              67.58 |                77.76 |                   22.24 |           81.46 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            7 | ALKS     | Alkermes plc                                           | OTHER    |                7.25 |                  67.83 |                    68.65 |                 71.73 |              67.87 |                76.99 |                   23.01 |           87.61 |             51.72 |       0.018 |         nan |       nan |       32.82 |        27.26 |        127.77 |        1.96 |                 nan |              nan |                  10 |                  0.53 |
|           10 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.9  |                  67    |                    68.2  |                 71.06 |              65.59 |                66.27 |                   33.73 |           91.37 |             54.21 |     nan     |         nan |       nan |        3.7  |         9.85 |         28.4  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            3 | SM       | SM Energy Company                                      | US       |                6.58 |                  73.62 |                    70.98 |                 70.46 |              69.94 |                65.46 |                   34.54 |           79.13 |             51.54 |       0.194 |         nan |       nan |        4.53 |         4.34 |          5.65 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            6 | MTRX     | Matrix Service Company                                 | US       |                0.29 |                  74.09 |                    69.61 |                 70.32 |              71.16 |                65.26 |                   34.74 |           72.34 |             60.69 |       0.301 |         nan |       nan |      -46.91 |        16.88 |        nan    |        1.11 |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.5  |                  67.07 |                    68.23 |                 69.81 |              67.85 |                68.25 |                   31.75 |           73.91 |             72.71 |       0.02  |         nan |       nan |        3.81 |         6.09 |          4.73 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.08 |                  68.79 |                    67.42 |                 68.68 |              66.6  |                70.56 |                   29.44 |           82.29 |             43.77 |     nan     |         nan |       nan |        3.93 |       161.54 |          4.71 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           13 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.51 |                  66.86 |                    66.69 |                 67.95 |              67.04 |                68.53 |                   31.47 |           70.94 |             65.64 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           14 | INVA     | Innoviva, Inc.                                         | US       |                1.31 |                  65.48 |                    66.38 |                 67.82 |              64.97 |                78.13 |                   21.87 |           83.97 |             37.61 |       0.073 |         nan |       nan |        6.43 |         9.43 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           16 | AVGO     | Broadcom Inc.                                          | US       |             1740.2  |                  53.89 |                    65.32 |                 66.76 |              59.58 |                79.83 |                   20.17 |           83.64 |             64.14 |       0.014 |         nan |       nan |       48.11 |        21.59 |         70.4  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           15 | IHS      | IHS Holding Limited                                    | OTHER    |                2.45 |                  68.69 |                    65.75 |                 66.39 |              68.48 |                59.4  |                   40.6  |           56.28 |             83.3  |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           22 | ORC      | Orchid Island Capital, Inc.                            | US       |                1.15 |                  61.42 |                    63.83 |                 66.34 |              60.42 |                68.65 |                   31.35 |           90.57 |             38.44 |     nan     |         nan |       nan |      nan    |         6.42 |          3.78 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |                  74.57 |                    68.23 |                 66.06 |              73.04 |                68.45 |                   31.55 |           46.76 |             70.29 |       2.01  |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           26 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |                  55.41 |                    63.18 |                 65.31 |              61.56 |                75.08 |                   24.92 |           67.53 |             81.54 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           11 | UNIT     | Uniti Group Inc.                                       | US       |                2.04 |                  80.26 |                    67.89 |                 65.12 |              69.81 |                50.14 |                   49.86 |           67.97 |             29.9  |      -0.11  |         nan |       nan |        9.02 |       -13.67 |          2.46 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           20 | GENI     | Genius Sports Limited                                  | OTHER    |                1.86 |                  68.4  |                    64.09 |                 64.17 |              67.27 |                55.8  |                   44.2  |           52.21 |             79.79 |       0.075 |         nan |       nan |      -38.55 |         7.23 |        nan    |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           24 | YPF      | YPF Sociedad Anónima                                   | OTHER    |               16.54 |                  68.06 |                    63.54 |                 63.61 |              64.02 |                47.18 |                   52.82 |           64.49 |             65.22 |       0.061 |         nan |       nan |        1.68 |         8.47 |          1.25 |        0.1  |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | FTNT     | Fortinet, Inc.                    | US       |              104.12 |                     0.03 |     0.02 |      0.02 |                  49.66 |                        69.4  |         63.57 |         73.41 |          73.62 |        63.23 |           75    |             68.33 |         4.57 |
|               2 | VSXY     | Victorias Secret & Co.            | US       |                6.32 |                     0.08 |    -0.02 |      0.12 |                  60.42 |                        69.07 |         64.84 |         75.08 |          72.24 |        63.08 |           59.82 |             70.05 |         7.83 |
|               3 | ELF      | e.l.f. Beauty, Inc.               | US       |                4.7  |                     0.07 |    -0    |      0.23 |                  64.69 |                        68.15 |         65.65 |         63.02 |          54.87 |        54.11 |           83.18 |             59.91 |         8.36 |
|               4 | NNBR     | NN, Inc.                          | US       |                0.26 |                     0.07 |    -0.06 |      0.2  |                  80.53 |                        68.12 |         63.92 |         72.4  |          65.49 |        55.94 |           55.41 |             58.36 |         7.55 |
|               5 | ALL      | The Allstate Corporation          | US       |               56.56 |                     0.06 |    -0.06 |      0.07 |                  84.07 |                        67.88 |         57.89 |         64    |          61.51 |        55.71 |           69.02 |             63.07 |         3.06 |
|               6 | HRTG     | Heritage Insurance Holdings, Inc. | US       |                0.85 |                     0.06 |    -0.06 |      0.24 |                  84.61 |                        67.62 |         68.87 |         68.96 |          59.87 |        55.26 |           60.28 |             55.96 |         5.88 |
|               7 | GENI     | Genius Sports Limited             | OTHER    |                1.86 |                     0.07 |    -0.02 |      0.23 |                  63.28 |                        67.54 |         71.28 |         68.09 |          56.47 |        52.69 |           52.21 |             79.79 |         8.18 |
|               8 | ETSY     | Etsy, Inc.                        | US       |                6.34 |                     0.07 |    -0.03 |     -0.04 |                  67.01 |                        67.5  |         46.34 |         67.04 |          67.32 |        61.53 |           74.12 |             60.69 |         7.23 |
|               9 | BAX      | Baxter International Inc.         | US       |               12.08 |                     0.05 |    -0    |      0.15 |                  68.82 |                        66.74 |         72.63 |         69.1  |          57.77 |        55.27 |           58.85 |             55.56 |         5.49 |
|              10 | IRWD     | Ironwood Pharmaceuticals, Inc.    | US       |                0.59 |                     0.07 |    -0.03 |      0.07 |                  72.81 |                        66.71 |         55.9  |         55.39 |          70.07 |        82.6  |           90.2  |             65.29 |         6.46 |
|              11 | CLOV     | Clover Health Investments, Corp.  | US       |                2.07 |                     0.06 |    -0.04 |      0.02 |                  77.08 |                        65.99 |         46.65 |         64.22 |          69.22 |        59.46 |           57.75 |             71.81 |         7.53 |
|              12 | KELYA    | Kelly Services, Inc.              | US       |                0.47 |                     0.03 |     0.01 |      0.02 |                  51.97 |                        65.83 |         64.15 |         77.25 |          68.77 |        65.48 |           48.12 |             65.23 |         6.25 |
|              13 | AMZN     | Amazon.com, Inc.                  | US       |             2478.74 |                     0.07 |    -0.03 |      0.06 |                  71.49 |                        65.7  |         61.7  |         55.75 |          59.05 |        55.65 |           73.48 |             62.88 |         5.72 |
|              14 | CRCT     | Cricut, Inc.                      | US       |                1.06 |                     0.04 |    -0.04 |      0.24 |                  71.29 |                        65.46 |         72.73 |         69.64 |          55.69 |        49.2  |           42.65 |             65.8  |         6.44 |
|              15 | EDEN.PA  | Edenred SE                        | EUROPE   |                6.43 |                     0.05 |    -0.03 |      0.06 |                  74.07 |                        64.58 |         58.01 |         70.77 |          60.44 |        49.75 |           42.31 |             64.16 |         6.17 |
|              16 | WKC      | World Kinect Corporation          | US       |                1.65 |                     0.07 |     0    |      0.01 |                  59.23 |                        64.06 |         60.5  |         69.92 |          66.65 |        57.86 |           46.33 |             73.01 |         4.91 |
|              17 | MSFT     | Microsoft Corporation             | US       |             3186.52 |                     0.02 |    -0.01 |      0.23 |                  53.66 |                        63.9  |         70.41 |         63.99 |          54.66 |        53.37 |           59.15 |             58.74 |         5.7  |
|              18 | CLW      | Clearwater Paper Corporation      | US       |                0.31 |                     0.06 |    -0.04 |      0.34 |                  79.68 |                        63.82 |         67.13 |         63.44 |          50.27 |        46.86 |           45.24 |             61.67 |         6.76 |
|              19 | AMRX     | Amneal Pharmaceuticals, Inc.      | US       |                5.39 |                     0.07 |    -0.01 |     -0.01 |                  67.43 |                        63.62 |         49.14 |         62.05 |          64.2  |        60.55 |           73.04 |             52.5  |         5.14 |
|              20 | TOST     | Toast, Inc.                       | US       |               17.24 |                     0.04 |    -0.01 |      0.13 |                  64.81 |                        63.41 |         65.76 |         66.74 |          55.82 |        53.21 |           55.86 |             60.99 |         7.07 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | WDAY     | Workday, Inc.                | US       |               37.7  |             63.59 |         72.77 |         66.81 |          57.81 |        60.38 |           65.9  |             56.96 |             63.18 |         7.64 |             89.8  | short              |                0.19 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4734.86 |             62.99 |         67.66 |         56.52 |          61.53 |        64.45 |           89.1  |             60.49 |             37.64 |         5.55 |             89.54 | short              |               -2.55 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             59.93 |         61.43 |         61.31 |          55    |        58.55 |           37.66 |             49.04 |             81.94 |         8.42 |             85.47 | short              |               -3.26 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.14 |             41.92 |         26.61 |         36.11 |          47.74 |        63.82 |           77.48 |             47.66 |             78.83 |         8.5  |             82.99 | long               |               -0.08 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             39.67 |         51.28 |         38.53 |          35.13 |        40.81 |           28.94 |             28.56 |             62.52 |         4.44 |             74.95 | short              |               -1.01 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               33.82 |             38.32 |         32.71 |         34.74 |          41.9  |        45.7  |           45.32 |             49.75 |             55.85 |         8.5  |             83.72 | long               |              -15.41 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.92 |             37.14 |         26.46 |         32.97 |          41.31 |        53.09 |           49.1  |             46.44 |             78.76 |         6.19 |             78.58 | long               |               -3.16 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             36.08 |         27.84 |         32.54 |          39.63 |        52.84 |           46.72 |             40.66 |             86.54 |         7.14 |             78.43 | long               |               -3.88 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.62 |             35.86 |         30.08 |         28.97 |          41.64 |        59.62 |           75.26 |             24.57 |             76.43 |         4.91 |             81.52 | long               |               -2.68 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.89 |             35.06 |         34.84 |         21.1  |          35.28 |        46.56 |           64.09 |             19.37 |             42.67 |         9.09 |             77.55 | long               |               -3.74 |                   nan |                  nan |
|    nan | AT1.DE   | Aroundtown SA                | EUROPE   |                2.23 |             34.91 |         36.25 |         28.09 |          33.56 |        43.2  |           48.33 |             34.95 |             53.93 |         5.55 |             75.53 | long               |                3.57 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.73 |             32.8  |         37.93 |         22.37 |          28.82 |        36.78 |           38.42 |             37.36 |             48.67 |         7.04 |             75.4  | short              |               -1.11 |                   nan |                  nan |
|    nan | HFG.DE   | HelloFresh SE                | EUROPE   |                0.48 |             29.12 |         29.04 |         20.76 |          29.19 |        42.09 |           46.43 |             24.05 |             64.57 |         8.5  |             80.25 | long               |                5.98 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             27.28 |         57.78 |         23.41 |          22.29 |        31.14 |           21.62 |             27    |             59.43 |         7.77 |             75.24 | short              |               -0.71 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.43 |             22.58 |         25.36 |         20.18 |          21.28 |        23.88 |           16.55 |             36.69 |             35.48 |         6.86 |             73.61 | short              |               -6.71 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA.VI (security_id=ISIN:AR0940941575)

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
- Excluded by hard/data filters: **820**
- Event watch (otherwise eligible): **15**
- Final eligible: **165**
- Eligible change vs previous stored run: **+61**

Top exclusion categories:
- market_cap: 774
- liquidity: 234
- price: 177
- data_confidence: 48
- price_history: 18
- duplicate_listing: 3
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 9 |  | 9 | 2 | main,value,quality_value |
| ALKS | 6 | 7 |  | 5 | 2 | main,value,quality_value |
| SM | 9 | 3 |  | 7 | 2 | main,value,quality_value |
| IRWD | 20 | 1 | 10 | 1 | 2 | value,pullback,quality_value |
| AMCX | 3 | 8 |  | 16 | 2 | main,value |
| VSXY | 4 | 98 | 2 | 96 | 2 | main,pullback |
| FTNT | 5 | 30 | 1 | 23 | 2 | main,pullback |
| PKX | 79 | 10 | 23 | 6 | 1 | value,quality_value |
| NWL.MI | 90 | 4 |  | 3 | 1 | value,quality_value |
| MTRX | 94 | 6 | 47 | 8 | 1 | value,quality_value |
| 0QXR.IL | 99 | 2 |  | 2 | 1 | value,quality_value |
| 0P6O.IL | 137 | 5 |  | 4 | 1 | value,quality_value |
| TNK | 2 | 13 |  | 11 | 1 | main |
| SU.PA | 7 | 80 |  | 54 | 1 | main |
| KELYA | 8 | 17 | 12 | 22 | 1 | main |

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
| 1 | IRWD | value+pullback | 75.45 | 71.02 | 72.81 | 90.20 | 65.29 | 79.40 | 62.99 |
| 2 | 0P6O.IL | value+pullback | 71.45 | 65.03 | 76.67 | 81.46 |  | 77.76 | 41.18 |
| 3 | IRS | value+pullback | 68.65 | 68.79 | 68.72 | 82.29 | 43.77 | 70.56 | 47.68 |
| 4 | INVA | value+pullback | 68.43 | 65.48 | 67.20 | 83.97 | 37.61 | 78.13 | 43.20 |
| 5 | VOW3.DE | value+pullback | 66.67 | 70.73 | 78.78 | 65.61 | 36.07 | 61.54 | 37.29 |
| 6 | FLYW | value+pullback | 66.22 | 64.01 | 79.99 | 54.48 | 66.67 | 60.92 | 61.27 |
| 7 | PKX | value+pullback | 65.25 | 67.00 | 51.09 | 91.37 | 54.21 | 66.27 | 55.32 |
| 8 | MTRX | value+pullback | 65.15 | 74.09 | 51.81 | 72.34 | 60.69 | 65.26 | 52.04 |
| 9 | GSL | value+pullback | 64.37 | 61.67 | 69.99 | 68.31 | 37.27 | 72.01 | 57.64 |
| 10 | GENI | value+pullback | 63.31 | 68.40 | 63.28 | 52.21 | 79.79 | 55.80 | 62.28 |
| 11 | YPF | value+pullback | 62.21 | 68.06 | 64.64 | 64.49 | 65.22 | 47.18 | 62.52 |
| 12 | VOW.DE | value+pullback | 61.49 | 58.53 | 74.35 | 65.61 | 32.63 | 61.18 | 34.45 |
| 13 | 1VOW3.MI | value+pullback | 61.31 | 60.91 | 68.10 | 65.61 | 36.92 | 62.41 | 38.97 |
| 14 | PD | value+pullback | 61.08 | 69.75 | 62.93 | 52.35 | 49.37 | 58.18 | 60.18 |
| 15 | BHF | value+pullback | 60.88 | 68.11 | 61.35 | 52.35 | 43.11 | 64.75 | 43.85 |
| 16 | ALL-PH | value+pullback | 60.77 | 62.23 | 62.56 | 69.02 | 40.91 | 60.10 | 44.39 |
| 17 | TV | value+pullback | 60.26 | 67.11 | 55.42 | 48.38 | 61.64 | 64.28 | 48.93 |
| 18 | KELYA | value+pullback | 59.94 | 72.98 | 51.97 | 48.12 | 65.23 | 56.58 | 67.12 |
| 19 | LNC | value+pullback | 59.61 | 56.84 | 81.72 | 45.02 | 59.88 | 46.93 | 59.76 |
| 20 | AF.PA | value+pullback | 59.53 | 59.44 | 81.65 | 51.28 | 61.80 | 37.07 | 53.12 |
