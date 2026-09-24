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

- **EUROPE:** 80.1/100
- **OTHER:** 65.8/100
- **US:** 80.9/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC      | US       |               95.27 |             85.97 |         77.67 |         88.29 |          87.79 |        84.16 |           84.32 |             89.97 |             72.66 |         4.33 |             73.14 | swing              |               -1.17 |                nan    |               nan    |
|      2 | HPE      | HPE      | US       |               72.28 |             83.39 |         90.94 |         85.66 |          81.11 |        72.31 |           72.81 |             80.85 |             50.93 |         7    |             72.34 | short              |                2.03 |                  0.72 |               nan    |
|      3 | MU       | MU       | US       |             1057.46 |             83.29 |         80.75 |         74.8  |          86.44 |        85.83 |           95.41 |             81.35 |             72.44 |         8.25 |             73.14 | medium             |                2.52 |                  2.87 |                 2.21 |
|      4 | VLO      | VLO      | US       |               94.53 |             82.81 |         76.56 |         85.33 |          84.83 |        80.79 |           85.66 |             80.98 |             62.46 |         3.66 |             69.68 | swing              |               -2.93 |                  1.1  |                 1    |
|      5 | DELL     | DELL     | US       |              305.37 |             82.46 |         84.24 |         84.18 |          80.74 |        68.54 |           72.6  |             85.97 |             34.09 |         7.85 |             72.23 | short              |               -1.16 |                  0.05 |                -0.12 |
|      6 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |             82.25 |         79.45 |         82.07 |          84.29 |        82.42 |           96.27 |             77.45 |             62.61 |         3.69 |             73.14 | medium             |               -1.94 |                  1.22 |                 1.17 |
|      7 | FRO      | FRO      | US       |                9.25 |             82.1  |         82.05 |         82.15 |          83.68 |        81.46 |           91.52 |             80.48 |             59.1  |         5.59 |             73.14 | medium             |               -2.81 |                  0.55 |                 0.49 |
|      8 | HSHP     | HSHP     | US       |                0.75 |             81.31 |         85.16 |         82.99 |          79.63 |        70.23 |           86.41 |            nan    |             29.02 |         4.84 |             62.84 | short              |               -1.49 |                nan    |               nan    |
|      9 | PSX      | PSX      | US       |               89.83 |             80.73 |         78.9  |         85.37 |          82.56 |        78.03 |           79.49 |             85.53 |             60.21 |         3.84 |             73.14 | swing              |               -3.13 |                  1.13 |                 1.19 |
|     10 | AMC      | AMC      | US       |                2.24 |             80.61 |         81.01 |         86.36 |          80.21 |        79.4  |           85.22 |             79.02 |            nan    |         9.52 |             65.07 | swing              |                4.42 |                  4.34 |                 4.04 |
|     11 | DHT      | DHT      | US       |                3    |             78.63 |         77.11 |         77.19 |          80.08 |        81.24 |           88.71 |             83.13 |             64.35 |         4.76 |             73.14 | long               |               -3.43 |                  0.45 |                 0.22 |
|     12 | OKTA     | OKTA     | US       |               31.36 |             78.44 |         91.16 |         84.63 |          72.24 |        58.64 |           68.67 |             68.9  |             14.18 |         7.84 |             72.11 | short              |               -0.09 |                  0.94 |                 0.93 |
|     13 | NAT      | NAT      | US       |                1.41 |             77.55 |         80.07 |         77.3  |          77.8  |        73.49 |           87.59 |             70.12 |             40.52 |         4.95 |             73.14 | short              |               -3.01 |                 -0.11 |                -0.01 |
|     14 | REP.MC   | REP.MC   | EUROPE   |               32.74 |             77.41 |         82.35 |         80.7  |          74.13 |        70.03 |           59.69 |             79.22 |             70    |         3.77 |             73.14 | short              |                2.76 |                  1.64 |                 1.31 |
|     15 | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |             77.04 |         78.88 |         75.21 |          74.08 |        79.7  |           93.52 |             81.89 |             64.54 |         2.44 |             73.14 | long               |                2.89 |                  2.6  |                 2.47 |
|     16 | KIN.BR   | KIN.BR   | EUROPE   |                1.36 |             77.04 |         80.11 |         79.96 |          74.12 |        65.1  |           90.22 |             64.52 |             17.68 |         3.8  |             73.14 | short              |               -0.71 |                 -0.33 |                -0.25 |
|     17 | HALO     | HALO     | US       |               11.15 |             76.59 |         78.24 |         79.9  |          74.95 |        71.45 |           85.52 |             52.15 |             48.94 |         6.06 |             72.11 | swing              |                0.48 |                nan    |               nan    |
|     18 | P        | P        | US       |               31.92 |             76.57 |         87.44 |         82.36 |          70.78 |        58.37 |           69.36 |             85.92 |             14.45 |         8.11 |             72.68 | short              |               -0.8  |                  2.39 |                 1.72 |
|     19 | AMS.SW   | AMS.SW   | EUROPE   |                2.49 |             76.51 |         86.69 |         82.6  |          70.42 |        52.05 |           53.31 |             89.2  |              8.91 |         8.67 |             73.14 | short              |                5.44 |                  5.38 |               nan    |
|     20 | UGP      | UGP      | US       |                7.13 |             76.36 |         79.33 |         82.58 |          73.39 |        66.62 |           59.97 |             68.03 |             56.49 |         4.72 |             72.11 | swing              |               -0.11 |                  0.84 |                 0.35 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.02 |                  73.97 |                    74.49 |                 76.18 |              74.69 |                86.75 |                   13.25 |           84.64 |             58.14 |       0.87  |         nan |       nan |      nan    |       -78.29 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              237.89 |                  58.11 |                    70.94 |                 75.03 |              65.89 |                88.09 |                   11.91 |           93.52 |             81.89 |     nan     |         nan |       nan |      nan    |         9.5  |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA      | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    70.77 |                 72.78 |              65.8  |                77.41 |                   22.59 |           86.9  |             80.35 |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |              100.09 |                  60.32 |                    70.48 |                 73.85 |              66.66 |                81.61 |                   18.39 |           86.67 |             85.33 |     nan     |         nan |       nan |      nan    |         9.11 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                                 | US       |              237.78 |                  65.84 |                    70.27 |                 71.56 |              69.16 |                76.47 |                   23.53 |           73.91 |             79.87 |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                3    |                  59.76 |                    70.22 |                 73.76 |              66.01 |                81.48 |                   18.52 |           88.71 |             83.13 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  75.89 |                    70.16 |                 70.1  |              72.94 |                57.47 |                   42.53 |           61.58 |             79.56 |       0.141 |         nan |       nan |        1.8  |         4.78 |          4.78 |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.37 |                  68.48 |                    69.78 |                 71.74 |              68.68 |                68.66 |                   31.34 |           80.43 |             70.11 |       0.021 |         nan |       nan |        3.78 |         5.56 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | EMBC      | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.72 |                 69.77 |              70.67 |                62.56 |                   37.44 |           70.56 |             64.22 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | STNE      | StoneCo Ltd.                         | OTHER    |                1.91 |                  72.17 |                    69.42 |                 68.98 |              67.43 |                68.01 |                   31.99 |           85.87 |             32.25 |       0.634 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM        | SM                                   | US       |                7.13 |                  62.97 |                    69.3  |                 71.76 |              66.4  |                72.39 |                   27.61 |           82.06 |             80.35 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.89 |                  55.82 |                    69.18 |                 73.64 |              63.33 |                85.55 |                   14.45 |           96.27 |             77.45 |     nan     |         nan |       nan |      nan    |         9.3  |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | BBWI      | Bath & Body Works, Inc.              | US       |                3    |                  74.85 |                    69.15 |                 66.69 |              67.97 |                59.23 |                   40.77 |           75.98 |             34.2  |       0.223 |         nan |       nan |        5.61 |         6.11 |          4.5  |        0.7  |                 nan |              nan |                  11 |                  0.58 |
|            8 | INVA      | Innoviva, Inc.                       | US       |                1.28 |                  64.94 |                    69.1  |                 71.55 |              66.44 |                82.48 |                   17.52 |           90.78 |             48.37 |       0.075 |         nan |       nan |        6.22 |         9.16 |          4.87 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|            9 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               59.14 |                  74.59 |                    68.56 |                 65.91 |              70.89 |                60.34 |                   39.66 |           55.24 |             63.24 |       0.036 |         nan |       nan |       15.65 |        13.14 |         18.59 |        0.97 |                 nan |              nan |                  12 |                  0.63 |
|           10 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.75 |                  73.61 |                    68.49 |                 68.84 |              69.72 |                68.68 |                   31.32 |           75.5  |             43.6  |       0.617 |         nan |       nan |        4.65 |      -131.16 |          2.26 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | FRO       | FRO                                  | US       |                9.25 |                  56.45 |                    68.29 |                 72.41 |              63.16 |                80.38 |                   19.62 |           91.52 |             80.48 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | AVGO      | Broadcom Inc.                        | US       |             1480.26 |                  60.81 |                    68.27 |                 68.86 |              62.34 |                78.42 |                   21.58 |           92.29 |             44.41 |       0.018 |         nan |       nan |       33.1  |        18.31 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|           12 | IHS       | IHS Holding Limited                  | OTHER    |                2.49 |                  72.11 |                    67.85 |                 68.04 |              71.03 |                62.72 |                   37.28 |           57.81 |             78.22 |      -0.114 |         nan |       nan |        7.51 |        15.31 |          5.17 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.76 |                  55.32 |                    67.66 |                 71.72 |              61.73 |                85.02 |                   14.98 |           96.71 |             65.94 |     nan     |         nan |       nan |      nan    |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.02 |                  73.97 |                    74.49 |                 76.18 |              74.69 |                86.75 |                   13.25 |           84.64 |             58.14 |       0.87  |         nan |       nan |      nan    |       -78.29 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              237.89 |                  58.11 |                    70.94 |                 75.03 |              65.89 |                88.09 |                   11.91 |           93.52 |             81.89 |     nan     |         nan |       nan |      nan    |         9.5  |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.09 |                  60.32 |                    70.48 |                 73.85 |              66.66 |                81.61 |                   18.39 |           86.67 |             85.33 |     nan     |         nan |       nan |      nan    |         9.11 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3    |                  59.76 |                    70.22 |                 73.76 |              66.01 |                81.48 |                   18.52 |           88.71 |             83.13 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.89 |                  55.82 |                    69.18 |                 73.64 |              63.33 |                85.55 |                   14.45 |           96.27 |             77.45 |     nan     |         nan |       nan |      nan    |         9.3  |          6.53 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NVDA     | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    70.77 |                 72.78 |              65.8  |                77.41 |                   22.59 |           86.9  |             80.35 |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | FRO      | FRO                                  | US       |                9.25 |                  56.45 |                    68.29 |                 72.41 |              63.16 |                80.38 |                   19.62 |           91.52 |             80.48 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.13 |                  62.97 |                    69.3  |                 71.76 |              66.4  |                72.39 |                   27.61 |           82.06 |             80.35 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.37 |                  68.48 |                    69.78 |                 71.74 |              68.68 |                68.66 |                   31.34 |           80.43 |             70.11 |       0.021 |         nan |       nan |        3.78 |         5.56 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.76 |                  55.32 |                    67.66 |                 71.72 |              61.73 |                85.02 |                   14.98 |           96.71 |             65.94 |     nan     |         nan |       nan |      nan    |        10.84 |         14.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              237.78 |                  65.84 |                    70.27 |                 71.56 |              69.16 |                76.47 |                   23.53 |           73.91 |             79.87 |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | INVA     | Innoviva, Inc.                       | US       |                1.28 |                  64.94 |                    69.1  |                 71.55 |              66.44 |                82.48 |                   17.52 |           90.78 |             48.37 |       0.075 |         nan |       nan |        6.22 |         9.16 |          4.87 |        0.25 |                 nan |              nan |                  10 |                  0.53 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  75.89 |                    70.16 |                 70.1  |              72.94 |                57.47 |                   42.53 |           61.58 |             79.56 |       0.141 |         nan |       nan |        1.8  |         4.78 |          4.78 |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|          nan | MU       | MU                                   | US       |             1057.46 |                  49.34 |                    64.4  |                 69.86 |              57.58 |                77.33 |                   22.67 |           95.41 |             81.35 |     nan     |         nan |       nan |      nan    |         6.74 |         24.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               95.27 |                  50.79 |                    65.19 |                 69.78 |              60.39 |                82.32 |                   17.68 |           84.32 |             89.97 |     nan     |         nan |       nan |      nan    |         8.24 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  73.59 |                    69.72 |                 69.77 |              70.67 |                62.56 |                   37.44 |           70.56 |             64.22 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAGP     | PAGP                                 | US       |                5.43 |                  50.7  |                    65.18 |                 69.52 |              60.53 |                85.85 |                   14.15 |           83.88 |             85.74 |     nan     |         nan |       nan |      nan    |        12.94 |         76.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.67 |                  62.58 |                    67.44 |                 69.02 |              64.03 |                77.09 |                   22.91 |           86.57 |             51    |     nan     |         nan |       nan |      nan    |         8.62 |          7.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.91 |                  72.17 |                    69.42 |                 68.98 |              67.43 |                68.01 |                   31.99 |           85.87 |             32.25 |       0.634 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           11 | AVGO     | Broadcom Inc.                        | US       |             1480.26 |                  60.81 |                    68.27 |                 68.86 |              62.34 |                78.42 |                   21.58 |           92.29 |             44.41 |       0.018 |         nan |       nan |       33.1  |        18.31 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC      | MPC      | US       |               95.27 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        84.96 |         77.67 |         88.29 |          87.79 |        84.16 |           84.32 |             89.97 |         4.33 |
|               2 | FRO      | FRO      | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        82.58 |         82.05 |         82.15 |          83.68 |        81.46 |           91.52 |             80.48 |         5.59 |
|               3 | PSX      | PSX      | US       |               89.83 |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        82.49 |         78.9  |         85.37 |          82.56 |        78.03 |           79.49 |             85.53 |         3.84 |
|               4 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.89 |                     0.07 |    -0.02 |      0.11 |                  70.16 |                        82.43 |         79.45 |         82.07 |          84.29 |        82.42 |           96.27 |             77.45 |         3.69 |
|               5 | VLO      | VLO      | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        82.24 |         76.56 |         85.33 |          84.83 |        80.79 |           85.66 |             80.98 |         3.66 |
|               6 | DELL     | DELL     | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        80.22 |         84.24 |         84.18 |          80.74 |        68.54 |           72.6  |             85.97 |         7.85 |
|               7 | DHT      | DHT      | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        79.94 |         77.11 |         77.19 |          80.08 |        81.24 |           88.71 |             83.13 |         4.76 |
|               8 | BP       | BP       | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        79.1  |         75.41 |         72.76 |          72.19 |        78.32 |           86.67 |             85.33 |         4.53 |
|               9 | NAT      | NAT      | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        78.74 |         80.07 |         77.3  |          77.8  |        73.49 |           87.59 |             70.12 |         4.95 |
|              10 | SHELL.AS | SHELL.AS | EUROPE   |              237.89 |                     0.02 |    -0    |      0.06 |                  52.58 |                        78.32 |         78.88 |         75.21 |          74.08 |        79.7  |           93.52 |             81.89 |         2.44 |
|              11 | SMTC     | SMTC     | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        77.51 |         85.3  |         73.47 |          74.37 |        62.05 |           73.95 |             84.47 |         8.48 |
|              12 | PAGP     | PAGP     | US       |                5.43 |                     0.06 |    -0.04 |     -0.02 |                  76.61 |                        77.28 |         61.05 |         72.3  |          75.64 |        75.55 |           83.88 |             85.74 |         1.76 |
|              13 | EQNR     | EQNR     | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        77.02 |         70.75 |         76.7  |          74.41 |        74.29 |           74.3  |             83.83 |         5.69 |
|              14 | DAR      | DAR      | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        75.52 |         55.59 |         69.09 |          78.24 |        84.25 |           91.13 |             86.06 |         4.76 |
|              15 | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                     0.05 |    -0    |      0.06 |                  67.99 |                        75.36 |         75.11 |         66.89 |          71.03 |        74.73 |           97.88 |             53.56 |         2.68 |
|              16 | BIRG.IR  | BIRG.IR  | EUROPE   |               18.76 |                     0.02 |    -0.02 |      0.05 |                  57.74 |                        75.08 |         74.37 |         71.62 |          74.02 |        76.12 |           96.71 |             65.94 |         2.21 |
|              17 | APA      | APA      | US       |               13.37 |                     0.08 |    -0.02 |      0.06 |                  63.54 |                        74.72 |         73.03 |         75.98 |          75.01 |        77.35 |           75.12 |             81.15 |         6.06 |
|              18 | MT.AS    | MT.AS    | EUROPE   |               47.69 |                     0.06 |    -0.02 |     -0.02 |                  72.8  |                        74.51 |         60.97 |         74.2  |          77.22 |        74.08 |           71.52 |             81.29 |         5.04 |
|              19 | AVAH     | AVAH     | US       |                2.44 |                     0.11 |    -0.1  |     -0.06 |                  65.6  |                        74.4  |         52.61 |         75.54 |          77.86 |        73.89 |           92.92 |             54.71 |         7.77 |
|              20 | CIRSA.MC | CIRSA.MC | EUROPE   |                3.26 |                     0.02 |    -0.01 |      0.4  |                  49.44 |                        74.34 |         83.06 |         78.71 |          68.62 |        67.62 |           83.32 |             58.18 |         5.52 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              350.47 |             44.65 |         45.69 |         36    |          43.61 |        50.54 |           77.39 |             44.81 |             26    |         8.5  |             89.81 | long               |                3.81 |                  1.92 |                 1.73 |
|    nan | TLRY     | Tilray Brands, Inc.          | OTHER    |                0.5  |             27.53 |         29.17 |         20.86 |          25.88 |        32.82 |           44.87 |             31.96 |             28.26 |         8.91 |             78.44 | long               |                2.34 |                  0    |                 0.12 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     19 | AMS.SW   | AMS.SW                         | EUROPE   |                2.49 |             76.51 |         86.69 |         82.6  |          70.42 |        52.05 |           53.31 |             89.2  |              8.91 |         8.67 |             73.14 | short              |                5.44 |                  5.38 |               nan    |
|    335 | ITRG     | ITRG                           | US       |                0.49 |             57.45 |         55.58 |         57.66 |          57.24 |        66.28 |           59.71 |             63.47 |             85.96 |         8.25 |             68.32 | long               |                1.66 |                  4.78 |                 5.04 |
|     10 | AMC      | AMC                            | US       |                2.24 |             80.61 |         81.01 |         86.36 |          80.21 |        79.4  |           85.22 |             79.02 |            nan    |         9.52 |             65.07 | swing              |                4.42 |                  4.34 |                 4.04 |
|    553 | CYH      | Community Health Systems, Inc. | US       |                0.37 |             46.51 |         55.07 |         38.4  |          41.04 |        51.98 |           48.21 |             28.26 |             79.27 |         7.99 |             82.05 | short              |                6.92 |                  4.2  |                 3.8  |
|    284 | IHS      | IHS Holding Limited            | OTHER    |                2.49 |             59.68 |         63.45 |         56.25 |          57.77 |        61.59 |           57.81 |             78.22 |             63.08 |         2.05 |             72.86 | short              |               -0.53 |                  4.12 |                 4.18 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    454 | TEVA     | TEVA    | US       |               39.74 |             51.89 |         65.81 |         56.71 |          47.08 |        39.19 |           13.79 |             29.87 |             49.29 |         4.79 |             72.34 | short              |               -3.12 |                 -3.57 |                -3.66 |
|    663 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.42 |             37.37 |         27.23 |         32.06 |          42.68 |        74.05 |          nan    |            nan    |            100    |         5.15 |             60    | long               |               -0.24 |                 -3.07 |                -3.2  |
|    668 | PAH3.DE  | PAH3.DE | EUROPE   |                8.01 |             36.22 |         35.52 |         30.83 |          36.91 |        60.48 |          nan    |             27.4  |             95.05 |         5.11 |             70.3  | long               |               -9.13 |                 -3.05 |                -2.6  |
|    427 | CMPS     | CMPS    | US       |                1.66 |             53.42 |         47.14 |         59.7  |          59.98 |        44.08 |           45.29 |             51.94 |              6.86 |         7.9  |             69.27 | medium             |              -12.24 |                 -2.88 |                -3.14 |
|    307 | UMC      | UMC     | US       |               54.07 |             58.65 |         75.33 |         56.08 |          61.22 |        52.66 |           62.43 |             37.95 |             22.74 |         7.84 |             72.68 | short              |               -0.4  |                 -2.68 |                -2.98 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
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
- Excluded by hard/data filters: **291**
- Event watch (otherwise eligible): **2**
- Final eligible: **707**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 238
- price: 185
- market_cap: 158
- price_history: 17
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| VLO | 4 |  | 5 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| CMBT.BR | 6 |  | 4 |  | 2 | main,pullback |
| FRO | 7 |  | 2 |  | 2 | main,pullback |
| PSX | 9 |  | 3 |  | 2 | main,pullback |
| PBR-A | 33 | 3 | 28 | 5 | 1 | value,quality_value |
| PARR | 58 | 4 | 33 | 3 | 1 | value,quality_value |
| NVDA | 63 | 2 |  | 2 | 1 | value,quality_value |
| EMBC | 162 | 5 |  | 6 | 1 | value,quality_value |
| BION.SW | 190 | 1 | 129 | 1 | 1 | value,quality_value |
| NWL.MI | 244 | 10 | 54 | 9 | 1 | value,quality_value |
| INVA | 526 | 8 | 158 | 4 | 1 | value,quality_value |
| STNE | 603 | 6 | 268 | 7 | 1 | value,quality_value |
| HPE | 2 |  |  |  | 1 | main |

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
| 1 | INVA | value+pullback | 74.98 | 64.94 | 82.18 | 90.78 | 48.37 | 82.48 | 48.25 |
| 2 | NWL.MI | value+pullback | 70.60 | 73.61 | 76.40 | 75.50 | 43.60 | 68.68 | 60.92 |
| 3 | BION.SW | value+pullback | 70.11 | 73.97 | 48.25 | 84.64 | 58.14 | 86.75 | 63.04 |
| 4 | PARR | value+pullback | 69.35 | 68.48 | 63.98 | 80.43 | 70.11 | 68.66 | 72.47 |
| 5 | GSL | value+pullback | 67.81 | 70.19 | 67.13 | 77.16 | 30.39 | 76.81 | 61.16 |
| 6 | 0Q2N.IL | value+pullback | 67.61 | 68.76 | 75.43 | 61.12 |  | 69.76 | 64.08 |
| 7 | VOLV-B.ST | value+pullback | 66.90 | 74.59 | 71.38 | 55.24 | 63.24 | 60.34 | 55.29 |
| 8 | STNE | value+pullback | 66.17 | 72.17 | 59.25 | 85.87 | 32.25 | 68.01 | 43.50 |
| 9 | BCE | value+pullback | 63.23 | 59.29 | 66.86 | 80.43 | 53.49 | 56.59 | 43.69 |
| 10 | HMC | value+pullback | 63.16 | 57.07 | 53.10 | 75.65 | 81.42 | 66.36 | 68.73 |
| 11 | RCI | value+pullback | 62.33 | 64.38 | 54.56 | 89.13 | 42.70 | 58.69 | 44.35 |
| 12 | PBR-A | value+pullback | 62.14 | 75.89 | 42.76 | 61.58 | 79.56 | 57.47 | 74.41 |
| 13 | MAGN | value+pullback | 62.04 | 66.85 | 62.97 | 68.70 | 33.88 | 62.73 | 47.59 |
| 14 | IRS | value+pullback | 61.92 | 57.89 | 75.21 | 62.96 | 40.80 | 61.15 | 50.75 |
| 15 | WB | value+pullback | 61.27 | 71.47 | 59.98 | 73.42 | 17.62 | 60.28 | 38.48 |
| 16 | AVK | value+pullback | 60.77 | 55.75 | 69.54 | 62.10 |  | 61.74 | 50.17 |
| 17 | CNC | value+pullback | 60.00 | 71.24 | 56.87 | 50.47 | 64.27 | 52.06 | 59.94 |
| 18 | MFA | value+pullback | 59.69 | 57.74 | 65.79 | 77.07 | 26.00 | 58.81 | 41.28 |
| 19 | JD | value+pullback | 58.52 | 58.74 | 67.42 | 57.39 | 46.25 | 54.05 | 45.79 |
| 20 | UNIT | value+pullback | 58.19 | 80.01 | 50.67 | 65.22 | 28.97 | 44.19 | 39.96 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 9/10 | 8/10 | 0/10 | 72.7 | 7 / 3 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 72.7 | 13 / 12 |
| Top 50 | 50/50 | 48/50 | 49/50 | 47/50 | 0/50 | 72.7 | 25 / 25 |

Top-10 market-cap mix: micro_250m_1b=1, small_1_5b=2, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
