# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-23

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

- **EUROPE:** 81.2/100
- **OTHER:** 70.2/100
- **US:** 82.3/100

## Main multi-horizon ranking

|   rank | symbol    | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MU        | MU                             | US       |             1079.84 |             82.23 |         80.44 |         73.1  |          84.44 |        84.02 |           95.86 |             78.38 |             71.06 |         8.2  |             73.14 | medium             |                1.46 |                  2.66 |                 2.05 |
|      2 | HPE       | HPE                            | US       |               70.67 |             80.86 |         87.94 |         81.9  |          79.82 |        71.57 |           76.08 |             79.16 |             49.62 |         6.98 |             72.34 | short              |               -0.49 |                  0.21 |               nan    |
|      3 | DELL      | DELL                           | US       |              304.42 |             80.78 |         86.48 |         82.34 |          79.22 |        66.66 |           74.81 |             85.12 |             28.78 |         7.8  |             72.23 | short              |               -2.84 |                 -0.29 |                -0.37 |
|      4 | FRO       | FRO                            | US       |                9.31 |             80.67 |         81.41 |         77.65 |          81.98 |        79.94 |           92.05 |             79.28 |             59.05 |         5.51 |             73.14 | medium             |               -4.24 |                  0.26 |                 0.28 |
|      5 | AMC       | AMC                            | US       |                2.31 |             79.6  |         80.73 |         84.43 |          78.47 |        77.92 |           85.87 |             78.26 |            nan    |         9.55 |             65.07 | swing              |                3.4  |                  4.14 |                 3.88 |
|      6 | GH        | GH                             | US       |               20.74 |             79.4  |         76.93 |         84.07 |          81.88 |        74.76 |           64.07 |             86.95 |            nan    |         6.97 |             68.36 | swing              |              nan    |                nan    |               nan    |
|      7 | REP.MC    | REP.MC                         | EUROPE   |               32.44 |             79.13 |         82.36 |         82.36 |          75.91 |        73.6  |           57.26 |             77.14 |             82.12 |         3.69 |             73.14 | short              |                4.48 |                  1.98 |                 1.57 |
|      8 | KIN.BR    | KIN.BR                         | EUROPE   |                1.35 |             78.3  |         80.84 |         81.67 |          75.76 |        66.99 |           90.08 |             63.12 |             19.95 |         3.72 |             73.14 | swing              |                0.55 |                 -0.08 |                -0.06 |
|      9 | HSHP      | HSHP                           | US       |                0.75 |             77.87 |         81.75 |         78.11 |          77.63 |        68.93 |           87.3  |            nan    |             29    |         4.82 |             62.84 | short              |               -4.93 |                nan    |               nan    |
|     10 | PARR      | Par Pacific Holdings, Inc.     | US       |                3.46 |             77.77 |         66.13 |         77.22 |          78.83 |        78.32 |           82.79 |             69.3  |             64.91 |         7    |             84.98 | medium             |                3.5  |                  0.7  |                 0.77 |
|     11 | TRMD      | TRMD                           | US       |                3.1  |             77.77 |         80.49 |         73.02 |          75.35 |        80.2  |           86.74 |             50.26 |             84.39 |         5.46 |             69.68 | short              |              nan    |                nan    |               nan    |
|     12 | DINO      | HF Sinclair Corporation        | US       |               16.54 |             77.73 |         72.6  |         83.58 |          80.96 |        74.5  |           69.75 |             78.11 |             65.28 |         5.43 |             85.41 | swing              |               -2.55 |                 -0.25 |                -0.23 |
|     13 | DHT       | DHT                            | US       |                3.01 |             77.46 |         75.74 |         73.48 |          79.18 |        80.09 |           90.26 |             81.75 |             64.06 |         4.67 |             73.14 | long               |               -4.61 |                  0.21 |                 0.05 |
|     14 | MPC       | Marathon Petroleum Corporation | US       |               95.45 |             77.37 |         75.23 |         83.07 |          79.51 |        71.34 |           68.93 |             79.15 |             54.14 |         4.92 |             86.8  | swing              |               -9.78 |                nan    |               nan    |
|     15 | AMS.SW    | AMS.SW                         | EUROPE   |                2.38 |             76.84 |         86.58 |         82.52 |          71.16 |        53.2  |           51.69 |             87.22 |             11.34 |         8.64 |             73.14 | short              |                5.77 |                  5.44 |               nan    |
|     16 | HALO      | HALO                           | US       |               11.4  |             76.63 |         79.44 |         79.25 |          74.01 |        71.06 |           88.3  |             51.09 |             48.34 |         5.92 |             72.11 | short              |                0.52 |                nan    |               nan    |
|     17 | VLO       | Valero Energy Corporation      | US       |               94.72 |             76.49 |         75.2  |         81.28 |          77.79 |        69.49 |           68.93 |             75.38 |             48.84 |         4.58 |             87.14 | swing              |               -9.25 |                 -0.16 |                 0.05 |
|     18 | ABN.AS    | ABN.AS                         | EUROPE   |               35.48 |             76.42 |         76.73 |         78.24 |          76.12 |        71.49 |           77.97 |             65.65 |             53.76 |         2.82 |             73.14 | swing              |                0.36 |                  1.47 |                 1.43 |
|     19 | CMBT.BR   | Cmb.Tech NV                    | EUROPE   |                4.9  |             76.41 |         75.15 |         77.67 |          77.97 |        71.87 |           79.46 |             80.92 |             50.5  |         3.76 |             83.78 | medium             |               -7.77 |                  0.05 |                 0.29 |
|     20 | SSABBH.HE | SSABBH.HE                      | EUROPE   |                9.28 |             76.36 |         59.95 |         71.93 |          80.79 |        82.74 |           69.39 |            nan    |            100    |         4.17 |             62.84 | long               |                1.18 |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               13.29 |                  82.01 |                    79.51 |                 79.22 |              79.67 |                70.28 |                   29.72 |           79.54 |            nan    |       0.486 |         nan |       nan |        1.16 |       nan    |          0.67 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.06 |                    74.44 |                 76.47 |              74.04 |                87.41 |                   12.59 |           87.73 |             56.98 |       0.86  |         nan |       nan |      nan    |       -79.21 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | INVA     | Innoviva, Inc.                       | US       |                1.32 |                  79.91 |                    74.39 |                 74.61 |              74.65 |                77.51 |                   22.49 |           89.08 |             31.66 |       0.073 |         nan |       nan |        6.49 |         9.49 |          4.88 |        0.25 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.63 |                    71.29 |                 72.71 |              69.79 |                77.7  |                   22.3  |           77.31 |             78.29 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.22 |                  70.97 |                    70.91 |                 70.48 |              71.65 |                74.36 |                   25.64 |           67.26 |            nan    |       0.23  |         nan |       nan |        1.54 |       nan    |          3    |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  73.85 |                    70.81 |                 71.52 |              71.79 |                79.45 |                   20.55 |           79.58 |             43.2  |       0.609 |         nan |       nan |        4.72 |      -132.92 |          2.29 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.82 |                  57.98 |                    70.54 |                 74.54 |              65.5  |                87.48 |                   12.52 |           93.28 |             80.07 |     nan     |         nan |       nan |      nan    |         9.38 |         10.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.15 |                 70.19 |              73.02 |                57.63 |                   42.37 |           61.58 |             80.03 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            7 | DINO     | HF Sinclair Corporation              | US       |               16.54 |                  66.83 |                    70.15 |                 71.03 |              70.09 |                78.67 |                   21.33 |           69.75 |             78.11 |       0.107 |         nan |       nan |        6.27 |         9.02 |         10.42 |        1.81 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  59.07 |                    70    |                 73.71 |              65.46 |                81.98 |                   18.02 |           90.26 |             81.75 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1517.87 |                  62.99 |                    69.99 |                 70.6  |              64.07 |                79.76 |                   20.24 |           95.03 |             43.54 |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|            9 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.43 |                 68.99 |              67.45 |                68.16 |                   31.84 |           85.87 |             32.14 |       0.609 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  59.94 |                    69.3  |                 71.02 |              64.59 |                75.06 |                   24.94 |           83.6  |             79.26 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|           11 | BBWI     | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.04 |                 66.53 |              67.85 |                59.1  |                   40.9  |           75.98 |             33.23 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.44 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|           12 | MOMO     | Hello Group Inc.                     | OTHER    |                0.63 |                  78.54 |                    69    |                 66.22 |              72.11 |                72.83 |                   27.17 |           65.09 |             24.57 |       0.832 |         nan |       nan |       -5.95 |         4.85 |          4.93 |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BP       | BP                                   | US       |               96.82 |                  57.61 |                    68.99 |                 72.77 |              64.57 |                81.9  |                   18.1  |           88.16 |             83.47 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.25 |                    68.66 |                 71.17 |              65.48 |                72.05 |                   27.95 |           83.22 |             76.92 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  56.27 |                    68.15 |                 72.29 |              62.91 |                80.41 |                   19.59 |           92.05 |             79.28 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.84 |                  56.03 |                    67.72 |                 71.57 |              61.94 |                84.3  |                   15.7  |           96.28 |             64.24 |     nan     |         nan |       nan |      nan    |        10.89 |         14.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    67.69 |                 66.72 |              69.91 |                59.61 |                   40.39 |           61.46 |             61.97 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.58 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               13.29 |                  82.01 |                    79.51 |                 79.22 |              79.67 |                70.28 |                   29.72 |           79.54 |            nan    |       0.486 |         nan |       nan |        1.16 |       nan    |          0.67 |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            2 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.06 |                    74.44 |                 76.47 |              74.04 |                87.41 |                   12.59 |           87.73 |             56.98 |       0.86  |         nan |       nan |      nan    |       -79.21 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | INVA     | Innoviva, Inc.                       | US       |                1.32 |                  79.91 |                    74.39 |                 74.61 |              74.65 |                77.51 |                   22.49 |           89.08 |             31.66 |       0.073 |         nan |       nan |        6.49 |         9.49 |          4.88 |        0.25 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.82 |                  57.98 |                    70.54 |                 74.54 |              65.5  |                87.48 |                   12.52 |           93.28 |             80.07 |     nan     |         nan |       nan |      nan    |         9.38 |         10.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  59.07 |                    70    |                 73.71 |              65.46 |                81.98 |                   18.02 |           90.26 |             81.75 |     nan     |         nan |       nan |      nan    |         9.97 |          7.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               96.82 |                  57.61 |                    68.99 |                 72.77 |              64.57 |                81.9  |                   18.1  |           88.16 |             83.47 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.63 |                    71.29 |                 72.71 |              69.79 |                77.7  |                   22.3  |           77.31 |             78.29 |     nan     |         nan |       nan |      nan    |         9.07 |         10.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  56.27 |                    68.15 |                 72.29 |              62.91 |                80.41 |                   19.59 |           92.05 |             79.28 |     nan     |         nan |       nan |      nan    |        10.47 |          7.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.84 |                  56.03 |                    67.72 |                 71.57 |              61.94 |                84.3  |                   15.7  |           96.28 |             64.24 |     nan     |         nan |       nan |      nan    |        10.89 |         14.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  73.85 |                    70.81 |                 71.52 |              71.79 |                79.45 |                   20.55 |           79.58 |             43.2  |       0.609 |         nan |       nan |        4.72 |      -132.92 |          2.29 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.25 |                    68.66 |                 71.17 |              65.48 |                72.05 |                   27.95 |           83.22 |             76.92 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | DINO     | HF Sinclair Corporation              | US       |               16.54 |                  66.83 |                    70.15 |                 71.03 |              70.09 |                78.67 |                   21.33 |           69.75 |             78.11 |       0.107 |         nan |       nan |        6.27 |         9.02 |         10.42 |        1.81 |                 nan |              nan |                  12 |                  0.63 |
|           10 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  59.94 |                    69.3  |                 71.02 |              64.59 |                75.06 |                   24.94 |           83.6  |             79.26 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1517.87 |                  62.99 |                    69.99 |                 70.6  |              64.07 |                79.76 |                   20.24 |           95.03 |             43.54 |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|            4 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.22 |                  70.97 |                    70.91 |                 70.48 |              71.65 |                74.36 |                   25.64 |           67.26 |            nan    |       0.23  |         nan |       nan |        1.54 |       nan    |          3    |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.15 |                 70.19 |              73.02 |                57.63 |                   42.37 |           61.58 |             80.03 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  61.66 |                    67.48 |                 69.38 |              64.51 |                76.2  |                   23.8  |           82.41 |             64.01 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                               | EUROPE   |                1.67 |                  55.78 |                    65.82 |                 69.32 |              59.77 |                80.1  |                   19.9  |           97.68 |             51.88 |     nan     |         nan |       nan |      nan    |        10.46 |         10.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               41.13 |                  64.39 |                    67.53 |                 69.24 |              65.04 |                67.64 |                   32.36 |           78.93 |            nan    |       0.42  |         nan |       nan |        7.45 |       nan    |          2.68 |        0.58 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BEN      | BEN                                  | US       |               14.68 |                  54.69 |                    65.47 |                 69.01 |              60.67 |                79.68 |                   20.32 |           88.09 |             69.53 |     nan     |         nan |       nan |      nan    |        10.42 |         22.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                             | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | DELL     | DELL                             | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        80.45 |         86.48 |         82.34 |          79.22 |        66.66 |           74.81 |             85.12 |         7.8  |
|               2 | FRO      | FRO                              | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        80.42 |         81.41 |         77.65 |          81.98 |        79.94 |           92.05 |             79.28 |         5.51 |
|               3 | SHELL.AS | SHELL.AS                         | EUROPE   |              234.82 |                     0.04 |    -0.02 |      0.04 |                  63.32 |                        78.32 |         76.3  |         75.46 |          75.75 |        83.22 |           93.28 |             80.07 |         2.39 |
|               4 | DHT      | DHT                              | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        77.91 |         75.74 |         73.48 |          79.18 |        80.09 |           90.26 |             81.75 |         4.67 |
|               5 | NAT      | NAT                              | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        77.44 |         78.78 |         75.29 |          76.73 |        71.54 |           87.96 |             69.5  |         4.78 |
|               6 | CMBT.BR  | Cmb.Tech NV                      | EUROPE   |                4.9  |                     0.07 |    -0.02 |      0.11 |                  70.51 |                        77.44 |         75.15 |         77.67 |          77.97 |        71.87 |           79.46 |             80.92 |         3.76 |
|               7 | MPC      | Marathon Petroleum Corporation   | US       |               95.45 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        77.42 |         75.23 |         83.07 |          79.51 |        71.34 |           68.93 |             79.15 |         4.92 |
|               8 | AVAH     | Aveanna Healthcare Holdings Inc. | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        77.24 |         59.46 |         78.75 |          77.41 |        69    |           77.07 |             74.76 |         7.39 |
|               9 | DINO     | HF Sinclair Corporation          | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        76.79 |         72.6  |         83.58 |          80.96 |        74.5  |           69.75 |             78.11 |         5.43 |
|              10 | GH       | GH                               | US       |               20.74 |                     0.03 |     0.01 |      0.09 |                  54.36 |                        76.05 |         76.93 |         84.07 |          81.88 |        74.76 |           64.07 |             86.95 |         6.97 |
|              11 | VLO      | Valero Energy Corporation        | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        75.55 |         75.2  |         81.28 |          77.79 |        69.49 |           68.93 |             75.38 |         4.58 |
|              12 | DSX      | Diana Shipping Inc.              | OTHER    |                0.32 |                     0.07 |    -0.03 |      0.07 |                  71.96 |                        75.45 |         75.52 |         75.34 |          74.31 |        76.36 |           78.68 |             74.38 |         4.94 |
|              13 | PARR     | Par Pacific Holdings, Inc.       | US       |                3.46 |                     0.09 |    -0.06 |      0.06 |                  65.86 |                        75.44 |         66.13 |         77.22 |          78.83 |        78.32 |           82.79 |             69.3  |         7    |
|              14 | C5H.IR   | C5H.IR                           | EUROPE   |                1.67 |                     0.05 |    -0    |      0.06 |                  66.36 |                        75.05 |         75.55 |         68.01 |          72.85 |        77.81 |           97.68 |             51.88 |         2.65 |
|              15 | BIRG.IR  | BIRG.IR                          | EUROPE   |               18.84 |                     0.02 |    -0.02 |      0.05 |                  53.94 |                        74.73 |         75.5  |         73.33 |          76.01 |        79.43 |           96.28 |             64.24 |         2.18 |
|              16 | BP       | BP                               | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        74.44 |         60.24 |         64.27 |          69.97 |        76.84 |           88.16 |             83.47 |         4.46 |
|              17 | SHEL     | SHEL                             | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        74.02 |         65.69 |         68.73 |          69.69 |        76.05 |           77.31 |             78.29 |         3    |
|              18 | DAR      | DAR                              | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        73.7  |         51.45 |         65.28 |          76.43 |        82.07 |           90.97 |             84.51 |         4.6  |
|              19 | PSX      | Phillips 66                      | US       |               89.8  |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        73.26 |         74.69 |         79.77 |          72    |        60.05 |           52.72 |             77.72 |         4.57 |
|              20 | TRMD     | TRMD                             | US       |                3.1  |                     0.08 |     0    |      0.19 |                  51.92 |                        72.92 |         80.49 |         73.02 |          75.35 |        80.2  |           86.74 |             50.26 |         5.46 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol    | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | INDU-C.ST | AB Industrivärden (publ)     | EUROPE   |               20.85 |             67.61 |         70.06 |         66.31 |          68.91 |        64.26 |           82.09 |             81.63 |             23.95 |         2.48 |             64.78 | short              |               12.46 |                  3.8  |                 2.89 |
|    nan | COST      | Costco Wholesale Corporation | US       |              347.91 |             40.98 |         38.69 |         33.84 |          43.28 |        50.12 |           77.39 |             44.78 |             26    |         8.5  |             89.81 | long               |                0.14 |                  1.18 |                 1.18 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    222 | ITRG     | ITRG   | US       |                0.51 |             61.16 |         64.59 |         57.72 |          56.64 |        65.43 |           60.67 |             63.63 |             85.26 |         8.18 |             68.32 | long               |                5.36 |                  5.52 |                 5.6  |
|     15 | AMS.SW   | AMS.SW | EUROPE   |                2.38 |             76.84 |         86.58 |         82.52 |          71.16 |        53.2  |           51.69 |             87.22 |             11.34 |         8.64 |             73.14 | short              |                5.77 |                  5.44 |               nan    |
|    132 | VZLA     | VZLA   | OTHER    |                1.33 |             64.99 |         77.05 |         68.02 |          61.96 |        60.19 |           80.36 |            nan    |             33.33 |         8.36 |             61.82 | short              |                7.47 |                  4.87 |               nan    |
|      5 | AMC      | AMC    | US       |                2.31 |             79.6  |         80.73 |         84.43 |          78.47 |        77.92 |           85.87 |             78.26 |            nan    |         9.55 |             65.07 | swing              |                3.4  |                  4.14 |                 3.88 |
|    113 | RBI.VI   | RBI.VI | EUROPE   |               21.38 |             66.59 |         71.6  |         71.07 |          62.11 |        50.38 |            8.28 |             67.05 |             75.69 |         4.23 |             71.77 | short              |                6.34 |                  3.97 |                 3.33 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    434 | TEVA     | TEVA                  | US       |               40.2  |             51.86 |         65.79 |         57.13 |          46.6  |        37.77 |           13.14 |             31.42 |             47.38 |         4.69 |             72.34 | short              |               -3.15 |                 -3.57 |                -3.67 |
|    698 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             24.64 |         21.94 |         19.7  |          27.33 |        36.14 |           43.7  |             25.49 |             45.6  |         6.21 |             84.71 | long               |               -0.15 |                 -3.47 |               nan    |
|    590 | FRSH     | FRSH                  | US       |                2.83 |             43.18 |         36.64 |         55.81 |          46.69 |        39.67 |           31    |             31.55 |             43.14 |         7.58 |             72.11 | swing              |               -3.22 |                 -3.08 |                -2.35 |
|    411 | CHYM     | CHYM                  | US       |                9.45 |             52.97 |         35.75 |         60.49 |          57.29 |        48.64 |           49.87 |             44.92 |             29.22 |         7.91 |             71.32 | swing              |               -2.16 |                 -2.69 |                -2.08 |
|    172 | HAFN     | HAFN                  | US       |                4.02 |             63.44 |         72.72 |         62.73 |          61.54 |        64.15 |           76.11 |             20.35 |             57.46 |         5.61 |             69.68 | short              |               -2.53 |                 -2.67 |                -3.55 |

## Duplicate-security checks

- KRX.IR duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- SDLFL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates TEK.L (security_id=ISIN:PLCTHQM00018)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
- Excluded by hard/data filters: **297**
- Event watch (otherwise eligible): **2**
- Final eligible: **701**
- Eligible change vs previous stored run: **-8**

Top exclusion categories:
- liquidity: 239
- price: 188
- market_cap: 162
- price_history: 17
- data_confidence: 9
- duplicate_listing: 4
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DINO | 12 | 7 | 9 | 5 | 2 | value,pullback,quality_value |
| DELL | 3 |  | 1 |  | 2 | main,pullback |
| FRO | 4 |  | 2 |  | 2 | main,pullback |
| GH | 6 |  | 10 |  | 2 | main,pullback |
| PBR-A | 49 | 6 | 23 | 9 | 1 | value,quality_value |
| NVDA | 73 | 10 |  | 6 | 1 | value,quality_value |
| BION.SW | 176 | 2 | 99 | 2 | 1 | value,quality_value |
| 0Q2N.IL | 191 | 4 |  | 8 | 1 | value,quality_value |
| AVGO | 256 | 8 |  | 7 | 1 | value,quality_value |
| NWL.MI | 257 | 5 | 50 | 4 | 1 | value,quality_value |
| INVA | 419 | 3 | 184 | 3 | 1 | value,quality_value |
| 0QXR.IL | 631 | 1 |  | 1 | 1 | value,quality_value |
| MU | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| AMC | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (MU, HPE, DELL, FRO, AMC, GH, REP.MC, KIN.BR, HSHP)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (DELL, FRO, NAT, GH)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 71.84 | 73.85 | 70.17 | 79.58 | 43.20 | 79.45 | 59.66 |
| 2 | BION.SW | value+pullback | 71.11 | 73.06 | 51.40 | 87.73 | 56.98 | 87.41 | 63.16 |
| 3 | 0Q2N.IL | value+pullback | 70.15 | 70.97 | 75.61 | 67.26 |  | 74.36 | 62.56 |
| 4 | DINO | value+pullback | 69.61 | 66.83 | 62.23 | 69.75 | 78.11 | 78.67 | 77.73 |
| 5 | SDF.DE | value+pullback | 69.21 | 62.76 | 74.59 | 88.20 | 39.47 | 72.79 | 62.12 |
| 6 | DSX | value+pullback | 68.67 | 59.17 | 71.96 | 78.68 | 74.38 | 68.44 | 75.43 |
| 7 | PBR-A | value+pullback | 68.64 | 75.89 | 68.43 | 61.58 | 80.03 | 57.63 | 72.29 |
| 8 | INVA | value+pullback | 67.39 | 79.91 | 45.55 | 89.08 | 31.66 | 77.51 | 52.58 |
| 9 | STNE | value+pullback | 66.98 | 72.17 | 62.40 | 85.87 | 32.14 | 68.16 | 49.08 |
| 10 | PARR | value+pullback | 66.60 | 63.76 | 65.86 | 82.79 | 69.30 | 58.32 | 77.77 |
| 11 | GSL | value+pullback | 65.66 | 66.03 | 59.10 | 87.93 | 30.08 | 74.40 | 63.67 |
| 12 | 0P6O.IL | value+pullback | 64.46 | 64.39 | 59.09 | 78.93 |  | 67.64 | 48.68 |
| 13 | WB | value+pullback | 63.33 | 69.71 | 64.82 | 78.95 | 17.25 | 63.22 | 41.08 |
| 14 | UNIT | value+pullback | 63.10 | 80.01 | 70.08 | 64.98 | 29.21 | 44.54 | 42.70 |
| 15 | PAH3.DE | value+pullback | 62.83 | 70.93 | 63.07 | 45.00 | 59.67 | 65.31 | 43.66 |
| 16 | CNC | value+pullback | 62.66 | 75.23 | 69.23 | 43.57 | 62.53 | 50.00 | 60.43 |
| 17 | DBX | value+pullback | 61.87 | 67.97 | 70.54 | 52.96 | 41.52 | 58.75 | 58.99 |
| 18 | GDRX | value+pullback | 61.61 | 71.36 | 74.05 | 62.47 | 32.11 | 45.52 | 57.29 |
| 19 | VOW3.DE | value+pullback | 60.88 | 67.75 | 56.64 | 67.70 | 32.68 | 64.84 | 45.42 |
| 20 | DFDS.CO | value+pullback | 60.71 | 60.17 | 62.60 | 58.48 | 72.52 | 54.92 | 74.55 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 8/10 | 7/10 | 0/10 | 72.7 | 1 / 9 |
| Top 25 | 25/25 | 23/25 | 23/25 | 21/25 | 0/25 | 73.1 | 9 / 16 |
| Top 50 | 48/50 | 48/50 | 48/50 | 44/50 | 0/50 | 73.1 | 19 / 31 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=3, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
