# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-09

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

- **EUROPE:** 87.0/100
- **OTHER:** 84.5/100
- **US:** 83.1/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO      | FRO                        | US       |                8.93 |             80.07 |         86.57 |         81.09 |          79.05 |        77.09 |           90.64 |             70.72 |             54.06 |         5.5  |             69.68 | short              |               -2.09 |                  2.41 |               nan    |
|      2 | DELL     | DELL                       | US       |              296.67 |             79.63 |         88.46 |         82.55 |          76.71 |        63.88 |           71.41 |             79.22 |             27.13 |         7.58 |             68.77 | short              |               -1.99 |                  0.75 |                 0.14 |
|      3 | DK       | DK                         | US       |                3.98 |             78.58 |         87.11 |         83.95 |          73.21 |        57.88 |           54.8  |             85.73 |             26.38 |         7.25 |             69.68 | short              |                0.09 |                  0.71 |               nan    |
|      4 | UGP      | UGP                        | US       |                6.83 |             78.34 |         83.29 |         82.94 |          73.74 |        65.8  |           62.31 |             76.68 |             52.19 |         4.44 |             68.66 | short              |               -1.17 |                  3.26 |               nan    |
|      5 | PBF      | PBF                        | US       |                7.83 |             78.06 |         81.76 |         82.25 |          74.36 |        67.12 |           49.81 |             70.44 |             75.02 |         7.53 |             69.23 | swing              |                2.73 |                  1.41 |                 1.29 |
|      6 | CRGY     | CRGY                       | US       |                4.8  |             77.81 |         84.25 |         78.17 |          75.98 |        77.45 |           68.78 |             88.8  |             83.86 |         6.13 |             69.23 | short              |               -1.15 |                  0.54 |                 0.43 |
|      7 | PARR     | Par Pacific Holdings, Inc. | US       |                3.54 |             77.56 |         80.59 |         79.23 |          75.89 |        70.82 |           64.86 |             66.68 |             68.29 |         7.08 |             85.07 | short              |               -0.56 |                nan    |               nan    |
|      8 | DINO     | DINO                       | US       |               16.56 |             77.38 |         82.77 |         82.34 |          72.42 |        61.77 |           48.49 |             74.36 |             57.16 |         4.44 |             69.68 | short              |               -1.3  |                nan    |               nan    |
|      9 | KIN.BR   | KIN.BR                     | EUROPE   |                1.33 |             76.82 |         83.4  |         80.42 |          73.22 |        64.87 |           89.95 |             67.76 |             22.49 |         3.82 |             69.68 | short              |               -1.68 |                  0.16 |                -0.05 |
|     10 | DSX      | DSX                        | US       |                0.32 |             75.27 |         85.76 |         69.91 |          69.99 |        80.55 |           88.64 |             41.65 |             90.99 |         6.05 |             67.86 | short              |               -4.94 |                  0.01 |                -0.59 |
|     11 | WT       | WT                         | US       |                3.18 |             74.77 |         77.1  |         78.54 |          72.44 |        61.64 |           70.55 |             76.53 |             24.37 |         5.58 |             69.68 | swing              |               -2.26 |                  0.72 |               nan    |
|     12 | MU       | MU                         | US       |              971.55 |             74.12 |         71.26 |         62.54 |          76.99 |        78.82 |           95.33 |             50.41 |             67.66 |         8.24 |             69.68 | long               |               -3.9  |                  1.36 |               nan    |
|     13 | PR       | PR                         | US       |               17.04 |             74.09 |         79.55 |         74.55 |          73.64 |        72.55 |           77.12 |             75.1  |             59.08 |         4.17 |             68.32 | short              |               -1.97 |                  0.22 |                -0.02 |
|     14 | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.99 |             73.81 |         75.6  |         69.84 |          72.8  |        74.83 |           96.44 |             61.59 |             56.27 |         2.21 |             69.68 | short              |                0.93 |                  0.82 |                 0.37 |
|     15 | HPE      | HPE                        | US       |               63.97 |             73.73 |         74.35 |         73.11 |          78.24 |        69.88 |           73.87 |             83.35 |             48.18 |         6.45 |             68.89 | medium             |                3.42 |                nan    |               nan    |
|     16 | GTLB     | GTLB                       | US       |                6.76 |             73.57 |         83.35 |         81.8  |          65.34 |        49.55 |           58.83 |             91.89 |              8.01 |         8.56 |             69.68 | short              |               -1.91 |                  0.19 |                -0.28 |
|     17 | ABN.AS   | ABN.AS                     | EUROPE   |               35.29 |             73.49 |         75.58 |         74.5  |          72.48 |        68    |           80.16 |             60.05 |             49.8  |         2.84 |             69.68 | short              |               -2.35 |                  0.1  |                -0.21 |
|     18 | HQL      | HQL                        | US       |                0.54 |             73.12 |         57.42 |         72.17 |          76.76 |        74.06 |          nan    |            nan    |             71.15 |         2.04 |             55.57 | medium             |               15.4  |                nan    |               nan    |
|     19 | CIRSA.MC | CIRSA.MC                   | EUROPE   |                3.11 |             73.06 |         81.89 |         78.13 |          67.73 |        68    |           82.06 |             68.16 |             56.45 |         5.57 |             67.5  | short              |               -3.59 |                nan    |               nan    |
|     20 | MT.AS    | MT.AS                      | EUROPE   |               50.32 |             72.85 |         72.79 |         71.85 |          75.51 |        72.92 |           74.13 |             80.13 |             66    |         5.01 |             69.68 | medium             |               -4.38 |                  0.42 |                 0.2  |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                        | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:------------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | TTE.PA   | TTE.PA                                                      | EUROPE   |              172.03 |                  67.18 |                    69.8  |                 70.47 |              69.43 |                74.04 |                   25.96 |           70.11 |             77.35 |      nan    |         nan |       nan |      nan    |         9.1  |         11.3  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                        | US       |              234.55 |                  66.05 |                    68.93 |                 69.73 |              68.09 |                73.69 |                   26.31 |           72.18 |             72.72 |      nan    |         nan |       nan |      nan    |         9.61 |         10.54 |         nan |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A                                                       | US       |              111.05 |                  68.23 |                    67.27 |                 67.87 |              67.14 |                66.64 |                   33.36 |           72.58 |             60.2  |      nan    |         nan |       nan |      nan    |         7.67 |          4.76 |         nan |                 nan |              nan |                   6 |                  0.32 |
|          nan | NN.AS    | NN.AS                                                       | EUROPE   |               20.62 |                  63.78 |                    67.01 |                 67.77 |              65.89 |                74.77 |                   25.23 |           72.35 |             65.11 |      nan    |         nan |       nan |      nan    |         9.07 |         11.7  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                                     | EUROPE   |               18.99 |                  55.1  |                    66.79 |                 70.67 |              60.86 |                83.48 |                   16.52 |           96.44 |             61.59 |      nan    |         nan |       nan |      nan    |        11.01 |         14.92 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                         | US       |                8.93 |                  56.63 |                    66.7  |                 70.3  |              61.7  |                76.99 |                   23.01 |           90.64 |             70.72 |      nan    |         nan |       nan |      nan    |        10.4  |          6.99 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                                                         | US       |               14.73 |                  66.66 |                    66.36 |                 66.59 |              63.21 |                69.05 |                   30.95 |           88.24 |             27.85 |      nan    |         nan |       nan |      nan    |         7.31 |          5.49 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                                                         | US       |               45.79 |                  62.3  |                    66.16 |                 67.54 |              64.19 |                70.28 |                   29.72 |           75.74 |             66.9  |      nan    |         nan |       nan |      nan    |         8.92 |         10.52 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                                                      | EUROPE   |               11.8  |                  62.19 |                    65.82 |                 66.63 |              65.36 |                73.4  |                   26.6  |           66.31 |             73.72 |      nan    |         nan |       nan |      nan    |         8.42 |         12.23 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                                                    | EUROPE   |               14.9  |                  55.77 |                    65.54 |                 68.44 |              61.8  |                81.43 |                   18.57 |           82.58 |             69.91 |      nan    |         nan |       nan |      nan    |        11.38 |         14.38 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                         | US       |               15.14 |                  54.07 |                    65.47 |                 69.1  |              61.11 |                80.6  |                   19.4  |           84.69 |             76.69 |      nan    |         nan |       nan |      nan    |        10.89 |         23.57 |         nan |                 nan |              nan |                   5 |                  0.26 |
|            2 | PARR     | Par Pacific Holdings, Inc.                                  | US       |                3.54 |                  66.71 |                    65.47 |                 65.85 |              66.23 |                64.08 |                   35.92 |           64.86 |             66.68 |        0.02 |         nan |       nan |        3.98 |         6.95 |          4.82 |         nan |                 nan |              nan |                  10 |                  0.53 |
|          nan | A5G.IR   | A5G.IR                                                      | EUROPE   |               23.99 |                  54.41 |                    65.21 |                 68.85 |              59.22 |                81.04 |                   18.96 |           96.07 |             54.59 |      nan    |         nan |       nan |      nan    |        11.59 |         11.93 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                                                         | US       |              115.45 |                  69.53 |                    65.12 |                 64.11 |              64.54 |                59.22 |                   40.78 |           72.84 |             38.18 |      nan    |         nan |       nan |      nan    |         5.22 |          5.26 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                                                      | EUROPE   |                1.73 |                  53.24 |                    65.05 |                 69.04 |              58.65 |                81.8  |                   18.2  |           97.71 |             55.9  |      nan    |         nan |       nan |      nan    |        10.82 |         11.18 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI                                                      | EUROPE   |               22.85 |                  58.43 |                    64.87 |                 66.59 |              63.51 |                75.34 |                   24.66 |           68.73 |             78.78 |      nan    |         nan |       nan |      nan    |         9.16 |         14.69 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ETW      | Eaton Vance Tax-Managed Global Buy-Write Opportunities Fund | US       |                0.92 |                  57.6  |                    64.74 |                 66.53 |              63.93 |                76.57 |                   23.43 |           64.47 |             86.68 |      nan    |         nan |       nan |      nan    |       nan    |          4.78 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                                    | EUROPE   |              233.78 |                  62.22 |                    64.38 |                 65.54 |              59.78 |                69.56 |                   30.44 |           93.68 |             24.58 |      nan    |         nan |       nan |      nan    |        10.67 |         10.5  |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | ALLY     | ALLY                                                        | US       |               11.06 |                  61.18 |                    64.3  |                 65.34 |              62.58 |                68.96 |                   31.04 |           73.14 |             61.17 |      nan    |         nan |       nan |      nan    |         6.57 |          9.95 |         nan |                 nan |              nan |                   5 |                  0.26 |
|          nan | HBAN     | HBAN                                                        | US       |               29.12 |                  64.49 |                    64.2  |                 64.03 |              64.14 |                65.24 |                   34.76 |           65.1  |             59.65 |      nan    |         nan |       nan |      nan    |         8.93 |         12.89 |         nan |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                        | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:------------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | BIRG.IR  | BIRG.IR                                                     | EUROPE   |               18.99 |                  55.1  |                    66.79 |                 70.67 |              60.86 |                83.48 |                   16.52 |           96.44 |             61.59 |      nan    |         nan |       nan |      nan    |        11.01 |         14.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                                                      | EUROPE   |              172.03 |                  67.18 |                    69.8  |                 70.47 |              69.43 |                74.04 |                   25.96 |           70.11 |             77.35 |      nan    |         nan |       nan |      nan    |         9.1  |         11.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                         | US       |                8.93 |                  56.63 |                    66.7  |                 70.3  |              61.7  |                76.99 |                   23.01 |           90.64 |             70.72 |      nan    |         nan |       nan |      nan    |        10.4  |          6.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                        | US       |              234.55 |                  66.05 |                    68.93 |                 69.73 |              68.09 |                73.69 |                   26.31 |           72.18 |             72.72 |      nan    |         nan |       nan |      nan    |         9.61 |         10.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                         | US       |               15.14 |                  54.07 |                    65.47 |                 69.1  |              61.11 |                80.6  |                   19.4  |           84.69 |             76.69 |      nan    |         nan |       nan |      nan    |        10.89 |         23.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                                                      | EUROPE   |                1.73 |                  53.24 |                    65.05 |                 69.04 |              58.65 |                81.8  |                   18.2  |           97.71 |             55.9  |      nan    |         nan |       nan |      nan    |        10.82 |         11.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                                                      | EUROPE   |               23.99 |                  54.41 |                    65.21 |                 68.85 |              59.22 |                81.04 |                   18.96 |           96.07 |             54.59 |      nan    |         nan |       nan |      nan    |        11.59 |         11.93 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                                                    | EUROPE   |               14.9  |                  55.77 |                    65.54 |                 68.44 |              61.8  |                81.43 |                   18.57 |           82.58 |             69.91 |      nan    |         nan |       nan |      nan    |        11.38 |         14.38 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | PBR-A    | PBR-A                                                       | US       |              111.05 |                  68.23 |                    67.27 |                 67.87 |              67.14 |                66.64 |                   33.36 |           72.58 |             60.2  |      nan    |         nan |       nan |      nan    |         7.67 |          4.76 |      nan    |                 nan |              nan |                   6 |                  0.32 |
|          nan | NN.AS    | NN.AS                                                       | EUROPE   |               20.62 |                  63.78 |                    67.01 |                 67.77 |              65.89 |                74.77 |                   25.23 |           72.35 |             65.11 |      nan    |         nan |       nan |      nan    |         9.07 |         11.7  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN      | DVN                                                         | US       |               45.79 |                  62.3  |                    66.16 |                 67.54 |              64.19 |                70.28 |                   29.72 |           75.74 |             66.9  |      nan    |         nan |       nan |      nan    |         8.92 |         10.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                                                      | EUROPE   |               11.8  |                  62.19 |                    65.82 |                 66.63 |              65.36 |                73.4  |                   26.6  |           66.31 |             73.72 |      nan    |         nan |       nan |      nan    |         8.42 |         12.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI                                                      | EUROPE   |               22.85 |                  58.43 |                    64.87 |                 66.59 |              63.51 |                75.34 |                   24.66 |           68.73 |             78.78 |      nan    |         nan |       nan |      nan    |         9.16 |         14.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                                                         | US       |               14.73 |                  66.66 |                    66.36 |                 66.59 |              63.21 |                69.05 |                   30.95 |           88.24 |             27.85 |      nan    |         nan |       nan |      nan    |         7.31 |          5.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ETW      | Eaton Vance Tax-Managed Global Buy-Write Opportunities Fund | US       |                0.92 |                  57.6  |                    64.74 |                 66.53 |              63.93 |                76.57 |                   23.43 |           64.47 |             86.68 |      nan    |         nan |       nan |      nan    |       nan    |          4.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EQNR     | EQNR                                                        | US       |               88.51 |                  56.9  |                    63.86 |                 66.2  |              61.44 |                70.74 |                   29.26 |           73.54 |             77.34 |      nan    |         nan |       nan |      nan    |        11.18 |         11.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EVK.DE   | EVK.DE                                                      | EUROPE   |                8.56 |                  55.11 |                    63.64 |                 66.16 |              62.72 |                81.19 |                   18.81 |          nan    |             84.29 |      nan    |         nan |       nan |      nan    |        12.19 |         70.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVDA                                                        | US       |             4687.71 |                  49.56 |                    61.7  |                 65.88 |              55.9  |                76.04 |                   23.96 |           89.52 |             65.3  |      nan    |         nan |       nan |      nan    |        14.55 |         28.57 |        0.59 |                 nan |              nan |                   6 |                  0.32 |
|          nan | DTG.DE   | DTG.DE                                                      | EUROPE   |               34.21 |                  55.25 |                    63.61 |                 65.87 |              62.77 |                82.9  |                   17.1  |          nan    |             80.68 |      nan    |         nan |       nan |      nan    |         9.4  |         31.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | PARR     | Par Pacific Holdings, Inc.                                  | US       |                3.54 |                  66.71 |                    65.47 |                 65.85 |              66.23 |                64.08 |                   35.92 |           64.86 |             66.68 |        0.02 |         nan |       nan |        3.98 |         6.95 |          4.82 |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:--------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | GTLB     | GTLB    | US       |                6.76 |                     0.05 |     0.01 |      0.16 |                  66.26 |                        77.16 |         83.35 |         81.8  |          65.34 |        49.55 |           58.83 |             91.89 |         8.56 |
|               2 | ARGX.BR  | ARGX.BR | EUROPE   |               53.84 |                     0.05 |    -0.02 |      0.16 |                  75.12 |                        74.3  |         69.32 |         62.5  |          62.87 |        58    |           93.48 |             64.53 |         6.15 |
|               3 | CRM      | CRM     | US       |              176.33 |                     0.06 |    -0.03 |      0.26 |                  78.58 |                        74.15 |         78.53 |         73.06 |          58.69 |        53.78 |           60.39 |             73.5  |         7.8  |
|               4 | AMC      | AMC     | US       |                1.97 |                     0.05 |    -0.03 |      0.06 |                  77.72 |                        73.92 |         59.11 |         73.97 |          70.48 |        71.14 |           81.95 |             59.23 |         9.65 |
|               5 | RAND.AS  | RAND.AS | EUROPE   |                6.51 |                     0.08 |    -0.07 |     -0.05 |                  78.28 |                        72.94 |         41.82 |         69.65 |          69.35 |        64.21 |           81.29 |             67.41 |         6.8  |
|               6 | SNOW     | SNOW    | US       |              101.8  |                     0.06 |     0.01 |      0    |                  64.88 |                        72.41 |         69.04 |         78.71 |          67.51 |        46.12 |           42.85 |             98.33 |         7.94 |
|               7 | WT       | WT      | US       |                3.18 |                     0.02 |     0.01 |      0.1  |                  47.75 |                        72.02 |         77.1  |         78.54 |          72.44 |        61.64 |           70.55 |             76.53 |         5.58 |
|               8 | DOCU     | DOCU    | US       |               10.46 |                     0.05 |    -0.02 |      0.09 |                  72.16 |                        71.8  |         71.2  |         73.51 |          62.54 |        56.4  |           58.44 |             83.53 |         7.79 |
|               9 | PLTR     | PLTR    | US       |              351.96 |                     0.09 |    -0.09 |     -0.03 |                  76.64 |                        70.97 |         49.31 |         62.19 |          59.91 |        57.05 |           89.11 |             70.39 |         8.61 |
|              10 | CCC      | CCC     | US       |                3.59 |                     0.07 |    -0.05 |      0.02 |                  77.38 |                        70.95 |         56.68 |         66.43 |          61.7  |        64.59 |           85.73 |             59.91 |         8.13 |
|              11 | SBLK     | SBLK    | US       |                2.98 |                     0.04 |     0    |      0.13 |                  62.1  |                        69.84 |         76.38 |         69.27 |          69.7  |        71.01 |           73.61 |             50.75 |         4.32 |
|              12 | APA      | APA     | US       |               13.12 |                     0.03 |     0.01 |      0.06 |                  50.01 |                        69.62 |         73.92 |         71.35 |          72.74 |        70.23 |           71.58 |             72.3  |         5.71 |
|              13 | EQNR     | EQNR    | US       |               88.51 |                     0.02 |     0.01 |      0.07 |                  44.52 |                        69.36 |         72.74 |         72.63 |          73.28 |        68.84 |           73.54 |             77.34 |         5.41 |
|              14 | DFDS.CO  | DFDS.CO | EUROPE   |                1.11 |                     0.04 |    -0.04 |      0.2  |                  71.64 |                        69.04 |         72.31 |         63.38 |          64.72 |        63.02 |           64    |             62.28 |         6.1  |
|              15 | FSM      | FSM     | US       |                3.1  |                     0.05 |     0.01 |      0.13 |                  66.27 |                        68.81 |         74.56 |         63.9  |          62.4  |        71.38 |           77.55 |             40.52 |         7.34 |
|              16 | AG       | AG      | US       |                8.8  |                     0.05 |     0.01 |      0.1  |                  62.71 |                        68.63 |         69.25 |         53.7  |          58.33 |        63.51 |           88.52 |             45.94 |         8.44 |
|              17 | OKTA     | OKTA    | US       |               25.2  |                     0.03 |    -0.03 |      0.11 |                  65.44 |                        68.42 |         74.92 |         73.91 |          66.11 |        53.23 |           64.85 |             54.48 |         7.63 |
|              18 | CNQ      | CNQ     | US       |               90.24 |                     0.02 |     0.02 |      0.08 |                  42.82 |                        68.28 |         72.79 |         64.36 |          65.65 |        65.45 |           72.53 |             73.02 |         4.02 |
|              19 | PSKY     | PSKY    | US       |               10.42 |                     0.02 |    -0.01 |      0.17 |                  53.18 |                        68.05 |         70.84 |         53.9  |          52.94 |        57.85 |           61.24 |             82.71 |         6.9  |
|              20 | NTG.CO   | NTG.CO  | EUROPE   |                0.78 |                     0.06 |    -0.06 |     -0.01 |                  81.34 |                        68.03 |         51.41 |         64.55 |          66.72 |        62.21 |           84.97 |             43.74 |         5.26 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    144 | NNBR     | NNBR   | US       |                0.27 |             62.11 |         63.59 |         67.81 |          60.63 |        43.51 |           37.16 |             63.3  |             17.11 |         9.09 |             68.66 | swing              |                3.68 |                  3.74 |                 3.91 |
|     64 | ASX      | ASX    | US       |               89.1  |             67.53 |         68.97 |         66.1  |          69.64 |        57.46 |           63.16 |             75.83 |             21.53 |         7.3  |             69.23 | medium             |                6.14 |                  3.56 |                 2.96 |
|    152 | CMPS     | CMPS   | US       |                1.67 |             61.76 |         65.91 |         64.03 |          59.48 |        42.89 |           44.14 |             54.76 |              5.31 |         7.71 |             65.82 | short              |               11.52 |                  3.37 |                 3.56 |
|    149 | HAFN     | HAFN   | US       |                3.85 |             61.97 |         79.86 |         63.51 |          58.84 |        60.43 |           71.15 |             33.17 |             49.38 |         5.39 |             69.68 | short              |               -4.84 |                  3.35 |               nan    |
|     97 | LITE     | LITE   | US       |               75.49 |             65.63 |         81.83 |         66.71 |          64.55 |        48.3  |           43.13 |             90.8  |             10.37 |         8.5  |             69.68 | short              |                8.03 |                  3.3  |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    703 | 0QC9.L   | 0QC9.L  | EUROPE   |                3.32 |             29.64 |         26.07 |         22.49 |          33.21 |        58.62 |          nan    |            nan    |             80.12 |         4.09 |             60    | long               |              -10.83 |                 -6.32 |                -4.38 |
|    591 | NEWP     | NEWP    | OTHER    |                0.95 |             43.76 |         37.33 |         56.38 |          50.18 |        34.08 |           20.95 |             58.1  |              8.33 |         8.08 |             64.8  | swing              |              -13.65 |                 -2.91 |               nan    |
|    490 | CTSH     | CTSH    | US       |               23.21 |             48.5  |         49.09 |         47.91 |          45.87 |        54.73 |           57.42 |             42.21 |             65.09 |         7.98 |             68.32 | long               |              -12.92 |                 -2.87 |                -2.7  |
|    663 | DSY.PA   | DSY.PA  | EUROPE   |               26.88 |             38.24 |         27.79 |         37.97 |          38.52 |        38.64 |           49.12 |             29.98 |             29.52 |         6.47 |             69.68 | long               |               -0.61 |                 -2.66 |                -1.99 |
|    609 | NOVN.SW  | NOVN.SW | EUROPE   |              225.46 |             42.75 |         30.79 |         37.83 |          47.81 |        47.67 |           53.43 |             73.97 |             27.46 |         3.28 |             66.43 | medium             |               -9.63 |                 -2.56 |                -2.05 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `sector_score` vs `reaction_score`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
- `ret_126d_rank` vs `reaction_score`: r=0.86

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
- Event watch (otherwise eligible): **0**
- Final eligible: **712**
- Eligible change vs previous stored run: **+10**

Top exclusion categories:
- liquidity: 234
- price: 184
- market_cap: 154
- data_confidence: 15
- price_history: 15
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 7 | 2 |  | 3 | 2 | main,value,quality_value |
| PBR-A | 30 | 1 |  | 1 | 1 | value,quality_value |
| NVDA | 102 | 3 |  | 2 | 1 | value,quality_value |
| GAIN | 260 | 8 |  | 8 | 1 | value,quality_value |
| V | 276 | 7 | 58 | 5 | 1 | value,quality_value |
| ASML.AS | 391 | 10 |  | 7 | 1 | value,quality_value |
| ORC | 453 | 4 | 241 | 4 | 1 | value,quality_value |
| ORCL | 509 | 6 |  | 6 | 1 | value,quality_value |
| SIE.DE | 566 | 9 |  | 9 | 1 | value,quality_value |
| ARR | 569 | 5 | 359 | 10 | 1 | value,quality_value |
| FRO | 1 |  |  |  | 1 | main |
| DELL | 2 |  |  |  | 1 | main |
| DK | 3 |  |  |  | 1 | main |
| UGP | 4 |  |  |  | 1 | main |
| PBF | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **9** (FRO, DELL, DK, UGP, PBF, CRGY, DINO, KIN.BR, DSX)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (PLTR)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | ORC | value+pullback | 58.53 | 66.43 | 51.85 | 68.01 | 39.88 | 57.26 | 49.81 |
| 2 | ARGX.BR | pullback | 54.28 | 34.80 | 75.12 | 93.48 | 64.53 | 75.12 | 62.69 |
| 3 | PLTR | pullback | 53.55 | 36.11 | 76.64 | 89.11 | 70.39 | 69.93 | 58.48 |
| 4 | MA | pullback | 52.24 | 37.75 | 75.80 | 97.40 | 37.52 | 74.63 | 55.29 |
| 5 | RAND.AS | pullback | 52.24 | 49.89 | 78.28 | 81.29 | 67.41 | 68.66 | 66.78 |
| 6 | PAYX | pullback | 51.84 | 47.38 | 78.12 | 82.22 | 59.87 | 69.96 | 58.83 |
| 7 | FAST | pullback | 51.47 | 37.63 | 69.01 | 89.42 | 55.44 | 76.32 | 53.51 |
| 8 | CCC | pullback | 51.36 | 46.14 | 77.38 | 85.73 | 59.91 | 65.83 | 63.14 |
| 9 | GL9.IR | pullback | 51.28 | 40.59 | 73.86 | 97.71 | 32.39 | 74.58 | 51.98 |
| 10 | ARR | value+pullback | 50.94 | 66.37 | 46.74 | 38.91 | 41.86 | 46.61 | 44.88 |
| 11 | PBR-A | value | 50.70 | 68.23 | 30.95 | 72.58 | 60.20 | 66.64 | 71.56 |
| 12 | NTG.CO | pullback | 50.64 | 40.95 | 81.34 | 84.97 | 43.74 | 65.94 | 63.38 |
| 13 | DTG.DE | pullback | 50.58 | 55.25 | 73.73 |  | 80.68 | 82.90 | 59.59 |
| 14 | V | pullback | 50.21 | 39.59 | 70.01 | 93.31 | 38.79 | 74.15 | 56.68 |
| 15 | AMC | pullback | 49.79 |  | 77.72 | 81.95 | 59.23 | 60.70 | 70.81 |
| 16 | ASA | pullback | 49.65 | 50.62 | 74.91 | 81.03 |  | 68.83 | 61.69 |
| 17 | SHC | pullback | 49.61 | 41.21 | 72.57 | 83.84 | 51.15 | 68.87 | 60.04 |
| 18 | COLO-B.CO | pullback | 49.46 | 42.63 | 77.12 | 70.18 | 65.05 | 65.72 | 50.29 |
| 19 | BMY | pullback | 49.42 | 61.59 | 76.95 | 76.75 | 49.22 | 68.76 | 59.76 |
| 20 | SHO | pullback | 49.41 | 42.44 | 72.13 | 83.32 | 44.19 | 72.31 | 50.71 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.5 | 1 / 9 |
| Top 25 | 23/25 | 24/25 | 25/25 | 23/25 | 1/25 | 69.2 | 5 / 20 |
| Top 50 | 47/50 | 47/50 | 49/50 | 45/50 | 2/50 | 69.1 | 15 / 35 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=4, mid_5_20b=4, mega_100b_plus=1
