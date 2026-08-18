# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-18

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

- **EUROPE:** 88.4/100
- **OTHER:** 78.4/100
- **US:** 85.4/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | ECO      | Okeanis Eco Tankers Corp.  | OTHER    |                2.12 |             81.19 |         87.68 |         82.27 |          80.1  |        69.27 |           86.84 |             85.13 |             18.24 |         4.67 |             80.75 | short              |                0.14 |                nan    |                  nan |
|      2 | PARR     | Par Pacific Holdings, Inc. | US       |                3.55 |             80.81 |         78.74 |         79.86 |          82.45 |        81.77 |           87.39 |             68.06 |             77.9  |         6.65 |             85.6  | medium             |                4.77 |                  0.01 |                  nan |
|      3 | HPE      | HPE                        | US       |               65.91 |             80.51 |         80.67 |         84.51 |          80.35 |        72.82 |           73.87 |             73.06 |             55.98 |         6.72 |             65.68 | swing              |                0.47 |                 -0.95 |                  nan |
|      4 | MU       | MU                         | US       |              987.27 |             80.1  |         76.69 |         76.15 |          83.52 |        84.19 |           95.06 |             57.4  |             75.12 |         8.09 |             67.5  | long               |              nan    |                  1.25 |                  nan |
|      5 | CRDO     | CRDO                       | US       |               45.57 |             79.2  |         82.02 |         80.86 |          77.53 |        67.66 |           92.21 |             66.5  |             15.01 |         8.9  |             67.5  | short              |               -0.4  |                  0.94 |                  nan |
|      6 | CLMT     | CLMT                       | US       |                3.67 |             78.35 |         85.27 |         84.25 |          72.45 |        52.55 |           50.67 |             93.2  |              4.79 |         4.53 |             66.59 | short              |                0.73 |                nan    |                  nan |
|      7 | PBF      | PBF                        | US       |                7.69 |             77.66 |         83.64 |         80.86 |          74.46 |        71.09 |           52.08 |             54.98 |             90.6  |         7.01 |             67.05 | short              |               -0.6  |                 -3    |                  nan |
|      8 | TWN      | TWN                        | US       |                0.49 |             77.62 |         75.29 |         70.47 |          79.96 |        80.54 |           77.83 |            nan    |             84.03 |         4.93 |             58.41 | long               |                8.86 |                  0.68 |                  nan |
|      9 | NOEJ.DE  | NOEJ.DE                    | EUROPE   |                0.59 |             76.99 |         79.92 |         78.7  |          75.29 |        70.21 |           94.84 |             89.81 |             28.36 |         4.38 |             65.68 | short              |              nan    |                nan    |                  nan |
|     10 | RMAX     | RMAX                       | US       |                0.61 |             76.94 |         84.56 |         83.97 |          69.91 |        60.64 |           22.87 |             91.87 |             87.95 |         7.06 |             67.05 | short              |                0.32 |                  1.47 |                  nan |
|     11 | FSLY     | FSLY                       | US       |                4    |             76.8  |         85.41 |         81.84 |          71.76 |        52.89 |           41.77 |             99.03 |             15.65 |         8.39 |             67.5  | short              |               -0.71 |                 -0.79 |                  nan |
|     12 | TKA.DE   | TKA.DE                     | EUROPE   |                8.67 |             76.71 |         81.3  |         78    |          75.41 |        69.06 |          nan    |             84.95 |             54.33 |         6.35 |             64.66 | short              |               -2.83 |                  0.55 |                  nan |
|     13 | NNBR     | NNBR                       | US       |                0.29 |             76.57 |         82.85 |         84.96 |          70.29 |        52.3  |           37.04 |             88.47 |             29.32 |         8.99 |             66.48 | swing              |                0.79 |                  1.37 |                  nan |
|     14 | STX      | STX                        | US       |              195.11 |             76.33 |         84.09 |         75.19 |          77.47 |        69.15 |           83.69 |             68.45 |             32.89 |         7.34 |             67.5  | short              |               -0.21 |                  1.09 |                  nan |
|     15 | PSX      | PSX                        | US       |               82.93 |             76.24 |         78.2  |         77.73 |          74.75 |        73.27 |           78.89 |             53.03 |             64.73 |         3.38 |             67.5  | short              |              nan    |                nan    |                  nan |
|     16 | U        | U                          | US       |               17.28 |             76.21 |         85.21 |         85.42 |          67.21 |        50.96 |           45.03 |             99.03 |             24.15 |         8.32 |             67.5  | swing              |               -0.06 |                  0.58 |                  nan |
|     17 | BAX      | BAX                        | US       |               11.57 |             76.2  |         75.53 |         83.95 |          76.88 |        74.15 |           76.13 |             97.94 |             63.62 |         5.83 |             66.02 | swing              |                0.15 |                  0.79 |                  nan |
|     18 | W        | W                          | US       |               11.76 |             76.16 |         83.03 |         81.29 |          71.02 |        56.34 |          nan    |             97.57 |             22.61 |         8.7  |             63.75 | short              |                3.43 |                  2.83 |                  nan |
|     19 | RNW      | RNW                        | US       |                2.15 |             76.13 |         80.12 |         75.63 |          73.25 |        76.64 |           81.6  |             85.19 |             80.26 |         6.07 |             65.68 | short              |               -0.5  |                  1.44 |                  nan |
|     20 | NTAP     | NTAP                       | US       |               34.57 |             76.11 |         78.24 |         79.54 |          73.98 |        66.85 |           86.17 |             53.28 |             29.24 |         6.18 |             65.45 | swing              |               -0.41 |                nan    |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.55 |                  75.83 |                    74.13 |                 75.97 |              73.15 |                65.24 |                   34.76 |           87.39 |             68.06 |       0.02  |         nan |       nan |        3.98 |         6.94 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | INVA     | Innoviva, Inc.                       | US       |                1.31 |                  76.2  |                    73.38 |                 74.02 |              73.66 |                82.47 |                   17.53 |           85.69 |             39.57 |       0.073 |         nan |       nan |        6.48 |         9.48 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              216.11 |                  66.71 |                    71.36 |                 73.12 |              67.45 |                78.58 |                   21.42 |           93.57 |             52.79 |     nan     |         nan |       nan |      nan    |         9.78 |          9.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | MOMO     | Hello Group Inc.                     | OTHER    |                0.73 |                  76.49 |                    71.16 |                 69.99 |              73.77 |                71.75 |                   28.25 |           64.51 |             57.88 |       0.576 |         nan |       nan |       -5.16 |         5.33 |          8.67 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            4 | TNK      | Teekay Tankers Ltd.                  | OTHER    |                2.67 |                  66.75 |                    70.28 |                 72.48 |              70.17 |                82.41 |                   17.59 |           76.65 |             72.81 |       0.073 |         nan |       nan |        3.75 |         9.77 |          5.02 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |               96.66 |                  79.68 |                    69.94 |                 68.18 |              74.44 |                56.83 |                   43.17 |           54.14 |             68.39 |       0.161 |         nan |       nan |        1.72 |         6.64 |          4.05 |        4.02 |                 nan |              nan |                  12 |                  0.63 |
|            6 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.2  |                  75.04 |                    69.54 |                 67.33 |              68.12 |                77.31 |                   22.69 |           86.81 |              1.78 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | PAH3.DE  | PAH3.DE                              | EUROPE   |                8.38 |                  63.64 |                    69.31 |                 71.1  |              68.66 |                79.76 |                   20.24 |          nan    |             84.83 |     nan     |         nan |       nan |      nan    |         1.85 |         88.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.35 |                  76.59 |                    69.1  |                 67.68 |              71.46 |                69.06 |                   30.94 |           68.12 |             38.83 |       0.083 |         nan |       nan |        3.74 |         4.89 |          4.11 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            8 | WKC      | World Kinect Corporation             | US       |                1.58 |                  70.03 |                    68.77 |                 69.7  |              69.92 |                67.41 |                   32.59 |           68.15 |             73.6  |       0.064 |         nan |       nan |        7    |        13.92 |        nan    |        1.32 |                 nan |              nan |                  11 |                  0.58 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1613.12 |                  59.62 |                    68.43 |                 69.28 |              63.75 |                79.38 |                   20.62 |           82.94 |             65.39 |       0.015 |         nan |       nan |       45.44 |        20.09 |         65.4  |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           10 | SU.PA    | Schneider Electric S.E.              | EUROPE   |              173.55 |                  60.1  |                    67.29 |                 68.17 |              63.37 |                74.73 |                   25.27 |           79.78 |             66.47 |       0.031 |         nan |       nan |       22.32 |        25.58 |         36.37 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|          nan | VOW.DE   | VOW.DE                               | EUROPE   |               37.2  |                  68.38 |                    67.25 |                 66.91 |              67.38 |                65.06 |                   34.94 |          nan    |             64.32 |     nan     |         nan |       nan |      nan    |         2.73 |          7.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | YALA     | Yalla Group Limited                  | OTHER    |                0.7  |                  66.46 |                    67.11 |                 68.46 |              66.07 |                76.07 |                   23.93 |           81.39 |             45.28 |     nan     |         nan |       nan |        0.04 |         6.1  |          6.94 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|           12 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              101.62 |                  74.54 |                    66.61 |                 64.99 |              70.08 |                55.85 |                   44.15 |           54.14 |             63.56 |       0.154 |         nan |       nan |        1.78 |         4.58 |          4.61 |        4.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                  | US       |              114.07 |                  63.94 |                    66.59 |                 67.47 |              64.62 |                71.79 |                   28.21 |           77.79 |             56.55 |     nan     |         nan |       nan |      nan    |         9.86 |         14.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                              | EUROPE   |               36.7  |                  69.06 |                    66.58 |                 65.86 |              66.85 |                61.43 |                   38.57 |          nan    |             60.68 |     nan     |         nan |       nan |      nan    |         3.11 |          7.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS      | IHS Holding Limited                  | OTHER    |                2.44 |                  73.82 |                    66.57 |                 65.44 |              72.03 |                58.78 |                   41.22 |           43.81 |             82.98 |      -0.125 |         nan |       nan |        7.07 |        15.15 |          5.11 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | DXC      | DXC Technology Company               | US       |                1.43 |                  83.39 |                    66.56 |                 61.09 |              71.95 |                45.68 |                   54.32 |           44.69 |             36.92 |       0.528 |         nan |       nan |        3.03 |         3.51 |         14.63 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|           15 | SIE.DE   | Siemens Aktiengesellschaft           | EUROPE   |              215.32 |                  69.72 |                    66.05 |                 63.88 |              68.3  |                66.56 |                   33.44 |           53.37 |             61.19 |       0.03  |         nan |       nan |       21.12 |        21.76 |         28.23 |        5.35 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.55 |                  75.83 |                    74.13 |                 75.97 |              73.15 |                65.24 |                   34.76 |           87.39 |             68.06 |       0.02  |         nan |       nan |        3.98 |         6.94 |          4.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | INVA     | Innoviva, Inc.                       | US       |                1.31 |                  76.2  |                    73.38 |                 74.02 |              73.66 |                82.47 |                   17.53 |           85.69 |             39.57 |       0.073 |         nan |       nan |        6.48 |         9.48 |          4.92 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              216.11 |                  66.71 |                    71.36 |                 73.12 |              67.45 |                78.58 |                   21.42 |           93.57 |             52.79 |     nan     |         nan |       nan |      nan    |         9.78 |          9.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | TNK      | Teekay Tankers Ltd.                  | OTHER    |                2.67 |                  66.75 |                    70.28 |                 72.48 |              70.17 |                82.41 |                   17.59 |           76.65 |             72.81 |       0.073 |         nan |       nan |        3.75 |         9.77 |          5.02 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAH3.DE  | PAH3.DE                              | EUROPE   |                8.38 |                  63.64 |                    69.31 |                 71.1  |              68.66 |                79.76 |                   20.24 |          nan    |             84.83 |     nan     |         nan |       nan |      nan    |         1.85 |         88.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | MOMO     | Hello Group Inc.                     | OTHER    |                0.73 |                  76.49 |                    71.16 |                 69.99 |              73.77 |                71.75 |                   28.25 |           64.51 |             57.88 |       0.576 |         nan |       nan |       -5.16 |         5.33 |          8.67 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            8 | WKC      | World Kinect Corporation             | US       |                1.58 |                  70.03 |                    68.77 |                 69.7  |              69.92 |                67.41 |                   32.59 |           68.15 |             73.6  |       0.064 |         nan |       nan |        7    |        13.92 |        nan    |        1.32 |                 nan |              nan |                  11 |                  0.58 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1613.12 |                  59.62 |                    68.43 |                 69.28 |              63.75 |                79.38 |                   20.62 |           82.94 |             65.39 |       0.015 |         nan |       nan |       45.44 |        20.09 |         65.4  |        0.44 |                 nan |              nan |                  12 |                  0.63 |
|           11 | YALA     | Yalla Group Limited                  | OTHER    |                0.7  |                  66.46 |                    67.11 |                 68.46 |              66.07 |                76.07 |                   23.93 |           81.39 |             45.28 |     nan     |         nan |       nan |        0.04 |         6.1  |          6.94 |        0.59 |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                                  | US       |               15.01 |                  58.38 |                    65.85 |                 68.32 |              62.16 |                76.2  |                   23.8  |           84.05 |             64.08 |     nan     |         nan |       nan |      nan    |        10.83 |         23.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |               96.66 |                  79.68 |                    69.94 |                 68.18 |              74.44 |                56.83 |                   43.17 |           54.14 |             68.39 |       0.161 |         nan |       nan |        1.72 |         6.64 |          4.05 |        4.02 |                 nan |              nan |                  12 |                  0.63 |
|           10 | SU.PA    | Schneider Electric S.E.              | EUROPE   |              173.55 |                  60.1  |                    67.29 |                 68.17 |              63.37 |                74.73 |                   25.27 |           79.78 |             66.47 |       0.031 |         nan |       nan |       22.32 |        25.58 |         36.37 |        1.85 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.17 |                  58.6  |                    65.6  |                 68.13 |              60.13 |                77.14 |                   22.86 |           96.42 |             40.53 |     nan     |         nan |       nan |      nan    |        10.54 |         14.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.35 |                  76.59 |                    69.1  |                 67.68 |              71.46 |                69.06 |                   30.94 |           68.12 |             38.83 |       0.083 |         nan |       nan |        3.74 |         4.89 |          4.11 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | DHT      | DHT                                  | US       |                2.63 |                  62.32 |                    66.03 |                 67.62 |              62.3  |                70.55 |                   29.45 |           87.57 |             47.33 |     nan     |         nan |       nan |      nan    |        10.13 |          6.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              114.07 |                  63.94 |                    66.59 |                 67.47 |              64.62 |                71.79 |                   28.21 |           77.79 |             56.55 |     nan     |         nan |       nan |      nan    |         9.86 |         14.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.2  |                  75.04 |                    69.54 |                 67.33 |              68.12 |                77.31 |                   22.69 |           86.81 |              1.78 |       0.822 |         nan |       nan |      nan    |       -82.86 |          2.22 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | VOW.DE   | VOW.DE                               | EUROPE   |               37.2  |                  68.38 |                    67.25 |                 66.91 |              67.38 |                65.06 |                   34.94 |          nan    |             64.32 |     nan     |         nan |       nan |      nan    |         2.73 |          7.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           16 | STNG     | Scorpio Tankers Inc.                 | OTHER    |                3.48 |                  62.96 |                    66.02 |                 66.56 |              63.06 |                78.12 |                   21.88 |           84.06 |             36.65 |       0.068 |         nan |       nan |        3.64 |        13.86 |          4.95 |        2.46 |                 nan |              nan |                  12 |                  0.63 |
|           18 | DAC      | Danaos Corporation                   | OTHER    |                2.3  |                  62.71 |                    64.78 |                 66.28 |              64.55 |                76.92 |                   23.08 |           72.75 |             55.54 |       0.002 |         nan |       nan |        3.91 |         5.97 |          4.81 |        0.12 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX     | US       |               11.57 |                     0.08 |    -0.06 |      0.18 |                  72.03 |                        82.7  |         75.53 |         83.95 |          76.88 |        74.15 |           76.13 |             97.94 |         5.83 |
|               2 | CCC      | CCC     | US       |                3.4  |                     0.05 |    -0.03 |      0.08 |                  75.6  |                        79.08 |         67.82 |         76.67 |          71.85 |        72.92 |           86.48 |             80.7  |         7.85 |
|               3 | NET      | NET     | US       |               94.45 |                     0.07 |    -0.01 |      0.13 |                  64.57 |                        75.72 |         77.3  |         80.74 |          70.09 |        52.69 |           58.3  |             93.33 |         6.77 |
|               4 | PLTR     | PLTR    | US       |              358.26 |                     0.04 |    -0.02 |      0.27 |                  69.04 |                        74    |         76.14 |         65.28 |          57.76 |        54.44 |           89.28 |             51.46 |         8.3  |
|               5 | SNOW     | SNOW    | US       |               98.86 |                     0.02 |    -0.02 |      0.2  |                  55.78 |                        73.62 |         74.54 |         83.96 |          68.32 |        48.35 |           45.21 |             94.9  |         8.79 |
|               6 | GH       | GH      | US       |               18.75 |                     0.05 |    -0.04 |      0.08 |                  77.81 |                        73.47 |         62.8  |         77.35 |          76.77 |        72.76 |           64.53 |             68.08 |         6.76 |
|               7 | KLAR     | KLAR    | US       |                6.37 |                     0.05 |     0    |      0.05 |                  69.84 |                        73.05 |         64.56 |         69.53 |          63.34 |        59.5  |           68.51 |             94.05 |         8.17 |
|               8 | PANW     | PANW    | US       |              264.6  |                     0.05 |    -0.03 |      0.08 |                  76.76 |                        72.89 |         65.82 |         77.55 |          70.09 |        52.69 |           57.93 |             73.42 |         6.49 |
|               9 | CRWD     | CRWD    | US       |              188.19 |                     0.05 |    -0.05 |      0.08 |                  84.51 |                        72.43 |         63.04 |         77.22 |          67.25 |        46.05 |           41.3  |             85.92 |         6.71 |
|              10 | ERO      | ERO     | US       |                3.15 |                     0.03 |    -0.03 |      0.41 |                  67.67 |                        72.25 |         76.54 |         68.79 |          70.17 |        77.79 |           82.55 |             48.79 |         7.34 |
|              11 | JHX      | JHX     | US       |               15.26 |                     0.03 |    -0.01 |      0.21 |                  58.15 |                        71.89 |         78.78 |         77.1  |          64    |        59.48 |           59.1  |             79.73 |         6.79 |
|              12 | OKTA     | OKTA    | US       |               21.7  |                     0.08 |    -0.05 |     -0.03 |                  72.81 |                        71.76 |         48.97 |         73.74 |          71.22 |        59.53 |           66.5  |             71.12 |         7.47 |
|              13 | BRZE     | BRZE    | US       |                2.72 |                     0.06 |    -0.02 |      0.07 |                  74.47 |                        71.69 |         64.76 |         74.07 |          64.19 |        50.18 |           45.88 |             95.39 |         8.41 |
|              14 | GL9.IR   | GL9.IR  | EUROPE   |                5.54 |                     0.05 |    -0.05 |      0    |                  78.49 |                        71.56 |         46.67 |         61.56 |          72.56 |        69.07 |           97.8  |             62.99 |         2.23 |
|              15 | BFLY     | BFLY    | US       |                2.08 |                     0.03 |    -0.03 |      0.4  |                  66.83 |                        71.34 |         76.3  |         81.06 |          69.76 |        51.88 |           48.94 |             73.3  |         8.36 |
|              16 | AVTR     | AVTR    | US       |                7.89 |                     0.06 |    -0.02 |      0.27 |                  71.88 |                        70.68 |         77.07 |         81.06 |          62.9  |        50.66 |           22.58 |             99.03 |         7.53 |
|              17 | SHOP     | SHOP    | US       |              165.25 |                     0.06 |    -0.04 |      0.19 |                  78.65 |                        70.03 |         72.72 |         66.58 |          55.6  |        49.4  |           72.4  |             49.27 |         7.57 |
|              18 | ELF      | ELF     | US       |                4.78 |                     0.05 |    -0.02 |      0.17 |                  77.11 |                        69.76 |         68.46 |         70.34 |          56.66 |        50.4  |           59.25 |             74.51 |         8.26 |
|              19 | EXLS     | EXLS    | US       |                4.56 |                     0.04 |    -0.01 |      0.23 |                  62.31 |                        69.7  |         72.53 |         63.84 |          58.78 |        63.83 |           79.97 |             54    |         6.98 |
|              20 | SWON.SW  | SWON.SW | EUROPE   |                2.06 |                     0.06 |    -0.06 |      0.07 |                  86.41 |                        69.57 |         55.88 |         64.73 |          66.08 |        60.8  |           57.09 |             85.5  |         4.93 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.89 |             63.03 |         61.88 |         63.02 |          63.04 |        71.4  |           73.48 |             49.57 |             79.75 |         8.35 |             87.57 | long               |                3.56 |                 -0.68 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4708.83 |             61.81 |         68.51 |         57.09 |          61.57 |        62.05 |           91.12 |             60.39 |             25.96 |         5.39 |             89.53 | short              |               -1.29 |                  2.04 |                  nan |
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.77 |             59.68 |         63.88 |         66.75 |          55.48 |        51    |           51.24 |             50.96 |             56.12 |         8.23 |             86.86 | swing              |               10.66 |                 -1.09 |                  nan |
|    nan | JOYY     | JOYY Inc.                                            | OTHER    |                3.2  |             53.92 |         52.44 |         59.18 |          55.4  |        48.52 |           50.66 |             50.42 |             30.56 |         4.75 |             82.25 | swing              |                0.2  |                nan    |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             50.18 |         41.2  |         45.16 |          55.2  |        65.01 |           86.73 |             44.07 |             55.24 |         3.84 |             75.81 | long               |                0.63 |                 -0.18 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.75 |             41.34 |         42.22 |         32.58 |          40.47 |        47.39 |           50.38 |             67.16 |             50.46 |         6.96 |             77.1  | long               |                7.16 |                  0.7  |                  nan |
|    nan | ATHM     | Autohome Inc.                                        | OTHER    |                2.24 |             39.71 |         42.8  |         46.67 |          36.63 |        34.03 |           30.56 |             29.62 |             36.59 |         8.5  |             78.55 | swing              |               -2.99 |                nan    |                  nan |
|    nan | WB       | Weibo Corporation                                    | OTHER    |                1.6  |             35.58 |         28.02 |         30.11 |          41.05 |        57.71 |           70.69 |             25.5  |             75.44 |         8.5  |             81.52 | long               |                1.02 |                 -0.38 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.87 |             34.76 |         28.52 |         23.97 |          41    |        55.27 |           76.4  |             19.84 |             53    |         9.01 |             78.45 | long               |                3.71 |                 -1.08 |                  nan |
|    nan | DQ       | Daqo New Energy Corp.                                | OTHER    |                0.83 |             32.73 |         51.83 |         25.05 |          26.79 |        38.66 |           30.43 |             27.54 |             71.29 |         8.5  |             76.14 | short              |                5.29 |                 -0.13 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    315 | RGNX     | RGNX   | US       |                0.65 |             58.13 |         64.98 |         62.33 |          53.93 |        47.51 |           58.25 |             36.77 |             21.06 |         9.29 |             63.64 | short              |                1.3  |                  3.66 |                  nan |
|    455 | INSM     | INSM   | US       |               24.21 |             50.94 |         67.13 |         55.25 |          46.64 |        43.17 |           58.14 |             70.39 |              2.16 |         8.67 |             66.48 | short              |                0.81 |                  3.35 |                  nan |
|    394 | YMM      | YMM    | US       |                7.99 |             54.13 |         36.99 |         51.66 |          56.6  |        62.98 |           56.17 |             82.28 |             75.72 |         6.13 |             65.11 | long               |                0.09 |                  3.3  |                  nan |
|    409 | UNIT     | UNIT   | US       |                2.07 |             53.37 |         44.46 |         41.31 |          63.97 |        62.28 |           83.48 |            nan    |             23.61 |         5.28 |             60.32 | medium             |               10.06 |                  2.95 |                  nan |
|    157 | SYY      | SYY    | US       |               33.86 |             64.61 |         77.84 |         65.45 |          59.24 |        63.78 |           81.35 |             52.31 |             43.34 |         3.44 |             65.45 | short              |               11.44 |                  2.93 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    377 | ABCL     | ABCL   | US       |                2.97 |             54.86 |         74.29 |         64.6  |          45.11 |        33.51 |            9.88 |             11.04 |             43.29 |         8.99 |             63.64 | short              |               -0.28 |                 -5.79 |                  nan |
|    442 | RBI.VI   | RBI.VI | EUROPE   |               20.64 |             51.5  |         62.88 |         56.38 |          46.62 |        39.81 |           12.39 |             10.56 |             66.07 |         3.63 |             66.14 | short              |               -2.06 |                 -5.31 |                  nan |
|    537 | GLE.PA   | GLE.PA | EUROPE   |               60.22 |             47    |         55.05 |         51.2  |          42.8  |        38.94 |            6.79 |             27.06 |             70.49 |         3.54 |             67.5  | short              |               -9.96 |                 -5.17 |                  nan |
|    379 | REPL     | REPL   | US       |                1.19 |             54.84 |         78.44 |         63.83 |          45.86 |        27.72 |            2.95 |             34.22 |             14.58 |         9.91 |             62.61 | short              |               -0.8  |                 -5.13 |                  nan |
|    363 | UMAC     | UMAC   | OTHER    |                1.3  |             55.4  |         70.61 |         59.13 |          51.67 |        42.7  |           52.83 |              6.8  |             17.24 |         9.1  |             64.66 | short              |               -5.24 |                 -4.99 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.93
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90
- `risk_adj_mom_126d_rank` vs `dist_sma_200_rank`: r=0.85

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
- Excluded by hard/data filters: **288**
- Event watch (otherwise eligible): **10**
- Final eligible: **702**
- Eligible change vs previous stored run: **-8**

Top exclusion categories:
- liquidity: 231
- price: 176
- market_cap: 157
- price_history: 19
- data_confidence: 18
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 2 | 1 |  | 1 | 2 | main,value,quality_value |
| TNK | 34 | 4 |  | 3 | 1 | value,quality_value |
| WKC | 55 | 8 | 56 | 5 | 1 | value,quality_value |
| SU.PA | 81 | 10 |  | 9 | 1 | value,quality_value |
| GSL | 155 | 7 |  | 10 | 1 | value,quality_value |
| PBR-A | 320 | 5 | 149 | 8 | 1 | value,quality_value |
| AVGO | 393 | 9 | 89 | 6 | 1 | value,quality_value |
| MOMO | 544 | 3 | 191 | 4 | 1 | value,quality_value |
| INVA | 546 | 2 | 212 | 2 | 1 | value,quality_value |
| ECO | 1 | 38 |  | 24 | 1 | main |
| HPE | 3 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |
| CRDO | 5 |  |  |  | 1 | main |
| CLMT | 6 |  |  |  | 1 | main |
| PBF | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (MU, CRDO, CLMT, PBF, NOEJ.DE, RMAX)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (CCC, NET, KLAR, PANW)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | MOMO | value+pullback | 72.02 | 76.49 | 77.03 | 64.51 | 57.88 | 71.75 | 46.53 |
| 2 | AVGO | value+pullback | 71.43 | 59.62 | 74.76 | 82.94 | 65.39 | 79.38 | 54.15 |
| 3 | INVA | value+pullback | 70.40 | 76.20 | 56.96 | 85.69 | 39.57 | 82.47 | 46.41 |
| 4 | YALA | value+pullback | 68.31 | 66.46 | 65.69 | 81.39 | 45.28 | 76.07 | 41.80 |
| 5 | PBR-A | value+pullback | 66.78 | 79.68 | 66.18 | 54.14 | 68.39 | 56.83 | 57.80 |
| 6 | PBR | value+pullback | 65.14 | 74.54 | 68.54 | 54.14 | 63.56 | 55.85 | 59.13 |
| 7 | MSFT | value+pullback | 64.79 | 58.21 | 83.74 | 62.56 | 64.72 | 52.68 | 57.06 |
| 8 | WKC | value+pullback | 63.27 | 70.03 | 44.78 | 68.15 | 73.60 | 67.41 | 70.74 |
| 9 | ALL-PH | value+pullback | 61.80 | 67.18 | 60.07 | 72.33 | 43.50 | 57.16 | 45.55 |
| 10 | ORCL | value+pullback | 61.11 | 69.90 | 75.68 | 51.27 | 58.54 | 38.41 | 41.01 |
| 11 | MFA | value+pullback | 59.35 | 58.11 | 51.08 | 81.36 | 38.32 | 65.56 | 46.95 |
| 12 | SIE.DE | value+pullback | 58.91 | 69.72 | 42.24 | 53.37 | 61.19 | 66.56 | 59.70 |
| 13 | GL9.IR | pullback | 57.51 | 43.56 | 78.49 | 97.80 | 62.99 | 84.57 | 65.31 |
| 14 | DXC | value+pullback | 57.39 | 83.39 | 51.37 | 44.69 | 36.92 | 45.68 | 51.50 |
| 15 | CION | value+pullback | 57.18 | 63.25 | 73.82 | 38.17 | 57.48 | 41.35 | 49.90 |
| 16 | PARR | value | 55.71 | 75.83 | 50.02 | 87.39 | 68.06 | 65.24 | 80.81 |
| 17 | TV | value+pullback | 55.68 | 69.44 | 51.50 | 45.38 | 32.46 | 59.59 | 43.85 |
| 18 | AAPL | value+pullback | 55.54 | 62.00 | 44.72 | 67.47 | 46.71 | 54.86 | 50.67 |
| 19 | CHTR | value+pullback | 55.42 | 62.53 | 69.93 | 53.91 | 42.56 | 34.20 | 42.71 |
| 20 | TNK | value | 55.28 | 66.75 | 30.95 | 76.65 | 72.81 | 82.41 | 73.74 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 10/10 | 9/10 | 0/10 | 67.0 | 4 / 6 |
| Top 25 | 23/25 | 24/25 | 24/25 | 21/25 | 0/25 | 67.0 | 5 / 20 |
| Top 50 | 48/50 | 49/50 | 48/50 | 45/50 | 0/50 | 66.6 | 17 / 33 |

Top-10 market-cap mix: micro_250m_1b=3, small_1_5b=3, mid_5_20b=1, large_20_100b=2, mega_100b_plus=1
