# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-14

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

- **EUROPE:** 80.6/100
- **OTHER:** 71.9/100
- **US:** 82.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               96.82 |             84.37 |         84.29 |         89.06 |          84.44 |        77.93 |           84.2  |             81.28 |             53.27 |         3.44 |             69.68 | swing              |               -0.33 |                nan    |               nan    |
|      2 | SM       | SM                         | US       |                7.81 |             84.35 |         86.61 |         82.9  |          81.53 |        85.79 |           85.48 |             72.44 |             95.73 |         7.07 |             68.2  | short              |                1.54 |                  3.01 |                 2.74 |
|      3 | FRO      | FRO                        | US       |                9.44 |             83.97 |         88.13 |         85.31 |          82.63 |        79.98 |           91.49 |             67.38 |             58.59 |         5.7  |             69.68 | short              |               -0.38 |                  0.78 |                 0.33 |
|      4 | CRGY     | CRGY                       | US       |                4.97 |             83.81 |         88.86 |         85.43 |          80.02 |        82.19 |           69.08 |             89.55 |             93.99 |         6.32 |             69.23 | short              |               -0.04 |                  1.2  |                 0.88 |
|      5 | HPE      | HPE                        | US       |               70.99 |             82.81 |         84.92 |         85.36 |          80.69 |        71.24 |           72.53 |             77.11 |             48.25 |         6.87 |             68.89 | swing              |               -0.32 |                  1.82 |                 1.5  |
|      6 | DK       | DK                         | US       |                4.01 |             82.14 |         88.92 |         87.18 |          77.1  |        63.49 |           54.58 |             88.44 |             39.61 |         7.38 |             69.23 | short              |                0.04 |                  0.71 |                 0.12 |
|      7 | PBF      | PBF                        | US       |                7.99 |             80.91 |         81.76 |         86.96 |          80.07 |        74.32 |           51.21 |             81.12 |             87.88 |         7.64 |             69.23 | swing              |               -0.09 |                  0.57 |                -0.07 |
|      8 | DELL     | DELL                       | US       |              310.67 |             80.53 |         89.4  |         84.4  |          76.65 |        64.31 |           71.21 |             69.4  |             27.42 |         7.81 |             68.77 | short              |               -0.4  |                  0.18 |                -0.21 |
|      9 | PARR     | Par Pacific Holdings, Inc. | US       |                3.65 |             79.82 |         78.93 |         82.12 |          80.71 |        77.35 |           80.98 |             74.1  |             64.66 |         7.1  |             84.91 | swing              |               -0.09 |                  0.45 |                 0.2  |
|     10 | ANF      | ANF                        | US       |                5.31 |             79.7  |         89.75 |         82.73 |          76.68 |        75.01 |           88.2  |             64.03 |             54.33 |         8.61 |             67.64 | short              |              nan    |                  1.43 |               nan    |
|     11 | SHELL.AS | SHELL.AS                   | EUROPE   |              240.25 |             79.48 |         83.31 |         76.9  |          75.39 |        82.07 |           90.79 |             78.1  |             74.35 |         2.42 |             69.68 | short              |                2.67 |                  3.38 |                 2.68 |
|     12 | DINO     | DINO                       | US       |               16.51 |             79.14 |         82.62 |         85.13 |          75.66 |        66.28 |           47.67 |             76.16 |             67.64 |         4.51 |             69.68 | swing              |               -0.28 |                  0.35 |                -0.16 |
|     13 | TRMD     | TRMD                       | US       |                3.09 |             78.88 |         86.41 |         78.73 |          75.84 |        79.03 |           83.43 |             46.49 |             82.62 |         5.33 |             69.68 | short              |              nan    |                nan    |               nan    |
|     14 | KIN.BR   | KIN.BR                     | EUROPE   |                1.28 |             78.86 |         85.82 |         82.22 |          75.5  |        66.74 |           87.23 |             66.53 |             23.7  |         3.75 |             69.68 | short              |                0.45 |                  0.41 |                 0.28 |
|     15 | BAYN.DE  | BAYN.DE                    | EUROPE   |               48.65 |             78.72 |         72.74 |         77.44 |          80.12 |        80.01 |          nan    |             86.43 |             69.74 |         6.49 |             66.84 | medium             |                3.28 |                  1.27 |                 0.84 |
|     16 | AVAH     | AVAH                       | US       |                2.65 |             78.58 |         88.58 |         82.45 |          74.71 |        70.07 |           91.56 |             49.57 |             34.94 |         7.75 |             68.66 | short              |               -0.71 |                  1.8  |                 1.83 |
|     17 | EQNR     | EQNR                       | US       |               91.53 |             77.45 |         83.12 |         79.14 |          75.77 |        72.02 |           73.06 |             77.05 |             54.61 |         5.61 |             68.66 | short              |               -0.37 |                  0.95 |               nan    |
|     18 | NAT      | NAT                        | US       |                1.36 |             77.39 |         85.33 |         79.42 |          75.36 |        71.41 |           90.91 |             45.07 |             38.21 |         5.17 |             69.23 | short              |                0.87 |                  1.47 |                 1.25 |
|     19 | BIRG.IR  | BIRG.IR                    | EUROPE   |               19.1  |             77.36 |         78.83 |         72.67 |          75.99 |        78.73 |           95.4  |             60.61 |             63.63 |         2.22 |             69.68 | short              |                1.58 |                  0.71 |                 0.17 |
|     20 | APA      | APA                        | US       |               13.5  |             77.26 |         83.21 |         78.67 |          75.86 |        74.14 |           72.02 |             71.87 |             66.49 |         5.87 |             68.66 | short              |               -0.25 |                  1.04 |                 0.62 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.57 |                  81.82 |                    79.05 |                 78.6  |              79.44 |                69.92 |                   30.08 |           78.03 |            nan    |       0.443 |         nan |       nan |        1.16 |       nan    |          0.73 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.08 |                  75.21 |                    75.57 |                 77.46 |              75.58 |                85.92 |                   14.08 |           87.11 |             59.65 |       0.85  |         nan |       nan |      nan    |       -80.12 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  67.42 |                    73.38 |                 76.36 |              70.4  |                85.62 |                   14.38 |           94.01 |             64.5  |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | BBWI     | Bath & Body Works, Inc.              | US       |                3.23 |                  82.54 |                    72.07 |                 68.49 |              72.88 |                53.22 |                   46.78 |           70.25 |             38.7  |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.29 |                  71.1  |                    71.34 |                 70.98 |              71.98 |                75.53 |                   24.47 |           68.05 |            nan    |       0.225 |         nan |       nan |        1.54 |       nan    |          3.07 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  68.09 |                    71.23 |                 73.87 |              69.41 |                80.47 |                   19.53 |           89.28 |             58.93 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA     | NVIDIA Corporation                   | US       |             4540.11 |                  60.87 |                    70.49 |                 72.39 |              65.51 |                77.06 |                   22.94 |           86.9  |             78.06 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            8 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.65 |                  68.12 |                    70.41 |                 72.7  |              69.28 |                71.24 |                   28.76 |           80.98 |             74.1  |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              240.25 |                  58.99 |                    70.22 |                 73.79 |              65.68 |                85.55 |                   14.45 |           90.79 |             78.1  |     nan     |         nan |       nan |      nan    |         9.69 |         10.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | STNE     | StoneCo Ltd.                         | OTHER    |                2.01 |                  72.72 |                    70.13 |                 69.84 |              68.64 |                69.61 |                   30.39 |           84.18 |             37.52 |       0.595 |         nan |       nan |        1.63 |         4.38 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                 | US       |              238.33 |                  66.19 |                    69.97 |                 71.09 |              68.8  |                75.48 |                   24.52 |           74.56 |             75.62 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              102.26 |                  58.57 |                    69.59 |                 73.2  |              65.56 |                82.09 |                   17.91 |           86.46 |             86.14 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | MOMO     | Hello Group Inc.                     | OTHER    |                0.61 |                  77.75 |                    69.33 |                 67.1  |              72.49 |                71.05 |                   28.95 |           63.46 |             37.26 |       0.845 |         nan |       nan |       -5.96 |         4.79 |          4.9  |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                   | US       |                7.81 |                  63.62 |                    69.3  |                 71.64 |              65.98 |                71.85 |                   28.15 |           85.48 |             72.44 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | AVGO     | Broadcom Inc.                        | US       |             1488.38 |                  60.81 |                    68.95 |                 69.81 |              63.08 |                79.32 |                   20.68 |           92.11 |             50.16 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.05 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.1  |                  57.97 |                    68.05 |                 71.42 |              62.67 |                82.62 |                   17.38 |           95.4  |             60.61 |     nan     |         nan |       nan |      nan    |        11.07 |         15    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               44.98 |                  64.51 |                    67.91 |                 69.48 |              65.68 |                70.39 |                   29.61 |           77.88 |            nan    |       0.384 |         nan |       nan |        7.45 |       nan    |          2.93 |        0.62 |                 nan |              nan |                   9 |                  0.47 |
|           13 | UNIT     | Uniti Group Inc.                     | US       |                2.11 |                  80.26 |                    67.53 |                 64.77 |              69.43 |                46.04 |                   53.96 |           66.83 |             33.56 |      -0.106 |         nan |       nan |        9.11 |       -14.18 |          2.62 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           14 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.69 |                  74.98 |                    67.43 |                 66.74 |              71.27 |                50.93 |                   49.07 |           52.72 |             81.24 |       0.141 |         nan |       nan |        1.8  |         4.75 |          4.83 |        5.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY      | NLY                                  | US       |               14.22 |                  67.83 |                    67.39 |                 67.58 |              64.32 |                69.85 |                   30.15 |           88.83 |             29.17 |     nan     |         nan |       nan |      nan    |         7.04 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                  | OTHER    |               14.57 |                  81.82 |                    79.05 |                 78.6  |              79.44 |                69.92 |                   30.08 |           78.03 |            nan    |       0.443 |         nan |       nan |        1.16 |       nan    |          0.73 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.08 |                  75.21 |                    75.57 |                 77.46 |              75.58 |                85.92 |                   14.08 |           87.11 |             59.65 |       0.85  |         nan |       nan |      nan    |       -80.12 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  67.42 |                    73.38 |                 76.36 |              70.4  |                85.62 |                   14.38 |           94.01 |             64.5  |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.58 |                  68.09 |                    71.23 |                 73.87 |              69.41 |                80.47 |                   19.53 |           89.28 |             58.93 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              240.25 |                  58.99 |                    70.22 |                 73.79 |              65.68 |                85.55 |                   14.45 |           90.79 |             78.1  |     nan     |         nan |       nan |      nan    |         9.69 |         10.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                               | US       |              102.26 |                  58.57 |                    69.59 |                 73.2  |              65.56 |                82.09 |                   17.91 |           86.46 |             86.14 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.65 |                  68.12 |                    70.41 |                 72.7  |              69.28 |                71.24 |                   28.76 |           80.98 |             74.1  |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA     | NVIDIA Corporation               | US       |             4540.11 |                  60.87 |                    70.49 |                 72.39 |              65.51 |                77.06 |                   22.94 |           86.9  |             78.06 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                               | US       |                7.81 |                  63.62 |                    69.3  |                 71.64 |              65.98 |                71.85 |                   28.15 |           85.48 |             72.44 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               19.1  |                  57.97 |                    68.05 |                 71.42 |              62.67 |                82.62 |                   17.38 |           95.4  |             60.61 |     nan     |         nan |       nan |      nan    |        11.07 |         15    |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                             | US       |              238.33 |                  66.19 |                    69.97 |                 71.09 |              68.8  |                75.48 |                   24.52 |           74.56 |             75.62 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft           | OTHER    |                3.29 |                  71.1  |                    71.34 |                 70.98 |              71.98 |                75.53 |                   24.47 |           68.05 |            nan    |       0.225 |         nan |       nan |        1.54 |       nan    |          3.07 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                              | US       |               14.73 |                  57.48 |                    67.34 |                 70.54 |              63.24 |                80.18 |                   19.82 |           86.05 |             74.24 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                              | US       |                9.44 |                  57.39 |                    66.75 |                 70.19 |              61.73 |                75.94 |                   24.06 |           91.49 |             67.38 |     nan     |         nan |       nan |      nan    |        10.82 |          7.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                              | US       |               15.86 |                  54.6  |                    66.21 |                 69.86 |              61.44 |                82.98 |                   17.02 |           88.22 |             71.95 |     nan     |         nan |       nan |      nan    |        13.79 |         22.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | STNE     | StoneCo Ltd.                     | OTHER    |                2.01 |                  72.72 |                    70.13 |                 69.84 |              68.64 |                69.61 |                   30.39 |           84.18 |             37.52 |       0.595 |         nan |       nan |        1.63 |         4.38 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                    | US       |             1488.38 |                  60.81 |                    68.95 |                 69.81 |              63.08 |                79.32 |                   20.68 |           92.11 |             50.16 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.05 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|           12 | 0P6O.IL  | Volkswagen AG                    | OTHER    |               44.98 |                  64.51 |                    67.91 |                 69.48 |              65.68 |                70.39 |                   29.61 |           77.88 |            nan    |       0.384 |         nan |       nan |        7.45 |       nan    |          2.93 |        0.62 |                 nan |              nan |                   9 |                  0.47 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               24.3  |                  56.05 |                    65.39 |                 68.59 |              59.81 |                79.32 |                   20.68 |           94.79 |             51.79 |     nan     |         nan |       nan |      nan    |        11.7  |         11.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | BBWI     | Bath & Body Works, Inc.          | US       |                3.23 |                  82.54 |                    72.07 |                 68.49 |              72.88 |                53.22 |                   46.78 |           70.25 |             38.7  |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.76 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name               | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ANF      | ANF                | US       |                5.31 |                     0.05 |     0.01 |      0.33 |                  61.23 |                        81.31 |         89.75 |         82.73 |          76.68 |        75.01 |           88.2  |             64.03 |         8.61 |
|               2 | KIN.BR   | KIN.BR             | EUROPE   |                1.28 |                     0.03 |    -0    |      0.16 |                  56.13 |                        78.75 |         85.82 |         82.22 |          75.5  |        66.74 |           87.23 |             66.53 |         3.75 |
|               3 | SRAIL.SW | SRAIL.SW           | EUROPE   |                3.06 |                     0.08 |    -0.01 |      0.22 |                  58.81 |                        76.07 |         83.84 |         77.18 |          70.57 |        63.32 |           73.01 |             71.55 |         5.63 |
|               4 | AMC      | AMC                | US       |                1.89 |                     0.09 |    -0.03 |     -0.06 |                  59.04 |                        76.04 |         48.82 |         71.95 |          79.65 |        80.18 |           86.83 |             92.27 |         9.67 |
|               5 | WT       | WT                 | US       |                3.12 |                     0.04 |    -0.04 |      0.05 |                  75.25 |                        76.01 |         72.04 |         79.92 |          73.98 |        63.32 |           69.78 |             72.04 |         5.77 |
|               6 | AGRO     | AGRO               | US       |                1.46 |                     0.06 |     0.01 |      0.3  |                  66.33 |                        75.72 |         81.78 |         61.38 |          65.53 |        72.5  |           64.25 |             80.2  |         7.42 |
|               7 | KRX.IR   | KRX.IR             | EUROPE   |               17.93 |                     0.05 |    -0.04 |     -0    |                  80.85 |                        74.75 |         62.35 |         68.95 |          70.99 |        66.71 |           97.06 |             58.24 |         5.49 |
|               8 | RAND.AS  | RAND.AS            | EUROPE   |                6.74 |                     0.05 |     0.01 |     -0.01 |                  62.73 |                        73.7  |         65.6  |         78    |          72.44 |        66.45 |           75.47 |             68.01 |         6.98 |
|               9 | MU       | MU                 | US       |              948.71 |                     0.05 |     0.02 |      0.03 |                  63.21 |                        73.48 |         67.44 |         67.27 |          84.24 |        85.37 |           95.98 |             73.91 |         8.3  |
|              10 | NVDA     | NVIDIA Corporation | US       |             4540.11 |                     0.05 |    -0.04 |     -0.03 |                  81.22 |                        73.48 |         61.14 |         64.41 |          68.56 |        69.39 |           86.9  |             78.06 |         5.79 |
|              11 | SBSW     | SBSW               | US       |                7.81 |                     0.04 |    -0.04 |      0.2  |                  77.05 |                        73.39 |         75.78 |         68.99 |          64.46 |        70.22 |           57.58 |             82.82 |         8.64 |
|              12 | SNOW     | SNOW               | US       |               99.97 |                     0.08 |    -0.08 |     -0.02 |                  79.64 |                        73.19 |         61.57 |         78.24 |          67.57 |        46.63 |           42.89 |             90.29 |         8.08 |
|              13 | BEN      | BEN                | US       |               14.73 |                     0.04 |     0    |     -0.01 |                  60.3  |                        72.03 |         60.85 |         69.28 |          77.78 |        78.21 |           86.05 |             74.24 |         3.3  |
|              14 | C5H.IR   | C5H.IR             | EUROPE   |                1.69 |                     0.05 |    -0.01 |      0.07 |                  73.24 |                        71.82 |         73.2  |         66.69 |          68.71 |        75.7  |           97.06 |             32.17 |         2.63 |
|              15 | CF       | CF                 | US       |               17.35 |                     0.04 |    -0.03 |      0.14 |                  74.38 |                        71.81 |         76.91 |         68.44 |          62.26 |        64.18 |           63.4  |             63.42 |         5.17 |
|              16 | EOG      | EOG                | US       |               66.58 |                     0.04 |     0.01 |      0.04 |                  57    |                        71.75 |         72.99 |         66.02 |          68.1  |        73.3  |           80.2  |             71.09 |         3.48 |
|              17 | BMNR     | BMNR               | US       |               13.01 |                     0.05 |    -0.05 |      0.37 |                  85.68 |                        71.69 |         74.45 |         65.31 |          53.73 |        54.08 |           73.31 |             46.31 |         9.59 |
|              18 | OKTA     | OKTA               | US       |               25.07 |                     0.04 |    -0.02 |      0.07 |                  66.89 |                        71.57 |         78.44 |         77.3  |          70    |        57.34 |           68.37 |             57.64 |         7.8  |
|              19 | WDAY     | WDAY               | US       |               38.55 |                     0.1  |    -0.1  |     -0.1  |                  70.56 |                        71.3  |         46.83 |         70.83 |          65.63 |        61.9  |           73.03 |             71.33 |         8.69 |
|              20 | ABNB     | ABNB               | US       |               87.78 |                     0.11 |    -0.08 |     -0.08 |                  62.59 |                        71.04 |         48.91 |         69.47 |          70.4  |        62.98 |           85.77 |             65.07 |         5.17 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.61 |             41.51 |         38.35 |         35.46 |          44.66 |        51.34 |           77.39 |             51.85 |                26 |         3.31 |             89.74 | long               |                  -0 |                  1.47 |                 1.52 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    143 | STR.VI   | STR.VI                 | EUROPE   |               12.42 |             65.36 |         87.77 |         71.33 |          59.39 |        52.28 |          nan    |             56.39 |             35.44 |         5.58 |             66.84 | short              |                0.82 |                  4.6  |               nan    |
|    267 | SAP.DE   | SAP SE                 | EUROPE   |              209.79 |             59.77 |         63.5  |         59.51 |          55.7  |        60.04 |           84.06 |             50.91 |             43.49 |         6.52 |             88.48 | short              |                6.13 |                  4.38 |                 4.34 |
|    145 | SDF.DE   | K+S Aktiengesellschaft | EUROPE   |                3    |             65.29 |         75.32 |         60.23 |          60.23 |        70.34 |           86.8  |             39.41 |             60.33 |         4.9  |             82.14 | short              |                3.83 |                  4.12 |               nan    |
|    477 | AMP.MI   | AMP.MI                 | EUROPE   |                3.03 |             52.31 |         39.03 |         57.97 |          54.92 |        49.7  |          nan    |             57.47 |             44.63 |         6.23 |             66.84 | swing              |               13.45 |                  3.87 |                 3.33 |
|    319 | IHS      | IHS Holding Limited    | OTHER    |                2.47 |             57.82 |         65.86 |         56.14 |          56.62 |        59.02 |           54.33 |             78.19 |             58.8  |         2.6  |             72.86 | short              |               -1.31 |                  3.46 |                 3.45 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    553 | HQH      | Abrdn Healthcare Investors    | US       |                1.07 |             48.5  |         38.85 |         58.62 |          54.76 |        42.23 |           41.95 |            nan    |             18.87 |         2.48 |             59.6  | swing              |               -8.86 |                 -4.5  |               nan    |
|    495 | HQL      | Abrdn Life Sciences Investors | US       |                0.52 |             51.66 |         42.35 |         60.44 |          57.56 |        45.77 |           46.86 |            nan    |             20.75 |         2.6  |             59.6  | swing              |               -1.51 |                 -4.29 |                -3.52 |
|    683 | 0QXR.IL  | Stellantis N.V.               | OTHER    |               14.57 |             36.59 |         20.89 |         23.64 |          49.53 |        69.97 |           78.03 |            nan    |             90.5  |         9.03 |             69.59 | long               |              -24.83 |                 -4.11 |                -3.14 |
|    611 | AMV0.DE  | Aumovio SE                    | EUROPE   |                3.67 |             45.04 |         51.93 |         34.21 |          40.11 |        49.97 |           51.08 |             33.19 |             71.37 |         6.32 |             76.66 | short              |              -21.96 |                 -3.51 |                -3.26 |
|    405 | GOLD     | Gold.com, Inc.                | US       |                1.21 |             54.51 |         74.36 |         55.14 |          53.89 |        50.06 |           40.87 |             67.99 |             33.26 |         7.13 |             77.52 | short              |               -0.25 |                 -3.47 |               nan    |

## Duplicate-security checks

- SDLFL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.87

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
- Excluded by hard/data filters: **282**
- Event watch (otherwise eligible): **1**
- Final eligible: **717**
- Eligible change vs previous stored run: **-5**

Top exclusion categories:
- liquidity: 228
- price: 181
- market_cap: 167
- price_history: 12
- data_confidence: 7
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 9 | 8 |  | 5 | 2 | main,value,quality_value |
| NVDA | 120 | 7 | 10 | 6 | 2 | value,pullback,quality_value |
| ANF | 10 |  | 1 |  | 2 | main,pullback |
| DDI | 73 | 3 | 24 | 3 | 1 | value,quality_value |
| 0Q2N.IL | 83 | 5 |  | 7 | 1 | value,quality_value |
| BION.SW | 112 | 2 | 45 | 2 | 1 | value,quality_value |
| IRWD | 195 | 6 | 76 | 4 | 1 | value,quality_value |
| STNE | 562 | 9 | 238 | 8 | 1 | value,quality_value |
| 0QXR.IL | 683 | 1 |  | 1 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| SM | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |
| CRGY | 4 |  |  |  | 1 | main |
| HPE | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (VLO, SM, FRO, CRGY, HPE, DK, PBF, DELL)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 75.85 | 75.21 | 68.27 | 87.11 | 59.65 | 85.92 | 67.03 |
| 2 | NVDA | value+pullback | 74.82 | 60.87 | 81.22 | 86.90 | 78.06 | 77.06 | 66.49 |
| 3 | IRWD | value+pullback | 74.02 | 68.09 | 72.84 | 89.28 | 58.93 | 80.47 | 62.98 |
| 4 | DDI | value+pullback | 72.19 | 67.42 | 57.15 | 94.01 | 64.50 | 85.62 | 69.51 |
| 5 | ETG | value+pullback | 68.83 | 57.93 | 71.03 | 67.90 | 80.31 | 77.40 | 59.74 |
| 6 | BBWI | value+pullback | 67.69 | 82.54 | 71.52 | 70.25 | 38.70 | 53.22 | 50.75 |
| 7 | INVA | value+pullback | 67.49 | 58.70 | 69.84 | 86.28 | 37.39 | 78.70 | 46.21 |
| 8 | STNE | value+pullback | 66.90 | 72.72 | 59.12 | 84.18 | 37.52 | 69.61 | 48.15 |
| 9 | 0Q2N.IL | value+pullback | 66.69 | 71.10 | 60.18 | 68.05 |  | 75.53 | 68.77 |
| 10 | SDF.DE | value+pullback | 66.35 | 65.38 | 60.53 | 86.80 | 39.41 | 73.21 | 65.29 |
| 11 | MAGN | value+pullback | 66.14 | 72.36 | 70.81 | 68.70 | 37.39 | 63.42 | 44.13 |
| 12 | AVGO | value+pullback | 65.97 | 60.81 | 52.10 | 92.11 | 50.16 | 79.32 | 52.95 |
| 13 | DEC | value+pullback | 63.93 | 58.69 | 85.93 | 60.90 | 51.41 | 52.82 | 56.01 |
| 14 | XNET | value+pullback | 63.66 | 58.92 | 63.61 | 57.83 | 80.56 | 66.74 | 43.97 |
| 15 | AMV0.DE | value+pullback | 62.54 | 68.81 | 71.85 | 51.08 | 33.19 | 64.77 | 45.04 |
| 16 | WKC | value+pullback | 62.23 | 56.45 | 57.50 | 62.39 | 76.91 | 69.36 | 65.77 |
| 17 | KSS | value+pullback | 61.44 | 73.59 | 67.38 | 50.62 | 64.24 | 42.51 | 52.45 |
| 18 | 0P6O.IL | value+pullback | 61.42 | 64.51 | 45.24 | 77.88 |  | 70.39 | 56.01 |
| 19 | NOVO-B.CO | value+pullback | 60.66 | 63.25 | 67.51 | 61.80 | 54.40 | 50.51 | 47.18 |
| 20 | ALL-PH | value+pullback | 60.63 | 62.21 | 58.58 | 69.96 | 44.42 | 61.95 | 48.41 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.2 | 2 / 8 |
| Top 25 | 24/25 | 25/25 | 25/25 | 24/25 | 0/25 | 69.2 | 3 / 22 |
| Top 50 | 48/50 | 49/50 | 49/50 | 47/50 | 1/50 | 69.2 | 10 / 40 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
