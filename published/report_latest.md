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

- **EUROPE:** 80.5/100
- **OTHER:** 73.4/100
- **US:** 82.3/100

## Main multi-horizon ranking

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC     | US       |               99.23 |             86.22 |         76.65 |         87.97 |          88.15 |        84.47 |           85.53 |             88.66 |             72.47 |         4.22 |             69.89 | medium             |               -0.93 |                nan    |               nan    |
|      2 | CMBT.BR  | CMBT.BR | EUROPE   |                4.96 |             84.21 |         83.07 |         83.67 |          85.98 |        84.76 |           95.43 |             77.2  |             68.2  |         3.77 |             73.14 | medium             |                0.03 |                  1.61 |                 1.46 |
|      3 | MU       | MU      | US       |             1079.84 |             83.8  |         82.03 |         75.72 |          86.29 |        85.57 |           95.58 |             80.28 |             71.67 |         8.16 |             73.14 | medium             |                3.03 |                  2.98 |                 2.29 |
|      4 | VLO      | VLO     | US       |               94.72 |             83.6  |         76.62 |         85.44 |          85.69 |        81.75 |           86.82 |             82    |             63.59 |         3.6  |             69.68 | medium             |               -2.15 |                  1.26 |                 1.12 |
|      5 | DELL     | DELL    | US       |              304.42 |             82.51 |         87.71 |         84.3  |          80.73 |        68.13 |           74.06 |             85.76 |             30.45 |         7.74 |             72.23 | short              |               -1.1  |                  0.06 |                -0.11 |
|      6 | FRO      | FRO     | US       |                9.31 |             82.08 |         82.64 |         79.85 |          83.67 |        81.52 |           91.8  |             79.9  |             60.46 |         5.47 |             73.14 | medium             |               -2.83 |                  0.54 |                 0.49 |
|      7 | PSX      | PSX     | US       |               89.37 |             81.14 |         76.54 |         85.16 |          83.42 |        78.85 |           80.87 |             84.32 |             61.63 |         3.73 |             69.89 | swing              |               -2.73 |                  1.21 |                 1.25 |
|      8 | AMC      | AMC     | US       |                2.31 |             81    |         81.97 |         86.52 |          80.03 |        79.43 |           85.26 |             78.31 |            nan    |         9.53 |             61.82 | swing              |                4.81 |                  4.42 |                 4.09 |
|      9 | HPE      | HPE     | US       |               70.67 |             80.77 |         88.25 |         82.03 |          79.51 |        71.84 |           74.57 |             72.82 |             51.64 |         6.89 |             70.27 | short              |               -0.59 |                  0.19 |               nan    |
|     10 | HSHP     | HSHP    | US       |                0.75 |             79.94 |         82.77 |         80.52 |          79.37 |        70.12 |           86.82 |            nan    |             28.95 |         4.81 |             59.59 | short              |               -2.86 |                nan    |               nan    |
|     11 | OKTA     | OKTA    | US       |               29.98 |             79.93 |         90.71 |         85.01 |          74.85 |        63.07 |           79.86 |             68.65 |             14.17 |         7.72 |             69.25 | short              |                1.41 |                  1.24 |                 1.15 |
|     12 | DHT      | DHT     | US       |                3.01 |             78.77 |         76.9  |         75.53 |          80.64 |        81.72 |           89.36 |             81.62 |             66.95 |         4.66 |             69.89 | long               |               -3.29 |                  0.48 |                 0.24 |
|     13 | HALO     | HALO    | US       |               11.4  |             78.32 |         80.83 |         81.59 |          75.81 |        72.67 |           87.82 |             51.91 |             49.57 |         5.86 |             72.11 | swing              |                2.21 |                nan    |               nan    |
|     14 | KIN.BR   | KIN.BR  | EUROPE   |                1.36 |             78.14 |         80.6  |         82.05 |          75.67 |        65.94 |           88.58 |             64.59 |             17.63 |         3.68 |             73.14 | swing              |                0.39 |                 -0.11 |                -0.09 |
|     15 | FSM      | FSM     | US       |                3.15 |             77.78 |         71.66 |         77.58 |          77.97 |        81.19 |           80.63 |             71.34 |             84.32 |         7.14 |             73.14 | long               |                2.41 |                  3.56 |                 3.02 |
|     16 | NAT      | NAT     | US       |                1.41 |             77.75 |         80.12 |         77.25 |          78.25 |        73.1  |           87.69 |             69.43 |             39.45 |         4.77 |             73.14 | short              |               -2.81 |                 -0.07 |                 0.02 |
|     17 | P        | P       | US       |               32.23 |             76.87 |         87.84 |         82.6  |          71.15 |        58.76 |           72.4  |             85.07 |             11.86 |         8.04 |             70.61 | short              |               -0.49 |                  2.45 |                 1.77 |
|     18 | ABN.AS   | ABN.AS  | EUROPE   |               35.33 |             76.68 |         77.7  |         77.53 |          75.83 |        70.82 |           77.14 |             68.3  |             52.53 |         2.81 |             73.14 | short              |                0.62 |                  1.53 |                 1.47 |
|     19 | REP.MC   | REP.MC  | EUROPE   |               31.81 |             76.47 |         77.81 |         80.67 |          75.14 |        72.57 |           57.28 |             76.63 |             79.97 |         3.64 |             73.14 | swing              |                1.82 |                  1.45 |                 1.17 |
|     20 | BIRG.IR  | BIRG.IR | EUROPE   |               18.82 |             76.42 |         76.63 |         73.23 |          76.21 |        78.41 |           96.05 |             66.81 |             59.68 |         2.19 |             73.14 | long               |                0.69 |                  1.94 |                 1.65 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.52 |                 76.22 |              74.72 |                86.81 |                   13.19 |           84.64 |             58.32 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               25.94 |                  74.77 |                    72.28 |                 72.44 |              71.66 |                59.23 |                   40.77 |           76.19 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.8  |                    71.32 |                 72.67 |              70.06 |                77.61 |                   22.39 |           75.9  |             79.94 |     nan     |         nan |       nan |      nan    |         9.07 |         10.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.72 |                 72.69 |              65.81 |                77.44 |                   22.56 |           86.5  |             80.39 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  60.61 |                    70.66 |                 74.08 |              66.47 |                81.5  |                   18.5  |           89.36 |             81.62 |     nan     |         nan |       nan |      nan    |         9.97 |          7.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.07 |                  57.31 |                    70.33 |                 74.46 |              65.29 |                87.9  |                   12.1  |           92.71 |             82.04 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.96 |                  58.26 |                    70.33 |                 74.39 |              64.95 |                84.89 |                   15.11 |           95.43 |             77.2  |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.24 |                 70.32 |              73.11 |                57.74 |                   42.26 |           61.58 |             80.74 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.86 |                 71.85 |              68.76 |                68.87 |                   31.13 |           80.43 |             70.61 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.74 |                 69.8  |              70.69 |                62.59 |                   37.41 |           70.56 |             64.38 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.63 |                 69.27 |              67.66 |                68.43 |                   31.57 |           85.87 |             33.76 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | BBWI     | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.23 |                 66.79 |              68.05 |                59.38 |                   40.62 |           75.98 |             34.73 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.51 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|            9 | MOMO     | Hello Group Inc.                     | OTHER    |                0.63 |                  78.54 |                    69.14 |                 66.42 |              72.26 |                73.01 |                   26.99 |           65.09 |             25.67 |       0.832 |         nan |       nan |       -5.95 |         4.85 |          4.93 |        0.89 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.45 |                    68.96 |                 71.48 |              65.91 |                72.53 |                   27.47 |           82.63 |             78.93 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  57.11 |                    68.69 |                 72.72 |              63.61 |                80.57 |                   19.43 |           91.8  |             79.9  |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               96.82 |                  56.67 |                    68.63 |                 72.56 |              64.14 |                82.31 |                   17.69 |           87.75 |             85.16 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO     | Broadcom Inc.                        | US       |             1517.87 |                  60.81 |                    68.28 |                 68.87 |              62.36 |                78.55 |                   21.45 |           92.29 |             44.37 |       0.018 |         nan |       nan |       33.98 |        18.81 |         46.56 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|           11 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.18 |                  68.64 |                    68.21 |                 67.61 |              69.17 |                71.3  |                   28.7  |           63.54 |            nan    |       0.233 |         nan |       nan |        1.54 |       nan    |          2.96 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.77 |                  73.72 |                    68.14 |                 68.24 |              69.46 |                68.88 |                   31.12 |           75.04 |             39.85 |       0.602 |         nan |       nan |        4.72 |      -134.45 |          2.32 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  62.17 |                    67.99 |                 69.87 |              65.19 |                76.63 |                   23.37 |           81.78 |             66.34 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  73.97 |                    74.52 |                 76.22 |              74.72 |                86.81 |                   13.19 |           84.64 |             58.32 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.07 |                  57.31 |                    70.33 |                 74.46 |              65.29 |                87.9  |                   12.1  |           92.71 |             82.04 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.96 |                  58.26 |                    70.33 |                 74.39 |              64.95 |                84.89 |                   15.11 |           95.43 |             77.2  |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  60.61 |                    70.66 |                 74.08 |              66.47 |                81.5  |                   18.5  |           89.36 |             81.62 |     nan     |         nan |       nan |      nan    |         9.97 |          7.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  57.11 |                    68.69 |                 72.72 |              63.61 |                80.57 |                   19.43 |           91.8  |             79.9  |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation                   | US       |             4820.51 |                  60.87 |                    70.72 |                 72.69 |              65.81 |                77.44 |                   22.56 |           86.5  |             80.39 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.93 |        0.48 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  66.8  |                    71.32 |                 72.67 |              70.06 |                77.61 |                   22.39 |           75.9  |             79.94 |     nan     |         nan |       nan |      nan    |         9.07 |         10.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               96.82 |                  56.67 |                    68.63 |                 72.56 |              64.14 |                82.31 |                   17.69 |           87.75 |             85.16 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | 0QXR.IL  | Stellantis N.V.                      | OTHER    |               25.94 |                  74.77 |                    72.28 |                 72.44 |              71.66 |                59.23 |                   40.77 |           76.19 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        1.65 |                 nan |              nan |                   9 |                  0.47 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.86 |                 71.85 |              68.76 |                68.87 |                   31.13 |           80.43 |             70.61 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.81 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.82 |                  55.39 |                    67.69 |                 71.71 |              61.86 |                85    |                   15    |           96.05 |             66.81 |     nan     |         nan |       nan |      nan    |        10.88 |         14.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.45 |                    68.96 |                 71.48 |              65.91 |                72.53 |                   27.47 |           82.63 |             78.93 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  75.89 |                    70.24 |                 70.32 |              73.11 |                57.74 |                   42.26 |           61.58 |             80.74 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.74 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MPC      | MPC                                  | US       |               99.23 |                  50.81 |                    65.31 |                 69.95 |              60.34 |                82.72 |                   17.28 |           85.53 |             88.66 |     nan     |         nan |       nan |      nan    |         8.27 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  62.17 |                    67.99 |                 69.87 |              65.19 |                76.63 |                   23.37 |           81.78 |             66.34 |     nan     |         nan |       nan |      nan    |         9.48 |         13.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.74 |                 69.8  |              70.69 |                62.59 |                   37.41 |           70.56 |             64.38 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | MU       | MU                                   | US       |             1079.84 |                  48.74 |                    63.96 |                 69.46 |              57.02 |                77.25 |                   22.75 |           95.58 |             80.28 |     nan     |         nan |       nan |      nan    |         6.9  |         24.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.63 |                 69.27 |              67.66 |                68.43 |                   31.57 |           85.87 |             33.76 |       0.608 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           13 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               41.7  |                  64.5  |                    67.4  |                 69.07 |              64.95 |                66.78 |                   33.22 |           78.68 |            nan    |       0.415 |         nan |       nan |        7.45 |       nan    |          2.71 |        0.58 |                 nan |              nan |                   9 |                  0.47 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.68 |                  62.64 |                    67.47 |                 69.02 |              64.15 |                77.04 |                   22.96 |           86.01 |             51.8  |     nan     |         nan |       nan |      nan    |         8.73 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC       | MPC                        | US       |               99.23 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        84.62 |         76.65 |         87.97 |          88.15 |        84.47 |           85.53 |             88.66 |         4.22 |
|               2 | CMBT.BR   | CMBT.BR                    | EUROPE   |                4.96 |                     0.05 |     0.01 |      0.1  |                  68.66 |                        82.8  |         83.07 |         83.67 |          85.98 |        84.76 |           95.43 |             77.2  |         3.77 |
|               3 | PSX       | PSX                        | US       |               89.37 |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        82.58 |         76.54 |         85.16 |          83.42 |        78.85 |           80.87 |             84.32 |         3.73 |
|               4 | VLO       | VLO                        | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        82.2  |         76.62 |         85.44 |          85.69 |        81.75 |           86.82 |             82    |         3.6  |
|               5 | FRO       | FRO                        | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        81.08 |         82.64 |         79.85 |          83.67 |        81.52 |           91.8  |             79.9  |         5.47 |
|               6 | DELL      | DELL                       | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        81.01 |         87.71 |         84.3  |          80.73 |        68.13 |           74.06 |             85.76 |         7.74 |
|               7 | SHELL.AS  | SHELL.AS                   | EUROPE   |              234.07 |                     0.04 |    -0.04 |      0.03 |                  73.9  |                        79.11 |         73.45 |         74.35 |          75.66 |        82.31 |           92.71 |             82.04 |         2.35 |
|               8 | DHT       | DHT                        | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        78.3  |         76.9  |         75.53 |          80.64 |        81.72 |           89.36 |             81.62 |         4.66 |
|               9 | NAT       | NAT                        | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        78.05 |         80.12 |         77.25 |          78.25 |        73.1  |           87.69 |             69.43 |         4.77 |
|              10 | AVAH      | AVAH                       | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        76.53 |         56.38 |         76.95 |          77.92 |        73.48 |           92.91 |             54.91 |         7.63 |
|              11 | BP        | BP                         | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        75.81 |         61.58 |         66.66 |          72.01 |        78.77 |           87.75 |             85.16 |         4.42 |
|              12 | ARGX.BR   | ARGX.BR                    | EUROPE   |               53.51 |                     0.06 |    -0    |     -0.03 |                  67.36 |                        75.15 |         61.63 |         68.99 |          71.14 |        63.08 |           93.1  |             79.52 |         6.01 |
|              13 | SHEL      | SHEL                       | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        75.11 |         66.9  |         70.97 |          71.48 |        77.59 |           75.9  |             79.94 |         2.96 |
|              14 | BIRG.IR   | BIRG.IR                    | EUROPE   |               18.82 |                     0.02 |     0    |      0.04 |                  48    |                        74.75 |         76.63 |         73.23 |          76.21 |        78.41 |           96.05 |             66.81 |         2.19 |
|              15 | DINO      | DINO                       | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        74.56 |         70.45 |         84.27 |          79.49 |        71.63 |           51.06 |             85.85 |         4.56 |
|              16 | DAR       | DAR                        | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        74.52 |         52.44 |         67.19 |          77.87 |        83.57 |           90.11 |             84.81 |         4.61 |
|              17 | EQNR      | EQNR                       | US       |               86.45 |                     0.1  |    -0.1  |     -0.03 |                  72.7  |                        74.25 |         53.51 |         70.79 |          74.52 |        76.09 |           77.02 |             83.65 |         5.54 |
|              18 | PARR      | Par Pacific Holdings, Inc. | US       |                3.46 |                     0.09 |    -0.06 |      0.06 |                  65.86 |                        73.6  |         63.79 |         74.09 |          76.2  |        75.22 |           80.43 |             70.61 |         6.99 |
|              19 | APA       | APA                        | US       |               12.93 |                     0.11 |    -0.11 |     -0.01 |                  68.9  |                        73.47 |         57.93 |         71.41 |          75.58 |        79.21 |           77.3  |             79.8  |         5.88 |
|              20 | FORTUM.HE | FORTUM.HE                  | EUROPE   |               21.14 |                     0.05 |    -0.01 |      0.16 |                  68.4  |                        73.13 |         80.39 |         68.35 |          59.36 |        52.7  |           63.58 |             66.42 |         4.53 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol    | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | INDU-C.ST | AB Industrivärden (publ)     | EUROPE   |               20.93 |             65.68 |         70.33 |         64.46 |          66.9  |        62.06 |           79.67 |             78.35 |              24.1 |         2.46 |             64.78 | short              |               10.53 |                  3.42 |                 2.6  |
|    nan | COST      | Costco Wholesale Corporation | US       |              347.91 |             41.4  |         38.84 |         34.61 |          43.97 |        50.6  |           77.39 |             45.82 |              26   |         8.5  |             89.81 | long               |                0.56 |                  1.27 |                 1.24 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    201 | ITRG     | ITRG   | OTHER    |                0.51 |             63.08 |         66.6  |         59.56 |          59.53 |        66.96 |           78.92 |             63.57 |             61.28 |         8.15 |             65.07 | long               |                7.28 |                  5.91 |                 5.89 |
|     42 | AMS.SW   | AMS.SW | EUROPE   |                2.26 |             73.48 |         83.14 |         76.62 |          70.35 |        52.91 |           52.47 |             88.12 |             11.34 |         8.59 |             73.14 | short              |                2.41 |                  4.77 |               nan    |
|    175 | VZLA     | VZLA   | OTHER    |                1.33 |             64.11 |         76.67 |         67.92 |          60.29 |        57.26 |           72.68 |            nan    |             33.33 |         8.32 |             61.82 | short              |                6.59 |                  4.7  |               nan    |
|      8 | AMC      | AMC    | US       |                2.31 |             81    |         81.97 |         86.52 |          80.03 |        79.43 |           85.26 |             78.31 |            nan    |         9.53 |             61.82 | swing              |                4.81 |                  4.42 |                 4.09 |
|    191 | NEWP     | NEWP   | OTHER    |                1.12 |             63.45 |         69.64 |         67.15 |          59.74 |        46.3  |           47.35 |             38.01 |             14.81 |         7.9  |             65    | short              |                4.21 |                  4.4  |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    703 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             25.23 |         22.53 |         20.48 |          27.93 |        36.56 |           43.7  |             26.4  |             45.6  |         6.2  |             84.71 | long               |                0.45 |                 -3.35 |               nan    |
|    626 | FRSH     | FRSH                  | US       |                2.83 |             42.03 |         37.3  |         57.13 |          46.24 |        37.83 |           22.06 |             32.01 |             44.44 |         7.54 |             68.41 | swing              |               -4.37 |                 -3.31 |                -2.52 |
|    428 | TEVA     | TEVA                  | US       |               40.2  |             53.52 |         66.55 |         58.99 |          48.05 |        39.27 |           13.33 |             30.89 |             48.43 |         4.67 |             69.09 | short              |               -1.49 |                 -3.24 |                -3.42 |
|    619 | BAS.DE   | BAS.DE                | EUROPE   |               45.8  |             42.64 |         55.5  |         46.53 |          38.76 |        33.58 |           21.47 |             31.54 |             29.14 |         2.04 |             67.86 | short              |                1.4  |                 -2.58 |               nan    |
|    647 | AHR      | AHR                   | US       |                9.83 |             40.15 |         36.6  |         44.04 |          43.17 |        37.12 |           33.93 |             45.81 |             16.56 |         2.75 |             70.86 | swing              |               -0.46 |                 -2.34 |               nan    |

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
- Excluded by hard/data filters: **292**
- Event watch (otherwise eligible): **2**
- Final eligible: **706**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 235
- price: 183
- market_cap: 155
- price_history: 18
- data_confidence: 12
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| CMBT.BR | 2 |  | 2 |  | 2 | main,pullback |
| VLO | 4 |  | 4 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 5 |  | 2 | main,pullback |
| PSX | 7 |  | 3 |  | 2 | main,pullback |
| PARR | 31 | 5 | 18 | 4 | 1 | value,quality_value |
| PBR-A | 57 | 4 | 22 | 5 | 1 | value,quality_value |
| NVDA | 60 | 3 |  | 2 | 1 | value,quality_value |
| EMBC | 174 | 6 |  | 6 | 1 | value,quality_value |
| BION.SW | 180 | 1 | 98 | 1 | 1 | value,quality_value |
| AVGO | 291 | 10 |  | 9 | 1 | value,quality_value |
| 0QXR.IL | 421 | 2 |  | 3 | 1 | value,quality_value |
| STNE | 510 | 7 | 142 | 7 | 1 | value,quality_value |
| MU | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (CMBT.BR, MU, DELL, FRO, AMC, HPE, HSHP)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (CMBT.BR, FRO, DELL, NAT)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.34 | 73.97 | 53.02 | 84.64 | 58.32 | 86.81 | 63.82 |
| 2 | PARR | value+pullback | 69.91 | 68.48 | 65.86 | 80.43 | 70.61 | 68.87 | 74.66 |
| 3 | PBR-A | value+pullback | 68.73 | 75.89 | 68.43 | 61.58 | 80.74 | 57.74 | 72.47 |
| 4 | STNE | value+pullback | 67.19 | 72.17 | 62.40 | 85.87 | 33.76 | 68.43 | 49.52 |
| 5 | GSL | value+pullback | 66.94 | 63.62 | 59.10 | 95.11 | 30.99 | 78.59 | 63.55 |
| 6 | 0P6O.IL | value+pullback | 66.59 | 64.50 | 68.35 | 78.68 |  | 66.78 | 50.54 |
| 7 | SDF.DE | value+pullback | 66.22 | 64.91 | 69.69 | 78.87 | 41.72 | 66.61 | 61.08 |
| 8 | 0Q2N.IL | value+pullback | 65.65 | 68.64 | 65.06 | 63.54 |  | 71.30 | 61.92 |
| 9 | PAH3.DE | value+pullback | 64.13 | 70.93 | 71.25 | 41.00 | 60.56 | 64.14 | 43.46 |
| 10 | INVA | value+pullback | 63.48 | 63.47 | 45.55 | 90.78 | 32.51 | 80.94 | 51.12 |
| 11 | WB | value+pullback | 63.47 | 69.71 | 64.82 | 78.95 | 18.08 | 63.50 | 41.38 |
| 12 | CNC | value+pullback | 63.36 | 71.92 | 69.23 | 50.47 | 64.58 | 52.25 | 60.09 |
| 13 | UNIT | value+pullback | 63.16 | 80.01 | 70.08 | 64.98 | 29.67 | 44.61 | 43.10 |
| 14 | VOW3.DE | value+pullback | 62.56 | 68.88 | 67.06 | 61.37 | 34.10 | 62.59 | 44.68 |
| 15 | 1VOW3.MI | value+pullback | 62.21 | 65.89 | 66.61 | 61.37 | 37.97 | 63.93 | 43.29 |
| 16 | VOLV-B.ST | value+pullback | 61.78 | 57.21 | 64.97 | 66.59 | 61.42 | 61.21 | 56.68 |
| 17 | IRS | value+pullback | 61.68 | 68.99 | 60.56 | 64.61 | 40.49 | 60.49 | 52.10 |
| 18 | VOW.DE | value+pullback | 59.75 | 59.62 | 67.61 | 61.37 | 32.82 | 62.39 | 42.98 |
| 19 | ORC | value+pullback | 59.02 | 60.76 | 55.47 | 75.90 | 35.60 | 59.90 | 41.46 |
| 20 | BP | pullback | 58.40 | 56.67 | 81.04 | 87.75 | 85.16 | 82.31 | 69.34 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 9/10 | 8/10 | 0/10 | 70.1 | 3 / 7 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 70.6 | 11 / 14 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.1 | 23 / 27 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
