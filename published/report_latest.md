# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-18

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

- **EUROPE:** 82.4/100
- **OTHER:** 67.9/100
- **US:** 82.5/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |               10.49 |             86.54 |         87.71 |         88.15 |          85.37 |        81.02 |           91.83 |             79.36 |             55.67 |         5.58 |             73.14 | swing              |                0.15 |                  0.44 |                 0.17 |
|      2 | VLO      | VLO                        | US       |              103.56 |             85.98 |         86.57 |         90.23 |          85.4  |        79.64 |           86.27 |             81.03 |             56.51 |         3.37 |             69.68 | swing              |               -0.04 |                  0.26 |               nan    |
|      3 | PSX      | PSX                        | US       |               95.85 |             85.13 |         85.75 |         90.1  |          84.5  |        78.16 |           80.86 |             86.12 |             57.64 |         3.55 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      4 | DK       | DK                         | US       |                4.35 |             84.93 |         92.62 |         89.87 |          79.98 |        68.39 |           55.99 |             93.41 |             53.09 |         7.3  |             73.14 | short              |              nan    |                  0.57 |                 0.18 |
|      5 | CMBT.BR  | CMBT.BR                    | EUROPE   |                5.24 |             84.66 |         85.14 |         85.49 |          84.18 |        80.77 |           95.61 |             76.56 |             56.45 |         3.96 |             73.14 | swing              |               -2.02 |                  2.19 |                 2    |
|      6 | DHT      | DHT                        | US       |                3.21 |             84.65 |         87.32 |         85.84 |          83.45 |        81.26 |           89.45 |             82.42 |             60.6  |         4.66 |             73.14 | short              |               -0.78 |                  1.52 |                 0.91 |
|      7 | DELL     | DELL                       | US       |              326.17 |             83.8  |         93.41 |         87.36 |          80.24 |        67.41 |           74.02 |             82    |             28.61 |         7.85 |             72.23 | short              |                0.34 |                  0.58 |                -0.24 |
|      8 | PARR     | Par Pacific Holdings, Inc. | US       |                3.78 |             82.39 |         84.23 |         83.93 |          80.84 |        78.03 |           82.97 |             76.63 |             64    |         7.05 |             84.98 | short              |                2.4  |                  0.49 |                 0.27 |
|      9 | NAT      | NAT                        | US       |                1.5  |             82.22 |         86.66 |         84.82 |          79.62 |        72.65 |           87.51 |             68.53 |             35.57 |         4.98 |             73.14 | short              |                0.12 |                  1.14 |                 1.01 |
|     10 | SB       | SB                         | US       |                0.89 |             81.85 |         87.67 |         84.27 |          79.43 |        74.55 |           69.69 |             81.71 |             64.47 |         4.31 |             72.34 | short              |                2.48 |                  2.18 |               nan    |
|     11 | AVAH     | AVAH                       | US       |                2.66 |             81.73 |         82.32 |         85.19 |          81.14 |        74.71 |           93.87 |             67.86 |             36.83 |         7.78 |             72.11 | swing              |               -1.21 |                  0.49 |                 0.25 |
|     12 | DINO     | DINO                       | US       |               18.08 |             81.52 |         83.64 |         89.42 |          79.4  |        69.71 |           50.84 |             86.66 |             69.94 |         4.35 |             73.14 | swing              |               -0.09 |                  0.42 |                -0.07 |
|     13 | SM       | SM                         | US       |                7.67 |             81.19 |         69.1  |         79.99 |          82.39 |        86.4  |           82.53 |             80.46 |             96.14 |         7.14 |             72.11 | long               |               -2.15 |                 -0.32 |                -0.89 |
|     14 | HPE      | HPE                        | US       |               70.64 |             81.13 |         88.67 |         82.83 |          79.44 |        71.46 |           73.22 |             72.31 |             51.98 |         7.04 |             72.34 | short              |                7    |                 -0.4  |                -0.74 |
|     15 | PBF      | PBF                        | US       |                7.97 |             80.19 |         78.93 |         86.74 |          81.46 |        76.82 |           53.36 |             87.1  |             91.2  |         7.74 |             72.68 | swing              |                1.01 |                 -0.16 |                -0.78 |
|     16 | CRGY     | CRGY                       | US       |                4.84 |             79.49 |         74.35 |         79.55 |          79.42 |        84.02 |           72.37 |             89.47 |             94.79 |         6.58 |             72.68 | long               |               11.11 |                 -0.87 |                -1.22 |
|     17 | AMC      | AMC                        | US       |                2.11 |             79.22 |         77.94 |         76.09 |          80.49 |        80.55 |           86.24 |             98.13 |            nan    |         9.69 |             65.07 | long               |                0.13 |                  0.83 |                 0.6  |
|     18 | APA      | APA                        | US       |               13.89 |             78.24 |         79.27 |         79.22 |          77.26 |        76.66 |           75.97 |             77.95 |             65.61 |         6    |             72.11 | short              |                7.55 |                  0.14 |                -0.09 |
|     19 | OKTA     | OKTA                       | US       |               28.96 |             77.95 |         91.05 |         83.41 |          72.49 |        58.73 |           68.79 |             68.11 |             13.88 |         7.86 |             72.11 | short              |                0.33 |                  0.9  |                 0.99 |
|     20 | KIN.BR   | KIN.BR                     | EUROPE   |                1.33 |             77.71 |         83.89 |         81.04 |          74.38 |        65.19 |           88.51 |             65.63 |             20.01 |         3.81 |             73.14 | short              |               -1.28 |                 -0.14 |                -0.48 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.06 |                  84.42 |                    76.31 |                 75.71 |              80.56 |                65.2  |                   34.8  |           63.54 |             80.37 |     nan     |         nan |       nan |        1.79 |         4.71 |          4.78 |        5.41 |                 nan |              nan |                  11 |                  0.58 |
|            2 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  69.72 |                    74.91 |                 77.77 |              72.4  |                85.55 |                   14.45 |           93.42 |             68.04 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | NVDA      | NVIDIA Corporation                   | US       |             4617.67 |                  61.64 |                    71.25 |                 73.21 |              66.37 |                77.48 |                   22.52 |           87.16 |             80.41 |       0.008 |         nan |       nan |       26.15 |        14.05 |         27.01 |        0.45 |                 nan |              nan |                  12 |                  0.63 |
|            4 | BBWI      | Bath & Body Works, Inc.              | US       |                3.02 |                  77.56 |                    70.98 |                 68.31 |              70.25 |                60.68 |                   39.32 |           76.37 |             34.79 |       0.221 |         nan |       nan |        5.64 |         6.17 |          4.4  |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|            5 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.78 |                  68.03 |                    70.51 |                 73.1  |              68.94 |                68.31 |                   31.69 |           82.97 |             76.63 |       0.019 |         nan |       nan |        4.15 |         6.25 |          4.98 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | IRWD      | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  67.4  |                    70.29 |                 72.79 |              68.3  |                79.74 |                   20.26 |           89.46 |             54.2  |       0.174 |         nan |       nan |        4.27 |         2.82 |          5.29 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              237.45 |                  56.84 |                    70.02 |                 74.19 |              64.92 |                87.76 |                   12.24 |           92.63 |             81.96 |     nan     |         nan |       nan |      nan    |         9.48 |         10.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                3.21 |                  58.37 |                    69.51 |                 73.26 |              64.99 |                81.81 |                   18.19 |           89.45 |             82.42 |     nan     |         nan |       nan |      nan    |        10.82 |          7.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                                   | US       |                7.67 |                  62.43 |                    69.14 |                 71.72 |              66.1  |                72.81 |                   27.19 |           82.53 |             80.46 |     nan     |         nan |       nan |      nan    |         4.71 |          6.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                5.24 |                  56.38 |                    69.12 |                 73.42 |              63.44 |                84.39 |                   15.61 |           95.61 |             76.56 |     nan     |         nan |       nan |      nan    |        10.05 |          7.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE      | StoneCo Ltd.                         | OTHER    |                1.96 |                  71.39 |                    69.07 |                 68.75 |              66.96 |                68.21 |                   31.79 |           85.87 |             32.83 |     nan     |         nan |       nan |        1.62 |         4.28 |          3.67 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|            8 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.45 |                  73.43 |                    68.81 |                 68.08 |              69.7  |                76.18 |                   23.82 |           75.71 |             31.19 |       0.078 |         nan |       nan |        3.96 |         5.2  |          4.43 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            9 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               60.94 |                  79.07 |                    68.72 |                 64.83 |              72.1  |                54.91 |                   45.09 |           52.35 |             52.86 |       0.035 |         nan |       nan |       16.03 |        13.57 |         19.17 |        0.97 |                 nan |              nan |                  12 |                  0.63 |
|           10 | PBR       | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              117.65 |                  72.92 |                    68.65 |                 68.34 |              70.58 |                62.31 |                   37.69 |           63.54 |             68.63 |     nan     |         nan |       nan |        1.85 |         5.25 |          5.29 |        5.99 |                 nan |              nan |                  11 |                  0.58 |
|           11 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.8  |                  74.63 |                    68.61 |                 68.81 |              69.78 |                66.82 |                   33.18 |           76.69 |             40.17 |       0.587 |         nan |       nan |        4.41 |      -139.33 |          2.4  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | AVGO      | Broadcom Inc.                        | US       |             1445.42 |                  60.81 |                    68.32 |                 68.96 |              62.32 |                78.47 |                   21.53 |           92.79 |             44.16 |       0.018 |         nan |       nan |       32.4  |        17.92 |         43.3  |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO       | FRO                                  | US       |               10.49 |                  56.33 |                    68.13 |                 72.24 |              62.93 |                80.19 |                   19.81 |           91.83 |             79.36 |     nan     |         nan |       nan |      nan    |        11.88 |          8.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | IHS       | IHS Holding Limited                  | OTHER    |                2.49 |                  71.96 |                    67.65 |                 67.73 |              71.05 |                63.18 |                   36.82 |           56.28 |             78.64 |      -0.114 |         nan |       nan |        7.53 |        15.36 |          5.18 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           14 | HMC       | Honda Motor Co., Ltd.                | OTHER    |               36.8  |                  62.24 |                    67.5  |                 71.09 |              66.19 |                71.25 |                   28.75 |           78.26 |             85.56 |       0.041 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHEL      | SHEL                                 | US       |              238.65 |                  66.01 |                    67.21 |                 67.62 |              66.05 |                70.06 |                   29.94 |           74.16 |             59.08 |     nan     |         nan |       nan |      nan    |         9.27 |         10.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  69.72 |                    74.91 |                 77.77 |              72.4  |                85.55 |                   14.45 |           93.42 |             68.04 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.06 |                  84.42 |                    76.31 |                 75.71 |              80.56 |                65.2  |                   34.8  |           63.54 |             80.37 |     nan     |         nan |       nan |        1.79 |         4.71 |          4.78 |        5.41 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              237.45 |                  56.84 |                    70.02 |                 74.19 |              64.92 |                87.76 |                   12.24 |           92.63 |             81.96 |     nan     |         nan |       nan |      nan    |         9.48 |         10.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.24 |                  56.38 |                    69.12 |                 73.42 |              63.44 |                84.39 |                   15.61 |           95.61 |             76.56 |     nan     |         nan |       nan |      nan    |        10.05 |          7.05 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.21 |                  58.37 |                    69.51 |                 73.26 |              64.99 |                81.81 |                   18.19 |           89.45 |             82.42 |     nan     |         nan |       nan |      nan    |        10.82 |          7.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4617.67 |                  61.64 |                    71.25 |                 73.21 |              66.37 |                77.48 |                   22.52 |           87.16 |             80.41 |       0.008 |         nan |       nan |       26.15 |        14.05 |         27.01 |        0.45 |                 nan |              nan |                  12 |                  0.63 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.78 |                  68.03 |                    70.51 |                 73.1  |              68.94 |                68.31 |                   31.69 |           82.97 |             76.63 |       0.019 |         nan |       nan |        4.15 |         6.25 |          4.98 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.61 |                  67.4  |                    70.29 |                 72.79 |              68.3  |                79.74 |                   20.26 |           89.46 |             54.2  |       0.174 |         nan |       nan |        4.27 |         2.82 |          5.29 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO      | FRO                                  | US       |               10.49 |                  56.33 |                    68.13 |                 72.24 |              62.93 |                80.19 |                   19.81 |           91.83 |             79.36 |     nan     |         nan |       nan |      nan    |        11.88 |          8.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.67 |                  62.43 |                    69.14 |                 71.72 |              66.1  |                72.81 |                   27.19 |           82.53 |             80.46 |     nan     |         nan |       nan |      nan    |         4.71 |          6.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | HMC      | Honda Motor Co., Ltd.                | OTHER    |               36.8  |                  62.24 |                    67.5  |                 71.09 |              66.19 |                71.25 |                   28.75 |           78.26 |             85.56 |       0.041 |         nan |       nan |        7.16 |       nan    |        nan    |        3.45 |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                                  | US       |               14.65 |                  55.78 |                    66.02 |                 69.37 |              61.6  |                79.53 |                   20.47 |           86.58 |             71.31 |     nan     |         nan |       nan |      nan    |        10.4  |         22.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |              103.56 |                  51.58 |                    65.01 |                 69.28 |              60.06 |                82.33 |                   17.67 |           86.27 |             81.03 |     nan     |         nan |       nan |      nan    |        11.05 |         16.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              101.98 |                  59.03 |                    66.5  |                 69.18 |              62.39 |                75.05 |                   24.95 |           87.16 |             63.81 |     nan     |         nan |       nan |      nan    |         9.33 |         21.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | AVGO     | Broadcom Inc.                        | US       |             1445.42 |                  60.81 |                    68.32 |                 68.96 |              62.32 |                78.47 |                   21.53 |           92.79 |             44.16 |       0.018 |         nan |       nan |       32.4  |        17.92 |         43.3  |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|           11 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.8  |                  74.63 |                    68.61 |                 68.81 |              69.78 |                66.82 |                   33.18 |           76.69 |             40.17 |       0.587 |         nan |       nan |        4.41 |      -139.33 |          2.4  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.96 |                  71.39 |                    69.07 |                 68.75 |              66.96 |                68.21 |                   31.79 |           85.87 |             32.83 |     nan     |         nan |       nan |        1.62 |         4.28 |          3.67 |      nan    |                 nan |              nan |                   9 |                  0.47 |
|          nan | MU       | MU                                   | US       |              962.51 |                  48.9  |                    63.34 |                 68.65 |              56.34 |                75.55 |                   24.45 |           96.02 |             75.38 |     nan     |         nan |       nan |      nan    |         6.24 |         20.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY                                  | US       |               51.67 |                  52.41 |                    64.5  |                 68.56 |              59.61 |                77.95 |                   22.05 |           86.12 |             78.36 |     nan     |         nan |       nan |      nan    |        14.69 |         17.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.51 |                  55.49 |                    65.22 |                 68.53 |              59.54 |                79.51 |                   20.49 |           94.89 |             52.74 |     nan     |         nan |       nan |      nan    |        11.8  |         12.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH     | AVAH                                 | US       |                2.66 |                     0.03 |     0.01 |      0.06 |                  52.12 |                        79.37 |         82.32 |         85.19 |          81.14 |        74.71 |           93.87 |             67.86 |         7.78 |
|               2 | TALO     | TALO                                 | US       |                2.5  |                     0.06 |    -0.02 |     -0    |                  71.51 |                        77.06 |         66.99 |         76.75 |          77.44 |        76.78 |           68.76 |             94.72 |         5.74 |
|               3 | SHELL.AS | SHELL.AS                             | EUROPE   |              237.45 |                     0.03 |     0.01 |      0.03 |                  50.44 |                        76.82 |         76.88 |         73.13 |          73.64 |        78.72 |           92.63 |             81.96 |         2.39 |
|               4 | CRGY     | CRGY                                 | US       |                4.84 |                     0.08 |    -0.02 |      0.05 |                  60.2  |                        76.7  |         74.35 |         79.55 |          79.42 |        84.02 |           72.37 |             89.47 |         6.58 |
|               5 | PR       | PR                                   | US       |               16.94 |                     0.05 |    -0.01 |      0.01 |                  69.81 |                        76.04 |         70.09 |         75.61 |          76.71 |        78.34 |           80.15 |             78.23 |         4.49 |
|               6 | SM       | SM                                   | US       |                7.67 |                     0.1  |    -0.03 |      0.03 |                  49.36 |                        75.97 |         69.1  |         79.99 |          82.39 |        86.4  |           82.53 |             80.46 |         7.14 |
|               7 | NVDA     | NVIDIA Corporation                   | US       |             4617.67 |                     0.05 |     0    |      0.01 |                  64.43 |                        74.16 |         70.01 |         66.52 |          69.12 |        69.22 |           87.16 |             80.41 |         5.86 |
|               8 | MU       | MU                                   | US       |              962.51 |                     0.05 |     0    |      0.04 |                  67.04 |                        73.97 |         66.8  |         66.33 |          83.73 |        85.44 |           96.02 |             75.38 |         8.33 |
|               9 | C5H.IR   | C5H.IR                               | EUROPE   |                1.68 |                     0.04 |    -0.01 |      0.11 |                  67.29 |                        73.76 |         74.88 |         67.49 |          68.78 |        73.29 |           97.55 |             44.78 |         2.64 |
|              10 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.06 |                     0.03 |    -0.01 |      0.17 |                  60.96 |                        73.39 |         78.97 |         75.14 |          70.8  |        74.67 |           63.54 |             80.37 |         3.75 |
|              11 | CRM      | CRM                                  | US       |              174.25 |                     0.08 |     0    |      0.18 |                  55.03 |                        73.23 |         81.34 |         76.95 |          63.19 |        60.11 |           65.23 |             75.09 |         7.97 |
|              12 | BP       | BP                                   | US       |              101.98 |                     0.03 |    -0.01 |      0.04 |                  61.26 |                        72.63 |         72.86 |         65.97 |          67.04 |        74.9  |           87.16 |             63.81 |         4.48 |
|              13 | OXY      | OXY                                  | US       |               51.67 |                     0.07 |    -0.03 |     -0.01 |                  72.57 |                        71.83 |         58.89 |         63.94 |          68.53 |        73.48 |           86.12 |             78.36 |         5.11 |
|              14 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              117.65 |                     0.04 |    -0.02 |      0.16 |                  66.39 |                        71.78 |         77.64 |         71.3  |          67.11 |        70.58 |           63.54 |             68.63 |         4.45 |
|              15 | GEN      | GEN                                  | US       |               15.77 |                     0.04 |     0.01 |      0.1  |                  58.1  |                        71.77 |         77.61 |         75.72 |          69.16 |        69.85 |           77.5  |             58.34 |         5.83 |
|              16 | MT.AS    | MT.AS                                | EUROPE   |               49.32 |                     0.03 |     0.02 |      0.07 |                  50.3  |                        71.51 |         75.3  |         76.1  |          76.72 |        72.82 |           72.29 |             76.39 |         5.06 |
|              17 | OSCR     | OSCR                                 | US       |                8.61 |                     0.05 |    -0.02 |     -0.01 |                  75.66 |                        71.5  |         62.47 |         73.4  |          73.85 |        61.89 |           53.81 |             84.56 |         8.25 |
|              18 | BEN      | BEN                                  | US       |               14.65 |                     0.06 |    -0.02 |     -0.03 |                  75.36 |                        71.3  |         51.2  |         63.97 |          76    |        77.7  |           86.58 |             71.31 |         3.29 |
|              19 | KRX.IR   | KRX.IR                               | EUROPE   |               17.42 |                     0.08 |    -0.06 |     -0.04 |                  70.71 |                        71.22 |         49.1  |         64.68 |          69.89 |        65.66 |           96.14 |             60.32 |         5.62 |
|              20 | KOS      | KOS                                  | US       |                1.47 |                     0.08 |    -0.03 |      0.01 |                  64.72 |                        71.15 |         60.46 |         68.67 |          72.69 |        74.54 |           65.76 |             93.02 |         8.77 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.64 |             39.37 |         36.11 |         33.42 |          42.63 |        49.92 |           77.39 |             45.55 |                26 |         3.22 |             89.79 | long               |               -0.63 |                 -0.43 |                -0.22 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     40 | PANW     | PANW   | US       |              267.48 |             74.69 |         79.37 |         79.21 |          70.17 |        50.8  |           48.82 |             85.09 |              6.43 |         7.59 |             73.14 | short              |                1.87 |                  4.76 |                 4.26 |
|     22 | RBRK     | RBRK   | US       |               19.35 |             77.61 |         88.7  |         85.44 |          69.79 |        50.77 |           53.77 |             90.38 |              1.81 |         8.72 |             72.23 | short              |                1.21 |                  4.12 |                 3.54 |
|    334 | BRKR     | BRKR   | US       |                8.38 |             57.34 |         75.19 |         62.9  |          51.77 |        36.55 |           20.3  |             45.91 |             22.11 |         8.01 |             71.66 | short              |                4.42 |                  3.55 |               nan    |
|     36 | NTSK     | NTSK   | US       |                6.13 |             75.14 |         90.8  |         84.29 |          65.99 |        45.75 |           51.09 |             86.78 |              1.83 |         9.31 |             65    | short              |                0.66 |                  3.3  |                 2.36 |
|    116 | FTRE     | FTRE   | US       |                1.68 |             66.59 |         79.3  |         73.3  |          59.88 |        44.32 |           22.6  |             58.56 |             35.86 |         8.03 |             73.14 | short              |                0.86 |                  3.21 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    492 | APH      | APH                                  | US       |              168.49 |             50.6  |         49.52 |         44.77 |          51.68 |        53.41 |           80.51 |             27.52 |             18.68 |         6.11 |             73.14 | long               |                3.66 |                 -2.95 |                -2.85 |
|    213 | HMY      | HMY                                  | US       |               10.89 |             61.57 |         51.06 |         57.46 |          65.68 |        73.77 |           83.16 |             29.09 |             82.46 |         8.19 |             73.14 | long               |                3.54 |                 -2.89 |               nan    |
|    591 | ASA      | ASA Gold and Precious Metals Limited | US       |                0.94 |             45.27 |         38.8  |         37.54 |          51.74 |        58.38 |           65.23 |            nan    |             47.08 |         5.84 |             63.1  | long               |               -0.08 |                 -2.89 |                -2.23 |
|    376 | CLOV     | CLOV                                 | US       |                2.1  |             55.31 |         59.92 |         53.8  |          56.82 |        45.99 |           52.87 |             44.36 |             16.5  |         8.43 |             73.14 | short              |               -2.69 |                 -2.6  |                -2.67 |
|    331 | SBSW     | SBSW                                 | US       |                7.6  |             57.48 |         59.72 |         54.56 |          55.25 |        64.76 |           58.47 |             43.16 |             80.6  |         8.52 |             69.68 | long               |                1.85 |                 -2.57 |                -2.33 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.86

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
- Excluded by hard/data filters: **305**
- Event watch (otherwise eligible): **1**
- Final eligible: **694**
- Eligible change vs previous stored run: **-12**

Top exclusion categories:
- liquidity: 258
- market_cap: 236
- price: 201
- data_confidence: 49
- price_history: 22
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 8 | 5 |  | 4 | 2 | main,value,quality_value |
| PBR-A | 38 | 1 | 10 | 2 | 2 | value,pullback,quality_value |
| NVDA | 83 | 3 | 7 | 3 | 2 | value,pullback,quality_value |
| DDI | 59 | 2 | 24 | 1 | 1 | value,quality_value |
| PBR | 63 | 10 | 14 | 10 | 1 | value,quality_value |
| IRWD | 128 | 6 |  | 5 | 1 | value,quality_value |
| STNE | 580 | 7 | 137 | 9 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| VLO | 2 |  |  |  | 1 | main |
| PSX | 3 |  |  |  | 1 | main |
| DK | 4 |  |  |  | 1 | main |
| CMBT.BR | 5 |  |  |  | 1 | main |
| DHT | 6 |  |  |  | 1 | main |
| DELL | 7 |  |  |  | 1 | main |
| NAT | 9 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (FRO, VLO, PSX, DK, CMBT.BR, DHT, DELL, NAT, SB)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SHELL.AS, SM)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | STNE | value+pullback | 72.08 | 71.39 | 83.44 | 85.87 | 32.83 | 68.21 | 45.71 |
| 2 | DDI | value+pullback | 71.23 | 69.72 | 49.56 | 93.42 | 68.04 | 85.55 | 71.44 |
| 3 | NVDA | value+pullback | 71.21 | 61.64 | 64.43 | 87.16 | 80.41 | 77.48 | 69.17 |
| 4 | PBR-A | value+pullback | 71.17 | 84.42 | 60.96 | 63.54 | 80.37 | 65.20 | 74.90 |
| 5 | AVGO | value+pullback | 71.13 | 60.81 | 75.43 | 92.79 | 44.16 | 78.47 | 49.30 |
| 6 | PBR | value+pullback | 67.33 | 72.92 | 66.39 | 63.54 | 68.63 | 62.31 | 70.94 |
| 7 | UNIT | value+pullback | 64.65 | 80.26 | 74.84 | 66.19 | 29.65 | 44.86 | 42.22 |
| 8 | RCI | value+pullback | 64.01 | 59.04 | 71.38 | 84.40 | 43.23 | 57.34 | 45.78 |
| 9 | VOLV-B.ST | value+pullback | 63.29 | 79.07 | 61.78 | 52.35 | 52.86 | 54.91 | 54.64 |
| 10 | BCE | value+pullback | 62.80 | 56.01 | 78.04 | 68.54 | 58.07 | 52.02 | 43.81 |
| 11 | BHF | value+pullback | 62.52 | 70.59 | 58.74 | 52.45 | 55.22 | 66.37 | 41.19 |
| 12 | MFA | value+pullback | 60.84 | 57.07 | 69.96 | 77.49 | 26.70 | 59.65 | 39.59 |
| 13 | ORCL | value+pullback | 60.15 | 69.43 | 63.92 | 57.47 | 64.45 | 41.39 | 48.71 |
| 14 | MAGN | value+pullback | 60.10 | 70.20 | 50.81 | 68.70 | 34.48 | 62.90 | 45.72 |
| 15 | ORC | value+pullback | 59.65 | 55.71 | 64.77 | 75.41 | 35.24 | 59.53 | 38.76 |
| 16 | BBWI | value+pullback | 59.24 | 77.56 | 35.61 | 76.37 | 34.79 | 60.68 | 40.41 |
| 17 | AVK | value+pullback | 58.62 | 55.28 | 60.38 | 63.12 |  | 62.36 | 49.31 |
| 18 | KYN | value+pullback | 58.40 | 55.39 | 66.15 | 55.97 | 50.07 | 59.21 | 52.73 |
| 19 | GVR.IR | pullback | 58.29 | 54.82 | 82.33 | 91.24 | 73.05 | 83.60 | 61.92 |
| 20 | JD | value+pullback | 57.53 | 65.77 | 50.68 | 60.87 | 43.15 | 58.44 | 41.49 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 72.3 | 5 / 20 |
| Top 50 | 47/50 | 50/50 | 49/50 | 46/50 | 0/50 | 72.3 | 16 / 34 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=2, large_20_100b=1, mega_100b_plus=2
