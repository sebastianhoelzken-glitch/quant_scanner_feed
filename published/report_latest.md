# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-17

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

- **EUROPE:** 79.6/100
- **OTHER:** 66.9/100
- **US:** 79.3/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |               10.36 |             87.07 |         88.44 |         88.64 |          85.7  |        81.49 |           92.78 |             78.32 |             56.41 |         5.67 |             73.14 | swing              |                1.48 |                  1.79 |                 1.27 |
|      2 | VLO      | VLO                        | US       |              100.64 |             86.44 |         86.74 |         90.44 |          86.15 |        80.88 |           87.22 |             81.44 |             59.39 |         3.45 |             69.68 | swing              |                0.7  |                  0.38 |               nan    |
|      3 | DHT      | DHT                        | US       |                3.22 |             86.11 |         88.19 |         87.63 |          84.59 |        82.12 |           91.01 |             80.82 |             61.74 |         4.78 |             73.14 | short              |                2.54 |                  1.94 |                 1.06 |
|      4 | CMBT.BR  | CMBT.BR                    | EUROPE   |                5.01 |             85.97 |         86.38 |         86.44 |          85.57 |        83.16 |           96.29 |             75.6  |             61.79 |         4.02 |             73.14 | swing              |                4.26 |                  2.52 |                 1.77 |
|      5 | DELL     | DELL                       | US       |              310.42 |             84.29 |         91.83 |         87.53 |          81.04 |        69.22 |           75.1  |             81.12 |             33.98 |         7.94 |             72.23 | short              |                2.2  |                  0.86 |                -0.17 |
|      6 | SM       | SM                         | US       |                7.87 |             84.14 |         81.67 |         84.29 |          83.99 |        87.14 |           83.12 |             81.1  |             96.1  |         7.24 |             72.11 | long               |               -2.92 |                  0.29 |                -0.65 |
|      7 | AVAH     | AVAH                       | US       |                2.7  |             83.75 |         87.58 |         86.48 |          81.01 |        75.08 |           94.38 |             67.05 |             38.12 |         7.89 |             72.11 | short              |                0.78 |                  2.06 |                 1.57 |
|      8 | CRGY     | CRGY                       | US       |                4.91 |             83.41 |         83.71 |         83.11 |          81.07 |        84.32 |           72.61 |             89.26 |             94.93 |         6.64 |             69.23 | long               |               -1.87 |                 -0.05 |                -0.81 |
|      9 | NAT      | NAT                        | US       |                1.47 |             82.76 |         87.57 |         85.26 |          80.26 |        73.86 |           88.75 |             67.37 |             38.72 |         5.09 |             73.14 | short              |                1.09 |                  1.37 |                 0.86 |
|     10 | DINO     | DINO                       | US       |               17.56 |             82.05 |         84.22 |         89.59 |          79.87 |        70.63 |           51.08 |             86.27 |             72.96 |         4.53 |             73.14 | swing              |                0.86 |                  0.55 |                -0.17 |
|     11 | PARR     | Par Pacific Holdings, Inc. | US       |                3.69 |             80.33 |         80.22 |         82.98 |          80.43 |        76.09 |           80.43 |             76.48 |             60.5  |         7.17 |             84.98 | swing              |                0.6  |                  0.26 |                -0.55 |
|     12 | SB       | SB                         | US       |                0.77 |             79.9  |         84.73 |         81.64 |          78.17 |        74.14 |           69.9  |             74.17 |             66.53 |         4.38 |             68.89 | short              |                3.71 |                  1.87 |                 1.18 |
|     13 | PBF      | PBF                        | US       |                7.8  |             79.65 |         74.66 |         86.35 |          82.08 |        77.23 |           53.75 |             87.14 |             91.94 |         7.85 |             72.68 | swing              |                0.57 |                 -0.22 |                -1.09 |
|     14 | TALO     | TALO                       | US       |                2.52 |             79.64 |         79.75 |         82.19 |          79.54 |        77.36 |           69.36 |             95.34 |             70.94 |         5.82 |             69.68 | swing              |              nan    |                nan    |               nan    |
|     15 | AMC      | AMC                        | US       |                2.06 |             79.5  |         79.04 |         77.9  |          79.96 |        80.83 |           88.17 |             93.76 |            nan    |         9.71 |             66.89 | long               |                1.17 |                  0.86 |                 0.4  |
|     16 | SHELL.AS | SHELL.AS                   | EUROPE   |              239.04 |             79.1  |         82.27 |         77.12 |          75.97 |        81.08 |           93.71 |             83.08 |             64.71 |         2.47 |             73.14 | short              |               -1.3  |                  0.52 |                -0.19 |
|     17 | APA      | APA                        | US       |               13.6  |             78.83 |         79.16 |         79.86 |          78.5  |        78    |           77.87 |             77.93 |             67.53 |         6.1  |             72.11 | swing              |               -2.05 |                  0.31 |                -0.18 |
|     18 | KIN.BR   | KIN.BR                     | EUROPE   |                1.33 |             78.73 |         87.13 |         82.59 |          74.86 |        66.01 |           89.92 |             63.96 |             19.58 |         3.93 |             73.14 | short              |               -0.11 |                  0.11 |                -0.02 |
|     19 | OKTA     | OKTA                       | US       |               28.5  |             78.32 |         91.29 |         83.49 |          73.14 |        59.57 |           70.79 |             67.64 |             13.83 |         7.96 |             72.11 | short              |                0.39 |                  1.11 |                 0.97 |
|     20 | HAFN     | HAFN                       | US       |                4.21 |             78.17 |         85.25 |         82.5  |          73.85 |        70.85 |           75.06 |             59.89 |             58.52 |         5.71 |             69.68 | short              |                1.29 |                  1.56 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  76.12 |                    75.66 |                 77.12 |              76.22 |                86.74 |                   13.26 |           84.64 |             57.98 |       0.867 |         nan |       nan |      nan    |       -78.6  |          2.1  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.04 |                  60.49 |                    72.54 |                 76.38 |              67.79 |                88.49 |                   11.51 |           93.71 |             83.08 |     nan     |         nan |       nan |      nan    |         9.59 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              237.02 |                  66.55 |                    71.52 |                 73    |              70.24 |                78.1  |                   21.9  |           75.74 |             82.72 |     nan     |         nan |       nan |      nan    |         9.26 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  64.22 |                    71.3  |                 74.57 |              67.9  |                83.27 |                   16.73 |           92.69 |             66.76 |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4476.7  |                  61.64 |                    71.2  |                 73.16 |              66.26 |                77.41 |                   22.59 |           87.53 |             79.52 |       0.008 |         nan |       nan |       25.5  |        13.7  |         26.8  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.6  |                  68.38 |                    70.85 |                 73.24 |              69.03 |                79.9  |                   20.1  |           89.46 |             54.13 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | BBWI     | Bath & Body Works, Inc.              | US       |                2.92 |                  77.56 |                    70.85 |                 68.13 |              70.11 |                60.46 |                   39.54 |           76.37 |             33.8  |       0.227 |         nan |       nan |        5.57 |         6    |          4.39 |        0.73 |                 nan |              nan |                  11 |                  0.58 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.01 |                  58.69 |                    70.45 |                 74.47 |              64.99 |                84.31 |                   15.69 |           96.29 |             75.6  |     nan     |         nan |       nan |      nan    |         9.6  |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                  75.89 |                    70.17 |                 70.24 |              73.04 |                57.55 |                   42.45 |           61.58 |             80.38 |       0.142 |         nan |       nan |        1.79 |         4.7  |          4.95 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |              101.3  |                  59.22 |                    70.08 |                 73.7  |              65.95 |                81.99 |                   18.01 |           87.69 |             85.5  |     nan     |         nan |       nan |      nan    |         9.32 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.22 |                  58.78 |                    69.83 |                 73.6  |              65.13 |                81.84 |                   18.16 |           91.01 |             80.82 |     nan     |         nan |       nan |      nan    |        10.93 |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.94 |                  72.4  |                    69.41 |                 68.81 |              67.74 |                68.61 |                   31.39 |           84.18 |             32.63 |       0.614 |         nan |       nan |        1.62 |         4.27 |          3.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.87 |                  62.42 |                    69.34 |                 72    |              66.21 |                73.1  |                   26.9  |           83.12 |             81.1  |     nan     |         nan |       nan |      nan    |         4.86 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1404.71 |                  62.75 |                    69.34 |                 69.76 |              63.67 |                78.32 |                   21.68 |           92.79 |             43.88 |       0.019 |         nan |       nan |       31.69 |        17.52 |         43.3  |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|            9 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.69 |                  65.4  |                    68.88 |                 71.47 |              67.28 |                69.72 |                   30.28 |           80.43 |             76.48 |       0.019 |         nan |       nan |        4.09 |         6.13 |          4.91 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.78 |                  74.54 |                    68.44 |                 68.51 |              69.79 |                67.46 |                   32.54 |           75.5  |             39.86 |       0.597 |         nan |       nan |        4.37 |      -137    |          2.36 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO      | FRO                                  | US       |               10.36 |                  56.49 |                    68.26 |                 72.39 |              62.93 |                80.16 |                   19.84 |           92.78 |             78.32 |     nan     |         nan |       nan |      nan    |        11.8  |          7.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS      | IHS Holding Limited                  | OTHER    |                2.47 |                  72.99 |                    68.09 |                 68.03 |              71.71 |                62.78 |                   37.22 |           55.95 |             78.52 |      -0.114 |         nan |       nan |        7.51 |        15.31 |          5.17 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              176.79 |                  65.29 |                    67.68 |                 68.23 |              67.63 |                71.91 |                   28.09 |           66.18 |             76.78 |     nan     |         nan |       nan |      nan    |         9.14 |         11.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.29 |                  69.88 |                    67.59 |                 66.29 |              69.48 |                67.91 |                   32.09 |           58.88 |            nan    |       0.225 |         nan |       nan |        1.54 |       nan    |          3.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  76.12 |                    75.66 |                 77.12 |              76.22 |                86.74 |                   13.26 |           84.64 |             57.98 |       0.867 |         nan |       nan |      nan    |       -78.6  |          2.1  |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.04 |                  60.49 |                    72.54 |                 76.38 |              67.79 |                88.49 |                   11.51 |           93.71 |             83.08 |     nan     |         nan |       nan |      nan    |         9.59 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.55 |                  64.22 |                    71.3  |                 74.57 |              67.9  |                83.27 |                   16.73 |           92.69 |             66.76 |       0.154 |         nan |       nan |        0.75 |         5.22 |          5.05 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                5.01 |                  58.69 |                    70.45 |                 74.47 |              64.99 |                84.31 |                   15.69 |           96.29 |             75.6  |     nan     |         nan |       nan |      nan    |         9.6  |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              101.3  |                  59.22 |                    70.08 |                 73.7  |              65.95 |                81.99 |                   18.01 |           87.69 |             85.5  |     nan     |         nan |       nan |      nan    |         9.32 |         22.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.22 |                  58.78 |                    69.83 |                 73.6  |              65.13 |                81.84 |                   18.16 |           91.01 |             80.82 |     nan     |         nan |       nan |      nan    |        10.93 |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.6  |                  68.38 |                    70.85 |                 73.24 |              69.03 |                79.9  |                   20.1  |           89.46 |             54.13 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4476.7  |                  61.64 |                    71.2  |                 73.16 |              66.26 |                77.41 |                   22.59 |           87.53 |             79.52 |       0.008 |         nan |       nan |       25.5  |        13.7  |         26.8  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                                 | US       |              237.02 |                  66.55 |                    71.52 |                 73    |              70.24 |                78.1  |                   21.9  |           75.74 |             82.72 |     nan     |         nan |       nan |      nan    |         9.26 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |               10.36 |                  56.49 |                    68.26 |                 72.39 |              62.93 |                80.16 |                   19.84 |           92.78 |             78.32 |     nan     |         nan |       nan |      nan    |        11.8  |          7.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.87 |                  62.42 |                    69.34 |                 72    |              66.21 |                73.1  |                   26.9  |           83.12 |             81.1  |     nan     |         nan |       nan |      nan    |         4.86 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.69 |                  65.4  |                    68.88 |                 71.47 |              67.28 |                69.72 |                   30.28 |           80.43 |             76.48 |       0.019 |         nan |       nan |        4.09 |         6.13 |          4.91 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.43 |                  55.07 |                    66.59 |                 70.43 |              60.71 |                82.74 |                   17.26 |           95.93 |             61.68 |     nan     |         nan |       nan |      nan    |        11.76 |         12.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                  75.89 |                    70.17 |                 70.24 |              73.04 |                57.55 |                   42.45 |           61.58 |             80.38 |       0.142 |         nan |       nan |        1.79 |         4.7  |          4.95 |        5.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EOG      | EOG                                  | US       |               65.89 |                  57.69 |                    66.9  |                 69.94 |              62.98 |                78.32 |                   21.68 |           84.87 |             73.41 |     nan     |         nan |       nan |      nan    |         9.84 |         11.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |              100.64 |                  52.1  |                    65.58 |                 69.88 |              60.55 |                82.77 |                   17.23 |           87.22 |             81.44 |     nan     |         nan |       nan |      nan    |        10.8  |         16.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1404.71 |                  62.75 |                    69.34 |                 69.76 |              63.67 |                78.32 |                   21.68 |           92.79 |             43.88 |       0.019 |         nan |       nan |       31.69 |        17.52 |         43.3  |        0.34 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               19.19 |                  56.35 |                    65.92 |                 69.21 |              60.14 |                79.97 |                   20.03 |           96.39 |             51.74 |     nan     |         nan |       nan |      nan    |        11.12 |         15.07 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              112.6  |                  60.3  |                    66.86 |                 69.02 |              63.55 |                76.39 |                   23.61 |           83.4  |             63.86 |     nan     |         nan |       nan |      nan    |         9.69 |         14.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |              906.98 |                  49.83 |                    63.67 |                 68.82 |              56.82 |                75.06 |                   24.94 |           95.97 |             74.28 |     nan     |         nan |       nan |      nan    |         5.93 |         20.96 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | TALO     | TALO                                 | US       |                2.52 |                     0.05 |    -0.01 |      0.06 |                  69.02 |                        79.62 |         79.75 |         82.19 |          79.54 |        77.36 |           69.36 |             95.34 |         5.82 |
|               2 | SM       | SM                                   | US       |                7.87 |                     0.08 |     0    |      0.08 |                  56.57 |                        79.42 |         81.67 |         84.29 |          83.99 |        87.14 |           83.12 |             81.1  |         7.24 |
|               3 | CRGY     | CRGY                                 | US       |                4.91 |                     0.06 |     0.01 |      0.11 |                  62.54 |                        79.15 |         83.71 |         83.11 |          81.07 |        84.32 |           72.61 |             89.26 |         6.64 |
|               4 | BP       | BP                                   | US       |              101.3  |                     0.03 |    -0.01 |      0.05 |                  59.53 |                        78.64 |         78.69 |         72.06 |          72.89 |        78.47 |           87.69 |             85.5  |         4.62 |
|               5 | APA      | APA                                  | US       |               13.6  |                     0.06 |    -0    |      0.06 |                  71    |                        77.84 |         79.16 |         79.86 |          78.5  |        78    |           77.87 |             77.93 |         6.1  |
|               6 | SRAIL.SW | SRAIL.SW                             | EUROPE   |                3.14 |                     0.05 |     0.02 |      0.27 |                  64.91 |                        77.58 |         85.82 |         76.67 |          68.71 |        62.19 |           78.71 |             61.3  |         5.71 |
|               7 | EQNR     | EQNR                                 | US       |               90.84 |                     0.03 |    -0.02 |      0.06 |                  64.4  |                        75.98 |         75.77 |         79.16 |          76.11 |        74.45 |           75.72 |             77.28 |         5.73 |
|               8 | BE       | BE                                   | US       |               68.93 |                     0.03 |     0    |      0.29 |                  52.06 |                        75.87 |         78.47 |         63.97 |          72.2  |        63.06 |           86.86 |             76.34 |         9.25 |
|               9 | PBF      | PBF                                  | US       |                7.8  |                     0.03 |    -0.01 |      0.01 |                  57.73 |                        75.66 |         74.66 |         86.35 |          82.08 |        77.23 |           53.75 |             87.14 |         7.85 |
|              10 | SSL      | SSL                                  | US       |                7.94 |                     0.05 |    -0.02 |      0.21 |                  76.18 |                        75.4  |         82.63 |         77.11 |          73.85 |        77.78 |           59.66 |             71.46 |         6.96 |
|              11 | AGRO     | AGRO                                 | US       |                1.45 |                     0.07 |    -0.07 |      0.18 |                  82.81 |                        75.36 |         74.7  |         68.02 |          67.76 |        76.25 |           66.85 |             81.48 |         7.33 |
|              12 | SHEL     | SHEL                                 | US       |              237.02 |                     0.03 |     0    |      0.04 |                  56.81 |                        75.1  |         78.04 |         74.24 |          72.08 |        77.71 |           75.74 |             82.72 |         3.13 |
|              13 | KRX.IR   | KRX.IR                               | EUROPE   |               17.56 |                     0.07 |    -0.06 |     -0.04 |                  77.67 |                        74.3  |         52.39 |         67.77 |          71.5  |        66.56 |           96.78 |             62.69 |         5.69 |
|              14 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.09 |                     0.03 |    -0.01 |      0.19 |                  59.83 |                        74.06 |         81.42 |         75.73 |          69.75 |        71.27 |           61.58 |             80.38 |         3.85 |
|              15 | KOS      | KOS                                  | US       |                1.48 |                     0.07 |     0    |      0.05 |                  60.81 |                        73.31 |         71.75 |         74.05 |          75.57 |        75.17 |           65.74 |             93.43 |         8.81 |
|              16 | MUR      | MUR                                  | US       |                4.74 |                     0.05 |    -0.01 |      0.09 |                  72.7  |                        73.13 |         73.95 |         64.96 |          65.84 |        70.71 |           66.31 |             79.95 |         6.29 |
|              17 | HPE      | HPE                                  | US       |               65.21 |                     0.09 |    -0.04 |      0.02 |                  61.94 |                        73.1  |         70.72 |         76.68 |          79.07 |        72.06 |           73.38 |             71.97 |         7.11 |
|              18 | CVE      | CVE                                  | US       |               51.98 |                     0.04 |    -0.02 |      0    |                  69.18 |                        73.01 |         67.65 |         75.12 |          75.34 |        73.13 |           79.21 |             61.53 |         5.08 |
|              19 | MU       | MU                                   | US       |              906.98 |                     0.1  |    -0.1  |     -0.02 |                  72.64 |                        72.54 |         48.88 |         62.62 |          83.33 |        85.7  |           95.97 |             74.28 |         8.39 |
|              20 | OXY      | OXY                                  | US       |               51.43 |                     0.07 |    -0.03 |     -0    |                  72.27 |                        72.5  |         61.21 |         65.43 |          69.41 |        74.04 |           86    |             78.32 |         5.2  |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              343.53 |             40.21 |         37.32 |         33.65 |          43.09 |        50.25 |           77.39 |             45.69 |                26 |         3.41 |             89.74 | long               |               -1.12 |                 -0.02 |                 0.18 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     50 | PANW     | PANW   | US       |              266.33 |             73.19 |         75.86 |         79.28 |          70.51 |        51.04 |           48.96 |             84.13 |              6.7  |         7.71 |             73.14 | swing              |                3.51 |                  4.63 |                 3.98 |
|     26 | RBRK     | RBRK   | US       |               18.73 |             76.95 |         85.61 |         84.25 |          69.66 |        50.9  |           54.49 |             89.59 |              1.95 |         8.76 |             72.23 | short              |                1.53 |                  4.05 |                 3.35 |
|     34 | NTSK     | NTSK   | US       |                6.12 |             75    |         90.03 |         84.16 |          65.84 |        45.45 |           50.63 |             85.76 |              1.96 |         9.34 |             64.96 | short              |                0.73 |                  3.35 |                 2.19 |
|    134 | FTRE     | FTRE   | US       |                1.65 |             66.23 |         78.42 |         72.38 |          60.08 |        44.96 |           22.52 |             58.41 |             38.8  |         8.15 |             73.14 | short              |                2.42 |                  3.26 |                 2.73 |
|     44 | CRWD     | CRWD   | US       |              214.2  |             73.82 |         88.17 |         81.52 |          66.12 |        44.71 |           37.39 |             79.79 |              1.96 |         8.02 |             73.14 | short              |                0.52 |                  3.23 |                 3.22 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    575 | APH      | APH                     | US       |              165.13 |             47.24 |         42.54 |         43.11 |          51.37 |        54.14 |           80.92 |             27.46 |             20.39 |         6.19 |             73.14 | long               |               -1.81 |                 -3.58 |               nan    |
|    329 | HMY      | HMY                     | US       |               10.41 |             58    |         50.82 |         53.35 |          62.66 |        73.83 |           84.49 |             30.58 |             84.31 |         8.27 |             73.14 | long               |               -1.45 |                 -3.46 |               nan    |
|    399 | SBSW     | SBSW                    | US       |                7.27 |             55.45 |         58.46 |         50    |          52.44 |        64.03 |           59.61 |             42.43 |             81.37 |         8.61 |             69.68 | long               |               -0.71 |                 -2.97 |                -2.81 |
|    569 | BAC      | BAC                     | US       |              350.92 |             47.71 |         32.06 |         45.35 |          50.07 |        52.2  |           44.05 |             27.31 |             68.86 |         2.78 |             72.8  | long               |               -1.69 |                 -2.52 |                -2.32 |
|    659 | BBWI     | Bath & Body Works, Inc. | US       |                2.92 |             38.65 |         33.18 |         30.66 |          44.13 |        60.89 |           76.37 |             33.8  |             79.35 |         7.56 |             88.55 | long               |                0.36 |                 -2.48 |                -2.83 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
- market_cap: 160
- price_history: 22
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| SM | 6 |  | 2 |  | 2 | main,pullback |
| CRGY | 8 |  | 3 |  | 2 | main,pullback |
| PARR | 11 | 9 |  | 5 | 1 | value,quality_value |
| PBR-A | 47 | 6 | 14 | 6 | 1 | value,quality_value |
| DDI | 81 | 2 | 43 | 2 | 1 | value,quality_value |
| NVDA | 140 | 3 | 26 | 4 | 1 | value,quality_value |
| IRWD | 166 | 4 |  | 3 | 1 | value,quality_value |
| NWL.MI | 188 | 10 |  | 9 | 1 | value,quality_value |
| BION.SW | 207 | 1 | 108 | 1 | 1 | value,quality_value |
| STNE | 539 | 7 | 185 | 8 | 1 | value,quality_value |
| AVGO | 572 | 8 | 234 | 7 | 1 | value,quality_value |
| BBWI | 659 | 5 |  | 10 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| VLO | 2 |  |  |  | 1 | main |
| DHT | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (FRO, VLO, DHT, CMBT.BR, DELL, NAT, DINO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (BP, BE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 73.85 | 76.12 | 60.68 | 84.64 | 57.98 | 86.74 | 62.85 |
| 2 | NVDA | value+pullback | 73.48 | 61.64 | 73.72 | 87.53 | 79.52 | 77.41 | 65.80 |
| 3 | AVGO | value+pullback | 70.65 | 62.75 | 71.42 | 92.79 | 43.88 | 78.32 | 47.68 |
| 4 | ETG | value+pullback | 69.54 | 55.84 | 74.90 | 68.49 | 81.86 | 78.00 | 58.41 |
| 5 | STNE | value+pullback | 68.59 | 72.40 | 69.05 | 84.18 | 32.63 | 68.61 | 49.12 |
| 6 | DDI | value+pullback | 68.50 | 64.22 | 48.01 | 92.69 | 66.76 | 83.27 | 69.99 |
| 7 | PBR-A | value+pullback | 66.51 | 75.89 | 59.83 | 61.58 | 80.38 | 57.55 | 73.50 |
| 8 | 0Q2N.IL | value+pullback | 65.54 | 69.88 | 68.65 | 58.88 |  | 67.91 | 67.84 |
| 9 | VOLV-B.ST | value+pullback | 65.48 | 75.88 | 75.88 | 55.10 | 44.53 | 55.15 | 52.08 |
| 10 | UNIT | value+pullback | 63.56 | 80.01 | 72.06 | 65.23 | 29.14 | 44.24 | 40.27 |
| 11 | RCI | value+pullback | 63.47 | 63.60 | 69.62 | 82.71 | 35.29 | 55.25 | 49.63 |
| 12 | AVK | value+pullback | 63.26 | 55.60 | 79.07 | 63.12 |  | 61.74 | 45.88 |
| 13 | BHF | value+pullback | 62.61 | 72.83 | 56.96 | 52.45 | 54.35 | 66.10 | 41.57 |
| 14 | GSL | value+pullback | 62.33 | 69.69 | 47.67 | 76.48 | 30.35 | 75.01 | 68.25 |
| 15 | WKC | value+pullback | 62.26 | 58.36 | 54.99 | 63.66 | 78.06 | 68.24 | 67.36 |
| 16 | ORC | value+pullback | 61.85 | 60.76 | 66.80 | 76.18 | 35.27 | 59.81 | 39.01 |
| 17 | BCE | value+pullback | 61.77 | 58.64 | 70.43 | 68.18 | 56.83 | 53.29 | 45.71 |
| 18 | MFA | value+pullback | 60.46 | 57.07 | 70.66 | 75.60 | 26.31 | 58.52 | 38.48 |
| 19 | MAGN | value+pullback | 60.00 | 70.20 | 50.68 | 68.70 | 34.12 | 62.77 | 45.10 |
| 20 | GL9.IR | pullback | 59.78 | 40.69 | 83.36 | 97.88 | 70.23 | 86.19 | 64.67 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 72.7 | 3 / 7 |
| Top 25 | 24/25 | 25/25 | 24/25 | 23/25 | 0/25 | 72.1 | 11 / 14 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 72.2 | 23 / 27 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=4, mega_100b_plus=2
