# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-21

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

- **EUROPE:** 81.0/100
- **OTHER:** 66.4/100
- **US:** 79.3/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC                        | US       |              103.97 |             87.77 |         87.68 |         93.09 |          87.87 |        81.58 |           84.35 |             89.86 |             61.93 |         4.05 |             73.14 | swing              |                0.74 |                nan    |               nan    |
|      2 | FRO      | FRO                        | US       |                9.97 |             86.83 |         88.2  |         88.33 |          85.45 |        81.17 |           91.53 |             79.78 |             56.4  |         5.59 |             73.14 | swing              |                0.65 |                  0.25 |                -0.16 |
|      3 | DHT      | DHT                        | US       |                3.27 |             85.58 |         88.19 |         87.2  |          83.96 |        81.3  |           89.53 |             83.81 |             59.55 |         4.73 |             73.14 | short              |                1    |                  0.4  |                -0.26 |
|      4 | CMBT.BR  | CMBT.BR                    | EUROPE   |                5.1  |             85.23 |         88.22 |         84.93 |          85.53 |        83.11 |           95.8  |             76.75 |             62.13 |         4.01 |             73.14 | short              |                1.06 |                  0.71 |                 0.34 |
|      5 | DELL     | DELL                       | US       |              314.72 |             84.46 |         89.35 |         87.47 |          81.45 |        68.89 |           73.47 |             85.5  |             33.05 |         7.91 |             72.23 | short              |                0.76 |                  0.48 |                -0.5  |
|      6 | DK       | DK                         | US       |                4.17 |             84.26 |         89.92 |         88.42 |          80.09 |        69.05 |           55.5  |             93.35 |             56.2  |         7.39 |             73.14 | short              |                0.34 |                 -0.15 |                -0.37 |
|      7 | SB       | SB                         | US       |                0.91 |             83.3  |         90.14 |         86.2  |          80.41 |        75.16 |           70.5  |             82.92 |             64.47 |         4.37 |             72.34 | short              |                1.4  |                  1.42 |                 0.75 |
|      8 | NAT      | NAT                        | US       |                1.52 |             82.63 |         87.09 |         85.26 |          80.01 |        72.94 |           87.09 |             69.61 |             36.6  |         4.99 |             73.14 | short              |                0.83 |                  0.19 |                -0.12 |
|      9 | HPE      | HPE                        | US       |               70.28 |             82.22 |         84.23 |         84.2  |          80.24 |        72.26 |           73.81 |             73.75 |             52.61 |         7.1  |             72.34 | short              |                0.79 |                  1.57 |                 0.96 |
|     10 | DINO     | DINO                       | US       |               17.95 |             82.04 |         85.06 |         89.28 |          79.03 |        69.14 |           48.91 |             86.83 |             70.39 |         4.46 |             73.14 | swing              |                0.52 |                  0.17 |                -0.31 |
|     11 | PBF      | PBF                        | US       |                7.97 |             81.88 |         82.67 |         87.71 |          81.08 |        76    |           51.41 |             87.6  |             90.59 |         7.79 |             72.68 | swing              |                0.34 |                  0.56 |                 0.13 |
|     12 | SM       | SM                         | US       |                7.66 |             81.1  |         65.95 |         79.68 |          82.52 |        86.29 |           82.18 |             78.72 |             95.56 |         7.18 |             72.11 | long               |                1.08 |                 -1.19 |                -1.29 |
|     13 | CRGY     | CRGY                       | US       |                4.76 |             79.95 |         68.57 |         79.56 |          80.34 |        84.43 |           72.53 |             89.73 |             95.19 |         6.58 |             72.68 | long               |                1.22 |                 -1.07 |                -1.4  |
|     14 | KIN.BR   | KIN.BR                     | EUROPE   |                1.34 |             79.21 |         83.67 |         82.71 |          75.71 |        65.89 |           88.71 |             65.47 |             18.16 |         3.84 |             73.14 | short              |                0.84 |                  0.07 |                -0.31 |
|     15 | PARR     | Par Pacific Holdings, Inc. | US       |                3.68 |             78.82 |         80.99 |         80.64 |          77    |        72.81 |           77.17 |             76.34 |             56.29 |         7.1  |             84.98 | short              |               -0.24 |                 -0.18 |                -0.23 |
|     16 | MU       | MU                         | US       |              999.68 |             78.7  |         73.57 |         67.39 |          83.83 |        85.03 |           95.68 |             75.76 |             73.36 |         8.38 |             73.14 | long               |                0.99 |                  1.52 |                 1.22 |
|     17 | HALO     | HALO                       | US       |               11.12 |             78.49 |         81.83 |         81.86 |          75.15 |        71.75 |           84.86 |             53.05 |             50.34 |         6.03 |             72.11 | swing              |              nan    |                nan    |               nan    |
|     18 | DAR      | DAR                        | US       |                8.99 |             78.46 |         68.13 |         75.88 |          81.04 |        83.97 |           92.39 |             86.06 |             65.83 |         4.68 |             71.32 | long               |                1.13 |                nan    |               nan    |
|     19 | REP.MC   | REP.MC                     | EUROPE   |               31.55 |             77.94 |         80.86 |         81.62 |          75.02 |        71.95 |           58.79 |             78.97 |             74.62 |         3.78 |             73.14 | swing              |                1.05 |                  0.23 |                -0.12 |
|     20 | AVAH     | AVAH                       | US       |                2.6  |             77.68 |         76.88 |         82.18 |          78.48 |        73.47 |           93.06 |             56.25 |             39.92 |         7.87 |             72.11 | swing              |               -1.15 |                 -1.06 |                -1.05 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.03 |                  76.12 |                    75.74 |                 77.24 |              76.3  |                86.76 |                   13.24 |           84.64 |             58.75 |       0.863 |         nan |       nan |      nan    |       -78.9  |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI       | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  65.67 |                    72.63 |                 75.89 |              69.44 |                85.4  |                   14.6  |           93.42 |             67.81 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                  75.46 |                    71.59 |                 72.08 |              74.03 |                64.73 |                   35.27 |           65.35 |             80.46 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              235.97 |                  59.16 |                    71.41 |                 75.31 |              66.65 |                87.77 |                   12.23 |           92.56 |             82.55 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | BBWI      | Bath & Body Works, Inc.              | US       |                3.06 |                  75.58 |                    71.18 |                 68.69 |              70.39 |                69.52 |                   30.48 |           76.3  |             34.53 |       0.218 |         nan |       nan |        5.67 |         6.24 |          4.57 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|            5 | NVDA      | NVIDIA Corporation                   | US       |             4676.83 |                  60.87 |                    70.72 |                 72.7  |              65.8  |                77.32 |                   22.68 |           86.5  |             80.56 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|            6 | SAP.DE    | SAP SE                               | EUROPE   |              213.34 |                  70.21 |                    70.5  |                 70.08 |              67.69 |                68.62 |                   31.38 |           84.06 |             47.87 |       0.043 |         nan |       nan |       17.87 |        22.1  |         27.67 |        1.6  |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                                   | US       |                7.66 |                  64.18 |                    69.78 |                 72.03 |              67.04 |                71.99 |                   28.01 |           82.18 |             78.72 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                3.27 |                  58.36 |                    69.72 |                 73.54 |              65.19 |                82.15 |                   17.85 |           89.53 |             83.81 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                5.1  |                  57.21 |                    69.66 |                 73.88 |              64.07 |                84.46 |                   15.54 |           95.8  |             76.75 |     nan     |         nan |       nan |      nan    |         9.73 |          6.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC      | Embecta Corp.                        | US       |                0.26 |                  71.15 |                    68.66 |                 68.87 |              69.4  |                65.29 |                   34.71 |           69.73 |             64.22 |       0.461 |         nan |       nan |        5.64 |         3    |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | STNE      | StoneCo Ltd.                         | OTHER    |                1.91 |                  71.4  |                    68.52 |                 68.03 |              66.6  |                66.05 |                   33.95 |           84.18 |             32.99 |       0.629 |         nan |       nan |        1.61 |         4.17 |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  73.59 |                    68.49 |                 68.83 |              69.79 |                68.85 |                   31.15 |           75.04 |             44.15 |       0.612 |         nan |       nan |        4.33 |      -133.79 |          2.3  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1487.53 |                  60.81 |                    68.27 |                 68.87 |              62.34 |                78.38 |                   21.62 |           92.29 |             44.49 |       0.018 |         nan |       nan |       33.34 |        18.45 |         45.67 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|           11 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.23 |                  68.63 |                    67.63 |                 66.81 |              68.89 |                69.96 |                   30.04 |           61.65 |            nan    |       0.229 |         nan |       nan |        1.54 |       nan    |          3.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               59.69 |                  72.04 |                    67.6  |                 65.52 |              68.46 |                61.96 |                   38.04 |           62.63 |             54.34 |       0.036 |         nan |       nan |       15.86 |        13.3  |         18.79 |        0.97 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                                  | US       |              112.25 |                  61.05 |                    67.53 |                 69.63 |              64.52 |                76.82 |                   23.18 |           82.12 |             67.36 |     nan     |         nan |       nan |      nan    |         9.61 |         13.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                                  | US       |                9.97 |                  55.12 |                    67.42 |                 71.68 |              62.09 |                80.16 |                   19.84 |           91.53 |             79.78 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EOG       | EOG                                  | US       |               65.92 |                  59.1  |                    67.36 |                 70.05 |              64.06 |                77.68 |                   22.32 |           82.09 |             75.24 |     nan     |         nan |       nan |      nan    |         9.74 |         11.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.99 |                  54.56 |                    67.3  |                 71.46 |              61.34 |                85.08 |                   14.92 |           96.14 |             67.43 |     nan     |         nan |       nan |      nan    |        10.98 |         14.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.03 |                  76.12 |                    75.74 |                 77.24 |              76.3  |                86.76 |                   13.24 |           84.64 |             58.75 |       0.863 |         nan |       nan |      nan    |       -78.9  |          2.11 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  65.67 |                    72.63 |                 75.89 |              69.44 |                85.4  |                   14.6  |           93.42 |             67.81 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                  59.16 |                    71.41 |                 75.31 |              66.65 |                87.77 |                   12.23 |           92.56 |             82.55 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.1  |                  57.21 |                    69.66 |                 73.88 |              64.07 |                84.46 |                   15.54 |           95.8  |             76.75 |     nan     |         nan |       nan |      nan    |         9.73 |          6.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.27 |                  58.36 |                    69.72 |                 73.54 |              65.19 |                82.15 |                   17.85 |           89.53 |             83.81 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4676.83 |                  60.87 |                    70.72 |                 72.7  |              65.8  |                77.32 |                   22.68 |           86.5  |             80.56 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                  75.46 |                    71.59 |                 72.08 |              74.03 |                64.73 |                   35.27 |           65.35 |             80.46 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                7.66 |                  64.18 |                    69.78 |                 72.03 |              67.04 |                71.99 |                   28.01 |           82.18 |             78.72 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.97 |                  55.12 |                    67.42 |                 71.68 |              62.09 |                80.16 |                   19.84 |           91.53 |             79.78 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.99 |                  54.56 |                    67.3  |                 71.46 |              61.34 |                85.08 |                   14.92 |           96.14 |             67.43 |     nan     |         nan |       nan |      nan    |        10.98 |         14.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |              103.97 |                  52.5  |                    66.25 |                 70.62 |              61.7  |                82.86 |                   17.14 |           84.35 |             89.86 |     nan     |         nan |       nan |      nan    |         9.79 |         14.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | SAP.DE   | SAP SE                               | EUROPE   |              213.34 |                  70.21 |                    70.5  |                 70.08 |              67.69 |                68.62 |                   31.38 |           84.06 |             47.87 |       0.043 |         nan |       nan |       17.87 |        22.1  |         27.67 |        1.6  |                 nan |              nan |                  12 |                  0.63 |
|          nan | EOG      | EOG                                  | US       |               65.92 |                  59.1  |                    67.36 |                 70.05 |              64.06 |                77.68 |                   22.32 |           82.09 |             75.24 |     nan     |         nan |       nan |      nan    |         9.74 |         11.22 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              112.25 |                  61.05 |                    67.53 |                 69.63 |              64.52 |                76.82 |                   23.18 |           82.12 |             67.36 |     nan     |         nan |       nan |      nan    |         9.61 |         13.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.04 |                  59.24 |                    66.49 |                 69.08 |              62.61 |                74.66 |                   25.34 |           85.76 |             65.22 |     nan     |         nan |       nan |      nan    |         9.13 |         21.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY                                  | US       |               51.25 |                  52.68 |                    64.86 |                 68.91 |              60.24 |                78.29 |                   21.71 |           84.53 |             82.22 |     nan     |         nan |       nan |      nan    |        14.58 |         17.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.26 |                  71.15 |                    68.66 |                 68.87 |              69.4  |                65.29 |                   34.71 |           69.73 |             64.22 |       0.461 |         nan |       nan |        5.64 |         3    |          3.6  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1487.53 |                  60.81 |                    68.27 |                 68.87 |              62.34 |                78.38 |                   21.62 |           92.29 |             44.49 |       0.018 |         nan |       nan |       33.34 |        18.45 |         45.67 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|            9 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  73.59 |                    68.49 |                 68.83 |              69.79 |                68.85 |                   31.15 |           75.04 |             44.15 |       0.612 |         nan |       nan |        4.33 |      -133.79 |          2.3  |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           17 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                  61.91 |                    66.21 |                 68.82 |              64.46 |                68.07 |                   31.93 |           77.17 |             76.34 |       0.019 |         nan |       nan |        4.07 |         6.1  |          4.95 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | DELL     | DELL                                 | US       |              314.72 |                     0.03 |     0    |      0.31 |                  57.79 |                        80.86 |         89.35 |         87.47 |          81.45 |        68.89 |           73.47 |             85.5  |         7.91 |
|               2 | BE       | BE                                   | US       |               68.17 |                     0.05 |    -0.04 |      0.31 |                  80.85 |                        79.7  |         76.73 |         61.1  |          71.66 |        63.28 |           86.36 |             79.61 |         9.23 |
|               3 | AVAH     | AVAH                                 | US       |                2.6  |                     0.05 |    -0.03 |      0.05 |                  75.84 |                        79.51 |         76.88 |         82.18 |          78.48 |        73.47 |           93.06 |             56.25 |         7.87 |
|               4 | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                     0.03 |    -0.01 |      0.04 |                  61.22 |                        78.83 |         77.5  |         75.66 |          75.12 |        81.05 |           92.56 |             82.55 |         2.46 |
|               5 | DAR      | DAR                                  | US       |                8.99 |                     0.03 |     0    |     -0.04 |                  57.06 |                        77.88 |         68.13 |         75.88 |          81.04 |        83.97 |           92.39 |             86.06 |         4.68 |
|               6 | CRGY     | CRGY                                 | US       |                4.76 |                     0.1  |    -0.05 |      0.01 |                  60.8  |                        76.86 |         68.57 |         79.56 |          80.34 |        84.43 |           72.53 |             89.73 |         6.58 |
|               7 | ARGX.BR  | ARGX.BR                              | EUROPE   |               53.85 |                     0.05 |    -0    |      0    |                  68.67 |                        76.78 |         68.87 |         72.97 |          71.35 |        62.71 |           92.95 |             76.05 |         6.24 |
|               8 | TALO     | TALO                                 | US       |                2.47 |                     0.07 |    -0.04 |     -0.04 |                  71.35 |                        76.46 |         60.91 |         76.03 |          77.13 |        76.43 |           67.97 |             94.32 |         5.82 |
|               9 | HPE      | HPE                                  | US       |               70.28 |                     0.02 |    -0.02 |      0.15 |                  54.04 |                        76.04 |         84.23 |         84.2  |          80.24 |        72.26 |           73.81 |             73.75 |         7.1  |
|              10 | NVDA     | NVIDIA Corporation                   | US       |             4676.83 |                     0.03 |     0.02 |      0.03 |                  52.54 |                        75.78 |         77.03 |         68.57 |          69.3  |        68.6  |           86.5  |             80.56 |         5.86 |
|              11 | SM       | SM                                   | US       |                7.66 |                     0.1  |    -0.03 |     -0.01 |                  48.76 |                        75.4  |         65.95 |         79.68 |          82.52 |        86.29 |           82.18 |             78.72 |         7.18 |
|              12 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                     0.02 |    -0    |      0.16 |                  52.92 |                        75.32 |         80.99 |         80.64 |          77    |        72.81 |           77.17 |             76.34 |         7.1  |
|              13 | PR       | PR                                   | US       |               16.61 |                     0.06 |    -0.04 |     -0.04 |                  75.61 |                        74.94 |         59.3  |         73.05 |          75.64 |        77.51 |           77.34 |             77.35 |         4.61 |
|              14 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.28 |                     0.04 |    -0.02 |      0.14 |                  64.94 |                        74.59 |         79.43 |         75.89 |          71.66 |        74.61 |           65.35 |             80.46 |         3.85 |
|              15 | FSM      | FSM                                  | US       |                3.08 |                     0.07 |    -0    |      0    |                  64.29 |                        73.68 |         67.99 |         75.32 |          76.99 |        80.18 |           78.87 |             70.66 |         7.39 |
|              16 | WT       | WT                                   | US       |                3.05 |                     0.08 |    -0.04 |      0.02 |                  66.66 |                        73.27 |         66.52 |         76.14 |          74.27 |        65.72 |           74.15 |             69.19 |         6.04 |
|              17 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.8  |                     0.04 |    -0.02 |      0.13 |                  69.87 |                        73.12 |         78.34 |         72.35 |          68.46 |        71.45 |           65.35 |             69.31 |         4.55 |
|              18 | MT.AS    | MT.AS                                | EUROPE   |               47.73 |                     0.06 |     0.01 |      0.01 |                  64.03 |                        73.1  |         67.94 |         74.98 |          77.97 |        74.82 |           68.58 |             81.9  |         5.14 |
|              19 | OXY      | OXY                                  | US       |               51.25 |                     0.07 |    -0.04 |     -0.04 |                  71.7  |                        72.52 |         54.48 |         65.06 |          69.65 |        74.12 |           84.53 |             82.22 |         5.16 |
|              20 | OSCR     | OSCR                                 | US       |                8.64 |                     0.05 |    -0.02 |      0.02 |                  73.24 |                        72.39 |         69.06 |         76.01 |          74.07 |        61.97 |           52.92 |             85.44 |         8.3  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.98 |             41.69 |         40.32 |         35.09 |          43.07 |        50.08 |           77.39 |             45.46 |                26 |         3.32 |              89.8 | long               |               -0.39 |                  0.07 |                 0.16 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    346 | ABSI     | ABSI   | US       |                1.44 |             57.09 |         67.54 |         63    |          51.18 |        31.5  |            3.81 |             40.13 |             21.93 |         9.27 |             69.27 | short              |                0.83 |                  3.55 |                 3.29 |
|    309 | VSAT     | VSAT   | US       |                9.17 |             58.47 |         65.7  |         61.45 |          55.48 |        40.03 |           26.17 |             58.4  |             14.65 |         7.84 |             73.14 | short              |                0.52 |                  2.85 |               nan    |
|     30 | FSM      | FSM    | US       |                3.08 |             76.15 |         67.99 |         75.32 |          76.99 |        80.18 |           78.87 |             70.66 |             83.82 |         7.39 |             73.14 | long               |               10.67 |                  2.84 |                 2.47 |
|    178 | INTC     | INTC   | US       |              500.23 |             63.98 |         77.77 |         61.75 |          66.22 |        49.48 |           45.41 |             85.56 |             11.77 |         8.3  |             73.14 | short              |                0.17 |                  2.84 |               nan    |
|     77 | SBSW     | SBSW   | US       |                7.35 |             70.1  |         68.83 |         70.95 |          69.25 |        72.45 |           57.44 |             92.3  |             82.61 |         8.46 |             69.68 | long               |                0.73 |                  2.79 |                 2.37 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    555 | PTEN     | PTEN                       | US       |                3.91 |             47.83 |         46.85 |         54.09 |          48.81 |        41.19 |           26.81 |             41.77 |             27.23 |         7.25 |             73.14 | swing              |                0.58 |                 -3.78 |                -3.16 |
|    562 | EGY      | EGY                        | US       |                0.56 |             47.43 |         60.36 |         50.41 |          44.46 |        41.07 |           34.01 |             37.97 |             26.45 |         5.75 |             69.68 | short              |              nan    |                 -2.83 |                -2.46 |
|    295 | BTE      | BTE                        | US       |                2.95 |             58.95 |         60.83 |         62.21 |          57.07 |        52.28 |           40.89 |             50.76 |             43.79 |         5.73 |             69.68 | swing              |                0.64 |                 -2.69 |                -2.36 |
|    614 | DEC      | Diversified Energy Company | US       |                0.83 |             43.61 |         36.16 |         41.22 |          46.01 |        56.75 |           64.54 |             32.93 |             62.93 |         5.6  |             82.82 | long               |                5.11 |                 -2.53 |                -1.62 |
|    411 | NOG      | NOG                        | US       |                2.33 |             53.99 |         42.54 |         61.34 |          52.77 |        55.22 |           17.92 |             71.26 |             92.35 |         7.37 |             68.2  | swing              |              nan    |                 -2.51 |                -2.05 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
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
- Excluded by hard/data filters: **287**
- Event watch (otherwise eligible): **1**
- Final eligible: **712**
- Eligible change vs previous stored run: **-1**

Top exclusion categories:
- liquidity: 230
- price: 180
- market_cap: 150
- price_history: 19
- data_confidence: 11
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| NVDA | 91 | 5 | 10 | 3 | 2 | value,pullback,quality_value |
| DELL | 5 |  | 1 |  | 2 | main,pullback |
| HPE | 9 |  | 9 |  | 2 | main,pullback |
| PBR-A | 33 | 3 | 14 | 4 | 1 | value,quality_value |
| DDI | 56 | 2 | 34 | 2 | 1 | value,quality_value |
| BION.SW | 166 | 1 | 90 | 1 | 1 | value,quality_value |
| SAP.DE | 206 | 6 | 66 | 5 | 1 | value,quality_value |
| EMBC | 251 | 7 |  | 6 | 1 | value,quality_value |
| NWL.MI | 259 | 9 |  | 8 | 1 | value,quality_value |
| AVGO | 394 | 10 | 113 | 7 | 1 | value,quality_value |
| BBWI | 635 | 4 | 339 | 10 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| DHT | 3 |  |  |  | 1 | main |
| CMBT.BR | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (MPC, FRO, DHT, CMBT.BR, SB, NAT, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SHELL.AS, CRGY)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.32 | 76.12 | 54.26 | 84.64 | 58.75 | 86.76 | 64.44 |
| 2 | PBR-A | value+pullback | 69.67 | 75.46 | 64.94 | 65.35 | 80.46 | 64.73 | 75.25 |
| 3 | DDI | value+pullback | 68.99 | 65.67 | 45.68 | 93.42 | 67.81 | 85.40 | 72.53 |
| 4 | STNE | value+pullback | 68.35 | 71.40 | 71.20 | 84.18 | 32.99 | 66.05 | 46.10 |
| 5 | AVGO | value+pullback | 68.09 | 60.81 | 63.52 | 92.29 | 44.49 | 78.38 | 54.76 |
| 6 | NVDA | value+pullback | 67.89 | 60.87 | 52.54 | 86.50 | 80.56 | 77.32 | 68.95 |
| 7 | 0Q2N.IL | value+pullback | 67.49 | 68.63 | 74.66 | 61.65 |  | 69.96 | 66.56 |
| 8 | SAP.DE | value+pullback | 67.27 | 70.21 | 60.36 | 84.06 | 47.87 | 68.62 | 62.78 |
| 9 | VOLV-B.ST | value+pullback | 67.04 | 72.04 | 72.85 | 62.63 | 54.34 | 61.96 | 56.07 |
| 10 | PBR | value+pullback | 66.14 | 65.16 | 69.87 | 65.35 | 69.31 | 61.95 | 71.90 |
| 11 | BBWI | value+pullback | 65.55 | 75.58 | 56.31 | 76.30 | 34.53 | 69.52 | 41.04 |
| 12 | RCI | value+pullback | 64.80 | 61.25 | 71.98 | 84.40 | 43.23 | 57.24 | 47.46 |
| 13 | PARR | value+pullback | 64.63 | 61.91 | 52.92 | 77.17 | 76.34 | 68.07 | 78.82 |
| 14 | SDF.DE | value+pullback | 64.27 | 57.40 | 74.11 | 77.43 | 41.38 | 63.86 | 60.70 |
| 15 | UNIT | value+pullback | 64.14 | 80.01 | 74.52 | 64.98 | 29.11 | 44.25 | 41.02 |
| 16 | BCE | value+pullback | 63.31 | 57.11 | 79.05 | 68.54 | 57.76 | 51.77 | 44.27 |
| 17 | BHF | value+pullback | 62.10 | 70.59 | 57.69 | 51.67 | 55.46 | 66.01 | 43.21 |
| 18 | JD | value+pullback | 61.30 | 68.72 | 54.75 | 65.87 | 46.98 | 62.10 | 44.15 |
| 19 | MFA | value+pullback | 61.09 | 58.14 | 70.89 | 76.63 | 26.49 | 58.91 | 38.81 |
| 20 | AMCX | value+pullback | 61.05 | 64.18 | 56.39 | 47.83 | 66.98 | 69.13 | 62.90 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 3 / 7 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 73.1 | 6 / 19 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.5 | 17 / 33 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=3, large_20_100b=1, mega_100b_plus=2
