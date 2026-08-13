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
- **OTHER:** 71.9/100
- **US:** 83.4/100

## Main multi-horizon ranking

|   rank | symbol   | name                                            | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                      | US       |                3.52 |             79.32 |         79.55 |         79.08 |          79.88 |        75.35 |           75.36 |             71.83 |             66.83 |         6.78 |             85.65 | medium             |                4.78 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                             | OTHER    |                2.49 |             72.33 |         78.54 |         69.8  |          71.62 |        73.04 |           70.94 |             72.52 |             70.45 |         5.06 |             84.89 | short              |                0.01 |                   nan |                  nan |
|      3 | TWN      | The Taiwan Fund, Inc.                           | US       |                0.49 |             69.19 |         71.48 |         66.89 |          71.48 |        61.03 |           72.52 |             80.26 |             20.4  |         6.3  |             61.74 | short              |                2.28 |                   nan |                  nan |
|      4 | SU.PA    | Schneider Electric S.E.                         | EUROPE   |              173.84 |             68.02 |         77.16 |         69.19 |          66.66 |        66.85 |           77.61 |             71.59 |             49.92 |         4.63 |             89.69 | short              |                0.41 |                   nan |                  nan |
|      5 | CEF      | Sprott Physical Gold and Silver Trust           | OTHER    |                7.11 |             67.77 |         73.13 |         50.72 |          62.42 |        83.57 |          nan    |             80.26 |            100    |         5.19 |             56.3  | long               |                2.05 |                   nan |                  nan |
|      6 | AOD      | AOD                                             | OTHER    |                1.14 |             67.7  |         67.86 |         65.25 |          67.54 |        73.06 |          nan    |             80.26 |            nan    |         1.85 |             55.39 | long               |                5.37 |                   nan |                  nan |
|      7 | AMCX     | AMC Global Media Inc.                           | US       |                0.43 |             67.57 |         70.67 |         70.46 |          64.69 |        59.22 |           41.23 |             69.73 |             75.73 |         7.58 |             85.14 | short              |                0.89 |                   nan |                  nan |
|      8 | RMAX     | RE/MAX Holdings, Inc.                           | US       |                0.59 |             67.29 |         73.94 |         70.02 |          64.55 |        60.15 |           61.68 |             55.05 |             57.81 |         7.28 |             75.57 | short              |                1.83 |                   nan |                  nan |
|      9 | DAC      | Danaos Corporation                              | OTHER    |                2.23 |             67.27 |         67.54 |         63.88 |          67.62 |        67    |           77.72 |             54.81 |             53.9  |         3.29 |             84.55 | medium             |                1.69 |                   nan |                  nan |
|     10 | SM       | SM Energy Company                               | US       |                6.64 |             67.19 |         66.1  |         60.51 |          68.28 |        73.57 |           80.8  |             48.22 |             80.33 |         6.67 |             88.18 | long               |               -1.52 |                   nan |                  nan |
|     11 | HQH      | Abrdn Healthcare Investors                      | US       |                1.17 |             67.01 |         75.05 |         71.95 |          62.07 |        48.71 |           44.23 |             80.26 |             18.99 |         2.17 |             61.74 | short              |                4.95 |                   nan |                  nan |
|     12 | HRTG     | Heritage Insurance Holdings, Inc.               | US       |                0.85 |             65.32 |         69.61 |         70.4  |          61.04 |        56.36 |           59.27 |             54.77 |             41.04 |         5.9  |             79.32 | swing              |                0.4  |                   nan |                  nan |
|     13 | ASML.AS  | ASML Holding N.V.                               | EUROPE   |              618.17 |             64.72 |         60    |         65.47 |          70.83 |        63.98 |           72.47 |             74.39 |             30.04 |         6.03 |             89.58 | medium             |                0.78 |                   nan |                  nan |
|     14 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund | US       |                1.91 |             64.67 |         69.37 |         68.46 |          60.87 |        53.57 |           49.69 |             80.51 |             35.96 |         2.13 |             62.78 | short              |                0.96 |                   nan |                  nan |
|     15 | AMZN     | Amazon.com, Inc.                                | US       |             2489.81 |             64.59 |         63.55 |         58.86 |          65.62 |        67.7  |           89.57 |             62.64 |             45.17 |         5.74 |             89.85 | long               |                0.47 |                   nan |                  nan |
|     16 | CNC      | Centene Corporation                             | US       |               28.24 |             64.51 |         63.1  |         64.19 |          69.23 |        64.82 |           56.91 |             64.33 |             69.12 |         5.81 |             88.46 | medium             |                0.73 |                   nan |                  nan |
|     17 | YPF      | YPF Sociedad Anónima                            | OTHER    |               16.76 |             64.21 |         49.42 |         61.1  |          68.24 |        67.32 |           64.49 |             64.46 |             64.35 |         5.74 |             84.57 | medium             |                1.91 |                   nan |                  nan |
|     18 | WKC      | World Kinect Corporation                        | US       |                1.65 |             64.19 |         60.59 |         71.06 |          67.79 |        59.38 |           46.4  |             71.22 |             56.33 |         4.92 |             84.31 | swing              |                0.71 |                   nan |                  nan |
|     19 | SLDE     | Slide Insurance Holdings, Inc.                  | US       |                2.17 |             64.17 |         63.93 |         64.82 |          64.4  |        62.38 |           76.51 |             53.73 |             40.14 |         5.77 |             80.19 | swing              |                2.34 |                   nan |                  nan |
|     20 | HQL      | Abrdn Life Sciences Investors                   | US       |                0.56 |             63.94 |         74.22 |         68.63 |          59.26 |        45.99 |           47.15 |            nan    |             20.61 |         2.27 |             61.1  | short              |               -0.61 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                                    | US       |                6.64 |                  77.15 |                    72.62 |                 71.6  |              71.71 |                63.01 |                   36.99 |           80.8  |             48.22 |       0.192 |         nan |       nan |        4.53 |         4.38 |          5.71 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            2 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.31 |                  78.38 |                    71.04 |                 70.04 |              72.83 |                69.16 |                   30.84 |           73.91 |             39.46 |       0.086 |         nan |       nan |        3.57 |         4.73 |          4.09 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            3 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.52 |                  71.16 |                    70.31 |                 71.58 |              70.35 |                66.28 |                   33.72 |           75.36 |             71.83 |       0.02  |         nan |       nan |        3.81 |         6.13 |          4.76 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    69.15 |                 69.19 |              72.57 |                68.04 |                   31.96 |           60    |             71.76 |       0.527 |         nan |       nan |        6.42 |         7.54 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.2  |                 69.81 |              66.98 |                72.84 |                   27.16 |           85.31 |             44.42 |     nan     |         nan |       nan |        3.93 |       161.21 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.49 |                  67.78 |                    68.06 |                 69.57 |              68.6  |                69.74 |                   30.26 |           70.94 |             72.52 |       0.078 |         nan |       nan |        3.2  |         9.11 |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            7 | IHS      | IHS Holding Limited                                  | OTHER    |                2.45 |                  69.61 |                    68.04 |                 69.13 |              70.3  |                65.94 |                   34.06 |           61.75 |             83.14 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | INVA     | Innoviva, Inc.                                       | US       |                1.3  |                  66.84 |                    67.42 |                 68.88 |              66.1  |                78.47 |                   21.53 |           85.02 |             38.5  |       0.074 |         nan |       nan |        6.43 |         9.39 |          4.81 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|            9 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.91 |                  66.69 |                    66.95 |                 69.43 |              64.76 |                63.19 |                   36.81 |           87.54 |             53.7  |     nan     |         nan |       nan |        3.7  |         9.86 |         28.56 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.92 |                 67.86 |              68.17 |                69.42 |                   30.58 |           70.87 |             56.37 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | AVGO     | Broadcom Inc.                                        | US       |             1736.65 |                  57.41 |                    66.69 |                 67.51 |              61.94 |                78.55 |                   21.45 |           80.74 |             64.74 |       0.014 |         nan |       nan |       48.11 |        21.56 |         70.29 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           12 | CNC      | Centene Corporation                                  | US       |               28.24 |                  69.74 |                    65.83 |                 63.47 |              66.5  |                54.74 |                   45.26 |           56.91 |             64.33 |       0.296 |         nan |       nan |        4.84 |        12.44 |        nan    |        0.91 |                 nan |              nan |                  10 |                  0.53 |
|           13 | UNIT     | Uniti Group Inc.                                     | US       |                2.05 |                  73.48 |                    65.31 |                 63.43 |              66.02 |                55.39 |                   44.61 |           69.33 |             31.46 |      -0.109 |         nan |       nan |        9.02 |       -13.73 |          2.54 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           14 | DAC      | Danaos Corporation                                   | OTHER    |                2.23 |                  61.65 |                    65.04 |                 67.1  |              63.92 |                78.08 |                   21.92 |           77.72 |             54.81 |       0.002 |         nan |       nan |        3.74 |         5.78 |          4.79 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           15 | RCI      | Rogers Communications Inc.                           | OTHER    |               17    |                  59.32 |                    64.62 |                 66.13 |              58.34 |                63.2  |                   36.8  |           94.29 |             42.53 |     nan     |         nan |       nan |        7.28 |        10.4  |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           16 | SU.PA    | Schneider Electric S.E.                              | EUROPE   |              173.84 |                  53.98 |                    64.41 |                 65.92 |              59.81 |                76.58 |                   23.42 |           77.61 |             71.59 |       0.031 |         nan |       nan |       22.47 |        25.62 |         36.43 |        1.83 |                 nan |              nan |                  12 |                  0.63 |
|           17 | FVRR     | Fiverr International Ltd.                            | OTHER    |                0.28 |                  76.82 |                    63.73 |                 59.94 |              66.28 |                49.66 |                   50.34 |           59.52 |             20.29 |       0.261 |         nan |       nan |        1.25 |         6.84 |         11.06 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           18 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.76 |                  68.06 |                    63.45 |                 63.48 |              63.92 |                47.06 |                   52.94 |           64.49 |             64.46 |       0.06  |         nan |       nan |        1.68 |         8.59 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           19 | BHF      | Brighthouse Financial, Inc.                          | US       |                2.97 |                  69.85 |                    63.25 |                 60.95 |              66.35 |                65.07 |                   34.93 |           52.94 |             43.45 |       5.804 |         nan |       nan |      nan    |         2.96 |          4.72 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           20 | MTRX     | Matrix Service Company                               | US       |                0.29 |                  74.8  |                    63.08 |                 60.38 |              69.27 |                52.57 |                   47.43 |           39.59 |             59.57 |       0.302 |         nan |       nan |      -46.91 |        16.83 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | SM       | SM Energy Company                                    | US       |                6.64 |                  77.15 |                    72.62 |                 71.6  |              71.71 |                63.01 |                   36.99 |           80.8  |             48.22 |       0.192 |         nan |       nan |        4.53 |         4.38 |          5.71 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            3 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.52 |                  71.16 |                    70.31 |                 71.58 |              70.35 |                66.28 |                   33.72 |           75.36 |             71.83 |       0.02  |         nan |       nan |        3.81 |         6.13 |          4.76 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.31 |                  78.38 |                    71.04 |                 70.04 |              72.83 |                69.16 |                   30.84 |           73.91 |             39.46 |       0.086 |         nan |       nan |        3.57 |         4.73 |          4.09 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            5 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.2  |                 69.81 |              66.98 |                72.84 |                   27.16 |           85.31 |             44.42 |     nan     |         nan |       nan |        3.93 |       161.21 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.49 |                  67.78 |                    68.06 |                 69.57 |              68.6  |                69.74 |                   30.26 |           70.94 |             72.52 |       0.078 |         nan |       nan |        3.2  |         9.11 |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            9 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.91 |                  66.69 |                    66.95 |                 69.43 |              64.76 |                63.19 |                   36.81 |           87.54 |             53.7  |     nan     |         nan |       nan |        3.7  |         9.86 |         28.56 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            4 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    69.15 |                 69.19 |              72.57 |                68.04 |                   31.96 |           60    |             71.76 |       0.527 |         nan |       nan |        6.42 |         7.54 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            7 | IHS      | IHS Holding Limited                                  | OTHER    |                2.45 |                  69.61 |                    68.04 |                 69.13 |              70.3  |                65.94 |                   34.06 |           61.75 |             83.14 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | INVA     | Innoviva, Inc.                                       | US       |                1.3  |                  66.84 |                    67.42 |                 68.88 |              66.1  |                78.47 |                   21.53 |           85.02 |             38.5  |       0.074 |         nan |       nan |        6.43 |         9.39 |          4.81 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.92 |                 67.86 |              68.17 |                69.42 |                   30.58 |           70.87 |             56.37 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | AVGO     | Broadcom Inc.                                        | US       |             1736.65 |                  57.41 |                    66.69 |                 67.51 |              61.94 |                78.55 |                   21.45 |           80.74 |             64.74 |       0.014 |         nan |       nan |       48.11 |        21.56 |         70.29 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           14 | DAC      | Danaos Corporation                                   | OTHER    |                2.23 |                  61.65 |                    65.04 |                 67.1  |              63.92 |                78.08 |                   21.92 |           77.72 |             54.81 |       0.002 |         nan |       nan |        3.74 |         5.78 |          4.79 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           15 | RCI      | Rogers Communications Inc.                           | OTHER    |               17    |                  59.32 |                    64.62 |                 66.13 |              58.34 |                63.2  |                   36.8  |           94.29 |             42.53 |     nan     |         nan |       nan |        7.28 |        10.4  |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           16 | SU.PA    | Schneider Electric S.E.                              | EUROPE   |              173.84 |                  53.98 |                    64.41 |                 65.92 |              59.81 |                76.58 |                   23.42 |           77.61 |             71.59 |       0.031 |         nan |       nan |       22.47 |        25.62 |         36.43 |        1.83 |                 nan |              nan |                  12 |                  0.63 |
|           31 | HMC      | Honda Motor Co., Ltd.                                | OTHER    |               35.1  |                  48.67 |                    60.28 |                 64.81 |              57.34 |                77.41 |                   22.59 |           75    |             83.63 |     nan     |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  10 |                  0.53 |
|           24 | AMZN     | Amazon.com, Inc.                                     | US       |             2489.81 |                  50.79 |                    61.65 |                 64.17 |              54.26 |                63.48 |                   36.52 |           89.57 |             62.64 |       0.001 |         nan |       nan |       17.83 |        25.65 |         21.42 |        1.48 |                 nan |              nan |                  11 |                  0.58 |
|          nan | GGN      | GAMCO Global Gold, Natural Resources & Income Trust  | US       |                0.72 |                  48.43 |                    60.22 |                 63.65 |              56.88 |                77.67 |                   22.33 |           72.67 |             80.26 |     nan     |         nan |       nan |      nan    |       nan    |          2.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           32 | ORC      | Orchid Island Capital, Inc.                          | US       |                1.16 |                  54.58 |                    60.23 |                 63.51 |              55.55 |                68.89 |                   31.11 |           91.35 |             38.53 |     nan     |         nan |       nan |      nan    |         6.42 |          3.8  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           18 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.76 |                  68.06 |                    63.45 |                 63.48 |              63.92 |                47.06 |                   52.94 |           64.49 |             64.46 |       0.06  |         nan |       nan |        1.68 |         8.59 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           12 | CNC      | Centene Corporation                                  | US       |               28.24 |                  69.74 |                    65.83 |                 63.47 |              66.5  |                54.74 |                   45.26 |           56.91 |             64.33 |       0.296 |         nan |       nan |        4.84 |        12.44 |        nan    |        0.91 |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                 | US       |             2489.81 |                     0.06 |    -0.02 |      0.07 |                  72.55 |                        69.97 |         63.55 |         58.86 |          65.62 |        67.7  |           89.57 |             62.64 |         5.74 |
|               2 | ALL      | The Allstate Corporation                         | US       |               56.65 |                     0.06 |    -0.06 |      0.07 |                  84.91 |                        69.27 |         59.97 |         66.53 |          63.31 |        57.27 |           68.63 |             63.64 |         3    |
|               3 | HRTG     | Heritage Insurance Holdings, Inc.                | US       |                0.85 |                     0.06 |    -0.06 |      0.24 |                  84.01 |                        67.87 |         69.61 |         70.4  |          61.04 |        56.36 |           59.27 |             54.77 |         5.9  |
|               4 | HMC      | Honda Motor Co., Ltd.                            | OTHER    |               35.1  |                     0.02 |     0.01 |      0.08 |                  44.68 |                        66.2  |         63.92 |         63.4  |          60.14 |        65.16 |           75    |             83.63 |         3.74 |
|               5 | CLW      | Clearwater Paper Corporation                     | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.37 |                        65.07 |         67.58 |         64.45 |          53.14 |        52.37 |           50.18 |             61.22 |         6.82 |
|               6 | WKC      | World Kinect Corporation                         | US       |                1.65 |                     0.07 |     0    |      0.01 |                  58.89 |                        64.33 |         60.59 |         71.06 |          67.79 |        59.38 |           46.4  |             71.22 |         4.92 |
|               7 | LLY      | Eli Lilly and Company                            | US       |              934.34 |                     0.02 |     0.01 |      0.03 |                  44.71 |                        64.3  |         60    |         61.33 |          66.61 |        65.79 |           90.07 |             59.45 |         4.13 |
|               8 | AVGO     | Broadcom Inc.                                    | US       |             1736.65 |                     0.02 |     0    |      0.13 |                  45.61 |                        64.25 |         63.11 |         56.06 |          61.9  |        61.51 |           80.74 |             64.74 |         6.14 |
|               9 | SLDE     | Slide Insurance Holdings, Inc.                   | US       |                2.17 |                     0.03 |     0.01 |      0.04 |                  54.44 |                        63.94 |         63.93 |         64.82 |          64.4  |        62.38 |           76.51 |             53.73 |         5.77 |
|              10 | MSFT     | Microsoft Corporation                            | US       |             3192.19 |                     0.02 |    -0.01 |      0.24 |                  51.43 |                        63.61 |         70.72 |         64.51 |          54.63 |        52.32 |           58.4  |             59.03 |         5.68 |
|              11 | YPF      | YPF Sociedad Anónima                             | OTHER    |               16.76 |                     0.06 |    -0.01 |      0.02 |                  68.53 |                        63.4  |         49.42 |         61.1  |          68.24 |        67.32 |           64.49 |             64.46 |         5.74 |
|              12 | PKX      | POSCO Holdings Inc.                              | OTHER    |               14.91 |                     0.03 |     0.01 |      0.11 |                  49.75 |                        61.81 |         57.58 |         36.91 |          51.57 |        65.39 |           87.54 |             53.7  |         6.07 |
|              13 | DSX      | Diana Shipping Inc.                              | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  55.47 |                        61.43 |         64.96 |         49.22 |          56.06 |        61.68 |           60    |             57.56 |         4.58 |
|              14 | MA       | Mastercard Incorporated                          | US       |              428.2  |                     0.02 |    -0.02 |      0.02 |                  57.53 |                        61.01 |         56.34 |         57.88 |          53.14 |        50.63 |           72.2  |             59.97 |         3.13 |
|              15 | V        | Visa Inc.                                        | US       |              586    |                     0.02 |    -0.02 |     -0.01 |                  55.94 |                        60.22 |         52.35 |         58.36 |          54.61 |        50.56 |           68.53 |             59.63 |         2.83 |
|              16 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund | US       |                0.78 |                     0.02 |     0    |     -0.01 |                  50.36 |                        59.91 |         50.98 |         57.12 |          59.48 |        59.7  |           58.78 |             80.26 |         1.81 |
|              17 | AMD      | Advanced Micro Devices, Inc.                     | US       |              694.24 |                     0.11 |     0    |     -0.02 |                  34.88 |                        58.51 |         44.91 |         58.55 |          69.75 |        59.57 |           65.04 |             73.28 |         7.25 |
|              18 | GSL      | Global Ship Lease, Inc.                          | OTHER    |                1.31 |                     0.05 |    -0.02 |      0.01 |                  74.55 |                        58.44 |         53.12 |         52.31 |          61.48 |        68.58 |           73.91 |             39.46 |         3.74 |
|              19 | GOOGL    | Alphabet Inc.                                    | US       |             3665.37 |                     0.08 |    -0.03 |     -0.02 |                  62.35 |                        58.17 |         43.57 |         43.61 |          59.45 |        58.69 |           81.86 |             70.96 |         4.84 |
|              20 | KELYA    | Kelly Services, Inc.                             | US       |                0.48 |                     0.02 |     0.02 |      0.03 |                  43.14 |                        57.92 |         64.87 |         75.59 |          61.06 |        51.37 |           20.27 |             64.02 |         6.3  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation           | US       |                1.92 |             65.55 |         66.1  |         64.99 |          62.79 |        69.52 |           67.03 |             49.58 |             78.15 |         8.39 |             86.67 | long               |                2.36 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4736.88 |             63.6  |         68.46 |         57.78 |          62.5  |        64.7  |           91.3  |             60.69 |             32.73 |         5.56 |             89.54 | short              |               -1.94 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.02 |             42.15 |         54.74 |         42.18 |          37.32 |        42.12 |           28.56 |             29.66 |             61.54 |         4.47 |             74.95 | short              |                1.46 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             39.63 |         29.73 |         35.04 |          44.21 |        58.45 |           64.33 |             42.32 |             78.89 |         7.15 |             78.43 | long               |               -0.34 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.91 |             39.36 |         38.34 |         23.91 |          40.39 |        54.87 |           74.9  |             20.02 |             54.95 |         9.1  |             77.55 | long               |                0.56 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             36.68 |         41.11 |         24.52 |          32.25 |        42.21 |           45.32 |             38.27 |             56.41 |         7.08 |             75.4  | long               |                2.77 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.62 |             35.35 |         29.28 |         29.15 |          41.41 |        58.39 |           72    |             25.5  |             75.22 |         4.87 |             81.52 | long               |               -3.2  |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.87 |             31.71 |         59.05 |         25.46 |          26.14 |        37.28 |           29.73 |             28    |             67.86 |         7.77 |             75.24 | short              |                3.73 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.42 |             25.45 |         26.26 |         21.51 |          24.63 |        28.59 |           29.19 |             37.53 |             33.44 |         6.88 |             73.61 | long               |               -3.84 |                   nan |                  nan |

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
- Excluded by hard/data filters: **880**
- Event watch (otherwise eligible): **9**
- Final eligible: **111**
- Eligible change vs previous stored run: **+7**

Top exclusion categories:
- market_cap: 857
- liquidity: 211
- price: 128
- data_confidence: 51
- price_history: 20
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 1 | 3 |  | 2 | 2 | main,value,quality_value |
| TNK | 2 | 6 |  | 5 | 2 | main,value,quality_value |
| SM | 10 | 1 |  | 1 | 2 | main,value,quality_value |
| IHS | 40 | 7 |  | 8 | 1 | value,quality_value |
| GSL | 44 | 2 | 18 | 3 | 1 | value,quality_value |
| PKX | 52 | 9 | 12 | 6 | 1 | value,quality_value |
| MAGN | 63 | 4 |  | 7 | 1 | value,quality_value |
| NWL.MI | 72 | 10 |  | 10 | 1 | value,quality_value |
| IRS | 73 | 5 | 21 | 4 | 1 | value,quality_value |
| INVA | 88 | 8 | 29 | 9 | 1 | value,quality_value |
| TWN | 3 |  |  |  | 1 | main |
| SU.PA | 4 | 16 |  | 14 | 1 | main |
| CEF | 5 |  |  |  | 1 | main |
| AOD | 6 |  |  |  | 1 | main |
| AMCX | 7 | 21 |  | 28 | 1 | main |

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
| 1 | GSL | value+pullback | 71.02 | 78.38 | 74.55 | 73.91 | 39.46 | 69.16 | 57.30 |
| 2 | INVA | value+pullback | 70.31 | 66.84 | 71.85 | 85.02 | 38.50 | 78.47 | 42.92 |
| 3 | IRS | value+pullback | 69.88 | 68.64 | 69.92 | 85.31 | 44.42 | 72.84 | 50.21 |
| 4 | SUZ | value+pullback | 64.86 | 58.39 | 72.46 | 70.51 | 46.85 | 69.82 | 39.68 |
| 5 | PKX | value+pullback | 63.58 | 66.69 | 49.75 | 87.54 | 53.70 | 63.19 | 54.57 |
| 6 | YPF | value+pullback | 63.08 | 68.06 | 68.53 | 64.49 | 64.46 | 47.06 | 64.21 |
| 7 | AVGO | value+pullback | 62.92 | 57.41 | 45.61 | 80.74 | 64.74 | 78.55 | 61.71 |
| 8 | CLW | value+pullback | 62.14 | 56.94 | 80.37 | 50.18 | 61.22 | 56.60 | 58.79 |
| 9 | BHF | value+pullback | 61.24 | 69.85 | 59.95 | 52.94 | 43.45 | 65.07 | 46.03 |
| 10 | ALL-PH | value+pullback | 61.20 | 60.38 | 65.91 | 68.63 | 42.05 | 60.53 | 45.38 |
| 11 | MTRX | value+pullback | 57.63 | 74.80 | 51.10 | 39.59 | 59.57 | 52.57 | 47.06 |
| 12 | MSFT | value+pullback | 57.01 | 64.66 | 51.43 | 58.40 | 59.03 | 50.45 | 59.57 |
| 13 | AAPL | value+pullback | 55.18 | 60.39 | 46.93 | 62.85 | 50.63 | 54.19 | 51.08 |
| 14 | TV | value+pullback | 55.02 | 61.08 | 49.08 | 48.91 | 61.31 | 54.78 | 50.44 |
| 15 | VOR | value+pullback | 53.32 | 58.69 | 54.93 | 40.17 | 47.43 | 56.07 | 53.35 |
| 16 | PARR | value | 53.09 | 71.16 | 62.82 | 75.36 | 71.83 | 66.28 | 79.32 |
| 17 | SM | value | 52.69 | 77.15 | 56.63 | 80.80 | 48.22 | 63.01 | 67.19 |
| 18 | TNK | value | 52.17 | 67.78 | 30.95 | 70.94 | 72.52 | 69.74 | 72.33 |
| 19 | MAGN | value | 51.93 | 73.82 | 34.23 | 60.00 | 71.76 | 68.04 | 52.05 |
| 20 | IHS | value | 51.65 | 69.61 | 34.54 | 61.75 | 83.14 | 65.94 | 58.64 |
