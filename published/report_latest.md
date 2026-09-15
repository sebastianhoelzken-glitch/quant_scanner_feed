# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-15

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

- **EUROPE:** 76.9/100
- **OTHER:** 69.6/100
- **US:** 81.0/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC                        | US       |               96.03 |             87.24 |         87.28 |         90.83 |          87.21 |        81.29 |           85.03 |             87.85 |             61.46 |         4.23 |             73.14 | swing              |              nan    |                nan    |               nan    |
|      2 | FRO      | FRO                        | US       |                9.7  |             86.3  |         89.42 |         87.35 |          85.25 |        81.28 |           91.99 |             78.73 |             57.36 |         5.57 |             73.14 | short              |                2.33 |                nan    |               nan    |
|      3 | VLO      | VLO                        | US       |               95.1  |             85.9  |         86.53 |         88.42 |          85.27 |        79.69 |           85.39 |             81.92 |             57.77 |         3.6  |             69.68 | swing              |                1.53 |                  0.62 |               nan    |
|      4 | DHT      | DHT                        | US       |                3.08 |             85.58 |         89.2  |         87.24 |          83.93 |        81.92 |           89.51 |             81.11 |             63.14 |         4.78 |             73.14 | short              |                8.68 |                  2.65 |                 1.82 |
|      5 | SM       | SM                         | US       |                8.01 |             85.39 |         88.79 |         85.2  |          82.54 |        85.57 |           81.83 |             78.56 |             94.91 |         7.15 |             72.11 | short              |                1.04 |                  2.76 |                 2.29 |
|      6 | DK       | DK                         | US       |                3.93 |             84.26 |         88.96 |         88.29 |          80.24 |        69.2  |           54.97 |             92.7  |             57.91 |         7.41 |             73.14 | short              |                2.12 |                  0.97 |                 0.44 |
|      7 | CRGY     | CRGY                       | US       |                4.95 |             83.54 |         88.92 |         84.21 |          79.83 |        82.87 |           70.62 |             88.92 |             93.99 |         6.41 |             69.23 | short              |               -0.27 |                  0.85 |                 0.31 |
|      8 | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.86 |             83.33 |         84.54 |         82.13 |          82.47 |        84.2  |           94.65 |             55.1  |             76.67 |         4.01 |             73.14 | short              |                7.44 |                  2.79 |                 1.41 |
|      9 | AVAH     | AVAH                       | US       |                2.71 |             83.22 |         89.56 |         86.61 |          79.83 |        73.4  |           93.44 |             65.25 |             34.69 |         7.81 |             72.11 | short              |                4.64 |                  2.57 |                 2.32 |
|     10 | NAT      | NAT                        | US       |                1.39 |             82.09 |         87.9  |         84.51 |          79.68 |        72.85 |           87.64 |             67.42 |             36.86 |         5.03 |             73.14 | short              |                4.71 |                  2.02 |               nan    |
|     11 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |             82    |         85.84 |         85.5  |          78.51 |        69.06 |           87.11 |             77.38 |             26.44 |         3.86 |             73.14 | short              |                3.14 |                  1.13 |                 0.88 |
|     12 | DELL     | DELL                       | US       |              293    |             81.98 |         85.86 |         84.26 |          79.71 |        66.92 |           73.09 |             80.65 |             28.93 |         7.89 |             72.23 | short              |                1.46 |                  0.33 |                -0.23 |
|     13 | DINO     | DINO                       | US       |               16.39 |             81.53 |         84.17 |         87.31 |          78.89 |        69.72 |           49.44 |             84.78 |             73.18 |         4.6  |             73.14 | swing              |                2.39 |                nan    |               nan    |
|     14 | SHELL.AS | SHELL.AS                   | EUROPE   |              239.5  |             80.85 |         82.87 |         78.83 |          77.28 |        84.22 |           91.32 |             81.86 |             78.38 |         2.34 |             73.14 | long               |                1.36 |                  3.61 |                 2.77 |
|     15 | ANF      | ANF                        | US       |                5.15 |             79.8  |         82.76 |         81.83 |          77.76 |        76.34 |           88.46 |             65.29 |             57.21 |         8.68 |             67.64 | short              |                0.09 |                  0.1  |                -1    |
|     16 | TALO     | TALO                       | US       |                2.54 |             79.59 |         85.69 |         81.2  |          77.98 |        75.57 |           67.6  |             94.71 |             68.94 |         5.81 |             69.68 | short              |              nan    |                nan    |               nan    |
|     17 | APA      | APA                        | US       |               13.61 |             79.23 |         86.09 |         80.71 |          77.75 |        76.19 |           74.98 |             77.72 |             66.14 |         5.94 |             72.11 | short              |                1.96 |                  0.6  |                 0.3  |
|     18 | PARR     | Par Pacific Holdings, Inc. | US       |                3.53 |             78.49 |         74.53 |         79.22 |          79.99 |        77.76 |           80.98 |             74.93 |             67.79 |         7.18 |             84.91 | medium             |               -1.34 |                  0.04 |                -0.13 |
|     19 | UGP      | UGP                        | US       |                6.84 |             78.21 |         82.97 |         82.56 |          73.85 |        67.17 |           61.38 |             66.2  |             57.59 |         4.79 |             72.11 | short              |                7.87 |                 -0.05 |                -0.77 |
|     20 | OKTA     | OKTA                       | US       |               28.11 |             77.59 |         91.01 |         83.28 |          71.91 |        57.73 |           67.04 |             66.46 |             13.09 |         7.9  |             72.11 | short              |                3.94 |                  1.21 |                 0.35 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.18 |                  81.82 |                    79.03 |                 78.58 |              79.41 |                69.78 |                   30.22 |           78.03 |            nan    |       0.456 |         nan |       nan |        1.16 |       nan    |          0.71 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  74.43 |                    74.4  |                 76    |              74.62 |                85.11 |                   14.89 |           84.71 |             57.09 |       0.857 |         nan |       nan |      nan    |       -79.51 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | DDI      | DoubleDown Interactive Co., Ltd.     | OTHER    |                0.54 |                  67.42 |                    73.51 |                 76.52 |              70.53 |                85.9  |                   14.1  |           94.01 |             65.33 |       0.156 |         nan |       nan |        0.71 |         5.17 |          5    |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              239.5  |                  61.16 |                    72.21 |                 75.71 |              67.91 |                87.18 |                   12.82 |           91.32 |             81.86 |     nan     |         nan |       nan |      nan    |         9.66 |         10.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.53 |                  70.82 |                    71.99 |                 74.04 |              71.31 |                71.29 |                   28.71 |           80.98 |             74.93 |       0.02  |         nan |       nan |        3.96 |         6.05 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                                 | US       |              237.87 |                  66.71 |                    71.03 |                 72.26 |              70.23 |                76.93 |                   23.07 |           72.7  |             83.49 |     nan     |         nan |       nan |      nan    |         9.33 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4393.72 |                  61.64 |                    70.99 |                 72.85 |              66.13 |                77.09 |                   22.91 |           86.9  |             78.8  |       0.008 |         nan |       nan |       25.14 |        13.51 |         26.7  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.       | US       |                0.59 |                  68.09 |                    70.66 |                 73.08 |              68.81 |                79.63 |                   20.37 |           89.28 |             54.51 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                   | US       |              102.03 |                  59.42 |                    70    |                 73.5  |              66.08 |                81.78 |                   18.22 |           86.53 |             85.76 |     nan     |         nan |       nan |      nan    |         9.36 |         21.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.24 |                  68.79 |                    69.82 |                 69.73 |              70.1  |                75.34 |                   24.66 |           68.05 |            nan    |       0.228 |         nan |       nan |        1.54 |       nan    |          3.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | BBWI     | Bath & Body Works, Inc.              | US       |                3.11 |                  79.22 |                    69.58 |                 66.11 |              69.74 |                51.87 |                   48.13 |           70.52 |             33.66 |       0.212 |         nan |       nan |        5.75 |         6.43 |          4.7  |        0.76 |                 nan |              nan |                  11 |                  0.58 |
|            9 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.72 |                    69.56 |                 69.05 |              68.04 |                68.73 |                   31.27 |           84.18 |             33.13 |       0.602 |         nan |       nan |        1.63 |         4.31 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1419.33 |                  62.75 |                    69.31 |                 69.7  |              63.73 |                78.2  |                   21.8  |           92.11 |             44.72 |       0.019 |         nan |       nan |       32.17 |        17.78 |         43.86 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.08 |                  57.86 |                    68.99 |                 72.76 |              64.39 |                81.19 |                   18.81 |           89.51 |             81.11 |     nan     |         nan |       nan |      nan    |        10.5  |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | MOMO     | Hello Group Inc.                     | OTHER    |                0.61 |                  77.75 |                    68.81 |                 66.38 |              71.96 |                70.28 |                   29.72 |           63.46 |             33.25 |       0.85  |         nan |       nan |       -5.96 |         4.77 |          4.88 |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                   | US       |                8.01 |                  62.49 |                    68.71 |                 71.13 |              65.77 |                71.82 |                   28.18 |           81.83 |             78.56 |     nan     |         nan |       nan |      nan    |         5.01 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.7  |                  56.74 |                    68.31 |                 72.36 |              63.14 |                80.1  |                   19.9  |           91.99 |             78.73 |     nan     |         nan |       nan |      nan    |        11.11 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.86 |                  60.86 |                    68.13 |                 70.85 |              63.18 |                76.93 |                   23.07 |           94.65 |             55.1  |     nan     |         nan |       nan |      nan    |         9.37 |          6.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               44.49 |                  64.51 |                    67.89 |                 69.47 |              65.67 |                70.32 |                   29.68 |           77.88 |            nan    |       0.389 |         nan |       nan |        7.45 |       nan    |          2.89 |        0.62 |                 nan |              nan |                   9 |                  0.47 |
|           13 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.61 |                  74.98 |                    67.46 |                 66.79 |              71.3  |                50.9  |                   49.1  |           52.72 |             81.6  |       0.14  |         nan |       nan |        1.8  |         4.74 |          4.82 |        5.47 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                             | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                  | OTHER    |               14.18 |                  81.82 |                    79.03 |                 78.58 |              79.41 |                69.78 |                   30.22 |           78.03 |            nan    |       0.456 |         nan |       nan |        1.16 |       nan    |          0.71 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            3 | DDI      | DoubleDown Interactive Co., Ltd. | OTHER    |                0.54 |                  67.42 |                    73.51 |                 76.52 |              70.53 |                85.9  |                   14.1  |           94.01 |             65.33 |       0.156 |         nan |       nan |        0.71 |         5.17 |          5    |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BION.SW  | BB Biotech AG                    | EUROPE   |                3.06 |                  74.43 |                    74.4  |                 76    |              74.62 |                85.11 |                   14.89 |           84.71 |             57.09 |       0.857 |         nan |       nan |      nan    |       -79.51 |          2.13 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                         | EUROPE   |              239.5  |                  61.16 |                    72.21 |                 75.71 |              67.91 |                87.18 |                   12.82 |           91.32 |             81.86 |     nan     |         nan |       nan |      nan    |         9.66 |         10.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.53 |                  70.82 |                    71.99 |                 74.04 |              71.31 |                71.29 |                   28.71 |           80.98 |             74.93 |       0.02  |         nan |       nan |        3.96 |         6.05 |          4.79 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                               | US       |              102.03 |                  59.42 |                    70    |                 73.5  |              66.08 |                81.78 |                   18.22 |           86.53 |             85.76 |     nan     |         nan |       nan |      nan    |         9.36 |         21.98 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | IRWD     | Ironwood Pharmaceuticals, Inc.   | US       |                0.59 |                  68.09 |                    70.66 |                 73.08 |              68.81 |                79.63 |                   20.37 |           89.28 |             54.51 |       0.177 |         nan |       nan |        4.23 |         2.78 |          5.28 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA     | NVIDIA Corporation               | US       |             4393.72 |                  61.64 |                    70.99 |                 72.85 |              66.13 |                77.09 |                   22.91 |           86.9  |             78.8  |       0.008 |         nan |       nan |       25.14 |        13.51 |         26.7  |        0.46 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                              | US       |                3.08 |                  57.86 |                    68.99 |                 72.76 |              64.39 |                81.19 |                   18.81 |           89.51 |             81.11 |     nan     |         nan |       nan |      nan    |        10.5  |          7.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                              | US       |                9.7  |                  56.74 |                    68.31 |                 72.36 |              63.14 |                80.1  |                   19.9  |           91.99 |             78.73 |     nan     |         nan |       nan |      nan    |        11.11 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                             | US       |              237.87 |                  66.71 |                    71.03 |                 72.26 |              70.23 |                76.93 |                   23.07 |           72.7  |             83.49 |     nan     |         nan |       nan |      nan    |         9.33 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                               | US       |                8.01 |                  62.49 |                    68.71 |                 71.13 |              65.77 |                71.82 |                   28.18 |           81.83 |             78.56 |     nan     |         nan |       nan |      nan    |         5.01 |          6.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                          | EUROPE   |                4.86 |                  60.86 |                    68.13 |                 70.85 |              63.18 |                76.93 |                   23.07 |           94.65 |             55.1  |     nan     |         nan |       nan |      nan    |         9.37 |          6.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.63 |                  57.65 |                    67.44 |                 70.74 |              62.06 |                81.59 |                   18.41 |           95.05 |             58.64 |     nan     |         nan |       nan |      nan    |        10.8  |         14.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                           | EUROPE   |               23.93 |                  56.55 |                    67.02 |                 70.52 |              61.53 |                81.98 |                   18.02 |           94.77 |             60.56 |     nan     |         nan |       nan |      nan    |        11.52 |         11.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | 0Q2N.IL  | K+S Aktiengesellschaft           | OTHER    |                3.24 |                  68.79 |                    69.82 |                 69.73 |              70.1  |                75.34 |                   24.66 |           68.05 |            nan    |       0.228 |         nan |       nan |        1.54 |       nan    |          3.02 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO     | Broadcom Inc.                    | US       |             1419.33 |                  62.75 |                    69.31 |                 69.7  |              63.73 |                78.2  |                   21.8  |           92.11 |             44.72 |       0.019 |         nan |       nan |       32.17 |        17.78 |         43.86 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAA      | PAA                              | US       |               15.73 |                  54.1  |                    65.91 |                 69.64 |              61.04 |                82.84 |                   17.16 |           88.42 |             71.75 |     nan     |         nan |       nan |      nan    |        13.66 |         22.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | 0P6O.IL  | Volkswagen AG                    | OTHER    |               44.49 |                  64.51 |                    67.89 |                 69.47 |              65.67 |                70.32 |                   29.68 |           77.88 |            nan    |       0.389 |         nan |       nan |        7.45 |       nan    |          2.89 |        0.62 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BEN      | BEN                              | US       |               14.67 |                  56.13 |                    65.87 |                 69.07 |              61.54 |                78.66 |                   21.34 |           86.24 |             69.69 |     nan     |         nan |       nan |      nan    |        10.53 |         22.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | KIN.BR   | KIN.BR                     | EUROPE   |                1.29 |                     0.02 |    -0.02 |      0.16 |                  57.92 |                        80.64 |         85.84 |         85.5  |          78.51 |        69.06 |           87.11 |             77.38 |         3.86 |
|               2 | ANF      | ANF                        | US       |                5.15 |                     0.08 |    -0.06 |      0.3  |                  75.87 |                        80.25 |         82.76 |         81.83 |          77.76 |        76.34 |           88.46 |             65.29 |         8.68 |
|               3 | AMC      | AMC                        | US       |                1.92 |                     0.07 |    -0.06 |      0    |                  75.54 |                        79.57 |         57.72 |         74.27 |          79.41 |        79.35 |           85.11 |             93.89 |         9.7  |
|               4 | DELL     | DELL                       | US       |              293    |                     0.06 |     0.02 |      0.09 |                  63.22 |                        79.13 |         85.86 |         84.26 |          79.71 |        66.92 |           73.09 |             80.65 |         7.89 |
|               5 | PARR     | Par Pacific Holdings, Inc. | US       |                3.53 |                     0.03 |     0    |      0.02 |                  57    |                        75.59 |         74.53 |         79.22 |          79.99 |        77.76 |           80.98 |             74.93 |         7.18 |
|               6 | BE       | BE                         | US       |               65.3  |                     0.07 |     0.02 |      0.12 |                  55.02 |                        75.45 |         77.47 |         62.92 |          71.54 |        62.25 |           85.82 |             75.31 |         9.23 |
|               7 | SRAIL.SW | SRAIL.SW                   | EUROPE   |                3.05 |                     0.08 |    -0.02 |      0.22 |                  58.04 |                        75.36 |         82.53 |         77.31 |          70.73 |        63.71 |           73.58 |             71.13 |         5.65 |
|               8 | SB       | SB                         | US       |                0.73 |                     0.09 |    -0.09 |      0.08 |                  75.61 |                        74.83 |         69.91 |         76.99 |          76.89 |        73.58 |           69.09 |             74.49 |         4.39 |
|               9 | WDAY     | WDAY                       | US       |               40.37 |                     0.06 |    -0.01 |     -0.02 |                  69.21 |                        74.36 |         63.98 |         75.43 |          68.08 |        63.29 |           74.25 |             76.11 |         8.73 |
|              10 | WT       | WT                         | US       |                2.98 |                     0.09 |    -0.08 |     -0    |                  73.86 |                        74.34 |         57.98 |         75.37 |          73.85 |        64.4  |           72.24 |             74.19 |         5.93 |
|              11 | KRX.IR   | KRX.IR                     | EUROPE   |               17.12 |                     0.1  |    -0.1  |     -0.04 |                  72.55 |                        74.18 |         49.79 |         66.5  |          72.86 |        68.96 |           96.96 |             71.05 |         5.66 |
|              12 | A5G.IR   | A5G.IR                     | EUROPE   |               23.93 |                     0.02 |     0    |      0.05 |                  46.89 |                        73.77 |         77.39 |         73.05 |          76.17 |        77.49 |           94.77 |             60.56 |         2.38 |
|              13 | PAGP     | PAGP                       | US       |                5.63 |                     0.02 |     0    |      0.08 |                  45.85 |                        73.68 |         81.54 |         73.37 |          71.95 |        71.39 |           84.21 |             61.22 |         1.8  |
|              14 | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.63 |                     0.03 |    -0.02 |      0.03 |                  58.58 |                        73.3  |         73.42 |         70.5  |          75.8  |        80.37 |           95.05 |             58.64 |         2.33 |
|              15 | BEN      | BEN                        | US       |               14.67 |                     0.04 |    -0.04 |     -0.01 |                  74.94 |                        72.72 |         56.37 |         67.55 |          76.45 |        77.65 |           86.24 |             69.69 |         3.38 |
|              16 | HOOD     | HOOD                       | US       |               88.66 |                     0.08 |    -0.06 |      0.2  |                  71.89 |                        72.33 |         74.64 |         71.69 |          60.95 |        50.58 |           65.55 |             74.11 |         8.99 |
|              17 | SNOW     | SNOW                       | US       |              101.13 |                     0.07 |    -0.01 |      0.01 |                  67.17 |                        72.23 |         73    |         80.32 |          67.58 |        46.56 |           42.42 |             90.08 |         8.11 |
|              18 | XP       | XP                         | US       |                8.58 |                     0.02 |    -0.01 |      0.24 |                  53.21 |                        72.06 |         82.11 |         70.59 |          61.75 |        66.49 |           57.47 |             76.87 |         6.25 |
|              19 | CRM      | CRM                        | US       |              184.16 |                     0.02 |     0    |      0.32 |                  48.27 |                        72.04 |         86.52 |         77.04 |          59.95 |        55.67 |           63.24 |             59.27 |         7.98 |
|              20 | ASRNL.AS | ASRNL.AS                   | EUROPE   |               14.7  |                     0.02 |    -0.01 |      0.05 |                  54.44 |                        71.53 |         77.27 |         73.01 |          70.88 |        70.61 |           74.46 |             65.57 |         1.09 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NWL.MI   | NewPrinces S.p.A.            | EUROPE   |                0.71 |             58.36 |         69.51 |         50.34 |          51.09 |        65.62 |           75    |             40.49 |             86.49 |         8.5  |             77.91 | short              |                1.77 |                  3.28 |                 2.01 |
|    nan | COST     | Costco Wholesale Corporation | US       |              351.49 |             44.45 |         45.45 |         35.51 |          43.44 |        50.55 |           77.39 |             46.77 |             26    |         3.37 |             89.74 | long               |                2.94 |                  1.86 |                 1.83 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    150 | STR.VI   | STR.VI                 | EUROPE   |               12.28 |             65.23 |         88.54 |         71.11 |          59.36 |        53.53 |          nan    |             56.17 |             37.73 |         5.64 |             66.84 | short              |               -0.13 |                  4.46 |               nan    |
|    155 | SDF.DE   | K+S Aktiengesellschaft | EUROPE   |                2.96 |             65.02 |         70.89 |         59.51 |          59.89 |        70.15 |           86.8  |             40.35 |             60.33 |         4.97 |             82.14 | short              |               -0.27 |                  4.26 |                 3.25 |
|    116 | CTSH     | CTSH                   | US       |               24.9  |             67.16 |         72.97 |         64.15 |          60.27 |        70.17 |           84.67 |             50.09 |             68.02 |         8.21 |             70.75 | short              |               10.7  |                  4.11 |                 4.12 |
|    243 | ACN      | ACN                    | US       |              102.92 |             60.77 |         72.79 |         59.03 |          54.82 |        62.51 |           80.51 |             52.83 |             49.26 |         8.55 |             67.64 | short              |                4.19 |                  4.1  |               nan    |
|     57 | RBRK     | RBRK                   | US       |               17.79 |             72.25 |         75.56 |         80.21 |          68.94 |        50.05 |           53.47 |             88.31 |              1.65 |         8.76 |             72.23 | swing              |               15.62 |                  3.87 |                 3.35 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    489 | HQL      | Abrdn Life Sciences Investors        | US       |                0.52 |             51.43 |         45.21 |         61.17 |          57.4  |        45.45 |           46.37 |            nan    |             22.22 |         2.68 |             59.6  | swing              |               -0.24 |                 -4.29 |                -3.66 |
|    668 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               14.18 |             37.34 |         21.63 |         24.62 |          50.07 |        71.19 |           78.03 |            nan    |             93.57 |         9.13 |             69.59 | long               |                0.76 |                 -4.09 |                -3.03 |
|    446 | GOLD     | Gold.com, Inc.                       | US       |                1.19 |             52.6  |         71.22 |         52.63 |          52.57 |        49    |           39.96 |             68.86 |             33.16 |         7.17 |             77.52 | short              |               -1.91 |                 -3.99 |               nan    |
|    559 | ASA      | ASA Gold and Precious Metals Limited | US       |                0.93 |             48.84 |         45.99 |         42.75 |          51.68 |        59.06 |           63.37 |            nan    |             49.47 |         5.97 |             63.1  | long               |               -6.31 |                 -3.81 |                -3.42 |
|    613 | AMV0.DE  | Aumovio SE                           | EUROPE   |                3.59 |             44.25 |         48.75 |         35.14 |          39.76 |        50.49 |           50.4  |             29.53 |             72.35 |         6.35 |             76.69 | long               |               -0.79 |                 -3.41 |                -2.97 |

## Duplicate-security checks

- SDLFL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.89
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
- Excluded by hard/data filters: **282**
- Event watch (otherwise eligible): **2**
- Final eligible: **716**
- Eligible change vs previous stored run: **-1**

Top exclusion categories:
- liquidity: 226
- price: 180
- market_cap: 159
- price_history: 16
- data_confidence: 10
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 18 | 4 | 5 | 4 | 2 | value,pullback,quality_value |
| DDI | 95 | 3 | 35 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 124 | 7 |  | 7 | 1 | value,quality_value |
| IRWD | 168 | 6 | 60 | 5 | 1 | value,quality_value |
| NVDA | 172 | 5 | 23 | 6 | 1 | value,quality_value |
| BION.SW | 183 | 2 | 80 | 3 | 1 | value,quality_value |
| STNE | 547 | 9 | 172 | 10 | 1 | value,quality_value |
| AVGO | 573 | 10 |  | 8 | 1 | value,quality_value |
| 0QXR.IL | 668 | 1 |  | 1 | 1 | value,quality_value |
| MPC | 1 |  |  |  | 1 | main |
| FRO | 2 |  |  |  | 1 | main |
| VLO | 3 |  |  |  | 1 | main |
| DHT | 4 |  |  |  | 1 | main |
| SM | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (MPC, FRO, VLO, DHT, SM, DK, CRGY, CMBT.BR, NAT)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 74.36 | 68.09 | 76.64 | 89.28 | 54.51 | 79.63 | 64.29 |
| 2 | NVDA | value+pullback | 74.24 | 61.64 | 77.65 | 86.90 | 78.80 | 77.09 | 64.03 |
| 3 | BION.SW | value+pullback | 73.89 | 74.43 | 64.49 | 84.71 | 57.09 | 85.11 | 63.65 |
| 4 | DDI | value+pullback | 72.90 | 67.42 | 59.45 | 94.01 | 65.33 | 85.90 | 68.33 |
| 5 | INDU-C.ST | value+pullback | 71.57 | 59.22 | 83.72 | 72.30 | 80.83 | 69.76 | 59.38 |
| 6 | SDF.DE | value+pullback | 71.56 | 65.38 | 80.90 | 86.80 | 40.35 | 73.31 | 65.02 |
| 7 | 0Q2N.IL | value+pullback | 71.25 | 68.79 | 81.35 | 68.05 |  | 75.34 | 66.67 |
| 8 | ETG | value+pullback | 69.86 | 55.84 | 77.89 | 67.52 | 80.57 | 77.24 | 58.68 |
| 9 | PARR | value+pullback | 69.39 | 70.82 | 57.00 | 80.98 | 74.93 | 71.29 | 78.49 |
| 10 | STNE | value+pullback | 68.56 | 72.72 | 68.24 | 84.18 | 33.13 | 68.73 | 49.49 |
| 11 | PKX | value+pullback | 68.47 | 55.47 | 85.07 | 75.04 | 73.71 | 59.67 | 56.48 |
| 12 | UNIT | value+pullback | 66.41 | 80.26 | 81.23 | 67.17 | 29.44 | 45.04 | 41.68 |
| 13 | EMBC | value+pullback | 65.92 | 68.18 | 73.27 | 63.60 | 62.70 | 56.68 | 59.32 |
| 14 | 0P6O.IL | value+pullback | 65.61 | 64.51 | 62.04 | 77.88 |  | 70.32 | 56.65 |
| 15 | BBWI | value+pullback | 65.26 | 79.22 | 68.70 | 70.52 | 33.66 | 51.87 | 42.83 |
| 16 | AMV0.DE | value+pullback | 64.99 | 69.19 | 83.65 | 50.40 | 29.53 | 64.06 | 44.25 |
| 17 | MAGN | value+pullback | 64.93 | 72.36 | 67.55 | 68.70 | 34.59 | 62.87 | 41.41 |
| 18 | WKC | value+pullback | 64.25 | 56.45 | 65.11 | 62.39 | 77.85 | 69.46 | 65.39 |
| 19 | XNET | value+pullback | 63.88 | 59.28 | 64.00 | 57.83 | 80.83 | 66.68 | 43.31 |
| 20 | INVA | value+pullback | 63.76 | 57.10 | 59.38 | 86.28 | 32.79 | 77.82 | 48.37 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 73.1 | 1 / 9 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 72.2 | 8 / 17 |
| Top 50 | 48/50 | 50/50 | 49/50 | 47/50 | 0/50 | 72.1 | 16 / 34 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=2, large_20_100b=2
