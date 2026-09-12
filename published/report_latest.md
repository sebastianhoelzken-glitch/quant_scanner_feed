# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-12

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

- **EUROPE:** 81.7/100
- **OTHER:** 73.2/100
- **US:** 82.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               96.89 |             84.54 |         84.39 |         89.09 |          84.7  |        78.45 |           85.6  |             80.91 |             53.31 |         3.46 |             69.68 | swing              |               -0.41 |                  0.54 |               nan    |
|      2 | CRGY     | CRGY                       | US       |                4.97 |             83.65 |         88.73 |         85.19 |          79.83 |        82.12 |           69.59 |             88.97 |             93.38 |         6.3  |             69.23 | short              |                1.73 |                  0.79 |                 0.55 |
|      3 | HPE      | HPE                        | US       |               71.04 |             82.73 |         84.93 |         84.99 |          80.53 |        71.38 |           73.22 |             75.93 |             48.55 |         6.83 |             68.89 | swing              |                7.07 |                  2.37 |                 1.96 |
|      4 | SM       | SM                         | US       |                7.81 |             82.69 |         85.89 |         81.9  |          79.75 |        83.47 |           80.58 |             70.86 |             95.31 |         7.02 |             68.66 | short              |                2.14 |                  2.32 |                 2.16 |
|      5 | DK       | DK                         | US       |                4.02 |             82    |         89.05 |         87.03 |          76.98 |        63.54 |           54.57 |             88.15 |             40    |         7.36 |             69.68 | short              |                0.26 |                  0.59 |                -0.01 |
|      6 | PBF      | PBF                        | US       |                8    |             80.78 |         81.62 |         86.72 |          79.93 |        74.32 |           51.74 |             80.58 |             87.42 |         7.61 |             69.23 | swing              |               -0.82 |                  1.02 |                 1.04 |
|      7 | DELL     | DELL                       | US       |              310.88 |             80    |         89.17 |         83.7  |          76.29 |        64.52 |           72.97 |             66.07 |             27.39 |         7.79 |             68.77 | short              |                5.08 |                 -0.44 |                -0.69 |
|      8 | ANF      | ANF                        | US       |                5.31 |             79.76 |         89.8  |         82.64 |          76.88 |        75.67 |           90.14 |             63.29 |             54.36 |         8.61 |             67.64 | short              |                0.1  |                  0.69 |               nan    |
|      9 | DSX      | DSX                        | US       |                0.32 |             79.44 |         85.28 |         74.49 |          74.24 |        84.4  |           89.46 |             42.99 |             98.55 |         6.27 |             67.86 | short              |              nan    |                 -0.23 |                -1.14 |
|     10 | DINO     | DINO                       | US       |               16.52 |             79.3  |         82.59 |         85.19 |          76.01 |        66.99 |           49.37 |             76.08 |             67.86 |         4.49 |             69.68 | swing              |              nan    |                  0.01 |               nan    |
|     11 | PARR     | Par Pacific Holdings, Inc. | US       |                3.66 |             79.01 |         78.19 |         80.94 |          79.83 |        76.7  |           80.98 |             73.16 |             64.66 |         7.1  |             84.91 | swing              |                0.77 |                  0.3  |                 0.08 |
|     12 | TRMD     | TRMD                       | US       |                3.1  |             78.65 |         86.26 |         78.15 |          75.49 |        79.16 |           84.51 |             44.5  |             82.68 |         5.3  |             69.68 | short              |              nan    |                nan    |               nan    |
|     13 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             78.15 |         85.71 |         81.43 |          74.87 |        66.28 |           89.06 |             66.13 |             21.83 |         3.75 |             69.68 | short              |               -0.36 |                 -0.17 |                -0.24 |
|     14 | FRO      | FRO                        | US       |                9.44 |             78.13 |         85.24 |         79.31 |          76.96 |        76.68 |           92.2  |             43.27 |             57.97 |         5.63 |             69.68 | short              |               -5.7  |                 -0.9  |                -1.13 |
|     15 | EQNR     | EQNR                       | US       |               91.59 |             77.63 |         83.19 |         79.17 |          76.1  |        72.6  |           74.54 |             77.03 |             54.7  |         5.58 |             68.66 | short              |               -0.22 |                  1.1  |               nan    |
|     16 | APA      | APA                        | US       |               13.51 |             77.29 |         83.03 |         78.6  |          75.99 |        74.43 |           73.2  |             71.73 |             66    |         5.84 |             68.66 | short              |                0.81 |                  0.49 |                 0.45 |
|     17 | CIRSA.MC | CIRSA.MC                   | EUROPE   |                3.25 |             76.88 |         85.11 |         82.99 |          70.78 |        68.86 |           79.59 |             69.17 |             53.09 |         5.62 |             67.5  | short              |                0.18 |                  0.36 |               nan    |
|     18 | CXW      | CXW                        | US       |                2.98 |             76.86 |         83.95 |         81.18 |          72.54 |        61.84 |           54.3  |             73.15 |             47.15 |         4.85 |             68.89 | short              |                6.35 |                  0.9  |                 0.63 |
|     19 | PAA      | PAA                        | US       |               15.87 |             76.77 |         85.34 |         77.56 |          75.99 |        75.36 |           88.72 |             71.85 |             51.65 |         2.08 |             68.89 | short              |                1.88 |                nan    |               nan    |
|     20 | SHELL.AS | SHELL.AS                   | EUROPE   |              236.84 |             76.52 |         82.7  |         73.97 |          73.3  |        79.06 |           91.79 |             76.11 |             65.51 |         2.39 |             69.68 | short              |                0.09 |                  0.58 |                 0.03 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.06 |                  76.12 |                    75.76 |                 77.28 |              76.33 |                86.79 |                   13.21 |           84.64 |             58.97 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  68.37 |                    73.33 |                 76.1  |              70.58 |                82.73 |                   17.27 |           92.93 |             64.62 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE      | StoneCo Ltd.                         | OTHER    |                2.01 |                  74.97 |                    71.37 |                 70.9  |              70.3  |                69.67 |                   30.33 |           84.18 |             37.82 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.84 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  67.07 |                    70.63 |                 73.39 |              68.53 |                80.22 |                   19.78 |           89.89 |             58.02 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.77 |                  78.76 |                    70.37 |                 69.43 |              74.66 |                55.58 |                   44.42 |           54.89 |             79.49 |       0.141 |         nan |       nan |        1.8  |         4.75 |          4.83 |        5.44 |                 nan |              nan |                  12 |                  0.63 |
|            6 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.66 |                  68.12 |                    70.29 |                 72.53 |              69.15 |                71.06 |                   28.94 |           80.98 |             73.16 |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | BBWI      | Bath & Body Works, Inc.              | US       |                3.23 |                  78.45 |                    70.04 |                 66.72 |              70.42 |                56.74 |                   43.26 |           69.28 |             37.25 |       0.204 |         nan |       nan |        5.85 |         6.66 |          4.59 |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|            8 | NVDA      | NVIDIA Corporation                   | US       |             4543.12 |                  59.98 |                    69.86 |                 71.78 |              64.84 |                76.88 |                   23.12 |           86.15 |             78.14 |       0.008 |         nan |       nan |       26.01 |        14.02 |         27.63 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |              102.33 |                  58.49 |                    69.67 |                 73.34 |              65.54 |                82.36 |                   17.64 |           87.05 |             86.02 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              236.84 |                  58.08 |                    69.63 |                 73.32 |              64.81 |                85.46 |                   14.54 |           91.79 |             76.11 |     nan     |         nan |       nan |      nan    |         9.56 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.27 |                  72.76 |                    69.47 |                 67.84 |              71.81 |                68.04 |                   31.96 |           58.88 |            nan    |       0.226 |         nan |       nan |        1.54 |       nan    |          3.05 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHEL      | SHEL                                 | US       |              238.49 |                  66.15 |                    69.3  |                 70.2  |              68.39 |                74.17 |                   25.83 |           72.76 |             74.11 |     nan     |         nan |       nan |      nan    |         9.27 |         10.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1489.37 |                  60.81 |                    69.17 |                 70.1  |              63.5  |                79.68 |                   20.32 |           90.87 |             53.77 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.05 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                                   | US       |                7.81 |                  63.41 |                    67.78 |                 69.65 |              65.16 |                68.98 |                   31.02 |           80.58 |             70.86 |     nan     |         nan |       nan |      nan    |         4.97 |          6.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | MOMO      | Hello Group Inc.                     | OTHER    |                0.61 |                  76.52 |                    67.64 |                 65.03 |              71.42 |                69.21 |                   30.79 |           57.61 |             38.74 |       0.845 |         nan |       nan |       -5.96 |         4.79 |          4.9  |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               19.21 |                  57    |                    67.55 |                 71.08 |              61.96 |                82.69 |                   17.31 |           95.9  |             60.34 |     nan     |         nan |       nan |      nan    |        11.13 |         15.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               61.62 |                  75.88 |                    67.42 |                 64.16 |              69.98 |                56.53 |                   43.47 |           55.1  |             51.73 |       0.035 |         nan |       nan |       16.13 |        13.67 |         19.35 |        1.2  |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY       | NLY                                  | US       |               14.23 |                  67.91 |                    67.34 |                 67.49 |              64.29 |                69.68 |                   30.32 |           88.81 |             28.53 |     nan     |         nan |       nan |      nan    |         7.04 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                                  | US       |               14.74 |                  57.44 |                    67.28 |                 70.47 |              63.18 |                80.16 |                   19.84 |           86.05 |             73.92 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.42 |                  68.77 |                    67.27 |                 68.1  |              65.88 |                71.4  |                   28.6  |           84.67 |             35.17 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.44 |        0.87 |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  76.12 |                    75.76 |                 77.28 |              76.33 |                86.79 |                   13.21 |           84.64 |             58.97 |       0.853 |         nan |       nan |      nan    |       -79.82 |          2.14 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  68.37 |                    73.33 |                 76.1  |              70.58 |                82.73 |                   17.27 |           92.93 |             64.62 |       0.155 |         nan |       nan |        0.74 |         5.2  |          5.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.58 |                  67.07 |                    70.63 |                 73.39 |              68.53 |                80.22 |                   19.78 |           89.89 |             58.02 |       0.181 |         nan |       nan |        4.17 |         2.72 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                   | US       |              102.33 |                  58.49 |                    69.67 |                 73.34 |              65.54 |                82.36 |                   17.64 |           87.05 |             86.02 |     nan     |         nan |       nan |      nan    |         9.39 |         22.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              236.84 |                  58.08 |                    69.63 |                 73.32 |              64.81 |                85.46 |                   14.54 |           91.79 |             76.11 |     nan     |         nan |       nan |      nan    |         9.56 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.66 |                  68.12 |                    70.29 |                 72.53 |              69.15 |                71.06 |                   28.94 |           80.98 |             73.16 |       0.019 |         nan |       nan |        4.08 |         6.27 |          4.97 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | NVDA     | NVIDIA Corporation                   | US       |             4543.12 |                  59.98 |                    69.86 |                 71.78 |              64.84 |                76.88 |                   23.12 |           86.15 |             78.14 |       0.008 |         nan |       nan |       26.01 |        14.02 |         27.63 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.21 |                  57    |                    67.55 |                 71.08 |              61.96 |                82.69 |                   17.31 |           95.9  |             60.34 |     nan     |         nan |       nan |      nan    |        11.13 |         15.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | STNE     | StoneCo Ltd.                         | OTHER    |                2.01 |                  74.97 |                    71.37 |                 70.9  |              70.3  |                69.67 |                   30.33 |           84.18 |             37.82 |       0.595 |         nan |       nan |        1.63 |         4.28 |          3.84 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN      | BEN                                  | US       |               14.74 |                  57.44 |                    67.28 |                 70.47 |              63.18 |                80.16 |                   19.84 |           86.05 |             73.92 |     nan     |         nan |       nan |      nan    |        10.59 |         22.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              238.49 |                  66.15 |                    69.3  |                 70.2  |              68.39 |                74.17 |                   25.83 |           72.76 |             74.11 |     nan     |         nan |       nan |      nan    |         9.27 |         10.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1489.37 |                  60.81 |                    69.17 |                 70.1  |              63.5  |                79.68 |                   20.32 |           90.87 |             53.77 |       0.018 |         nan |       nan |       33.74 |        18.67 |         46.05 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAA      | PAA                                  | US       |               15.87 |                  54.66 |                    66.35 |                 70.03 |              61.51 |                83.17 |                   16.83 |           88.72 |             71.85 |     nan     |         nan |       nan |      nan    |        13.79 |         22.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.81 |                  63.41 |                    67.78 |                 69.65 |              65.16 |                68.98 |                   31.02 |           80.58 |             70.86 |     nan     |         nan |       nan |      nan    |         4.97 |          6.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.77 |                  78.76 |                    70.37 |                 69.43 |              74.66 |                55.58 |                   44.42 |           54.89 |             79.49 |       0.141 |         nan |       nan |        1.8  |         4.75 |          4.83 |        5.44 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EOG      | EOG                                  | US       |               66.62 |                  56.94 |                    65.4  |                 68.16 |              61.73 |                76.54 |                   23.46 |           82.49 |             69.56 |     nan     |         nan |       nan |      nan    |        10.12 |         11.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.42 |                  68.77 |                    67.27 |                 68.1  |              65.88 |                71.4  |                   28.6  |           84.67 |             35.17 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.44 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.39 |                  54.02 |                    64.47 |                 68.01 |              58.5  |                79.81 |                   20.19 |           95.46 |             52.43 |     nan     |         nan |       nan |      nan    |        11.74 |         12.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |              949.34 |                  48.07 |                    62.56 |                 67.89 |              55.47 |                74.99 |                   25.01 |           95.9  |             73.59 |     nan     |         nan |       nan |      nan    |         6.25 |         22.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.27 |                  72.76 |                    69.47 |                 67.84 |              71.81 |                68.04 |                   31.96 |           58.88 |            nan    |       0.226 |         nan |       nan |        1.54 |       nan    |          3.05 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                  | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ANF      | ANF                   | US       |                5.31 |                     0.05 |     0.01 |      0.33 |                  61.23 |                        81.61 |         89.8  |         82.64 |          76.88 |        75.67 |           90.14 |             63.29 |         8.61 |
|               2 | SRAIL.SW | SRAIL.SW              | EUROPE   |                3.12 |                     0.06 |    -0    |      0.21 |                  67.45 |                        78.77 |         85.25 |         77.65 |          70.86 |        63.53 |           76.52 |             71.49 |         5.57 |
|               3 | KIN.BR   | KIN.BR                | EUROPE   |                1.29 |                     0.02 |    -0    |      0.17 |                  52.98 |                        78.53 |         85.71 |         81.43 |          74.87 |        66.28 |           89.06 |             66.13 |         3.75 |
|               4 | WT       | WT                    | US       |                3.12 |                     0.04 |    -0.04 |      0.05 |                  75.25 |                        76.26 |         71.62 |         79.82 |          74.17 |        63.79 |           71.05 |             72.36 |         5.75 |
|               5 | AGRO     | AGRO                  | US       |                1.46 |                     0.06 |     0.01 |      0.3  |                  66.33 |                        75.65 |         81.69 |         61.05 |          65.47 |        72.73 |           65.27 |             78.67 |         7.39 |
|               6 | AMC      | AMC                   | US       |                1.89 |                     0.09 |    -0.03 |     -0.06 |                  59.04 |                        75.55 |         48.23 |         71.24 |          79.16 |        80.05 |           87.06 |             91.05 |         9.69 |
|               7 | NOEJ.DE  | NOEJ.DE               | EUROPE   |                0.56 |                     0.05 |    -0.01 |     -0.05 |                  68.76 |                        74.22 |         62.96 |         69.23 |          72.14 |        68.84 |           97.12 |             65.74 |         4.44 |
|               8 | SBSW     | SBSW                  | US       |                7.82 |                     0.04 |    -0.04 |      0.2  |                  77.05 |                        74.02 |         76    |         69.7  |          65.31 |        70.91 |           58.35 |             85.3  |         8.64 |
|               9 | SNOW     | SNOW                  | US       |              100.04 |                     0.08 |    -0.08 |     -0.02 |                  79.64 |                        73.63 |         61.43 |         78.54 |          67.88 |        46.83 |           42.83 |             92.33 |         8.05 |
|              10 | METSO.HE | METSO.HE              | EUROPE   |               14.76 |                     0.05 |     0    |      0.08 |                  69.3  |                        73.58 |         77.17 |         63.41 |          60.12 |        56.55 |           77.62 |             60.5  |         4.92 |
|              11 | MU       | MU                    | US       |              949.34 |                     0.05 |     0.02 |      0.03 |                  63.21 |                        73.4  |         67.4  |         67.03 |          84.08 |        85.33 |           95.9  |             73.59 |         8.29 |
|              12 | RAND.AS  | RAND.AS               | EUROPE   |                6.59 |                     0.08 |    -0.04 |     -0.05 |                  69.99 |                        73.3  |         48.85 |         73.82 |          71.45 |        65.73 |           78.65 |             67.74 |         6.94 |
|              13 | NVDA     | NVIDIA Corporation    | US       |             4543.12 |                     0.05 |    -0.04 |     -0.03 |                  81.22 |                        72.94 |         60.37 |         63.61 |          67.85 |        68.46 |           86.15 |             78.14 |         5.78 |
|              14 | FLS.CO   | FLS.CO                | EUROPE   |                4.09 |                     0.06 |     0    |      0.14 |                  70.74 |                        72.6  |         77.74 |         57.93 |          55.4  |        58.36 |           86.76 |             38.45 |         5.19 |
|              15 | CF       | CF                    | US       |               17.36 |                     0.04 |    -0.03 |      0.14 |                  74.38 |                        72.09 |         76.92 |         68.71 |          62.67 |        64.67 |           64.42 |             63.9  |         5.17 |
|              16 | KRX.IR   | KRX.IR                | EUROPE   |               18.45 |                     0.03 |    -0    |      0.01 |                  53.81 |                        72    |         71.37 |         71.51 |          71.24 |        66.45 |           97.49 |             57.84 |         5.43 |
|              17 | EOG      | EOG                   | US       |               66.62 |                     0.04 |     0.01 |      0.04 |                  57    |                        71.81 |         72.66 |         65.71 |          68.28 |        73.87 |           82.49 |             69.56 |         3.48 |
|              18 | SYENS.BR | SYENS.BR              | EUROPE   |                8.2  |                     0.02 |    -0.01 |     -0.02 |                  51.53 |                        71.8  |         64.2  |         76.46 |          69.96 |        57.92 |           64.76 |             85.91 |         5.32 |
|              19 | BEN      | BEN                   | US       |               14.74 |                     0.04 |     0    |     -0.01 |                  60.3  |                        71.72 |         60.23 |         68.76 |          77.59 |        78.11 |           86.05 |             73.92 |         3.26 |
|              20 | HMC      | Honda Motor Co., Ltd. | OTHER    |               36.37 |                     0.03 |    -0.02 |      0.04 |                  57.14 |                        71.4  |         67.38 |         70.95 |          66.78 |        68.99 |           73.85 |             83.93 |         3.73 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.83 |             40.32 |         36.94 |         34.04 |           43.7 |        50.61 |           77.39 |             50.55 |                26 |         3.25 |             89.74 | long               |                2.99 |                  0.76 |                 0.85 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    136 | ACVA     | ACVA   | US       |                1.52 |             65.15 |         85.06 |         78.2  |          52.1  |        34.33 |           19.7  |             68.1  |             16.58 |         9.39 |             67.64 | short              |               14.91 |                  4.25 |                 3.43 |
|     98 | CMPS     | CMPS   | US       |                1.71 |             67.23 |         73.54 |         71.49 |          62.98 |        45.43 |           45.45 |             57.11 |              4.26 |         7.9  |             65.82 | short              |                2.84 |                  3.34 |                 3.05 |
|     26 | HMY      | HMY    | US       |               11.12 |             75.32 |         75.81 |         74.77 |          74.84 |        79.67 |           82.6  |             67.18 |             83.11 |         8.28 |             69.68 | long               |               10.69 |                  3.16 |               nan    |
|     80 | CLOV     | CLOV   | US       |                2.21 |             68.31 |         75.85 |         68.22 |          68.4  |        51.86 |           50.71 |             94.25 |             13.71 |         8.34 |             69.68 | short              |                1.2  |                  2.86 |                 2.25 |
|      3 | HPE      | HPE    | US       |               71.04 |             82.73 |         84.93 |         84.99 |          80.53 |        71.38 |           73.22 |             75.93 |             48.55 |         6.83 |             68.89 | swing              |                7.07 |                  2.37 |                 1.96 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    640 | ACRS      | ACRS      | US       |                0.67 |             42.34 |         30.65 |         50.85 |          49.2  |        35.48 |           17.77 |             30.04 |             23.81 |         7.19 |             66.84 | swing              |               -1.14 |                 -3.9  |                -3.03 |
|    680 | REPL      | REPL      | US       |                1.05 |             37.67 |         29.09 |         55.14 |          46.25 |        27.91 |            2.92 |             36.32 |             12.28 |         9.91 |             64.8  | swing              |               -0.27 |                 -3.46 |                -2.82 |
|    547 | SMWB      | SMWB      | US       |                0.61 |             48.87 |         41.04 |         71.2  |          56.7  |        37.77 |           30.54 |             69.11 |             12.08 |         9.59 |             68.66 | swing              |               -1.92 |                 -3.26 |               nan    |
|    339 | RSKD      | RSKD      | US       |                0.69 |             56.82 |         52.57 |         66.85 |          61.06 |        49.93 |           36.96 |             67.65 |             39.05 |         6.27 |             69.68 | swing              |                1.29 |                 -3.23 |                -2.88 |
|    573 | PNDORA.CO | PNDORA.CO | EUROPE   |                7.98 |             47.65 |         44.51 |         60.13 |          50.79 |        40.56 |           49.29 |             31.95 |             17.4  |         6.52 |             69.68 | swing              |               -1.85 |                 -3.2  |                -2.84 |

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
- Excluded by hard/data filters: **283**
- Event watch (otherwise eligible): **1**
- Final eligible: **716**
- Eligible change vs previous stored run: **+5**

Top exclusion categories:
- liquidity: 230
- price: 182
- market_cap: 162
- price_history: 14
- data_confidence: 10
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| ANF | 8 |  | 1 |  | 2 | main,pullback |
| PARR | 11 | 6 |  | 4 | 1 | value,quality_value |
| PBR-A | 42 | 5 |  | 8 | 1 | value,quality_value |
| DDI | 67 | 2 | 30 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 106 | 9 |  | 10 | 1 | value,quality_value |
| BION.SW | 111 | 1 | 47 | 1 | 1 | value,quality_value |
| NVDA | 127 | 8 | 13 | 5 | 1 | value,quality_value |
| IRWD | 155 | 4 | 60 | 3 | 1 | value,quality_value |
| AVGO | 449 | 10 | 198 | 7 | 1 | value,quality_value |
| STNE | 567 | 3 | 233 | 6 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| CRGY | 2 |  |  |  | 1 | main |
| HPE | 3 |  |  |  | 1 | main |
| SM | 4 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (VLO, CRGY, HPE, SM, DK, PBF, DELL, DSX, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (KIN.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 76.59 | 76.12 | 71.22 | 84.64 | 58.97 | 86.79 | 66.69 |
| 2 | NVDA | value+pullback | 74.41 | 59.98 | 81.22 | 86.15 | 78.14 | 76.88 | 65.73 |
| 3 | IRWD | value+pullback | 73.66 | 67.07 | 72.84 | 89.89 | 58.02 | 80.22 | 64.56 |
| 4 | DDI | value+pullback | 71.75 | 68.37 | 57.15 | 92.93 | 64.62 | 82.73 | 69.59 |
| 5 | ETG | value+pullback | 68.84 | 57.93 | 71.03 | 67.52 | 81.60 | 77.11 | 58.61 |
| 6 | STNE | value+pullback | 67.61 | 74.97 | 59.12 | 84.18 | 37.82 | 69.67 | 48.03 |
| 7 | AMCX | value+pullback | 67.50 | 63.76 | 83.68 | 47.83 | 65.18 | 68.81 | 63.14 |
| 8 | BBWI | value+pullback | 66.88 | 78.45 | 71.52 | 69.28 | 37.25 | 56.74 | 51.05 |
| 9 | INVA | value+pullback | 66.69 | 56.36 | 69.84 | 86.71 | 36.18 | 78.49 | 47.30 |
| 10 | AVGO | value+pullback | 66.21 | 60.81 | 52.10 | 90.87 | 53.77 | 79.68 | 53.02 |
| 11 | MAGN | value+pullback | 66.10 | 72.36 | 70.81 | 68.70 | 37.11 | 63.37 | 43.18 |
| 12 | 0Q2N.IL | value+pullback | 66.02 | 72.76 | 67.02 | 58.88 |  | 68.04 | 66.79 |
| 13 | ORC | value+pullback | 65.42 | 63.46 | 77.60 | 75.13 | 36.79 | 60.15 | 41.85 |
| 14 | HMC | value+pullback | 65.23 | 56.60 | 57.14 | 73.85 | 83.93 | 72.47 | 68.18 |
| 15 | RCI | value+pullback | 64.91 | 61.50 | 71.23 | 83.70 | 46.04 | 57.45 | 51.45 |
| 16 | DEC | value+pullback | 64.39 | 56.66 | 85.93 | 60.90 | 59.19 | 54.25 | 56.59 |
| 17 | XNET | value+pullback | 63.85 | 58.92 | 63.61 | 57.83 | 81.87 | 67.04 | 43.98 |
| 18 | VOLV-B.ST | value+pullback | 63.14 | 75.88 | 62.51 | 55.10 | 51.73 | 56.53 | 55.10 |
| 19 | WKC | value+pullback | 62.18 | 56.45 | 57.50 | 62.39 | 76.50 | 69.30 | 65.02 |
| 20 | MFA | value+pullback | 61.92 | 56.91 | 74.53 | 75.19 | 30.13 | 59.62 | 38.11 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.1 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 3 / 22 |
| Top 50 | 49/50 | 50/50 | 49/50 | 48/50 | 0/50 | 69.7 | 13 / 37 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=4, large_20_100b=2, mega_100b_plus=1
