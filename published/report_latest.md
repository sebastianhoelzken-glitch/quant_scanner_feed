# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-24

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
- **OTHER:** 64.3/100
- **US:** 80.8/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC      | US       |               99.04 |             86.17 |         77.74 |         88.41 |          87.89 |        84.46 |           84.52 |             89.57 |             73.59 |         4.37 |             73.14 | swing              |               -0.98 |                nan    |               nan    |
|      2 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |             83.55 |         80.4  |         83.48 |          85.3  |        83.62 |           95.74 |             77.25 |             65    |         3.71 |             73.14 | medium             |               -0.64 |                  1.48 |                 1.36 |
|      3 | HPE      | HPE      | US       |               72.28 |             83.46 |         90.98 |         85.76 |          81.16 |        72.55 |           72.26 |             80.99 |             52.64 |         7.01 |             72.34 | short              |                2.1  |                  0.73 |               nan    |
|      4 | MU       | MU       | US       |             1057.46 |             83.32 |         80.78 |         74.93 |          86.45 |        85.85 |           95.06 |             81.36 |             72.99 |         8.24 |             73.14 | medium             |                2.55 |                  2.88 |                 2.22 |
|      5 | VLO      | VLO      | US       |               94.53 |             83.31 |         76.68 |         85.58 |          85.16 |        81.45 |           86.14 |             81.04 |             64.17 |         3.71 |             69.68 | swing              |               -2.44 |                  1.2  |                 1.08 |
|      6 | DELL     | DELL     | US       |              305.37 |             82.56 |         84.22 |         84.25 |          80.9  |        68.93 |           72.77 |             85.91 |             35.29 |         7.85 |             72.23 | swing              |               -1.06 |                  0.07 |                -0.1  |
|      7 | FRO      | FRO      | US       |                9.25 |             82.18 |         82.05 |         82.32 |          83.8  |        81.74 |           91.03 |             80.28 |             60.89 |         5.58 |             73.14 | medium             |               -2.73 |                  0.56 |                 0.51 |
|      8 | HSHP     | HSHP     | US       |                0.75 |             81.36 |         85.16 |         83.13 |          79.59 |        70.05 |           86.16 |            nan    |             28.8  |         4.84 |             62.84 | short              |               -1.44 |                nan    |               nan    |
|      9 | PSX      | PSX      | US       |               89.4  |             80.92 |         78.95 |         85.6  |          82.89 |        78.63 |           79.77 |             85.36 |             62    |         3.85 |             73.14 | swing              |               -2.95 |                  1.17 |                 1.22 |
|     10 | AMC      | AMC      | US       |                2.24 |             80.68 |         81.09 |         86.47 |          80.28 |        79.5  |           85.31 |             78.97 |            nan    |         9.53 |             65.07 | swing              |                4.49 |                  4.36 |                 4.05 |
|     11 | OKTA     | OKTA     | US       |               31.36 |             79.07 |         91.45 |         85.06 |          73.07 |        59.79 |           71.25 |             69.5  |             14.24 |         7.85 |             71.77 | short              |                0.54 |                  1.06 |                 1.02 |
|     12 | DHT      | DHT      | US       |                3    |             78.89 |         77.11 |         77.45 |          80.32 |        81.59 |           88.44 |             82.85 |             66.09 |         4.77 |             73.14 | long               |               -3.18 |                  0.5  |                 0.26 |
|     13 | REP.MC   | REP.MC   | EUROPE   |               32.74 |             78.59 |         83.23 |         82.18 |          74.99 |        70.81 |           57.68 |             79.47 |             72.72 |         3.78 |             73.14 | short              |                3.93 |                  1.87 |                 1.49 |
|     14 | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |             78.25 |         79.83 |         76.66 |          75.13 |        80.82 |           92.62 |             81.84 |             66.95 |         2.45 |             73.14 | long               |                4.09 |                  2.84 |                 2.65 |
|     15 | KIN.BR   | KIN.BR   | EUROPE   |                1.36 |             77.86 |         81.06 |         81.23 |          74.66 |        65.17 |           88.81 |             64.77 |             16.91 |         3.8  |             73.14 | swing              |                0.11 |                 -0.17 |                -0.13 |
|     16 | NAT      | NAT      | US       |                1.41 |             77.8  |         80.15 |         77.56 |          78.04 |        73.81 |           87.51 |             70.26 |             41.73 |         4.96 |             73.14 | short              |               -2.76 |                 -0.06 |                 0.03 |
|     17 | AMS.SW   | AMS.SW   | EUROPE   |                2.49 |             77.05 |         87.47 |         83.59 |          70.51 |        51.61 |           50.63 |             88.84 |              8.49 |         8.67 |             73.14 | short              |                5.98 |                  5.48 |               nan    |
|     18 | HALO     | HALO     | US       |               11.15 |             76.8  |         78.32 |         80.11 |          75.27 |        72    |           85.74 |             52.23 |             50.41 |         6.05 |             72.11 | swing              |                0.69 |                nan    |               nan    |
|     19 | P        | P        | US       |               31.92 |             76.68 |         87.55 |         82.48 |          70.88 |        58.44 |           69.82 |             85.67 |             13.96 |         8.1  |             72.68 | short              |               -0.69 |                  2.41 |                 1.74 |
|     20 | ABN.AS   | ABN.AS   | EUROPE   |               35.45 |             76.64 |         77.87 |         78.29 |          75.4  |        69.81 |           76.6  |             68.28 |             50.5  |         2.87 |             73.14 | swing              |                0.58 |                  1.52 |                 1.46 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  73.97 |                    74.45 |                 76.12 |              74.64 |                86.63 |                   13.37 |           84.64 |             57.83 |       0.87  |         nan |       nan |      nan    |       -78.29 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              237.89 |                  59.08 |                    71.27 |                 75.16 |              66.49 |                87.59 |                   12.41 |           92.62 |             81.84 |     nan     |         nan |       nan |      nan    |         9.5  |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3    |                  61.22 |                    70.95 |                 74.27 |              66.98 |                81.22 |                   18.78 |           88.44 |             82.85 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    70.72 |                 72.71 |              65.75 |                77.34 |                   22.66 |           86.9  |             79.97 |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |              100.09 |                  60.48 |                    70.61 |                 73.98 |              66.76 |                81.69 |                   18.31 |           86.97 |             85.15 |     nan     |         nan |       nan |      nan    |         9.11 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              237.78 |                  65.88 |                    70.29 |                 71.57 |              69.2  |                76.46 |                   23.54 |           73.83 |             79.99 |     nan     |         nan |       nan |      nan    |         9.21 |         10.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.37 |                  68.48 |                    69.73 |                 71.67 |              68.62 |                68.57 |                   31.43 |           80.43 |             69.71 |       0.021 |         nan |       nan |        3.78 |         5.56 |          4.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  74.98 |                    69.64 |                 69.66 |              72.26 |                57.39 |                   42.61 |           61.58 |             79.45 |       0.14  |         nan |       nan |        1.8  |         4.78 |          4.8  |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|            5 | STNE     | StoneCo Ltd.                         | OTHER    |                1.91 |                  72.17 |                    69.42 |                 68.99 |              67.44 |                68.01 |                   31.99 |           85.87 |             32.3  |       0.632 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.46 |                    69.42 |                 69.45 |              70.31 |                61.42 |                   38.58 |           70.56 |             63.63 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.13 |                  62.86 |                    69.18 |                 71.63 |              66.3  |                72.28 |                   27.72 |           81.84 |             80.29 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | BBWI     | Bath & Body Works, Inc.              | US       |                3    |                  74.85 |                    69.12 |                 66.64 |              67.93 |                59.17 |                   40.83 |           75.98 |             33.94 |       0.223 |         nan |       nan |        5.61 |         6.11 |          4.5  |        0.7  |                 nan |              nan |                  11 |                  0.58 |
|            8 | INVA     | Innoviva, Inc.                       | US       |                1.28 |                  64.94 |                    69.12 |                 71.56 |              66.45 |                82.49 |                   17.51 |           90.78 |             48.49 |       0.075 |         nan |       nan |        6.22 |         9.16 |          4.87 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.89 |                  55.81 |                    69.01 |                 73.41 |              63.24 |                85.18 |                   14.82 |           95.74 |             77.25 |     nan     |         nan |       nan |      nan    |         9.3  |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.25 |                  57.17 |                    68.57 |                 72.54 |              63.61 |                80.09 |                   19.91 |           91.03 |             80.28 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.75 |                  73.61 |                    68.46 |                 68.8  |              69.69 |                68.63 |                   31.37 |           75.5  |             43.35 |       0.617 |         nan |       nan |        4.65 |      -131.16 |          2.26 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1480.26 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.36 |                   21.64 |           92.29 |             44.24 |       0.018 |         nan |       nan |       33.1  |        18.31 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.76 |                  55.03 |                    67.43 |                 71.49 |              61.53 |                84.83 |                   15.17 |           96.18 |             66.34 |     nan     |         nan |       nan |      nan    |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.48 |                  62.66 |                    67.25 |                 68.72 |              64.04 |                76.57 |                   23.43 |           85.3  |             51.44 |     nan     |         nan |       nan |      nan    |         8.62 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.22 |                  66.96 |                    66.92 |                 66.42 |              67.75 |                70.92 |                   29.08 |           62.76 |            nan    |       0.23  |         nan |       nan |        1.54 |       nan    |          3    |      nan    |                 nan |              nan |                   8 |                  0.42 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  73.97 |                    74.45 |                 76.12 |              74.64 |                86.63 |                   13.37 |           84.64 |             57.83 |       0.87  |         nan |       nan |      nan    |       -78.29 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              237.89 |                  59.08 |                    71.27 |                 75.16 |              66.49 |                87.59 |                   12.41 |           92.62 |             81.84 |     nan     |         nan |       nan |      nan    |         9.5  |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3    |                  61.22 |                    70.95 |                 74.27 |              66.98 |                81.22 |                   18.78 |           88.44 |             82.85 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.09 |                  60.48 |                    70.61 |                 73.98 |              66.76 |                81.69 |                   18.31 |           86.97 |             85.15 |     nan     |         nan |       nan |      nan    |         9.11 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.89 |                  55.81 |                    69.01 |                 73.41 |              63.24 |                85.18 |                   14.82 |           95.74 |             77.25 |     nan     |         nan |       nan |      nan    |         9.3  |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    70.72 |                 72.71 |              65.75 |                77.34 |                   22.66 |           86.9  |             79.97 |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.25 |                  57.17 |                    68.57 |                 72.54 |              63.61 |                80.09 |                   19.91 |           91.03 |             80.28 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.37 |                  68.48 |                    69.73 |                 71.67 |              68.62 |                68.57 |                   31.43 |           80.43 |             69.71 |       0.021 |         nan |       nan |        3.78 |         5.56 |          4.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM       | SM                                   | US       |                7.13 |                  62.86 |                    69.18 |                 71.63 |              66.3  |                72.28 |                   27.72 |           81.84 |             80.29 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              237.78 |                  65.88 |                    70.29 |                 71.57 |              69.2  |                76.46 |                   23.54 |           73.83 |             79.99 |     nan     |         nan |       nan |      nan    |         9.21 |         10.55 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | INVA     | Innoviva, Inc.                       | US       |                1.28 |                  64.94 |                    69.12 |                 71.56 |              66.45 |                82.49 |                   17.51 |           90.78 |             48.49 |       0.075 |         nan |       nan |        6.22 |         9.16 |          4.87 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.76 |                  55.03 |                    67.43 |                 71.49 |              61.53 |                84.83 |                   15.17 |           96.18 |             66.34 |     nan     |         nan |       nan |      nan    |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |             1057.46 |                  49.51 |                    64.42 |                 69.83 |              57.67 |                77.17 |                   22.83 |           95.06 |             81.36 |     nan     |         nan |       nan |      nan    |         6.74 |         24.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               99.04 |                  50.64 |                    65.08 |                 69.69 |              60.22 |                82.23 |                   17.77 |           84.52 |             89.57 |     nan     |         nan |       nan |      nan    |         8.24 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  74.98 |                    69.64 |                 69.66 |              72.26 |                57.39 |                   42.61 |           61.58 |             79.45 |       0.14  |         nan |       nan |        1.8  |         4.78 |          4.8  |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|            6 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.46 |                    69.42 |                 69.45 |              70.31 |                61.42 |                   38.58 |           70.56 |             63.63 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | STNE     | StoneCo Ltd.                         | OTHER    |                1.91 |                  72.17 |                    69.42 |                 68.99 |              67.44 |                68.01 |                   31.99 |           85.87 |             32.3  |       0.632 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1480.26 |                  60.81 |                    68.24 |                 68.83 |              62.31 |                78.36 |                   21.64 |           92.29 |             44.24 |       0.018 |         nan |       nan |       33.1  |        18.31 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|            9 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.75 |                  73.61 |                    68.46 |                 68.8  |              69.69 |                68.63 |                   31.37 |           75.5  |             43.35 |       0.617 |         nan |       nan |        4.65 |      -131.16 |          2.26 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.48 |                  62.66 |                    67.25 |                 68.72 |              64.04 |                76.57 |                   23.43 |           85.3  |             51.44 |     nan     |         nan |       nan |      nan    |         8.62 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC      | MPC      | US       |               99.04 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        85    |         77.74 |         88.41 |          87.89 |        84.46 |           84.52 |             89.57 |         4.37 |
|               2 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |                     0.07 |    -0.02 |      0.11 |                  70.16 |                        83    |         80.4  |         83.48 |          85.3  |        83.62 |           95.74 |             77.25 |         3.71 |
|               3 | PSX      | PSX      | US       |               89.4  |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        82.63 |         78.95 |         85.6  |          82.89 |        78.63 |           79.77 |             85.36 |         3.85 |
|               4 | FRO      | FRO      | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        82.54 |         82.05 |         82.32 |          83.8  |        81.74 |           91.03 |             80.28 |         5.58 |
|               5 | VLO      | VLO      | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        82.47 |         76.68 |         85.58 |          85.16 |        81.45 |           86.14 |             81.04 |         3.71 |
|               6 | DELL     | DELL     | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        80.26 |         84.22 |         84.25 |          80.9  |        68.93 |           72.77 |             85.91 |         7.85 |
|               7 | DHT      | DHT      | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        79.97 |         77.11 |         77.45 |          80.32 |        81.59 |           88.44 |             82.85 |         4.77 |
|               8 | BP       | BP       | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        79.15 |         75.46 |         73    |          72.53 |        78.85 |           86.97 |             85.15 |         4.54 |
|               9 | NAT      | NAT      | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        78.78 |         80.15 |         77.56 |          78.04 |        73.81 |           87.51 |             70.26 |         4.96 |
|              10 | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |                     0.02 |    -0    |      0.06 |                  52.58 |                        78.6  |         79.83 |         76.66 |          75.13 |        80.82 |           92.62 |             81.84 |         2.45 |
|              11 | SMTC     | SMTC     | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        77.45 |         85.28 |         73.69 |          74.32 |        61.81 |           73.57 |             84.61 |         8.47 |
|              12 | EQNR     | EQNR     | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        77.24 |         70.85 |         76.94 |          74.82 |        74.97 |           74.97 |             83.59 |         5.72 |
|              13 | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                     0.05 |    -0    |      0.06 |                  67.99 |                        75.9  |         76.12 |         68.55 |          72.31 |        76.05 |           97.73 |             53.97 |         2.72 |
|              14 | BIRG.IR  | BIRG.IR  | EUROPE   |               18.76 |                     0.02 |    -0.02 |      0.05 |                  57.74 |                        75.55 |         75.4  |         73.22 |          75.14 |        77.21 |           96.18 |             66.34 |         2.23 |
|              15 | DAR      | DAR      | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        75.36 |         55.64 |         69.17 |          78.13 |        84.11 |           90.31 |             85.83 |         4.78 |
|              16 | APA      | APA      | US       |               13.37 |                     0.08 |    -0.02 |      0.06 |                  63.54 |                        74.85 |         73.13 |         76.19 |          75.34 |        77.98 |           75.34 |             81.01 |         6.07 |
|              17 | AVAH     | AVAH     | US       |                2.44 |                     0.11 |    -0.1  |     -0.06 |                  65.6  |                        74.47 |         52.52 |         75.67 |          77.98 |        74.05 |           92.78 |             54.96 |         7.76 |
|              18 | CIRSA.MC | CIRSA.MC | EUROPE   |                3.26 |                     0.02 |    -0.01 |      0.4  |                  49.44 |                        74.45 |         83.93 |         80.16 |          69.38 |        68.16 |           81.3  |             58.75 |         5.52 |
|              19 | MT.AS    | MT.AS    | EUROPE   |               47.69 |                     0.06 |    -0.02 |     -0.02 |                  72.8  |                        74.38 |         61.73 |         75.42 |          77.49 |        73.98 |           67.67 |             81.45 |         5.09 |
|              20 | DK       | DK       | US       |                3.87 |                     0.11 |    -0.09 |      0.07 |                  59.78 |                        74.38 |         70.79 |         82.36 |          78.41 |        69.95 |           55.62 |             87.39 |         7.37 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol    | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | INDU-C.ST | AB Industrivärden (publ)     | EUROPE   |               20.7  |             65.2  |         68.64 |         63.97 |          66.43 |        62.61 |           77.46 |             77.7  |             30.99 |         2.53 |             64.78 | short              |               10.05 |                  3.32 |                 2.53 |
|    nan | COST      | Costco Wholesale Corporation | US       |              350.47 |             44.67 |         45.69 |         36.1  |          43.65 |        50.52 |           77.39 |             44.66 |             26    |         8.5  |             89.81 | long               |                3.82 |                  1.92 |                 1.73 |
|    nan | TLRY      | Tilray Brands, Inc.          | OTHER    |                0.5  |             27.69 |         29.1  |         21.01 |          26.28 |        33.83 |           44.87 |             31.86 |             32.02 |         8.9  |             78.44 | long               |                2.5  |                  0.04 |                 0.14 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     17 | AMS.SW   | AMS.SW                         | EUROPE   |                2.49 |             77.05 |         87.47 |         83.59 |          70.51 |        51.61 |           50.63 |             88.84 |              8.49 |         8.67 |             73.14 | short              |                5.98 |                  5.48 |               nan    |
|    320 | ITRG     | ITRG                           | US       |                0.49 |             57.9  |         55.56 |         58.06 |          57.74 |        66.97 |           60.67 |             63.88 |             86.83 |         8.26 |             68.32 | long               |                2.11 |                  4.87 |                 5.11 |
|     10 | AMC      | AMC                            | US       |                2.24 |             80.68 |         81.09 |         86.47 |          80.28 |        79.5  |           85.31 |             78.97 |            nan    |         9.53 |             65.07 | swing              |                4.49 |                  4.36 |                 4.05 |
|    262 | IHS      | IHS Holding Limited            | OTHER    |                2.49 |             60.44 |         63.84 |         56.97 |          58.44 |        62.44 |           58.76 |             77.88 |             63.84 |         2.08 |             72.86 | short              |                0.23 |                  4.27 |                 4.29 |
|    560 | CYH      | Community Health Systems, Inc. | US       |                0.37 |             46.48 |         55.1  |         38.46 |          41.03 |        51.94 |           48.21 |             27.87 |             79.27 |         7.98 |             82.05 | short              |                6.89 |                  4.2  |                 3.8  |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    683 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.42 |             34.01 |         24.89 |         28.49 |          39.52 |        70.92 |          nan    |            nan    |            100    |         5.14 |             60    | long               |               -3.6  |                 -3.74 |                -3.71 |
|    453 | TEVA     | TEVA    | US       |               39.74 |             52.31 |         65.91 |         57.06 |          47.57 |        39.93 |           14.42 |             29.91 |             50.97 |         4.82 |             72.34 | short              |               -2.7  |                 -3.48 |                -3.6  |
|    431 | CMPS     | CMPS    | US       |                1.66 |             53.43 |         47.04 |         59.81 |          59.89 |        43.97 |           44.74 |             51.74 |              7.33 |         7.91 |             69.27 | medium             |              -12.23 |                 -2.88 |                -3.14 |
|    663 | PAH3.DE  | PAH3.DE | EUROPE   |                8.01 |             37.49 |         36.52 |         32.4  |          38.45 |        62.72 |          nan    |             27.38 |             97.06 |         5.11 |             70.3  | long               |               -7.86 |                 -2.8  |                -2.41 |
|    302 | UMC      | UMC     | US       |               54.07 |             58.74 |         75.35 |         56.22 |          61.25 |        52.45 |           62    |             38.9  |             22.17 |         7.85 |             72.68 | short              |               -0.31 |                 -2.66 |                -2.97 |

## Duplicate-security checks

- None detected.

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
- Excluded by hard/data filters: **288**
- Event watch (otherwise eligible): **3**
- Final eligible: **709**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- liquidity: 237
- price: 182
- market_cap: 157
- price_history: 17
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| CMBT.BR | 2 |  | 2 |  | 2 | main,pullback |
| VLO | 5 |  | 5 |  | 2 | main,pullback |
| DELL | 6 |  | 6 |  | 2 | main,pullback |
| FRO | 7 |  | 4 |  | 2 | main,pullback |
| PSX | 9 |  | 3 |  | 2 | main,pullback |
| PBR-A | 45 | 4 | 31 | 5 | 1 | value,quality_value |
| PARR | 58 | 3 | 29 | 3 | 1 | value,quality_value |
| NVDA | 62 | 2 |  | 2 | 1 | value,quality_value |
| EMBC | 171 | 6 |  | 6 | 1 | value,quality_value |
| BION.SW | 195 | 1 | 128 | 1 | 1 | value,quality_value |
| NWL.MI | 257 | 9 | 53 | 9 | 1 | value,quality_value |
| AVGO | 326 | 10 |  | 8 | 1 | value,quality_value |
| INVA | 533 | 8 | 157 | 4 | 1 | value,quality_value |
| STNE | 609 | 5 | 266 | 7 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **3** (HPE, MU, AMC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | INVA | value+pullback | 74.99 | 64.94 | 82.18 | 90.78 | 48.49 | 82.49 | 48.39 |
| 2 | NWL.MI | value+pullback | 70.57 | 73.61 | 76.40 | 75.50 | 43.35 | 68.63 | 60.65 |
| 3 | BION.SW | value+pullback | 70.06 | 73.97 | 48.25 | 84.64 | 57.83 | 86.63 | 63.23 |
| 4 | PARR | value+pullback | 69.29 | 68.48 | 63.98 | 80.43 | 69.71 | 68.57 | 72.55 |
| 5 | 0Q2N.IL | value+pullback | 67.54 | 66.96 | 75.43 | 62.76 |  | 70.92 | 64.65 |
| 6 | STNE | value+pullback | 66.18 | 72.17 | 59.25 | 85.87 | 32.30 | 68.01 | 43.55 |
| 7 | GSL | value+pullback | 66.12 | 66.04 | 67.13 | 76.93 | 30.18 | 74.85 | 60.13 |
| 8 | IRS | value+pullback | 65.00 | 67.32 | 75.21 | 63.97 | 40.31 | 61.87 | 51.16 |
| 9 | VOLV-B.ST | value+pullback | 64.98 | 61.87 | 71.38 | 64.50 | 63.21 | 62.91 | 55.08 |
| 10 | SDF.DE | value+pullback | 64.34 | 59.63 | 74.77 | 73.47 | 40.47 | 63.44 | 60.26 |
| 11 | BCE | value+pullback | 63.21 | 59.29 | 66.86 | 80.43 | 53.34 | 56.53 | 43.73 |
| 12 | HMC | value+pullback | 62.52 | 55.22 | 53.10 | 75.65 | 80.87 | 66.23 | 67.43 |
| 13 | RCI | value+pullback | 62.27 | 64.38 | 54.56 | 89.13 | 42.31 | 58.60 | 44.35 |
| 14 | MAGN | value+pullback | 62.00 | 66.85 | 62.97 | 68.70 | 33.58 | 62.68 | 47.63 |
| 15 | PBR-A | value+pullback | 61.84 | 74.98 | 42.76 | 61.58 | 79.45 | 57.39 | 73.80 |
| 16 | WB | value+pullback | 61.24 | 71.47 | 59.98 | 73.42 | 17.45 | 60.25 | 38.46 |
| 17 | SAP.DE | value+pullback | 61.14 | 59.67 | 52.67 | 74.09 | 55.22 | 67.17 | 64.66 |
| 18 | GAB | value+pullback | 61.08 | 57.64 | 61.24 | 54.99 | 77.47 | 62.39 | 51.20 |
| 19 | AVK | value+pullback | 60.66 | 57.41 | 69.54 | 62.10 | 49.68 | 58.83 | 49.96 |
| 20 | CNC | value+pullback | 59.94 | 71.24 | 56.87 | 50.47 | 63.90 | 51.95 | 59.93 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 9/10 | 8/10 | 0/10 | 72.7 | 7 / 3 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 72.8 | 14 / 11 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 72.7 | 26 / 24 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
