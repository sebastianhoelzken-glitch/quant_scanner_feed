# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-13

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
- **OTHER:** 72.4/100
- **US:** 82.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               96.9  |             84.7  |         84.55 |         89.19 |          84.85 |        78.71 |           85.21 |             81.02 |             54.65 |         3.43 |             69.68 | swing              |                0.15 |                  0.12 |               nan    |
|      2 | FRO      | FRO                        | US       |                9.44 |             84.36 |         88.42 |         85.65 |          83.07 |        80.59 |           91.84 |             68.23 |             59.77 |         5.68 |             69.68 | short              |                6.23 |                  0.44 |                -0.09 |
|      3 | CRGY     | CRGY                       | US       |                4.18 |             83.85 |         88.91 |         85.45 |          80.05 |        82.25 |           69.2  |             89.77 |             93.98 |         6.33 |             69.23 | short              |                0.2  |                  0.98 |                 0.72 |
|      4 | HPE      | HPE                        | US       |               71.05 |             83.12 |         85.33 |         85.47 |          80.92 |        71.61 |           72.37 |             77.67 |             49.54 |         6.85 |             68.89 | swing              |                0.39 |                  2.56 |                 2.12 |
|      5 | SM       | SM                         | US       |                7.81 |             82.81 |         86.12 |         82.21 |          79.99 |        83.4  |           79.73 |             71.95 |             95.68 |         7.06 |             68.66 | short              |                0.12 |                  2.38 |                 2.2  |
|      6 | DK       | DK                         | US       |                4.02 |             82.1  |         89.13 |         87.13 |          77.06 |        63.64 |           54.33 |             87.92 |             40.65 |         7.37 |             69.68 | short              |                0.09 |                  0.72 |                 0.38 |
|      7 | PBF      | PBF                        | US       |                8    |             81.01 |         81.93 |         86.86 |          80.09 |        74.48 |           51.8  |             80.68 |             87.81 |         7.65 |             69.23 | swing              |                0.23 |                  1.14 |                 1.14 |
|      8 | DELL     | DELL                       | US       |              310.91 |             80.92 |         89.64 |         84.68 |          77.17 |        65.01 |           72.72 |             69.86 |             27.56 |         7.8  |             68.77 | short              |                0.93 |                 -0.14 |                -0.44 |
|      9 | PARR     | Par Pacific Holdings, Inc. | US       |                3.66 |             79.91 |         79.19 |         82.04 |          80.63 |        77.31 |           80.98 |             73.52 |             64.66 |         7.09 |             84.91 | swing              |                0.9  |                  0.36 |                 0.12 |
|     10 | DINO     | DINO                       | US       |               16.53 |             79.42 |         82.8  |         85.23 |          76.04 |        67.01 |           48.88 |             76.11 |             68.43 |         4.5  |             69.68 | swing              |                0.11 |                  0.15 |               nan    |
|     11 | AVAH     | AVAH                       | US       |                2.65 |             79.29 |         88.89 |         83.02 |          75.57 |        71    |           93.02 |             51.2  |             35.28 |         7.76 |             68.66 | short              |                5.86 |                  1.34 |                 1.3  |
|     12 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             78.41 |         86.26 |         82.05 |          74.77 |        65.17 |           87.59 |             67.19 |             18.1  |         3.77 |             69.68 | short              |                0.26 |                 -0.02 |                -0.03 |
|     13 | EQNR     | EQNR                       | US       |               91.6  |             77.82 |         83.41 |         79.35 |          76.3  |        72.87 |           74.28 |             77.09 |             55.93 |         5.6  |             68.66 | short              |                0.19 |                  1.2  |               nan    |
|     14 | APA      | APA                        | US       |               13.51 |             77.51 |         83.4  |         78.8  |          76.23 |        74.69 |           72.67 |             72.1  |             67.44 |         5.85 |             68.66 | short              |                0.22 |                  0.65 |                 0.59 |
|     15 | HAFN     | HAFN                       | US       |                4.04 |             77.46 |         85.29 |         81.76 |          73.16 |        69.29 |           70.88 |             62.04 |             57.82 |         5.53 |             69.68 | short              |                7.07 |                  2.13 |               nan    |
|     16 | DSX      | DSX                        | US       |                0.32 |             77.33 |         83.92 |         71.6  |          71.61 |        83.05 |           90.44 |             30.39 |             98.49 |         6.3  |             67.86 | short              |               -2.11 |                 -0.58 |                -1.27 |
|     17 | PAA      | PAA                        | US       |               15.87 |             77.18 |         85.76 |         77.97 |          76.39 |        75.81 |           89.12 |             72.59 |             52.24 |         2.07 |             68.89 | short              |                0.41 |                nan    |               nan    |
|     18 | REP.MC   | REP.MC                     | EUROPE   |               30.91 |             77.1  |         79.62 |         80.33 |          74.59 |        71.02 |           58.57 |             75.77 |             72.39 |         3.67 |             69.68 | swing              |                0.79 |                  2.17 |                 1.94 |
|     19 | DHT      | DHT                        | US       |                3.06 |             77.07 |         85.14 |         78.66 |          74.94 |        75.47 |           89.15 |             45.31 |             58.28 |         4.86 |             69.68 | short              |                0.68 |                  0.33 |                 0.43 |
|     20 | CXW      | CXW                        | US       |                2.98 |             77.01 |         84.21 |         81.42 |          72.6  |        61.78 |           53.43 |             73.98 |             47.71 |         4.84 |             68.89 | short              |                0.15 |                  0.98 |                 0.71 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  76.12 |                    75.89 |                 77.45 |              76.46 |                86.98 |                   13.02 |           84.64 |             59.94 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI      | Bath & Body Works, Inc.              | US       |                3.23 |                  82.54 |                    71.98 |                 68.4  |              72.81 |                53.19 |                   46.81 |           70.25 |             38.1  |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|            3 | STNE      | StoneCo Ltd.                         | OTHER    |                2.01 |                  74.97 |                    71.45 |                 71.02 |              70.39 |                69.8  |                   30.2  |           84.18 |             38.47 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  68.09 |                    70.86 |                 73.31 |              69.29 |                79.98 |                   20.02 |           87.49 |             58.64 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA      | NVIDIA Corporation                   | US       |             4543.64 |                  60.87 |                    70.54 |                 72.46 |              65.56 |                77.14 |                   22.86 |           86.9  |             78.48 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            6 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.66 |                  68.12 |                    70.34 |                 72.6  |              69.2  |                71.14 |                   28.86 |           80.98 |             73.52 |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              236.84 |                  59.25 |                    70.25 |                 73.78 |              65.61 |                85.31 |                   14.69 |           91.7  |             75.96 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                                   | US       |              102.34 |                  58.76 |                    69.76 |                 73.37 |              65.7  |                82.25 |                   17.75 |           86.83 |             85.9  |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.27 |                  72.99 |                    69.64 |                 67.98 |              72.01 |                68.1  |                   31.9  |           58.88 |            nan    |       0.226 |         nan |       nan |        1.54 |       nan    |          3.05 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | AVGO      | Broadcom Inc.                        | US       |             1489.54 |                  60.81 |                    69.41 |                 70.46 |              63.66 |                80.01 |                   19.99 |           91.52 |             54.74 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.23 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                                 | US       |              238.52 |                  66.38 |                    69.26 |                 70.06 |              68.53 |                73.77 |                   26.23 |           71.73 |             74.59 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  61.52 |                    68.97 |                 72.38 |              65.09 |                79.26 |                   20.74 |           92.07 |             65.26 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | MOMO      | Hello Group Inc.                     | OTHER    |                0.61 |                  77.82 |                    68.4  |                 65.72 |              72.32 |                68.63 |                   31.37 |           58.02 |             39.36 |       0.844 |         nan |       nan |       -5.96 |         4.79 |          4.9  |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|           11 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.42 |                  71.26 |                    68.19 |                 67.99 |              68.59 |                76.02 |                   23.98 |           76.48 |             36.01 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.47 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SM        | SM                                   | US       |                7.81 |                  63.36 |                    67.71 |                 69.56 |              65.21 |                68.83 |                   31.17 |           79.73 |             71.95 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                                  | US       |               14.23 |                  67.95 |                    67.54 |                 67.74 |              64.45 |                70.01 |                   29.99 |           89.12 |             29.21 |     nan     |         nan |       nan |      nan    |         7.04 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               61.62 |                  75.88 |                    67.41 |                 64.14 |              69.97 |                56.51 |                   43.49 |           55.1  |             51.64 |       0.035 |         nan |       nan |       16.13 |        13.67 |         19.35 |        0.99 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN       | BEN                                  | US       |               14.74 |                  57.5  |                    67.4  |                 70.61 |              63.32 |                80.3  |                   19.7  |           86.01 |             74.61 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | UNIT      | Uniti Group Inc.                     | US       |                2.11 |                  80.26 |                    67.34 |                 64.51 |              69.24 |                45.74 |                   54.26 |           66.83 |             32.14 |      -0.106 |         nan |       nan |        9.11 |       -14.18 |          2.62 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           14 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.78 |                  74.98 |                    67.25 |                 66.48 |              71.08 |                50.72 |                   49.28 |           52.72 |             79.68 |       0.141 |         nan |       nan |        1.8  |         4.75 |          4.83 |        5.44 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.06 |                  76.12 |                    75.89 |                 77.45 |              76.46 |                86.98 |                   13.02 |           84.64 |             59.94 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              236.84 |                  59.25 |                    70.25 |                 73.78 |              65.61 |                85.31 |                   14.69 |           91.7  |             75.96 |     nan     |         nan |       nan |      nan    |         9.58 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                                   | US       |              102.34 |                  58.76 |                    69.76 |                 73.37 |              65.7  |                82.25 |                   17.75 |           86.83 |             85.9  |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.58 |                  68.09 |                    70.86 |                 73.31 |              69.29 |                79.98 |                   20.02 |           87.49 |             58.64 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.66 |                  68.12 |                    70.34 |                 72.6  |              69.2  |                71.14 |                   28.86 |           80.98 |             73.52 |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA     | NVIDIA Corporation                                   | US       |             4543.64 |                  60.87 |                    70.54 |                 72.46 |              65.56 |                77.14 |                   22.86 |           86.9  |             78.48 |       0.008 |         nan |       nan |       26.02 |        14.02 |         27.63 |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            9 | DDI      | DoubleDown Interactive Co., Ltd.                     | OTHER    |                0.54 |                  61.52 |                    68.97 |                 72.38 |              65.09 |                79.26 |                   20.74 |           92.07 |             65.26 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  74.97 |                    71.45 |                 71.02 |              70.39 |                69.8  |                   30.2  |           84.18 |             38.47 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.78 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                                                  | US       |               14.74 |                  57.5  |                    67.4  |                 70.61 |              63.32 |                80.3  |                   19.7  |           86.01 |             74.61 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                  | US       |                9.44 |                  57.63 |                    67.12 |                 70.59 |              62.08 |                76.42 |                   23.58 |           91.84 |             68.23 |     nan     |         nan |       nan |      nan    |        10.82 |          7.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               19.21 |                  55.24 |                    66.67 |                 70.46 |              60.85 |                82.95 |                   17.05 |           95.79 |             61.42 |     nan     |         nan |       nan |      nan    |        11.13 |         15.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                                        | US       |             1489.54 |                  60.81 |                    69.41 |                 70.46 |              63.66 |                80.01 |                   19.99 |           91.52 |             54.74 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.23 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAA      | PAA                                                  | US       |               15.87 |                  54.72 |                    66.6  |                 70.34 |              61.71 |                83.63 |                   16.37 |           89.12 |             72.59 |     nan     |         nan |       nan |      nan    |        13.79 |         22.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              238.52 |                  66.38 |                    69.26 |                 70.06 |              68.53 |                73.77 |                   26.23 |           71.73 |             74.59 |     nan     |         nan |       nan |      nan    |         9.27 |         10.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                                   | US       |                7.81 |                  63.36 |                    67.71 |                 69.56 |              65.21 |                68.83 |                   31.17 |           79.73 |             71.95 |     nan     |         nan |       nan |      nan    |         4.9  |          6.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                                               | EUROPE   |               24.39 |                  54.51 |                    64.89 |                 68.4  |              59    |                80.11 |                   19.89 |           95.46 |             53.27 |     nan     |         nan |       nan |      nan    |        11.74 |         12.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BBWI     | Bath & Body Works, Inc.                              | US       |                3.23 |                  82.54 |                    71.98 |                 68.4  |              72.81 |                53.19 |                   46.81 |           70.25 |             38.1  |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.87 |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | MU       | MU                                                   | US       |              949.45 |                  48.35 |                    62.83 |                 68.15 |              55.79 |                75.23 |                   24.77 |           95.83 |             74.36 |     nan     |         nan |       nan |      nan    |         6.25 |         22.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.42 |                  71.26 |                    68.19 |                 67.99 |              68.59 |                76.02 |                   23.98 |           76.48 |             36.01 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.47 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|           15 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.13 |                  66.67 |                    66.52 |                 67.98 |              65.23 |                72.73 |                   27.27 |           83.5  |             41.3  |     nan     |         nan |       nan |        3.93 |        60    |          4.65 |        2.73 |                 nan |              nan |                  11 |                  0.58 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                  | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | SRAIL.SW | SRAIL.SW              | EUROPE   |                3.12 |                     0.06 |    -0    |      0.21 |                  67.25 |                        79.27 |         85.84 |         78.43 |          71.28 |        63.22 |           77.12 |             72.23 |         5.59 |
|               2 | KIN.BR   | KIN.BR                | EUROPE   |                1.29 |                     0.02 |    -0    |      0.17 |                  52.98 |                        78.67 |         86.26 |         82.05 |          74.77 |        65.17 |           87.59 |             67.19 |         3.77 |
|               3 | WT       | WT                    | US       |                3.13 |                     0.04 |    -0.04 |      0.05 |                  75.25 |                        76.41 |         72.19 |         80.24 |          74.42 |        64.07 |           70.59 |             72.55 |         5.77 |
|               4 | AGRO     | AGRO                  | US       |                1.46 |                     0.06 |     0.01 |      0.3  |                  66.33 |                        75.62 |         81.72 |         61.15 |          65.51 |        72.73 |           65.46 |             78.15 |         7.4  |
|               5 | AMC      | AMC                   | US       |                1.89 |                     0.09 |    -0.03 |     -0.06 |                  59.04 |                        75.21 |         48.6  |         71.3  |          78.82 |        79.26 |           85.71 |             90.43 |         9.67 |
|               6 | RAND.AS  | RAND.AS               | EUROPE   |                6.59 |                     0.07 |    -0.04 |     -0.05 |                  71.48 |                        74.26 |         51.62 |         75.14 |          71.79 |        65.27 |           78.28 |             68.73 |         6.96 |
|               7 | SBSW     | SBSW                  | US       |                7.82 |                     0.04 |    -0.04 |      0.2  |                  77.05 |                        74.11 |         76.28 |         69.8  |          65.31 |        70.9  |           57.83 |             85.66 |         8.65 |
|               8 | METSO.HE | METSO.HE              | EUROPE   |               14.76 |                     0.05 |     0    |      0.08 |                  69.3  |                        73.87 |         77.97 |         64.17 |          60.31 |        56.29 |           76.6  |             61.11 |         4.93 |
|               9 | MU       | MU                    | US       |              949.45 |                     0.05 |     0.02 |      0.03 |                  63.21 |                        73.75 |         67.9  |         67.38 |          84.3  |        85.42 |           95.83 |             74.36 |         8.28 |
|              10 | PAGP     | PAGP                  | US       |                5.62 |                     0.02 |     0.01 |      0.1  |                  43.96 |                        73.63 |         82.17 |         72.73 |          71.59 |        70.82 |           83.99 |             61.03 |         1.79 |
|              11 | NVDA     | NVIDIA Corporation    | US       |             4543.64 |                     0.05 |    -0.04 |     -0.03 |                  81.22 |                        73.61 |         61.44 |         64.54 |          68.59 |        69.44 |           86.9  |             78.48 |         5.79 |
|              12 | SNOW     | SNOW                  | US       |              100.05 |                     0.08 |    -0.08 |     -0.02 |                  79.64 |                        73.59 |         62.05 |         78.76 |          67.89 |        46.97 |           42.41 |             91.85 |         8.05 |
|              13 | FLS.CO   | FLS.CO                | EUROPE   |                4.09 |                     0.06 |     0    |      0.14 |                  70.74 |                        73.05 |         78.52 |         58.82 |          55.7  |        57.98 |           86.19 |             39.59 |         5.19 |
|              14 | KRX.IR   | KRX.IR                | EUROPE   |               18.45 |                     0.03 |    -0    |      0.01 |                  53.81 |                        72.72 |         72.39 |         72.47 |          71.79 |        66.31 |           97.58 |             59.31 |         5.48 |
|              15 | SYENS.BR | SYENS.BR              | EUROPE   |                8.2  |                     0.02 |    -0.01 |     -0.02 |                  51.53 |                        72.32 |         65.38 |         77.08 |          70.25 |        57.76 |           65.52 |             86.3  |         5.32 |
|              16 | BEN      | BEN                   | US       |               14.74 |                     0.04 |     0    |     -0.01 |                  60.3  |                        72.15 |         61.09 |         69.43 |          77.99 |        78.42 |           86.01 |             74.61 |         3.29 |
|              17 | CF       | CF                    | US       |               17.36 |                     0.04 |    -0.03 |      0.14 |                  74.38 |                        71.94 |         77.2  |         68.67 |          62.46 |        64.54 |           63.2  |             63.63 |         5.16 |
|              18 | BMNR     | BMNR                  | US       |               13.02 |                     0.05 |    -0.05 |      0.37 |                  85.68 |                        71.54 |         74.4  |         65.26 |          53.57 |        53.88 |           72.8  |             46.14 |         9.58 |
|              19 | OKTA     | OKTA                  | US       |               25.09 |                     0.04 |    -0.02 |      0.07 |                  66.89 |                        71.47 |         78.54 |         77.09 |          69.77 |        57.27 |           68.39 |             56.59 |         7.8  |
|              20 | HMC      | Honda Motor Co., Ltd. | OTHER    |               36.37 |                     0.03 |    -0.02 |      0.04 |                  57.14 |                        71.36 |         67.84 |         70.79 |          65.87 |        66.47 |           73.85 |             84.17 |         3.75 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.87 |             41.51 |         38.35 |         35.34 |          44.66 |        51.36 |           77.39 |             51.73 |                26 |         3.28 |             89.74 | long               |                1.18 |                     1 |                 1.08 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    158 | STR.VI   | STR.VI | EUROPE   |               12.26 |             64.54 |         88.06 |         70.79 |          58.3  |        50.47 |          nan    |             57.32 |             31.71 |         5.59 |             66.84 | short              |               13.13 |                  4.18 |               nan    |
|    106 | CMPS     | CMPS   | US       |                1.71 |             67.33 |         73.84 |         71.66 |          63.01 |        45.44 |           44.99 |             56.99 |              4.96 |         7.92 |             65.82 | short              |                0.1  |                  3.42 |                 3.13 |
|    253 | ACVA     | ACVA   | US       |                1.57 |             60.45 |         82.54 |         73.33 |          47.56 |        31.68 |           20.69 |             47.43 |             15.82 |         9.38 |             67.64 | short              |               -4.7  |                  3.35 |                 2.75 |
|     24 | HMY      | HMY    | US       |               11.12 |             76.03 |         76.47 |         75.59 |          75.36 |        79.84 |           81.83 |             69.44 |             83.45 |         8.31 |             69.68 | long               |                0.7  |                  3.29 |               nan    |
|     86 | CLOV     | CLOV   | US       |                2.21 |             68.32 |         75.97 |         68.17 |          68.46 |        52    |           51.27 |             93.32 |             13.9  |         8.32 |             69.68 | short              |                0.01 |                  2.94 |                 2.33 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    633 | ACRS     | ACRS   | US       |                0.68 |             43.25 |         31.22 |         51.51 |          50.04 |        36.47 |           18.79 |             31.34 |             25.31 |         7.19 |             66.84 | swing              |                0.91 |                 -3.67 |                -2.84 |
|    683 | REPL     | REPL   | US       |                1.05 |             38.15 |         29.48 |         55.73 |          46.82 |        28.5  |            3.11 |             37.51 |             13.4  |         9.91 |             64.8  | swing              |                0.48 |                 -3.33 |                -2.33 |
|    339 | RSKD     | RSKD   | US       |                0.69 |             57.22 |         53.01 |         67.18 |          61.42 |        50.31 |           37.35 |             67.76 |             39.78 |         6.29 |             69.68 | swing              |                0.4  |                 -3.02 |                -2.7  |
|    667 | BRKR     | BRKR   | US       |                7.02 |             39.61 |         32.37 |         43.38 |          48.29 |        35.84 |           18.55 |             49.03 |             25.24 |         7.93 |             68.2  | medium             |                0.52 |                 -2.9  |                -2.01 |
|    159 | MT.AS    | MT.AS  | EUROPE   |               48.43 |             64.42 |         60.46 |         61.83 |          67.02 |        68.04 |           69.86 |             37.97 |             68.09 |         4.96 |             69.68 | long               |                0.89 |                 -2.56 |                -2.73 |

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
- Eligible change vs previous stored run: **+6**

Top exclusion categories:
- liquidity: 225
- price: 176
- market_cap: 166
- price_history: 14
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 9 | 6 |  | 3 | 2 | main,value,quality_value |
| DDI | 72 | 9 | 32 | 5 | 1 | value,quality_value |
| BION.SW | 107 | 1 | 51 | 1 | 1 | value,quality_value |
| NVDA | 118 | 5 | 11 | 4 | 1 | value,quality_value |
| IRWD | 202 | 4 | 92 | 2 | 1 | value,quality_value |
| AVGO | 441 | 8 | 191 | 7 | 1 | value,quality_value |
| BBWI | 513 | 2 | 223 | 8 | 1 | value,quality_value |
| STNE | 559 | 3 | 231 | 6 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| CRGY | 3 |  |  |  | 1 | main |
| HPE | 4 |  |  |  | 1 | main |
| SM | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |
| PBF | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (VLO, FRO, CRGY, HPE, SM, DK, PBF, DELL, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (PAGP)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 76.87 | 76.12 | 71.78 | 84.64 | 59.94 | 86.98 | 67.31 |
| 2 | NVDA | value+pullback | 74.88 | 60.87 | 81.22 | 86.90 | 78.48 | 77.14 | 66.57 |
| 3 | IRWD | value+pullback | 73.62 | 68.09 | 72.84 | 87.49 | 58.64 | 79.98 | 62.72 |
| 4 | DDI | value+pullback | 68.93 | 61.52 | 57.15 | 92.07 | 65.26 | 79.26 | 69.38 |
| 5 | ETG | value+pullback | 68.21 | 56.25 | 71.03 | 67.90 | 79.51 | 77.23 | 60.22 |
| 6 | STNE | value+pullback | 67.70 | 74.97 | 59.12 | 84.18 | 38.47 | 69.80 | 48.47 |
| 7 | BBWI | value+pullback | 67.63 | 82.54 | 71.52 | 70.25 | 38.10 | 53.19 | 50.88 |
| 8 | INVA | value+pullback | 67.07 | 58.70 | 69.84 | 84.48 | 36.94 | 78.15 | 46.05 |
| 9 | AVGO | value+pullback | 66.47 | 60.81 | 52.10 | 91.52 | 54.74 | 80.01 | 53.70 |
| 10 | MAGN | value+pullback | 66.19 | 72.36 | 70.81 | 68.70 | 37.76 | 63.48 | 44.30 |
| 11 | 0Q2N.IL | value+pullback | 66.11 | 72.99 | 67.02 | 58.88 |  | 68.10 | 67.14 |
| 12 | RCI | value+pullback | 65.22 | 63.58 | 71.23 | 81.74 | 46.97 | 56.89 | 51.53 |
| 13 | HMC | value+pullback | 64.93 | 55.51 | 57.14 | 73.85 | 84.17 | 72.49 | 67.16 |
| 14 | DEC | value+pullback | 64.74 | 57.56 | 85.93 | 60.90 | 59.82 | 54.37 | 57.72 |
| 15 | XNET | value+pullback | 63.64 | 59.23 | 63.61 | 57.83 | 79.75 | 66.60 | 44.16 |
| 16 | VOLV-B.ST | value+pullback | 63.12 | 75.88 | 62.51 | 55.10 | 51.64 | 56.51 | 55.89 |
| 17 | AVK | value+pullback | 62.44 | 57.50 | 72.63 | 62.32 | 54.57 | 61.11 | 50.60 |
| 18 | WKC | value+pullback | 62.21 | 56.45 | 57.50 | 62.39 | 76.71 | 69.36 | 65.87 |
| 19 | JD | value+pullback | 61.52 | 67.63 | 62.57 | 57.76 | 47.75 | 60.73 | 42.58 |
| 20 | KSS | value+pullback | 61.42 | 73.59 | 67.38 | 50.62 | 64.03 | 42.51 | 52.51 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 3 / 22 |
| Top 50 | 49/50 | 50/50 | 49/50 | 48/50 | 0/50 | 69.7 | 12 / 38 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
