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
- **OTHER:** 73.9/100
- **US:** 82.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |             74.08 |         73.64 |         74.53 |          77.67 |        72.4  |           73.91 |             71.73 |             60.14 |         6.79 |             85.65 | medium             |               -0.46 |                   nan |                  nan |
|      2 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |             71.84 |         74.65 |         65.05 |          70.2  |        73.48 |           70.94 |             64.97 |             76.7  |         5.1  |             84.89 | short              |               -0.48 |                   nan |                  nan |
|      3 | SM       | SM Energy Company                                      | US       |                6.68 |             68.26 |         68.64 |         61.95 |          67.88 |        71.39 |           79.13 |             51.85 |             74.29 |         6.73 |             87.81 | long               |               -0.45 |                   nan |                  nan |
|      4 | SU.PA    | Schneider Electric S.E.                                | EUROPE   |              174.38 |             67.96 |         77.54 |         70.44 |          65.49 |        64.05 |           68.84 |             71.99 |             49.15 |         4.66 |             89.69 | short              |                0.35 |                   nan |                  nan |
|      5 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |             67.73 |         66.01 |         54.98 |          69.46 |        81.03 |           91.54 |             64.47 |             78.08 |         6.59 |             82.86 | long               |              nan    |                   nan |                  nan |
|      6 | ASML.AS  | ASML Holding N.V.                                      | EUROPE   |              605.96 |             67.22 |         57.63 |         65.51 |          74.05 |        68.92 |           86.3  |             75.28 |             25.85 |         6.01 |             89.58 | medium             |                3.27 |                   nan |                  nan |
|      7 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.2  |             66.49 |         68.79 |         64.74 |          61.5  |        68.23 |           86.34 |             72.68 |             56.83 |         3.85 |             78.07 | short              |               -0.22 |                   nan |                  nan |
|      8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |             66.45 |         67.28 |         69.68 |          65.62 |        61.79 |           42.97 |             70.26 |             82.89 |         7.62 |             85.14 | swing              |               -0.23 |                   nan |                  nan |
|      9 | RMAX     | RE/MAX Holdings, Inc.                                  | US       |                0.59 |             65.97 |         73.85 |         68.5  |          63.43 |        59.76 |           61.68 |             54.41 |             57.4  |         7.35 |             75.57 | short              |                0.51 |                   nan |                  nan |
|     10 | TWN      | The Taiwan Fund, Inc.                                  | US       |                0.48 |             65.43 |         66.57 |         64.3  |          70.28 |        59.55 |           73.08 |             79.52 |             17.04 |         6.26 |             61.74 | medium             |               -1.47 |                   nan |                  nan |
|     11 | DAC      | Danaos Corporation                                     | OTHER    |                2.2  |             65.22 |         68.78 |         62.65 |          66.11 |        64.33 |           74.57 |             54.68 |             48.48 |         3.3  |             83.35 | short              |               -0.36 |                   nan |                  nan |
|     12 | HRTG     | Heritage Insurance Holdings, Inc.                      | US       |                0.85 |             65.01 |         76.69 |         69.58 |          60.44 |        55.97 |           59.63 |             55.02 |             41.75 |         6    |             79.32 | short              |                0.08 |                   nan |                  nan |
|     13 | LLY      | Eli Lilly and Company                                  | US       |              942.65 |             64.71 |         65.55 |         63.88 |          65.64 |        62.84 |           84.42 |             59.65 |             24.52 |         4.21 |             89.62 | medium             |               -2.5  |                   nan |                  nan |
|     14 | CEF      | CEF                                                    | OTHER    |                7.21 |             64.09 |         73.17 |         40.71 |          55.01 |        84.57 |          nan    |            nan    |            100    |         5.28 |             55.57 | long               |               -1.63 |                   nan |                  nan |
|     15 | HQL      | HQL                                                    | US       |                0.56 |             64.08 |         72.47 |         68.7  |          59.46 |        46.85 |           47.82 |            nan    |             24.53 |         2.26 |             59.6  | short              |               -0.47 |                   nan |                  nan |
|     16 | KELYA    | Kelly Services, Inc.                                   | US       |                0.46 |             63.62 |         67.98 |         75.2  |          59.25 |        49.24 |           19.26 |             64.6  |             67.57 |         6.33 |             85.62 | swing              |               -0.14 |                   nan |                  nan |
|     17 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |             63.35 |         67.04 |         64.86 |          61.85 |        59.66 |           67.19 |             79.77 |             37.98 |         2.91 |             64.78 | short              |               -1.09 |                   nan |                  nan |
|     18 | SAP.DE   | SAP SE                                                 | EUROPE   |              204.94 |             63.17 |         77.22 |         61.05 |          56.5  |        65.29 |           73.48 |             51.34 |             72.95 |         6.5  |             89.13 | short              |                5.02 |                   nan |                  nan |
|     19 | AMZN     | Amazon.com, Inc.                                       | US       |             2497.43 |             62.99 |         63.65 |         59.2  |          63.36 |        62.62 |           81.16 |             63.03 |             36.83 |         5.76 |             89.85 | short              |               -1.13 |                   nan |                  nan |
|     20 | PEO      | Adams Natural Resources Fund, Inc.                     | US       |                0.67 |             62.94 |         72.25 |         64.9  |          60.98 |        53.91 |           62.54 |             79.52 |             19.26 |         2.03 |             68.24 | short              |               -1.03 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |                  67.18 |                    71.42 |                 74.64 |              69.04 |                79.03 |                   20.97 |           91.54 |             64.47 |       0.171 |         nan |       nan |        4.33 |         2.93 |          5.47 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | SAP.DE   | SAP SE                                                 | EUROPE   |              204.94 |                  73.38 |                    70.89 |                 69.27 |              70.19 |                67.9  |                   32.1  |           73.48 |             51.34 |       0.044 |         nan |       nan |       17.17 |        21.22 |         26.54 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|            3 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |                  73.69 |                    70.35 |                 70.89 |              71.86 |                68.34 |                   31.66 |           70.94 |             64.97 |       0.08  |         nan |       nan |        3.2  |         8.87 |          4.77 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            4 | SM       | SM Energy Company                                      | US       |                6.68 |                  72.05 |                    70.14 |                 69.8  |              68.84 |                65.41 |                   34.59 |           79.13 |             51.85 |       0.191 |         nan |       nan |        4.53 |         4.44 |          5.77 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.11 |              72.5  |                67.84 |                   32.16 |           60    |             71.44 |       0.519 |         nan |       nan |        6.42 |         7.64 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            6 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |                  67.07 |                    68.1  |                 69.62 |              67.71 |                68.03 |                   31.97 |           73.91 |             71.73 |       0.021 |         nan |       nan |        3.81 |         5.88 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  69.21 |                    67.96 |                 69.4  |              66.86 |                70.19 |                   29.81 |           84.58 |             43.9  |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  73.8  |                    67.67 |                 65.19 |              73    |                71.32 |                   28.68 |           42.97 |             70.26 |       2.071 |         nan |       nan |        6.98 |         4.25 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|            9 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.46 |                    67.08 |                 67.59 |              70.07 |                61.27 |                   38.73 |           56.9  |             83.15 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.32 |                 67.44 |              67.37 |                70.52 |                   29.48 |           70.78 |             57.03 |       0.969 |         nan |       nan |        5.3  |      -121.42 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | AVGO     | Broadcom Inc.                                          | US       |             1714.69 |                  57.41 |                    66.19 |                 66.76 |              61.8  |                77.79 |                   22.21 |           78.23 |             64.68 |       0.014 |         nan |       nan |       48.11 |        21.3  |         69.46 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           12 | UNIT     | Uniti Group Inc.                                       | US       |                2    |                  73.45 |                    64.9  |                 62.97 |              65.55 |                53.45 |                   46.55 |           69.33 |             30.46 |      -0.112 |         nan |       nan |        9.02 |       -13.39 |          2.48 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           13 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |                  58.69 |                    64.63 |                 66.24 |              63.51 |                73.74 |                   26.26 |           67.19 |             79.77 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           14 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.77 |                  59.32 |                    64.51 |                 65.98 |              58.21 |                62.87 |                   37.13 |           94.29 |             41.88 |     nan     |         nan |       nan |        7.28 |        10.28 |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|           15 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.29 |                  65.09 |                    64.06 |                 64.45 |              63.48 |                70.86 |                   29.14 |           75    |             38.56 |       0.087 |         nan |       nan |        3.57 |         4.65 |          4.02 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           16 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.96 |                  61.35 |                    63.91 |                 66.76 |              61.12 |                64.17 |                   35.83 |           85.75 |             53.93 |     nan     |         nan |       nan |        3.7  |         9.9  |         28.69 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           17 | FVRR     | Fiverr International Ltd.                              | OTHER    |                0.27 |                  76.82 |                    63.74 |                 59.97 |              66.29 |                49.65 |                   50.35 |           59.52 |             20.45 |       0.27  |         nan |       nan |        1.25 |         6.61 |         10.69 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|           18 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  60.08 |                    62.52 |                 64.15 |              60.68 |                75.68 |                   24.32 |           80.26 |             37.97 |       0.073 |         nan |       nan |        6.43 |         9.42 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           19 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.2  |                  49.84 |                    62.1  |                 67.1  |              57.78 |                81.23 |                   18.77 |           86.34 |             72.68 |     nan     |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   7 |                  0.37 |
|           20 | CNC      | Centene Corporation                                    | US       |               28.7  |                  67.05 |                    61.93 |                 58.85 |              62.97 |                49.73 |                   50.27 |           50.47 |             57.37 |       0.291 |         nan |       nan |        4.84 |        12.65 |        nan    |        1.17 |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.                         | US       |                0.62 |                  67.18 |                    71.42 |                 74.64 |              69.04 |                79.03 |                   20.97 |           91.54 |             64.47 |       0.171 |         nan |       nan |        4.33 |         2.93 |          5.47 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.43 |                  73.69 |                    70.35 |                 70.89 |              71.86 |                68.34 |                   31.66 |           70.94 |             64.97 |       0.08  |         nan |       nan |        3.2  |         8.87 |          4.77 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            4 | SM       | SM Energy Company                                      | US       |                6.68 |                  72.05 |                    70.14 |                 69.8  |              68.84 |                65.41 |                   34.59 |           79.13 |             51.85 |       0.191 |         nan |       nan |        4.53 |         4.44 |          5.77 |        0.55 |                 nan |              nan |                  12 |                  0.63 |
|            6 | PARR     | Par Pacific Holdings, Inc.                             | US       |                3.38 |                  67.07 |                    68.1  |                 69.62 |              67.71 |                68.03 |                   31.97 |           73.91 |             71.73 |       0.021 |         nan |       nan |        3.81 |         5.88 |          4.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima   | OTHER    |                1.07 |                  69.21 |                    67.96 |                 69.4  |              66.86 |                70.19 |                   29.81 |           84.58 |             43.9  |     nan     |         nan |       nan |        3.93 |       160.99 |          4.7  |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            2 | SAP.DE   | SAP SE                                                 | EUROPE   |              204.94 |                  73.38 |                    70.89 |                 69.27 |              70.19 |                67.9  |                   32.1  |           73.48 |             51.34 |       0.044 |         nan |       nan |       17.17 |        21.22 |         26.54 |        1.79 |                 nan |              nan |                  12 |                  0.63 |
|            5 | MAGN     | Magnera Corporation                                    | US       |                0.38 |                  73.82 |                    69.09 |                 69.11 |              72.5  |                67.84 |                   32.16 |           60    |             71.44 |       0.519 |         nan |       nan |        6.42 |         7.64 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|            9 | IHS      | IHS Holding Limited                                    | OTHER    |                2.44 |                  70.46 |                    67.08 |                 67.59 |              70.07 |                61.27 |                   38.73 |           56.9  |             83.15 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                                      | EUROPE   |                0.69 |                  68.02 |                    66.32 |                 67.44 |              67.37 |                70.52 |                   29.48 |           70.78 |             57.03 |       0.969 |         nan |       nan |        5.3  |      -121.42 |          2.13 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           19 | HMC      | Honda Motor Company, Ltd.                              | OTHER    |               35.2  |                  49.84 |                    62.1  |                 67.1  |              57.78 |                81.23 |                   18.77 |           86.34 |             72.68 |     nan     |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   7 |                  0.37 |
|           16 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.96 |                  61.35 |                    63.91 |                 66.76 |              61.12 |                64.17 |                   35.83 |           85.75 |             53.93 |     nan     |         nan |       nan |        3.7  |         9.9  |         28.69 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                                          | US       |             1714.69 |                  57.41 |                    66.19 |                 66.76 |              61.8  |                77.79 |                   22.21 |           78.23 |             64.68 |       0.014 |         nan |       nan |       48.11 |        21.3  |         69.46 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           13 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.62 |                  58.69 |                    64.63 |                 66.24 |              63.51 |                73.74 |                   26.26 |           67.19 |             79.77 |       0.027 |         nan |       nan |      nan    |       nan    |          3.81 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           14 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.77 |                  59.32 |                    64.51 |                 65.98 |              58.21 |                62.87 |                   37.13 |           94.29 |             41.88 |     nan     |         nan |       nan |        7.28 |        10.28 |          4.38 |        0.86 |                 nan |              nan |                  10 |                  0.53 |
|            8 | AMCX     | AMC Global Media Inc.                                  | US       |                0.42 |                  73.8  |                    67.67 |                 65.19 |              73    |                71.32 |                   28.68 |           42.97 |             70.26 |       2.071 |         nan |       nan |        6.98 |         4.25 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           15 | GSL      | Global Ship Lease Inc New                              | OTHER    |                1.29 |                  65.09 |                    64.06 |                 64.45 |              63.48 |                70.86 |                   29.14 |           75    |             38.56 |       0.087 |         nan |       nan |        3.57 |         4.65 |          4.02 |        0.87 |                 nan |              nan |                   9 |                  0.47 |
|           18 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  60.08 |                    62.52 |                 64.15 |              60.68 |                75.68 |                   24.32 |           80.26 |             37.97 |       0.073 |         nan |       nan |        6.43 |         9.42 |          4.83 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|          nan | UTG      | Reaves Utility Income Fund                             | US       |                3.17 |                  56.83 |                    61.47 |                 63.12 |              60.31 |                63.56 |                   36.44 |           64.33 |             79.52 |       0.003 |         nan |       nan |      nan    |       nan    |          2.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | UNIT     | Uniti Group Inc.                                       | US       |                2    |                  73.45 |                    64.9  |                 62.97 |              65.55 |                53.45 |                   46.55 |           69.33 |             30.46 |      -0.112 |         nan |       nan |        9.02 |       -13.39 |          2.48 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           34 | ORC      | Orchid Island Capital, Inc.                            | US       |                1.14 |                  53.23 |                    59.53 |                 62.95 |              54.62 |                68.98 |                   31.02 |           91.35 |             38.75 |     nan     |         nan |       nan |      nan    |         6.4  |          3.78 |      nan    |                 nan |              nan |                   7 |                  0.37 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                     | US       |             2497.43 |                     0.06 |    -0.02 |      0.05 |                  74.14 |                        68.63 |         63.65 |         59.2  |          63.36 |        62.62 |           81.16 |             63.03 |         5.76 |
|               2 | ALL      | The Allstate Corporation                             | US       |               56.04 |                     0.07 |    -0.03 |      0.07 |                  71.17 |                        66.02 |         59.82 |         64.76 |          61.8  |        55.54 |           68.32 |             62    |         3.07 |
|               3 | CLW      | Clearwater Paper Corporation                         | US       |                0.31 |                     0.05 |    -0.03 |      0.43 |                  77.38 |                        65.28 |         69.18 |         64.04 |          51.86 |        51.6  |           49.66 |             60.99 |         6.88 |
|               4 | SLDE     | Slide Insurance Holdings, Inc.                       | US       |                2.12 |                     0.05 |     0.01 |      0.06 |                  66.69 |                        65.25 |         63.85 |         61.14 |          61.1  |        60.79 |           76.03 |             54.13 |         5.83 |
|               5 | WKC      | World Kinect Corporation                             | US       |                1.64 |                     0.08 |    -0.04 |      0    |                  65.5  |                        64.93 |         56.51 |         70.21 |          67.09 |        58.26 |           46.33 |             71.56 |         4.92 |
|               6 | DAC      | Danaos Corporation                                   | OTHER    |                2.2  |                     0.02 |     0.01 |      0.09 |                  48.73 |                        64.81 |         68.78 |         62.65 |          66.11 |        64.33 |           74.57 |             54.68 |         3.3  |
|               7 | MSFT     | Microsoft Corporation                                | US       |             3167.57 |                     0.03 |     0.01 |      0.24 |                  50.49 |                        63.94 |         73.01 |         63.04 |          53.15 |        51.96 |           54.76 |             59.41 |         5.76 |
|               8 | AMCX     | AMC Global Media Inc.                                | US       |                0.42 |                     0.02 |    -0.02 |      0.11 |                  57.98 |                        62.67 |         67.28 |         69.68 |          65.62 |        61.79 |           42.97 |             70.26 |         7.62 |
|               9 | DSX      | Diana Shipping Inc.                                  | OTHER    |                0.26 |                     0.07 |    -0.07 |      0.13 |                  83.06 |                        62.47 |         58.74 |         46.08 |          54.63 |        59.38 |           60.31 |             57.18 |         4.63 |
|              10 | LNC      | Lincoln National Corporation                         | US       |                7.31 |                     0.06 |    -0.06 |      0.08 |                  84.16 |                        62.4  |         63.67 |         64.1  |          56.43 |        56.55 |           44.18 |             59.3  |         4.73 |
|              11 | AVGO     | Broadcom Inc.                                        | US       |             1714.69 |                     0.03 |    -0.01 |      0.06 |                  55.29 |                        62.3  |         57.33 |         53.19 |          61.24 |        61.52 |           78.23 |             64.68 |         6.18 |
|              12 | MA       | Mastercard Incorporated                              | US       |              424.76 |                     0.03 |    -0.02 |      0.05 |                  61.17 |                        61.46 |         57.8  |         55.75 |          51.2  |        48.96 |           71.6  |             60.41 |         3.22 |
|              13 | V        | Visa Inc.                                            | US       |              581.31 |                     0.03 |    -0.02 |      0.01 |                  60.82 |                        61.08 |         53.91 |         57.37 |          53.93 |        49.55 |           68.4  |             63.94 |         2.91 |
|              14 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.61 |                     0.07 |     0    |     -0.03 |                  60.61 |                        60.66 |         45.97 |         58.01 |          65.8  |        62.17 |           64.49 |             64.42 |         5.1  |
|              15 | KELYA    | Kelly Services, Inc.                                 | US       |                0.46 |                     0.04 |     0.01 |      0.08 |                  59.78 |                        60.11 |         67.98 |         75.2  |          59.25 |        49.24 |           19.26 |             64.6  |         6.33 |
|              16 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0.01 |                  47.53 |                        58.44 |         52.55 |         56.26 |          57.78 |        57.1  |           56.28 |             79.52 |         1.88 |
|              17 | GOOGL    | Alphabet Inc.                                        | US       |             3639.61 |                     0.09 |    -0.05 |     -0.07 |                  64.17 |                        57.92 |         40.81 |         42.79 |          58.98 |        59.11 |           81.74 |             70.34 |         4.93 |
|              18 | LYFT     | Lyft, Inc.                                           | US       |                5.44 |                     0.05 |     0.01 |      0.02 |                  68.9  |                        57.1  |         56.66 |         52.05 |          50.89 |        56.08 |           52.48 |             52.89 |         7.99 |
|              19 | GSL      | Global Ship Lease Inc New                            | OTHER    |                1.29 |                     0.07 |    -0.03 |      0    |                  69.82 |                        56.05 |         48.75 |         49.58 |          60.59 |        67.91 |           75    |             38.56 |         3.77 |
|              20 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                     0.06 |    -0.02 |     -0.05 |                  70.61 |                        56.03 |         39.47 |         43.88 |          53.56 |        63.68 |           84.58 |             43.9  |         4.18 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4701.84 |             64.44 |         65.41 |         57.81 |          63.48 |        66.66 |           92.75 |             60.98 |             39    |         5.59 |             89.54 | long               |               -1.1  |                   nan |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.89 |             63.08 |         61.27 |         64.47 |          61.69 |        65.64 |           55.86 |             49.86 |             79.92 |         8.47 |             85.47 | long               |               -0.11 |                   nan |                  nan |
|    nan | JD       | JD.com, Inc.                 | OTHER    |               36.98 |             54.16 |         59.44 |         51.6  |          52.56 |        55.76 |           62.37 |             52.3  |             58    |         8.5  |             83.53 | short              |                0.42 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.11 |             40.78 |         25.5  |         33.8  |          47.75 |        64.22 |           77.48 |             48.74 |             78.83 |         8.5  |             82.99 | long               |               -1.23 |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.65 |             38.88 |         36.21 |         31.28 |          41.55 |        58.6  |           72    |             25.15 |             75.22 |         5.01 |             81.52 | long               |                0.34 |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             38.81 |         29.51 |         34.99 |          42.64 |        54.11 |           50.26 |             47.6  |             77.74 |         6.28 |             78.58 | long               |               -1.48 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.33 |             38.62 |         31.45 |         35.92 |          41.33 |        54.19 |           47.64 |             41.85 |             85.58 |         8.5  |             78.43 | long               |               -1.34 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.92 |             37.55 |         38.17 |         22.19 |          36.94 |        47.59 |           64.09 |             19.74 |             42.67 |         9.09 |             77.55 | long               |               -1.25 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.45 |         44.21 |         23.88 |          29.55 |        37.35 |           38.42 |             38.29 |             48.67 |         7.16 |             75.4  | short              |               -0.46 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.86 |             27.54 |         57.4  |         23.62 |          22.81 |        31.47 |           21.62 |             27.38 |             59.43 |         7.78 |             75.24 | short              |               -0.44 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.6  |             26.32 |         32.48 |         23.73 |          24.8  |        27.85 |           25.61 |             37.19 |             32.3  |         7.06 |             73.61 | short              |               -2.97 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.95
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.95
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
- Excluded by hard/data filters: **869**
- Event watch (otherwise eligible): **11**
- Final eligible: **120**
- Eligible change vs previous stored run: **+16**

Top exclusion categories:
- market_cap: 841
- liquidity: 220
- price: 149
- data_confidence: 46
- price_history: 20
- asset_type: 1
- delisted: 1
- duplicate_listing: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AMCX | 8 | 8 | 8 | 15 | 3 | main,value,pullback |
| PARR | 1 | 6 |  | 4 | 2 | main,value,quality_value |
| TNK | 2 | 3 |  | 2 | 2 | main,value,quality_value |
| SM | 3 | 4 |  | 3 | 2 | main,value,quality_value |
| IRWD | 5 | 1 |  | 1 | 2 | main,value,quality_value |
| HMC | 7 | 19 |  | 10 | 1 | main,quality_value |
| SAP.DE | 18 | 2 |  | 6 | 1 | value,quality_value |
| IHS | 44 | 9 |  | 8 | 1 | value,quality_value |
| MAGN | 65 | 5 | 21 | 7 | 1 | value,quality_value |
| NWL.MI | 72 | 10 |  | 9 | 1 | value,quality_value |
| IRS | 77 | 7 | 20 | 5 | 1 | value,quality_value |
| SU.PA | 4 | 29 |  | 25 | 1 | main |
| ASML.AS | 6 | 65 |  | 35 | 1 | main |
| RMAX | 9 | 24 |  | 26 | 1 | main |
| TWN | 10 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **0** (none)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)
