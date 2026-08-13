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

- **EUROPE:** 90.1/100
- **OTHER:** 71.5/100
- **US:** 88.7/100

## Main multi-horizon ranking

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | TXG      | TXG    | US       |                6.6  |             96.28 |         88.99 |         96.17 |          97.49 |        96.38 |             nan |               nan |               nan |         7.08 |             59.09 | medium             |               -1.96 |                   nan |                  nan |
|      2 | TWST     | TWST   | US       |                6.79 |             96.07 |         89.18 |         95.79 |          96.96 |        96.36 |             nan |               nan |               nan |         6.85 |             59.09 | medium             |               -2.23 |                   nan |                  nan |
|      3 | DELL     | DELL   | US       |              276.86 |             95.96 |         85.02 |         95.89 |          97.34 |        96.02 |             nan |               nan |               nan |         7.72 |             59.09 | medium             |               -1.92 |                   nan |                  nan |
|      4 | HPE      | HPE    | US       |               68.76 |             95.19 |         84.46 |         95.71 |          95.8  |        94.68 |             nan |               nan |               nan |         6.9  |             59.09 | medium             |               -1.77 |                   nan |                  nan |
|      5 | PBF      | PBF    | US       |                7.64 |             95.18 |         92.59 |         95.01 |          95.51 |        95.35 |             nan |               nan |               nan |         7.1  |             59.09 | medium             |                1.24 |                   nan |                  nan |
|      6 | PANW     | PANW   | US       |              278.7  |             93.54 |         79.88 |         93.77 |          95.07 |        93.31 |             nan |               nan |               nan |         6.69 |             59.09 | medium             |               -1.81 |                   nan |                  nan |
|      7 | BFLY     | BFLY   | US       |                2.09 |             93.47 |         84.08 |         90.58 |          96.36 |        96.59 |             nan |               nan |               nan |         8.43 |             59.09 | long               |               -3.24 |                   nan |                  nan |
|      8 | REPL     | REPL   | US       |                1.23 |             92.64 |         96.48 |         91.14 |          89.69 |        94.14 |             nan |               nan |               nan |         9.91 |             59.09 | short              |               -2.52 |                   nan |                  nan |
|      9 | FSLY     | FSLY   | US       |                4.13 |             92.1  |         88.9  |         89.38 |          96.05 |        94.82 |             nan |               nan |               nan |         8.52 |             59.09 | medium             |               -0.04 |                   nan |                  nan |
|     10 | CRWD     | CRWD   | US       |              199.55 |             91.64 |         78.15 |         91.62 |          93.45 |        91.65 |             nan |               nan |               nan |         6.9  |             59.09 | medium             |               -0.68 |                   nan |                  nan |
|     11 | DFTX     | DFTX   | US       |                5.15 |             90.48 |         48.84 |         84.53 |          96.47 |        96.44 |             nan |               nan |               nan |         7.23 |             59.09 | medium             |               -0.35 |                   nan |                  nan |
|     12 | LFST     | LFST   | US       |                4.02 |             90.29 |         81.7  |         88.39 |          92.18 |        92.65 |             nan |               nan |               nan |         4.88 |             59.09 | long               |               -1.82 |                   nan |                  nan |
|     13 | OKTA     | OKTA   | US       |               23.63 |             90.26 |         72.37 |         90.18 |          90.34 |        90.69 |             nan |               nan |               nan |         7.56 |             59.09 | long               |                3.34 |                   nan |                  nan |
|     14 | VLO      | VLO    | US       |               85.49 |             90.18 |         82.3  |         89.14 |          91.23 |        91.57 |             nan |               nan |               nan |         3.48 |             59.09 | long               |                2.46 |                   nan |                  nan |
|     15 | ABSI     | ABSI   | US       |                1.39 |             89.66 |         72.39 |         84.27 |          96.39 |        95.05 |             nan |               nan |               nan |         9.09 |             59.09 | medium             |               -0.99 |                   nan |                  nan |
|     16 | ABCL     | ABCL   | US       |                2.85 |             89.39 |         90.31 |         97.5  |          88.46 |        85.88 |             nan |               nan |               nan |         9.07 |             59.09 | swing              |               -2.18 |                   nan |                  nan |
|     17 | CRNX     | CRNX   | US       |                7.77 |             88.96 |         49.05 |         87.11 |          90.82 |        95.55 |             nan |               nan |               nan |         8.51 |             59.09 | long               |               -1.83 |                   nan |                  nan |
|     18 | CAKE     | CAKE   | US       |                4.86 |             88.88 |         88.04 |         92.96 |          89.47 |        88.29 |             nan |               nan |               nan |         5.77 |             59.09 | swing              |               -1.98 |                   nan |                  nan |
|     19 | HZO      | HZO    | US       |                1    |             88.45 |         90.27 |         90.82 |          85.34 |        86.63 |             nan |               nan |               nan |         7.04 |             59.09 | swing              |               -2.02 |                   nan |                  nan |
|     20 | FROG     | FROG   | US       |                9.97 |             88.17 |         77.88 |         85.22 |          91.12 |        91.36 |             nan |               nan |               nan |         7.94 |             59.09 | long               |               12.24 |                   nan |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                                        | EUROPE   |                3.16 |                  72.47 |                    76.26 |                 79.42 |              74.44 |                90.53 |                    9.47 |           97.13 |             59.66 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | VOLV-B.ST | AB Volvo (publ)                                      | EUROPE   |               62.71 |                  87.18 |                    74.1  |                 69.83 |              78.9  |                56.41 |                   43.59 |           52.72 |             59.72 |       0.035 |         nan |       nan |       16.23 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            3 | SM        | SM Energy Company                                    | US       |                6.66 |                  77.15 |                    72.63 |                 71.61 |              71.72 |                63.02 |                   36.98 |           80.8  |             48.23 |       0.192 |         nan |       nan |        4.53 |         4.39 |          5.73 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            4 | MOMO      | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.01 |                 71    |              74.41 |                76.36 |                   23.64 |           66.72 |             56.56 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL       | Global Ship Lease, Inc.                              | OTHER    |                1.3  |                  79.69 |                    71.76 |                 70.63 |              73.77 |                69.17 |                   30.83 |           73.91 |             39.47 |       0.086 |         nan |       nan |        3.57 |         4.69 |          4.05 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | TNK       | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  68.6  |                    70.67 |                 72.46 |              71.16 |                80.54 |                   19.46 |           74.41 |             72.71 |       0.077 |         nan |       nan |        3.2  |         9.18 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            7 | PARR      | Par Pacific Holdings, Inc.                           | US       |                3.56 |                  71.16 |                    70.35 |                 71.63 |              70.38 |                66.34 |                   33.66 |           75.36 |             72.08 |       0.02  |         nan |       nan |        3.81 |         6.19 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | YPF       | YPF Sociedad Anónima                                 | OTHER    |               16.8  |                  76.47 |                    69.89 |                 69.35 |              71.69 |                56.53 |                   43.47 |           67.12 |             64.5  |       0.06  |         nan |       nan |        1.68 |         8.6  |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|            9 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.19 |                 69.79 |              66.96 |                72.77 |                   27.23 |           85.31 |             44.37 |     nan     |         nan |       nan |        3.93 |       161.61 |          4.71 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           10 | EMBC      | Embecta Corp.                                        | US       |                0.25 |                  74.87 |                    68.08 |                 67.06 |              69.28 |                59.24 |                   40.76 |           69.63 |             47.16 |       0.476 |         nan |       nan |        5.53 |         2.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | IHS       | IHS Holding Limited                                  | OTHER    |                2.45 |                  69.61 |                    68.01 |                 69.08 |              70.27 |                65.87 |                   34.13 |           61.75 |             82.93 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | MAGN      | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    67.92 |                 67.47 |              71.29 |                66.25 |                   33.75 |           60    |             62.12 |       0.53  |         nan |       nan |        6.42 |         7.49 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|           13 | NWL.MI    | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.98 |                 67.94 |              68.23 |                69.5  |                   30.5  |           70.87 |             56.81 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           14 | AVGO      | Broadcom Inc.                                        | US       |             1721.27 |                  57.41 |                    66.69 |                 67.51 |              61.95 |                78.54 |                   21.46 |           80.74 |             64.77 |       0.014 |         nan |       nan |       48.11 |        21.36 |         69.65 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           15 | DAC       | Danaos Corporation                                   | OTHER    |                2.21 |                  63.91 |                    66.28 |                 68.12 |              65.55 |                78.09 |                   21.91 |           77.72 |             54.78 |       0.002 |         nan |       nan |        3.74 |         5.71 |          4.73 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           16 | HMC       | Honda Motor Co., Ltd.                                | OTHER    |               35.12 |                  58.33 |                    65.57 |                 69.12 |              64.27 |                77.36 |                   22.64 |           75    |             83.46 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|           17 | RCI       | Rogers Communications Inc.                           | OTHER    |               17.04 |                  60.52 |                    65.33 |                 66.73 |              59.25 |                63.26 |                   36.74 |           94.29 |             42.86 |       0.277 |         nan |       nan |        7.28 |        10.42 |          4.39 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|           18 | UNIT      | Uniti Group Inc.                                     | US       |                2.07 |                  73.48 |                    65.29 |                 63.4  |              66    |                55.3  |                   44.7  |           69.33 |             31.37 |      -0.108 |         nan |       nan |        9.02 |       -13.84 |          2.56 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           19 | PKX       | POSCO Holdings Inc.                                  | OTHER    |               14.86 |                  62.88 |                    64.86 |                 67.73 |              62.02 |                63.15 |                   36.85 |           87.54 |             53.82 |     nan     |         nan |       nan |        3.7  |         9.82 |         28.46 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           20 | INVA      | Innoviva, Inc.                                       | US       |                1.3  |                  61.84 |                    64.76 |                 66.75 |              62.56 |                78.8  |                   21.2  |           85.26 |             38.55 |       0.074 |         nan |       nan |        6.43 |         9.38 |          4.81 |        0.3  |                 nan |              nan |                  11 |                  0.58 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                                        | EUROPE   |                3.16 |                  72.47 |                    76.26 |                 79.42 |              74.44 |                90.53 |                    9.47 |           97.13 |             59.66 |       0.834 |         nan |       nan |      nan    |       -81.64 |          2.19 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            6 | TNK       | Teekay Tankers Ltd.                                  | OTHER    |                2.51 |                  68.6  |                    70.67 |                 72.46 |              71.16 |                80.54 |                   19.46 |           74.41 |             72.71 |       0.077 |         nan |       nan |        3.2  |         9.18 |          4.93 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            7 | PARR      | Par Pacific Holdings, Inc.                           | US       |                3.56 |                  71.16 |                    70.35 |                 71.63 |              70.38 |                66.34 |                   33.66 |           75.36 |             72.08 |       0.02  |         nan |       nan |        3.81 |         6.19 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | SM        | SM Energy Company                                    | US       |                6.66 |                  77.15 |                    72.63 |                 71.61 |              71.72 |                63.02 |                   36.98 |           80.8  |             48.23 |       0.192 |         nan |       nan |        4.53 |         4.39 |          5.73 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            4 | MOMO      | Hello Group Inc.                                     | OTHER    |                0.74 |                  76.41 |                    72.01 |                 71    |              74.41 |                76.36 |                   23.64 |           66.72 |             56.56 |       0.574 |         nan |       nan |       -5.14 |         5.36 |          8.71 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL       | Global Ship Lease, Inc.                              | OTHER    |                1.3  |                  79.69 |                    71.76 |                 70.63 |              73.77 |                69.17 |                   30.83 |           73.91 |             39.47 |       0.086 |         nan |       nan |        3.57 |         4.69 |          4.05 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            2 | VOLV-B.ST | AB Volvo (publ)                                      | EUROPE   |               62.71 |                  87.18 |                    74.1  |                 69.83 |              78.9  |                56.41 |                   43.59 |           52.72 |             59.72 |       0.035 |         nan |       nan |       16.23 |        13.66 |         19.31 |        1.48 |                 nan |              nan |                  12 |                  0.63 |
|            9 | IRS       | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                  68.64 |                    68.19 |                 69.79 |              66.96 |                72.77 |                   27.23 |           85.31 |             44.37 |     nan     |         nan |       nan |        3.93 |       161.61 |          4.71 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|            8 | YPF       | YPF Sociedad Anónima                                 | OTHER    |               16.8  |                  76.47 |                    69.89 |                 69.35 |              71.69 |                56.53 |                   43.47 |           67.12 |             64.5  |       0.06  |         nan |       nan |        1.68 |         8.6  |          1.27 |        0.1  |                 nan |              nan |                  11 |                  0.58 |
|           16 | HMC       | Honda Motor Co., Ltd.                                | OTHER    |               35.12 |                  58.33 |                    65.57 |                 69.12 |              64.27 |                77.36 |                   22.64 |           75    |             83.46 |       0.041 |         nan |       nan |        7.16 |         6.29 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|           11 | IHS       | IHS Holding Limited                                  | OTHER    |                2.45 |                  69.61 |                    68.01 |                 69.08 |              70.27 |                65.87 |                   34.13 |           61.75 |             82.93 |      -0.111 |         nan |       nan |        7.1  |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           15 | DAC       | Danaos Corporation                                   | OTHER    |                2.21 |                  63.91 |                    66.28 |                 68.12 |              65.55 |                78.09 |                   21.91 |           77.72 |             54.78 |       0.002 |         nan |       nan |        3.74 |         5.71 |          4.73 |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           13 | NWL.MI    | NewPrinces S.p.A.                                    | EUROPE   |                0.69 |                  69.5  |                    66.98 |                 67.94 |              68.23 |                69.5  |                   30.5  |           70.87 |             56.81 |       0.967 |         nan |       nan |        5.3  |      -121.64 |          2.14 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           19 | PKX       | POSCO Holdings Inc.                                  | OTHER    |               14.86 |                  62.88 |                    64.86 |                 67.73 |              62.02 |                63.15 |                   36.85 |           87.54 |             53.82 |     nan     |         nan |       nan |        3.7  |         9.82 |         28.46 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|           14 | AVGO      | Broadcom Inc.                                        | US       |             1721.27 |                  57.41 |                    66.69 |                 67.51 |              61.95 |                78.54 |                   21.46 |           80.74 |             64.77 |       0.014 |         nan |       nan |       48.11 |        21.36 |         69.65 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|           12 | MAGN      | Magnera Corporation                                  | US       |                0.38 |                  73.82 |                    67.92 |                 67.47 |              71.29 |                66.25 |                   33.75 |           60    |             62.12 |       0.53  |         nan |       nan |        6.42 |         7.49 |        nan    |        4.23 |                 nan |              nan |                  10 |                  0.53 |
|          nan | AOD       | Abrdn Total Dynamic Dividend Fund                    | OTHER    |                0.98 |                  51.83 |                    63.72 |                 67.23 |              60.01 |                81.3  |                   18.7  |           78.46 |             80.64 |     nan     |         nan |       nan |      nan    |       nan    |          4.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | EMBC      | Embecta Corp.                                        | US       |                0.25 |                  74.87 |                    68.08 |                 67.06 |              69.28 |                59.24 |                   40.76 |           69.63 |             47.16 |       0.476 |         nan |       nan |        5.53 |         2.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           20 | INVA      | Innoviva, Inc.                                       | US       |                1.3  |                  61.84 |                    64.76 |                 66.75 |              62.56 |                78.8  |                   21.2  |           85.26 |             38.55 |       0.074 |         nan |       nan |        6.43 |         9.38 |          4.81 |        0.3  |                 nan |              nan |                  11 |                  0.58 |
|           17 | RCI       | Rogers Communications Inc.                           | OTHER    |               17.04 |                  60.52 |                    65.33 |                 66.73 |              59.25 |                63.26 |                   36.74 |           94.29 |             42.86 |       0.277 |         nan |       nan |        7.28 |        10.42 |          4.39 |        0.86 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AMZN     | Amazon.com, Inc.                                     | US       |             2477.89 |                     0.07 |    -0.03 |      0.06 |                  71.3  |                        68.93 |         62.85 |         58.98 |          63.98 |        62.68 |           81.16 |             70.55 |         5.78 |
|               2 | ALL      | The Allstate Corporation                             | US       |               57.25 |                     0.05 |    -0.05 |      0.08 |                  84.85 |                        68.86 |         61.13 |         66.04 |          62.3  |        56.11 |           67.79 |             63.73 |         3.01 |
|               3 | HRTG     | Heritage Insurance Holdings, Inc.                    | US       |                0.86 |                     0.06 |    -0.06 |      0.25 |                  86.56 |                        67.72 |         69.34 |         69.44 |          60.07 |        55.29 |           58.92 |             54.91 |         5.91 |
|               4 | HMC      | Honda Motor Co., Ltd.                                | OTHER    |               35.12 |                     0.02 |     0.01 |      0.08 |                  44.68 |                        66.79 |         65.15 |         64.93 |          62.24 |        69.11 |           75    |             83.46 |         3.75 |
|               5 | DAC      | Danaos Corporation                                   | OTHER    |                2.21 |                     0.02 |    -0.02 |      0.08 |                  55.36 |                        64.97 |         65.82 |         63.13 |          67.92 |        67.86 |           77.72 |             54.78 |         3.28 |
|               6 | YPF      | YPF Sociedad Anónima                                 | OTHER    |               16.8  |                     0.06 |    -0    |      0.02 |                  68.94 |                        64.81 |         50.9  |         62.73 |          69.94 |        69.82 |           67.12 |             64.5  |         5.78 |
|               7 | AVGO     | Broadcom Inc.                                        | US       |             1721.27 |                     0.02 |    -0.01 |      0.12 |                  52.78 |                        64.52 |         61.48 |         55.23 |          61.44 |        61.31 |           80.74 |             64.77 |         6.15 |
|               8 | LLY      | Eli Lilly and Company                                | US       |              934.97 |                     0.02 |     0.01 |      0.03 |                  44.33 |                        64.49 |         60.33 |         61.46 |          66.63 |        65.6  |           90.8  |             59.69 |         4.14 |
|               9 | CLW      | Clearwater Paper Corporation                         | US       |                0.31 |                     0.06 |    -0.05 |      0.34 |                  78.58 |                        64.48 |         67.01 |         63.86 |          52.86 |        52.18 |           50.18 |             60.99 |         6.83 |
|              10 | WKC      | World Kinect Corporation                             | US       |                1.65 |                     0.08 |    -0    |      0.01 |                  57.98 |                        64.11 |         59.77 |         70.93 |          67.83 |        59.46 |           46.4  |             71.15 |         4.93 |
|              11 | MSFT     | Microsoft Corporation                                | US       |             3193.89 |                     0.02 |    -0.01 |      0.24 |                  49.48 |                        63.43 |         70.9  |         64.54 |          54.72 |        52.23 |           58.4  |             59.21 |         5.72 |
|              12 | SLDE     | Slide Insurance Holdings, Inc.                       | US       |                2.19 |                     0.02 |     0.02 |      0.05 |                  44.45 |                        62.66 |         65.58 |         64.5  |          63.5  |        61.34 |           75.73 |             53.7  |         5.81 |
|              13 | PKX      | POSCO Holdings Inc.                                  | OTHER    |               14.86 |                     0.03 |     0.01 |      0.11 |                  52.43 |                        62.04 |         57.18 |         37.15 |          51.68 |        65.56 |           87.54 |             53.82 |         6.11 |
|              14 | LNC      | Lincoln National Corporation                         | US       |                7.52 |                     0.04 |    -0.03 |      0.08 |                  68.9  |                        61.93 |         66.38 |         67.07 |          57.98 |        56.33 |           44.01 |             61.7  |         4.64 |
|              15 | DSX      | Diana Shipping Inc.                                  | OTHER    |                0.27 |                     0.03 |    -0.01 |      0.18 |                  55.47 |                        61.63 |         65.29 |         49.77 |          56.32 |        61.96 |           60    |             57.78 |         4.59 |
|              16 | MA       | Mastercard Incorporated                              | US       |              430.92 |                     0.02 |    -0.02 |      0.03 |                  52.13 |                        60.86 |         57.49 |         58.18 |          53.03 |        49.85 |           71.39 |             64.47 |         3.13 |
|              17 | V        | Visa Inc.                                            | US       |              590.21 |                     0.02 |    -0.02 |     -0    |                  50.51 |                        59.07 |         53.13 |         57.78 |          53.68 |        49.31 |           68.11 |             59.89 |         2.83 |
|              18 | HTD      | John Hancock Tax-Advantaged Dividend Income Fund     | US       |                0.78 |                     0.02 |     0    |     -0.01 |                  51.06 |                        58.58 |         49.2  |         55.22 |          57.64 |        57.55 |           56.07 |             80.64 |         1.82 |
|              19 | GOOGL    | Alphabet Inc.                                        | US       |             3674.06 |                     0.08 |    -0.03 |     -0.02 |                  62.86 |                        58.49 |         44.21 |         43.77 |          59.29 |        58.61 |           81.86 |             70.58 |         4.87 |
|              20 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.08 |                     0.06 |    -0    |     -0.03 |                  71.42 |                        57.37 |         42.97 |         45.88 |          54.79 |        64.59 |           85.31 |             44.37 |         4.14 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation           | US       |                1.93 |             63.87 |         65.54 |         63.4  |          59.44 |        64.34 |           55.86 |             49.69 |             77    |         8.42 |             86.67 | short              |                0.68 |                   nan |                  nan |
|    nan | NVDA     | NVIDIA Corporation           | US       |             4730.1  |             63.49 |         68.56 |         57.86 |          62.38 |        64.6  |           91.3  |             60.91 |             32.73 |         5.6  |             89.54 | short              |               -2.05 |                   nan |                  nan |
|    nan | XNET     | Xunlei Limited               | OTHER    |                0.28 |             49.92 |         34.43 |         39.45 |          60.38 |        71.67 |           87.5  |             80.64 |             70    |         8.5  |             63.8  | long               |               -0.27 |                   nan |                  nan |
|    nan | STNE     | StoneCo Ltd.                 | OTHER    |                2.17 |             43.3  |         28.51 |         37.58 |          49.02 |        65.08 |           79.4  |             49.57 |             79.25 |         8.5  |             85.99 | long               |                1.3  |                   nan |                  nan |
|    nan | PSEC     | Prospect Capital Corporation | US       |                1.01 |             40.89 |         52.68 |         39.9  |          36.21 |        41.87 |           28.13 |             29.39 |             65.41 |         4.45 |             74.95 | short              |                0.2  |                   nan |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.93 |             39.7  |         29.47 |         35.81 |          43.58 |        54.78 |           52.15 |             48.53 |             75.88 |         6.22 |             78.58 | long               |               -0.6  |                   nan |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.32 |             39.16 |         31.25 |         35.62 |          42.71 |        55.91 |           52.87 |             42.47 |             84.23 |         7.13 |             78.43 | long               |               -0.8  |                   nan |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.63 |             36.03 |         30.81 |         29.44 |          41.25 |        58.3  |           72    |             25.16 |             75.22 |         4.89 |             81.52 | long               |               -2.51 |                   nan |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.9  |             35.31 |         34.88 |         21.38 |          35.75 |        46.88 |           64.32 |             19.79 |             42.67 |         9.1  |             77.55 | long               |               -3.49 |                   nan |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.74 |             33.7  |         39.91 |         23.21 |          29.69 |        37.71 |           39.66 |             38.61 |             49.29 |         7.07 |             75.4  | short              |               -0.21 |                   nan |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.88 |             28.33 |         58.54 |         24.22 |          23.49 |        32.45 |           25.2  |             27.71 |             58    |         7.75 |             75.24 | short              |                0.35 |                   nan |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.43 |             26.38 |         27.71 |         22.69 |          25.06 |        28.42 |           29.19 |             37.55 |             30.07 |         6.88 |             76.61 | long               |               -2.9  |                   nan |                  nan |

## Fastest improving (5 stored runs)

_Not enough stored runs yet._

## Fastest deteriorating (5 stored runs)

_Not enough stored runs yet._

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.91

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
- Excluded by hard/data filters: **297**
- Event watch (otherwise eligible): **12**
- Final eligible: **691**
- Eligible change vs previous stored run: **+587**

Top exclusion categories:
- liquidity: 242
- price: 182
- market_cap: 146
- data_confidence: 43
- price_history: 20
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| YPF | 267 | 8 | 6 | 9 | 2 | value,pullback,quality_value |
| PARR | 73 | 7 |  | 3 | 1 | value,quality_value |
| BION.SW | 132 | 1 |  | 1 | 1 | value,quality_value |
| TNK | 148 | 6 |  | 2 | 1 | value,quality_value |
| SM | 239 | 3 |  | 4 | 1 | value,quality_value |
| HMC | 291 | 16 | 4 | 10 | 1 | pullback,quality_value |
| GSL | 439 | 5 | 21 | 6 | 1 | value,quality_value |
| VOLV-B.ST | 460 | 2 | 24 | 7 | 1 | value,quality_value |
| IRS | 525 | 9 | 20 | 8 | 1 | value,quality_value |
| MOMO | 585 | 4 | 28 | 5 | 1 | value,quality_value |
| TXG | 1 |  |  |  | 1 | main |
| TWST | 2 |  |  |  | 1 | main |
| DELL | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |

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
| 1 | GSL | value+pullback | 70.98 | 79.69 | 72.82 | 73.91 | 39.47 | 69.17 | 56.11 |
| 2 | MOMO | value+pullback | 70.55 | 76.41 | 66.78 | 66.72 | 56.56 | 76.36 | 46.20 |
| 3 | IRS | value+pullback | 70.24 | 68.64 | 71.42 | 85.31 | 44.37 | 72.77 | 50.34 |
| 4 | VOLV-B.ST | value+pullback | 68.87 | 87.18 | 70.20 | 52.72 | 59.72 | 56.41 | 54.38 |
| 5 | INVA | value+pullback | 68.60 | 61.84 | 70.58 | 85.26 | 38.55 | 78.80 | 42.54 |
| 6 | YPF | value+pullback | 68.00 | 76.47 | 68.94 | 67.12 | 64.50 | 56.53 | 66.28 |
| 7 | SUZ | value+pullback | 67.81 | 65.46 | 75.81 | 70.51 | 46.87 | 69.79 | 39.87 |
| 8 | DAC | value+pullback | 65.77 | 63.91 | 55.36 | 77.72 | 54.78 | 78.09 | 66.84 |
| 9 | AVGO | value+pullback | 64.71 | 57.41 | 52.78 | 80.74 | 64.77 | 78.54 | 61.38 |
| 10 | HMC | value+pullback | 63.74 | 58.33 | 44.68 | 75.00 | 83.46 | 77.36 | 65.04 |
| 11 | PKX | value+pullback | 63.12 | 62.88 | 52.43 | 87.54 | 53.82 | 63.15 | 54.43 |
| 12 | CLW | value+pullback | 61.09 | 55.03 | 78.58 | 50.18 | 60.99 | 56.55 | 58.36 |
| 13 | BHF | value+pullback | 60.93 | 69.98 | 59.90 | 51.47 | 43.36 | 64.51 | 44.39 |
| 14 | ALL-PH | value+pullback | 60.90 | 61.76 | 64.52 | 67.79 | 42.11 | 59.30 | 44.35 |
| 15 | BION.SW | value | 60.38 | 72.47 | 33.25 | 97.13 | 59.66 | 90.53 | 75.39 |
| 16 | MFA | value+pullback | 58.45 | 58.09 | 48.33 | 80.96 | 37.72 | 65.11 | 47.63 |
| 17 | BYD | value+pullback | 57.71 | 57.49 | 52.93 | 77.54 | 37.28 | 59.34 | 47.49 |
| 18 | MTRX | value+pullback | 57.24 | 74.80 | 49.47 | 39.59 | 59.77 | 52.58 | 44.76 |
| 19 | MSFT | value+pullback | 56.54 | 64.66 | 49.48 | 58.40 | 59.21 | 50.44 | 59.63 |
| 20 | LNC | value+pullback | 56.18 | 56.56 | 68.90 | 44.01 | 61.70 | 46.08 | 62.18 |
