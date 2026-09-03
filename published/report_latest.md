# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-03

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

- **EUROPE:** 85.8/100
- **OTHER:** 72.3/100
- **US:** 83.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PSX      | PSX                        | US       |               88.12 |             81.85 |         84.9  |         84.16 |          79.53 |        74.83 |           79.39 |             74.02 |             58.87 |         3.57 |             69.68 | short              |                4.99 |                nan    |               nan    |
|      2 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.65 |             81.3  |         84.18 |         79.08 |          80.94 |        81.66 |           96.24 |             62.76 |             63.8  |         4.04 |             69.68 | short              |               -0.78 |                  0.1  |                -0.41 |
|      3 | FRO      | FRO                        | US       |                8.72 |             81.05 |         84.27 |         81.01 |          80.54 |        81.09 |           91.53 |             69.23 |             65.44 |         5.48 |             69.68 | short              |               -0.15 |                 -0.04 |                -0.37 |
|      4 | VLO      | VLO                        | US       |               90.9  |             80.81 |         81.84 |         82.31 |          79.77 |        76.06 |           85.39 |             64.57 |             57.22 |         3.31 |             67.5  | swing              |              nan    |                nan    |               nan    |
|      5 | CRGY     | CRGY                       | US       |                4.07 |             79.71 |         85.87 |         79.08 |          76.52 |        80.34 |           71.33 |             84.04 |             96    |         6.21 |             69.23 | short              |                3.15 |                  1.42 |               nan    |
|      6 | NAT      | NAT                        | US       |                1.29 |             79.43 |         82.07 |         80.48 |          78.39 |        75.06 |           87.09 |             73.29 |             46.73 |         4.93 |             69.68 | short              |                1.86 |                 -0.05 |               nan    |
|      7 | PARR     | Par Pacific Holdings, Inc. | US       |                3.46 |             79.22 |         80.57 |         78.41 |          79.77 |        78.66 |           83.23 |             62.25 |             70.5  |         7.01 |             85.07 | short              |                3.44 |                  0.28 |                 0.08 |
|      8 | DELL     | DELL                       | US       |              274.27 |             79.11 |         79.81 |         78.41 |          79.95 |        64.03 |          nan    |             82.64 |             37.63 |         7.57 |             65.93 | medium             |              nan    |                  2.32 |                 2.54 |
|      9 | KIN.BR   | KIN.BR                     | EUROPE   |                1.26 |             78.55 |         82.81 |         81.83 |          75.27 |        67.01 |           90.28 |             63.96 |             22.84 |         3.99 |             69.68 | short              |               -0.81 |                  1.54 |                 1.2  |
|     10 | ANF      | ANF                        | US       |                5.23 |             78.31 |         79.45 |         80.06 |          76.81 |        77.17 |           88.41 |             68.18 |             62.33 |         8.49 |             67.64 | swing              |               -0.36 |                  1.04 |               nan    |
|     11 | DINO     | DINO                       | US       |               16.26 |             78.29 |         83.49 |         82.67 |          73.9  |        65.71 |           49.41 |             72.46 |             69.29 |         4.47 |             69.68 | short              |                0.04 |                  1.3  |                 1.71 |
|     12 | OKTA     | OKTA                       | US       |               24.6  |             78.23 |         83.17 |         79.81 |          76.66 |        63.77 |           77.63 |             80.84 |             17.92 |         7.57 |             67.86 | short              |                1.26 |                 -0.28 |                -0.99 |
|     13 | DK       | DK                         | US       |                3.77 |             78.02 |         82.83 |         81.81 |          74.23 |        61.31 |           54.38 |             84.59 |             37.89 |         7.09 |             69.68 | short              |                4.68 |                  0.17 |                 0.14 |
|     14 | GTLB     | GTLB                       | US       |                7.13 |             76.59 |         91.19 |         86.57 |          66.62 |        43.76 |          nan    |             85.78 |             10.19 |         8.36 |             66.84 | short              |               14.41 |                  2.83 |                 2.41 |
|     15 | PR       | PR                         | US       |               17.21 |             76.51 |         83.53 |         76.39 |          76.05 |        76.63 |           78.19 |             74.6  |             72.39 |         4.35 |             68.32 | short              |               -0.57 |                  0.55 |                 0.27 |
|     16 | AVAH     | AVAH                       | US       |                2.48 |             76.4  |         81.66 |         79.73 |          73.07 |        71    |           93.48 |             51.13 |             42.02 |         7.45 |             68.66 | short              |               -0.65 |                 -0.13 |                 0.16 |
|     17 | EVK.DE   | EVK.DE                     | EUROPE   |                8.84 |             76.21 |         77.69 |         79.29 |          74.73 |        64.68 |          nan    |             84    |             48.97 |         3.19 |             66.84 | swing              |                5.16 |                  1.98 |               nan    |
|     18 | ABN.AS   | ABN.AS                     | EUROPE   |               34.49 |             75.59 |         76.12 |         77.1  |          75.07 |        70.36 |           77.89 |             60.88 |             52.15 |         2.89 |             69.68 | swing              |                0.4  |                  0.74 |                 0.89 |
|     19 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.15 |             75.51 |         82.01 |         78.77 |          72.26 |        64.57 |           76.16 |             74.93 |             32.41 |         5.32 |             69.68 | short              |                0.94 |                  0.26 |                -0.65 |
|     20 | PBF      | PBF                        | US       |                7.72 |             75.49 |         81.76 |         78.7  |          72.29 |        69.91 |           51.36 |             52.4  |             89.55 |         7.46 |             69.23 | short              |               -0.68 |                  1.54 |                 2.4  |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               61.66 |                  85.5  |                    73.22 |                 69.18 |              77.57 |                55.16 |                   44.84 |           53.23 |             60.83 |       0.035 |         nan |       nan |       16.05 |        13.59 |         19.19 |        1.22 |                 nan |              nan |                  12 |                  0.63 |
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.63 |                  70.88 |                    72.99 |                 75.37 |              72.08 |                80.56 |                   19.44 |           86.25 |             65.51 |       0.167 |         nan |       nan |        4.39 |         2.94 |          5.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              221.16 |                  63.39 |                    72.13 |                 75.03 |              67.93 |                84.05 |                   15.95 |           92.64 |             71.6  |     nan     |         nan |       nan |      nan    |        10.06 |         10.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  79.9  |                    71.25 |                 69.35 |              74.22 |                73.27 |                   26.73 |           68.57 |             35.07 |       0.08  |         nan |       nan |        3.83 |         5.09 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            4 | BBWI      | Bath & Body Works, Inc.              | US       |                3.22 |                  80    |                    71.08 |                 67.84 |              71.31 |                57.21 |                   42.79 |           72.54 |             34.16 |       0.205 |         nan |       nan |        5.86 |         6.61 |          4.89 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            5 | STNE      | StoneCo Ltd.                         | OTHER    |                2.06 |                  73.2  |                    70.28 |                 70.02 |              68.62 |                68.83 |                   31.17 |           85.87 |             35.28 |       0.575 |         nan |       nan |        1.62 |         4.47 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA      | NVIDIA Corporation                   | US       |             4673.2  |                  59.98 |                    69.96 |                 71.99 |              64.4  |                77.02 |                   22.98 |           89.7  |             73.48 |       0.008 |         nan |       nan |       25.92 |        14.57 |         28.37 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            7 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.46 |                  69.43 |                    69.89 |                 71.61 |              68.48 |                68.12 |                   31.88 |           83.23 |             62.25 |       0.02  |         nan |       nan |        3.9  |         6.78 |          4.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | IHS       | IHS Holding Limited                  | OTHER    |                2.46 |                  73.41 |                    68.6  |                 68.7  |              72.35 |                61.71 |                   38.29 |           55.32 |             83.89 |      -0.114 |         nan |       nan |        7.52 |        15.33 |          5.14 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.65 |                  58.76 |                    68.47 |                 71.93 |              63.01 |                80.11 |                   19.89 |           96.24 |             62.76 |     nan     |         nan |       nan |      nan    |         8.89 |          6.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.85 |                  63    |                    68.04 |                 69.65 |              64.64 |                77.92 |                   22.08 |           86.93 |             52.56 |     nan     |         nan |       nan |      nan    |         8.83 |          7.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  59.73 |                    67.91 |                 71.25 |              63.86 |                81.82 |                   18.18 |           91.64 |             61.23 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO       | FRO                                  | US       |                8.72 |                  58.45 |                    67.74 |                 71.12 |              62.87 |                76.99 |                   23.01 |           91.53 |             69.23 |     nan     |         nan |       nan |      nan    |        10.54 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                                  | US       |               14.76 |                  68.28 |                    67.69 |                 67.84 |              64.65 |                69.93 |                   30.07 |           89.09 |             29    |     nan     |         nan |       nan |      nan    |         7.3  |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.06 |                  79.06 |                    67.45 |                 64.71 |              72.67 |                49.19 |                   50.81 |           45.65 |             68.96 |       0.142 |         nan |       nan |        1.79 |         7.65 |          4.6  |        5.21 |                 nan |              nan |                  12 |                  0.63 |
|           11 | WB        | Weibo Corporation                    | OTHER    |                1.43 |                  78.6  |                    67.29 |                 62.98 |              70.02 |                62.83 |                   37.17 |           60.02 |             21.2  |     nan     |         nan |       nan |        1.86 |         5.27 |          5.64 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           12 | AVGO      | Broadcom Inc.                        | US       |             1506.76 |                  59.62 |                    67.1  |                 67.42 |              62.65 |                77.41 |                   22.59 |           81.17 |             57.9  |       0.016 |         nan |       nan |       42.59 |        18.76 |         61.31 |        0.42 |                 nan |              nan |                  12 |                  0.63 |
|           13 | UNIT      | Uniti Group Inc.                     | US       |                2.06 |                  80.26 |                    66.71 |                 63.59 |              68.97 |                44.59 |                   55.41 |           64.2  |             31.55 |      -0.108 |         nan |       nan |        9.08 |       -13.87 |          2.57 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | EC        | EC                                   | US       |               31.04 |                  64.18 |                    66.37 |                 66.93 |              66.46 |                69.1  |                   30.9  |           63.89 |             78.05 |     nan     |         nan |       nan |      nan    |        10.22 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | HMC       | Honda Motor Co., Ltd.                | OTHER    |               36.3  |                  60.39 |                    66.25 |                 69.67 |              65.14 |                73.53 |                   26.47 |           75.31 |             84.28 |       0.04  |         nan |       nan |        7.16 |         6.54 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | IRWD      | Ironwood Pharmaceuticals, Inc.   | US       |                0.63 |                  70.88 |                    72.99 |                 75.37 |              72.08 |                80.56 |                   19.44 |           86.25 |             65.51 |       0.167 |         nan |       nan |        4.39 |         2.94 |          5.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                         | EUROPE   |              221.16 |                  63.39 |                    72.13 |                 75.03 |              67.93 |                84.05 |                   15.95 |           92.64 |             71.6  |     nan     |         nan |       nan |      nan    |        10.06 |         10.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | NVDA      | NVIDIA Corporation               | US       |             4673.2  |                  59.98 |                    69.96 |                 71.99 |              64.4  |                77.02 |                   22.98 |           89.7  |             73.48 |       0.008 |         nan |       nan |       25.92 |        14.57 |         28.37 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                          | EUROPE   |                4.65 |                  58.76 |                    68.47 |                 71.93 |              63.01 |                80.11 |                   19.89 |           96.24 |             62.76 |     nan     |         nan |       nan |      nan    |         8.89 |          6.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR      | Par Pacific Holdings, Inc.       | US       |                3.46 |                  69.43 |                    69.89 |                 71.61 |              68.48 |                68.12 |                   31.88 |           83.23 |             62.25 |       0.02  |         nan |       nan |        3.9  |         6.78 |          4.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | DDI       | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  59.73 |                    67.91 |                 71.25 |              63.86 |                81.82 |                   18.18 |           91.64 |             61.23 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO       | FRO                              | US       |                8.72 |                  58.45 |                    67.74 |                 71.12 |              62.87 |                76.99 |                   23.01 |           91.53 |             69.23 |     nan     |         nan |       nan |      nan    |        10.54 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | STNE      | StoneCo Ltd.                     | OTHER    |                2.06 |                  73.2  |                    70.28 |                 70.02 |              68.62 |                68.83 |                   31.17 |           85.87 |             35.28 |       0.575 |         nan |       nan |        1.62 |         4.47 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | HMC       | Honda Motor Co., Ltd.            | OTHER    |               36.3  |                  60.39 |                    66.25 |                 69.67 |              65.14 |                73.53 |                   26.47 |           75.31 |             84.28 |       0.04  |         nan |       nan |        7.16 |         6.54 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|          nan | AGS.BR    | AGS.BR                           | EUROPE   |               15.85 |                  63    |                    68.04 |                 69.65 |              64.64 |                77.92 |                   22.08 |           86.93 |             52.56 |     nan     |         nan |       nan |      nan    |         8.83 |          7.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP       | KDP                              | US       |               38.25 |                  55.07 |                    65.84 |                 69.39 |              61.13 |                79.78 |                   20.22 |           87.87 |             71.13 |     nan     |         nan |       nan |      nan    |        12.86 |         32.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL       | Global Ship Lease, Inc.          | OTHER    |                1.4  |                  79.9  |                    71.25 |                 69.35 |              74.22 |                73.27 |                   26.73 |           68.57 |             35.07 |       0.08  |         nan |       nan |        3.83 |         5.09 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NAT       | NAT                              | US       |                1.29 |                  55.21 |                    65.61 |                 69.18 |              60.97 |                77.16 |                   22.84 |           87.09 |             73.29 |     nan     |         nan |       nan |      nan    |        15.54 |         11.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | VOLV-B.ST | AB Volvo (publ)                  | EUROPE   |               61.66 |                  85.5  |                    73.22 |                 69.18 |              77.57 |                55.16 |                   44.84 |           53.23 |             60.83 |       0.035 |         nan |       nan |       16.05 |        13.59 |         19.19 |        1.22 |                 nan |              nan |                  12 |                  0.63 |
|            8 | IHS       | IHS Holding Limited              | OTHER    |                2.46 |                  73.41 |                    68.6  |                 68.7  |              72.35 |                61.71 |                   38.29 |           55.32 |             83.89 |      -0.114 |         nan |       nan |        7.52 |        15.33 |          5.14 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | ASRNL.AS  | ASRNL.AS                         | EUROPE   |               14.75 |                  56.74 |                    65.88 |                 68.55 |              62.56 |                80.95 |                   19.05 |           80.69 |             71.35 |     nan     |         nan |       nan |      nan    |        11.37 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | TNK       | Teekay Tankers Ltd.              | OTHER    |                2.71 |                  58.08 |                    65.53 |                 68.3  |              63.99 |                80    |                   20    |           74.06 |             77.68 |       0.073 |         nan |       nan |        3.86 |         8.33 |          5.2  |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR   | BIRG.IR                          | EUROPE   |               18.34 |                  57.07 |                    65.3  |                 68.2  |              59.64 |                78.1  |                   21.9  |           96.26 |             44.88 |     nan     |         nan |       nan |      nan    |        10.65 |         14.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR    | A5G.IR                           | EUROPE   |               23.17 |                  54.35 |                    64.45 |                 67.89 |              58.47 |                79.61 |                   20.39 |           95.92 |             50.09 |     nan     |         nan |       nan |      nan    |        11.24 |         11.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY       | NLY                              | US       |               14.76 |                  68.28 |                    67.69 |                 67.84 |              64.65 |                69.93 |                   30.07 |           89.09 |             29    |     nan     |         nan |       nan |      nan    |         7.3  |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ANF      | ANF                                                 | US       |                5.23 |                     0.08 |    -0.08 |      0.25 |                  77.59 |                        79.58 |         79.45 |         80.06 |          76.81 |        77.17 |           88.41 |             68.18 |         8.49 |
|               2 | SRAIL.SW | SRAIL.SW                                            | EUROPE   |                3.15 |                     0.06 |    -0.01 |      0.19 |                  73.5  |                        78.5  |         82.01 |         78.77 |          72.26 |        64.57 |           76.16 |             74.93 |         5.32 |
|               3 | AVAH     | AVAH                                                | US       |                2.48 |                     0.04 |    -0.03 |      0.41 |                  73.55 |                        78.23 |         81.66 |         79.73 |          73.07 |        71    |           93.48 |             51.13 |         7.45 |
|               4 | WT       | WT                                                  | US       |                3.1  |                     0.05 |    -0.04 |      0.08 |                  80.94 |                        76.38 |         67.7  |         75.91 |          73.38 |        65    |           72.45 |             78.63 |         5.61 |
|               5 | RAND.AS  | RAND.AS                                             | EUROPE   |                6.77 |                     0.05 |    -0.03 |      0    |                  75.37 |                        76.27 |         58.7  |         77.13 |          71.88 |        65.76 |           79.28 |             70.3  |         6.75 |
|               6 | DK       | DK                                                  | US       |                3.77 |                     0.04 |     0.01 |      0.2  |                  58.34 |                        73.73 |         82.83 |         81.81 |          74.23 |        61.31 |           54.38 |             84.59 |         7.09 |
|               7 | KRX.IR   | KRX.IR                                              | EUROPE   |               18.1  |                     0.03 |    -0.02 |      0.2  |                  63.27 |                        73.59 |         76.18 |         68.16 |          65.49 |        64.29 |           97.64 |             43.25 |         5.29 |
|               8 | GL9.IR   | GL9.IR                                              | EUROPE   |                5.42 |                     0.06 |    -0.02 |      0.01 |                  73.21 |                        73.55 |         54.25 |         63.95 |          75.55 |        71.39 |           97.17 |             74.35 |         2.29 |
|               9 | VWS.CO   | VWS.CO                                              | EUROPE   |               27.6  |                     0.03 |     0.01 |      0.22 |                  50.28 |                        73.35 |         81.76 |         68.4  |          66.03 |        62.54 |           87.52 |             49.49 |         5.75 |
|              10 | CCC      | CCC                                                 | US       |                3.65 |                     0.06 |    -0.02 |      0.11 |                  75.46 |                        72.86 |         68.01 |         69.81 |          64.45 |        68.37 |           86.71 |             61.94 |         8.01 |
|              11 | GGN      | GAMCO Global Gold, Natural Resources & Income Trust | US       |                0.75 |                     0.02 |    -0.01 |      0.1  |                  52.34 |                        71.77 |         73.45 |         62.88 |          59.68 |        59.43 |           75.04 |             81.21 |         2.23 |
|              12 | BAX      | BAX                                                 | US       |               11.46 |                     0.07 |    -0.03 |     -0.06 |                  67.45 |                        71.62 |         49.07 |         71.83 |          71.96 |        70.05 |           75.97 |             69.29 |         6.21 |
|              13 | WKC      | World Kinect Corporation                            | US       |                1.55 |                     0.06 |    -0.02 |     -0.09 |                  77.09 |                        71.3  |         45.67 |         69.45 |          74.56 |        69.34 |           67.7  |             76.46 |         4.95 |
|              14 | ABNB     | ABNB                                                | US       |               94.63 |                     0.04 |    -0.03 |      0.2  |                  67.77 |                        71.1  |         75.59 |         72.72 |          63.91 |        55.12 |           71.12 |             59.47 |         4.91 |
|              15 | AMC      | AMC                                                 | US       |                2.03 |                     0.02 |     0.01 |     -0.01 |                  47.19 |                        70.96 |         60.44 |         75.2  |          73.98 |        74.87 |           85.2  |             61.6  |         9.61 |
|              16 | BHVN     | BHVN                                                | US       |                2.04 |                     0.07 |    -0.07 |      0.15 |                  80.54 |                        70.93 |         69.92 |         72.99 |          59.09 |        43.83 |           50.75 |             81.34 |         8.88 |
|              17 | A        | A                                                   | US       |               36.81 |                     0.05 |    -0.02 |      0.07 |                  73.35 |                        69.77 |         67.63 |         63.81 |          61.42 |        56.5  |           72.63 |             69.48 |         4.43 |
|              18 | METSO.HE | METSO.HE                                            | EUROPE   |               14.32 |                     0.06 |    -0.05 |      0.03 |                  82.75 |                        69.74 |         63.02 |         56.9  |          60.48 |        58.24 |           78.36 |             67.62 |         4.82 |
|              19 | ITRG     | ITRG                                                | US       |                0.49 |                     0.05 |    -0.04 |      0.17 |                  79.29 |                        69.45 |         67.26 |         57.37 |          58.01 |        68.76 |           58.53 |             81.48 |         8.28 |
|              20 | HQH      | Abrdn Healthcare Investors                          | US       |                1.12 |                     0.05 |    -0.03 |      0.03 |                  77.21 |                        69.02 |         60.71 |         68.99 |          63.79 |        50.75 |           53.82 |             81.21 |         2.3  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.12 |             57.83 |         61.47 |         46.42 |          54.2  |        63.57 |           82.62 |             44.04 |             53.31 |         8.5  |             75.81 | long               |                4.7  |                  2.38 |                 1.94 |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.7  |             44.23 |         35.41 |         39.64 |          48.81 |        62.16 |           60.12 |             55.35 |             92.62 |         8.5  |             82.14 | long               |                0.04 |                 -0.48 |                -0.4  |
|    nan | ORCL     | Oracle Corporation                                   | US       |              362.06 |             43.03 |         46.61 |         38.03 |          41.18 |        44.89 |           47.06 |             61.65 |             43.09 |         7.94 |             89.54 | short              |                2.99 |                 -0.06 |                -0.15 |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.32 |             29.69 |         25.82 |         25.17 |          33.56 |        42.68 |           38.55 |             45.82 |             62.47 |         7.01 |             84.21 | long               |               -0.49 |                 -0.29 |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    310 | MAU.PA    | MAU.PA    | EUROPE   |                1.64 |             57.51 |         64.52 |         36.04 |          50.51 |        64.8  |           74.54 |             12    |             71.1  |         5.31 |             69.68 | long               |               -2.32 |                  3.01 |                 2.85 |
|     14 | GTLB      | GTLB      | US       |                7.13 |             76.59 |         91.19 |         86.57 |          66.62 |        43.76 |          nan    |             85.78 |             10.19 |         8.36 |             66.84 | short              |               14.41 |                  2.83 |                 2.41 |
|     86 | DEMANT.CO | DEMANT.CO | EUROPE   |                8.31 |             68.05 |         74.41 |         70.25 |          65.86 |        56.49 |           75.51 |             63.29 |             14.73 |         3.7  |             69.68 | short              |                4.38 |                  2.66 |                 2.74 |
|    271 | EQX       | EQX       | US       |               12.72 |             58.97 |         66.74 |         53.73 |          53.48 |        64.2  |           51.46 |             62.35 |             86.99 |         8.19 |             67.16 | short              |              nan    |                  2.63 |               nan    |
|    444 | ALEC      | ALEC      | US       |                0.26 |             52.77 |         79.25 |         63.86 |          41.69 |        27.78 |            2.92 |             50.77 |            nan    |         9.5  |             64.91 | short              |              nan    |                  2.62 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    349 | FNKO     | FNKO    | US       |                0.29 |             56.12 |         54.75 |         57.81 |          57.49 |        47.95 |           29.53 |             64.41 |             42.53 |         7.66 |             68.66 | swing              |               -4.28 |                 -3.5  |                -2.7  |
|    580 | HAFN     | HAFN    | US       |                3.83 |             45.73 |         70.59 |         51.49 |          39.97 |        36.76 |            8.46 |             20    |             61.68 |         5.43 |             65.68 | short              |              nan    |                 -3.1  |               nan    |
|    227 | BION.SW  | BION.SW | EUROPE   |                3.27 |             60.47 |         66.6  |         63.29 |          57.66 |        56.26 |           47.49 |             25.9  |             63.86 |         2.05 |             63.59 | short              |              -15.65 |                 -2.78 |                -2.29 |
|    490 | TENB     | TENB    | US       |                3.26 |             50.46 |         46.07 |         56.29 |          54.85 |        42.21 |           27.52 |             63.51 |             36.37 |         8.35 |             68.2  | swing              |               -5.58 |                 -2.74 |                -1.86 |
|    598 | S        | S       | US       |                5.91 |             44.68 |         39.73 |         54.07 |          49.63 |        36.95 |           34.46 |             45.4  |             15    |         7.12 |             68.66 | swing              |               -7.25 |                 -2.57 |                -1.11 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
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
- Excluded by hard/data filters: **283**
- Event watch (otherwise eligible): **4**
- Final eligible: **713**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 226
- price: 181
- market_cap: 151
- price_history: 14
- data_confidence: 8
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 7 | 7 |  | 3 | 2 | main,value,quality_value |
| ANF | 10 |  | 1 |  | 2 | main,pullback |
| IRWD | 37 | 2 |  | 1 | 1 | value,quality_value |
| DDI | 50 | 9 |  | 4 | 1 | value,quality_value |
| NVDA | 84 | 6 |  | 2 | 1 | value,quality_value |
| GSL | 105 | 3 |  | 7 | 1 | value,quality_value |
| IHS | 217 | 8 |  | 9 | 1 | value,quality_value |
| VOLV-B.ST | 432 | 1 | 223 | 8 | 1 | value,quality_value |
| STNE | 515 | 5 |  | 5 | 1 | value,quality_value |
| PSX | 1 |  |  |  | 1 | main |
| CMBT.BR | 2 |  |  |  | 1 | main |
| FRO | 3 |  |  |  | 1 | main |
| VLO | 4 |  |  |  | 1 | main |
| CRGY | 5 |  |  |  | 1 | main |
| NAT | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (PSX, FRO, VLO, CRGY, NAT, DELL, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SRAIL.SW, RAND.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | VOLV-B.ST | value+pullback | 69.53 | 85.50 | 75.15 | 53.23 | 60.83 | 55.16 | 53.49 |
| 2 | WKC | value+pullback | 68.40 | 58.31 | 77.09 | 67.70 | 76.46 | 69.18 | 69.40 |
| 3 | SIE.DE | value+pullback | 66.21 | 57.00 | 85.08 | 55.40 | 62.83 | 66.22 | 54.48 |
| 4 | BBWI | value+pullback | 64.92 | 80.00 | 60.75 | 72.54 | 34.16 | 57.21 | 42.59 |
| 5 | UNIT | value+pullback | 64.40 | 80.26 | 74.45 | 64.20 | 31.55 | 44.59 | 45.98 |
| 6 | XNET | value+pullback | 63.24 | 59.86 | 62.21 | 56.69 | 81.21 | 65.55 | 43.71 |
| 7 | ETG | value+pullback | 62.98 | 55.15 | 51.96 | 67.14 | 81.21 | 76.24 | 59.80 |
| 8 | ALL-PH | value+pullback | 61.04 | 61.19 | 64.79 | 68.71 | 43.50 | 59.16 | 44.11 |
| 9 | TV | value+pullback | 61.03 | 67.97 | 75.93 | 43.04 | 29.34 | 61.32 | 34.59 |
| 10 | MFA | value+pullback | 60.79 | 56.91 | 63.62 | 77.90 | 35.30 | 63.00 | 44.86 |
| 11 | NOMD | value+pullback | 58.73 | 55.30 | 78.76 | 61.96 | 30.54 | 50.53 | 51.12 |
| 12 | MAGN | value+pullback | 58.54 | 64.74 | 58.31 | 54.08 | 37.15 | 63.59 | 47.13 |
| 13 | MSFT | value+pullback | 58.12 | 58.21 | 56.66 | 60.95 | 67.87 | 52.80 | 60.05 |
| 14 | GL9.IR | pullback | 57.87 | 42.28 | 73.21 | 97.17 | 74.35 | 87.77 | 67.67 |
| 15 | IRWD | value | 56.86 | 70.88 | 30.95 | 86.25 | 65.51 | 80.56 | 72.05 |
| 16 | ORC | value+pullback | 56.48 | 55.71 | 53.72 | 72.31 | 37.01 | 58.97 | 47.84 |
| 17 | LNC | value+pullback | 56.29 | 57.31 | 65.22 | 44.88 | 66.18 | 47.20 | 59.40 |
| 18 | MTRX | value+pullback | 56.27 | 75.35 | 43.75 | 42.26 | 57.95 | 52.95 | 36.47 |
| 19 | NVDA | value | 54.20 | 59.98 | 40.65 | 89.70 | 73.48 | 77.02 | 68.19 |
| 20 | DDI | value | 54.15 | 59.73 | 42.56 | 91.64 | 61.23 | 81.82 | 70.72 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 10/10 | 10/10 | 9/10 | 0/10 | 69.7 | 3 / 7 |
| Top 25 | 22/25 | 25/25 | 24/25 | 21/25 | 0/25 | 69.2 | 6 / 19 |
| Top 50 | 46/50 | 50/50 | 49/50 | 45/50 | 0/50 | 69.3 | 12 / 38 |

Top-10 market-cap mix: small_1_5b=5, mid_5_20b=2, large_20_100b=2, mega_100b_plus=1
