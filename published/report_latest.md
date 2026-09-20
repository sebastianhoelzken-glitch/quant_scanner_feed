# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-20

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

- **EUROPE:** 78.0/100
- **OTHER:** 64.7/100
- **US:** 79.4/100

## Main multi-horizon ranking

|   rank | symbol   | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC                                  | US       |              107.95 |             87.03 |         86.97 |         92.28 |          87.1  |        80.37 |           83.99 |             90.18 |             59.03 |         3.95 |             73.14 | swing              |                3.64 |                 -0.04 |               nan    |
|      2 | FRO      | FRO                                  | US       |                9.96 |             86.18 |         87.7  |         87.64 |          84.71 |        80.09 |           90.96 |             80.31 |             54.16 |         5.52 |             73.14 | short              |                3.66 |                 -0.03 |                -0.31 |
|      3 | VLO      | VLO                                  | US       |              103.56 |             85.98 |         87.23 |         89.97 |          84.73 |        78.24 |           84.91 |             82.39 |             53.35 |         3.36 |             69.68 | swing              |              nan    |                  0.02 |               nan    |
|      4 | PSX      | PSX                                  | US       |               94.85 |             84.95 |         86.62 |         89.3  |          83.27 |        76.46 |           78.61 |             86.7  |             55.16 |         3.57 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      5 | DHT      | DHT                                  | US       |                3.27 |             84.58 |         87.36 |         86.3  |          82.86 |        79.82 |           87.73 |             83.91 |             57.79 |         4.68 |             73.14 | short              |                4.39 |                 -0.2  |                -0.8  |
|      6 | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.12 |             84.17 |         87.02 |         84.03 |          84.31 |        81.24 |           96.1  |             77.21 |             57.08 |         3.9  |             69.89 | short              |               -0.48 |                  0.17 |                -0.06 |
|      7 | DK       | DK                                   | US       |                4.16 |             83.92 |         89.85 |         88.08 |          79.76 |        68.54 |           56.39 |             93.68 |             53.96 |         7.35 |             73.14 | short              |                4.46 |                 -0.07 |                -0.4  |
|      8 | DELL     | DELL                                 | US       |              314.33 |             83.71 |         89.27 |         86.83 |          80.58 |        67.45 |           72.12 |             85.9  |             30.53 |         7.92 |             72.23 | short              |                6.97 |                  0.34 |                -0.46 |
|      9 | SB       | SB                                   | US       |                0.91 |             81.9  |         89.38 |         84.95 |          78.84 |        72.97 |           68.54 |             82.27 |             60.8  |         4.31 |             69.09 | short              |                3.73 |                  1.33 |                 0.74 |
|     10 | NAT      | NAT                                  | US       |                1.52 |             81.81 |         86.53 |         84.54 |          79.07 |        71.57 |           86.21 |             69.75 |             33.87 |         4.93 |             73.14 | short              |                4.28 |                 -0.06 |                -0.33 |
|     11 | PBF      | PBF                                  | US       |                7.96 |             81.53 |         82.44 |         87.32 |          80.63 |        75.05 |           52.54 |             88.35 |             86.05 |         7.77 |             72.68 | swing              |                3.87 |                  1.87 |                 1.2  |
|     12 | DINO     | DINO                                 | US       |               17.93 |             81.53 |         84.54 |         88.85 |          78.51 |        68.15 |           49.1  |             87.24 |             67.29 |         4.39 |             73.14 | swing              |                3.72 |                 -0    |                -0.48 |
|     13 | HPE      | HPE                                  | US       |               70.2  |             81.43 |         83.85 |         83.59 |          79.27 |        70.62 |           72.03 |             73.87 |             50.15 |         7.08 |             72.34 | short              |                3.9  |                  1.38 |                 1.01 |
|     14 | SM       | SM                                   | US       |                7.65 |             80.03 |         65.18 |         78.79 |          81.26 |        84.25 |           80.61 |             79.26 |             91.25 |         7.15 |             72.11 | long               |                3.45 |                 -1.07 |                -1.17 |
|     15 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |             79.06 |         80.44 |         80.05 |          78.06 |        76.23 |           81.16 |             76.63 |             66    |         7.03 |             84.98 | short              |                2.96 |                  0.11 |                 0.06 |
|     16 | AVAH     | AVAH                                 | US       |                2.6  |             78.84 |         77.68 |         83.77 |          80    |        73.67 |           92.3  |             66.38 |             37.65 |         7.81 |             72.11 | swing              |                2.77 |                 -0.88 |                -0.93 |
|     17 | CRGY     | CRGY                                 | US       |                4    |             78.73 |         67.96 |         78.59 |          78.87 |        82.22 |           70.47 |             90.46 |             90.81 |         6.55 |             72.68 | long               |                4.01 |                 -0.96 |                -1.27 |
|     18 | KIN.BR   | KIN.BR                               | EUROPE   |                1.33 |             78.37 |         84.44 |         81.6  |          75.13 |        65.85 |           89.7  |             66.25 |             19.15 |         3.86 |             73.14 | short              |               -0.18 |                 -0.73 |                -1    |
|     19 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.14 |             77.79 |         79.42 |         76.15 |          73.6  |        79.45 |           70.06 |             80.54 |             91.54 |         3.7  |             84.47 | long               |                4.01 |                  0.96 |                 0.25 |
|     20 | MU       | MU                                   | US       |              998.44 |             77.71 |         72.82 |         66.28 |          82.61 |        83.47 |           95.18 |             73.73 |             70.22 |         8.35 |             73.14 | long               |                2.88 |                  1.03 |                 0.58 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.14 |                  85.55 |                    78.61 |                 78.56 |              82.21 |                69.78 |                   30.22 |           70.06 |             80.54 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  66.63 |                    73.63 |                 77    |              70.39 |                86.21 |                   13.79 |           94.95 |             68.99 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.44 |                  80.7  |                    72.62 |                 71.19 |              74.63 |                74.59 |                   25.41 |           76.15 |             30.98 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.47 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            4 | INVA     | Innoviva, Inc.                       | US       |                1.33 |                  74.72 |                    72.31 |                 73.1  |              71.7  |                82.32 |                   17.68 |           90    |             30.85 |       0.072 |         nan |       nan |        6.55 |         9.57 |          4.9  |        0.25 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                  59.69 |                    72.05 |                 75.99 |              67.21 |                88.51 |                   11.49 |           93.64 |             82.99 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | BBWI     | Bath & Body Works, Inc.              | US       |                3.05 |                  76.64 |                    71.15 |                 68.98 |              69.69 |                61.08 |                   38.92 |           80.25 |             35.12 |       0.218 |         nan |       nan |        5.67 |         6.24 |          4.57 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4671.03 |                  60.87 |                    70.92 |                 73    |              65.92 |                77.67 |                   22.33 |           87.17 |             81.07 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.12 |                  58.1  |                    70.35 |                 74.5  |              64.85 |                84.97 |                   15.03 |           96.1  |             77.21 |     nan     |         nan |       nan |      nan    |         9.76 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                  67.1  |                    69.15 |                 71.65 |              67.58 |                64.48 |                   35.52 |           81.16 |             76.63 |       0.019 |         nan |       nan |        4.07 |         6.1  |          4.95 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                                  | US       |                3.27 |                  57.95 |                    69.09 |                 72.81 |              64.77 |                81.4  |                   18.6  |           87.73 |             83.91 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              175.22 |                  64.46 |                    68.46 |                 69.54 |              67.72 |                74.58 |                   25.42 |           70.06 |             78.83 |     nan     |         nan |       nan |      nan    |         8.9  |         11.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.66 |                  69.18 |                    68.3  |                 69.03 |              68.75 |                66.84 |                   33.16 |           70.06 |             69.06 |       0.137 |         nan |       nan |        1.84 |         5.22 |          5.25 |        5.96 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM       | SM                                   | US       |                7.65 |                  61.95 |                    68.21 |                 70.63 |              65.39 |                71.44 |                   28.56 |           80.61 |             79.26 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | AVGO     | Broadcom Inc.                        | US       |             1485.69 |                  60.81 |                    68.16 |                 68.71 |              62.24 |                78.29 |                   21.71 |           92.17 |             43.7  |       0.018 |         nan |       nan |       33.34 |        18.45 |         45.67 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|           10 | CNX      | CNX Resources Corporation            | US       |                4.23 |                  72    |                    67.94 |                 67.39 |              68.25 |                59.9  |                   40.1  |           70.29 |             56.25 |       0.09  |         nan |       nan |        3.96 |         8.48 |          5.33 |        1.93 |                 nan |              nan |                  11 |                  0.58 |
|          nan | FRO      | FRO                                  | US       |                9.96 |                  55.34 |                    67.52 |                 71.72 |              62.31 |                80.18 |                   19.82 |           90.96 |             80.31 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS      | IHS Holding Limited                  | OTHER    |                2.48 |                  71.48 |                    67.48 |                 67.58 |              70.89 |                64.19 |                   35.81 |           55.89 |             78.75 |      -0.114 |         nan |       nan |        7.51 |        15.31 |          5.17 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.08 |                  54.81 |                    67.43 |                 71.56 |              61.47 |                85.01 |                   14.99 |           96.32 |             67.11 |     nan     |         nan |       nan |      nan    |        11.03 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.87 |                  62.18 |                    67.38 |                 69.06 |              63.87 |                77.51 |                   22.49 |           86.94 |             51.46 |     nan     |         nan |       nan |      nan    |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | MOMO     | Hello Group Inc.                     | OTHER    |                0.61 |                  77.86 |                    67.32 |                 64.3  |              70.65 |                67.17 |                   32.83 |           61.76 |             24.97 |       0.86  |         nan |       nan |       -5.97 |         4.72 |          4.83 |        0.89 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.14 |                  85.55 |                    78.61 |                 78.56 |              82.21 |                69.78 |                   30.22 |           70.06 |             80.54 |       0.143 |         nan |       nan |        1.79 |         4.68 |          4.75 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  66.63 |                    73.63 |                 77    |              70.39 |                86.21 |                   13.79 |           94.95 |             68.99 |       0.154 |         nan |       nan |        0.76 |         5.23 |          5.06 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                  59.69 |                    72.05 |                 75.99 |              67.21 |                88.51 |                   11.49 |           93.64 |             82.99 |     nan     |         nan |       nan |      nan    |         9.43 |         10.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.12 |                  58.1  |                    70.35 |                 74.5  |              64.85 |                84.97 |                   15.03 |           96.1  |             77.21 |     nan     |         nan |       nan |      nan    |         9.76 |          6.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | INVA     | Innoviva, Inc.                       | US       |                1.33 |                  74.72 |                    72.31 |                 73.1  |              71.7  |                82.32 |                   17.68 |           90    |             30.85 |       0.072 |         nan |       nan |        6.55 |         9.57 |          4.9  |        0.25 |                 nan |              nan |                  11 |                  0.58 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4671.03 |                  60.87 |                    70.92 |                 73    |              65.92 |                77.67 |                   22.33 |           87.17 |             81.07 |       0.008 |         nan |       nan |       26.5  |        14.17 |         28.1  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.27 |                  57.95 |                    69.09 |                 72.81 |              64.77 |                81.4  |                   18.6  |           87.73 |             83.91 |     nan     |         nan |       nan |      nan    |        10.85 |          7.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.96 |                  55.34 |                    67.52 |                 71.72 |              62.31 |                80.18 |                   19.82 |           90.96 |             80.31 |     nan     |         nan |       nan |      nan    |        11.23 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                  67.1  |                    69.15 |                 71.65 |              67.58 |                64.48 |                   35.52 |           81.16 |             76.63 |       0.019 |         nan |       nan |        4.07 |         6.1  |          4.95 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.08 |                  54.81 |                    67.43 |                 71.56 |              61.47 |                85.01 |                   14.99 |           96.32 |             67.11 |     nan     |         nan |       nan |      nan    |        11.03 |         14.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.44 |                  80.7  |                    72.62 |                 71.19 |              74.63 |                74.59 |                   25.41 |           76.15 |             30.98 |       0.078 |         nan |       nan |        3.93 |         5.17 |          4.47 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | MPC      | MPC                                  | US       |              107.95 |                  52.78 |                    66.42 |                 70.73 |              61.96 |                83    |                   17    |           83.99 |             90.18 |     nan     |         nan |       nan |      nan    |         9.79 |         14.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.65 |                  61.95 |                    68.21 |                 70.63 |              65.39 |                71.44 |                   28.56 |           80.61 |             79.26 |     nan     |         nan |       nan |      nan    |         4.71 |          6.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |              103.56 |                  52.61 |                    65.51 |                 69.58 |              60.9  |                82.12 |                   17.88 |           84.91 |             82.39 |     nan     |         nan |       nan |      nan    |        11.07 |         17.24 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              175.22 |                  64.46 |                    68.46 |                 69.54 |              67.72 |                74.58 |                   25.42 |           70.06 |             78.83 |     nan     |         nan |       nan |      nan    |         8.9  |         11.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.87 |                  62.18 |                    67.38 |                 69.06 |              63.87 |                77.51 |                   22.49 |           86.94 |             51.46 |     nan     |         nan |       nan |      nan    |         8.83 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.66 |                  69.18 |                    68.3  |                 69.03 |              68.75 |                66.84 |                   33.16 |           70.06 |             69.06 |       0.137 |         nan |       nan |        1.84 |         5.22 |          5.25 |        5.96 |                 nan |              nan |                  12 |                  0.63 |
|            5 | BBWI     | Bath & Body Works, Inc.              | US       |                3.05 |                  76.64 |                    71.15 |                 68.98 |              69.69 |                61.08 |                   38.92 |           80.25 |             35.12 |       0.218 |         nan |       nan |        5.67 |         6.24 |          4.57 |        0.71 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.42 |                  55.08 |                    65.39 |                 68.89 |              59.54 |                80.27 |                   19.73 |           95.67 |             54.33 |     nan     |         nan |       nan |      nan    |        11.75 |         12.02 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              112.11 |                  61.3  |                    66.92 |                 68.71 |              64.36 |                75.36 |                   24.64 |           79.33 |             66.61 |     nan     |         nan |       nan |      nan    |         9.61 |         13.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | AVAH     | AVAH                                 | US       |                2.6  |                     0.05 |    -0.03 |      0.05 |                  75.84 |                        81.68 |         77.68 |         83.77 |          80    |        73.67 |           92.3  |             66.38 |         7.81 |
|               2 | DELL     | DELL                                 | US       |              314.33 |                     0.03 |     0    |      0.31 |                  57.79 |                        80.61 |         89.27 |         86.83 |          80.58 |        67.45 |           72.12 |             85.9  |         7.92 |
|               3 | SHELL.AS | SHELL.AS                             | EUROPE   |              235.97 |                     0.03 |    -0    |      0.04 |                  56.82 |                        79.22 |         79.05 |         74.82 |          74.52 |        79.48 |           93.64 |             82.99 |         2.43 |
|               4 | BE       | BE                                   | US       |               68.09 |                     0.05 |    -0.04 |      0.31 |                  80.85 |                        79.13 |         76.04 |         60.46 |          70.99 |        62.63 |           85.04 |             79.81 |         9.16 |
|               5 | DAR      | DAR                                  | US       |                8.98 |                     0.03 |     0    |     -0.04 |                  57.06 |                        77.03 |         68.09 |         74.98 |          79.67 |        82.06 |           90.09 |             86.43 |         4.6  |
|               6 | NVDA     | NVIDIA Corporation                   | US       |             4671.03 |                     0.03 |     0.02 |      0.03 |                  52.54 |                        76.32 |         77.69 |         69.97 |          70.37 |        69.97 |           87.17 |             81.07 |         5.8  |
|               7 | CRGY     | CRGY                                 | US       |                4    |                     0.1  |    -0.05 |      0.01 |                  60.8  |                        76.08 |         67.96 |         78.59 |          78.87 |        82.22 |           70.47 |             90.46 |         6.55 |
|               8 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.68 |                     0.02 |    -0    |      0.16 |                  52.92 |                        75.89 |         80.44 |         80.05 |          78.06 |        76.23 |           81.16 |             76.63 |         7.03 |
|               9 | TALO     | TALO                                 | US       |                2.47 |                     0.07 |    -0.04 |     -0.04 |                  71.35 |                        75.77 |         60.38 |         75.05 |          75.86 |        74.54 |           66.57 |             94.87 |         5.75 |
|              10 | SRAIL.SW | SRAIL.SW                             | EUROPE   |                3.15 |                     0.05 |     0.01 |      0.23 |                  66.13 |                        75.74 |         83.49 |         72.23 |          65.85 |        60.34 |           79.74 |             54.16 |         5.57 |
|              11 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.14 |                     0.04 |    -0.02 |      0.14 |                  64.94 |                        75.54 |         79.42 |         76.15 |          73.6  |        79.45 |           70.06 |             80.54 |         3.7  |
|              12 | HPE      | HPE                                  | US       |               70.2  |                     0.02 |    -0.02 |      0.15 |                  54.04 |                        75.52 |         83.85 |         83.59 |          79.27 |        70.62 |           72.03 |             73.87 |         7.08 |
|              13 | PR       | PR                                   | US       |               16.59 |                     0.06 |    -0.04 |     -0.04 |                  75.61 |                        74.75 |         58.94 |         72.28 |          74.95 |        76.7  |           78.11 |             77.62 |         4.57 |
|              14 | SM       | SM                                   | US       |                7.65 |                     0.1  |    -0.03 |     -0.01 |                  48.76 |                        74.72 |         65.18 |         78.79 |          81.26 |        84.25 |           80.61 |             79.26 |         7.15 |
|              15 | CIRSA.MC | CIRSA.MC                             | EUROPE   |                3.27 |                     0.02 |     0.01 |      0.38 |                  44.37 |                        74.24 |         84.13 |         79.5  |          68.6  |        67.26 |           83.52 |             58.77 |         5.54 |
|              16 | MT.AS    | MT.AS                                | EUROPE   |               47.49 |                     0.07 |    -0.02 |      0.01 |                  69.99 |                        74.02 |         63.46 |         72.95 |          77.58 |        74.31 |           73.33 |             82.56 |         5.2  |
|              17 | PBR      | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              116.66 |                     0.04 |    -0.02 |      0.13 |                  69.87 |                        74    |         78.29 |         72.08 |          69.59 |        74.58 |           70.06 |             69.06 |         4.49 |
|              18 | C5H.IR   | C5H.IR                               | EUROPE   |                1.64 |                     0.07 |    -0.01 |      0.07 |                  67.68 |                        73.14 |         73.02 |         66.14 |          68.91 |        73.75 |           97.74 |             46.18 |         2.73 |
|              19 | VWS.CO   | VWS.CO                               | EUROPE   |               27.06 |                     0.06 |    -0.04 |     -0.01 |                  82.59 |                        72.58 |         63.46 |         67.04 |          68.17 |        63.46 |           87.25 |             61.49 |         5.99 |
|              20 | WT       | WT                                   | US       |                3.04 |                     0.08 |    -0.04 |      0.02 |                  66.66 |                        72.46 |         65.84 |         75.33 |          73.22 |        64.24 |           72.15 |             69.11 |         6    |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              345.55 |             42.09 |         40.82 |         35.73 |          43.35 |        50.44 |           77.39 |             44.77 |                26 |         3.16 |              89.8 | long               |                3.68 |                 -0.47 |                -0.44 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    263 | 0QXR.IL  | 0QXR.IL                       | OTHER    |               25.94 |             60.06 |         61.55 |         57.48 |          58.57 |        68.8  |           83.33 |            nan    |             60.87 |         9.16 |             61.02 | long               |               -0.5  |                  4.54 |                 4.32 |
|    359 | ABSI     | ABSI                          | US       |                1.44 |             56.26 |         66.54 |         62.06 |          50.46 |        30.65 |            4.41 |             39.02 |             19.5  |         9.19 |             69.27 | short              |                4.07 |                  3.07 |                 2.55 |
|    338 | GAB      | The Gabelli Equity Trust Inc. | US       |                1.62 |             56.99 |         59.04 |         56.9  |          56.15 |        57.08 |           61.55 |             85.5  |             42.28 |         1.84 |             63.74 | short              |                7.12 |                  2.92 |               nan    |
|    149 | GF.SW    | GF.SW                         | EUROPE   |                4.79 |             64.96 |         71.58 |         72.99 |          58.35 |        43.77 |           39.95 |             89.78 |             17.47 |         6.3  |             72.23 | swing              |                2.2  |                  2.86 |               nan    |
|    125 | FTRE     | FTRE                          | US       |                1.65 |             66.35 |         77.97 |         72.55 |          60.14 |        45.01 |           24.92 |             58.63 |             36.1  |         7.99 |             73.14 | short              |                4.1  |                  2.75 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    655 | DEC      | DEC    | US       |                0.83 |             38.51 |         32.31 |         37.03 |          39.99 |        54.27 |           43.02 |              9.18 |             92.55 |         5.64 |             69.89 | long               |                4.54 |                 -3.36 |                -2.35 |
|    664 | VOR      | VOR    | US       |                1.1  |             37.3  |         30.15 |         52.21 |          43.44 |        31.17 |           17.99 |             19.96 |            nan    |         9.45 |             65.11 | swing              |                4.82 |                 -2.97 |                -2.32 |
|    570 | PTEN     | PTEN   | US       |                3.89 |             47.25 |         46.19 |         53.21 |          48.32 |        41.26 |           28.81 |             40.54 |             26.18 |         7.23 |             73.14 | swing              |               -2.51 |                 -2.71 |                -2.27 |
|    514 | U        | U      | US       |               15.86 |             49.54 |         42.7  |         68.35 |          56.39 |        41.61 |           37.47 |             58.26 |             22.08 |         8.39 |             72.11 | swing              |                1.89 |                 -2.58 |                -1.81 |
|    633 | HBAN     | HBAN   | US       |               27.92 |             41.49 |         35.82 |         37.08 |          45.91 |        59.63 |           64.79 |             17.33 |             81.06 |         3.59 |             71.77 | long               |                4.87 |                 -2.49 |                -2.01 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **286**
- Event watch (otherwise eligible): **1**
- Final eligible: **713**
- Eligible change vs previous stored run: **+12**

Top exclusion categories:
- liquidity: 229
- price: 178
- market_cap: 154
- price_history: 20
- data_confidence: 12
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 15 | 7 | 8 | 5 | 2 | value,pullback,quality_value |
| NVDA | 76 | 6 | 6 | 4 | 2 | value,pullback,quality_value |
| DELL | 8 |  | 2 |  | 2 | main,pullback |
| PBR-A | 19 | 1 | 11 | 1 | 1 | value,quality_value |
| PBR | 45 | 8 | 17 | 7 | 1 | value,quality_value |
| DDI | 53 | 2 | 32 | 2 | 1 | value,quality_value |
| GSL | 87 | 3 |  | 6 | 1 | value,quality_value |
| AVGO | 388 | 9 | 126 | 9 | 1 | value,quality_value |
| INVA | 405 | 4 |  | 3 | 1 | value,quality_value |
| BBWI | 634 | 5 | 353 | 8 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| PSX | 4 |  |  |  | 1 | main |
| DHT | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (MPC, FRO, VLO, PSX, DHT, CMBT.BR, SB, NAT)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (SHELL.AS, BE, CRGY, SRAIL.SW)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | PBR-A | value+pullback | 74.42 | 85.55 | 64.94 | 70.06 | 80.54 | 69.78 | 77.79 |
| 2 | DDI | value+pullback | 69.79 | 66.63 | 45.68 | 94.95 | 68.99 | 86.21 | 71.85 |
| 3 | PBR | value+pullback | 69.00 | 69.18 | 69.87 | 70.06 | 69.06 | 66.84 | 73.33 |
| 4 | NVDA | value+pullback | 68.11 | 60.87 | 52.54 | 87.17 | 81.07 | 77.67 | 70.17 |
| 5 | AVGO | value+pullback | 67.98 | 60.81 | 63.52 | 92.17 | 43.70 | 78.29 | 54.97 |
| 6 | EVT | value+pullback | 66.52 | 57.41 | 59.89 | 63.16 | 85.50 | 81.49 | 60.68 |
| 7 | PARR | value+pullback | 66.10 | 67.10 | 52.92 | 81.16 | 76.63 | 64.48 | 79.06 |
| 8 | BBWI | value+pullback | 64.83 | 76.64 | 56.31 | 80.25 | 35.12 | 61.08 | 41.35 |
| 9 | RCI | value+pullback | 64.76 | 60.72 | 71.98 | 84.13 | 44.12 | 57.57 | 46.36 |
| 10 | GAB | value+pullback | 63.93 | 60.69 | 53.82 | 61.55 | 85.50 | 72.39 | 56.99 |
| 11 | BCE | value+pullback | 63.69 | 56.84 | 79.05 | 69.94 | 58.36 | 52.73 | 43.50 |
| 12 | GNW | value+pullback | 63.42 | 64.32 | 81.14 | 29.09 | 85.83 | 54.44 | 60.71 |
| 13 | MFA | value+pullback | 61.92 | 58.30 | 70.89 | 79.80 | 26.21 | 60.57 | 39.19 |
| 14 | AMCX | value+pullback | 61.39 | 64.53 | 56.39 | 49.13 | 67.40 | 69.14 | 64.22 |
| 15 | IRS | value+pullback | 61.20 | 68.13 | 59.35 | 63.84 | 41.03 | 61.19 | 52.58 |
| 16 | KYN | value+pullback | 61.06 | 55.87 | 65.76 | 60.93 | 50.28 | 68.44 | 56.06 |
| 17 | ORC | value+pullback | 59.95 | 58.67 | 61.53 | 76.00 | 35.71 | 59.96 | 39.63 |
| 18 | MAGN | value+pullback | 59.78 | 70.20 | 49.61 | 68.70 | 34.34 | 62.88 | 43.71 |
| 19 | MSFT | value+pullback | 58.54 | 58.21 | 61.68 | 57.83 | 66.57 | 51.63 | 63.12 |
| 20 | WB | value+pullback | 57.88 | 68.07 | 58.41 | 66.03 | 17.94 | 55.79 | 34.88 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 2 / 8 |
| Top 25 | 25/25 | 25/25 | 25/25 | 25/25 | 0/25 | 73.1 | 7 / 18 |
| Top 50 | 50/50 | 50/50 | 49/50 | 49/50 | 0/50 | 72.7 | 14 / 36 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=2, large_20_100b=1, mega_100b_plus=3
