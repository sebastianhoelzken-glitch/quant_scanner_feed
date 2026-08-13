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

- **EUROPE:** 91.0/100
- **OTHER:** 71.6/100
- **US:** 88.7/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | TWST     | TWST   | US       |                6.81 |             96.56 |         89.72 |         96.77 |          96.96 |        96.36 |             nan |               nan |               nan |         6.85 |             59.09 | medium             |               -1.74 |                   nan |                  nan |
|      2 | TXG      | TXG    | US       |                6.57 |             96.19 |         89.14 |         96.01 |          97.49 |        96.38 |             nan |               nan |               nan |         7.08 |             59.09 | medium             |               -2.04 |                   nan |                  nan |
|      3 | DELL     | DELL   | US       |              277.12 |             96.04 |         85.48 |         96.08 |          97.34 |        96.01 |             nan |               nan |               nan |         7.7  |             59.09 | medium             |               -1.84 |                   nan |                  nan |
|      4 | HPE      | HPE    | US       |               68.7  |             95.21 |         84.53 |         95.76 |          95.92 |        94.65 |             nan |               nan |               nan |         6.9  |             59.09 | medium             |               -1.75 |                   nan |                  nan |
|      5 | PBF      | PBF    | US       |                7.64 |             95.17 |         92.74 |         95.04 |          95.49 |        95.31 |             nan |               nan |               nan |         7.11 |             59.09 | medium             |                1.24 |                   nan |                  nan |
|      6 | PANW     | PANW   | US       |              279.91 |             93.59 |         80.27 |         93.91 |          95.03 |        93.27 |             nan |               nan |               nan |         6.71 |             59.09 | medium             |               -1.77 |                   nan |                  nan |
|      7 | BFLY     | BFLY   | US       |                2.05 |             92.99 |         82.66 |         89.75 |          96.23 |        96.59 |             nan |               nan |               nan |         8.44 |             59.09 | long               |               -3.72 |                   nan |                  nan |
|      8 | REPL     | REPL   | US       |                1.23 |             92.84 |         96.87 |         91.61 |          89.64 |        94.07 |             nan |               nan |               nan |         9.91 |             59.09 | short              |               -2.32 |                   nan |                  nan |
|      9 | FSLY     | FSLY   | US       |                4.15 |             92.2  |         88.91 |         89.57 |          96.05 |        94.83 |             nan |               nan |               nan |         8.53 |             59.09 | medium             |                0.06 |                   nan |                  nan |
|     10 | CRWD     | CRWD   | US       |              199.17 |             91.97 |         79.11 |         92.28 |          93.45 |        91.66 |             nan |               nan |               nan |         6.92 |             59.09 | medium             |               -0.34 |                   nan |                  nan |
|     11 | LFST     | LFST   | US       |                4.05 |             90.78 |         83.14 |         89.19 |          92.37 |        92.81 |             nan |               nan |               nan |         4.89 |             59.09 | long               |               -1.33 |                   nan |                  nan |
|     12 | DFTX     | DFTX   | US       |                5.12 |             90.37 |         48.2  |         84.38 |          96.36 |        96.44 |             nan |               nan |               nan |         7.24 |             59.09 | long               |               -0.46 |                   nan |                  nan |
|     13 | VLO      | VLO    | US       |               85.63 |             90.32 |         82.45 |         89.34 |          91.31 |        91.74 |             nan |               nan |               nan |         3.49 |             59.09 | long               |                2.6  |                   nan |                  nan |
|     14 | ABSI     | ABSI   | US       |                1.41 |             90.27 |         74.51 |         85.39 |          96.47 |        95.14 |             nan |               nan |               nan |         9.1  |             59.09 | medium             |               -0.38 |                   nan |                  nan |
|     15 | OKTA     | OKTA   | US       |               23.56 |             90.19 |         72.16 |         90.13 |          90.25 |        90.52 |             nan |               nan |               nan |         7.54 |             59.09 | long               |                3.27 |                   nan |                  nan |
|     16 | ABCL     | ABCL   | US       |                2.92 |             89.25 |         89.95 |         97.5  |          88.56 |        86.01 |             nan |               nan |               nan |         9.08 |             59.09 | swing              |               -2.31 |                   nan |                  nan |
|     17 | CRNX     | CRNX   | US       |                7.77 |             88.96 |         48.97 |         87.14 |          90.78 |        95.49 |             nan |               nan |               nan |         8.52 |             59.09 | long               |               -1.83 |                   nan |                  nan |
|     18 | CAKE     | CAKE   | US       |                4.83 |             88.9  |         88.13 |         92.92 |          89.5  |        88.3  |             nan |               nan |               nan |         5.78 |             59.09 | swing              |               -1.96 |                   nan |                  nan |
|     19 | NBIS     | NBIS   | US       |               56.16 |             88.8  |         89.26 |         78.23 |          89.54 |        88.34 |             nan |               nan |               nan |         8.91 |             59.09 | medium             |               -3.11 |                   nan |                  nan |
|     20 | FROG     | FROG   | US       |               10    |             88.52 |         78.97 |         85.82 |          91.22 |        91.48 |             nan |               nan |               nan |         7.97 |             59.09 | long               |               12.59 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                                        | EUROPE   |                3.16 |                  72.13 |                    76.2  |                 79.47 |              74.24 |                90.69 |                    9.31 |           97.76 |             59.77 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | VOLV-B.ST | AB Volvo (publ)                                      | EUROPE   |               62.71 |                  87.18 |                    74.12 |                 69.86 |              78.91 |                56.42 |                   43.58 |           52.72 |             59.87 |       0.035 |         nan |       nan |       16.11 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            3 | MOMO      | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.16 |                 71.21 |              74.57 |                76.6  |                   23.4  |           66.72 |             57.71 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            4 | EMBC      | Embecta Corp.                                        | US       |                0.25 |                  73.11 |                    70.85 |                 70.6  |              70.97 |                62.39 |                   37.61 |           71    |            nan    |       0.477 |         nan |       nan |        5.53 |         2.9  |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | TNK       | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  67.77 |                    70.34 |                 72.26 |              70.62 |                80.86 |                   19.14 |           74.91 |             72.68 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            6 | YPF       | YPF Sociedad Anónima                                 | OTHER    |               16.82 |                  76.49 |                    70.14 |                 69.6  |              72    |                58.05 |                   41.95 |           67.03 |             64.77 |       0.06  |         nan |       nan |        1.68 |         8.61 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            7 | SM        | SM Energy Company                                    | US       |                6.69 |                  71.87 |                    69.85 |                 69.23 |              68.35 |                64.98 |                   35.02 |           79.13 |             49.04 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            8 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.2  |                 69.8  |              66.97 |                72.8  |                   27.2  |           85.31 |             44.43 |     nan     |         nan |       nan |        3.93 |       162.2  |          4.73 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            9 | IHS       | IHS Holding Limited                                  | OTHER    |                2.44 |                  69.61 |                    68.11 |                 69.22 |              70.38 |                66.07 |                   33.93 |           61.75 |             83.66 |      -0.111 |         nan |       nan |        7.1  |        15.11 |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | MAGN      | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    67.93 |                 67.48 |              71.29 |                66.26 |                   33.74 |           60    |             62.17 |       0.531 |         nan |       nan |        6.42 |         7.47 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|           11 | PARR      | Par Pacific Holdings, Inc.                           | US       |                3.57 |                  66.04 |                    67.61 |                 69.22 |              67.01 |                68.1  |                   31.9  |           73.91 |             72.05 |       0.02  |         nan |       nan |        3.81 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | NWL.MI    | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.97 |                 67.94 |              68.23 |                69.49 |                   30.51 |           70.87 |             56.82 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           13 | AVGO      | Broadcom Inc.                                        | US       |             1724.03 |                  57.79 |                    66.91 |                 67.69 |              62.22 |                78.55 |                   21.45 |           80.74 |             64.78 |       0.014 |         nan |       nan |       48.11 |        21.39 |         69.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           14 | HMC       | Honda Motor Co., Ltd.                                | OTHER    |               35.11 |                  58.33 |                    65.59 |                 69.15 |              64.29 |                77.39 |                   22.61 |           75    |             83.62 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|           15 | UNIT      | Uniti Group Inc.                                     | US       |                2.06 |                  73.48 |                    65.46 |                 63.63 |              66.17 |                55.62 |                   44.38 |           69.33 |             32.58 |      -0.109 |         nan |       nan |        9.02 |       -13.79 |          2.55 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           16 | RCI       | Rogers Communications Inc.                           | OTHER    |               17.05 |                  60.52 |                    65.43 |                 66.87 |              59.36 |                63.4  |                   36.6  |           94.29 |             43.7  |       0.277 |         nan |       nan |        7.28 |        10.43 |          4.39 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           17 | CNC       | Centene Corporation                                  | US       |               28.29 |                  68.2  |                    64.86 |                 62.56 |              65.4  |                54.89 |                   45.11 |           56.05 |             64.14 |       0.295 |         nan |       nan |        4.84 |        12.46 |        nan    |        0.91 |                 nan |              nan |                  10 |                  0.53 |
|           18 | PKX       | POSCO Holdings Inc.                                  | OTHER    |               14.84 |                  62.88 |                    64.86 |                 67.73 |              62.02 |                63.15 |                   36.85 |           87.54 |             53.81 |     nan     |         nan |       nan |        3.7  |         9.81 |         28.43 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           19 | MTRX      | Matrix Service Company                               | US       |                0.28 |                  76.25 |                    64.58 |                 61.92 |              70.88 |                55.28 |                   44.72 |           41.08 |             60.28 |       0.303 |         nan |       nan |      -46.91 |        16.78 |        nan    |        1.12 |                 nan |              nan |                  10 |                  0.53 |
|           20 | DAC       | Danaos Corporation                                   | OTHER    |                2.22 |                  66.31 |                    64.48 |                 64.91 |              65.66 |                68.91 |                   31.09 |           65.87 |             55.11 |       0.002 |         nan |       nan |        3.74 |         5.73 |          4.75 |        0.12 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                                        | EUROPE   |                3.16 |                  72.13 |                    76.2  |                 79.47 |              74.24 |                90.69 |                    9.31 |           97.76 |             59.77 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | TNK       | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  67.77 |                    70.34 |                 72.26 |              70.62 |                80.86 |                   19.14 |           74.91 |             72.68 |       0.078 |         nan |       nan |        3.2  |         9.16 |          4.92 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            3 | MOMO      | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.16 |                 71.21 |              74.57 |                76.6  |                   23.4  |           66.72 |             57.71 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            4 | EMBC      | Embecta Corp.                                        | US       |                0.25 |                  73.11 |                    70.85 |                 70.6  |              70.97 |                62.39 |                   37.61 |           71    |            nan    |       0.477 |         nan |       nan |        5.53 |         2.9  |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | VOLV-B.ST | AB Volvo (publ)                                      | EUROPE   |               62.71 |                  87.18 |                    74.12 |                 69.86 |              78.91 |                56.42 |                   43.58 |           52.72 |             59.87 |       0.035 |         nan |       nan |       16.11 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            8 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.2  |                 69.8  |              66.97 |                72.8  |                   27.2  |           85.31 |             44.43 |     nan     |         nan |       nan |        3.93 |       162.2  |          4.73 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            6 | YPF       | YPF Sociedad Anónima                                 | OTHER    |               16.82 |                  76.49 |                    70.14 |                 69.6  |              72    |                58.05 |                   41.95 |           67.03 |             64.77 |       0.06  |         nan |       nan |        1.68 |         8.61 |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            7 | SM        | SM Energy Company                                    | US       |                6.69 |                  71.87 |                    69.85 |                 69.23 |              68.35 |                64.98 |                   35.02 |           79.13 |             49.04 |       0.191 |         nan |       nan |        4.53 |         4.41 |          5.75 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            9 | IHS       | IHS Holding Limited                                  | OTHER    |                2.44 |                  69.61 |                    68.11 |                 69.22 |              70.38 |                66.07 |                   33.93 |           61.75 |             83.66 |      -0.111 |         nan |       nan |        7.1  |        15.11 |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | PARR      | Par Pacific Holdings, Inc.                           | US       |                3.57 |                  66.04 |                    67.61 |                 69.22 |              67.01 |                68.1  |                   31.9  |           73.91 |             72.05 |       0.02  |         nan |       nan |        3.81 |         6.21 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | HMC       | Honda Motor Co., Ltd.                                | OTHER    |               35.11 |                  58.33 |                    65.59 |                 69.15 |              64.29 |                77.39 |                   22.61 |           75    |             83.62 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|           12 | NWL.MI    | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.97 |                 67.94 |              68.23 |                69.49 |                   30.51 |           70.87 |             56.82 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           18 | PKX       | POSCO Holdings Inc.                                  | OTHER    |               14.84 |                  62.88 |                    64.86 |                 67.73 |              62.02 |                63.15 |                   36.85 |           87.54 |             53.81 |     nan     |         nan |       nan |        3.7  |         9.81 |         28.43 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           13 | AVGO      | Broadcom Inc.                                        | US       |             1724.03 |                  57.79 |                    66.91 |                 67.69 |              62.22 |                78.55 |                   21.45 |           80.74 |             64.78 |       0.014 |         nan |       nan |       48.11 |        21.39 |         69.75 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           10 | MAGN      | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    67.93 |                 67.48 |              71.29 |                66.26 |                   33.74 |           60    |             62.17 |       0.531 |         nan |       nan |        6.42 |         7.47 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|           16 | RCI       | Rogers Communications Inc.                           | OTHER    |               17.05 |                  60.52 |                    65.43 |                 66.87 |              59.36 |                63.4  |                   36.6  |           94.29 |             43.7  |       0.277 |         nan |       nan |        7.28 |        10.43 |          4.39 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           21 | INVA      | Innoviva, Inc.                                       | US       |                1.3  |                  60.16 |                    64.41 |                 66.87 |              61.54 |                79.44 |                   20.56 |           87.93 |             39.32 |       0.074 |         nan |       nan |        6.43 |         9.39 |          4.81 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           27 | AMZN      | Amazon.com, Inc.                                     | US       |             2480.28 |                  50.79 |                    62.69 |                 65.61 |              55.34 |                64.94 |                   35.06 |           89.57 |             70.8  |       0.001 |         nan |       nan |       17.83 |        25.54 |         21.33 |        1.42 |                 nan |              nan |                  11 |                  0.58 |
|           20 | DAC       | Danaos Corporation                                   | OTHER    |                2.22 |                  66.31 |                    64.48 |                 64.91 |              65.66 |                68.91 |                   31.09 |           65.87 |             55.11 |       0.002 |         nan |       nan |        3.74 |         5.73 |          4.75 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           22 | SUZ       | Suzano S.A.                                          | OTHER    |                8.53 |                  65.46 |                    64.05 |                 64.62 |              64.41 |                69.85 |                   30.15 |           70.51 |             47.07 |      -0.036 |         nan |       nan |        4.11 |         5.4  |          4.44 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN      | Amazon.com, Inc.                                     | US       |             2480.28 |                     0.07 |    -0.03 |      0.06 |                  71.35 |                        70.86 |         63.25 |         59.69 |          66.92 |        68.37 |           89.57 |             70.8  |         5.75 |
|               2 | ALL       | The Allstate Corporation                             | US       |               57.12 |                     0.05 |    -0.05 |      0.08 |                  85.22 |                        69.57 |         61.61 |         66.61 |          63.12 |        57.16 |           69.42 |             63.95 |         3.01 |
|               3 | HRTG      | Heritage Insurance Holdings, Inc.                    | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.84 |                        68.37 |         69.99 |         70.13 |          60.9  |        56.35 |           59.86 |             55.38 |         5.9  |
|               4 | HMC       | Honda Motor Co., Ltd.                                | OTHER    |               35.11 |                     0.02 |     0.02 |      0.08 |                  44.39 |                        67.01 |         65.62 |         65.42 |          62.57 |        69.39 |           75    |             83.62 |         3.76 |
|               5 | CLW       | Clearwater Paper Corporation                         | US       |                0.31 |                     0.06 |    -0.04 |      0.35 |                  80.37 |                        65.49 |         67.91 |         64.71 |          53.43 |        52.49 |           50.18 |             62.95 |         6.83 |
|               6 | LLY       | Eli Lilly and Company                                | US       |              934.65 |                     0.02 |     0.01 |      0.03 |                  44.14 |                        65.03 |         60.6  |         61.68 |          67.2  |        66.57 |           93.1  |             59.66 |         4.14 |
|               7 | YPF       | YPF Sociedad Anónima                                 | OTHER    |               16.82 |                     0.06 |    -0    |      0.02 |                  69.41 |                        64.96 |         51.5  |         62.86 |          69.84 |        69.53 |           67.03 |             64.77 |         5.78 |
|               8 | AVGO      | Broadcom Inc.                                        | US       |             1724.03 |                     0.02 |    -0.01 |      0.12 |                  53.08 |                        64.72 |         61.79 |         55.52 |          61.73 |        61.58 |           80.74 |             64.78 |         6.14 |
|               9 | DSX       | Diana Shipping Inc.                                  | OTHER    |                0.27 |                     0.03 |    -0.02 |      0.18 |                  60.85 |                        63.77 |         65.15 |         50.71 |          59.35 |        68.09 |           66.93 |             57.85 |         4.59 |
|              10 | MSFT      | Microsoft Corporation                                | US       |             3199.99 |                     0.02 |    -0.01 |      0.24 |                  49.75 |                        63.69 |         71.27 |         65.01 |          55.03 |        52.5  |           58.4  |             59.39 |         5.7  |
|              11 | SLDE      | Slide Insurance Holdings, Inc.                       | US       |                2.19 |                     0.02 |     0.01 |      0.05 |                  48.61 |                        63.39 |         65.11 |         64.56 |          64.13 |        62.28 |           77.24 |             53.95 |         5.79 |
|              12 | WKC       | World Kinect Corporation                             | US       |                1.65 |                     0.08 |    -0    |      0    |                  57.6  |                        62.97 |         57.82 |         68.81 |          66.08 |        57.55 |           46.33 |             71.03 |         4.92 |
|              13 | PKX       | POSCO Holdings Inc.                                  | OTHER    |               14.84 |                     0.03 |     0.01 |      0.11 |                  53.07 |                        62.28 |         57.49 |         37.42 |          51.88 |        65.74 |           87.54 |             53.81 |         6.11 |
|              14 | DAC       | Danaos Corporation                                   | OTHER    |                2.22 |                     0.02 |    -0.02 |      0.08 |                  54.47 |                        62.25 |         65.27 |         62.59 |          66    |        65.53 |           65.87 |             55.11 |         3.29 |
|              15 | MA        | Mastercard Incorporated                              | US       |              430.82 |                     0.02 |    -0.02 |      0.03 |                  52.35 |                        61.42 |         57.97 |         58.71 |          53.69 |        50.76 |           72.44 |             64.81 |         3.14 |
|              16 | HTD       | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0.01 |     -0.01 |                  48.6  |                        59.62 |         51.15 |         56.47 |          59.01 |        58.93 |           59.21 |             81.69 |         1.8  |
|              17 | GOOGL     | Alphabet Inc.                                        | US       |             3673.85 |                     0.08 |    -0.03 |     -0.02 |                  62.88 |                        58.05 |         44.05 |         43.75 |          59.11 |        58.52 |           80    |             70.61 |         4.85 |
|              18 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                     0.05 |    -0    |     -0.03 |                  70.14 |                        57.63 |         44.27 |         46.77 |          55.34 |        65.02 |           85.31 |             44.43 |         4.13 |
|              19 | NOVN.SW   | Novartis AG                                          | EUROPE   |              250.93 |                     0.05 |    -0.01 |      0.01 |                  70.2  |                        56.98 |         45.49 |         48.07 |          54.75 |        56.53 |           69.83 |             56.29 |         2.18 |
|              20 | VOLV-B.ST | AB Volvo (publ)                                      | EUROPE   |               62.71 |                     0.08 |    -0.06 |     -0    |                  70.2  |                        55.53 |         43.57 |         50.95 |          57.9  |        65.59 |           52.72 |             59.87 |         3.8  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation           | US       |                1.93 |             65.5  |         66.5  |         64.49 |          62.42 |        69.14 |           67.03 |             50.02 |             78.15 |         8.4  |             86.67 | long               |                2.31 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4732.85 |             63.84 |         68.7  |         58.1  |          62.71 |        64.96 |           91.3  |             60.91 |             33.09 |         5.58 |             89.54 | short              |               -1.7  |                   nan |                  nan |
|    nan | XNET     | Xunlei Limited               | OTHER    |                0.28 |             52.68 |         35.92 |         41.67 |          63.69 |        77.23 |           91.13 |             81.69 |             82.22 |         8.5  |             63.8  | long               |                2.49 |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.02 |             41.37 |         54.36 |         41.04 |          36.65 |        41.7  |           28.81 |             30.19 |             62.14 |         4.47 |             74.95 | short              |                0.68 |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.32 |             39.35 |         30.89 |         34.95 |          43.76 |        58.43 |           63.16 |             38.6  |             81.25 |         7.11 |             78.48 | long               |               -0.61 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             39.15 |         37.71 |         24.15 |          40.58 |        55.18 |           74.9  |             19.84 |             54.95 |         9.09 |             77.55 | long               |                0.34 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             36.61 |         40.71 |         24.86 |          32.51 |        42.48 |           45.32 |             38.37 |             56.41 |         7.11 |             75.4  | long               |                2.7  |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             35.8  |         30.24 |         29.37 |          41.36 |        58.34 |           72    |             25.94 |             75.22 |         4.91 |             81.52 | long               |               -2.74 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.88 |             32.06 |         59.64 |         26.15 |          26.49 |        37.63 |           29.73 |             28.25 |             67.86 |         7.77 |             75.24 | short              |                4.08 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.45 |             26.91 |         28.2  |         23.4  |          25.63 |        28.85 |           29.19 |             38.97 |             30.07 |         6.91 |             76.61 | long               |               -2.37 |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.91
- `relative_63d_rank` vs `sector_score`: r=0.85

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
- Excluded by hard/data filters: **304**
- Event watch (otherwise eligible): **10**
- Final eligible: **686**
- Eligible change vs previous stored run: **+582**

Top exclusion categories:
- liquidity: 244
- price: 182
- market_cap: 147
- data_confidence: 57
- price_history: 22
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| YPF | 274 | 6 | 7 | 7 | 2 | value,pullback,quality_value |
| BION.SW | 136 | 1 |  | 1 | 1 | value,quality_value |
| TNK | 153 | 5 |  | 2 | 1 | value,quality_value |
| SM | 257 | 7 |  | 8 | 1 | value,quality_value |
| EMBC | 324 | 4 |  | 4 | 1 | value,quality_value |
| IHS | 398 | 9 |  | 9 | 1 | value,quality_value |
| VOLV-B.ST | 462 | 2 | 20 | 5 | 1 | value,quality_value |
| IRS | 511 | 8 | 18 | 6 | 1 | value,quality_value |
| MOMO | 581 | 3 | 23 | 3 | 1 | value,quality_value |
| TWST | 1 |  |  |  | 1 | main |
| TXG | 2 |  |  |  | 1 | main |
| DELL | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |
| PANW | 6 |  |  |  | 1 | main |

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
| 1 | MOMO | value+pullback | 70.91 | 76.41 | 67.55 | 66.72 | 57.71 | 76.60 | 46.35 |
| 2 | IRS | value+pullback | 69.93 | 68.64 | 70.14 | 85.31 | 44.43 | 72.80 | 51.06 |
| 3 | INVA | value+pullback | 69.02 | 60.16 | 71.85 | 87.93 | 39.32 | 79.44 | 42.97 |
| 4 | VOLV-B.ST | value+pullback | 68.88 | 87.18 | 70.20 | 52.72 | 59.87 | 56.42 | 54.42 |
| 5 | YPF | value+pullback | 68.44 | 76.49 | 69.41 | 67.03 | 64.77 | 58.05 | 66.19 |
| 6 | SUZ | value+pullback | 67.61 | 65.46 | 74.88 | 70.51 | 47.07 | 69.85 | 39.97 |
| 7 | AVGO | value+pullback | 64.91 | 57.79 | 53.08 | 80.74 | 64.78 | 78.55 | 61.66 |
| 8 | DSX | value+pullback | 63.85 | 62.93 | 60.85 | 66.93 | 57.85 | 69.67 | 62.25 |
| 9 | HMC | value+pullback | 63.69 | 58.33 | 44.39 | 75.00 | 83.62 | 77.39 | 65.52 |
| 10 | PKX | value+pullback | 63.27 | 62.88 | 53.07 | 87.54 | 53.81 | 63.15 | 54.68 |
| 11 | DAC | value+pullback | 62.68 | 66.31 | 54.47 | 65.87 | 55.11 | 68.91 | 65.40 |
| 12 | CLW | value+pullback | 61.81 | 55.03 | 80.37 | 50.18 | 62.95 | 56.90 | 59.07 |
| 13 | BHF | value+pullback | 61.51 | 69.85 | 59.95 | 53.74 | 44.06 | 65.52 | 45.09 |
| 14 | ALL-PH | value+pullback | 61.22 | 60.56 | 64.99 | 69.42 | 42.69 | 60.59 | 44.72 |
| 15 | BION.SW | value | 60.42 | 72.13 | 34.40 | 97.76 | 59.77 | 90.69 | 75.20 |
| 16 | MTRX | value+pullback | 58.66 | 76.25 | 50.17 | 41.08 | 60.28 | 55.28 | 46.14 |
| 17 | MFA | value+pullback | 58.15 | 58.09 | 47.35 | 80.96 | 37.36 | 65.03 | 48.37 |
| 18 | MSFT | value+pullback | 56.63 | 64.66 | 49.75 | 58.40 | 59.39 | 50.49 | 60.02 |
| 19 | AAPL | value+pullback | 55.05 | 60.17 | 48.41 | 62.85 | 47.46 | 53.61 | 50.95 |
| 20 | TNK | value | 55.01 | 67.77 | 30.95 | 74.91 | 72.68 | 80.86 | 74.19 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 0/10 | 0/10 | 0/10 | 0/10 | 10/10 | 59.1 | 10 / 0 |
| Top 25 | 0/25 | 0/25 | 0/25 | 0/25 | 25/25 | 59.1 | 25 / 0 |
| Top 50 | 0/50 | 0/50 | 0/50 | 0/50 | 50/50 | 59.1 | 48 / 2 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=3, large_20_100b=1, mega_100b_plus=3
Top-10 sparse-data names: TWST (missing quality,revisions,valuation; conf=59.1), TXG (missing quality,revisions,valuation; conf=59.1), DELL (missing quality,revisions,valuation; conf=59.1), HPE (missing quality,revisions,valuation; conf=59.1), PBF (missing quality,revisions,valuation; conf=59.1), PANW (missing quality,revisions,valuation; conf=59.1), BFLY (missing quality,revisions,valuation; conf=59.1), REPL (missing quality,revisions,valuation; conf=59.1), FSLY (missing quality,revisions,valuation; conf=59.1), CRWD (missing quality,revisions,valuation; conf=59.1)
