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

- **EUROPE:** 81.1/100
- **OTHER:** 73.6/100
- **US:** 82.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               96.82 |             84.73 |         84.54 |         89.22 |          84.91 |        78.84 |           85.28 |             81.03 |             55.02 |         3.42 |             69.68 | swing              |                0.03 |                nan    |               nan    |
|      2 | FRO      | FRO                        | US       |                9.44 |             84.38 |         88.41 |         85.65 |          83.11 |        80.73 |           91.96 |             68.16 |             60.18 |         5.68 |             69.68 | short              |                0.03 |                  0.86 |                 0.39 |
|      3 | CRGY     | CRGY                       | US       |                4.17 |             83.88 |         88.9  |         85.44 |          80.06 |        82.32 |           69.31 |             89.62 |             94.14 |         6.32 |             69.23 | short              |                0.03 |                  1.21 |                 0.89 |
|      4 | HPE      | HPE                        | US       |               70.99 |             83.16 |         85.36 |         85.48 |          80.97 |        71.73 |           72.49 |             77.61 |             49.87 |         6.85 |             68.89 | swing              |                0.04 |                  1.89 |                 1.55 |
|      5 | SM       | SM                         | US       |                7.81 |             82.98 |         86.23 |         82.4  |          80.2  |        83.56 |           79.92 |             72.69 |             95.65 |         7.06 |             68.66 | short              |                0.18 |                  2.73 |                 2.53 |
|      6 | DK       | DK                         | US       |                4.01 |             82.1  |         89.1  |         87.13 |          77.06 |        63.68 |           54.22 |             87.88 |             40.97 |         7.37 |             69.68 | short              |               -0    |                  0.7  |                 0.12 |
|      7 | DELL     | DELL                       | US       |              310.67 |             81.03 |         89.67 |         84.76 |          77.29 |        65.17 |           72.9  |             70.05 |             27.78 |         7.8  |             68.77 | short              |                0.1  |                  0.28 |                -0.13 |
|      8 | PBF      | PBF                        | US       |                7.99 |             81.03 |         81.95 |         86.87 |          80.1  |        74.5  |           51.77 |             80.69 |             87.91 |         7.65 |             69.23 | swing              |                0.02 |                  0.59 |                -0.05 |
|      9 | PARR     | Par Pacific Holdings, Inc. | US       |                3.65 |             79.93 |         79.23 |         82.05 |          80.63 |        77.31 |           80.98 |             73.5  |             64.66 |         7.12 |             84.91 | swing              |                0.01 |                  0.47 |                 0.21 |
|     10 | DINO     | DINO                       | US       |               16.51 |             79.45 |         82.8  |         85.27 |          76.11 |        67.16 |           48.99 |             76.13 |             68.85 |         4.5  |             69.68 | swing              |                0.04 |                  0.42 |                -0.12 |
|     11 | AVAH     | AVAH                       | US       |                2.65 |             79.27 |         88.86 |         82.98 |          75.56 |        71.06 |           93.05 |             51.01 |             35.56 |         7.75 |             68.66 | short              |               -0.02 |                  1.93 |                 1.93 |
|     12 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             78.39 |         86.29 |         82.08 |          74.69 |        65.03 |           87.18 |             67.13 |             18.08 |         3.76 |             69.68 | short              |               -0.02 |                  0.31 |                 0.21 |
|     13 | EQNR     | EQNR                       | US       |               91.53 |             77.89 |         83.42 |         79.39 |          76.39 |        73.05 |           74.44 |             77.16 |             56.37 |         5.59 |             68.66 | short              |                0.07 |                  1.04 |               nan    |
|     14 | APA      | APA                        | US       |               13.5  |             77.54 |         83.4  |         78.81 |          76.27 |        74.8  |           72.68 |             72.12 |             67.85 |         5.85 |             68.66 | short              |                0.03 |                  1.1  |                 0.66 |
|     15 | HAFN     | HAFN                       | US       |                4.04 |             77.46 |         85.28 |         81.75 |          73.17 |        69.36 |           70.92 |             61.97 |             58.09 |         5.53 |             69.68 | short              |                0    |                  3.1  |               nan    |
|     16 | SHELL.AS | SHELL.AS                   | EUROPE   |              236.84 |             77.37 |         83.63 |         75.01 |          74.12 |        79.72 |           91.46 |             77.75 |             66.34 |         2.41 |             69.68 | short              |                0.56 |                  2.96 |                 2.36 |
|     17 | DSX      | DSX                        | US       |                0.32 |             77.33 |         83.93 |         71.64 |          71.61 |        83.02 |           90.34 |             30.5  |             98.48 |         6.3  |             67.86 | short              |                0    |                  0.41 |                -0.26 |
|     18 | PAA      | PAA                        | US       |               15.86 |             77.25 |         85.79 |         78.03 |          76.46 |        75.93 |           89.21 |             72.67 |             52.53 |         2.06 |             68.89 | short              |                0.06 |                  2.67 |               nan    |
|     19 | DHT      | DHT                        | US       |                3.06 |             77.22 |         85.19 |         78.77 |          75.08 |        75.67 |           89.3  |             45.62 |             58.62 |         4.86 |             69.68 | short              |                0.15 |                  1.27 |                 1.37 |
|     20 | REP.MC   | REP.MC                     | EUROPE   |               30.91 |             77.19 |         79.67 |         80.43 |          74.71 |        71.34 |           58.25 |             75.7  |             73.9  |         3.67 |             69.68 | swing              |                0.09 |                  3.23 |                 2.81 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  76.12 |                    75.89 |                 77.45 |              76.46 |                86.94 |                   13.06 |           84.64 |             59.99 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI     | Bath & Body Works, Inc.              | US       |                3.23 |                  82.54 |                    72.1  |                 68.53 |              72.91 |                53.3  |                   46.7  |           70.25 |             38.87 |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            3 | STNE     | StoneCo Ltd.                         | OTHER    |                2.01 |                  74.97 |                    71.29 |                 70.74 |              70.18 |                69.51 |                   30.49 |           84.18 |             36.91 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  68.09 |                    71.23 |                 73.86 |              69.4  |                80.48 |                   19.52 |           89.28 |             58.87 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  64.22 |                    71.04 |                 74.23 |              67.63 |                82.69 |                   17.31 |           92.69 |             65.05 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4540.11 |                  60.87 |                    70.52 |                 72.44 |              65.54 |                77.1  |                   22.9  |           86.9  |             78.35 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              236.84 |                  59.25 |                    70.47 |                 74.06 |              65.88 |                85.78 |                   14.22 |           91.46 |             77.75 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.65 |                  68.12 |                    70.33 |                 72.59 |              69.19 |                71.1  |                   28.9  |           80.98 |             73.5  |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                   | US       |              102.26 |                  58.56 |                    69.66 |                 73.31 |              65.57 |                82.3  |                   17.7  |           86.91 |             85.91 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              238.33 |                  66.36 |                    69.4  |                 70.25 |              68.66 |                74.1  |                   25.9  |           71.85 |             75.38 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1488.38 |                  60.81 |                    68.97 |                 69.85 |              63.1  |                79.38 |                   20.62 |           92.11 |             50.31 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.23 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|            9 | MOMO     | Hello Group Inc.                     | OTHER    |                0.61 |                  77.82 |                    68.11 |                 65.32 |              72.02 |                68.17 |                   31.83 |           58.02 |             37.15 |       0.845 |         nan |       nan |       -5.96 |         4.79 |          4.9  |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                   | US       |                7.81 |                  63.29 |                    67.83 |                 69.74 |              65.28 |                69.16 |                   30.84 |           79.92 |             72.69 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.33 |                  70.11 |                    67.77 |                 66.45 |              69.7  |                68.07 |                   31.93 |           58.88 |            nan    |       0.223 |         nan |       nan |        1.54 |       nan    |          3.1  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | NLY      | NLY                                  | US       |               14.22 |                  68.05 |                    67.6  |                 67.79 |              64.53 |                70.02 |                   29.98 |           89.06 |             29.32 |     nan     |         nan |       nan |      nan    |         7.04 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.73 |                  57.56 |                    67.52 |                 70.75 |              63.41 |                80.48 |                   19.52 |           86.21 |             74.81 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | UNIT     | Uniti Group Inc.                     | US       |                2.11 |                  80.26 |                    67.47 |                 64.68 |              69.37 |                45.94 |                   54.06 |           66.83 |             33.1  |      -0.106 |         nan |       nan |        9.11 |       -14.18 |          2.62 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           12 | SAP.DE   | SAP SE                               | EUROPE   |              204.59 |                  68.99 |                    67.43 |                 66.02 |              66.17 |                63.39 |                   36.61 |           71.3  |             50.9  |       0.044 |         nan |       nan |       17.3  |        21.19 |         26.54 |        1.55 |                 nan |              nan |                  12 |                  0.63 |
|           13 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.69 |                  74.98 |                    67.38 |                 66.67 |              71.22 |                50.87 |                   49.13 |           52.72 |             80.8  |       0.141 |         nan |       nan |        1.8  |         4.75 |          4.83 |        5.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.44 |                  57.79 |                    67.23 |                 70.69 |              62.19 |                76.47 |                   23.53 |           91.96 |             68.16 |     nan     |         nan |       nan |      nan    |        10.82 |          7.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.06 |                  76.12 |                    75.89 |                 77.45 |              76.46 |                86.94 |                   13.06 |           84.64 |             59.99 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | DDI      | DoubleDown Interactive Co., Ltd.                     | OTHER    |                0.54 |                  64.22 |                    71.04 |                 74.23 |              67.63 |                82.69 |                   17.31 |           92.69 |             65.05 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              236.84 |                  59.25 |                    70.47 |                 74.06 |              65.88 |                85.78 |                   14.22 |           91.46 |             77.75 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.58 |                  68.09 |                    71.23 |                 73.86 |              69.4  |                80.48 |                   19.52 |           89.28 |             58.87 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                                   | US       |              102.26 |                  58.56 |                    69.66 |                 73.31 |              65.57 |                82.3  |                   17.7  |           86.91 |             85.91 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.65 |                  68.12 |                    70.33 |                 72.59 |              69.19 |                71.1  |                   28.9  |           80.98 |             73.5  |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                                   | US       |             4540.11 |                  60.87 |                    70.52 |                 72.44 |              65.54 |                77.1  |                   22.9  |           86.9  |             78.35 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN      | BEN                                                  | US       |               14.73 |                  57.56 |                    67.52 |                 70.75 |              63.41 |                80.48 |                   19.52 |           86.21 |             74.81 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  74.97 |                    71.29 |                 70.74 |              70.18 |                69.51 |                   30.49 |           84.18 |             36.91 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                                  | US       |                9.44 |                  57.79 |                    67.23 |                 70.69 |              62.19 |                76.47 |                   23.53 |           91.96 |             68.16 |     nan     |         nan |       nan |      nan    |        10.82 |          7.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                                  | US       |               15.86 |                  54.87 |                    66.72 |                 70.45 |              61.84 |                83.71 |                   16.29 |           89.21 |             72.67 |     nan     |         nan |       nan |      nan    |        13.79 |         22.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               19.21 |                  55.24 |                    66.65 |                 70.43 |              60.85 |                82.91 |                   17.09 |           95.64 |             61.48 |     nan     |         nan |       nan |      nan    |        11.13 |         15.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              238.33 |                  66.36 |                    69.4  |                 70.25 |              68.66 |                74.1  |                   25.9  |           71.85 |             75.38 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                                        | US       |             1488.38 |                  60.81 |                    68.97 |                 69.85 |              63.1  |                79.38 |                   20.62 |           92.11 |             50.31 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.23 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                                   | US       |                7.81 |                  63.29 |                    67.83 |                 69.74 |              65.28 |                69.16 |                   30.84 |           79.92 |             72.69 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BBWI     | Bath & Body Works, Inc.                              | US       |                3.23 |                  82.54 |                    72.1  |                 68.53 |              72.91 |                53.3  |                   46.7  |           70.25 |             38.87 |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                                               | EUROPE   |               24.39 |                  54.51 |                    64.85 |                 68.35 |              58.98 |                80.03 |                   19.97 |           95.28 |             53.28 |     nan     |         nan |       nan |      nan    |        11.74 |         12.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                                   | US       |              948.71 |                  48.13 |                    62.73 |                 68.08 |              55.66 |                75.28 |                   24.72 |           95.79 |             74.56 |     nan     |         nan |       nan |      nan    |         6.25 |         22.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY                                                  | US       |               52.92 |                  50.77 |                    63.71 |                 67.97 |              58.72 |                78.72 |                   21.28 |           85.28 |             80    |     nan     |         nan |       nan |      nan    |        15.31 |         18.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.13 |                  66.67 |                    66.49 |                 67.94 |              65.19 |                72.63 |                   27.37 |           83.5  |             41.13 |     nan     |         nan |       nan |        3.93 |        60    |          4.65 |        2.73 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name               | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | SRAIL.SW | SRAIL.SW           | EUROPE   |                3.12 |                     0.06 |    -0    |      0.21 |                  67.25 |                        79.2  |         85.85 |         78.48 |          71.25 |        63.17 |           76.73 |             72.26 |         5.59 |
|               2 | KIN.BR   | KIN.BR             | EUROPE   |                1.29 |                     0.02 |    -0    |      0.17 |                  52.98 |                        78.6  |         86.29 |         82.08 |          74.69 |        65.03 |           87.18 |             67.13 |         3.76 |
|               3 | WT       | WT                 | US       |                3.12 |                     0.04 |    -0.04 |      0.05 |                  75.25 |                        76.43 |         72.25 |         80.26 |          74.45 |        64.15 |           70.66 |             72.55 |         5.76 |
|               4 | AGRO     | AGRO               | US       |                1.46 |                     0.06 |     0.01 |      0.3  |                  66.33 |                        75.67 |         81.76 |         61.21 |          65.55 |        72.8  |           65.52 |             78.24 |         7.4  |
|               5 | AMC      | AMC                | US       |                1.89 |                     0.09 |    -0.03 |     -0.06 |                  59.04 |                        75.5  |         48.77 |         71.6  |          79.06 |        79.37 |           85.56 |             91.54 |         9.67 |
|               6 | RAND.AS  | RAND.AS            | EUROPE   |                6.59 |                     0.07 |    -0.04 |     -0.05 |                  71.48 |                        74.22 |         51.73 |         75.22 |          71.8  |        65.31 |           77.87 |             68.73 |         6.95 |
|               7 | MU       | MU                 | US       |              948.71 |                     0.05 |     0.02 |      0.03 |                  63.21 |                        73.81 |         67.98 |         67.49 |          84.37 |        85.49 |           95.79 |             74.56 |         8.28 |
|               8 | METSO.HE | METSO.HE           | EUROPE   |               14.76 |                     0.05 |     0    |      0.08 |                  69.3  |                        73.81 |         78    |         64.19 |          60.23 |        56.14 |           76.15 |             61.23 |         4.93 |
|               9 | PAGP     | PAGP               | US       |                5.62 |                     0.02 |     0.01 |      0.1  |                  43.96 |                        73.74 |         82.24 |         72.83 |          71.72 |        71.01 |           84.2  |             61.23 |         1.78 |
|              10 | SBSW     | SBSW               | US       |                7.81 |                     0.04 |    -0.04 |      0.2  |                  77.05 |                        73.7  |         76.06 |         69.34 |          64.89 |        70.72 |           57.98 |             83.49 |         8.65 |
|              11 | NVDA     | NVIDIA Corporation | US       |             4540.11 |                     0.05 |    -0.04 |     -0.03 |                  81.22 |                        73.58 |         61.49 |         64.54 |          68.55 |        69.41 |           86.9  |             78.35 |         5.8  |
|              12 | SNOW     | SNOW               | US       |               99.97 |                     0.08 |    -0.08 |     -0.02 |                  79.64 |                        73.54 |         62.07 |         78.71 |          67.84 |        46.95 |           42.45 |             91.64 |         8.05 |
|              13 | FLS.CO   | FLS.CO             | EUROPE   |                4.09 |                     0.06 |     0    |      0.14 |                  70.74 |                        73.05 |         78.56 |         58.93 |          55.7  |        57.9  |           85.81 |             39.94 |         5.18 |
|              14 | KRX.IR   | KRX.IR             | EUROPE   |               18.45 |                     0.03 |    -0    |      0.01 |                  53.81 |                        72.74 |         72.46 |         72.53 |          71.8  |        66.33 |           97.49 |             59.36 |         5.48 |
|              15 | BEN      | BEN                | US       |               14.73 |                     0.04 |     0    |     -0.01 |                  60.3  |                        72.28 |         61.18 |         69.54 |          78.13 |        78.63 |           86.21 |             74.81 |         3.28 |
|              16 | SYENS.BR | SYENS.BR           | EUROPE   |                8.2  |                     0.02 |    -0.01 |     -0.02 |                  51.53 |                        72.14 |         65.42 |         77.06 |          70.06 |        57.46 |           64.66 |             86.35 |         5.31 |
|              17 | CF       | CF                 | US       |               17.35 |                     0.04 |    -0.03 |      0.14 |                  74.38 |                        72.13 |         77.31 |         68.92 |          62.73 |        64.8  |           63.33 |             64.35 |         5.15 |
|              18 | BMNR     | BMNR               | US       |               13.01 |                     0.05 |    -0.05 |      0.37 |                  85.68 |                        71.58 |         74.43 |         65.32 |          53.62 |        53.91 |           72.74 |             46.44 |         9.58 |
|              19 | OKTA     | OKTA               | US       |               25.07 |                     0.04 |    -0.02 |      0.07 |                  66.89 |                        71.57 |         78.61 |         77.19 |          69.87 |        57.36 |           68.46 |             56.91 |         7.8  |
|              20 | C5H.IR   | C5H.IR             | EUROPE   |                1.69 |                     0.05 |    -0.05 |      0.05 |                  85.8  |                        71.43 |         68.45 |         65.94 |          67.53 |        73.53 |           97.49 |             32.24 |         2.64 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.61 |             41.52 |         38.39 |         35.37 |          44.66 |        51.34 |           77.39 |             51.73 |                26 |         3.32 |             89.74 | long               |                0.02 |                  1.47 |                 1.52 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    156 | STR.VI   | STR.VI                | EUROPE   |               12.26 |             64.59 |         88.06 |         70.83 |          58.35 |        50.65 |          nan    |             57.26 |             32.1  |         5.58 |             66.84 | short              |                0.05 |                  4.45 |               nan    |
|    110 | HMC      | Honda Motor Co., Ltd. | OTHER    |               36.34 |             67.05 |         67.88 |         70.76 |          65.76 |        66.22 |           73.85 |             84.18 |             61.69 |         3.79 |             83.9  | swing              |               -0.1  |                  3.88 |                 3.84 |
|    371 | SAP.DE   | SAP SE                | EUROPE   |              204.59 |             56.24 |         52.5  |         57.35 |          55.13 |        62.67 |           71.3  |             50.9  |             72    |         6.53 |             88.48 | long               |                2.6  |                  3.67 |                 3.81 |
|    295 | IHS      | IHS Holding Limited   | OTHER    |                2.47 |             58.82 |         66.48 |         56.5  |          57.25 |        60.38 |           54.89 |             77.62 |             63.14 |         2.6  |             72.86 | short              |               -0.32 |                  3.66 |                 3.6  |
|     86 | CLOV     | CLOV                  | US       |                2.21 |             68.3  |         75.97 |         68.17 |          68.44 |        52    |           51.22 |             93.18 |             14.01 |         8.31 |             69.68 | short              |               -0.01 |                  3.4  |                 2.78 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    461 | HQL      | Abrdn Life Sciences Investors | US       |                0.52 |             53.05 |         46.38 |         63.87 |          59.72 |        45.77 |           37.95 |             78.64 |             17.04 |         2.58 |             63.74 | swing              |               -0.13 |                 -4.01 |                -3.31 |
|    406 | GOLD     | Gold.com, Inc.                | US       |                1.21 |             54.73 |         74.73 |         55.47 |          54    |        50.11 |           40.87 |             68.04 |             33.33 |         7.12 |             77.52 | short              |               -0.03 |                 -3.42 |               nan    |
|    722 | TLRY     | Tilray Brands, Inc.           | OTHER    |                0.48 |             20.74 |         18.94 |         17.54 |          22.54 |        27.93 |           35.05 |             32.37 |             26.44 |         8.85 |             78.44 | long               |                0.14 |                 -3.23 |                -2.7  |
|    634 | ACRS     | ACRS                          | US       |                0.67 |             43.27 |         31.26 |         51.55 |          50.05 |        36.49 |           18.68 |             31.46 |             25.5  |         7.19 |             66.84 | swing              |                0.02 |                 -2.79 |                -2.01 |
|    341 | HQH      | Abrdn Healthcare Investors    | US       |                1.07 |             57.25 |         44.71 |         64.55 |          63.1  |        51.4  |           54.47 |             78.64 |             15.67 |         2.49 |             63.74 | swing              |               -0.11 |                 -2.75 |               nan    |

## Duplicate-security checks

- None detected.

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
- Excluded by hard/data filters: **277**
- Event watch (otherwise eligible): **1**
- Final eligible: **722**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- liquidity: 225
- price: 177
- market_cap: 166
- price_history: 14
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 9 | 7 |  | 4 | 2 | main,value,quality_value |
| DDI | 72 | 5 | 31 | 2 | 1 | value,quality_value |
| BION.SW | 107 | 1 | 49 | 1 | 1 | value,quality_value |
| NVDA | 119 | 6 | 11 | 5 | 1 | value,quality_value |
| IRWD | 196 | 4 | 91 | 3 | 1 | value,quality_value |
| AVGO | 459 | 8 | 208 | 7 | 1 | value,quality_value |
| BBWI | 513 | 2 | 221 | 8 | 1 | value,quality_value |
| STNE | 564 | 3 | 239 | 6 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| CRGY | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| SM | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |
| DELL | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (VLO, FRO, CRGY, HPE, SM, DK, DELL, PBF, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (PAGP)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 76.86 | 76.12 | 71.78 | 84.64 | 59.99 | 86.94 | 67.13 |
| 2 | NVDA | value+pullback | 74.86 | 60.87 | 81.22 | 86.90 | 78.35 | 77.10 | 66.54 |
| 3 | IRWD | value+pullback | 74.01 | 68.09 | 72.84 | 89.28 | 58.87 | 80.48 | 63.09 |
| 4 | DDI | value+pullback | 70.50 | 64.22 | 57.15 | 92.69 | 65.05 | 82.69 | 69.57 |
| 5 | ETG | value+pullback | 68.08 | 56.25 | 71.03 | 67.90 | 78.64 | 77.00 | 60.06 |
| 6 | BBWI | value+pullback | 67.73 | 82.54 | 71.52 | 70.25 | 38.87 | 53.30 | 51.07 |
| 7 | STNE | value+pullback | 67.49 | 74.97 | 59.12 | 84.18 | 36.91 | 69.51 | 48.24 |
| 8 | INVA | value+pullback | 67.43 | 58.70 | 69.84 | 86.28 | 36.94 | 78.62 | 46.37 |
| 9 | SAP.DE | value+pullback | 67.31 | 68.99 | 72.61 | 71.30 | 50.90 | 63.39 | 56.24 |
| 10 | MAGN | value+pullback | 66.14 | 72.36 | 70.81 | 68.70 | 37.40 | 63.42 | 44.27 |
| 11 | AVGO | value+pullback | 65.99 | 60.81 | 52.10 | 92.11 | 50.31 | 79.38 | 53.08 |
| 12 | RCI | value+pullback | 65.35 | 63.87 | 71.23 | 82.06 | 46.41 | 57.19 | 51.55 |
| 13 | 0Q2N.IL | value+pullback | 65.23 | 70.11 | 67.02 | 58.88 |  | 68.07 | 66.71 |
| 14 | DEC | value+pullback | 63.54 | 57.56 | 85.93 | 60.90 | 51.08 | 52.76 | 56.24 |
| 15 | XNET | value+pullback | 63.51 | 59.23 | 63.61 | 57.83 | 78.88 | 66.37 | 44.06 |
| 16 | VOLV-B.ST | value+pullback | 62.67 | 70.20 | 62.51 | 59.68 | 51.56 | 59.36 | 55.53 |
| 17 | AVK | value+pullback | 62.43 | 57.50 | 72.63 | 62.32 | 54.57 | 61.09 | 50.61 |
| 18 | WKC | value+pullback | 62.22 | 56.45 | 57.50 | 62.39 | 76.82 | 69.34 | 65.89 |
| 19 | KSS | value+pullback | 61.44 | 73.59 | 67.38 | 50.62 | 64.19 | 42.52 | 52.59 |
| 20 | JD | value+pullback | 61.33 | 67.11 | 62.57 | 57.76 | 47.56 | 60.67 | 42.57 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 3 / 22 |
| Top 50 | 49/50 | 50/50 | 49/50 | 48/50 | 0/50 | 69.7 | 13 / 37 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
