# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-17

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

- **EUROPE:** 90.8/100
- **OTHER:** 76.3/100
- **US:** 86.8/100

## Main multi-horizon ranking

|   rank | symbol    | name                      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:--------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | JCAP      | JCAP                      | US       |                1.17 |             81.97 |         86.44 |         80.71 |          76.69 |        83.24 |           87.88 |             85.07 |             84.09 |         5.3  |             65.45 | short              |                0.06 |                nan    |                  nan |
|      2 | SSABBH.HE | SSABBH.HE                 | EUROPE   |                9.81 |             81.25 |         80.32 |         80.55 |          81.96 |        82.89 |           68.5  |            nan    |             99.79 |         3.29 |             62.84 | long               |                1.53 |                  1.16 |                  nan |
|      3 | ECO       | Okeanis Eco Tankers Corp. | OTHER    |                2.11 |             81.05 |         87.55 |         82.17 |          79.92 |        68.84 |           86.18 |             85.21 |             16.98 |         4.67 |             80.75 | short              |              nan    |                nan    |                  nan |
|      4 | HPE       | HPE                       | US       |               65.87 |             80.04 |         80.11 |         84.23 |          79.97 |        72.45 |           71.33 |             72.09 |             57.89 |         6.71 |             65.68 | swing              |               -1.17 |                 -3.38 |                  nan |
|      5 | MPC       | MPC                       | US       |               86.85 |             79.73 |         80.19 |         80.86 |          79.27 |        76.81 |           85.03 |             59.83 |             62.99 |         3.86 |             67.5  | swing              |               -0.49 |                 -1.86 |                  nan |
|      6 | CRDO      | CRDO                      | US       |               45.54 |             79.6  |         82.29 |         81.08 |          78.12 |        68.58 |           93.42 |             66.75 |             15.72 |         8.97 |             67.5  | short              |                2.81 |                 -0.84 |                  nan |
|      7 | TKA.DE    | TKA.DE                    | EUROPE   |                8.67 |             79.53 |         82.68 |         80.81 |          78.26 |        73.83 |          nan    |             83.86 |             59.03 |         6.38 |             64.66 | short              |                1.7  |                  2.87 |                  nan |
|      8 | HALO      | HALO                      | US       |               10.09 |             78.68 |         83.77 |         81.35 |          74.38 |        76.02 |           86.37 |             67.48 |             62.13 |         5.39 |             66.48 | short              |                0.98 |                nan    |                  nan |
|      9 | AKER.OL   | Aker ASA                  | EUROPE   |                9.88 |             78.49 |         82.9  |         76.04 |          80.07 |        76.91 |           88.54 |             77.94 |             56.03 |         3.39 |             74.34 | short              |               -1.81 |                 -0.76 |                  nan |
|     10 | PBF       | PBF                       | US       |                7.68 |             78.26 |         83.46 |         81.41 |          75.12 |        72.2  |           51.66 |             55.34 |             94.14 |         7.03 |             67.05 | short              |                0.49 |                 -3.13 |                  nan |
|     11 | CLMT      | CLMT                      | US       |                3.67 |             77.62 |         82.86 |         82.99 |          72.37 |        52.97 |           51.27 |             92.11 |              5.33 |         4.49 |             66.59 | swing              |               -0.69 |                 -3.01 |                  nan |
|     12 | FSLY      | FSLY                      | US       |                3.99 |             77.51 |         86.01 |         82.52 |          72.5  |        53.96 |           42.86 |             99.03 |             17.13 |         8.44 |             67.5  | short              |               -1.71 |                 -2.93 |                  nan |
|     13 | RNW       | RNW                       | US       |                2.15 |             76.63 |         78.59 |         74.78 |          73.9  |        78.47 |           85.54 |             84.1  |             81.64 |         6.14 |             65.68 | short              |                1.47 |                nan    |                  nan |
|     14 | AYA       | AYA                       | US       |                3.32 |             76.62 |         81.47 |         79.6  |          73.64 |        66.3  |           59.55 |            nan    |             57.71 |         8.05 |             65.68 | short              |                3.73 |                nan    |                  nan |
|     15 | RMAX      | RMAX                      | US       |                0.61 |             76.62 |         84.28 |         83.76 |          69.47 |        60.46 |           21.42 |             90.66 |             89.58 |         7.1  |             67.05 | short              |                0.3  |                  2.23 |                  nan |
|     16 | STX       | STX                       | US       |              194.67 |             76.54 |         83.75 |         75.14 |          77.95 |        70.13 |           84.7  |             67.84 |             34.46 |         7.36 |             67.5  | short              |                0.72 |                nan    |                  nan |
|     17 | NTAP      | NTAP                      | US       |               34.6  |             76.51 |         78.4  |         79.92 |          74.63 |        68.43 |           88.91 |             51.58 |             31.19 |         6.14 |             65.45 | swing              |               -0.42 |                 -3.03 |                  nan |
|     18 | AVT       | AVT                       | US       |                6.99 |             76.38 |         76.4  |         74.39 |          76.36 |        76.93 |           71.69 |             68.45 |             84.77 |         4.26 |             66.7  | long               |                3.16 |                nan    |                  nan |
|     19 | U         | U                         | US       |               17.27 |             76.27 |         85.08 |         85.51 |          67.46 |        51.71 |           46.57 |             97.09 |             24.91 |         8.32 |             67.5  | swing              |                0.33 |                 -0.32 |                  nan |
|     20 | BAX       | BAX                       | US       |               11.57 |             76.05 |         74.08 |         83.57 |          77.18 |        74.92 |           77.33 |             97.45 |             64.45 |         5.88 |             66.02 | swing              |               -2.74 |                  0.04 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE     | StoneCo Ltd.                                         | OTHER    |                1.95 |                  75.84 |                    74.26 |                 74.74 |              71.94 |                74.24 |                   25.76 |           94.1  |             39.66 |       0.638 |         nan |       nan |        1.55 |         3.97 |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.2  |                  72.71 |                    74.03 |                 75.96 |              73.88 |                87.16 |                   12.84 |           85.6  |             58.43 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.7  |                  80.83 |                    72.06 |                 69.23 |              74.75 |                66.91 |                   33.09 |           64.22 |             45.11 |       0.384 |         nan |       nan |       13.77 |         3.11 |          7.02 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              216.2  |                  68.23 |                    71.83 |                 73.25 |              68.32 |                77.85 |                   22.15 |           92.37 |             51.82 |     nan     |         nan |       nan |      nan    |         9.78 |          9.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | 0QXR.IL  | Stellantis N.V.                                      | OTHER    |               25.94 |                  71.25 |                    71.16 |                 71.24 |              71    |                70.02 |                   29.98 |           71.97 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.55 |                  71.05 |                    71.08 |                 72.75 |              70.34 |                68.91 |                   31.09 |           81.06 |             67.84 |       0.02  |         nan |       nan |        3.91 |         6.85 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | EMBC     | Embecta Corp.                                        | US       |                0.25 |                  80.19 |                    70.98 |                 69.18 |              74.26 |                59.78 |                   40.22 |           61.95 |             57.62 |       0.475 |         nan |       nan |        5.6  |         2.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.43 |                    70.77 |                 69.43 |              73.53 |                71.48 |                   28.52 |           63.46 |             56.32 |       0.577 |         nan |       nan |       -5.15 |         5.33 |          8.67 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            8 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.88 |                  63.26 |                    70.2  |                 73.12 |              66.33 |                72.16 |                   27.84 |           88.54 |             77.94 |       0.112 |         nan |       nan |        5.32 |        55.54 |          3.83 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            9 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.91 |                  69.07 |                    69.32 |                 68.86 |              70.15 |                74.44 |                   25.56 |           65.11 |            nan    |       0.254 |         nan |       nan |        1.54 |       nan    |          2.71 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.35 |                  74.66 |                    68.89 |                 67.87 |              70.6  |                72.82 |                   27.18 |           71    |             37.33 |       0.083 |         nan |       nan |        3.64 |         4.89 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           11 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               40.48 |                  64.89 |                    68.78 |                 70.64 |              66.13 |                71.08 |                   28.92 |           80.73 |            nan    |       0.427 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|           12 | AMCX     | AMC Global Media Inc.                                | US       |                0.43 |                  71.31 |                    68.52 |                 67.26 |              72.56 |                74.62 |                   25.38 |           49.21 |             77.81 |       2.013 |         nan |       nan |        7.08 |         4.37 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           13 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  70.56 |                    68.49 |                 69.6  |              67.86 |                71.04 |                   28.96 |           83.16 |             42.66 |     nan     |         nan |       nan |        3.93 |       160.88 |          4.66 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|           14 | AVGO     | Broadcom Inc.                                        | US       |             1611.98 |                  59.62 |                    68.04 |                 68.7  |              63.58 |                78.81 |                   21.19 |           81.34 |             64.75 |       0.015 |         nan |       nan |       45.5  |        20.09 |         65.3  |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           15 | IHS      | IHS Holding Limited                                  | OTHER    |                2.43 |                  73.36 |                    67.66 |                 67.39 |              71.84 |                59.62 |                   40.38 |           51.98 |             82.88 |      -0.125 |         nan |       nan |        7.07 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                                  | US       |              113.99 |                  64.27 |                    67.59 |                 68.74 |              65.06 |                73.51 |                   26.49 |           81.89 |             55.46 |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           16 | SAP.DE   | SAP SE                                               | EUROPE   |              207.27 |                  64.22 |                    67.35 |                 67.21 |              64.24 |                72.57 |                   27.43 |           80.05 |             49.44 |       0.044 |         nan |       nan |       17.52 |        21.46 |         26.88 |        1.8  |                 nan |              nan |                  12 |                  0.63 |
|           17 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  68.28 |                    67.31 |                 68.6  |              68.09 |                74.25 |                   25.75 |           73.56 |             55.69 |       0.982 |         nan |       nan |        5.3  |      -119.83 |          2.11 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BP       | BP                                                   | US       |               95.28 |                  58.2  |                    67.24 |                 70.29 |              63.1  |                78.32 |                   21.68 |           86.83 |             71    |     nan     |         nan |       nan |      nan    |         9.69 |         20.5  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.2  |                  72.71 |                    74.03 |                 75.96 |              73.88 |                87.16 |                   12.84 |           85.6  |             58.43 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            1 | STNE     | StoneCo Ltd.                                         | OTHER    |                1.95 |                  75.84 |                    74.26 |                 74.74 |              71.94 |                74.24 |                   25.76 |           94.1  |             39.66 |       0.638 |         nan |       nan |        1.55 |         3.97 |          3.48 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              216.2  |                  68.23 |                    71.83 |                 73.25 |              68.32 |                77.85 |                   22.15 |           92.37 |             51.82 |     nan     |         nan |       nan |      nan    |         9.78 |          9.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AKER.OL  | Aker ASA                                             | EUROPE   |                9.88 |                  63.26 |                    70.2  |                 73.12 |              66.33 |                72.16 |                   27.84 |           88.54 |             77.94 |       0.112 |         nan |       nan |        5.32 |        55.54 |          3.83 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.55 |                  71.05 |                    71.08 |                 72.75 |              70.34 |                68.91 |                   31.09 |           81.06 |             67.84 |       0.02  |         nan |       nan |        3.91 |         6.85 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | 0QXR.IL  | Stellantis N.V.                                      | OTHER    |               25.94 |                  71.25 |                    71.16 |                 71.24 |              71    |                70.02 |                   29.98 |           71.97 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|           11 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               40.48 |                  64.89 |                    68.78 |                 70.64 |              66.13 |                71.08 |                   28.92 |           80.73 |            nan    |       0.427 |         nan |       nan |        7.45 |       nan    |          2.63 |        0.68 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BP       | BP                                                   | US       |               95.28 |                  58.2  |                    67.24 |                 70.29 |              63.1  |                78.32 |                   21.68 |           86.83 |             71    |     nan     |         nan |       nan |      nan    |         9.69 |         20.5  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |                  70.56 |                    68.49 |                 69.6  |              67.86 |                71.04 |                   28.96 |           83.16 |             42.66 |     nan     |         nan |       nan |        3.93 |       160.88 |          4.66 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                                  | US       |               15    |                  59.16 |                    66.87 |                 69.47 |              62.8  |                77.53 |                   22.47 |           87.38 |             62.5  |     nan     |         nan |       nan |      nan    |        10.83 |         23.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |                  76.43 |                    70.77 |                 69.43 |              73.53 |                71.48 |                   28.52 |           63.46 |             56.32 |       0.577 |         nan |       nan |       -5.15 |         5.33 |          8.67 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            3 | VOW3.DE  | Volkswagen AG                                        | EUROPE   |               36.7  |                  80.83 |                    72.06 |                 69.23 |              74.75 |                66.91 |                   33.09 |           64.22 |             45.11 |       0.384 |         nan |       nan |       13.77 |         3.11 |          7.02 |        0.68 |                 nan |              nan |                  12 |                  0.63 |
|            6 | EMBC     | Embecta Corp.                                        | US       |                0.25 |                  80.19 |                    70.98 |                 69.18 |              74.26 |                59.78 |                   40.22 |           61.95 |             57.62 |       0.475 |         nan |       nan |        5.6  |         2.91 |          3.49 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               18.17 |                  61.3  |                    66.88 |                 68.97 |              61.87 |                76.59 |                   23.41 |           95.93 |             39.44 |     nan     |         nan |       nan |      nan    |        10.54 |         14.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | 0Q2N.IL  | K+S Aktiengesellschaft                               | OTHER    |                2.91 |                  69.07 |                    69.32 |                 68.86 |              70.15 |                74.44 |                   25.56 |           65.11 |            nan    |       0.254 |         nan |       nan |        1.54 |       nan    |          2.71 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BMY      | BMY                                                  | US       |              113.99 |                  64.27 |                    67.59 |                 68.74 |              65.06 |                73.51 |                   26.49 |           81.89 |             55.46 |     nan     |         nan |       nan |      nan    |         9.86 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | AVGO     | Broadcom Inc.                                        | US       |             1611.98 |                  59.62 |                    68.04 |                 68.7  |              63.58 |                78.81 |                   21.19 |           81.34 |             64.75 |       0.015 |         nan |       nan |       45.5  |        20.09 |         65.3  |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           17 | NWL.MI   | NewPrinces S.p.A.                                    | EUROPE   |                0.68 |                  68.28 |                    67.31 |                 68.6  |              68.09 |                74.25 |                   25.75 |           73.56 |             55.69 |       0.982 |         nan |       nan |        5.3  |      -119.83 |          2.11 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO      | FRO                                                  | US       |                8.11 |                  59.2  |                    65.61 |                 68.01 |              61.81 |                72.21 |                   27.79 |           85.01 |             61.89 |     nan     |         nan |       nan |      nan    |        10.67 |         10.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.35 |                  74.66 |                    68.89 |                 67.87 |              70.6  |                72.82 |                   27.18 |           71    |             37.33 |       0.083 |         nan |       nan |        3.64 |         4.89 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name   | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX    | US       |               11.57 |                     0.09 |    -0.07 |      0.17 |                  71.23 |                        82.55 |         74.08 |         83.57 |          77.18 |        74.92 |           77.33 |             97.45 |         5.88 |
|               2 | CCC      | CCC    | US       |                3.4  |                     0.06 |    -0.04 |      0.07 |                  79.21 |                        78.84 |         64.66 |         75.43 |          71.38 |        73.25 |           87.05 |             78.88 |         7.88 |
|               3 | BCRX     | BCRX   | US       |                2.19 |                     0.06 |     0.01 |      0.09 |                  63.92 |                        76.58 |         67.62 |         71.94 |          78.57 |        79.36 |           84.92 |             93.57 |         5.69 |
|               4 | NET      | NET    | US       |               94.39 |                     0.07 |    -0.01 |      0.13 |                  63.67 |                        75.25 |         75.79 |         80.22 |          69.93 |        52.76 |           58.4  |             92.72 |         6.78 |
|               5 | TIC      | TIC    | US       |                1.81 |                     0.09 |    -0.07 |      0.47 |                  70.59 |                        74.03 |         75.51 |         62.52 |          58.29 |        60.29 |           56.79 |             95.51 |         7.7  |
|               6 | SVM      | SVM    | US       |                2.28 |                     0.05 |    -0.02 |      0.34 |                  77.59 |                        73.65 |         71.06 |         57.71 |          70.43 |        77.6  |           72.08 |             80.46 |         7.82 |
|               7 | PLTR     | PLTR   | US       |              358.01 |                     0.04 |    -0.02 |      0.28 |                  63.59 |                        73.2  |         76.47 |         65.26 |          57.68 |        54.7  |           89.75 |             49.88 |         8.36 |
|               8 | SNOW     | SNOW   | US       |               98.79 |                     0.02 |    -0.01 |      0.2  |                  54.13 |                        72.61 |         74.35 |         83.75 |          67.52 |        47.42 |           42.64 |             93.93 |         8.87 |
|               9 | PANW     | PANW   | US       |              264.41 |                     0.05 |    -0.02 |      0.08 |                  75.46 |                        72.35 |         65.23 |         77.28 |          70.03 |        52.79 |           57.6  |             72.45 |         6.52 |
|              10 | BFLY     | BFLY   | US       |                2.07 |                     0.07 |    -0.07 |      0.35 |                  81.93 |                        72.33 |         72.67 |         79.51 |          69.36 |        51.53 |           47.27 |             72.21 |         8.38 |
|              11 | CAKE     | CAKE   | US       |                4.69 |                     0.07 |    -0.02 |      0.27 |                  66.28 |                        72.32 |         78.05 |         76.04 |          71.03 |        65.13 |           86.09 |             40.9  |         5.61 |
|              12 | CRWD     | CRWD   | US       |              188.05 |                     0.05 |    -0.05 |      0.08 |                  83.29 |                        72.02 |         62.51 |         76.97 |          67.37 |        46.59 |           41.67 |             84.71 |         6.72 |
|              13 | GH       | GH     | US       |               18.73 |                     0.04 |    -0.03 |      0.09 |                  71.47 |                        71.96 |         63.31 |         77.31 |          76.24 |        71.99 |           62.95 |             66.63 |         6.77 |
|              14 | EXK      | EXK    | US       |                2.59 |                     0.05 |    -0.01 |      0.35 |                  69.83 |                        71.91 |         76.22 |         55.92 |          60.11 |        68.46 |           60.36 |             75    |         8.01 |
|              15 | GL9.IR   | GL9.IR | EUROPE   |                5.54 |                     0.05 |    -0.05 |      0    |                  78.49 |                        71.9  |         46.95 |         62.78 |          73.81 |        70.66 |           97.41 |             61.65 |         2.21 |
|              16 | OKTA     | OKTA   | US       |               21.5  |                     0.08 |    -0.05 |     -0.03 |                  72.66 |                        71.78 |         47.91 |         73.4  |          71.62 |        60.81 |           69.11 |             69.05 |         7.49 |
|              17 | KLAR     | KLAR   | US       |                6.37 |                     0.06 |    -0.01 |      0.04 |                  68.4  |                        71.73 |         60.7  |         67.95 |          62.66 |        59.81 |           68.3  |             92.23 |         8.2  |
|              18 | ZD       | ZD     | US       |                1.61 |                     0.03 |     0    |     -0    |                  54.5  |                        71.15 |         61.4  |         78.63 |          77.94 |        72.6  |           52.59 |             87.62 |         5.29 |
|              19 | JHX      | JHX    | US       |               15.25 |                     0.02 |     0    |      0.22 |                  49.73 |                        70.96 |         79.85 |         77.51 |          64.33 |        60.29 |           59.05 |             78.4  |         6.83 |
|              20 | W        | W      | US       |               12.19 |                     0.11 |    -0    |      0.17 |                  36.06 |                        70.69 |         78.57 |         78.3  |          67.17 |        56.84 |           57.23 |             96.97 |         8.77 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NVDA     | NVIDIA Corporation           | US       |             4705.5  |             63.1  |         68.25 |         56.99 |          62.34 |        63.85 |           92.39 |             59.85 |             29.58 |         5.4  |             89.53 | short              |               -0.74 |                 -0.49 |                  nan |
|    nan | KSS      | Kohl's Corporation           | US       |                1.89 |             59.47 |         59.32 |         59.62 |          57.23 |        63.03 |           55.86 |             49    |             78.33 |         8.39 |             86.67 | long               |               -0.15 |                 -0.74 |                  nan |
|    nan | JOYY     | JOYY Inc.                    | OTHER    |                3.2  |             53.72 |         52.34 |         58.94 |          55.1  |        48.51 |           49.34 |             49.83 |             33.17 |         4.75 |             82.25 | swing              |               -0.11 |                nan    |                  nan |
|    nan | ATHM     | Autohome Inc.                | OTHER    |                2.24 |             42.7  |         47.7  |         48.37 |          37.71 |        35.01 |           32.89 |             29.14 |             36.79 |         5.89 |             78.55 | swing              |               -1.01 |                nan    |                  nan |
|    nan | YALA     | Yalla Group Limited          | OTHER    |                0.7  |             39.26 |         36.32 |         29.75 |          42.19 |        56.17 |           74.25 |             44.74 |             61.22 |         8.5  |             79.76 | long               |              nan    |                nan    |                  nan |
|    nan | FINV     | FinVolution Group            | OTHER    |                0.89 |             38.64 |         25.74 |         34.83 |          42.45 |        53.93 |           47.52 |             47.14 |             80    |         6.17 |             78.58 | long               |               -0.37 |                 -0.33 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.          | OTHER    |                1.26 |             36.8  |         25.43 |         33.53 |          40.07 |        53.41 |           44.85 |             37.04 |             89.29 |         7.12 |             78.48 | long               |               -2.08 |                 -0.63 |                  nan |
|    nan | WB       | Weibo Corporation            | OTHER    |                1.6  |             34.56 |         26.7  |         29.08 |          40.04 |        56.4  |           68.2  |             25.03 |             74.84 |         8.5  |             81.52 | long               |               -2.3  |                 -0.8  |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd. | OTHER    |                0.75 |             34.18 |         36.75 |         24.08 |          31.61 |        39.89 |           47.09 |             37.99 |             45.1  |         7.03 |             76.3  | long               |               -2.89 |                  0.05 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.          | OTHER    |                0.87 |             31.05 |         25.44 |         21.17 |          36.66 |        48.16 |           67.7  |             19.45 |             42.38 |         9.03 |             78.45 | long               |               -4.21 |                 -1.55 |                  nan |
|    nan | DQ       | Daqo New Energy Corp.        | OTHER    |                0.83 |             27.44 |         49.84 |         22.72 |          23.17 |        31.71 |           27.17 |             27    |             52.86 |         7.7  |             76.14 | short              |               -0.42 |                 -0.11 |                  nan |
|    nan | LI       | Li Auto Inc.                 | OTHER    |               10.52 |             24.23 |         31.56 |         23.11 |          23.66 |        24.8  |           27.36 |             39.63 |             19.92 |         6.85 |             76.54 | short              |               -2.74 |                 -1.01 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    563 | HFG.DE   | HFG.DE  | EUROPE   |                0.44 |             48.19 |         32.52 |         42.29 |          54.09 |        73    |          nan    |             94.78 |             89.13 |         6.86 |             64.66 | long               |                1.17 |                  5.01 |                  nan |
|    156 | AMV0.DE  | AMV0.DE | EUROPE   |                3.7  |             64.45 |         58.82 |         59.22 |          69.69 |        83.09 |           89.8  |             91.63 |             88.9  |         5.8  |             56.79 | long               |                0.11 |                  3.93 |                  nan |
|    122 | PRGO     | PRGO    | US       |                1.53 |             66.43 |         73.25 |         65.9  |          59.04 |        66.97 |           48.46 |             88.11 |             98.79 |         8.49 |             67.05 | short              |              nan    |                  3.56 |                  nan |
|    223 | KLAR     | KLAR    | US       |                6.37 |             61.68 |         60.7  |         67.95 |          62.66 |        59.81 |           68.3  |             92.23 |             40.77 |         8.2  |             58.75 | swing              |               -6.55 |                  3.42 |                  nan |
|      7 | TKA.DE   | TKA.DE  | EUROPE   |                8.67 |             79.53 |         82.68 |         80.81 |          78.26 |        73.83 |          nan    |             83.86 |             59.03 |         6.38 |             64.66 | short              |                1.7  |                  2.87 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    390 | REPL     | REPL   | US       |                1.18 |             55.65 |         79.59 |         64.8  |          46.49 |        28.43 |            2.91 |             35.68 |             15.6  |         9.91 |             62.61 | short              |              -11.4  |                 -7.9  |                  nan |
|    458 | ABSI     | ABSI   | US       |                1.37 |             52.66 |         57.8  |         58.5  |          47.51 |        30.63 |            3.86 |             18.81 |             30.02 |         9.07 |             63.64 | swing              |                0.7  |                 -7.6  |                  nan |
|    425 | NBIS     | NBIS   | US       |               63.1  |             54.11 |         77.82 |         55.79 |          52.42 |        44.99 |           57.02 |              1.09 |             18.91 |         8.85 |             64.66 | short              |               -2.18 |                 -7.56 |                  nan |
|    643 | AEVA     | AEVA   | US       |                1.43 |             41.61 |         64.25 |         45.35 |          37.86 |        28.64 |           35.23 |              1.09 |              2.13 |         9.05 |             63.64 | short              |                0.77 |                 -7.4  |                  nan |
|    433 | ADPT     | ADPT   | US       |                3.4  |             53.82 |         60.86 |         59.94 |          47.7  |        36.06 |           38.96 |              8.5  |              7.09 |         7.39 |             64.66 | short              |               -0.1  |                 -7.32 |                  nan |

## Duplicate-security checks

- HEADL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90

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
- Excluded by hard/data filters: **278**
- Event watch (otherwise eligible): **12**
- Final eligible: **710**
- Eligible change vs previous stored run: **+2**

Top exclusion categories:
- liquidity: 223
- price: 168
- market_cap: 150
- price_history: 20
- data_confidence: 18
- duplicate_listing: 3
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| AKER.OL | 9 | 8 |  | 3 | 2 | main,value,quality_value |
| PARR | 21 | 5 |  | 4 | 1 | value,quality_value |
| BION.SW | 50 | 2 |  | 1 | 1 | value,quality_value |
| EMBC | 229 | 6 |  | 10 | 1 | value,quality_value |
| 0QXR.IL | 495 | 4 |  | 5 | 1 | value,quality_value |
| MOMO | 599 | 7 | 242 | 8 | 1 | value,quality_value |
| STNE | 651 | 1 |  | 2 | 1 | value,quality_value |
| VOW3.DE | 659 | 3 | 287 | 9 | 1 | value,quality_value |
| JCAP | 1 |  |  |  | 1 | main |
| SSABBH.HE | 2 |  |  |  | 1 | main |
| ECO | 3 | 42 |  | 22 | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| MPC | 5 |  |  |  | 1 | main |
| CRDO | 6 |  |  |  | 1 | main |
| TKA.DE | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **700**
- Adaptive selected: **300**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **3** (JCAP, TKA.DE, HALO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (TIC, SVM)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MOMO | value+pullback | 71.63 | 76.43 | 77.03 | 63.46 | 56.32 | 71.48 | 45.46 |
| 2 | AVGO | value+pullback | 70.93 | 59.62 | 74.45 | 81.34 | 64.75 | 78.81 | 54.07 |
| 3 | VOW3.DE | value+pullback | 70.50 | 80.83 | 74.92 | 64.22 | 45.11 | 66.91 | 40.15 |
| 4 | IRS | value+pullback | 69.94 | 70.56 | 71.28 | 83.16 | 42.66 | 71.04 | 49.55 |
| 5 | 0P6O.IL | value+pullback | 69.46 | 64.89 | 74.67 | 80.73 |  | 71.08 | 41.87 |
| 6 | INVA | value+pullback | 65.12 | 61.50 | 56.96 | 84.32 | 38.76 | 79.52 | 45.17 |
| 7 | 1VOW3.MI | value+pullback | 64.20 | 66.40 | 70.76 | 64.22 | 37.42 | 66.07 | 39.22 |
| 8 | PBR-A | value+pullback | 63.85 | 73.63 | 67.80 | 54.53 | 67.87 | 49.23 | 56.60 |
| 9 | MSFT | value+pullback | 63.67 | 58.21 | 83.05 | 58.51 | 63.94 | 51.35 | 56.48 |
| 10 | VOLV-B.ST | value+pullback | 63.49 | 65.92 | 66.68 | 57.73 | 58.84 | 62.51 | 54.32 |
| 11 | VOW.DE | value+pullback | 63.08 | 64.89 | 70.21 | 64.22 | 34.25 | 65.00 | 36.00 |
| 12 | ALL-PH | value+pullback | 62.00 | 61.95 | 68.83 | 68.62 | 41.44 | 58.86 | 43.22 |
| 13 | CNC | value+pullback | 61.70 | 71.53 | 75.37 | 37.41 | 65.17 | 46.37 | 57.25 |
| 14 | ONIT | value+pullback | 61.62 | 70.58 | 73.45 | 61.00 | 44.71 | 42.29 | 44.84 |
| 15 | ORCL | value+pullback | 60.24 | 69.90 | 75.45 | 48.01 | 57.46 | 37.31 | 40.68 |
| 16 | WKC | value+pullback | 60.16 | 61.29 | 44.93 | 61.36 | 73.43 | 69.96 | 65.89 |
| 17 | PBR | value+pullback | 59.90 | 61.62 | 69.46 | 54.53 | 62.41 | 48.17 | 56.23 |
| 18 | MFA | value+pullback | 58.54 | 57.89 | 50.09 | 79.81 | 37.65 | 64.55 | 46.26 |
| 19 | BION.SW | value | 57.93 | 72.71 | 30.95 | 85.60 | 58.43 | 87.16 | 71.80 |
| 20 | CION | value+pullback | 57.51 | 63.27 | 73.82 | 35.11 | 57.65 | 45.21 | 48.87 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 10/10 | 8/10 | 0/10 | 66.8 | 7 / 3 |
| Top 25 | 24/25 | 23/25 | 25/25 | 22/25 | 0/25 | 67.0 | 20 / 5 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 66.6 | 38 / 12 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=5, large_20_100b=3
