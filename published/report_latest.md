# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-06

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

- **EUROPE:** 87.4/100
- **OTHER:** 78.1/100
- **US:** 86.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.84 |             82.29 |         85.06 |         82.62 |          81.94 |        81.97 |           90.48 |             70.18 |             68.12 |         5.41 |             69.68 | short              |               -0.3  |                  0.73 |                 0.39 |
|      2 | DELL     | DELL                       | US       |              291.42 |             82.02 |         88.61 |         84.55 |          79.49 |        68.17 |           72.1  |             80.16 |             37.27 |         7.53 |             68.77 | short              |               -0.19 |                  3.41 |                 3.08 |
|      3 | VLO      | VLO                        | US       |               91.85 |             81.55 |         82.88 |         83.85 |          80.22 |        76.51 |           84.55 |             63.8  |             58.39 |         3.25 |             67.5  | swing              |               -0.47 |                  0.18 |               nan    |
|      4 | DSX      | DSX                        | US       |                0.32 |             80.37 |         86.69 |         75.28 |          75.24 |        85.46 |           91.12 |             44.52 |             98.66 |         5.96 |             67.86 | short              |               -0.09 |                  1.65 |                 0.8  |
|      5 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.87 |             79.97 |         85.56 |         79.94 |          79.61 |        79.99 |           95.93 |             52.12 |             61.54 |         3.96 |             69.68 | short              |                0.31 |                  0.42 |               nan    |
|      6 | KIN.BR   | KIN.BR                     | EUROPE   |                1.3  |             79.45 |         85.14 |         83.88 |          75.03 |        65.92 |           89.49 |             64.45 |             18.62 |         3.92 |             69.68 | short              |                0.51 |                  1.58 |                 0.99 |
|      7 | UGP      | UGP                        | US       |                6.68 |             79.41 |         83.86 |         84.2  |          74.96 |        68.48 |           57.82 |             75.03 |             64.92 |         4.35 |             68.66 | swing              |               -0.39 |                  3.13 |                 2.28 |
|      8 | CRGY     | CRGY                       | US       |                3.91 |             79.3  |         81.94 |         77.51 |          76.63 |        81.09 |           69.6  |             87.85 |             95.85 |         6.03 |             69.23 | short              |               -0.45 |                  1.19 |               nan    |
|      9 | DINO     | DINO                       | US       |               16.13 |             78.89 |         84.37 |         83.52 |          74.26 |        65.98 |           47.9  |             72.54 |             70.41 |         4.34 |             69.68 | short              |               -0.54 |                  1.3  |                 0.87 |
|     10 | PARR     | Par Pacific Holdings, Inc. | US       |                3.51 |             78.78 |         81.34 |         79.06 |          78.5  |        76.18 |           79.62 |             63.61 |             67.54 |         6.92 |             85.07 | short              |                0.43 |                  0.19 |                 0.05 |
|     11 | DK       | DK                         | US       |                3.79 |             78.73 |         82.43 |         83.32 |          75.03 |        62.02 |           54.08 |             85.12 |             38.9  |         7.1  |             69.68 | swing              |               -0.38 |                 -0.24 |                -0.52 |
|     12 | MT.AS    | MT.AS                      | EUROPE   |               50.7  |             78.38 |         78.3  |         78.68 |          78.47 |        74.48 |           72.71 |             79.23 |             63.31 |         4.94 |             69.68 | swing              |                0.33 |                  1.8  |                 1.37 |
|     13 | OKTA     | OKTA                       | US       |               25.66 |             78.19 |         85.51 |         81.66 |          74.73 |        62.78 |           76.97 |             69.98 |             17.51 |         7.59 |             67.86 | short              |                1.06 |                  0.14 |                -0.45 |
|     14 | MU       | MU                         | US       |              987.97 |             77.78 |         74.23 |         71.02 |          81.33 |        83.07 |           95.51 |             52.44 |             75.52 |         8.21 |             69.68 | long               |               -0.43 |                  1.03 |               nan    |
|     15 | WT       | WT                         | US       |                3.25 |             77.4  |         80.8  |         81.05 |          73.99 |        64.41 |           70.67 |             74.73 |             31.57 |         5.51 |             69.68 | swing              |               -0.3  |                  0.38 |               nan    |
|     16 | PR       | PR                         | US       |               16.84 |             76.36 |         80.67 |         75.9  |          75.31 |        76.81 |           76.1  |             73.73 |             74.46 |         4.07 |             68.32 | short              |               -0.62 |                  0.25 |                -0.07 |
|     17 | ABN.AS   | ABN.AS                     | EUROPE   |               35.15 |             76.09 |         77.78 |         77.97 |          74.41 |        69.62 |           78.51 |             55.98 |             49.57 |         2.74 |             69.68 | swing              |                0.5  |                  0.57 |                 0.17 |
|     18 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.78 |             75.98 |         86.25 |         78.42 |          73.53 |        68.67 |           79.57 |             77.34 |             36.4  |         5.08 |             84.92 | short              |               -0.21 |                  0.39 |                 0.2  |
|     19 | GTLB     | GTLB                       | US       |                7.14 |             75.88 |         89.4  |         85.6  |          66.15 |        50.7  |           56.89 |             88.86 |             10.92 |         8.42 |             69.68 | short              |               -0.44 |                  2.63 |                 2.05 |
|     20 | ANF      | ANF                        | US       |                5.72 |             75.65 |         85.97 |         79.34 |          71.66 |        71.96 |           85.34 |             42.51 |             58.23 |         8.54 |             67.64 | short              |               -0.26 |                  0.39 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DDI      | DoubleDown Interactive Co., Ltd.                     | OTHER    |                0.55 |                  67.99 |                    73.94 |                 76.7  |              71.2  |                89.28 |                   10.72 |           93.81 |             61.72 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.6  |                    73.75 |                 73.51 |              72.6  |                70.41 |                   29.59 |           87.77 |             40.57 |       0.594 |         nan |       nan |        1.63 |         4.29 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.61 |                  70.75 |                    72.71 |                 75.02 |              71.9  |                79.9  |                   20.1  |           85.33 |             65.75 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.23 |                  72.8  |                    71.81 |                 71.09 |              69.77 |                82.02 |                   17.98 |           88.57 |             25.88 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.44 |                  75.62 |                    69.98 |                 69.13 |              71.41 |                74.1  |                   25.9  |           74.2  |             36.23 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              229.46 |                  60.25 |                    69.77 |                 72.91 |              65.16 |                83.07 |                   16.93 |           92.42 |             68.23 |     nan     |         nan |       nan |      nan    |        10.06 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | BBWI     | Bath & Body Works, Inc.                              | US       |                3.39 |                  77.31 |                    69.65 |                 66.76 |              69.4  |                56.36 |                   43.64 |           72.48 |             35.94 |       0.194 |         nan |       nan |        5.99 |         6.96 |          5.12 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            7 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               45.09 |                  67.13 |                    68.35 |                 69.03 |              67.37 |                68.33 |                   31.67 |           72.88 |            nan    |       0.384 |         nan |       nan |        7.45 |       nan    |          2.93 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|            8 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras                 | OTHER    |              107.52 |                  79.16 |                    68.13 |                 65.76 |              72.8  |                49.61 |                   50.39 |           49.57 |             68.71 |       0.148 |         nan |       nan |        1.78 |         7.42 |          4.61 |        5.32 |                 nan |              nan |                  12 |                  0.63 |
|            9 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.51 |                  67.77 |                    67.9  |                 69.49 |              66.61 |                63.66 |                   36.34 |           79.62 |             63.61 |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | NLY      | NLY                                                  | US       |               14.79 |                  68.31 |                    67.8  |                 67.97 |              64.73 |                70.15 |                   29.85 |           89.33 |             29.18 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                  | US       |                8.84 |                  58.62 |                    67.75 |                 71.06 |              63.07 |                76.9  |                   23.1  |           90.48 |             70.18 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | WB       | Weibo Corporation                                    | OTHER    |                1.42 |                  78.6  |                    67.74 |                 63.63 |              70.25 |                63.64 |                   36.36 |           61.62 |             22.07 |     nan     |         nan |       nan |        1.84 |         5.23 |          5.55 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | DVN      | DVN                                                  | US       |               45.49 |                  63.46 |                    66.78 |                 67.98 |              64.95 |                70.28 |                   29.72 |           75.86 |             66.11 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS      | IHS Holding Limited                                  | OTHER    |                2.47 |                  71.75 |                    66.67 |                 66.62 |              70.09 |                59.17 |                   40.83 |           55.14 |             77.79 |      -0.113 |         nan |       nan |        7.54 |        15.4  |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           12 | UNIT     | Uniti Group Inc.                                     | US       |                2.12 |                  80.01 |                    66.48 |                 63.3  |              68.95 |                44.58 |                   55.42 |           62.54 |             33.16 |      -0.105 |         nan |       nan |        9.13 |       -14.32 |          2.65 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           13 | APA      | APA Corporation                                      | US       |               12.89 |                  69.52 |                    66.41 |                 64.64 |              66.22 |                63.75 |                   36.25 |           67.07 |             46.87 |       0.143 |         nan |       nan |        3.38 |        10.21 |          9.02 |        1.05 |                 nan |              nan |                  12 |                  0.63 |
|           14 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.1  |                  68.38 |                    66.34 |                 67.26 |              65.83 |                68.94 |                   31.06 |           79.48 |             41.82 |     nan     |         nan |       nan |        3.93 |        56.78 |          4.54 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | KDP      | KDP                                                  | US       |               38.16 |                  55.82 |                    66.24 |                 69.67 |              61.62 |                79.91 |                   20.09 |           87.99 |             70.42 |     nan     |         nan |       nan |      nan    |        12.86 |         32.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GNK      | GNK                                                  | US       |                1.04 |                  56.41 |                    66.02 |                 69.28 |              61.68 |                77.51 |                   22.49 |           86.37 |             71.17 |     nan     |         nan |       nan |      nan    |        15.21 |         30.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | DDI      | DoubleDown Interactive Co., Ltd.                     | OTHER    |                0.55 |                  67.99 |                    73.94 |                 76.7  |              71.2  |                89.28 |                   10.72 |           93.81 |             61.72 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.61 |                  70.75 |                    72.71 |                 75.02 |              71.9  |                79.9  |                   20.1  |           85.33 |             65.75 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE     | StoneCo Ltd.                                         | OTHER    |                2.01 |                  77.6  |                    73.75 |                 73.51 |              72.6  |                70.41 |                   29.59 |           87.77 |             40.57 |       0.594 |         nan |       nan |        1.63 |         4.29 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                                             | EUROPE   |              229.46 |                  60.25 |                    69.77 |                 72.91 |              65.16 |                83.07 |                   16.93 |           92.42 |             68.23 |     nan     |         nan |       nan |      nan    |        10.06 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | BION.SW  | BB Biotech AG                                        | EUROPE   |                3.23 |                  72.8  |                    71.81 |                 71.09 |              69.77 |                82.02 |                   17.98 |           88.57 |             25.88 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | FRO      | FRO                                                  | US       |                8.84 |                  58.62 |                    67.75 |                 71.06 |              63.07 |                76.9  |                   23.1  |           90.48 |             70.18 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                                                  | US       |               38.16 |                  55.82 |                    66.24 |                 69.67 |              61.62 |                79.91 |                   20.09 |           87.99 |             70.42 |     nan     |         nan |       nan |      nan    |        12.86 |         32.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PARR     | Par Pacific Holdings, Inc.                           | US       |                3.51 |                  67.77 |                    67.9  |                 69.49 |              66.61 |                63.66 |                   36.34 |           79.62 |             63.61 |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | GNK      | GNK                                                  | US       |                1.04 |                  56.41 |                    66.02 |                 69.28 |              61.68 |                77.51 |                   22.49 |           86.37 |             71.17 |     nan     |         nan |       nan |      nan    |        15.21 |         30.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | GSL      | Global Ship Lease, Inc.                              | OTHER    |                1.44 |                  75.62 |                    69.98 |                 69.13 |              71.41 |                74.1  |                   25.9  |           74.2  |             36.23 |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            7 | 0P6O.IL  | Volkswagen AG                                        | OTHER    |               45.09 |                  67.13 |                    68.35 |                 69.03 |              67.37 |                68.33 |                   31.67 |           72.88 |            nan    |       0.384 |         nan |       nan |        7.45 |       nan    |          2.93 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|          nan | CMBT.BR  | CMBT.BR                                              | EUROPE   |                4.87 |                  55.49 |                    64.87 |                 68.27 |              58.97 |                76.7  |                   23.3  |           95.93 |             52.12 |     nan     |         nan |       nan |      nan    |         9.33 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                                                  | US       |               45.49 |                  63.46 |                    66.78 |                 67.98 |              64.95 |                70.28 |                   29.72 |           75.86 |             66.11 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                                                  | US       |               14.79 |                  68.31 |                    67.8  |                 67.97 |              64.73 |                70.15 |                   29.85 |           89.33 |             29.18 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                                               | EUROPE   |                1.81 |                  51.04 |                    63.61 |                 67.81 |              56.92 |                81.69 |                   18.31 |           97.56 |             54.67 |     nan     |         nan |       nan |      nan    |        11.15 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.1  |                  68.38 |                    66.34 |                 67.26 |              65.83 |                68.94 |                   31.06 |           79.48 |             41.82 |     nan     |         nan |       nan |        3.93 |        56.78 |          4.54 |        2.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                                               | EUROPE   |               24.01 |                  52.53 |                    63.49 |                 67.18 |              57.32 |                79.81 |                   20.19 |           95.47 |             51.39 |     nan     |         nan |       nan |      nan    |        11.64 |         11.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                                                 | US       |                3.91 |                  57.04 |                    64.46 |                 66.89 |              62.62 |                70.92 |                   29.08 |           69.6  |             87.85 |     nan     |         nan |       nan |      nan    |         6.32 |        172.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                  | US       |                2.9  |                  61.03 |                    65.1  |                 66.87 |              61.03 |                69.76 |                   30.24 |           88.56 |             45.36 |     nan     |         nan |       nan |      nan    |        11.1  |          7.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                  | US       |               15.18 |                  56.7  |                    64.22 |                 66.81 |              59.77 |                74.99 |                   25.01 |           87.5  |             54.5  |     nan     |         nan |       nan |      nan    |        10.97 |         23.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CRGY     | CRGY     | US       |                3.91 |                     0.04 |     0.02 |      0.2  |                  53.52 |                        76.09 |         81.94 |         77.51 |          76.63 |        81.09 |           69.6  |             87.85 |         6.03 |
|               2 | ARGX.BR  | ARGX.BR  | EUROPE   |               55.9  |                     0.02 |    -0    |      0.17 |                  50.06 |                        75.43 |         78.95 |         72.44 |          67.7  |        61.06 |           92.28 |             66.63 |         6.02 |
|               3 | WDAY     | WDAY     | US       |               40.6  |                     0.05 |    -0.04 |      0.09 |                  82.81 |                        74.23 |         69.12 |         72.45 |          64.18 |        62.78 |           73.53 |             72.51 |         8.6  |
|               4 | DK       | DK       | US       |                3.79 |                     0.03 |    -0.01 |      0.23 |                  59.01 |                        74.1  |         82.43 |         83.32 |          75.03 |        62.02 |           54.08 |             85.12 |         7.1  |
|               5 | CRM      | CRM      | US       |              183.58 |                     0.02 |     0.01 |      0.34 |                  45.28 |                        71.82 |         83.4  |         77.72 |          61.57 |        57.7  |           60.83 |             74.4  |         7.72 |
|               6 | TECK     | TECK     | US       |               29.17 |                     0.04 |    -0    |      0.04 |                  59.58 |                        71.75 |         69.64 |         69.07 |          74.39 |        72.01 |           85.82 |             72.22 |         5.64 |
|               7 | AVAH     | AVAH     | US       |                2.55 |                     0.02 |     0.02 |      0.43 |                  41.84 |                        71.59 |         85.21 |         76.19 |          68.71 |        68.44 |           92.47 |             28.12 |         7.49 |
|               8 | VWS.CO   | VWS.CO   | EUROPE   |               27.94 |                     0.02 |     0.01 |      0.2  |                  44.02 |                        71.49 |         81.36 |         69.7  |          65.53 |        61.14 |           86.74 |             45.73 |         5.65 |
|               9 | BAX      | BAX      | US       |               11.49 |                     0.07 |    -0.01 |     -0.06 |                  65    |                        71.46 |         50.21 |         72.5  |          72.84 |        70.56 |           75.58 |             69.01 |         6.06 |
|              10 | MGTX     | MGTX     | US       |                1.15 |                     0.07 |     0.01 |      0.06 |                  58.74 |                        71.33 |         66.15 |         76.33 |          73.7  |        62.63 |           69.72 |             69.44 |         6.71 |
|              11 | METSO.HE | METSO.HE | EUROPE   |               14.69 |                     0.03 |    -0.02 |      0.06 |                  65.56 |                        70.9  |         70.71 |         62.05 |          61.68 |        58.24 |           78.54 |             66.69 |         4.73 |
|              12 | EQNR     | EQNR     | US       |               85.96 |                     0.05 |     0.02 |      0.09 |                  61.8  |                        70.84 |         71.18 |         70.61 |          73.53 |        72.49 |           72.17 |             76.97 |         5.31 |
|              13 | RAND.AS  | RAND.AS  | EUROPE   |                6.84 |                     0.04 |    -0.03 |      0    |                  67.19 |                        70.52 |         57.95 |         73.94 |          67.84 |        62.69 |           79.69 |             50.21 |         6.67 |
|              14 | FLS.CO   | FLS.CO   | EUROPE   |                4.1  |                     0.06 |    -0.04 |      0.14 |                  81.04 |                        70.47 |         72.24 |         56.8  |          54.68 |        57.76 |           86.69 |             32.39 |         4.96 |
|              15 | GL9.IR   | GL9.IR   | EUROPE   |                5.38 |                     0.07 |     0    |     -0.06 |                  63.13 |                        70.42 |         47.25 |         61.22 |          74.65 |        70.4  |           97.06 |             72.88 |         2.22 |
|              16 | CMG      | CMG      | US       |               40.25 |                     0.04 |    -0.03 |      0.13 |                  70.06 |                        69.68 |         67.51 |         60.72 |          54.87 |        57.02 |           87.83 |             52.33 |         6.49 |
|              17 | GEN      | GEN      | US       |               15.79 |                     0.02 |    -0.01 |      0.06 |                  53.7  |                        69.68 |         72.34 |         72.46 |          69.03 |        69.73 |           74.42 |             70.04 |         5.61 |
|              18 | BCRX     | BCRX     | US       |                2.19 |                     0.06 |     0.01 |      0.06 |                  63.9  |                        69.47 |         65.34 |         65.78 |          69.54 |        75.71 |           84.11 |             67.83 |         5.57 |
|              19 | AG       | AG       | US       |                8.89 |                     0.04 |     0.01 |      0.14 |                  55.76 |                        69.47 |         72.28 |         57.24 |          61.47 |        67.46 |           88.59 |             48.31 |         8.42 |
|              20 | DSFIR.AS | DSFIR.AS | EUROPE   |               22.89 |                     0.03 |    -0.02 |     -0.01 |                  60.97 |                        69.34 |         58.61 |         74.39 |          67.13 |        53.62 |           59.9  |             73.46 |         5.11 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | ORCL     | Oracle Corporation      | US       |              393.56 |             45.4  |         62.82 |         41.76 |          43.53 |        47.27 |           56.75 |             60.08 |             38.5  |         7.82 |             89.63 | short              |                2.86 |                  0.4  |                 0.16 |
|    nan | SHOE     | Shoe Station Group Inc. | US       |                0.33 |             35.59 |         36.06 |         27.46 |          35.11 |        45.76 |           41.77 |             41.06 |             68.02 |         7.02 |             84.18 | long               |                0.35 |                  0.74 |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    113 | HAFN     | HAFN    | US       |                3.97 |             66.93 |         80.67 |         68.69 |          62.71 |        65.17 |           70.68 |             35.43 |             61.43 |         5.23 |             69.68 | short              |               -0.23 |                  4.53 |               nan    |
|      2 | DELL     | DELL    | US       |              291.42 |             82.02 |         88.61 |         84.55 |          79.49 |        68.17 |           72.1  |             80.16 |             37.27 |         7.53 |             68.77 | short              |               -0.19 |                  3.41 |                 3.08 |
|      7 | UGP      | UGP     | US       |                6.68 |             79.41 |         83.86 |         84.2  |          74.96 |        68.48 |           57.82 |             75.03 |             64.92 |         4.35 |             68.66 | swing              |               -0.39 |                  3.13 |                 2.28 |
|    409 | 0QXR.IL  | 0QXR.IL | OTHER    |               25.94 |             54.18 |         52.48 |         42.09 |          55.89 |        70.49 |           75    |            nan    |             82.35 |         9.12 |             57.77 | long               |                1.18 |                  3.12 |                 2.96 |
|     52 | RNW      | RNW     | US       |                2.16 |             70.85 |         76.86 |         70.32 |          68.3  |        71.38 |          nan    |             87.01 |             77.44 |         5.89 |             66.84 | short              |               -0.51 |                  2.89 |                 3.18 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    379 | 0P6O.IL  | Volkswagen AG | OTHER    |               45.09 |             55    |         71.31 |         41.18 |          47.52 |        62.48 |           72.88 |            nan    |             68.75 |         5.46 |             69.59 | short              |                2.48 |                 -3.79 |                -4.44 |
|    375 | CRWD     | CRWD          | US       |              187.76 |             55.33 |         54.77 |         61.9  |          55.9  |        38.52 |           36.81 |             43.91 |              1.91 |         7.63 |             69.68 | swing              |               -0.17 |                 -3.24 |                -2.76 |
|    382 | 0MHU.IL  | 0MHU.IL       | OTHER    |               21.46 |             54.88 |         51.04 |         49.43 |          58.73 |        60.92 |           61.93 |            nan    |             55.88 |         1.67 |             59.25 | long               |                1.1  |                 -2.77 |                -2.91 |
|    403 | NET      | NET           | US       |               85.46 |             54.28 |         43.43 |         60.32 |          62.67 |        48.23 |           55.79 |             83.56 |              1.91 |         7    |             69.68 | medium             |              nan    |                 -2.7  |                -1.77 |
|    510 | TENB     | TENB          | US       |                3.25 |             50.47 |         39.46 |         59.83 |          56.61 |        44.33 |           29.27 |             63.99 |             37.96 |         8.39 |             68.2  | swing              |                0.51 |                 -2.63 |                -2.31 |

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
- Excluded by hard/data filters: **290**
- Event watch (otherwise eligible): **2**
- Final eligible: **708**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 233
- price: 180
- market_cap: 127
- price_history: 14
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 10 | 9 |  | 5 | 2 | main,value,quality_value |
| CRGY | 8 |  | 1 |  | 2 | main,pullback |
| DDI | 50 | 1 |  | 1 | 1 | value,quality_value |
| GSL | 81 | 5 |  | 6 | 1 | value,quality_value |
| IRWD | 84 | 3 |  | 2 | 1 | value,quality_value |
| BION.SW | 100 | 4 | 78 | 4 | 1 | value,quality_value |
| 0P6O.IL | 379 | 7 |  | 7 | 1 | value,quality_value |
| BBWI | 502 | 6 | 255 | 9 | 1 | value,quality_value |
| STNE | 533 | 2 |  | 3 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| DELL | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| DSX | 4 |  |  |  | 1 | main |
| CMBT.BR | 5 |  |  |  | 1 | main |
| KIN.BR | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (FRO, DELL, VLO, DSX, CMBT.BR, KIN.BR, UGP, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 69.12 | 72.80 | 60.00 | 88.57 | 25.88 | 82.02 | 67.89 |
| 2 | SIE.DE | value+pullback | 67.12 | 55.46 | 85.45 | 61.96 | 63.33 | 67.45 | 56.82 |
| 3 | XNET | value+pullback | 66.35 | 59.67 | 68.82 | 62.22 | 81.77 | 68.69 | 47.09 |
| 4 | SAP.DE | value+pullback | 64.40 | 60.24 | 63.63 | 75.65 | 51.41 | 69.66 | 58.32 |
| 5 | AMCX | value+pullback | 63.89 | 65.95 | 58.76 | 47.49 | 80.30 | 71.33 | 66.27 |
| 6 | APA | value+pullback | 63.84 | 69.52 | 61.94 | 67.07 | 46.87 | 63.75 | 66.55 |
| 7 | LYFT | value+pullback | 63.31 | 58.48 | 86.75 | 60.09 | 56.65 | 46.99 | 56.46 |
| 8 | WKC | value+pullback | 63.20 | 56.19 | 65.88 | 60.22 | 75.76 | 66.31 | 65.54 |
| 9 | ALL-PH | value+pullback | 59.96 | 61.16 | 57.23 | 71.03 | 43.58 | 61.44 | 45.01 |
| 10 | BBWI | value+pullback | 59.57 | 77.31 | 42.56 | 72.48 | 35.94 | 56.36 | 50.84 |
| 11 | AIR.PA | value+pullback | 59.12 | 55.86 | 63.51 | 71.93 | 55.27 | 50.84 | 58.29 |
| 12 | MAGN | value+pullback | 59.12 | 64.74 | 59.96 | 54.08 | 38.28 | 63.84 | 46.45 |
| 13 | GASS | value+pullback | 58.95 | 60.59 | 68.49 | 44.98 | 51.19 | 58.91 | 51.70 |
| 14 | DDI | value | 58.50 | 67.99 | 42.92 | 93.81 | 61.72 | 89.28 | 70.96 |
| 15 | ORC | value+pullback | 58.46 | 63.46 | 50.48 | 73.37 | 38.00 | 59.97 | 46.17 |
| 16 | TV | value+pullback | 57.61 | 67.97 | 60.98 | 45.32 | 27.95 | 61.93 | 32.22 |
| 17 | MFA | value+pullback | 56.68 | 57.19 | 50.30 | 73.81 | 36.14 | 61.32 | 43.83 |
| 18 | IRWD | value | 56.58 | 70.75 | 52.01 | 85.33 | 65.75 | 79.90 | 68.98 |
| 19 | BHF | value+pullback | 56.18 | 72.27 | 34.85 | 53.16 | 46.83 | 65.64 | 43.68 |
| 20 | UNIT | value+pullback | 56.12 | 80.01 | 42.01 | 62.54 | 33.16 | 44.58 | 49.44 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 69.7 | 5 / 20 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 69.7 | 15 / 35 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=3, large_20_100b=1, mega_100b_plus=1
