# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-05

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

- **EUROPE:** 87.6/100
- **OTHER:** 78.2/100
- **US:** 86.7/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.84 |             82.6  |         85.67 |         82.77 |          82.11 |        82.42 |           91.24 |             69.39 |             68.31 |         5.37 |             69.68 | short              |               14.57 |                  0.44 |                 0    |
|      2 | DELL     | DELL                       | US       |              291.42 |             82.21 |         89.12 |         84.76 |          79.66 |        68.33 |           72.54 |             79.7  |             36.58 |         7.5  |             68.77 | short              |                6.34 |                  2.92 |                 2.62 |
|      3 | VLO      | VLO                        | US       |               91.85 |             82.02 |         83.54 |         84.23 |          80.49 |        76.81 |           85.01 |             63.58 |             58.06 |         3.24 |             67.5  | swing              |              nan    |                nan    |               nan    |
|      4 | DSX      | DSX                        | US       |                0.32 |             80.46 |         87.12 |         75.36 |          75.26 |        85.56 |           91.05 |             43.6  |             98.74 |         5.92 |             67.86 | short              |                5.24 |                  2.52 |                 1.49 |
|      5 | UGP      | UGP                        | US       |                6.68 |             79.8  |         84.44 |         84.48 |          75.16 |        68.82 |           58.4  |             74.55 |             64.73 |         4.32 |             68.66 | swing              |               17.77 |                  3.01 |                 1.83 |
|      6 | CRGY     | CRGY                       | US       |                4.66 |             79.75 |         82.61 |         77.98 |          77    |        81.51 |           69.77 |             87.61 |             96.36 |         6    |             69.23 | short              |                4.66 |                  1.43 |               nan    |
|      7 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.87 |             79.66 |         85.38 |         79.25 |          79.21 |        80.06 |           95.66 |             51.62 |             63.61 |         3.93 |             69.68 | short              |                1.96 |                  0.02 |               nan    |
|      8 | DINO     | DINO                       | US       |               16.13 |             79.43 |         85.05 |         84.1  |          74.76 |        66.47 |           48.32 |             72.93 |             70.48 |         4.29 |             69.68 | short              |              nan    |                  1.5  |                 1.08 |
|      9 | DK       | DK                         | US       |                3.79 |             79.11 |         83.02 |         83.7  |          75.2  |        62.11 |           54.04 |             85.08 |             38.42 |         7.05 |             69.68 | swing              |                4.1  |                  0.35 |                 0    |
|     10 | KIN.BR   | KIN.BR                     | EUROPE   |                1.3  |             78.95 |         85.02 |         83.29 |          74.6  |        65.61 |           89.44 |             63.99 |             18.87 |         3.89 |             69.68 | short              |                2.95 |                  1.22 |                 0.7  |
|     11 | AVAH     | AVAH                       | US       |                2.55 |             78.56 |         88.76 |         82.51 |          74.61 |        72.16 |           93.12 |             51.83 |             42.48 |         7.43 |             68.66 | short              |                3.85 |                  0.16 |                -0.32 |
|     12 | PARR     | Par Pacific Holdings, Inc. | US       |                3.51 |             78.35 |         81.43 |         78.54 |          78.15 |        75.78 |           80.98 |             63.36 |             65.21 |         6.97 |             85.07 | short              |              nan    |                  0.07 |                -0.07 |
|     13 | MU       | MU                         | US       |              987.97 |             78.21 |         74.76 |         71.45 |          81.65 |        83.44 |           95.97 |             51.8  |             75.53 |         8.19 |             69.68 | long               |               10.86 |                  1.89 |               nan    |
|     14 | MT.AS    | MT.AS                      | EUROPE   |               50.7  |             78.05 |         78.6  |         78.32 |          77.79 |        73.9  |           70.45 |             78.82 |             65.71 |         4.92 |             69.68 | short              |                7.29 |                  1.3  |                 0.94 |
|     15 | WT       | WT                         | US       |                3.25 |             77.7  |         81.52 |         81.29 |          74.11 |        64.46 |           71.28 |             74.44 |             30.21 |         5.47 |             69.68 | short              |                6.51 |                nan    |               nan    |
|     16 | OKTA     | OKTA                       | US       |               25.66 |             77.13 |         85.49 |         81.46 |          72.81 |        59.19 |           67.34 |             71.42 |             16.93 |         7.55 |             68.32 | short              |                4.01 |                 -0.54 |                -1.05 |
|     17 | PR       | PR                         | US       |               16.84 |             76.98 |         81.36 |         76.43 |          75.88 |        77.53 |           76.95 |             73.93 |             74.93 |         4.05 |             68.32 | short              |                3.99 |                  0.6  |                 0.15 |
|     18 | GTLB     | GTLB                       | US       |                7.14 |             76.32 |         89.97 |         86.2  |          66.44 |        50.76 |           56.76 |             89.56 |             10.16 |         8.36 |             69.68 | short              |                3.7  |                  2.76 |                 2.34 |
|     19 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.79 |             76.18 |         86.79 |         78.65 |          73.72 |        68.86 |           79.57 |             77.22 |             36.4  |         5.15 |             84.92 | short              |              nan    |                  0.51 |                 0.21 |
|     20 | ANF      | ANF                        | US       |                5.72 |             75.91 |         86.38 |         79.44 |          71.75 |        72.38 |           86.65 |             40.72 |             57.95 |         8.51 |             67.64 | short              |                5.62 |                  0.45 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              229.46 |                  68.08 |                    74.24 |                 76.35 |              70.73 |                82.94 |                   17.06 |           92.39 |             67.83 |     nan     |         nan |       nan |      nan    |        10.07 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  67.99 |                    74.19 |                 77.05 |              71.45 |                89.57 |                   10.43 |           93.81 |             63.73 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.23 |                  73.25 |                    74.06 |                 75.78 |              74.25 |                86.72 |                   13.28 |           83.85 |             58.99 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | STNE      | StoneCo Ltd.                         | OTHER    |                2.01 |                  77.6  |                    73.61 |                 73.32 |              72.46 |                70.17 |                   29.83 |           87.77 |             39.5  |       0.594 |         nan |       nan |        1.63 |         4.28 |          3.9  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  70.75 |                    72.63 |                 74.91 |              71.81 |                79.79 |                   20.21 |           85.33 |             65.14 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA      | NVIDIA Corporation                   | US       |             4786.53 |                  59.98 |                    69.89 |                 71.83 |              64.76 |                77.05 |                   22.95 |           86.9  |             77.06 |       0.008 |         nan |       nan |       27.47 |        14.9  |         28.9  |        0.58 |                 nan |              nan |                  12 |                  0.63 |
|            6 | AVGO      | Broadcom Inc.                        | US       |             1465.19 |                  61.56 |                    69.82 |                 70.77 |              64.16 |                80.13 |                   19.87 |           91.7  |             54.13 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.48 |        0.4  |                 nan |              nan |                  12 |                  0.63 |
|            7 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.32 |                  72.76 |                    69.56 |                 67.93 |              71.91 |                68.53 |                   31.47 |           58.88 |            nan    |       0.223 |         nan |       nan |        1.54 |       nan    |          3.1  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.51 |                  68.38 |                    69.28 |                 70.93 |              68.07 |                69.45 |                   30.55 |           80.98 |             63.36 |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | BBWI      | Bath & Body Works, Inc.              | US       |                3.39 |                  77.31 |                    69.13 |                 66.03 |              68.86 |                55.61 |                   44.39 |           72.48 |             31.84 |       0.194 |         nan |       nan |        5.99 |         6.96 |          4.98 |        0.78 |                 nan |              nan |                  11 |                  0.58 |
|           10 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              107.52 |                  79.16 |                    68.12 |                 65.76 |              72.79 |                49.59 |                   50.41 |           49.57 |             68.7  |       0.148 |         nan |       nan |        1.78 |         7.42 |          4.61 |        5.32 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY       | NLY                                  | US       |               14.79 |                  68.45 |                    67.88 |                 68.03 |              64.81 |                70.15 |                   29.85 |           89.41 |             29.04 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                8.84 |                  58.5  |                    67.75 |                 71.11 |              62.94 |                77.11 |                   22.89 |           91.24 |             69.39 |     nan     |         nan |       nan |      nan    |        10.29 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | WB        | Weibo Corporation                    | OTHER    |                1.42 |                  78.6  |                    67.64 |                 63.49 |              70.14 |                63.41 |                   36.59 |           61.62 |             21.39 |     nan     |         nan |       nan |        1.84 |         5.23 |          5.55 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           12 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.44 |                  68.77 |                    67.35 |                 68.19 |              65.97 |                71.73 |                   28.27 |           84.67 |             35.42 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|           13 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.84 |                  75.88 |                    67.33 |                 64.04 |              69.89 |                56.42 |                   43.58 |           55.1  |             51    |       0.034 |         nan |       nan |       16.42 |        14    |         19.77 |        1.23 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.87 |                  59.46 |                    67.03 |                 69.88 |              61.74 |                76.46 |                   23.54 |           95.66 |             51.62 |     nan     |         nan |       nan |      nan    |         9.34 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | UNIT      | Uniti Group Inc.                     | US       |                2.12 |                  80.01 |                    66.87 |                 63.9  |              68.95 |                45.21 |                   54.79 |           65.23 |             32.03 |      -0.105 |         nan |       nan |        9.13 |       -14.32 |          2.65 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.85 |                  61.57 |                    66.84 |                 68.51 |              63.49 |                77.15 |                   22.85 |           85.29 |             52.72 |     nan     |         nan |       nan |      nan    |         8.9  |          7.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN       | DVN                                  | US       |               45.49 |                  63.74 |                    66.81 |                 67.97 |              64.87 |                70.05 |                   29.95 |           76.92 |             63.64 |     nan     |         nan |       nan |      nan    |         8.86 |         10.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  67.99 |                    74.19 |                 77.05 |              71.45 |                89.57 |                   10.43 |           93.81 |             63.73 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              229.46 |                  68.08 |                    74.24 |                 76.35 |              70.73 |                82.94 |                   17.06 |           92.39 |             67.83 |     nan     |         nan |       nan |      nan    |        10.07 |         10.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.23 |                  73.25 |                    74.06 |                 75.78 |              74.25 |                86.72 |                   13.28 |           83.85 |             58.99 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  70.75 |                    72.63 |                 74.91 |              71.81 |                79.79 |                   20.21 |           85.33 |             65.14 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                     | OTHER    |                2.01 |                  77.6  |                    73.61 |                 73.32 |              72.46 |                70.17 |                   29.83 |           87.77 |             39.5  |       0.594 |         nan |       nan |        1.63 |         4.28 |          3.9  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA     | NVIDIA Corporation               | US       |             4786.53 |                  59.98 |                    69.89 |                 71.83 |              64.76 |                77.05 |                   22.95 |           86.9  |             77.06 |       0.008 |         nan |       nan |       27.47 |        14.9  |         28.9  |        0.58 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                              | US       |                8.84 |                  58.5  |                    67.75 |                 71.11 |              62.94 |                77.11 |                   22.89 |           91.24 |             69.39 |     nan     |         nan |       nan |      nan    |        10.29 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.51 |                  68.38 |                    69.28 |                 70.93 |              68.07 |                69.45 |                   30.55 |           80.98 |             63.36 |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | AVGO     | Broadcom Inc.                    | US       |             1465.19 |                  61.56 |                    69.82 |                 70.77 |              64.16 |                80.13 |                   19.87 |           91.7  |             54.13 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.48 |        0.4  |                 nan |              nan |                  12 |                  0.63 |
|           16 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               36.48 |                  60.36 |                    66.66 |                 70.15 |              65.49 |                75.61 |                   24.39 |           76.09 |             84.19 |       0.04  |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|          nan | KDP      | KDP                              | US       |               38.16 |                  56.01 |                    66.53 |                 69.99 |              61.84 |                80.32 |                   19.68 |           88.62 |             70.55 |     nan     |         nan |       nan |      nan    |        12.86 |         33.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.87 |                  59.46 |                    67.03 |                 69.88 |              61.74 |                76.46 |                   23.54 |           95.66 |             51.62 |     nan     |         nan |       nan |      nan    |         9.34 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GNK      | GNK                              | US       |                1.04 |                  56.49 |                    66    |                 69.22 |              61.64 |                77.43 |                   22.57 |           86.58 |             70.28 |     nan     |         nan |       nan |      nan    |        15.21 |         30.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                           | EUROPE   |                1.81 |                  53.85 |                    65.1  |                 68.89 |              58.88 |                81.39 |                   18.61 |           97.06 |             54.55 |     nan     |         nan |       nan |      nan    |        11.15 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.85 |                  61.57 |                    66.84 |                 68.51 |              63.49 |                77.15 |                   22.85 |           85.29 |             52.72 |     nan     |         nan |       nan |      nan    |         8.9  |          7.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           17 | RJET     | Republic Airways Holdings Inc.   | US       |                0.72 |                  64.88 |                    66.52 |                 68.32 |              64.59 |                53.64 |                   46.36 |           75    |             82.2  |      -0.056 |         nan |       nan |        4.72 |       nan    |         11.34 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               24.01 |                  55.08 |                    64.9  |                 68.23 |              59.12 |                79.64 |                   20.36 |           95.22 |             51.31 |     nan     |         nan |       nan |      nan    |        11.64 |         11.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.44 |                  68.77 |                    67.35 |                 68.19 |              65.97 |                71.73 |                   28.27 |           84.67 |             35.42 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | NLY      | NLY                              | US       |               14.79 |                  68.45 |                    67.88 |                 68.03 |              64.81 |                70.15 |                   29.85 |           89.41 |             29.04 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                              | US       |               45.49 |                  63.74 |                    66.81 |                 67.97 |              64.87 |                70.05 |                   29.95 |           76.92 |             63.64 |     nan     |         nan |       nan |      nan    |         8.86 |         10.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH     | AVAH     | US       |                2.55 |                     0.02 |     0.02 |      0.43 |                  41.84 |                        77.05 |         88.76 |         82.51 |          74.61 |        72.16 |           93.12 |             51.83 |         7.43 |
|               2 | CRGY     | CRGY     | US       |                4.66 |                     0.04 |     0.02 |      0.2  |                  53.52 |                        76.43 |         82.61 |         77.98 |          77    |        81.51 |           69.77 |             87.61 |         6    |
|               3 | ARGX.BR  | ARGX.BR  | EUROPE   |               55.57 |                     0.02 |    -0    |      0.17 |                  50.06 |                        75.76 |         79.11 |         72.44 |          67.64 |        61.02 |           92.35 |             68.14 |         5.97 |
|               4 | WDAY     | WDAY     | US       |               40.6  |                     0.05 |    -0.04 |      0.09 |                  82.81 |                        75.34 |         69.95 |         73.67 |          65.13 |        63.24 |           73.39 |             76.06 |         8.54 |
|               5 | DK       | DK       | US       |                3.79 |                     0.03 |    -0.01 |      0.23 |                  59.01 |                        74.27 |         83.02 |         83.7  |          75.2  |        62.11 |           54.04 |             85.08 |         7.05 |
|               6 | DFDS.CO  | DFDS.CO  | EUROPE   |                1.13 |                     0.02 |     0.02 |      0.2  |                  43.12 |                        73.74 |         84.95 |         74.5  |          72.26 |        66.52 |           59.12 |             86.48 |         5.96 |
|               7 | TECK     | TECK     | US       |               29.17 |                     0.04 |    -0    |      0.04 |                  59.58 |                        72.45 |         70.42 |         69.97 |          75.07 |        72.66 |           86.69 |             73.14 |         5.61 |
|               8 | CRM      | CRM      | US       |              183.58 |                     0.02 |     0.01 |      0.34 |                  45.28 |                        72.28 |         84.03 |         78.21 |          61.95 |        58.07 |           61.36 |             74.67 |         7.65 |
|               9 | DAR      | DAR      | US       |                8.85 |                     0.05 |     0.01 |      0.1  |                  61.37 |                        72.06 |         73.02 |         63.36 |          72.46 |        78.36 |           91.69 |             53.35 |         4.18 |
|              10 | BAX      | BAX      | US       |               11.49 |                     0.07 |    -0.01 |     -0.06 |                  65    |                        71.69 |         50.75 |         72.73 |          72.99 |        70.77 |           75.9  |             69.29 |         6.03 |
|              11 | VWS.CO   | VWS.CO   | EUROPE   |               27.94 |                     0.02 |     0.01 |      0.2  |                  44.02 |                        71.4  |         81.28 |         69.1  |          65.08 |        60.81 |           86.59 |             45.57 |         5.62 |
|              12 | EQNR     | EQNR     | US       |               85.96 |                     0.05 |     0.02 |      0.09 |                  61.8  |                        71.29 |         71.8  |         71.21 |          73.99 |        72.99 |           72.63 |             77.26 |         5.27 |
|              13 | TALO     | TALO     | US       |                2.42 |                     0.05 |     0.01 |      0.17 |                  65.55 |                        71.22 |         75.31 |         69.23 |          70.07 |        71.18 |           67.94 |             67.63 |         5.51 |
|              14 | NTG.CO   | NTG.CO   | EUROPE   |                0.8  |                     0.04 |    -0.04 |      0.04 |                  76.03 |                        70.8  |         64.21 |         71.53 |          69.69 |        64    |           83.65 |             45.98 |         5.12 |
|              15 | GL9.IR   | GL9.IR   | EUROPE   |                5.38 |                     0.07 |     0    |     -0.06 |                  63.13 |                        70.76 |         47.33 |         61.43 |          74.9  |        70.68 |           96.5  |             75.17 |         2.22 |
|              16 | METSO.HE | METSO.HE | EUROPE   |               14.69 |                     0.03 |    -0.02 |      0.06 |                  65.56 |                        70.66 |         70.48 |         61.83 |          61.38 |        57.93 |           77.89 |             66.7  |         4.7  |
|              17 | CMG      | CMG      | US       |               40.25 |                     0.04 |    -0.03 |      0.13 |                  70.06 |                        70.51 |         68.34 |         61.42 |          55.58 |        57.71 |           89.08 |             53.42 |         6.46 |
|              18 | GEN      | GEN      | US       |               15.79 |                     0.02 |    -0.01 |      0.06 |                  53.7  |                        70.16 |         72.96 |         73.09 |          69.42 |        70.2  |           74.74 |             70.72 |         5.58 |
|              19 | FLS.CO   | FLS.CO   | EUROPE   |                4.09 |                     0.06 |    -0.04 |      0.14 |                  81.04 |                        70.06 |         71.88 |         56.11 |          54    |        57.25 |           86.44 |             31.18 |         4.92 |
|              20 | ITRG     | ITRG     | OTHER    |                0.49 |                     0.05 |    -0.01 |      0.09 |                  70.33 |                        69.99 |         66.43 |         58.09 |          58.45 |        67.2  |           69.82 |             81.73 |         8.22 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | ORCL     | Oracle Corporation      | US       |              393.56 |             42.54 |         62.08 |         40.77 |          41.16 |        43.92 |           47.06 |             59.56 |             40.82 |         7.83 |             89.63 | short              |               -0.53 |                 -0.15 |                -0.17 |
|    nan | SHOE     | Shoe Station Group Inc. | US       |                0.33 |             35.24 |         36.07 |         27.09 |          34.4  |        44.5  |           41.77 |             40.11 |             63.86 |         7.02 |             84.18 | long               |                3.77 |                  0.82 |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    124 | HAFN     | HAFN   | US       |                3.97 |             67.16 |         81.24 |         68.95 |          62.91 |        65.37 |           71.16 |             35.24 |             60.8  |         5.2  |             69.68 | short              |               21.93 |                  4.35 |               nan    |
|      5 | UGP      | UGP    | US       |                6.68 |             79.8  |         84.44 |         84.48 |          75.16 |        68.82 |           58.4  |             74.55 |             64.73 |         4.32 |             68.66 | swing              |               17.77 |                  3.01 |                 1.83 |
|      2 | DELL     | DELL   | US       |              291.42 |             82.21 |         89.12 |         84.76 |          79.66 |        68.33 |           72.54 |             79.7  |             36.58 |         7.5  |             68.77 | short              |                6.34 |                  2.92 |                 2.62 |
|     56 | RNW      | RNW    | US       |                2.16 |             71.36 |         77.3  |         70.77 |          68.6  |        71.95 |          nan    |             86.78 |             77.98 |         5.86 |             66.84 | short              |                8.46 |                  2.8  |                 2.99 |
|     18 | GTLB     | GTLB   | US       |                7.14 |             76.32 |         89.97 |         86.2  |          66.44 |        50.76 |           56.76 |             89.56 |             10.16 |         8.36 |             69.68 | short              |                3.7  |                  2.76 |                 2.34 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    449 | W        | W      | US       |               11.72 |             52.92 |         43.27 |         64.96 |          57.77 |        48.06 |           49.13 |             69.07 |             18.95 |         8.85 |             66.39 | swing              |                1.33 |                 -3.04 |                -2.18 |
|    378 | CRWD     | CRWD   | US       |              187.76 |             55.51 |         55.14 |         61.95 |          55.88 |        38.54 |           36.69 |             43.24 |              1.72 |         7.57 |             69.68 | swing              |                2.59 |                 -3.03 |                -2.4  |
|    377 | DASH     | DASH   | US       |               78.94 |             55.54 |         47.76 |         64.67 |          58.25 |        52.83 |           66.55 |             72.29 |             18.03 |         7.08 |             67.86 | swing              |               -3.6  |                 -3.01 |                -2.47 |
|    646 | ZIP      | ZIP    | US       |                0.3  |             41.72 |         37.25 |         55.9  |          46.18 |        30.34 |           17.92 |             51.24 |             14.47 |         9.39 |             67.75 | swing              |                0.07 |                 -2.93 |                -2.12 |
|    521 | TENB     | TENB   | US       |                3.25 |             49.96 |         39.65 |         59.82 |          56.2  |        43.72 |           27.72 |             63.62 |             37.57 |         8.32 |             64.95 | swing              |                4.01 |                 -2.84 |                -2.15 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.88

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
- Excluded by hard/data filters: **287**
- Event watch (otherwise eligible): **2**
- Final eligible: **711**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 229
- price: 183
- market_cap: 152
- price_history: 14
- data_confidence: 10
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CRGY | 6 |  | 2 |  | 2 | main,pullback |
| DK | 9 |  | 5 |  | 2 | main,pullback |
| PARR | 12 | 8 |  | 6 | 1 | value,quality_value |
| BION.SW | 48 | 2 | 27 | 2 | 1 | value,quality_value |
| DDI | 55 | 1 |  | 1 | 1 | value,quality_value |
| NVDA | 86 | 5 |  | 5 | 1 | value,quality_value |
| IRWD | 87 | 4 |  | 3 | 1 | value,quality_value |
| AVGO | 535 | 6 |  | 7 | 1 | value,quality_value |
| STNE | 537 | 3 |  | 4 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| DELL | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| DSX | 4 |  |  |  | 1 | main |
| UGP | 5 |  |  |  | 1 | main |
| CMBT.BR | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (FRO, DELL, VLO, DSX, UGP, CMBT.BR, DINO, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (ARGX.BR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.59 | 73.25 | 55.17 | 83.85 | 58.99 | 86.72 | 71.94 |
| 2 | XNET | value+pullback | 66.39 | 59.72 | 68.82 | 62.22 | 81.93 | 68.71 | 46.80 |
| 3 | WKC | value+pullback | 64.32 | 56.74 | 65.88 | 62.39 | 75.88 | 69.39 | 66.34 |
| 4 | LYFT | value+pullback | 63.16 | 60.49 | 86.75 | 57.82 | 56.03 | 45.25 | 56.18 |
| 5 | ALL-PH | value+pullback | 59.70 | 61.11 | 57.23 | 70.27 | 42.69 | 61.25 | 44.74 |
| 6 | VOLV-B.ST | value+pullback | 59.25 | 75.88 | 47.35 | 55.10 | 51.00 | 56.42 | 55.79 |
| 7 | BBWI | value+pullback | 59.01 | 77.31 | 42.56 | 72.48 | 31.84 | 55.61 | 50.20 |
| 8 | DDI | value | 58.76 | 67.99 | 42.92 | 93.81 | 63.73 | 89.57 | 71.36 |
| 9 | MSFT | value+pullback | 58.68 | 60.88 | 61.31 | 58.98 | 60.43 | 50.97 | 55.83 |
| 10 | MAGN | value+pullback | 58.47 | 63.97 | 59.96 | 52.17 | 37.62 | 63.52 | 46.01 |
| 11 | AF.PA | value+pullback | 57.96 | 67.87 | 71.44 | 42.70 | 59.09 | 37.14 | 49.81 |
| 12 | ORC | value+pullback | 57.73 | 60.76 | 50.48 | 74.47 | 36.99 | 60.06 | 46.54 |
| 13 | TV | value+pullback | 57.54 | 67.97 | 60.98 | 45.32 | 27.57 | 61.74 | 32.06 |
| 14 | IF.MI | value+pullback | 57.52 | 56.90 | 83.47 | 46.29 | 41.96 | 42.22 | 36.22 |
| 15 | GASS | value+pullback | 57.37 | 60.59 | 68.49 | 39.78 | 49.98 | 55.53 | 49.02 |
| 16 | LKFT.AS | value+pullback | 56.94 | 64.82 | 62.09 | 53.11 | 19.07 | 60.47 | 43.61 |
| 17 | UNIT | value+pullback | 56.53 | 80.01 | 42.01 | 65.23 | 32.03 | 45.21 | 50.01 |
| 18 | IRWD | value | 56.50 | 70.75 | 52.01 | 85.33 | 65.14 | 79.79 | 69.11 |
| 19 | AAPL | value+pullback | 55.80 | 56.29 | 52.08 | 63.89 | 53.06 | 55.01 | 55.26 |
| 20 | NOVO-B.CO | value+pullback | 55.66 | 62.95 | 51.33 | 61.80 | 47.74 | 49.47 | 53.17 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 6 / 19 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 69.7 | 14 / 36 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=3, large_20_100b=1, mega_100b_plus=1
