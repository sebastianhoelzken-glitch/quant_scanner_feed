# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-08

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
- **OTHER:** 76.6/100
- **US:** 86.6/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               91.79 |             84.11 |         84.92 |         87.22 |          83.3  |        78.15 |           84.51 |             77.67 |             57.46 |         3.24 |             65.99 | swing              |                2.29 |                  0.66 |               nan    |
|      2 | FRO      | FRO                        | US       |                8.83 |             82.16 |         85.41 |         82.42 |          81.77 |        81.91 |           91.01 |             69.58 |             67.56 |         5.39 |             65.99 | short              |               -0.47 |                  0.22 |                 0.01 |
|      3 | DELL     | DELL                       | US       |              291.25 |             81.62 |         88.61 |         84.17 |          79.06 |        67.69 |           71.91 |             79.21 |             36.36 |         7.49 |             65.08 | short              |               -0.59 |                  0.5  |                 0.13 |
|      4 | DSX      | DSX                        | US       |                0.32 |             80.21 |         86.77 |         75.03 |          75.11 |        85.3  |           90.91 |             44.39 |             98.56 |         5.94 |             64.17 | short              |               -0.38 |                  1.29 |                 0.49 |
|      5 | UGP      | UGP                        | US       |                6.67 |             79.51 |         84.19 |         84.16 |          74.86 |        68.27 |           58.03 |             74.95 |             63.92 |         4.3  |             64.97 | short              |               -0.3  |                  2.61 |               nan    |
|      6 | CRGY     | CRGY                       | US       |                4.66 |             78.96 |         82.05 |         77.13 |          76.33 |        80.79 |           69.22 |             86.55 |             95.88 |         6    |             65.53 | short              |               -0.73 |                 -0.15 |               nan    |
|      7 | DINO     | DINO                       | US       |               16.12 |             78.68 |         84.54 |         83.37 |          73.99 |        65.67 |           47.81 |             71.72 |             69.89 |         4.32 |             65.99 | short              |               -0.58 |                  0.08 |                -0.28 |
|      8 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             78.5  |         85.47 |         82.51 |          74.48 |        65.5  |           88.25 |             63.72 |             19.51 |         3.68 |             69.68 | short              |               -0.53 |                 -0.01 |                -0.44 |
|      9 | DK       | DK                         | US       |                3.78 |             78.49 |         82.44 |         83.1  |          74.54 |        61.45 |           53.8  |             84.02 |             37.85 |         7.05 |             65.99 | swing              |               -0.54 |                  0.09 |               nan    |
|     10 | PARR     | Par Pacific Holdings, Inc. | US       |                3.5  |             78.12 |         81.39 |         78.35 |          77.9  |        75.62 |           80.98 |             62.1  |             65.21 |         6.98 |             83.85 | short              |                0.61 |                 -0.22 |                -0.29 |
|     11 | MU       | MU                         | US       |              987.36 |             78.02 |         74.64 |         71.14 |          81.4  |        83.1  |           95.94 |             52.47 |             74.91 |         8.18 |             65.99 | long               |               -0.16 |                  1.59 |                 1.62 |
|     12 | MT.AS    | MT.AS                      | EUROPE   |               50.93 |             77.24 |         77.55 |         77.4  |          77.08 |        73.95 |           69.07 |             77.14 |             67.82 |         4.89 |             69.68 | short              |               -0.65 |                nan    |               nan    |
|     13 | WT       | WT                         | US       |                3.24 |             77.03 |         80.84 |         80.61 |          73.45 |        63.79 |           70.83 |             73.36 |             29.78 |         5.48 |             65.99 | short              |               -0.6  |                  1.3  |               nan    |
|     14 | CIRSA.MC | CIRSA.MC                   | EUROPE   |                3.08 |             76.65 |         85.13 |         82.82 |          70.48 |        70.43 |           79.02 |             69.32 |             59.18 |         5.5  |             67.5  | short              |                1.57 |                nan    |               nan    |
|     15 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.78 |             76.37 |         87.07 |         78.79 |          73.94 |        68.88 |           81.59 |             76.6  |             33.13 |         5.15 |             83.7  | short              |              nan    |                  0.51 |                 0.31 |
|     16 | PR       | PR                         | US       |               16.83 |             76.07 |         80.87 |         75.58 |          75.09 |        76.55 |           75.86 |             72.83 |             74.27 |         4.06 |             64.62 | short              |               -0.63 |                 -0.09 |                -0.36 |
|     17 | ANF      | ANF                        | US       |                5.46 |             76.04 |         86.28 |         79.5  |          72.08 |        72.57 |           87.53 |             42.5  |             57.3  |         8.5  |             63.94 | short              |               -0.27 |                 -0.45 |               nan    |
|     18 | BAYN.DE  | BAYN.DE                    | EUROPE   |               47.85 |             76.01 |         57.06 |         74.4  |          79.85 |        77.63 |          nan    |             87.9  |             64.1  |         6.2  |             66.84 | medium             |                2.2  |                  1.13 |                 0.87 |
|     19 | ABN.AS   | ABN.AS                     | EUROPE   |               35.38 |             75.84 |         77.83 |         77.78 |          73.9  |        69.29 |           76.22 |             55.69 |             52.04 |         2.72 |             69.68 | short              |                0.23 |                  0.05 |                -0.48 |
|     20 | OKTA     | OKTA                       | US       |               25.65 |             75.75 |         84.7  |         80.24 |          71.26 |        57.44 |           64.32 |             69.4  |             16.87 |         7.55 |             64.97 | short              |               -0.46 |                 -0.5  |                -0.99 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                  | OTHER    |               25.94 |                  78.61 |                    76.04 |                 75.56 |              76.51 |                68.09 |                   31.91 |           74.53 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  67.99 |                    74.12 |                 76.95 |              71.38 |                89.45 |                   10.55 |           93.81 |             63.19 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.18 |                  73.25 |                    74.02 |                 75.74 |              74.21 |                86.62 |                   13.38 |           83.85 |             58.79 |       0.827 |         nan |       nan |      nan    |       -82.4  |          2.21 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            4 | VOW3.DE  | Volkswagen AG                    | EUROPE   |               40.61 |                  83.56 |                    73.99 |                 70.98 |              76.94 |                71.19 |                   28.81 |           67.03 |             39.61 |       0.347 |         nan |       nan |       13.97 |         3.52 |          7.77 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|            5 | STNE     | StoneCo Ltd.                     | OTHER    |                2    |                  77.6  |                    73.51 |                 73.19 |              72.36 |                70.03 |                   29.97 |           87.77 |             38.77 |       0.594 |         nan |       nan |        1.63 |         4.31 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  70.75 |                    72.57 |                 74.82 |              71.75 |                79.68 |                   20.32 |           85.33 |             64.68 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA     | NVIDIA Corporation               | US       |             4783.59 |                  59.98 |                    69.72 |                 71.58 |              64.7  |                76.79 |                   23.21 |           86.15 |             76.86 |       0.008 |         nan |       nan |       27.47 |        14.84 |         29.16 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|            8 | AVGO     | Broadcom Inc.                    | US       |             1464.28 |                  60.59 |                    69.13 |                 70.1  |              63.42 |                79.88 |                   20.12 |           90.87 |             54.22 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.65 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|            9 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.5  |                  68.38 |                    69.12 |                 70.71 |              67.9  |                69.21 |                   30.79 |           80.98 |             62.1  |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | BBWI     | Bath & Body Works, Inc.          | US       |                3.38 |                  77.31 |                    69    |                 65.85 |              68.72 |                55.4  |                   44.6  |           72.48 |             30.9  |       0.194 |         nan |       nan |        5.99 |         6.96 |          5.12 |        0.8  |                 nan |              nan |                  11 |                  0.58 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft           | OTHER    |                3.31 |                  69.72 |                    68.03 |                 66.98 |              69.58 |                69.02 |                   30.98 |           60.81 |            nan    |       0.224 |         nan |       nan |        1.54 |       nan    |          3.08 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | NLY      | NLY                              | US       |               14.78 |                  68.44 |                    67.96 |                 68.14 |              64.9  |                70.32 |                   29.68 |           89.39 |             29.66 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                              | US       |                8.83 |                  58.38 |                    67.66 |                 71.02 |              62.86 |                77.02 |                   22.98 |           91.01 |             69.58 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | WB       | Weibo Corporation                | OTHER    |                1.42 |                  78.6  |                    67.61 |                 63.46 |              70.12 |                63.37 |                   36.63 |           61.62 |             21.2  |     nan     |         nan |       nan |        1.84 |         5.23 |          5.55 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           13 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.44 |                  68.77 |                    67.39 |                 68.25 |              66.01 |                71.78 |                   28.22 |           84.67 |             35.8  |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|           14 | IHS      | IHS Holding Limited              | OTHER    |                2.46 |                  72.23 |                    67.34 |                 67.35 |              70.69 |                60.64 |                   39.36 |           56.4  |             77.67 |      -0.113 |         nan |       nan |        7.54 |        15.4  |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              232.15 |                  65.43 |                    67.28 |                 68.25 |              63.39 |                71.79 |                   28.21 |           92    |             33.57 |     nan     |         nan |       nan |      nan    |        10.17 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                              | US       |               45.46 |                  63.68 |                    66.75 |                 67.89 |              64.98 |                70.03 |                   29.97 |           75.74 |             65.28 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                           | EUROPE   |              171.04 |                  64.56 |                    66.63 |                 67.05 |              66.72 |                70.72 |                   29.28 |           64.55 |             75.02 |     nan     |         nan |       nan |      nan    |         9.03 |         11.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | UNIT     | Uniti Group Inc.                 | US       |                2.12 |                  80.01 |                    66.59 |                 63.48 |              68.91 |                44.71 |                   55.29 |           63.56 |             32.53 |      -0.105 |         nan |       nan |        9.13 |       -14.32 |          2.65 |        0.17 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  67.99 |                    74.12 |                 76.95 |              71.38 |                89.45 |                   10.55 |           93.81 |             63.19 |       0.153 |         nan |       nan |        0.78 |         5.26 |          5.09 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.18 |                  73.25 |                    74.02 |                 75.74 |              74.21 |                86.62 |                   13.38 |           83.85 |             58.79 |       0.827 |         nan |       nan |      nan    |       -82.4  |          2.21 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            1 | 0QXR.IL  | Stellantis N.V.                  | OTHER    |               25.94 |                  78.61 |                    76.04 |                 75.56 |              76.51 |                68.09 |                   31.91 |           74.53 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.61 |                  70.75 |                    72.57 |                 74.82 |              71.75 |                79.68 |                   20.32 |           85.33 |             64.68 |       0.173 |         nan |       nan |        4.29 |         2.84 |          5.39 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | STNE     | StoneCo Ltd.                     | OTHER    |                2    |                  77.6  |                    73.51 |                 73.19 |              72.36 |                70.03 |                   29.97 |           87.77 |             38.77 |       0.594 |         nan |       nan |        1.63 |         4.31 |          3.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | NVDA     | NVIDIA Corporation               | US       |             4783.59 |                  59.98 |                    69.72 |                 71.58 |              64.7  |                76.79 |                   23.21 |           86.15 |             76.86 |       0.008 |         nan |       nan |       27.47 |        14.84 |         29.16 |        0.59 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                              | US       |                8.83 |                  58.38 |                    67.66 |                 71.02 |              62.86 |                77.02 |                   22.98 |           91.01 |             69.58 |     nan     |         nan |       nan |      nan    |        10.29 |          6.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | VOW3.DE  | Volkswagen AG                    | EUROPE   |               40.61 |                  83.56 |                    73.99 |                 70.98 |              76.94 |                71.19 |                   28.81 |           67.03 |             39.61 |       0.347 |         nan |       nan |       13.97 |         3.52 |          7.77 |        0.63 |                 nan |              nan |                  12 |                  0.63 |
|            9 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.5  |                  68.38 |                    69.12 |                 70.71 |              67.9  |                69.21 |                   30.79 |           80.98 |             62.1  |       0.02  |         nan |       nan |        3.95 |         6.88 |          4.77 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | AVGO     | Broadcom Inc.                    | US       |             1464.28 |                  60.59 |                    69.13 |                 70.1  |              63.42 |                79.88 |                   20.12 |           90.87 |             54.22 |       0.018 |         nan |       nan |       33.45 |        18.47 |         45.65 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | KDP      | KDP                              | US       |               38.14 |                  56.1  |                    66.26 |                 69.61 |              61.7  |                79.66 |                   20.34 |           87.84 |             69.7  |     nan     |         nan |       nan |      nan    |        12.86 |         32.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GNK      | GNK                              | US       |                1.04 |                  56.63 |                    65.88 |                 69.01 |              61.64 |                76.98 |                   23.02 |           85.84 |             70.14 |     nan     |         nan |       nan |      nan    |        15.21 |         30.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.44 |                  68.77 |                    67.39 |                 68.25 |              66.01 |                71.78 |                   28.22 |           84.67 |             35.8  |       0.077 |         nan |       nan |        3.98 |         5.24 |          4.53 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              232.15 |                  65.43 |                    67.28 |                 68.25 |              63.39 |                71.79 |                   28.21 |           92    |             33.57 |     nan     |         nan |       nan |      nan    |        10.17 |         10.43 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                              | US       |               14.78 |                  68.44 |                    67.96 |                 68.14 |              64.9  |                70.32 |                   29.68 |           89.39 |             29.66 |     nan     |         nan |       nan |      nan    |         7.33 |          5.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                           | EUROPE   |                1.74 |                  52.31 |                    64.05 |                 68.01 |              57.64 |                80.92 |                   19.08 |           96.91 |             54.05 |     nan     |         nan |       nan |      nan    |        10.73 |         11.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                              | US       |               45.46 |                  63.68 |                    66.75 |                 67.89 |              64.98 |                70.03 |                   29.97 |           75.74 |             65.28 |     nan     |         nan |       nan |      nan    |         8.86 |         10.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                              | US       |               91.79 |                  50.55 |                    63.52 |                 67.62 |              58.68 |                80.64 |                   19.36 |           84.51 |             77.67 |     nan     |         nan |       nan |      nan    |        11.88 |         15.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | IHS      | IHS Holding Limited              | OTHER    |                2.46 |                  72.23 |                    67.34 |                 67.35 |              70.69 |                60.64 |                   39.36 |           56.4  |             77.67 |      -0.113 |         nan |       nan |        7.54 |        15.4  |          5.2  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               23.87 |                  53.56 |                    63.79 |                 67.24 |              57.87 |                79.17 |                   20.83 |           94.75 |             50.51 |     nan     |         nan |       nan |      nan    |        11.57 |         11.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name          | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CRGY     | CRGY          | US       |                4.66 |                     0.04 |     0.02 |      0.2  |                  53.52 |                        75.88 |         82.05 |         77.13 |          76.33 |        80.79 |           69.22 |             86.55 |         6    |
|               2 | ARGX.BR  | ARGX.BR       | EUROPE   |               54.07 |                     0.05 |    -0.01 |      0.13 |                  68.03 |                        74.9  |         73.72 |         66.94 |          65.35 |        59.78 |           91.42 |             63.7  |         6.01 |
|               3 | DK       | DK            | US       |                3.78 |                     0.03 |    -0.01 |      0.23 |                  59.01 |                        73.77 |         82.44 |         83.1  |          74.54 |        61.45 |           53.8  |             84.02 |         7.05 |
|               4 | PLTR     | PLTR          | US       |              360.26 |                     0.06 |    -0.06 |      0.01 |                  83.58 |                        73.69 |         58.94 |         65.77 |          61.45 |        58.77 |           90.11 |             68.27 |         8.55 |
|               5 | APA      | APA           | US       |               12.89 |                     0.04 |     0.01 |      0.14 |                  61.94 |                        71.91 |         75.73 |         71.61 |          73.87 |        74.65 |           72.92 |             67.83 |         5.6  |
|               6 | DAR      | DAR           | US       |                8.85 |                     0.05 |     0.01 |      0.1  |                  61.37 |                        71.88 |         72.81 |         62.83 |          71.98 |        77.81 |           91.54 |             53.06 |         4.2  |
|               7 | AVAH     | AVAH          | US       |                2.55 |                     0.02 |     0.02 |      0.43 |                  41.84 |                        71.83 |         85.32 |         76.32 |          68.88 |        68.47 |           92.94 |             28.68 |         7.44 |
|               8 | CRM      | CRM           | US       |              183.47 |                     0.02 |     0.01 |      0.34 |                  45.28 |                        71.73 |         83.38 |         77.42 |          61.36 |        57.55 |           61.25 |             73.36 |         7.67 |
|               9 | BAX      | BAX           | US       |               11.48 |                     0.07 |    -0.01 |     -0.06 |                  65    |                        71.43 |         50.61 |         72.4  |          72.66 |        70.31 |           75.81 |             68.77 |         6.04 |
|              10 | RAND.AS  | RAND.AS       | EUROPE   |                6.66 |                     0.06 |    -0.06 |     -0.04 |                  84.96 |                        71.04 |         46.6  |         70.34 |          67.46 |        62.89 |           77.97 |             50.2  |         6.69 |
|              11 | EQNR     | EQNR          | US       |               85.91 |                     0.05 |     0.02 |      0.09 |                  61.8  |                        70.88 |         71.45 |         70.38 |          73.32 |        72.24 |           72.28 |             76.18 |         5.27 |
|              12 | BION.SW  | BB Biotech AG | EUROPE   |                3.18 |                     0.05 |    -0.03 |      0.02 |                  73.99 |                        70.84 |         57.64 |         68.31 |          73.71 |        78.84 |           83.85 |             58.79 |         2.3  |
|              13 | TALO     | TALO          | US       |                2.42 |                     0.05 |     0.01 |      0.17 |                  65.55 |                        70.8  |         74.87 |         68.52 |          69.6  |        70.56 |           67.47 |             66.93 |         5.52 |
|              14 | TECK     | TECK          | US       |               29.15 |                     0.04 |    -0    |      0.04 |                  59.58 |                        70.78 |         69.23 |         67.77 |          73.04 |        71.21 |           86.27 |             66.48 |         5.62 |
|              15 | CMG      | CMG           | US       |               40.22 |                     0.04 |    -0.03 |      0.13 |                  70.06 |                        70.04 |         67.91 |         60.72 |          54.99 |        57.23 |           88.94 |             51.92 |         6.47 |
|              16 | WDAY     | WDAY          | US       |               40.58 |                     0.05 |    -0.04 |      0.09 |                  82.81 |                        69.59 |         67.42 |         68.3  |          60.08 |        60    |           73.27 |             55.77 |         8.56 |
|              17 | AG       | AG            | US       |                8.89 |                     0.04 |     0.01 |      0.14 |                  55.76 |                        69.58 |         72.52 |         57.15 |          61.38 |        67.24 |           88.59 |             48.29 |         8.38 |
|              18 | ABNB     | ABNB          | US       |               93.69 |                     0.04 |    -0.04 |      0.02 |                  76.13 |                        69.53 |         64.52 |         70.81 |          64.69 |        55.35 |           69.15 |             59.14 |         4.8  |
|              19 | BCRX     | BCRX          | US       |                2.19 |                     0.06 |     0.01 |      0.06 |                  63.9  |                        69.51 |         65.64 |         65.76 |          69.57 |        75.72 |           84.67 |             67.42 |         5.54 |
|              20 | CDE      | CDE           | US       |               18.78 |                     0.04 |     0.01 |      0.22 |                  62.3  |                        69.5  |         74.85 |         60.36 |          60.31 |        73.13 |           86.04 |             36.81 |         8.3  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | ORCL     | Oracle Corporation      | US       |              393.32 |             43.59 |         62.94 |         41.99 |          42.08 |        45.1  |           45.19 |             59.53 |             45.07 |          8.5 |             88.41 | short              |                0.26 |                  0.11 |                 0.03 |
|    nan | SHOE     | Shoe Station Group Inc. | US       |                0.33 |             35.17 |         35.78 |         26.84 |          34.57 |        45.36 |           41.77 |             40.1  |             68.02 |          8.5 |             82.96 | long               |               -0.01 |                  1.1  |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    123 | HAFN     | HAFN    | US       |                3.96 |             66.81 |         80.93 |         68.64 |          62.71 |        64.97 |           70.81 |             35.78 |             60.22 |         5.21 |             65.99 | short              |               -0.29 |                  4.22 |               nan    |
|     62 | SNOW     | SNOW    | US       |              102.3  |             70.32 |         72.84 |         80.08 |          67.8  |        46.55 |           42.07 |             94.5  |              1.69 |         7.87 |             64.97 | swing              |               -0.26 |                  3.03 |                 3.09 |
|     49 | DOCU     | DOCU    | US       |               11    |             71.38 |         80.97 |         77.4  |          65.36 |        59.8  |           59.2  |             81.38 |             49.66 |         7.67 |             63.94 | short              |               -0.66 |                  3.03 |               nan    |
|    444 | 0P6O.IL  | 0P6O.IL | OTHER    |               44.61 |             52.72 |         69.5  |         38.17 |          40.34 |        65.1  |          nan    |            nan    |             86.96 |         4.93 |             56.75 | short              |                0.14 |                  2.95 |                 2.2  |
|      5 | UGP      | UGP     | US       |                6.67 |             79.51 |         84.19 |         84.16 |          74.86 |        68.27 |           58.03 |             74.95 |             63.92 |         4.3  |             64.97 | short              |               -0.3  |                  2.61 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    657 | DSY.PA   | DSY.PA   | EUROPE   |               27.02 |             38.85 |         30.69 |         39.5  |          39.61 |        38.19 |           41.86 |             35.81 |             27.4  |         6.56 |             69.68 | medium             |               -6.8  |                 -2.92 |                -2.42 |
|    336 | GL9.IR   | GL9.IR   | EUROPE   |                5.21 |             56.4  |         34.34 |         47.75 |          65.04 |        65.46 |           96.91 |             38.53 |             25.59 |         2.19 |             69.68 | long               |               -9.15 |                 -2.25 |                -1.87 |
|    159 | SRAIL.SW | SRAIL.SW | EUROPE   |                3.1  |             64.84 |         75.72 |         67.96 |          61.72 |        57.23 |           74.32 |             30.6  |             28.97 |         5.29 |             69.68 | short              |               -0.24 |                 -2.13 |               nan    |
|    604 | OMDA     | OMDA     | US       |                1.2  |             44.06 |         40.88 |         54.79 |          47.23 |        37.35 |           44.08 |             28.63 |             14.55 |         8.57 |             65.99 | swing              |                0.01 |                 -1.92 |               nan    |
|    276 | BOX      | BOX      | US       |                4.15 |             58.97 |         71.18 |         65.47 |          52.48 |        46.14 |           55.68 |             35.51 |             23.83 |         5.67 |             64.51 | short              |               -0.15 |                 -1.88 |                -1.94 |

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
- Excluded by hard/data filters: **296**
- Event watch (otherwise eligible): **2**
- Final eligible: **702**
- Eligible change vs previous stored run: **-10**

Top exclusion categories:
- liquidity: 240
- price: 191
- market_cap: 158
- price_history: 15
- data_confidence: 13
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 10 | 9 |  | 8 | 2 | main,value,quality_value |
| CRGY | 6 |  | 1 |  | 2 | main,pullback |
| DK | 9 |  | 3 |  | 2 | main,pullback |
| DDI | 47 | 2 |  | 1 | 1 | value,quality_value |
| BION.SW | 54 | 3 | 12 | 2 | 1 | value,quality_value |
| NVDA | 60 | 7 |  | 6 | 1 | value,quality_value |
| IRWD | 85 | 6 |  | 4 | 1 | value,quality_value |
| 0QXR.IL | 440 | 1 |  | 3 | 1 | value,quality_value |
| VOW3.DE | 454 | 4 |  | 7 | 1 | value,quality_value |
| AVGO | 493 | 8 |  | 9 | 1 | value,quality_value |
| STNE | 522 | 5 |  | 5 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| DELL | 3 |  |  |  | 1 | main |
| DSX | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (VLO, FRO, DELL, DSX, UGP, DINO, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 76.25 | 73.25 | 73.99 | 83.85 | 58.79 | 86.62 | 71.01 |
| 2 | XNET | value+pullback | 66.14 | 59.72 | 68.82 | 62.22 | 80.29 | 68.27 | 46.42 |
| 3 | SAP.DE | value+pullback | 64.93 | 58.38 | 76.73 | 71.74 | 50.90 | 61.90 | 54.36 |
| 4 | WKC | value+pullback | 64.25 | 56.74 | 65.88 | 62.39 | 75.40 | 69.28 | 66.37 |
| 5 | AMCX | value+pullback | 63.85 | 65.95 | 58.76 | 47.49 | 80.07 | 71.22 | 66.20 |
| 6 | MC.PA | value+pullback | 62.76 | 61.91 | 56.97 | 83.70 | 43.47 | 65.21 | 37.82 |
| 7 | LYFT | value+pullback | 62.68 | 61.66 | 86.75 | 54.11 | 56.02 | 43.87 | 56.35 |
| 8 | ALL-PH | value+pullback | 59.75 | 61.06 | 57.23 | 71.12 | 41.89 | 61.36 | 44.55 |
| 9 | BBWI | value+pullback | 58.87 | 77.31 | 42.56 | 72.48 | 30.90 | 55.40 | 49.88 |
| 10 | DDI | value | 58.68 | 67.99 | 42.92 | 93.81 | 63.19 | 89.45 | 71.51 |
| 11 | MSFT | value+pullback | 58.65 | 61.86 | 61.31 | 57.73 | 59.99 | 50.51 | 56.80 |
| 12 | GASS | value+pullback | 57.70 | 61.70 | 68.49 | 39.78 | 49.96 | 55.51 | 49.55 |
| 13 | TV | value+pullback | 57.60 | 68.33 | 60.98 | 45.32 | 27.17 | 61.70 | 31.87 |
| 14 | ORC | value+pullback | 57.42 | 60.76 | 50.48 | 72.88 | 37.49 | 59.43 | 46.29 |
| 15 | 0QC9.L | value+pullback | 57.01 | 55.42 | 62.73 | 59.42 | 51.65 | 53.11 | 40.47 |
| 16 | LKFT.AS | value+pullback | 56.69 | 64.10 | 60.33 | 53.11 | 22.05 | 61.02 | 44.84 |
| 17 | IRWD | value | 56.43 | 70.75 | 52.01 | 85.33 | 64.68 | 79.68 | 69.08 |
| 18 | MAGN | value+pullback | 56.41 | 58.36 | 59.96 | 51.94 | 37.71 | 61.77 | 45.72 |
| 19 | AF.PA | value+pullback | 56.25 | 62.62 | 67.37 | 46.65 | 58.22 | 38.99 | 48.12 |
| 20 | UNIT | value+pullback | 56.23 | 80.01 | 42.01 | 63.56 | 32.53 | 44.71 | 49.62 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 66.0 | 3 / 7 |
| Top 25 | 24/25 | 24/25 | 25/25 | 23/25 | 0/25 | 66.0 | 6 / 19 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 66.0 | 14 / 36 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=3, large_20_100b=1, mega_100b_plus=1
