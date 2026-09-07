# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-07

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

- **EUROPE:** 87.5/100
- **OTHER:** 75.3/100
- **US:** 86.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.83 |             82.63 |         85.55 |         82.93 |          82.19 |        82.33 |           91.04 |             70.23 |             67.83 |         5.39 |             69.68 | short              |                0.34 |                  0.29 |               nan    |
|      2 | DELL     | DELL                       | US       |              291.25 |             82.21 |         88.93 |         84.79 |          79.62 |        68.2  |           72.2  |             79.9  |             36.48 |         7.5  |             68.77 | short              |                0.19 |                nan    |               nan    |
|      3 | VLO      | VLO                        | US       |               91.79 |             81.82 |         83.27 |         84.13 |          80.37 |        76.61 |           84.83 |             63.57 |             57.62 |         3.23 |             67.5  | swing              |                0.27 |                nan    |               nan    |
|      4 | DSX      | DSX                        | US       |                0.32 |             80.58 |         87.01 |         75.5  |          75.42 |        85.66 |           91.08 |             44.2  |             98.75 |         5.94 |             67.86 | short              |                0.21 |                nan    |               nan    |
|      5 | UGP      | UGP                        | US       |                6.67 |             79.81 |         84.34 |         84.61 |          75.27 |        68.78 |           58.32 |             75.28 |             64.3  |         4.31 |             68.66 | swing              |                0.4  |                  2.86 |                 1.95 |
|      6 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.87 |             79.76 |         85.39 |         79.52 |          79.39 |        79.99 |           95.83 |             52.67 |             62.6  |         3.92 |             69.68 | short              |               -0.21 |                 -0.46 |                -1.87 |
|      7 | CRGY     | CRGY                       | US       |                4.66 |             79.68 |         82.45 |         77.98 |          76.94 |        81.39 |           69.4  |             87.97 |             96.24 |         6.01 |             69.23 | short              |                0.38 |                  0.62 |               nan    |
|      8 | DINO     | DINO                       | US       |               16.12 |             79.27 |         84.74 |         83.95 |          74.58 |        66.24 |           48.11 |             72.76 |             70.02 |         4.32 |             69.68 | short              |                0.38 |                  0.2  |                -0.26 |
|      9 | DK       | DK                         | US       |                3.78 |             79.03 |         82.9  |         83.7  |          75.16 |        61.97 |           54    |             85.28 |             37.85 |         7.06 |             69.68 | swing              |                0.3  |                  1.14 |               nan    |
|     10 | KIN.BR   | KIN.BR                     | EUROPE   |                1.3  |             79.03 |         84.9  |         83.32 |          74.73 |        65.87 |           89.43 |             64.21 |             19.73 |         3.88 |             69.68 | short              |               -0.43 |                 -0.07 |                -0.65 |
|     11 | MU       | MU                         | US       |              987.36 |             78.18 |         74.66 |         71.42 |          81.69 |        83.45 |           95.99 |             52.26 |             75.31 |         8.19 |             69.68 | long               |                0.39 |                  2.05 |                 2.15 |
|     12 | MT.AS    | MT.AS                      | EUROPE   |               50.7  |             77.89 |         77.88 |         78.04 |          77.89 |        74.04 |           71.97 |             79.08 |             64.05 |         4.89 |             69.68 | swing              |               -0.5  |                  1.85 |                 1.4  |
|     13 | WT       | WT                         | US       |                3.24 |             77.64 |         81.27 |         81.24 |          74.03 |        64.32 |           71.1  |             74.44 |             29.9  |         5.48 |             69.68 | short              |                0.24 |                nan    |               nan    |
|     14 | PARR     | Par Pacific Holdings, Inc. | US       |                3.5  |             77.51 |         80.89 |         78.04 |          76.99 |        74    |           76.69 |             62.9  |             65.19 |         6.98 |             85.07 | short              |               -1.27 |                  0.35 |                 0.51 |
|     15 | PR       | PR                         | US       |               16.83 |             76.69 |         81.1  |         76.25 |          75.63 |        77.13 |           76.28 |             73.85 |             74.44 |         4.04 |             68.32 | short              |                0.33 |                 -0.08 |                -0.4  |
|     16 | ANF      | ANF                        | US       |                5.72 |             76.31 |         86.44 |         79.79 |          72.27 |        72.83 |           87.56 |             42.15 |             57.46 |         8.51 |             67.64 | short              |                0.66 |                 -0.47 |               nan    |
|     17 | OKTA     | OKTA                       | US       |               25.65 |             76.22 |         84.93 |         80.75 |          71.69 |        57.84 |           64.46 |             69.88 |             17    |         7.57 |             68.66 | short              |               -1.98 |                 -0.15 |                -0.69 |
|     18 | GTLB     | GTLB                       | US       |                7.14 |             76.17 |         89.78 |         86.01 |          66.32 |        50.71 |           56.74 |             89.16 |             10.1  |         8.4  |             69.68 | short              |                0.29 |                  2.8  |                 2.2  |
|     19 | DHT      | DHT                        | US       |                2.89 |             75.71 |         84.81 |         74.61 |          72.62 |        76.81 |           88.97 |             45.2  |             66.01 |         4.48 |             69.68 | short              |                0.28 |                  0.34 |                 0.26 |
|     20 | PBF      | PBF                        | US       |                7.58 |             75.66 |         80.11 |         78.75 |          72.57 |        70.16 |           50.73 |             51.48 |             89.11 |         7.43 |             69.23 | short              |                0.23 |                 -0.1  |                -0    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  67.99 |                    74.27 |                 77.16 |              71.54 |                89.73 |                   10.27 |           93.81 |             64.35 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.23 |                  73.25 |                    74.08 |                 75.82 |              74.28 |                86.77 |                   13.23 |           83.85 |             59.18 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | STNE      | StoneCo Ltd.                         | OTHER    |                2    |                  77.6  |                    73.51 |                 73.17 |              72.35 |                70.04 |                   29.96 |           87.77 |             38.69 |       0.594 |         nan |       nan |        1.63 |         4.29 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              229.46 |                  65.32 |                    72.78 |                 75.28 |              68.91 |                83.25 |                   16.75 |           92.19 |             69.02 |     nan     |         nan |       nan |      nan    |        10.05 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  70.75 |                    72.68 |                 74.97 |              71.86 |                79.85 |                   20.15 |           85.33 |             65.48 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              107.45 |                  75.49 |                    70.18 |                 69.5  |              72.68 |                63.51 |                   36.49 |           62.6  |             69.01 |       0.148 |         nan |       nan |        1.78 |         7.42 |          4.61 |        5.23 |                 nan |              nan |                  12 |                  0.63 |
|            6 | NVDA      | NVIDIA Corporation                   | US       |             4783.59 |                  59.98 |                    69.85 |                 71.76 |              64.83 |                76.98 |                   23.02 |           86.15 |             77.9  |       0.008 |         nan |       nan |       27.47 |        14.9  |         29.16 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|            7 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.29 |                  72.76 |                    69.57 |                 67.94 |              71.92 |                68.58 |                   31.42 |           58.88 |            nan    |       0.225 |         nan |       nan |        1.54 |       nan    |          3.07 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | AVGO      | Broadcom Inc.                        | US       |             1464.28 |                  60.59 |                    69.16 |                 70.13 |              63.45 |                79.95 |                   20.05 |           90.87 |             54.37 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.65 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|            9 | BBWI      | Bath & Body Works, Inc.              | US       |                3.38 |                  77.31 |                    68.97 |                 65.81 |              68.7  |                55.39 |                   44.61 |           72.48 |             30.64 |       0.194 |         nan |       nan |        5.99 |         6.96 |          5.12 |        0.8  |                 nan |              nan |                  11 |                  0.58 |
|           10 | PBR       | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.5  |                  72.01 |                    68.05 |                 67.7  |              69.98 |                62.99 |                   37.01 |           62.6  |             67.99 |       0.142 |         nan |       nan |        1.82 |         5.05 |          5.08 |        5.76 |                 nan |              nan |                  12 |                  0.63 |
|           11 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.5  |                  68.07 |                    68.03 |                 69.26 |              67.33 |                66.82 |                   33.18 |           76.69 |             62.9  |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NLY       | NLY                                  | US       |               14.78 |                  68.4  |                    67.86 |                 68.02 |              64.78 |                70.17 |                   29.83 |           89.46 |             28.98 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                8.83 |                  58.17 |                    67.64 |                 71.06 |              62.81 |                77.24 |                   22.76 |           91.04 |             70.23 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | WB        | Weibo Corporation                    | OTHER    |                1.42 |                  78.6  |                    67.61 |                 63.45 |              70.11 |                63.38 |                   36.62 |           61.62 |             21.14 |     nan     |         nan |       nan |        1.84 |         5.23 |          5.55 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           13 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.44 |                  68.77 |                    67.41 |                 68.27 |              66.03 |                71.82 |                   28.18 |           84.67 |             35.87 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|           14 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.84 |                  75.88 |                    67.35 |                 64.06 |              69.92 |                56.47 |                   43.53 |           55.1  |             51.14 |       0.034 |         nan |       nan |       16.42 |        14    |         19.77 |        1.23 |                 nan |              nan |                  12 |                  0.63 |
|           15 | IHS       | IHS Holding Limited                  | OTHER    |                2.46 |                  71.91 |                    67.11 |                 67.07 |              70.59 |                61.15 |                   38.85 |           55.29 |             78.12 |      -0.113 |         nan |       nan |        7.54 |        15.4  |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | TTE.PA    | TTE.PA                               | EUROPE   |              168.38 |                  63.62 |                    67.07 |                 67.95 |              66.59 |                72.78 |                   27.22 |           67.52 |             76.83 |     nan     |         nan |       nan |      nan    |         8.87 |         11.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN       | DVN                                  | US       |               45.46 |                  63.68 |                    66.93 |                 68.11 |              65.11 |                70.39 |                   29.61 |           76.06 |             65.91 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  67.99 |                    74.27 |                 77.16 |              71.54 |                89.73 |                   10.27 |           93.81 |             64.35 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.23 |                  73.25 |                    74.08 |                 75.82 |              74.28 |                86.77 |                   13.23 |           83.85 |             59.18 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              229.46 |                  65.32 |                    72.78 |                 75.28 |              68.91 |                83.25 |                   16.75 |           92.19 |             69.02 |     nan     |         nan |       nan |      nan    |        10.05 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  70.75 |                    72.68 |                 74.97 |              71.86 |                79.85 |                   20.15 |           85.33 |             65.48 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | STNE     | StoneCo Ltd.                         | OTHER    |                2    |                  77.6  |                    73.51 |                 73.17 |              72.35 |                70.04 |                   29.96 |           87.77 |             38.69 |       0.594 |         nan |       nan |        1.63 |         4.29 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4783.59 |                  59.98 |                    69.85 |                 71.76 |              64.83 |                76.98 |                   23.02 |           86.15 |             77.9  |       0.008 |         nan |       nan |       27.47 |        14.9  |         29.16 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                8.83 |                  58.17 |                    67.64 |                 71.06 |              62.81 |                77.24 |                   22.76 |           91.04 |             70.23 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1464.28 |                  60.59 |                    69.16 |                 70.13 |              63.45 |                79.95 |                   20.05 |           90.87 |             54.37 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.65 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | KDP      | KDP                                  | US       |               38.14 |                  56.1  |                    66.39 |                 69.78 |              61.81 |                79.92 |                   20.08 |           87.97 |             70.33 |     nan     |         nan |       nan |      nan    |        12.86 |         32.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.87 |                  58.48 |                    66.68 |                 69.71 |              61.22 |                76.9  |                   23.1  |           95.83 |             52.67 |     nan     |         nan |       nan |      nan    |         9.32 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              107.45 |                  75.49 |                    70.18 |                 69.5  |              72.68 |                63.51 |                   36.49 |           62.6  |             69.01 |       0.148 |         nan |       nan |        1.78 |         7.42 |          4.61 |        5.23 |                 nan |              nan |                  12 |                  0.63 |
|          nan | GNK      | GNK                                  | US       |                1.04 |                  56.85 |                    66.16 |                 69.31 |              61.92 |                77.31 |                   22.69 |           86.11 |             70.66 |     nan     |         nan |       nan |      nan    |        15.21 |         30.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.5  |                  68.07 |                    68.03 |                 69.26 |              67.33 |                66.82 |                   33.18 |           76.69 |             62.9  |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | C5H.IR   | C5H.IR                               | EUROPE   |                1.81 |                  52.99 |                    64.7  |                 68.64 |              58.31 |                81.62 |                   18.38 |           97.44 |             54.61 |     nan     |         nan |       nan |      nan    |        11.15 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | HMC      | Honda Motor Co., Ltd.                | OTHER    |               36.46 |                  58.45 |                    64.85 |                 68.32 |              63.6  |                72.73 |                   27.27 |           73.85 |             84.27 |       0.04  |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|           13 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.44 |                  68.77 |                    67.41 |                 68.27 |              66.03 |                71.82 |                   28.18 |           84.67 |             35.87 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | DVN      | DVN                                  | US       |               45.46 |                  63.68 |                    66.93 |                 68.11 |              65.11 |                70.39 |                   29.61 |           76.06 |             65.91 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                                  | US       |               14.78 |                  68.4  |                    67.86 |                 68.02 |              64.78 |                70.17 |                   29.83 |           89.46 |             28.98 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              168.38 |                  63.62 |                    67.07 |                 67.95 |              66.59 |                72.78 |                   27.22 |           67.52 |             76.83 |     nan     |         nan |       nan |      nan    |         8.87 |         11.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.29 |                  72.76 |                    69.57 |                 67.94 |              71.92 |                68.58 |                   31.42 |           58.88 |            nan    |       0.225 |         nan |       nan |        1.54 |       nan    |          3.07 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CRGY     | CRGY     | US       |                4.66 |                     0.04 |     0.02 |      0.2  |                  53.52 |                        76.33 |         82.45 |         77.98 |          76.94 |        81.39 |           69.4  |             87.97 |         6.01 |
|               2 | ARGX.BR  | ARGX.BR  | EUROPE   |               55.57 |                     0.02 |    -0    |      0.17 |                  50.06 |                        75.43 |         78.76 |         71.97 |          67.41 |        60.92 |           92.44 |             66.98 |         5.99 |
|               3 | WDAY     | WDAY     | US       |               40.58 |                     0.05 |    -0.04 |      0.09 |                  82.81 |                        74.35 |         69.5  |         72.75 |          64.26 |        62.65 |           73.51 |             72.36 |         8.56 |
|               4 | DK       | DK       | US       |                3.78 |                     0.03 |    -0.01 |      0.23 |                  59.01 |                        74.3  |         82.9  |         83.7  |          75.16 |        61.97 |           54    |             85.28 |         7.06 |
|               5 | PLTR     | PLTR     | US       |              360.26 |                     0.06 |    -0.06 |      0.01 |                  83.58 |                        74.15 |         58.76 |         66.39 |          61.95 |        59.19 |           90.12 |             69.29 |         8.55 |
|               6 | APA      | APA      | US       |               12.89 |                     0.04 |     0.01 |      0.14 |                  61.94 |                        72.25 |         75.98 |         72.31 |          74.45 |        75.21 |           73.19 |             68.88 |         5.6  |
|               7 | CRM      | CRM      | US       |              183.47 |                     0.02 |     0.01 |      0.34 |                  45.28 |                        72.08 |         83.75 |         78.07 |          61.86 |        57.96 |           61.33 |             74.33 |         7.68 |
|               8 | AVAH     | AVAH     | US       |                2.55 |                     0.02 |     0.02 |      0.43 |                  41.84 |                        71.9  |         85.62 |         76.57 |          68.99 |        68.7  |           93.09 |             27.98 |         7.45 |
|               9 | DAR      | DAR      | US       |                8.85 |                     0.05 |     0.01 |      0.1  |                  61.37 |                        71.9  |         72.82 |         63.04 |          72.27 |        78.16 |           91.72 |             52.93 |         4.19 |
|              10 | BAX      | BAX      | US       |               11.48 |                     0.07 |    -0.01 |     -0.06 |                  65    |                        71.66 |         50.62 |         72.72 |          72.97 |        70.67 |           75.96 |             69.04 |         6.04 |
|              11 | VWS.CO   | VWS.CO   | EUROPE   |               27.94 |                     0.02 |     0.01 |      0.2  |                  44.02 |                        71.14 |         81.03 |         68.87 |          64.93 |        60.83 |           86.49 |             44.86 |         5.64 |
|              12 | EQNR     | EQNR     | US       |               85.91 |                     0.05 |     0.02 |      0.09 |                  61.8  |                        71.11 |         71.59 |         71.01 |          73.82 |        72.71 |           72.38 |             77.1  |         5.28 |
|              13 | TALO     | TALO     | US       |                2.42 |                     0.05 |     0.01 |      0.17 |                  65.55 |                        70.98 |         75.06 |         69    |          69.86 |        70.94 |           67.69 |             67.21 |         5.53 |
|              14 | TECK     | TECK     | US       |               29.15 |                     0.04 |    -0    |      0.04 |                  59.58 |                        70.94 |         69.41 |         68.18 |          73.43 |        71.58 |           86.32 |             66.91 |         5.62 |
|              15 | METSO.HE | METSO.HE | EUROPE   |               14.69 |                     0.03 |    -0.02 |      0.06 |                  65.56 |                        70.79 |         70.41 |         61.58 |          61.41 |        58.16 |           78.67 |             66.77 |         4.71 |
|              16 | NTG.CO   | NTG.CO   | EUROPE   |                0.8  |                     0.04 |    -0.04 |      0.04 |                  76.03 |                        70.6  |         63.93 |         71.29 |          69.39 |        63.49 |           83.44 |             45.76 |         5.12 |
|              17 | RAND.AS  | RAND.AS  | EUROPE   |                6.84 |                     0.04 |    -0.03 |      0    |                  67.19 |                        70.17 |         57.7  |         73.29 |          67.38 |        62.37 |           79.74 |             49.98 |         6.66 |
|              18 | CMG      | CMG      | US       |               40.22 |                     0.04 |    -0.03 |      0.13 |                  70.06 |                        70.17 |         68.07 |         61.07 |          55.25 |        57.49 |           88.98 |             52.2  |         6.48 |
|              19 | GL9.IR   | GL9.IR   | EUROPE   |                5.38 |                     0.07 |     0    |     -0.06 |                  63.13 |                        70.15 |         47.01 |         60.73 |          74.34 |        70.37 |           96.95 |             72.83 |         2.21 |
|              20 | FLS.CO   | FLS.CO   | EUROPE   |                4.09 |                     0.06 |    -0.04 |      0.14 |                  81.04 |                        70.14 |         71.86 |         55.96 |          54.15 |        57.64 |           86.78 |             31.3  |         4.91 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | ORCL     | Oracle Corporation      | US       |              393.32 |             43.33 |         62.45 |         41.59 |          41.79 |        44.87 |           45.19 |             59.9  |             45.07 |         7.85 |             89.63 | short              |               -2.07 |                  0.66 |                 0.54 |
|    nan | SHOE     | Shoe Station Group Inc. | US       |                0.33 |             35.18 |         35.69 |         26.91 |          34.67 |        45.42 |           41.77 |             40.51 |             68.02 |         7.01 |             84.18 | long               |               -0.4  |                  1    |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name               | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     28 | AMC      | AMC                | US       |                2.03 |             74.55 |         66.07 |         77.91 |          74.22 |        74.88 |           83.33 |             61.76 |            nan    |         9.63 |             63.43 | swing              |                0.82 |                  4.41 |                 4.48 |
|    180 | AMV0.DE  | AMV0.DE            | EUROPE   |                3.77 |             64.41 |         65.99 |         51.97 |          62.84 |        76.22 |           89.5  |             66.93 |             81.68 |         6    |             59.47 | long               |               -0.26 |                  3.78 |                 3.71 |
|     46 | DOCU     | DOCU               | US       |               11.23 |             72.04 |         81.18 |         78.11 |          65.97 |        60.37 |           59.33 |             82.51 |             50.15 |         7.68 |             67.64 | short              |              nan    |                  3.26 |                 2.75 |
|    311 | VOR      | Vor Biopharma Inc. | US       |                1.27 |             57.74 |         63.91 |         66.1  |          51.56 |        37.47 |           31.38 |             60.32 |             22.22 |         8.52 |             75.5  | swing              |                0.96 |                  3    |                 2.36 |
|      5 | UGP      | UGP                | US       |                6.67 |             79.81 |         84.34 |         84.61 |          75.27 |        68.78 |           58.32 |             75.28 |             64.3  |         4.31 |             68.66 | swing              |                0.4  |                  2.86 |                 1.95 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    707 | MTRX     | Matrix Service Company | US       |                0.26 |             30.23 |         26.91 |         25.43 |          33.55 |        38.97 |           37.77 |             44.49 |             49.51 |         5.87 |             83.59 | long               |               -1.14 |                 -2.74 |               nan    |
|    674 | QURE     | QURE                   | US       |                2.65 |             37.36 |         29.13 |         54.59 |          45.59 |        27.83 |            7.22 |             24.13 |             16.13 |         9.91 |             64.8  | swing              |              nan    |                 -2.57 |               nan    |
|    279 | BOX      | BOX                    | US       |                4.15 |             59.13 |         71.18 |         65.64 |          52.62 |        46.37 |           55.69 |             34.75 |             24.11 |         5.67 |             68.2  | short              |               -0.03 |                 -2.51 |                -2.37 |
|    161 | DEZ.DE   | DEZ.DE                 | EUROPE   |                1.96 |             65.31 |         77.84 |         69.71 |          56.91 |        60.9  |          nan    |             32.64 |             65.72 |         6.32 |             66.84 | short              |               -0.44 |                 -2.32 |                -2.83 |
|    375 | CRWD     | CRWD                   | US       |              187.65 |             55.55 |         55.09 |         62.05 |          56.02 |        38.68 |           36.9  |             43.57 |              1.74 |         7.58 |             69.68 | swing              |                0.22 |                 -2.27 |                -1.79 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
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
- Excluded by hard/data filters: **286**
- Event watch (otherwise eligible): **2**
- Final eligible: **712**
- Eligible change vs previous stored run: **+4**

Top exclusion categories:
- liquidity: 228
- price: 178
- market_cap: 151
- price_history: 14
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CRGY | 7 |  | 1 |  | 2 | main,pullback |
| DK | 9 |  | 4 |  | 2 | main,pullback |
| DDI | 51 | 1 |  | 1 | 1 | value,quality_value |
| BION.SW | 52 | 2 | 24 | 2 | 1 | value,quality_value |
| PBR-A | 61 | 5 |  | 7 | 1 | value,quality_value |
| NVDA | 72 | 6 |  | 5 | 1 | value,quality_value |
| IRWD | 91 | 4 |  | 3 | 1 | value,quality_value |
| AVGO | 518 | 8 |  | 6 | 1 | value,quality_value |
| STNE | 546 | 3 |  | 4 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| DELL | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| DSX | 4 |  |  |  | 1 | main |
| UGP | 5 |  |  |  | 1 | main |
| CMBT.BR | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (FRO, DELL, VLO, DSX, UGP, CMBT.BR, DINO, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.82 | 73.25 | 60.00 | 83.85 | 59.18 | 86.77 | 71.52 |
| 2 | XNET | value+pullback | 66.55 | 59.72 | 68.82 | 62.22 | 83.09 | 68.96 | 47.04 |
| 3 | WKC | value+pullback | 64.88 | 59.99 | 65.88 | 61.67 | 76.34 | 67.63 | 66.47 |
| 4 | AMCX | value+pullback | 63.94 | 65.95 | 58.76 | 47.49 | 80.70 | 71.34 | 66.28 |
| 5 | LYFT | value+pullback | 62.79 | 61.66 | 86.75 | 54.44 | 56.36 | 44.02 | 56.17 |
| 6 | ALL-PH | value+pullback | 59.96 | 61.20 | 57.23 | 71.12 | 42.92 | 61.66 | 44.58 |
| 7 | VOLV-B.ST | value+pullback | 59.28 | 75.88 | 47.35 | 55.10 | 51.14 | 56.47 | 55.72 |
| 8 | DDI | value | 58.85 | 67.99 | 42.92 | 93.81 | 64.35 | 89.73 | 71.68 |
| 9 | BBWI | value+pullback | 58.85 | 77.31 | 42.56 | 72.48 | 30.64 | 55.39 | 49.70 |
| 10 | MSFT | value+pullback | 58.74 | 61.86 | 61.31 | 57.73 | 60.56 | 50.67 | 56.28 |
| 11 | ORC | value+pullback | 58.57 | 63.46 | 50.48 | 74.47 | 37.16 | 60.11 | 46.23 |
| 12 | MAGN | value+pullback | 58.47 | 63.97 | 59.96 | 52.17 | 37.66 | 63.50 | 45.92 |
| 13 | AF.PA | value+pullback | 58.11 | 67.87 | 72.18 | 42.70 | 58.83 | 37.10 | 49.67 |
| 14 | LKFT.AS | value+pullback | 57.72 | 64.82 | 63.53 | 53.11 | 22.21 | 61.05 | 43.97 |
| 15 | TV | value+pullback | 57.50 | 67.97 | 60.98 | 45.32 | 27.23 | 61.72 | 32.40 |
| 16 | GASS | value+pullback | 57.39 | 60.59 | 68.49 | 39.78 | 50.11 | 55.58 | 49.38 |
| 17 | UNIT | value+pullback | 56.58 | 80.01 | 42.01 | 65.23 | 32.36 | 45.29 | 49.69 |
| 18 | IRWD | value | 56.54 | 70.75 | 52.01 | 85.33 | 65.48 | 79.85 | 69.19 |
| 19 | NOVO-B.CO | value+pullback | 55.74 | 62.95 | 51.33 | 61.80 | 48.32 | 49.61 | 53.23 |
| 20 | MFA | value+pullback | 55.52 | 56.95 | 50.30 | 73.11 | 30.63 | 59.16 | 42.70 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 4 / 21 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 69.2 | 13 / 37 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=3, large_20_100b=1, mega_100b_plus=1
