# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-11

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

- **EUROPE:** 80.7/100
- **OTHER:** 71.3/100
- **US:** 82.9/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               95.39 |             84.95 |         85.22 |         88.87 |          84.68 |        78.38 |           85.21 |             81.59 |             53.81 |         3.45 |             69.68 | swing              |                2.17 |                  0.68 |               nan    |
|      2 | FRO      | FRO                        | US       |                9.26 |             83.83 |         89.14 |         85.22 |          82.43 |        79.91 |           91.8  |             69.2  |             57.36 |         5.57 |             69.68 | short              |              nan    |                  0.31 |                -0.13 |
|      3 | CRGY     | CRGY                       | US       |                4.87 |             81.93 |         86.89 |         82.41 |          78.17 |        81.45 |           69.62 |             85.7  |             93.85 |         6.25 |             69.23 | short              |                2.63 |                  0.53 |                 0.33 |
|      4 | DK       | DK                         | US       |                3.94 |             81.74 |         88.5  |         86.58 |          76.91 |        63.57 |           54.29 |             87.9  |             41.13 |         7.36 |             69.68 | short              |                2.32 |                  0.6  |                 0.42 |
|      5 | PBF      | PBF                        | US       |                7.85 |             81.59 |         83.32 |         87.17 |          79.86 |        74.15 |           51.38 |             79.99 |             88.06 |         7.66 |             69.23 | swing              |                4.63 |                  1.23 |                 1.05 |
|      6 | SM       | SM                         | US       |                7.81 |             80.55 |         84.63 |         78.67 |          77.92 |        82.44 |           80.75 |             66.61 |             95.5  |         7.1  |             68.66 | short              |                8.96 |                  1.97 |                 1.7  |
|      7 | UGP      | UGP                        | US       |                6.92 |             79.81 |         84.3  |         85.45 |          75.32 |        67.98 |           60.99 |             75.51 |             57.1  |         4.6  |             68.66 | swing              |                1.34 |                  0.08 |                -0.77 |
|      8 | ANF      | ANF                        | US       |                5.21 |             79.66 |         90.27 |         82.47 |          76.86 |        75.65 |           89.43 |             64.56 |             55    |         8.67 |             67.64 | short              |                0.36 |                  0.8  |               nan    |
|      9 | KIN.BR   | KIN.BR                     | EUROPE   |                1.3  |             78.52 |         87.76 |         82.57 |          74.46 |        65.31 |           87.7  |             67.06 |             20.14 |         3.86 |             69.68 | short              |                2.15 |                 -0.19 |                -0.56 |
|     10 | VIST     | VIST                       | US       |                7.51 |             78.47 |         89.06 |         75.78 |          77.86 |        79.08 |           76.8  |             83.62 |             77.78 |         5.48 |             67.5  | short              |                3.5  |                nan    |               nan    |
|     11 | PARR     | Par Pacific Holdings, Inc. | US       |                3.6  |             78.24 |         79.78 |         78.8  |          77.67 |        75.11 |           80.98 |             62.85 |             64.66 |         7.08 |             85.07 | short              |               -0.05 |                 -0.11 |                -0.1  |
|     12 | EQNR     | EQNR                       | US       |               91.97 |             77.85 |         82.87 |         79.31 |          76.39 |        72.06 |           74.24 |             78.04 |             53.8  |         5.55 |             68.66 | short              |                0.67 |                  1.2  |                 0.77 |
|     13 | WT       | WT                         | US       |                3.16 |             76.72 |         79.1  |         80.96 |          74.34 |        63.96 |           71.71 |             71.19 |             28.17 |         5.65 |             69.68 | swing              |                4.12 |                 -0.13 |                -0.28 |
|     14 | CIRSA.MC | CIRSA.MC                   | EUROPE   |                3.23 |             76.7  |         84.85 |         83.05 |          70.35 |        68.23 |           78.6  |             68.22 |             53.36 |         5.77 |             67.5  | short              |                3.82 |                  0.25 |               nan    |
|     15 | REP.MC   | REP.MC                     | EUROPE   |               30.9  |             76.61 |         78.95 |         80.17 |          74.27 |        70.38 |           57.31 |             74.89 |             73.81 |         3.57 |             69.68 | swing              |               12.82 |                  2.15 |                 1.91 |
|     16 | APA      | APA                        | US       |               13.41 |             76.49 |         81.27 |         77.06 |          75.91 |        74.14 |           73.92 |             72.19 |             65.35 |         5.8  |             68.66 | short              |                0.26 |                  1.99 |                 1.72 |
|     17 | SHELL.AS | SHELL.AS                   | EUROPE   |              235.9  |             76.43 |         83.69 |         73.93 |          73.26 |        78.92 |           91.47 |             75.96 |             66.59 |         2.37 |             69.68 | short              |               13.63 |                  0.55 |                 0.28 |
|     18 | BAYN.DE  | BAYN.DE                    | EUROPE   |               47.84 |             76.15 |         65.06 |         76.34 |          78.9  |        75.95 |          nan    |             88.31 |             62.61 |         6.42 |             66.84 | medium             |                3.34 |                  0.37 |                 0.32 |
|     19 | DHT      | DHT                        | US       |                2.97 |             75.92 |         85.75 |         76.76 |          73.11 |        75.07 |           89.12 |             44.45 |             58.38 |         4.69 |             69.68 | short              |                3.58 |                  0.1  |                 0.05 |
|     20 | NAT      | NAT                        | US       |                1.31 |             75.69 |         85.31 |         77.75 |          73.63 |        70.27 |           87.17 |             44.12 |             40.69 |         5.02 |             69.68 | short              |                3.72 |                  0.41 |                 0.39 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.09 |                  76.12 |                    75.74 |                 77.25 |              76.3  |                86.73 |                   13.27 |           84.64 |             58.85 |       0.848 |         nan |       nan |      nan    |       -80.27 |          2.15 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  69.78 |                    74.06 |                 76.68 |              71.56 |                82.73 |                   17.27 |           92.93 |             64.24 |       0.153 |         nan |       nan |        0.79 |         5.27 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.56 |                  71.09 |                    72.39 |                 74.62 |              71.61 |                77.03 |                   22.97 |           84.92 |             65.64 |       0.186 |         nan |       nan |        4.09 |         2.65 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | STNE      | StoneCo Ltd.                         | OTHER    |                2.04 |                  75.23 |                    71.6  |                 71.14 |              70.57 |                69.75 |                   30.25 |           84.18 |             38.5  |       0.582 |         nan |       nan |        1.64 |         4.39 |          3.69 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              235.9  |                  61.55 |                    71.54 |                 74.75 |              67.26 |                85.28 |                   14.72 |           91.47 |             75.96 |     nan     |         nan |       nan |      nan    |         9.53 |         10.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | BBWI      | Bath & Body Works, Inc.              | US       |                3.02 |                  78.45 |                    70.15 |                 66.94 |              70.6  |                57.05 |                   42.95 |           69.28 |             38.44 |       0.217 |         nan |       nan |        5.68 |         6.26 |          4.65 |        0.8  |                 nan |              nan |                  11 |                  0.58 |
|          nan | BP        | BP                                   | US       |              102.01 |                  59.31 |                    69.95 |                 73.44 |              66.07 |                82.03 |                   17.97 |           86.2  |             86    |     nan     |         nan |       nan |      nan    |         9.39 |         21.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NVDA      | NVIDIA Corporation                   | US       |             4532.24 |                  59.98 |                    69.85 |                 71.76 |              64.83 |                76.92 |                   23.08 |           86.15 |             77.98 |       0.008 |         nan |       nan |       26.03 |        14.03 |         28.25 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|            7 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               61.59 |                  79.76 |                    69.82 |                 66.27 |              72.9  |                57.4  |                   42.6  |           56.25 |             51.41 |       0.035 |         nan |       nan |       16.08 |        13.62 |         19.24 |        1.23 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                                 | US       |              235.97 |                  66.84 |                    69.68 |                 70.46 |              69    |                74.16 |                   25.84 |           71.87 |             75.29 |     nan     |         nan |       nan |      nan    |         9.19 |         10.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.6  |                  68.12 |                    69.05 |                 70.71 |              67.79 |                69.23 |                   30.77 |           80.98 |             62.85 |       0.02  |         nan |       nan |        4.04 |         6.19 |          4.88 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | AVGO      | Broadcom Inc.                        | US       |             1480.57 |                  60.14 |                    68.87 |                 69.87 |              63.08 |                79.81 |                   20.19 |           90.87 |             54.14 |       0.018 |         nan |       nan |       33.72 |        18.61 |         46.5  |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|           10 | IHS       | IHS Holding Limited                  | OTHER    |                2.46 |                  73.25 |                    67.67 |                 67.47 |              71.35 |                60.16 |                   39.84 |           55.25 |             77.82 |      -0.113 |         nan |       nan |        7.54 |        15.4  |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.38 |                  69.88 |                    67.64 |                 66.35 |              69.54 |                68.21 |                   31.79 |           58.88 |            nan    |       0.219 |         nan |       nan |        1.54 |       nan    |          3.15 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  74.28 |                    67.55 |                 66.59 |              70.19 |                54.47 |                   45.53 |           58.53 |             69.05 |       0.14  |         nan |       nan |        1.8  |         7.81 |          4.85 |        5.23 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY       | NLY                                  | US       |               14.25 |                  67.83 |                    67.5  |                 67.74 |              64.34 |                70.04 |                   29.96 |           89.47 |             28.95 |     nan     |         nan |       nan |      nan    |         7.07 |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.41 |                  68.77 |                    67.4  |                 68.27 |              66.01 |                71.62 |                   28.38 |           84.67 |             36.07 |       0.079 |         nan |       nan |        3.91 |         5.14 |          4.39 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               16.12 |                  63.77 |                    67.21 |                 68.31 |              64.38 |                75.2  |                   24.8  |           83.74 |             49.31 |     nan     |         nan |       nan |      nan    |         8.61 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.97 |                  56.11 |                    67.01 |                 70.65 |              61.31 |                82.67 |                   17.33 |           95.81 |             60.32 |     nan     |         nan |       nan |      nan    |        10.99 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                9.26 |                  56.96 |                    66.91 |                 70.5  |              61.78 |                76.93 |                   23.07 |           91.8  |             69.2  |     nan     |         nan |       nan |      nan    |        10.79 |          7.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.09 |                  76.12 |                    75.74 |                 77.25 |              76.3  |                86.73 |                   13.27 |           84.64 |             58.85 |       0.848 |         nan |       nan |      nan    |       -80.27 |          2.15 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  69.78 |                    74.06 |                 76.68 |              71.56 |                82.73 |                   17.27 |           92.93 |             64.24 |       0.153 |         nan |       nan |        0.79 |         5.27 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              235.9  |                  61.55 |                    71.54 |                 74.75 |              67.26 |                85.28 |                   14.72 |           91.47 |             75.96 |     nan     |         nan |       nan |      nan    |         9.53 |         10.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.56 |                  71.09 |                    72.39 |                 74.62 |              71.61 |                77.03 |                   22.97 |           84.92 |             65.64 |       0.186 |         nan |       nan |        4.09 |         2.65 |          5.16 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                               | US       |              102.01 |                  59.31 |                    69.95 |                 73.44 |              66.07 |                82.03 |                   17.97 |           86.2  |             86    |     nan     |         nan |       nan |      nan    |         9.39 |         21.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NVDA     | NVIDIA Corporation               | US       |             4532.24 |                  59.98 |                    69.85 |                 71.76 |              64.83 |                76.92 |                   23.08 |           86.15 |             77.98 |       0.008 |         nan |       nan |       26.03 |        14.03 |         28.25 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|            4 | STNE     | StoneCo Ltd.                     | OTHER    |                2.04 |                  75.23 |                    71.6  |                 71.14 |              70.57 |                69.75 |                   30.25 |           84.18 |             38.5  |       0.582 |         nan |       nan |        1.64 |         4.39 |          3.69 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.6  |                  68.12 |                    69.05 |                 70.71 |              67.79 |                69.23 |                   30.77 |           80.98 |             62.85 |       0.02  |         nan |       nan |        4.04 |         6.19 |          4.88 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.97 |                  56.11 |                    67.01 |                 70.65 |              61.31 |                82.67 |                   17.33 |           95.81 |             60.32 |     nan     |         nan |       nan |      nan    |        10.99 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                              | US       |                9.26 |                  56.96 |                    66.91 |                 70.5  |              61.78 |                76.93 |                   23.07 |           91.8  |             69.2  |     nan     |         nan |       nan |      nan    |        10.79 |          7.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                             | US       |              235.97 |                  66.84 |                    69.68 |                 70.46 |              69    |                74.16 |                   25.84 |           71.87 |             75.29 |     nan     |         nan |       nan |      nan    |         9.19 |         10.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                              | US       |               14.7  |                  56.31 |                    66.57 |                 69.88 |              62.38 |                80.03 |                   19.97 |           85.57 |             74.29 |     nan     |         nan |       nan |      nan    |        10.59 |         23.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                    | US       |             1480.57 |                  60.14 |                    68.87 |                 69.87 |              63.08 |                79.81 |                   20.19 |           90.87 |             54.14 |       0.018 |         nan |       nan |       33.72 |        18.61 |         46.5  |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAA      | PAA                              | US       |               15.6  |                  54.54 |                    66.17 |                 69.81 |              61.42 |                83    |                   17    |           88.03 |             72.07 |     nan     |         nan |       nan |      nan    |        13.59 |         22.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                               | US       |                7.81 |                  62.8  |                    66.79 |                 68.57 |              64.04 |                67.55 |                   32.45 |           80.75 |             66.61 |     nan     |         nan |       nan |      nan    |         5.08 |          6.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               16.12 |                  63.77 |                    67.21 |                 68.31 |              64.38 |                75.2  |                   24.8  |           83.74 |             49.31 |     nan     |         nan |       nan |      nan    |         8.61 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.41 |                  68.77 |                    67.4  |                 68.27 |              66.01 |                71.62 |                   28.38 |           84.67 |             36.07 |       0.079 |         nan |       nan |        3.91 |         5.14 |          4.39 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|           18 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               35.27 |                  58.45 |                    64.78 |                 68.24 |              63.53 |                72.42 |                   27.58 |           73.85 |             84.1  |       0.042 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               23.99 |                  54.11 |                    64.6  |                 68.13 |              58.72 |                80.1  |                   19.9  |           95.02 |             53.42 |     nan     |         nan |       nan |      nan    |        11.55 |         11.93 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                              | US       |               14.25 |                  67.83 |                    67.5  |                 67.74 |              64.34 |                70.04 |                   29.96 |           89.47 |             28.95 |     nan     |         nan |       nan |      nan    |         7.07 |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                  | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | KIN.BR   | KIN.BR                | EUROPE   |                1.3  |                     0.02 |     0.01 |      0.19 |                  45.93 |                        78.37 |         87.76 |         82.57 |          74.46 |        65.31 |           87.7  |             67.06 |         3.86 |
|               2 | ARGX.BR  | ARGX.BR               | EUROPE   |               53.22 |                     0.06 |    -0.06 |      0.13 |                  84.57 |                        77.08 |         70.6  |         70.07 |          67.23 |        60.59 |           91.6  |             71.79 |         6.18 |
|               3 | SRAIL.SW | SRAIL.SW              | EUROPE   |                3.04 |                     0.09 |    -0.01 |      0.18 |                  53.12 |                        75.61 |         82.99 |         76.25 |          70.89 |        63.16 |           76.46 |             72.33 |         5.49 |
|               4 | SBSW     | SBSW                  | US       |                7.82 |                     0.04 |     0    |      0.17 |                  62.5  |                        74.15 |         80.82 |         70.83 |          65.66 |        71.03 |           57.85 |             85.28 |         8.69 |
|               5 | RAND.AS  | RAND.AS               | EUROPE   |                6.66 |                     0.07 |    -0.02 |     -0.02 |                  70.86 |                        73.88 |         56.01 |         75.19 |          70.78 |        64.35 |           77.64 |             67.51 |         6.93 |
|               6 | DOCU     | DOCU                  | US       |               10.57 |                     0.04 |     0.01 |      0.13 |                  58.58 |                        73.38 |         80.66 |         77.49 |          65.31 |        59.34 |           59.91 |             81.92 |         7.87 |
|               7 | ASRNL.AS | ASRNL.AS              | EUROPE   |               14.64 |                     0.02 |    -0.02 |      0.06 |                  55.84 |                        73.15 |         77.44 |         72.69 |          70.66 |        68.84 |           78.57 |             68.93 |         1.09 |
|               8 | NVDA     | NVIDIA Corporation    | US       |             4532.24 |                     0.05 |    -0.03 |     -0.02 |                  75.92 |                        72.76 |         63.02 |         64.88 |          67.91 |        68.41 |           86.15 |             77.98 |         5.71 |
|               9 | METSO.HE | METSO.HE              | EUROPE   |               14.67 |                     0.06 |     0.01 |      0.08 |                  64.61 |                        72.59 |         77.47 |         64.55 |          59.73 |        55.77 |           75.79 |             60.03 |         4.95 |
|              10 | SBLK     | SBLK                  | US       |                2.95 |                     0.05 |    -0.03 |      0.14 |                  78.76 |                        72.55 |         76.54 |         72.77 |          72.37 |        74.54 |           72.51 |             53.12 |         4.45 |
|              11 | HMC      | Honda Motor Co., Ltd. | OTHER    |               35.27 |                     0.05 |    -0.03 |      0.01 |                  76.62 |                        72.43 |         59.21 |         67.09 |          65.11 |        69.48 |           73.85 |             84.1  |         3.8  |
|              12 | SYENS.BR | SYENS.BR              | EUROPE   |                8.23 |                     0.02 |    -0.01 |      0.01 |                  52.59 |                        72.2  |         70.24 |         77.83 |          69.09 |        56.69 |           62.41 |             86.11 |         5.31 |
|              13 | KRX.IR   | KRX.IR                | EUROPE   |               18.43 |                     0.03 |     0    |     -0    |                  53.26 |                        72.17 |         70.7  |         72.07 |          71.34 |        66.39 |           97.41 |             57.73 |         5.38 |
|              14 | HTFL     | HTFL                  | US       |                3.4  |                     0.1  |    -0.09 |      0.52 |                  70.55 |                        71.89 |         76.31 |         80.99 |          62.81 |        44.51 |           38.58 |             87.3  |         8.88 |
|              15 | BEN      | BEN                   | US       |               14.7  |                     0.04 |     0.02 |      0    |                  55.25 |                        71.46 |         63.28 |         69.82 |          77.16 |        77.53 |           85.57 |             74.29 |         3.26 |
|              16 | ARIS     | ARIS                  | US       |                3.44 |                     0.09 |    -0.01 |      0.09 |                  55.16 |                        71.15 |         73    |         69.81 |          72.84 |        83.34 |           88.31 |             58.07 |         8.01 |
|              17 | CNQ      | CNQ                   | US       |               90.02 |                     0.02 |    -0.02 |      0.07 |                  54.54 |                        70.89 |         74.48 |         68.2  |          67.59 |        68.75 |           73.65 |             71.56 |         4.12 |
|              18 | WDAY     | WDAY                  | US       |               38.34 |                     0.11 |    -0.08 |      0.06 |                  62.48 |                        70.71 |         63.91 |         72.13 |          64.14 |        61.54 |           73.49 |             70.49 |         8.73 |
|              19 | GTLB     | GTLB                  | US       |                6.77 |                     0.05 |    -0.05 |      0.16 |                  81.69 |                        70.64 |         77.42 |         76.14 |          58.06 |        45.25 |           58.04 |             53.77 |         8.53 |
|              20 | CMG      | CMG                   | US       |               39.3  |                     0.06 |    -0.06 |      0.11 |                  84.57 |                        70.53 |         64.36 |         59.84 |          55.34 |        57.33 |           90.27 |             50.76 |         6.75 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              343.98 |             37.33 |         35.66 |         32.32 |             39 |        42.17 |           61.98 |             50.53 |             18.09 |         3.26 |             89.74 | long               |                2.17 |                  0.08 |                 0.33 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     84 | NTSK     | NTSK   | US       |                5.3  |             69.17 |         77.16 |         77.85 |          61.19 |        45.49 |           50.53 |             92.07 |              2.18 |         9.18 |             61.36 | swing              |               10.35 |                  3.35 |                 3.03 |
|     56 | NET      | NET    | US       |               95.24 |             70.89 |         74.77 |         77.74 |          67.02 |        50.42 |           55.44 |             84.82 |              1.76 |         7.31 |             69.68 | swing              |               -0.17 |                  3.32 |               nan    |
|     61 | ASX      | ASX    | US       |               89.21 |             70.43 |         69.5  |         71.37 |          72.29 |        59.7  |           63.34 |             76.61 |             23.27 |         7.47 |             69.23 | medium             |               -1.23 |                  2.89 |                 2.22 |
|    155 | CMPS     | CMPS   | US       |                1.69 |             64.39 |         66.16 |         69.84 |          62.62 |        45.3  |           45.15 |             55.95 |              5    |         7.95 |             65.82 | swing              |               -2.7  |                  2.79 |                 2.77 |
|    114 | CLOV     | CLOV   | US       |                2.15 |             67.11 |         72.46 |         65.95 |          68.27 |        52.24 |           51.26 |             93.65 |             14.9  |         8.3  |             69.68 | short              |               13.48 |                  2.63 |                 2.29 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    625 | ACRS     | ACRS                         | US       |                0.7  |             43.48 |         34.44 |         55.01 |          50.68 |        36.28 |           18.91 |             30.5  |             23.5  |         7.23 |             66.84 | swing              |                1.41 |                 -3.62 |                -3.05 |
|    364 | RSKD     | RSKD                         | US       |                0.68 |             55.53 |         50.31 |         65.09 |          60.41 |        50.65 |           38.23 |             67.4  |             41.67 |         6.22 |             69.68 | swing              |               -4.55 |                 -3.45 |                -2.83 |
|    686 | LKFT.AS  | Lakefront Biotherapeutics NV | EUROPE   |                1.53 |             34.4  |         32.51 |         27.04 |          36.3  |        51.88 |           51.09 |             22.69 |             86    |         3.8  |             77.98 | long               |               -6.62 |                 -3.45 |                -2.47 |
|    669 | REPL     | REPL                         | US       |                1.07 |             37.94 |         30.23 |         55.45 |          45.64 |        27.42 |            3.26 |             33    |             11.5  |         9.91 |             64.8  | swing              |               -9.76 |                 -3.36 |                -2.51 |
|    657 | BRKR     | BRKR                         | US       |                7.01 |             39.22 |         31.29 |         42.86 |          48.12 |        35.58 |           18.49 |             49.71 |             24.13 |         7.91 |             68.2  | medium             |              nan    |                 -3.03 |               nan    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.89

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
- Event watch (otherwise eligible): **1**
- Final eligible: **711**
- Eligible change vs previous stored run: **-8**

Top exclusion categories:
- liquidity: 230
- price: 183
- market_cap: 161
- price_history: 16
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| NVDA | 124 | 6 | 8 | 4 | 2 | value,pullback,quality_value |
| KIN.BR | 9 |  | 1 |  | 2 | main,pullback |
| PARR | 11 | 8 |  | 6 | 1 | value,quality_value |
| DDI | 37 | 2 |  | 2 | 1 | value,quality_value |
| BION.SW | 127 | 1 | 31 | 1 | 1 | value,quality_value |
| IRWD | 148 | 3 | 58 | 3 | 1 | value,quality_value |
| IHS | 257 | 10 |  | 10 | 1 | value,quality_value |
| STNE | 425 | 4 |  | 5 | 1 | value,quality_value |
| AVGO | 491 | 9 |  | 7 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| CRGY | 3 |  |  |  | 1 | main |
| DK | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |
| SM | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (VLO, FRO, CRGY, DK, PBF, SM, UGP, ANF, VIST)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (SBSW, ASRNL.AS, METSO.HE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 77.88 | 76.12 | 76.47 | 84.64 | 58.85 | 86.73 | 66.28 |
| 2 | IRWD | value+pullback | 74.09 | 71.09 | 72.22 | 84.92 | 65.64 | 77.03 | 64.68 |
| 3 | NVDA | value+pullback | 73.08 | 59.98 | 75.92 | 86.15 | 77.98 | 76.92 | 66.40 |
| 4 | HMC | value+pullback | 70.66 | 58.45 | 76.62 | 73.85 | 84.10 | 72.42 | 66.10 |
| 5 | ETG | value+pullback | 70.54 | 58.37 | 77.46 | 66.84 | 82.40 | 77.00 | 58.10 |
| 6 | AMCX | value+pullback | 66.72 | 63.76 | 80.68 | 47.83 | 64.93 | 68.77 | 62.65 |
| 7 | INVA | value+pullback | 66.46 | 58.76 | 71.54 | 79.96 | 36.75 | 76.41 | 46.19 |
| 8 | VOLV-B.ST | value+pullback | 65.42 | 79.76 | 65.73 | 56.25 | 51.41 | 57.40 | 54.77 |
| 9 | WKC | value+pullback | 63.90 | 56.45 | 64.48 | 62.39 | 76.25 | 69.31 | 65.23 |
| 10 | RCI | value+pullback | 63.07 | 61.26 | 63.83 | 83.70 | 46.60 | 57.59 | 53.78 |
| 11 | GSL | value+pullback | 62.66 | 68.77 | 45.61 | 84.67 | 36.07 | 71.62 | 70.55 |
| 12 | UNIT | value+pullback | 61.76 | 80.26 | 63.76 | 63.82 | 32.60 | 44.55 | 48.09 |
| 13 | ORC | value+pullback | 61.67 | 55.83 | 74.85 | 71.22 | 37.80 | 58.70 | 41.45 |
| 14 | MAGN | value+pullback | 61.34 | 64.24 | 71.19 | 52.17 | 37.82 | 63.32 | 38.68 |
| 15 | JD | value+pullback | 61.26 | 65.78 | 63.06 | 57.76 | 48.95 | 61.00 | 41.88 |
| 16 | ALL-PH | value+pullback | 61.22 | 61.89 | 63.67 | 69.39 | 42.82 | 60.24 | 45.80 |
| 17 | DEC | value+pullback | 61.18 | 56.27 | 73.43 | 60.90 | 59.39 | 54.34 | 56.38 |
| 18 | MFA | value+pullback | 60.91 | 56.67 | 69.79 | 75.49 | 30.95 | 60.23 | 38.65 |
| 19 | LKFT.AS | value+pullback | 59.68 | 66.95 | 71.74 | 51.09 | 22.69 | 58.61 | 34.40 |
| 20 | NOVO-B.CO | value+pullback | 59.61 | 58.01 | 76.39 | 57.39 | 48.91 | 48.07 | 45.99 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.2 | 1 / 9 |
| Top 25 | 24/25 | 25/25 | 24/25 | 23/25 | 0/25 | 69.2 | 5 / 20 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 69.2 | 14 / 36 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=6, large_20_100b=1
