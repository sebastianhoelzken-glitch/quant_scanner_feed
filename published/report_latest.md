# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-10

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

- **EUROPE:** 80.4/100
- **OTHER:** 73.8/100
- **US:** 81.8/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | VLO      | VLO                        | US       |               96.32 |             82.78 |         82.69 |         87.56 |          82.87 |        75.74 |           85.08 |             82.06 |             49.1  |         3.44 |             69.68 | swing              |              nan    |                  0.15 |               nan    |
|      2 | HPE      | HPE                        | US       |               67.24 |             80.68 |         85.02 |         81.49 |          79.88 |        70.68 |           73.84 |             83.54 |             47.99 |         6.55 |             68.89 | short              |                6.95 |                  1.93 |                 1.7  |
|      3 | DELL     | DELL                       | US       |              292.69 |             80.32 |         89.7  |         83.71 |          76.92 |        64.44 |           71.86 |             77.05 |             28.45 |         7.64 |             68.77 | short              |                0.69 |                 -0.38 |                -0.98 |
|      4 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.87 |             79.8  |         89.12 |         82.55 |          77.05 |        73.48 |           78.21 |             80.52 |             52.86 |         5.25 |             84.92 | short              |                9.9  |                  0.72 |                 0.43 |
|      5 | DK       | DK                         | US       |                3.96 |             79.42 |         86.95 |         84.51 |          74.34 |        60.01 |           55.08 |             86.87 |             32.67 |         7.31 |             69.68 | short              |                0.84 |                  0.06 |                -0.55 |
|      6 | ANF      | ANF                        | US       |                5.55 |             79.31 |         90.32 |         83.11 |          75.5  |        72.22 |           86.47 |             65.86 |             48.76 |         8.61 |             67.64 | short              |                6.73 |                  0.68 |               nan    |
|      7 | CRGY     | CRGY                       | US       |                4.82 |             79.3  |         83.35 |         80.33 |          77.05 |        78.27 |           69.56 |             86.78 |             84.84 |         6.22 |             69.23 | short              |                1.5  |                 -0.09 |               nan    |
|      8 | UGP      | UGP                        | US       |                6.81 |             78.47 |         83.22 |         83.03 |          73.9  |        66.04 |           61.31 |             76.68 |             53.63 |         4.51 |             68.66 | short              |                0.13 |                 -0.27 |                -1.12 |
|      9 | PARR     | Par Pacific Holdings, Inc. | US       |                3.58 |             78.28 |         81.12 |         80.61 |          75.96 |        69.75 |           69.91 |             64.95 |             55.81 |         7.17 |             85.07 | short              |                0.72 |                 -0.01 |                -0.44 |
|     10 | EQNR     | EQNR                       | US       |               92.27 |             77.18 |         80.06 |         78.97 |          75.4  |        69.56 |           73.36 |             77.97 |             49.54 |         5.5  |             68.66 | short              |                4.5  |                  0.96 |               nan    |
|     11 | PBF      | PBF                        | US       |                7.8  |             76.96 |         78.85 |         82.26 |          75.08 |        68.57 |           51.09 |             70.62 |             77.72 |         7.6  |             69.23 | swing              |               -1.1  |                  0.22 |                 0.05 |
|     12 | MU       | MU                         | US       |              998.3  |             76.62 |         74.85 |         67.02 |          78.39 |        79.68 |           95.46 |             51.96 |             67.77 |         8.31 |             69.68 | long               |                2.5  |                 -0.32 |                -0.25 |
|     13 | KIN.BR   | KIN.BR                     | EUROPE   |                1.3  |             76.37 |         85.47 |         79.43 |          73.31 |        65.15 |           90.93 |             68.38 |             22.28 |         3.86 |             69.68 | short              |               -0.45 |                 -0.52 |                -0.97 |
|     14 | APA      | APA                        | US       |               13.51 |             76.23 |         79.96 |         77.45 |          75.01 |        71.15 |           72.23 |             72.4  |             59.67 |         5.79 |             68.66 | short              |                4.19 |                  1.77 |                 1.45 |
|     15 | DSX      | DSX                        | US       |                0.31 |             75.95 |         85.32 |         70.75 |          70.08 |        81.15 |           89.64 |             43.19 |             92.6  |         6.14 |             67.86 | short              |                0.68 |                 -0.9  |                -1.49 |
|     16 | VIST     | VIST                       | US       |                7.09 |             74.97 |         79.07 |         67.44 |          74.16 |        75.77 |           75.22 |             83.42 |             73.44 |         5.27 |             67.5  | short              |              nan    |                nan    |               nan    |
|     17 | PR       | PR                         | US       |               17.01 |             74.21 |         76.56 |         74.98 |          73.45 |        72.65 |           77.67 |             68.5  |             60.89 |         4.2  |             68.32 | short              |                0.12 |                 -0.55 |                -0.66 |
|     18 | BP       | BP                         | US       |              101.18 |             73.61 |         81.08 |         70.22 |          72.42 |        74.8  |           87.03 |             87.03 |             57.3  |         4.25 |             68.89 | short              |              nan    |                nan    |               nan    |
|     19 | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.77 |             73.52 |         74.94 |         68.35 |          72.18 |        74.86 |           96.58 |             61.8  |             56.95 |         2.23 |             69.68 | short              |               -0.29 |                  0.02 |                -0.41 |
|     20 | OMV.VI   | OMV.VI                     | EUROPE   |               23.11 |             73.17 |         74.86 |         74.6  |          71.75 |        68.52 |           66.81 |             79.19 |             64.97 |         2.17 |             68.89 | short              |                1.3  |                 -0.02 |                -0.22 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.12 |                  76.02 |                    75.64 |                 76.12 |              73.29 |                72.48 |                   27.52 |           91.11 |             55.07 |     nan     |         nan |       nan |        3.93 |        59.69 |          4.61 |        2.73 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                                   | US       |              101.18 |                  59.61 |                    70.5  |                 74.07 |              66.55 |                82.9  |                   17.1  |           87.03 |             87.03 |     nan     |         nan |       nan |      nan    |         9.47 |         21.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              235.21 |                  65.82 |                    69.27 |                 70.25 |              68.33 |                74.68 |                   25.32 |           72.73 |             74.99 |     nan     |         nan |       nan |      nan    |         9.51 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.58 |                  66.27 |                    68.3  |                 70.11 |              68.06 |                76.24 |                   23.76 |           75.71 |             66.18 |       0.181 |         nan |       nan |        4.16 |         2.71 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PRU      | PRU                                                  | US       |               34.89 |                  67.37 |                    67.92 |                 67.99 |              67.86 |                69.82 |                   30.18 |           68.09 |             67.85 |     nan     |         nan |       nan |      nan    |         7.92 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               16.12 |                  62.73 |                    67.78 |                 69.42 |              64.27 |                77.66 |                   22.34 |           87.43 |             51.2  |     nan     |         nan |       nan |      nan    |         8.6  |          7.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NLY      | NLY                                                  | US       |               14.66 |                  67.28 |                    67.09 |                 67.34 |              63.96 |                69.91 |                   30.09 |           88.7  |             29.36 |     nan     |         nan |       nan |      nan    |         7.27 |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               18.77 |                  55.48 |                    67.07 |                 70.91 |              61.17 |                83.57 |                   16.43 |           96.58 |             61.8  |     nan     |         nan |       nan |      nan    |        10.87 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                  | US       |               14.91 |                  55.3  |                    66.58 |                 70.17 |              62.31 |                81.33 |                   18.67 |           85.23 |             78.55 |     nan     |         nan |       nan |      nan    |        10.69 |         23.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                                                | US       |              111.82 |                  69.33 |                    66.18 |                 65.49 |              65.57 |                61.87 |                   38.13 |           72.96 |             45.15 |     nan     |         nan |       nan |      nan    |         7.72 |          4.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                                             | EUROPE   |               14.65 |                  56.64 |                    66.16 |                 68.98 |              62.5  |                81.67 |                   18.33 |           82.88 |             70.18 |     nan     |         nan |       nan |      nan    |        11.19 |         14.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                                               | EUROPE   |               23.77 |                  55.31 |                    65.59 |                 69.07 |              59.7  |                80.76 |                   19.24 |           96.21 |             53.46 |     nan     |         nan |       nan |      nan    |        11.49 |         11.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVS      | CVS                                                  | US       |              104.91 |                  60.94 |                    65.51 |                 66.73 |              65.05 |                76.12 |                   23.88 |          nan    |             74.72 |     nan     |         nan |       nan |      nan    |        11.19 |         25.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                                               | EUROPE   |               11.65 |                  62.16 |                    65.47 |                 66.19 |              64.97 |                72.67 |                   27.33 |           66.49 |             71.32 |     nan     |         nan |       nan |      nan    |         8.51 |         12.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                                                  | US       |              116    |                  69.44 |                    65.4  |                 64.5  |              64.74 |                59.76 |                   40.24 |           73.23 |             39.87 |     nan     |         nan |       nan |      nan    |         5.25 |          5.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | RCI      | RCI                                                  | US       |               16.93 |                  58.65 |                    64.61 |                 66.82 |              60.43 |                72.5  |                   27.5  |           87.28 |             51.56 |     nan     |         nan |       nan |      nan    |        10.45 |          4.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                                               | EUROPE   |                1.71 |                  52.23 |                    64.54 |                 68.7  |              57.97 |                81.85 |                   18.15 |           97.86 |             56.32 |     nan     |         nan |       nan |      nan    |        10.69 |         11.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | ALL-PH   | The Allstate Corporation                             | US       |               24.05 |                  68.85 |                    64.48 |                 63.11 |              64.96 |                61.29 |                   38.71 |           65.63 |             43.52 |       0.542 |         nan |       nan |        0.49 |       nan    |          3.38 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | OMV.VI   | OMV.VI                                               | EUROPE   |               23.11 |                  57.8  |                    64.1  |                 65.75 |              62.93 |                74.39 |                   25.61 |           66.81 |             79.19 |     nan     |         nan |       nan |      nan    |         9.26 |         14.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DTG.DE   | DTG.DE                                               | EUROPE   |               33.4  |                  56.11 |                    64.09 |                 66.25 |              63.28 |                82.41 |                   17.59 |          nan    |             80.52 |     nan     |         nan |       nan |      nan    |         9.18 |         30.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.12 |                  76.02 |                    75.64 |                 76.12 |              73.29 |                72.48 |                   27.52 |           91.11 |             55.07 |     nan     |         nan |       nan |        3.93 |        59.69 |          4.61 |        2.73 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                                                   | US       |              101.18 |                  59.61 |                    70.5  |                 74.07 |              66.55 |                82.9  |                   17.1  |           87.03 |             87.03 |     nan     |         nan |       nan |      nan    |         9.47 |         21.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                              | EUROPE   |               18.77 |                  55.48 |                    67.07 |                 70.91 |              61.17 |                83.57 |                   16.43 |           96.58 |             61.8  |     nan     |         nan |       nan |      nan    |        10.87 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                 | US       |              235.21 |                  65.82 |                    69.27 |                 70.25 |              68.33 |                74.68 |                   25.32 |           72.73 |             74.99 |     nan     |         nan |       nan |      nan    |         9.51 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                  | US       |               14.91 |                  55.3  |                    66.58 |                 70.17 |              62.31 |                81.33 |                   18.67 |           85.23 |             78.55 |     nan     |         nan |       nan |      nan    |        10.69 |         23.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | IRWD     | Ironwood Pharmaceuticals, Inc.                       | US       |                0.58 |                  66.27 |                    68.3  |                 70.11 |              68.06 |                76.24 |                   23.76 |           75.71 |             66.18 |       0.181 |         nan |       nan |        4.16 |         2.71 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                                               | EUROPE   |               16.12 |                  62.73 |                    67.78 |                 69.42 |              64.27 |                77.66 |                   22.34 |           87.43 |             51.2  |     nan     |         nan |       nan |      nan    |         8.6  |          7.59 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                                               | EUROPE   |               23.77 |                  55.31 |                    65.59 |                 69.07 |              59.7  |                80.76 |                   19.24 |           96.21 |             53.46 |     nan     |         nan |       nan |      nan    |        11.49 |         11.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                                             | EUROPE   |               14.65 |                  56.64 |                    66.16 |                 68.98 |              62.5  |                81.67 |                   18.33 |           82.88 |             70.18 |     nan     |         nan |       nan |      nan    |        11.19 |         14.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | C5H.IR   | C5H.IR                                               | EUROPE   |                1.71 |                  52.23 |                    64.54 |                 68.7  |              57.97 |                81.85 |                   18.15 |           97.86 |             56.32 |     nan     |         nan |       nan |      nan    |        10.69 |         11.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PRU      | PRU                                                  | US       |               34.89 |                  67.37 |                    67.92 |                 67.99 |              67.86 |                69.82 |                   30.18 |           68.09 |             67.85 |     nan     |         nan |       nan |      nan    |         7.92 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                                  | US       |               96.32 |                  48.91 |                    63.32 |                 67.88 |              58.17 |                81.92 |                   18.08 |           85.08 |             82.06 |     nan     |         nan |       nan |      nan    |        11.92 |         16.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | TNK      | Teekay Tankers Ltd.                                  | OTHER    |                2.87 |                  53.82 |                    63.83 |                 67.59 |              60.89 |                78.26 |                   21.74 |           78.21 |             80.52 |       0.068 |         nan |       nan |        4.24 |         8.84 |          5.68 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | NLY      | NLY                                                  | US       |               14.66 |                  67.28 |                    67.09 |                 67.34 |              63.96 |                69.91 |                   30.09 |           88.7  |             29.36 |     nan     |         nan |       nan |      nan    |         7.27 |          5.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OXY      | OXY                                                  | US       |               52.7  |                  50.23 |                    62.84 |                 67    |              57.88 |                77.62 |                   22.38 |           84.57 |             77.38 |     nan     |         nan |       nan |      nan    |        15.85 |         18.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | RCI      | RCI                                                  | US       |               16.93 |                  58.65 |                    64.61 |                 66.82 |              60.43 |                72.5  |                   27.5  |           87.28 |             51.56 |     nan     |         nan |       nan |      nan    |        10.45 |          4.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVS      | CVS                                                  | US       |              104.91 |                  60.94 |                    65.51 |                 66.73 |              65.05 |                76.12 |                   23.88 |          nan    |             74.72 |     nan     |         nan |       nan |      nan    |        11.19 |         25.17 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DTG.DE   | DTG.DE                                               | EUROPE   |               33.4  |                  56.11 |                    64.09 |                 66.25 |              63.28 |                82.41 |                   17.59 |          nan    |             80.52 |     nan     |         nan |       nan |      nan    |         9.18 |         30.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGN.AS   | AGN.AS                                               | EUROPE   |               11.65 |                  62.16 |                    65.47 |                 66.19 |              64.97 |                72.67 |                   27.33 |           66.49 |             71.32 |     nan     |         nan |       nan |      nan    |         8.51 |         12.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | OMV.VI   | OMV.VI                                               | EUROPE   |               23.11 |                  57.8  |                    64.1  |                 65.75 |              62.93 |                74.39 |                   25.61 |           66.81 |             79.19 |     nan     |         nan |       nan |      nan    |         9.26 |         14.85 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | ARGX.BR  | ARGX.BR  | EUROPE   |               53.8  |                     0.05 |    -0.04 |      0.14 |                  80.27 |                        76.92 |         70.26 |         66.2  |          65.75 |        59.61 |           94.25 |             72.68 |         6.17 |
|               2 | WT       | WT       | US       |                3.11 |                     0.05 |    -0.02 |      0.09 |                  71.65 |                        75.87 |         72.05 |         78.55 |          73.15 |        62.75 |           71.01 |             77.61 |         5.64 |
|               3 | VIST     | VIST     | US       |                7.09 |                     0.03 |    -0    |      0.13 |                  57.1  |                        75.66 |         79.07 |         67.44 |          74.16 |        75.77 |           75.22 |             83.42 |         5.27 |
|               4 | XP       | XP       | US       |                8.31 |                     0.05 |     0.02 |      0.23 |                  61.51 |                        73.75 |         81.76 |         67.34 |          58.95 |        63.39 |           53.73 |             85.96 |         6.09 |
|               5 | RAND.AS  | RAND.AS  | EUROPE   |                6.62 |                     0.06 |    -0.02 |     -0.02 |                  70.82 |                        72.92 |         53.43 |         71.85 |          69.08 |        63.9  |           81.04 |             67.76 |         6.9  |
|               6 | CRM      | CRM      | US       |              172.82 |                     0.08 |    -0.05 |      0.24 |                  73.19 |                        72.29 |         77.12 |         72.66 |          58.76 |        54.66 |           61.43 |             69.74 |         7.91 |
|               7 | ASRNL.AS | ASRNL.AS | EUROPE   |               14.65 |                     0.02 |    -0.01 |      0.05 |                  53.58 |                        71.98 |         73.67 |         69.27 |          69.46 |        68.33 |           82.88 |             70.18 |         1.09 |
|               8 | DOCU     | DOCU     | US       |               10.36 |                     0.06 |    -0    |      0.09 |                  69.9  |                        71.5  |         72.9  |         73.67 |          62.81 |        56.95 |           58.59 |             83.07 |         7.89 |
|               9 | NTNX     | NTNX     | US       |               15.56 |                     0.04 |     0    |      0.04 |                  61.4  |                        70.61 |         67.91 |         70.12 |          64.53 |        58.93 |           94.72 |             49.29 |         6.78 |
|              10 | AMC      | AMC      | US       |                1.89 |                     0.09 |    -0.05 |      0.02 |                  63.42 |                        70.51 |         52.23 |         70.7  |          70.31 |        71.39 |           82.81 |             60.57 |         9.68 |
|              11 | PLTR     | PLTR     | US       |              350.37 |                     0.09 |    -0.06 |     -0.03 |                  65.76 |                        70.5  |         50.87 |         64.49 |          60.74 |        57.57 |           88.99 |             70.59 |         8.65 |
|              12 | WDAY     | WDAY     | US       |               38.56 |                     0.1  |    -0.06 |      0.03 |                  60.57 |                        69.11 |         59.88 |         69.08 |          62.31 |        59.58 |           73.12 |             72.37 |         8.71 |
|              13 | SWON.SW  | SWON.SW  | EUROPE   |                2.16 |                     0.03 |    -0    |      0.05 |                  56.05 |                        68.8  |         73.71 |         70.31 |          64.75 |        58.43 |           56.3  |             81.84 |         5.72 |
|              14 | MRK      | MRK      | US       |              313.04 |                     0.06 |    -0.02 |      0.13 |                  74.12 |                        68.4  |         74.01 |         69.87 |          62.88 |        53.16 |           47.43 |             71.92 |         3.57 |
|              15 | VIR      | VIR      | US       |                1.57 |                     0.07 |    -0.07 |      0.21 |                  81.8  |                        67.87 |         71.79 |         65.7  |          60.54 |        58.69 |           52.57 |             61.27 |         6.03 |
|              16 | ABN.AS   | ABN.AS   | EUROPE   |               34.66 |                     0.02 |     0    |      0.03 |                  47.97 |                        67.73 |         69.74 |         71.71 |          71.93 |        68.11 |           79.99 |             57.92 |         2.84 |
|              17 | KDP      | KDP      | US       |               37.55 |                     0.02 |     0.01 |      0.1  |                  50.11 |                        67.52 |         68.81 |         57.56 |          61.28 |        67.12 |           86.35 |             55.51 |         3.44 |
|              18 | KOS      | KOS      | US       |                1.47 |                     0.05 |    -0.03 |      0.12 |                  75.44 |                        67.4  |         66.84 |         57.92 |          63.56 |        64.13 |           64.06 |             65.69 |         8.83 |
|              19 | CCC      | CCC      | US       |                3.44 |                     0.11 |    -0.06 |     -0.01 |                  57.03 |                        67.33 |         50.57 |         64.91 |          61.72 |        65.71 |           85.71 |             61.19 |         8.26 |
|              20 | GEN      | GEN      | US       |               15.32 |                     0.05 |    -0.01 |      0.03 |                  70.33 |                        67.24 |         67.62 |         67.86 |          63.96 |        64.64 |           74.44 |             52.52 |         5.78 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

_No rows._

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     28 | GOLD     | GOLD   | US       |                1.24 |             72.56 |         82.99 |         64.73 |          69.92 |        75.2  |           90.19 |             71.12 |             51.86 |         7.28 |             68.89 | short              |                0.71 |                  4.05 |                 3.29 |
|     88 | CMPS     | CMPS   | US       |                1.81 |             67.09 |         77.83 |         72.93 |          61.25 |        43.94 |           44.6  |             55.96 |              4.9  |         7.86 |             65.82 | short              |                5.33 |                  3.29 |                 3.32 |
|     39 | AMD      | AMD    | US       |              731.62 |             71.49 |         74.85 |         69.2  |          73.79 |        60.88 |           79.03 |             78.75 |              9.75 |         7.16 |             65.64 | short              |                5.23 |                  3.06 |                 2.33 |
|     36 | ASX      | ASX    | US       |               92.26 |             71.67 |         73.35 |         71.97 |          71.36 |        58.41 |           63.79 |             77.03 |             21.32 |         7.38 |             69.23 | short              |                4.13 |                  3.04 |                 2.33 |
|     23 | HQL      | HQL    | US       |                0.53 |             72.87 |         51.98 |         70.42 |          75.94 |        75.32 |          nan    |            nan    |             73.07 |         2.11 |             55.57 | medium             |               -0.24 |                  2.99 |                 2.74 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    614 | ACRS     | ACRS    | US       |                0.7  |             42.07 |         32.4  |         52.15 |          49.09 |        35.05 |           20.53 |             30.59 |             21.85 |         7.23 |             66.84 | swing              |              -15.13 |                 -3.99 |                -3.35 |
|    470 | HMC      | HMC     | US       |               34.93 |             49.31 |         46.27 |         56.87 |          47.24 |        51.37 |           25.26 |            nan    |             89.64 |         5.07 |             61.82 | swing              |                1.64 |                 -3.89 |                -3.04 |
|    607 | KSS      | KSS     | US       |                1.71 |             42.37 |         39.43 |         41.89 |          42.86 |        42.96 |           25.35 |             30.25 |             66.6  |         8.25 |             67.86 | long               |               -2.57 |                 -3.86 |                -3.35 |
|    689 | NOVN.SW  | NOVN.SW | EUROPE   |              225.68 |             33.64 |         27.06 |         28.68 |          38.6  |        42.15 |           53.64 |             33.93 |             27.55 |         3.41 |             66.43 | long               |               -9.11 |                 -3.84 |                -2.79 |
|    703 | BBWI     | BBWI    | US       |                3.07 |             31.41 |         31    |         26.16 |          31.82 |        45.99 |           35.46 |              9.31 |             87.9  |         7.82 |             65.68 | long               |               -5.56 |                 -3.76 |               nan    |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.90

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
- Event watch (otherwise eligible): **0**
- Final eligible: **719**
- Eligible change vs previous stored run: **+7**

Top exclusion categories:
- liquidity: 226
- price: 180
- market_cap: 154
- price_history: 16
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| TNK | 4 | 4 |  | 3 | 2 | main,value,quality_value |
| IRS | 111 | 1 |  | 1 | 1 | value,quality_value |
| STNG | 134 | 8 |  | 4 | 1 | value,quality_value |
| IRWD | 201 | 2 | 59 | 2 | 1 | value,quality_value |
| RMT | 250 | 9 |  | 6 | 1 | value,quality_value |
| BCE | 424 | 10 | 118 | 7 | 1 | value,quality_value |
| AVK | 469 | 5 |  | 8 | 1 | value,quality_value |
| ALL-PH | 514 | 3 | 256 | 5 | 1 | value,quality_value |
| CHTR | 664 | 7 |  | 9 | 1 | value,quality_value |
| VLO | 1 |  |  |  | 1 | main |
| HPE | 2 |  |  |  | 1 | main |
| DELL | 3 |  |  |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |
| ANF | 6 |  |  |  | 1 | main |
| CRGY | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **8** (VLO, HPE, DELL, DK, ANF, CRGY, UGP, EQNR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (VIST, ASRNL.AS)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | IRWD | value+pullback | 70.81 | 66.27 | 70.82 | 75.71 | 66.18 | 76.24 | 60.63 |
| 2 | AVK | value+pullback | 62.88 | 63.08 | 69.66 | 62.44 |  | 60.87 | 49.37 |
| 3 | RMT | value+pullback | 62.25 | 58.07 | 68.43 | 74.09 |  | 58.05 | 58.78 |
| 4 | ALL-PH | value+pullback | 60.52 | 68.85 | 53.64 | 65.63 | 43.52 | 61.29 | 47.34 |
| 5 | LNC | value+pullback | 58.92 | 68.40 | 60.28 | 47.23 | 68.83 | 46.83 | 63.48 |
| 6 | GTN | value+pullback | 57.42 | 64.63 | 49.67 | 65.87 | 43.57 | 56.88 | 49.83 |
| 7 | ARGX.BR | pullback | 57.09 | 34.93 | 80.27 | 94.25 | 72.68 | 78.08 | 65.97 |
| 8 | IRS | value | 56.48 | 76.02 | 30.95 | 91.11 | 55.07 | 72.48 | 65.90 |
| 9 | BMY | pullback | 50.92 | 61.14 | 81.18 | 77.64 | 50.78 | 69.52 | 60.61 |
| 10 | PLTR | pullback | 50.82 | 36.06 | 65.76 | 88.99 | 70.59 | 69.87 | 59.15 |
| 11 | ISS.CO | pullback | 50.45 | 42.45 | 71.03 | 79.65 | 59.66 | 73.90 | 57.35 |
| 12 | FAST | pullback | 50.45 | 37.06 | 63.98 | 90.22 | 55.79 | 76.70 | 53.55 |
| 13 | RAND.AS | pullback | 50.33 | 49.98 | 70.82 | 81.04 | 67.76 | 68.45 | 66.49 |
| 14 | MA | pullback | 50.25 | 37.27 | 77.01 | 97.30 | 23.73 | 70.17 | 53.10 |
| 15 | WT | pullback | 50.14 | 36.35 | 71.65 | 71.01 | 77.61 | 69.10 | 72.60 |
| 16 | AGS.BR | pullback | 50.11 | 62.73 | 65.36 | 87.43 | 51.20 | 77.66 | 64.87 |
| 17 | NSIS-B.CO | pullback | 50.07 | 35.57 | 79.11 | 67.85 | 66.40 | 67.35 | 56.78 |
| 18 | V | pullback | 50.03 | 40.14 | 67.91 | 93.70 | 40.37 | 74.82 | 57.75 |
| 19 | APH | pullback | 49.83 | 38.52 | 67.35 | 77.66 | 72.12 | 70.65 | 57.31 |
| 20 | DTG.DE | pullback | 49.79 | 56.11 | 71.03 |  | 80.52 | 82.41 | 56.16 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 10/10 | 10/10 | 0/10 | 69.1 | 2 / 8 |
| Top 25 | 22/25 | 24/25 | 25/25 | 22/25 | 1/25 | 68.9 | 5 / 20 |
| Top 50 | 47/50 | 49/50 | 49/50 | 46/50 | 1/50 | 69.2 | 11 / 39 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=2, large_20_100b=3, mega_100b_plus=1
