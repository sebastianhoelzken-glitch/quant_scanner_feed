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

- **EUROPE:** 80.9/100
- **OTHER:** 70.1/100
- **US:** 82.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AKER.OL  | Aker ASA                                               | EUROPE   |                9.63 |             81.57 |         87.38 |         78.46 |          82.73 |        80.41 |           97.52 |             79.2  |             54.44 |         3.63 |             73.32 | short              |               -0.72 |                   nan |                  nan |
|      2 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.51 |             78.69 |         79.11 |         78.5  |          78.88 |        73.36 |           73.91 |             71.91 |             61.57 |         6.77 |             85.65 | short              |                4.16 |                   nan |                  nan |
|      3 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.16 |             72.85 |         72.3  |         66.45 |          73.41 |        79.61 |           92.79 |             59.42 |             80.8  |         2.33 |             78.65 | long               |                0.5  |                   nan |                  nan |
|      4 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.5  |             69.47 |         77.67 |         67.87 |          69.01 |        69.94 |           70.94 |             65.41 |             62.95 |         5.1  |             84.89 | short              |               -2.85 |                   nan |                  nan |
|      5 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              618.17 |             69.41 |         61.88 |         67.91 |          75.45 |        70.91 |           87.42 |             75.39 |             30.88 |         6.03 |             89.58 | medium             |                5.46 |                   nan |                  nan |
|      6 | AMCX     | AMC Global Media Inc.                                  | US       |                0.43 |             68.94 |         72.29 |         71.62 |          66.27 |        62.15 |           42.97 |             70.41 |             82.89 |         7.59 |             85.14 | short              |                2.26 |                   nan |                  nan |
|      7 | SM       | SM Energy Company                                      | US       |                6.61 |             67.24 |         66.27 |         60.84 |          68.21 |        72.65 |           79.13 |             52.09 |             77.86 |         6.67 |             87.81 | long               |               -1.47 |                   nan |                  nan |
|      8 | DAC      | Danaos Corporation                                     | OTHER    |                2.24 |             66.9  |         68.87 |         65.2  |          67.63 |        66.16 |           74.57 |             54.81 |             51.89 |         3.32 |             83.35 | short              |                1.32 |                   nan |                  nan |
|      9 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.48 |             66.64 |         68.94 |         64.33 |          70.07 |        59.63 |           73.08 |             78.72 |             17.04 |         6.31 |             61.74 | medium             |               -0.26 |                   nan |                  nan |
|     10 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.58 |             66.63 |         73.15 |         69.13 |          64.14 |        59.85 |           61.68 |             54.7  |             57.4  |         7.3  |             75.57 | short              |                1.17 |                   nan |                  nan |
|     11 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              173.84 |             66.56 |         78.45 |         68.99 |          64.13 |        61.03 |           73.07 |             72.15 |             33.58 |         4.69 |             89.69 | short              |               -1.06 |                   nan |                  nan |
|     12 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.17 |         69.63 |         70.09 |          60.71 |        56.14 |           59.63 |             55.17 |             41    |         5.95 |             79.32 | swing              |                0.25 |                   nan |                  nan |
|     13 | WKC      | World Kinect Corporation                               | US       |                1.65 |             64.18 |         60.74 |         71.12 |          67.61 |        58.87 |           46.33 |             72.16 |             54.29 |         4.93 |             84.31 | swing              |                0.69 |                   nan |                  nan |
|     14 | HQL      | HQL                                                    | US       |                0.56 |             63.91 |         74.1  |         68.38 |          59.44 |        47.1  |           47.82 |            nan    |             24.53 |         2.29 |             59.6  | short              |               -0.64 |                   nan |                  nan |
|     15 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.63 |             63.59 |         69.36 |         65.2  |          61.97 |        59.8  |           67.19 |             78.96 |             37.98 |         2.93 |             64.78 | short              |               -0.85 |                   nan |                  nan |
|     16 | SLDE     | Slide Insurance Holdings, Inc.                         | US       |                2.17 |             63.56 |         63.31 |         64.09 |          63.8  |        61.81 |           76.03 |             54.14 |             40.12 |         5.74 |             80.19 | swing              |                1.73 |                   nan |                  nan |
|     17 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.6  |             63.34 |         56.68 |         55.67 |          69.99 |        82.25 |           91.54 |             64.54 |             83.05 |         6.48 |             82.86 | long               |              nan    |                   nan |                  nan |
|     18 | CNC      | Centene Corporation                                    | US       |               28.47 |             63.33 |         64.08 |         62.57 |          65.61 |        60.16 |           50.47 |             57.33 |             64.79 |         5.86 |             88.46 | medium             |               -0.45 |                   nan |                  nan |
|     19 | CEF      | CEF                                                    | OTHER    |                7.15 |             63.24 |         72.75 |         39.73 |          53.73 |        84.29 |          nan    |            nan    |            100    |         5.28 |             55.57 | long               |               -2.49 |                   nan |                  nan |
|     20 | EVT      | Eaton Vance Tax-Advantaged Dividend Income Fund        | US       |                1.9  |             63.19 |         69.23 |         67.32 |          59.06 |        50.92 |           48.9  |             78.96 |             29.89 |         2.15 |             62.78 | short              |               -0.52 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                           | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                  | EUROPE   |                3.16 |                  72.82 |                    75.58 |                 78.26 |              74.43 |                89.2  |                   10.8  |           92.79 |             59.42 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc. | US       |                0.6  |                  70.16 |                    73.09 |                 76.01 |              71.21 |                79.16 |                   20.84 |           91.54 |             64.54 |       0.177 |         nan |       nan |        4.33 |         2.82 |          5.26 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0QXR.IL  | Stellantis N.V.                | OTHER    |               25.94 |                  73.28 |                    72.46 |                 72.52 |              72.26 |                68.17 |                   31.83 |           73.75 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            4 | AKER.OL  | Aker ASA                       | EUROPE   |                9.63 |                  63.04 |                    71.97 |                 75.78 |              66.7  |                74.36 |                   25.64 |           97.52 |             79.2  |       0.115 |         nan |       nan |        5.23 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | MOMO     | Hello Group Inc.               | OTHER    |                0.73 |                  76.41 |                    71.9  |                 70.86 |              74.3  |                76.15 |                   23.85 |           66.72 |             55.85 |       0.576 |         nan |       nan |       -5.14 |         5.34 |          8.55 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            6 | SM       | SM Energy Company              | US       |                6.61 |                  73.62 |                    71.04 |                 70.55 |              70.01 |                65.52 |                   34.48 |           79.13 |             52.09 |       0.193 |         nan |       nan |        4.53 |         4.36 |          5.68 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            7 | 0P6O.IL  | Volkswagen AG                  | OTHER    |               40.41 |                  64.17 |                    69.73 |                 71.76 |              67.02 |                78.43 |                   21.57 |           81.41 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            8 | MAGN     | Magnera Corporation            | US       |                0.38 |                  73.82 |                    69.18 |                 69.24 |              72.6  |                68.03 |                   31.97 |           60    |             72.1  |       0.53  |         nan |       nan |        6.42 |         7.49 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            9 | PARR     | Par Pacific Holdings, Inc.     | US       |                3.51 |                  67.84 |                    68.55 |                 70.01 |              68.29 |                68.08 |                   31.92 |           73.91 |             71.91 |       0.02  |         nan |       nan |        3.81 |         6.11 |          4.74 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | VOW3.DE  | Volkswagen AG                  | EUROPE   |               36.56 |                  77.29 |                    68.53 |                 65.66 |              70.7  |                63.17 |                   36.83 |           63.54 |             36.8  |       0.386 |         nan |       nan |       13.79 |         3.11 |          6.99 |        0.7  |                 nan |              nan |                  12 |                  0.63 |
|           11 | SAP.DE   | SAP SE                         | EUROPE   |              202.42 |                  65    |                    68.02 |                 67.91 |              65.06 |                72.81 |                   27.19 |           80.05 |             51.47 |       0.045 |         nan |       nan |       17.17 |        20.96 |         26.22 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|           12 | AMCX     | AMC Global Media Inc.          | US       |                0.43 |                  73.8  |                    67.69 |                 65.22 |              73.02 |                71.38 |                   28.62 |           42.97 |             70.41 |       2.01  |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           13 | IHS      | IHS Holding Limited            | OTHER    |                2.45 |                  70.95 |                    67.67 |                 68.3  |              70.53 |                61.83 |                   38.17 |           58.51 |             83.17 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | NWL.MI   | NewPrinces S.p.A.              | EUROPE   |                0.69 |                  68.02 |                    66.34 |                 67.46 |              67.39 |                70.6  |                   29.4  |           70.78 |             57.11 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           15 | AVGO     | Broadcom Inc.                  | US       |             1741.87 |                  57.41 |                    66.22 |                 66.8  |              61.83 |                77.8  |                   22.2  |           78.23 |             64.9  |       0.014 |         nan |       nan |       48.11 |        21.62 |         70.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           16 | RCI      | Rogers Communications Inc.     | OTHER    |               16.9  |                  60.52 |                    65.27 |                 66.65 |              59.18 |                63.02 |                   36.98 |           94.29 |             42.62 |       0.28  |         nan |       nan |        7.28 |        10.34 |          4.41 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           17 | UNIT     | Uniti Group Inc.               | US       |                2.05 |                  73.45 |                    65.24 |                 63.33 |              65.94 |                55.28 |                   44.72 |           69.33 |             31.03 |      -0.109 |         nan |       nan |        9.02 |       -13.69 |          2.46 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           18 | GSL      | Global Ship Lease Inc New      | OTHER    |                1.32 |                  66.96 |                    65.16 |                 65.4  |              64.9  |                70.96 |                   29.04 |           75    |             39.19 |       0.085 |         nan |       nan |        3.57 |         4.77 |          4.08 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           19 | PKX      | POSCO Holdings Inc.            | OTHER    |               14.9  |                  60.34 |                    64.62 |                 67.95 |              61.25 |                68.85 |                   31.15 |           89.41 |             54.1  |     nan     |         nan |       nan |        3.7  |         9.85 |         28.4  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           20 | TNK      | Teekay Tankers Ltd.            | OTHER    |                2.5  |                  62.49 |                    64.24 |                 65.93 |              63.85 |                68.42 |                   31.58 |           70.94 |             65.41 |       0.078 |         nan |       nan |        3.2  |         9.1  |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.16 |                  72.82 |                    75.58 |                 78.26 |              74.43 |                89.2  |                   10.8  |           92.79 |             59.42 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.6  |                  70.16 |                    73.09 |                 76.01 |              71.21 |                79.16 |                   20.84 |           91.54 |             64.54 |       0.177 |         nan |       nan |        4.33 |         2.82 |          5.26 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.63 |                  63.04 |                    71.97 |                 75.78 |              66.7  |                74.36 |                   25.64 |           97.52 |             79.2  |       0.115 |         nan |       nan |        5.23 |        54.32 |          3.74 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            3 | 0QXR.IL  | Stellantis N.V.                                      | OTHER    |               25.94 |                  73.28 |                    72.46 |                 72.52 |              72.26 |                68.17 |                   31.83 |           73.75 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.71 |                 nan |              nan |                   9 |                  0.47 |
|            7 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               40.41 |                  64.17 |                    69.73 |                 71.76 |              67.02 |                78.43 |                   21.57 |           81.41 |            nan    |       0.428 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.7  |                 nan |              nan |                   9 |                  0.47 |
|            5 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.41 |                    71.9  |                 70.86 |              74.3  |                76.15 |                   23.85 |           66.72 |             55.85 |       0.576 |         nan |       nan |       -5.14 |         5.34 |          8.55 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            6 | SM       | SM Energy Company                                    | US       |                6.61 |                  73.62 |                    71.04 |                 70.55 |              70.01 |                65.52 |                   34.48 |           79.13 |             52.09 |       0.193 |         nan |       nan |        4.53 |         4.36 |          5.68 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            9 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.51 |                  67.84 |                    68.55 |                 70.01 |              68.29 |                68.08 |                   31.92 |           73.91 |             71.91 |       0.02  |         nan |       nan |        3.81 |         6.11 |          4.74 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | MAGN     | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    69.18 |                 69.24 |              72.6  |                68.03 |                   31.97 |           60    |             72.1  |       0.53  |         nan |       nan |        6.42 |         7.49 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|           13 | IHS      | IHS Holding Limited                                  | OTHER    |                2.45 |                  70.95 |                    67.67 |                 68.3  |              70.53 |                61.83 |                   38.17 |           58.51 |             83.17 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           19 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.9  |                  60.34 |                    64.62 |                 67.95 |              61.25 |                68.85 |                   31.15 |           89.41 |             54.1  |     nan     |         nan |       nan |        3.7  |         9.85 |         28.4  |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           11 | SAP.DE   | SAP SE                                               | EUROPE   |              202.42 |                  65    |                    68.02 |                 67.91 |              65.06 |                72.81 |                   27.19 |           80.05 |             51.47 |       0.045 |         nan |       nan |       17.17 |        20.96 |         26.22 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|           14 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  68.02 |                    66.34 |                 67.46 |              67.39 |                70.6  |                   29.4  |           70.78 |             57.11 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           15 | AVGO     | Broadcom Inc.                                        | US       |             1741.87 |                  57.41 |                    66.22 |                 66.8  |              61.83 |                77.8  |                   22.2  |           78.23 |             64.9  |       0.014 |         nan |       nan |       48.11 |        21.62 |         70.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           16 | RCI      | Rogers Communications Inc.                           | OTHER    |               16.9  |                  60.52 |                    65.27 |                 66.65 |              59.18 |                63.02 |                   36.98 |           94.29 |             42.62 |       0.28  |         nan |       nan |        7.28 |        10.34 |          4.41 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           20 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.5  |                  62.49 |                    64.24 |                 65.93 |              63.85 |                68.42 |                   31.58 |           70.94 |             65.41 |       0.078 |         nan |       nan |        3.2  |         9.1  |          4.89 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|           10 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.56 |                  77.29 |                    68.53 |                 65.66 |              70.7  |                63.17 |                   36.83 |           63.54 |             36.8  |       0.386 |         nan |       nan |       13.79 |         3.11 |          6.99 |        0.7  |                 nan |              nan |                  12 |                  0.63 |
|           23 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  60.01 |                    63.22 |                 65.64 |              60.52 |                71.9  |                   28.1  |           85.13 |             43.76 |       0.093 |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  12 |                  0.63 |
|           18 | GSL      | Global Ship Lease Inc New                            | OTHER    |                1.32 |                  66.96 |                    65.16 |                 65.4  |              64.9  |                70.96 |                   29.04 |           75    |             39.19 |       0.085 |         nan |       nan |        3.57 |         4.77 |          4.08 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           12 | AMCX     | AMC Global Media Inc.                                | US       |                0.43 |                  73.8  |                    67.69 |                 65.22 |              73.02 |                71.38 |                   28.62 |           42.97 |             70.41 |       2.01  |         nan |       nan |        6.98 |         4.38 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | INDU-C.ST | AB Industrivärden (publ)          | EUROPE   |               20.56 |                     0.07 |    -0.05 |      0    |                  79.69 |                        70.56 |         47.36 |         60.25 |          67.6  |        65.16 |           83.03 |             79.2  |         2.47 |
|               2 | INDU-A.ST | AB Industrivärden (publ)          | EUROPE   |               20.66 |                     0.07 |    -0.06 |     -0.01 |                  78.19 |                        69.61 |         42.95 |         58.8  |          66.86 |        63.44 |           83.03 |             79.2  |         2.61 |
|               3 | ALL       | The Allstate Corporation          | US       |               56.58 |                     0.06 |    -0.06 |      0.07 |                  84.87 |                        68.53 |         59.52 |         65.55 |          62.27 |        56.24 |           68.32 |             62.39 |         3.04 |
|               4 | HRTG      | Heritage Insurance Holdings, Inc. | US       |                0.85 |                     0.06 |    -0.06 |      0.24 |                  83.9  |                        67.83 |         69.63 |         70.09 |          60.71 |        56.14 |           59.63 |             55.17 |         5.95 |
|               5 | AMZN      | Amazon.com, Inc.                  | US       |             2482.14 |                     0.07 |    -0.03 |      0.06 |                  71.66 |                        67.8  |         62.66 |         57.35 |          62.53 |        62.06 |           81.16 |             63.25 |         5.78 |
|               6 | IRWD      | Ironwood Pharmaceuticals, Inc.    | US       |                0.6  |                     0.06 |    -0.03 |      0.07 |                  73.88 |                        67.41 |         56.68 |         55.67 |          69.99 |        82.25 |           91.54 |             64.54 |         6.48 |
|               7 | WKC       | World Kinect Corporation          | US       |                1.65 |                     0.07 |     0    |      0.01 |                  58.73 |                        64.46 |         60.74 |         71.12 |          67.61 |        58.87 |           46.33 |             72.16 |         4.93 |
|               8 | CLW       | Clearwater Paper Corporation      | US       |                0.31 |                     0.06 |    -0.04 |      0.34 |                  79.68 |                        64.02 |         67.32 |         63.93 |          50.72 |        47.09 |           45.98 |             61.37 |         6.83 |
|               9 | SLDE      | Slide Insurance Holdings, Inc.    | US       |                2.17 |                     0.03 |     0    |      0.04 |                  56.94 |                        63.91 |         63.31 |         64.09 |          63.8  |        61.81 |           76.03 |             54.14 |         5.74 |
|              10 | MSFT      | Microsoft Corporation             | US       |             3185.48 |                     0.02 |    -0.01 |      0.23 |                  53.78 |                        63.49 |         71.1  |         64.87 |          54.65 |        52.74 |           54.76 |             59.45 |         5.75 |
|              11 | LNC       | Lincoln National Corporation      | US       |                7.41 |                     0.05 |    -0.04 |      0.07 |                  80.56 |                        63.18 |         64.04 |         66.6  |          57.83 |        56.58 |           44.18 |             59.78 |         4.71 |
|              12 | PKX       | POSCO Holdings Inc.               | OTHER    |               14.9  |                     0.03 |     0.01 |      0.11 |                  50.85 |                        62.55 |         57.86 |         37.31 |          51.88 |        65.72 |           89.41 |             54.1  |         6.13 |
|              13 | DSX       | Diana Shipping Inc.               | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  55.47 |                        62.2  |         66.43 |         50.46 |          56.23 |        60.67 |           60.31 |             57.36 |         4.63 |
|              14 | HMC       | Honda Motor Company, Ltd.         | OTHER    |               35.04 |                     0.02 |     0.01 |      0.08 |                  46.12 |                        62.18 |         61.94 |         59.8  |          55.04 |        59.7  |           67.06 |             72.52 |         3.85 |
|              15 | YPF       | YPF Sociedad Anónima              | OTHER    |               16.54 |                     0.08 |    -0.02 |      0    |                  64.19 |                        61.96 |         45.3  |         59.35 |          67.35 |        66.43 |           64.49 |             65.02 |         5.73 |
|              16 | MA        | Mastercard Incorporated           | US       |              425.83 |                     0.03 |    -0.03 |      0.02 |                  62.23 |                        61    |         55.06 |         56.6  |          52.1  |        49.45 |           71.6  |             60.31 |         3.22 |
|              17 | V         | Visa Inc.                         | US       |              583.68 |                     0.02 |    -0.02 |     -0.01 |                  59.45 |                        60.25 |         51.01 |         57.34 |          53.72 |        49.42 |           68.4  |             59.88 |         2.91 |
|              18 | AMD       | Advanced Micro Devices, Inc.      | US       |              699.81 |                     0.11 |     0.01 |     -0.01 |                  36.74 |                        59.55 |         47.59 |         59.84 |          70.51 |        60.3  |           64.84 |             74.36 |         7.25 |
|              19 | KELYA     | Kelly Services, Inc.              | US       |                0.47 |                     0.03 |     0.01 |      0.02 |                  50.83 |                        59.42 |         62.36 |         73.85 |          60.33 |        50.11 |           25.95 |             64.55 |         6.31 |
|              20 | GSL       | Global Ship Lease Inc New         | OTHER    |                1.32 |                     0.05 |    -0.01 |      0.02 |                  71.23 |                        59.35 |         55.58 |         54.28 |          62.67 |        69.5  |           75    |             39.19 |         3.78 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4740.68 |             65.49 |         68.95 |         58.53 |          63.78 |        67.2  |           92.75 |             61.15 |             39    |         5.6  |             89.54 | short              |               -0.05 |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.88 |             62.26 |         62.05 |         62.46 |          59.24 |        65.09 |           55.86 |             49.87 |             79.92 |         8.41 |             85.47 | long               |               -0.93 |                   nan |                  nan |
|    nan | ZEAL.CO  | Zealand Pharma A/S           | EUROPE   |                3.11 |             50.72 |         61.31 |         41.26 |          45.29 |        56.15 |           70.63 |             45.85 |             56.99 |         8.5  |             81.67 | short              |                1.89 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.16 |             42.73 |         27.6  |         37.23 |          48.23 |        63.82 |           77.48 |             49.15 |             77.68 |         8.5  |             85.99 | long               |                0.72 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             41.55 |         53.13 |         40.85 |          36.74 |        42.25 |           28.96 |             29.2  |             63.85 |         4.52 |             74.95 | short              |                0.86 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.92 |             38.39 |         27.69 |         34.33 |          42.45 |        53.91 |           50.26 |             47.97 |             77.74 |         6.26 |             78.58 | long               |               -1.91 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               33.96 |             38.2  |         32.89 |         34.91 |          41.5  |        43.95 |           43.93 |             51.3  |             50.09 |         8.5  |             86.72 | long               |              -15.53 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.31 |             37.2  |         28.82 |         33.76 |          40.64 |        53.53 |           47.64 |             42.03 |             85.58 |         7.21 |             78.43 | long               |               -2.76 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.62 |             35.78 |         30.24 |         29.35 |          41.32 |        58.38 |           72    |             25.61 |             75.22 |         4.89 |             81.52 | long               |               -2.76 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             35.46 |         35.77 |         21.23 |          35.15 |        45.77 |           64.09 |             19.67 |             39.33 |         9.1  |             77.55 | long               |               -3.34 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.13 |         38.51 |         22.78 |          29.24 |        37.02 |           38.42 |             38.36 |             48.67 |         7.12 |             75.4  | short              |               -0.79 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.87 |             25.91 |         57.86 |         23.23 |          21.5  |        28.6  |           21.62 |             27.6  |             49.43 |         7.77 |             75.24 | short              |               -2.07 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.42 |             21.74 |         26.2  |         20.29 |          21.14 |        22.34 |           19.42 |             37.39 |             24.95 |         6.91 |             76.61 | short              |               -7.55 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.96
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.95
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.92

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
- Excluded by hard/data filters: **849**
- Event watch (otherwise eligible): **13**
- Final eligible: **138**
- Eligible change vs previous stored run: **+34**

Top exclusion categories:
- market_cap: 789
- liquidity: 208
- price: 137
- price_history: 25
- data_confidence: 24
- duplicate_listing: 3
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 1 | 4 |  | 3 | 2 | main,value,quality_value |
| PARR | 2 | 9 |  | 8 | 2 | main,value,quality_value |
| BION.SW | 3 | 1 |  | 1 | 2 | main,value,quality_value |
| SM | 7 | 6 |  | 7 | 2 | main,value,quality_value |
| IRWD | 17 | 2 | 6 | 2 | 2 | value,pullback,quality_value |
| MAGN | 70 | 8 |  | 9 | 1 | value,quality_value |
| 0QXR.IL | 79 | 3 |  | 4 | 1 | value,quality_value |
| MOMO | 96 | 5 | 34 | 6 | 1 | value,quality_value |
| 0P6O.IL | 111 | 7 |  | 5 | 1 | value,quality_value |
| TNK | 4 | 20 |  | 16 | 1 | main |
| ASML.AS | 5 | 50 |  | 30 | 1 | main |
| AMCX | 6 | 12 |  | 20 | 1 | main |
| DAC | 8 | 35 |  | 25 | 1 | main |
| TWN | 9 |  |  |  | 1 | main |
| RMAX | 10 | 32 |  | 34 | 1 | main |

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
| 1 | IRWD | value+pullback | 75.53 | 70.16 | 73.88 | 91.54 | 64.54 | 79.16 | 63.34 |
| 2 | 0P6O.IL | value+pullback | 71.32 | 64.17 | 76.67 | 81.41 |  | 78.43 | 41.10 |
| 3 | MOMO | value+pullback | 71.21 | 76.41 | 69.84 | 66.72 | 55.85 | 76.15 | 45.88 |
| 4 | VOW3.DE | value+pullback | 68.73 | 77.29 | 78.78 | 63.54 | 36.80 | 63.17 | 37.56 |
| 5 | GSL | value+pullback | 67.26 | 66.96 | 71.23 | 75.00 | 39.19 | 70.96 | 59.12 |
| 6 | IRS | value+pullback | 66.46 | 60.01 | 67.71 | 85.13 | 43.76 | 71.90 | 49.25 |
| 7 | INVA | value+pullback | 65.90 | 58.49 | 69.31 | 80.26 | 38.23 | 75.80 | 41.55 |
| 8 | VOLV-B.ST | value+pullback | 64.57 | 65.37 | 70.20 | 59.18 | 60.18 | 62.58 | 53.55 |
| 9 | PKX | value+pullback | 63.41 | 60.34 | 50.85 | 89.41 | 54.10 | 68.85 | 54.87 |
| 10 | 1VOW3.MI | value+pullback | 62.70 | 65.37 | 68.10 | 63.54 | 37.28 | 64.01 | 39.47 |
| 11 | VOW.DE | value+pullback | 61.95 | 59.95 | 74.35 | 63.54 | 32.95 | 62.75 | 34.64 |
| 12 | AF.PA | value+pullback | 61.66 | 65.41 | 81.65 | 47.06 | 61.84 | 41.89 | 52.69 |
| 13 | YPF | value+pullback | 61.63 | 66.58 | 64.19 | 64.49 | 65.02 | 47.17 | 62.89 |
| 14 | BHF | value+pullback | 61.01 | 68.11 | 61.88 | 51.65 | 44.12 | 64.70 | 45.63 |
| 15 | ALL-PH | value+pullback | 60.68 | 61.60 | 64.44 | 68.32 | 39.87 | 59.27 | 44.77 |
| 16 | SUZ | value+pullback | 60.34 | 57.11 | 65.44 | 63.83 | 47.68 | 62.54 | 37.58 |
| 17 | LEG.DE | value+pullback | 59.97 | 70.50 | 51.00 | 63.33 | 42.33 | 61.71 | 40.01 |
| 18 | BION.SW | value | 59.55 | 72.82 | 33.25 | 92.79 | 59.42 | 89.20 | 72.85 |
| 19 | LNC | value+pullback | 59.00 | 56.82 | 80.56 | 44.18 | 59.78 | 46.06 | 60.93 |
| 20 | MAU.PA | value+pullback | 58.46 | 63.45 | 60.45 | 60.70 | 52.50 | 49.79 | 50.83 |
