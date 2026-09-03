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

- **EUROPE:** 85.7/100
- **OTHER:** 72.3/100
- **US:** 83.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PSX      | PSX                        | US       |               88.12 |             81.74 |         84.88 |         84.12 |          79.35 |        74.44 |           78.93 |             74.22 |             58.01 |         3.57 |             69.68 | short              |                4.88 |                nan    |               nan    |
|      2 | FRO      | FRO                        | US       |                8.72 |             80.86 |         84.26 |         80.98 |          80.39 |        80.74 |           91.22 |             69.35 |             64.5  |         5.48 |             69.68 | short              |               -0.34 |                 -0.08 |                -0.4  |
|      3 | VLO      | VLO                        | US       |               90.9  |             80.67 |         81.8  |         82.22 |          79.55 |        75.64 |           84.9  |             64.6  |             56.4  |         3.31 |             67.5  | swing              |              nan    |                nan    |               nan    |
|      4 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.65 |             80.43 |         83.4  |         77.99 |          80.12 |        80.73 |           96.42 |             62.95 |             62.43 |         4.04 |             69.68 | short              |               -1.65 |                 -0.08 |                -0.54 |
|      5 | CRGY     | CRGY                       | US       |                4.07 |             79.46 |         85.87 |         79.08 |          76.31 |        79.84 |           70.54 |             84.37 |             95.07 |         6.21 |             69.23 | short              |                2.9  |                  1.37 |               nan    |
|      6 | NAT      | NAT                        | US       |                1.29 |             79.34 |         82.05 |         80.43 |          78.25 |        74.76 |           86.79 |             73.36 |             46.03 |         4.93 |             69.68 | short              |                1.76 |                 -0.07 |               nan    |
|      7 | PARR     | Par Pacific Holdings, Inc. | US       |                3.46 |             79.25 |         80.58 |         78.45 |          79.82 |        78.69 |           83.23 |             62.47 |             70.5  |         6.97 |             85.07 | short              |                3.48 |                  0.29 |                 0.09 |
|      8 | DELL     | DELL                       | US       |              274.27 |             79.25 |         79.92 |         78.59 |          80.1  |        63.99 |          nan    |             83.26 |             37.14 |         7.57 |             65.93 | medium             |              nan    |                  2.35 |                 2.56 |
|      9 | DINO     | DINO                       | US       |               16.26 |             78.21 |         83.49 |         82.67 |          73.76 |        65.33 |           48.99 |             72.71 |             68.36 |         4.47 |             69.68 | short              |               -0.04 |                  1.29 |                 1.69 |
|     10 | OKTA     | OKTA                       | US       |               24.6  |             78.18 |         83.17 |         79.82 |          76.54 |        63.5  |           77.05 |             81.11 |             17.61 |         7.57 |             67.86 | short              |                1.2  |                 -0.29 |                -1    |
|     11 | ANF      | ANF                        | US       |                5.23 |             78.12 |         79.44 |         80.01 |          76.64 |        76.8  |           88.03 |             68.3  |             61.44 |         8.49 |             67.64 | swing              |               -0.55 |                  1    |               nan    |
|     12 | DK       | DK                         | US       |                3.77 |             78    |         82.85 |         81.83 |          74.16 |        61.08 |           54.15 |             84.87 |             37.19 |         7.09 |             69.68 | short              |                4.66 |                  0.16 |                 0.14 |
|     13 | KIN.BR   | KIN.BR                     | EUROPE   |                1.26 |             77.77 |         82.06 |         80.82 |          74.72 |        66.58 |           91    |             64.25 |             22.57 |         3.99 |             69.68 | short              |               -1.59 |                  1.39 |                 1.08 |
|     14 | GTLB     | GTLB                       | US       |                7.13 |             76.65 |         91.22 |         86.63 |          66.68 |        43.75 |          nan    |             86.05 |             10.02 |         8.36 |             66.84 | short              |               14.48 |                  2.84 |                 2.42 |
|     15 | AVAH     | AVAH                       | US       |                2.48 |             76.45 |         81.71 |         79.82 |          73.09 |        70.88 |           93.39 |             51.61 |             41.44 |         7.45 |             68.66 | short              |               -0.59 |                 -0.12 |                 0.17 |
|     16 | PR       | PR                         | US       |               17.21 |             76.25 |         83.52 |         76.36 |          75.83 |        76.14 |           77.51 |             74.8  |             71.41 |         4.35 |             68.32 | short              |               -0.83 |                  0.5  |                 0.23 |
|     17 | PBF      | PBF                        | US       |                7.72 |             75.31 |         81.71 |         78.58 |          72.04 |        69.48 |           50.87 |             52.25 |             88.73 |         7.46 |             69.23 | short              |               -0.87 |                  1.51 |                 2.37 |
|     18 | EVK.DE   | EVK.DE                     | EUROPE   |                8.84 |             75.28 |         76.85 |         78.12 |          73.71 |        63.31 |          nan    |             84.33 |             48.23 |         3.19 |             66.84 | swing              |                4.22 |                  1.79 |               nan    |
|     19 | ABN.AS   | ABN.AS                     | EUROPE   |               34.49 |             74.98 |         75.4  |         76.11 |          74.56 |        69.92 |           79.07 |             61.21 |             51.14 |         2.89 |             69.68 | swing              |               -0.21 |                  0.62 |                 0.79 |
|     20 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.15 |             74.71 |         81.25 |         77.74 |          71.68 |        64.09 |           77.05 |             75.13 |             31.73 |         5.32 |             69.68 | short              |                0.14 |                  0.1  |                -0.77 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              221.16 |                  66.34 |                    73.99 |                 76.55 |              70.13 |                84.35 |                   15.65 |           93.12 |             71.79 |     nan     |         nan |       nan |      nan    |        10.06 |         10.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.63 |                  73.36 |                    73.9  |                 75.83 |              73.7  |                79.56 |                   20.44 |           84.18 |             65.58 |       0.167 |         nan |       nan |        4.39 |         2.94 |          5.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BBWI     | Bath & Body Works, Inc.              | US       |                3.22 |                  80    |                    71.13 |                 67.9  |              71.36 |                57.28 |                   42.72 |           72.54 |             34.53 |       0.205 |         nan |       nan |        5.86 |         6.61 |          4.89 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            3 | HMC      | Honda Motor Co., Ltd.                | OTHER    |               36.3  |                  67.29 |                    70.75 |                 74.02 |              69.97 |                72.77 |                   27.23 |           80.8  |             84.17 |       0.04  |         nan |       nan |        7.16 |         6.54 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            4 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  78.35 |                    70.43 |                 68.59 |              73.31 |                74.44 |                   25.56 |           67.65 |             35.01 |       0.08  |         nan |       nan |        3.83 |         5.09 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            5 | STNE     | StoneCo Ltd.                         | OTHER    |                2.06 |                  73.2  |                    70.32 |                 70.09 |              68.67 |                68.9  |                   31.1  |           85.87 |             35.66 |       0.575 |         nan |       nan |        1.62 |         4.47 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4673.2  |                  59.98 |                    70.21 |                 72.37 |              64.49 |                77.4  |                   22.6  |           90.87 |             73.68 |       0.008 |         nan |       nan |       25.92 |        14.57 |         28.37 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            7 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  69.43 |                    69.92 |                 71.65 |              68.51 |                68.2  |                   31.8  |           83.23 |             62.47 |       0.02  |         nan |       nan |        3.9  |         6.78 |          4.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  61.13 |                    68.92 |                 72.24 |              64.92 |                82.19 |                   17.81 |           92.93 |             61.16 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.85 |                  63    |                    68.29 |                 70    |              64.77 |                78.46 |                   21.54 |           87.77 |             52.91 |     nan     |         nan |       nan |      nan    |         8.83 |          7.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.65 |                  57.9  |                    68.05 |                 71.64 |              62.43 |                80.26 |                   19.74 |           96.42 |             62.95 |     nan     |         nan |       nan |      nan    |         8.89 |          6.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IHS      | IHS Holding Limited                  | OTHER    |                2.46 |                  72.91 |                    68.03 |                 68.06 |              71.85 |                60.88 |                   39.12 |           54.11 |             83.96 |      -0.114 |         nan |       nan |        7.52 |        15.33 |          5.14 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | WB       | Weibo Corporation                    | OTHER    |                1.43 |                  78.6  |                    67.8  |                 63.73 |              70.22 |                63.72 |                   36.28 |           62.28 |             21.55 |     nan     |         nan |       nan |        1.86 |         5.27 |          5.64 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|          nan | NLY      | NLY                                  | US       |               14.76 |                  68.39 |                    67.75 |                 67.88 |              64.74 |                69.92 |                   30.08 |           89.03 |             29.07 |     nan     |         nan |       nan |      nan    |         7.3  |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                8.72 |                  58.37 |                    67.64 |                 71.01 |              62.8  |                76.88 |                   23.12 |           91.22 |             69.35 |     nan     |         nan |       nan |      nan    |        10.54 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.06 |                  79.06 |                    67.42 |                 64.67 |              72.64 |                49.15 |                   50.85 |           45.65 |             68.74 |       0.142 |         nan |       nan |        1.79 |         7.65 |          4.6  |        5.21 |                 nan |              nan |                  12 |                  0.63 |
|           12 | AVGO     | Broadcom Inc.                        | US       |             1506.76 |                  59.62 |                    67.06 |                 67.35 |              62.65 |                77.35 |                   22.65 |           80.87 |             58.03 |       0.016 |         nan |       nan |       42.59 |        18.76 |         61.31 |        0.42 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NN.AS    | NN.AS                                | EUROPE   |               20.37 |                  62.49 |                    66.62 |                 67.61 |              65.56 |                75.5  |                   24.5  |           70.8  |             69.77 |     nan     |         nan |       nan |      nan    |         8.79 |         11.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | UNIT     | Uniti Group Inc.                     | US       |                2.06 |                  80.26 |                    66.6  |                 63.41 |              69    |                44.4  |                   55.6  |           63.21 |             32.19 |      -0.108 |         nan |       nan |        9.08 |       -13.87 |          2.57 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|          nan | EC       | EC                                   | US       |               31.04 |                  64.18 |                    66.27 |                 66.79 |              66.42 |                68.88 |                   31.12 |           63.41 |             78.13 |     nan     |         nan |       nan |      nan    |        10.22 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              221.16 |                  66.34 |                    73.99 |                 76.55 |              70.13 |                84.35 |                   15.65 |           93.12 |             71.79 |     nan     |         nan |       nan |      nan    |        10.06 |         10.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.63 |                  73.36 |                    73.9  |                 75.83 |              73.7  |                79.56 |                   20.44 |           84.18 |             65.58 |       0.167 |         nan |       nan |        4.39 |         2.94 |          5.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | HMC      | Honda Motor Co., Ltd.            | OTHER    |               36.3  |                  67.29 |                    70.75 |                 74.02 |              69.97 |                72.77 |                   27.23 |           80.8  |             84.17 |       0.04  |         nan |       nan |        7.16 |         6.54 |        nan    |        3.45 |                 nan |              nan |                  11 |                  0.58 |
|            6 | NVDA     | NVIDIA Corporation               | US       |             4673.2  |                  59.98 |                    70.21 |                 72.37 |              64.49 |                77.4  |                   22.6  |           90.87 |             73.68 |       0.008 |         nan |       nan |       25.92 |        14.57 |         28.37 |        0.56 |                 nan |              nan |                  12 |                  0.63 |
|            8 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.55 |                  61.13 |                    68.92 |                 72.24 |              64.92 |                82.19 |                   17.81 |           92.93 |             61.16 |       0.153 |         nan |       nan |        0.77 |         5.25 |          5.04 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.46 |                  69.43 |                    69.92 |                 71.65 |              68.51 |                68.2  |                   31.8  |           83.23 |             62.47 |       0.02  |         nan |       nan |        3.9  |         6.78 |          4.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.65 |                  57.9  |                    68.05 |                 71.64 |              62.43 |                80.26 |                   19.74 |           96.42 |             62.95 |     nan     |         nan |       nan |      nan    |         8.89 |          6.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                              | US       |                8.72 |                  58.37 |                    67.64 |                 71.01 |              62.8  |                76.88 |                   23.12 |           91.22 |             69.35 |     nan     |         nan |       nan |      nan    |        10.54 |          6.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | STNE     | StoneCo Ltd.                     | OTHER    |                2.06 |                  73.2  |                    70.32 |                 70.09 |              68.67 |                68.9  |                   31.1  |           85.87 |             35.66 |       0.575 |         nan |       nan |        1.62 |         4.47 |          3.68 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                           | EUROPE   |               15.85 |                  63    |                    68.29 |                 70    |              64.77 |                78.46 |                   21.54 |           87.77 |             52.91 |     nan     |         nan |       nan |      nan    |         8.83 |          7.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                              | US       |               38.25 |                  55.07 |                    65.7  |                 69.18 |              61.1  |                79.47 |                   20.53 |           87.05 |             71.44 |     nan     |         nan |       nan |      nan    |        12.86 |         32.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                         | EUROPE   |               14.75 |                  56.74 |                    66.22 |                 69.01 |              62.71 |                81.66 |                   18.34 |           81.95 |             71.6  |     nan     |         nan |       nan |      nan    |        11.37 |         14.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NAT      | NAT                              | US       |                1.29 |                  54.98 |                    65.42 |                 69    |              60.79 |                77.03 |                   22.97 |           86.79 |             73.36 |     nan     |         nan |       nan |      nan    |        15.54 |         11.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | GSL      | Global Ship Lease, Inc.          | OTHER    |                1.4  |                  78.35 |                    70.43 |                 68.59 |              73.31 |                74.44 |                   25.56 |           67.65 |             35.01 |       0.08  |         nan |       nan |        3.83 |         5.09 |          4.34 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               23.17 |                  55.37 |                    65.18 |                 68.53 |              59.3  |                79.89 |                   20.11 |           96.21 |             50.49 |     nan     |         nan |       nan |      nan    |        11.24 |         11.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           15 | TNK      | Teekay Tankers Ltd.              | OTHER    |                2.71 |                  58.08 |                    65.57 |                 68.36 |              64.03 |                80.07 |                   19.93 |           74.06 |             77.95 |       0.073 |         nan |       nan |        3.86 |         8.33 |          5.2  |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.34 |                  57.07 |                    65.33 |                 68.24 |              59.64 |                78.17 |                   21.83 |           96.5  |             44.71 |     nan     |         nan |       nan |      nan    |        10.65 |         14.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IHS      | IHS Holding Limited              | OTHER    |                2.46 |                  72.91 |                    68.03 |                 68.06 |              71.85 |                60.88 |                   39.12 |           54.11 |             83.96 |      -0.114 |         nan |       nan |        7.52 |        15.33 |          5.14 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BBWI     | Bath & Body Works, Inc.          | US       |                3.22 |                  80    |                    71.13 |                 67.9  |              71.36 |                57.28 |                   42.72 |           72.54 |             34.53 |       0.205 |         nan |       nan |        5.86 |         6.61 |          4.89 |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|          nan | NLY      | NLY                              | US       |               14.76 |                  68.39 |                    67.75 |                 67.88 |              64.74 |                69.92 |                   30.08 |           89.03 |             29.07 |     nan     |         nan |       nan |      nan    |         7.3  |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                                | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:----------------------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ANF      | ANF                                                 | US       |                5.23 |                     0.08 |    -0.08 |      0.25 |                  77.59 |                        79.5  |         79.44 |         80.01 |          76.64 |        76.8  |           88.03 |             68.3  |         8.49 |
|               2 | SRAIL.SW | SRAIL.SW                                            | EUROPE   |                3.15 |                     0.06 |    -0.01 |      0.19 |                  73.5  |                        78.33 |         81.25 |         77.74 |          71.68 |        64.09 |           77.05 |             75.13 |         5.32 |
|               3 | AVAH     | AVAH                                                | US       |                2.48 |                     0.04 |    -0.03 |      0.41 |                  73.55 |                        78.31 |         81.71 |         79.82 |          73.09 |        70.88 |           93.39 |             51.61 |         7.45 |
|               4 | WT       | WT                                                  | US       |                3.1  |                     0.05 |    -0.04 |      0.08 |                  80.94 |                        76.32 |         67.7  |         75.9  |          73.26 |        64.71 |           71.97 |             78.9  |         5.61 |
|               5 | RAND.AS  | RAND.AS                                             | EUROPE   |                6.77 |                     0.05 |    -0.03 |      0    |                  75.37 |                        75.93 |         57.93 |         76.09 |          71.3  |        65.33 |           80.11 |             70.42 |         6.75 |
|               6 | DK       | DK                                                  | US       |                3.77 |                     0.04 |     0.01 |      0.2  |                  58.34 |                        73.74 |         82.85 |         81.83 |          74.16 |        61.08 |           54.15 |             84.87 |         7.09 |
|               7 | VWS.CO   | VWS.CO                                              | EUROPE   |               27.6  |                     0.03 |     0.01 |      0.22 |                  50.28 |                        73.25 |         81.06 |         67.5  |          65.6  |        62.24 |           88.37 |             50.03 |         5.75 |
|               8 | KRX.IR   | KRX.IR                                              | EUROPE   |               18.1  |                     0.03 |    -0.02 |      0.2  |                  63.27 |                        73.19 |         75.35 |         67.03 |          64.74 |        63.67 |           97.81 |             43.08 |         5.29 |
|               9 | GL9.IR   | GL9.IR                                              | EUROPE   |                5.42 |                     0.06 |    -0.02 |      0.01 |                  73.21 |                        73.1  |         53.5  |         62.94 |          74.87 |        70.74 |           97.37 |             74.54 |         2.29 |
|              10 | CCC      | CCC                                                 | US       |                3.65 |                     0.06 |    -0.02 |      0.11 |                  75.46 |                        72.8  |         67.99 |         69.75 |          64.31 |        68.1  |           86.58 |             61.92 |         8.01 |
|              11 | GGN      | GAMCO Global Gold, Natural Resources & Income Trust | US       |                0.75 |                     0.02 |    -0.01 |      0.1  |                  52.34 |                        72.51 |         73.7  |         63.32 |          60.52 |        60.6  |           77.31 |             82.33 |         2.22 |
|              12 | BAX      | BAX                                                 | US       |               11.46 |                     0.07 |    -0.03 |     -0.06 |                  67.45 |                        71.55 |         49.04 |         71.76 |          71.82 |        69.79 |           75.9  |             69.18 |         6.21 |
|              13 | WKC      | World Kinect Corporation                            | US       |                1.55 |                     0.06 |    -0.02 |     -0.09 |                  77.09 |                        71.35 |         45.7  |         69.49 |          74.6  |        69.36 |           67.7  |             76.68 |         4.94 |
|              14 | ABNB     | ABNB                                                | US       |               94.63 |                     0.04 |    -0.03 |      0.2  |                  67.77 |                        71.03 |         75.57 |         72.72 |          63.82 |        54.9  |           70.62 |             59.69 |         4.91 |
|              15 | BHVN     | BHVN                                                | US       |                2.04 |                     0.07 |    -0.07 |      0.15 |                  80.54 |                        70.99 |         69.96 |         73.06 |          59.14 |        43.84 |           50.7  |             81.61 |         8.88 |
|              16 | AMC      | AMC                                                 | US       |                2.03 |                     0.02 |     0.01 |     -0.01 |                  47.19 |                        70.64 |         60.33 |         75.07 |          73.62 |        74.2  |           83.97 |             61.59 |         9.61 |
|              17 | A        | A                                                   | US       |               36.81 |                     0.05 |    -0.02 |      0.07 |                  73.35 |                        69.78 |         67.67 |         63.87 |          61.4  |        56.39 |           72.47 |             69.67 |         4.43 |
|              18 | METSO.HE | METSO.HE                                            | EUROPE   |               14.32 |                     0.06 |    -0.05 |      0.03 |                  82.75 |                        69.65 |         62.35 |         56.01 |          60.1  |        58.12 |           79.42 |             67.86 |         4.82 |
|              19 | HQH      | Abrdn Healthcare Investors                          | US       |                1.12 |                     0.05 |    -0.03 |      0.03 |                  77.21 |                        69.61 |         60.88 |         69.31 |          64.34 |        51.39 |           55.12 |             82.33 |         2.27 |
|              20 | ITRG     | ITRG                                                | US       |                0.49 |                     0.05 |    -0.04 |      0.17 |                  79.29 |                        69.61 |         67.34 |         57.47 |          58.1  |        68.77 |           58.96 |             81.68 |         8.28 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.12 |             57.8  |         61.45 |         46.43 |          54.14 |        63.48 |           82.18 |             44.18 |             53.55 |         8.5  |             75.81 | long               |                4.67 |                  2.38 |                 1.93 |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.7  |             44.18 |         35.24 |         39.46 |          48.9  |        62.45 |           61.05 |             55.5  |             92.89 |         8.5  |             82.14 | long               |               -0.01 |                 -0.49 |                -0.41 |
|    nan | ORCL     | Oracle Corporation                                   | US       |              362.06 |             43.65 |         46.68 |         38.23 |          41.6  |        45.7  |           47.61 |             61.75 |             45.07 |         7.95 |             89.54 | short              |                3.6  |                  0.06 |                -0.06 |
|    nan | SHOE     | Shoe Station Group Inc.                              | US       |                0.32 |             29.69 |         25.82 |         25.16 |          33.55 |        42.67 |           38.55 |             45.72 |             62.47 |         7.02 |             84.21 | long               |               -0.5  |                 -0.29 |               nan    |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    321 | MAU.PA   | MAU.PA | EUROPE   |                1.64 |             56.79 |         63.75 |         34.92 |          49.84 |        64.2  |           75.76 |             11.72 |             69.69 |         5.31 |             69.68 | long               |               -3.04 |                  2.87 |                 2.74 |
|     14 | GTLB     | GTLB   | US       |                7.13 |             76.65 |         91.22 |         86.63 |          66.68 |        43.75 |          nan    |             86.05 |             10.02 |         8.36 |             66.84 | short              |               14.48 |                  2.84 |                 2.42 |
|    211 | SHEL.L   | SHEL.L | EUROPE   |            18936.7  |             61.02 |         70.94 |         56.06 |          57.94 |        64.1  |          nan    |            nan    |            nan    |         2.95 |             55.84 | short              |               -3.63 |                  2.6  |                 2.64 |
|    442 | ALEC     | ALEC   | US       |                0.26 |             52.68 |         79.21 |         63.8  |          41.57 |        27.6  |            2.65 |             50.62 |            nan    |         9.5  |             64.91 | short              |              nan    |                  2.6  |               nan    |
|    278 | EQX      | EQX    | US       |               12.72 |             58.78 |         66.74 |         53.69 |          53.35 |        63.87 |           51.39 |             62.38 |             85.82 |         8.19 |             67.16 | short              |              nan    |                  2.6  |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    341 | FNKO     | FNKO    | US       |                0.29 |             56.15 |         54.79 |         57.83 |          57.52 |        47.93 |           29.85 |             64.4  |             41.95 |         7.66 |             68.66 | swing              |               -4.24 |                 -3.49 |                -2.69 |
|    572 | HAFN     | HAFN    | US       |                3.83 |             45.82 |         70.68 |         51.61 |          40.03 |        36.68 |            8.63 |             20.42 |             60.85 |         5.43 |             65.68 | short              |              nan    |                 -3.09 |               nan    |
|    254 | BION.SW  | BION.SW | EUROPE   |                3.27 |             59.52 |         65.81 |         62.15 |          56.89 |        55.45 |           48.33 |             25.79 |             62.21 |         2.05 |             63.59 | short              |              -16.61 |                 -2.97 |                -2.43 |
|    483 | TENB     | TENB    | US       |                3.26 |             50.48 |         46.11 |         56.32 |          54.85 |        42.14 |           27.6  |             63.5  |             35.89 |         8.35 |             68.2  | swing              |               -5.56 |                 -2.74 |                -1.86 |
|    595 | S        | S       | US       |                5.91 |             44.6  |         39.7  |         54.01 |          49.5  |        36.72 |           34.08 |             45.34 |             14.74 |         7.12 |             68.66 | swing              |               -7.34 |                 -2.59 |                -1.13 |

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
- Excluded by hard/data filters: **281**
- Event watch (otherwise eligible): **4**
- Final eligible: **715**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 226
- price: 179
- market_cap: 152
- price_history: 14
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 7 | 7 |  | 5 | 2 | main,value,quality_value |
| IRWD | 36 | 1 |  | 1 | 1 | value,quality_value |
| DDI | 47 | 8 |  | 4 | 1 | value,quality_value |
| NVDA | 70 | 6 |  | 3 | 1 | value,quality_value |
| HMC | 85 | 3 |  | 2 | 1 | value,quality_value |
| GSL | 109 | 4 |  | 7 | 1 | value,quality_value |
| IHS | 221 | 9 |  | 9 | 1 | value,quality_value |
| STNE | 510 | 5 |  | 6 | 1 | value,quality_value |
| BBWI | 621 | 2 | 321 | 10 | 1 | value,quality_value |
| PSX | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| CMBT.BR | 4 |  |  |  | 1 | main |
| CRGY | 5 |  |  |  | 1 | main |
| NAT | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (PSX, FRO, VLO, CRGY, NAT, DELL, DINO, OKTA)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SRAIL.SW, RAND.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | SIE.DE | value+pullback | 68.47 | 65.33 | 85.08 | 53.37 | 62.61 | 66.68 | 53.33 |
| 2 | WKC | value+pullback | 68.44 | 58.31 | 77.09 | 67.70 | 76.68 | 69.24 | 69.43 |
| 3 | CEF | value+pullback | 67.75 | 56.26 | 79.50 | 63.49 | 82.33 | 66.21 | 55.47 |
| 4 | SU.PA | value+pullback | 66.45 | 56.31 | 69.15 | 79.78 | 56.99 | 73.01 | 56.55 |
| 5 | BBWI | value+pullback | 64.97 | 80.00 | 60.75 | 72.54 | 34.53 | 57.28 | 42.69 |
| 6 | UNIT | value+pullback | 64.27 | 80.26 | 74.45 | 63.21 | 32.19 | 44.40 | 45.83 |
| 7 | ETG | value+pullback | 63.58 | 55.06 | 51.96 | 69.18 | 82.33 | 77.28 | 60.39 |
| 8 | XNET | value+pullback | 63.41 | 59.86 | 62.21 | 56.69 | 82.33 | 65.80 | 43.96 |
| 9 | AVK | value+pullback | 61.97 | 56.27 | 74.57 | 63.42 | 54.70 | 57.33 | 48.35 |
| 10 | ALL-PH | value+pullback | 61.18 | 61.97 | 64.79 | 69.30 | 43.88 | 58.06 | 44.26 |
| 11 | TV | value+pullback | 61.12 | 67.97 | 75.93 | 43.47 | 29.34 | 61.48 | 34.34 |
| 12 | MFA | value+pullback | 60.91 | 57.12 | 63.62 | 77.67 | 35.99 | 63.08 | 44.81 |
| 13 | AIR.PA | value+pullback | 59.90 | 61.83 | 64.48 | 65.33 | 55.71 | 49.33 | 53.91 |
| 14 | NOMD | value+pullback | 58.85 | 55.30 | 78.76 | 61.96 | 31.39 | 50.70 | 50.60 |
| 15 | MAGN | value+pullback | 58.62 | 64.74 | 58.31 | 54.08 | 37.74 | 63.70 | 47.23 |
| 16 | MSFT | value+pullback | 58.58 | 58.21 | 56.66 | 63.26 | 67.74 | 53.44 | 60.62 |
| 17 | GL9.IR | pullback | 57.95 | 42.28 | 73.21 | 97.37 | 74.54 | 87.93 | 66.84 |
| 18 | IRWD | value | 57.10 | 73.36 | 30.95 | 84.18 | 65.58 | 79.56 | 71.90 |
| 19 | LNC | value+pullback | 56.79 | 59.01 | 65.22 | 46.62 | 66.15 | 45.88 | 60.42 |
| 20 | ORC | value+pullback | 56.64 | 55.71 | 53.72 | 72.79 | 37.25 | 59.28 | 47.91 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 10/10 | 10/10 | 9/10 | 0/10 | 69.7 | 2 / 8 |
| Top 25 | 22/25 | 25/25 | 24/25 | 21/25 | 0/25 | 69.2 | 6 / 19 |
| Top 50 | 46/50 | 50/50 | 49/50 | 45/50 | 0/50 | 69.3 | 13 / 37 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=2, large_20_100b=3, mega_100b_plus=1
