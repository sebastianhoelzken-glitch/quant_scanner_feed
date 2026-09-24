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

- **EUROPE:** 78.1/100
- **OTHER:** 73.0/100
- **US:** 80.4/100

## Main multi-horizon ranking

|   rank | symbol    | name                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:-------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC       | MPC                                  | US       |               95.27 |             83.64 |         76.41 |         86.11 |          85.91 |        81.36 |           85.49 |             90.3  |             64.99 |         4.38 |             73.14 | swing              |               -3.51 |                nan    |               nan    |
|      2 | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.95 |             83    |         78.57 |         83.48 |          84.82 |        82.53 |           96.26 |             77.58 |             61.72 |         3.73 |             73.14 | medium             |               -1.18 |                  1.37 |                 1.28 |
|      3 | HPE       | HPE                                  | US       |               72.28 |             81.56 |         89.78 |         83.68 |          79.44 |        69.74 |           73.8  |             81.51 |             43.99 |         7.02 |             72.34 | short              |                0.2  |                  0.35 |               nan    |
|      4 | MU        | MU                                   | US       |             1057.46 |             81.52 |         79.56 |         73    |          84.93 |        83.48 |           95.75 |             82.43 |             66.59 |         8.25 |             73.14 | medium             |                0.76 |                  2.52 |                 1.95 |
|      5 | DELL      | DELL                                 | US       |              305.37 |             80.76 |         83.34 |         82.25 |          79.27 |        66.54 |           73.42 |             86.72 |             29.43 |         7.87 |             72.23 | short              |               -2.86 |                 -0.29 |                -0.37 |
|      6 | VLO       | VLO                                  | US       |               94.53 |             80.54 |         75.34 |         83.23 |          83.03 |        78.05 |           86.83 |             81.54 |             54.89 |         3.68 |             69.68 | swing              |               -5.21 |                  0.65 |                 0.66 |
|      7 | FRO       | FRO                                  | US       |                9.25 |             80.53 |         80.89 |         80.16 |          81.94 |        78.7  |           92.13 |             81.15 |             51.84 |         5.61 |             73.14 | medium             |               -4.39 |                  0.23 |                 0.26 |
|      8 | PSX       | PSX                                  | US       |               89.83 |             79.41 |         77.96 |         83.37 |          80.87 |        75.51 |           80.96 |             86.24 |             52.9  |         3.87 |             73.14 | swing              |               -4.45 |                  0.87 |                 0.99 |
|      9 | AMC       | AMC                                  | US       |                2.24 |             79.15 |         79.51 |         84.19 |          78.78 |        78.05 |           86.01 |             78.77 |            nan    |         9.51 |             65.07 | swing              |                2.95 |                  4.05 |                 3.82 |
|     10 | REP.MC    | REP.MC                               | EUROPE   |               33.46 |             79.09 |         83.02 |         82.41 |          75.78 |        71    |           62.71 |             80.32 |             67.34 |         3.8  |             73.14 | short              |                4.44 |                  1.97 |                 1.57 |
|     11 | HSHP      | HSHP                                 | US       |                0.75 |             78.76 |         83.96 |         80.24 |          77.28 |        67.32 |           87.21 |            nan    |             23.08 |         4.85 |             62.84 | short              |               -4.05 |                nan    |               nan    |
|     12 | SHELL.AS  | SHELL.AS                             | EUROPE   |              240.83 |             78.38 |         83    |         76.98 |          74.96 |        79.77 |           93.44 |             82.58 |             63.03 |         2.47 |             73.14 | short              |                4.23 |                  2.86 |                 2.67 |
|     13 | SSABBH.HE | SSABBH.HE                            | EUROPE   |                9.32 |             77.46 |         61.47 |         73.98 |          80.94 |        83.16 |           73.52 |            nan    |             98.5  |         4.29 |             62.84 | long               |                2.28 |                nan    |               nan    |
|     14 | KIN.BR    | KIN.BR                               | EUROPE   |                1.35 |             77.4  |         80.29 |         80.32 |          74.52 |        65.46 |           90.48 |             64.3  |             17.75 |         3.82 |             73.14 | swing              |               -0.34 |                 -0.26 |                -0.2  |
|     15 | DHT       | DHT                                  | US       |                3    |             77.2  |         76.13 |         75.33 |          78.28 |        78.27 |           89.08 |             83.94 |             56.24 |         4.77 |             73.14 | medium             |               -4.87 |                  0.16 |                 0.01 |
|     16 | OKTA      | OKTA                                 | US       |               31.36 |             76.73 |         89.82 |         82.58 |          70.89 |        57.25 |           69.83 |             68.88 |             11.96 |         7.85 |             72.11 | short              |               -1.79 |                  0.6  |                 0.67 |
|     17 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |             76.39 |         83.05 |         77.22 |          72.03 |        75.55 |           67.93 |             79.86 |             80.67 |         3.74 |             84.67 | short              |                1.86 |                  0.58 |                 0.24 |
|     18 | OMV.VI    | OMV.VI                               | EUROPE   |               23.45 |             76.33 |         77.74 |         80.22 |          74.92 |        71.14 |           65.65 |             84.92 |             64.99 |         1.79 |             72.34 | swing              |                5.11 |                  1.15 |                 0.64 |
|     19 | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.9  |             75.65 |         77.3  |         74.04 |          75.04 |        76.27 |           96.57 |             66.73 |             53.72 |         2.18 |             73.14 | short              |               -0.08 |                  1.79 |                 1.53 |
|     20 | NAT       | NAT                                  | US       |                1.41 |             75.53 |         78.88 |         75.07 |          75.99 |        71.07 |           88.66 |             69.5  |             34.39 |         4.96 |             73.14 | short              |               -5.03 |                 -0.51 |                -0.31 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  85.14 |                    74.23 |                 71.74 |              77.58 |                76.02 |                   23.98 |           72.49 |             26    |       0.081 |         nan |       nan |        3.83 |         5.03 |          4.38 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            2 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  79.16 |                    74.13 |                 74.39 |              76.75 |                65.35 |                   34.65 |           67.93 |             79.86 |       0.14  |         nan |       nan |        1.8  |         4.78 |          4.8  |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                                   | US       |              100.09 |                  60.32 |                    71.1  |                 74.67 |              67.15 |                82.84 |                   17.16 |           87.52 |             88.1  |     nan     |         nan |       nan |      nan    |         9.06 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  77.15 |                    70.87 |                 70.45 |              72.5  |                58.18 |                   41.82 |           69.17 |             64.76 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | BBWI     | Bath & Body Works, Inc.              | US       |                3    |                  87.84 |                    70.81 |                 65    |              74.1  |                43.88 |                   56.12 |           57.83 |             29.57 |       0.223 |         nan |       nan |        5.61 |         6.11 |          4.5  |        0.7  |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHEL     | SHEL                                 | US       |              237.78 |                  65.84 |                    70.62 |                 72.03 |              69.32 |                77.19 |                   22.81 |           75.18 |             80.2  |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              240.83 |                  57.36 |                    70.58 |                 74.79 |              65.44 |                88.2  |                   11.8  |           93.44 |             82.58 |     nan     |         nan |       nan |      nan    |         9.62 |         10.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.13 |                  63    |                    69.86 |                 72.49 |              66.75 |                73.49 |                   26.51 |           83.51 |             81.61 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    69.85 |                 71.39 |              65.56 |                75.77 |                   24.23 |           81.99 |             80.9  |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3    |                  57.54 |                    69.14 |                 73.04 |              64.56 |                81.89 |                   18.11 |           89.08 |             83.94 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.95 |                  55.63 |                    69.07 |                 73.56 |              63.2  |                85.5  |                   14.5  |           96.26 |             77.58 |     nan     |         nan |       nan |      nan    |         9.42 |          6.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.25 |                  56.39 |                    68.5  |                 72.71 |              63.27 |                80.86 |                   19.14 |           92.13 |             81.15 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.4  |                  63.08 |                    67.84 |                 69.4  |              64.39 |                77.33 |                   22.67 |           87.32 |             50.54 |     nan     |         nan |       nan |      nan    |         8.57 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.9  |                  55.42 |                    67.82 |                 71.88 |              61.92 |                85.24 |                   14.76 |           96.57 |             66.73 |     nan     |         nan |       nan |      nan    |        10.92 |         14.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              177.16 |                  63.61 |                    67.55 |                 68.6  |              66.82 |                73.69 |                   26.31 |           69.14 |             77.6  |     nan     |         nan |       nan |      nan    |         9.06 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.91 |                  84.49 |                    67.51 |                 61.37 |              73.47 |                56.02 |                   43.98 |           44.48 |             25.52 |       0.632 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | RCI      | Rogers Communications Inc.           | OTHER    |               15.7  |                  75.98 |                    66.85 |                 63.41 |              67.63 |                51.07 |                   48.93 |           63.87 |             37.31 |       0.301 |         nan |       nan |        7.13 |         9.71 |          4.08 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1480.26 |                  60.81 |                    66.75 |                 66.66 |              61.41 |                76.08 |                   23.92 |           87.89 |             39.39 |       0.018 |         nan |       nan |       33.1  |        18.32 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                  | US       |              109.11 |                  61.95 |                    66.01 |                 67.4  |              63.33 |                72.73 |                   27.27 |           80.59 |             56.41 |     nan     |         nan |       nan |      nan    |         9.31 |         13.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                | EUROPE   |               20.47 |                  62.44 |                    65.97 |                 66.86 |              64.59 |                74.06 |                   25.94 |           72.81 |             63.01 |     nan     |         nan |       nan |      nan    |         8.85 |         11.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              240.83 |                  57.36 |                    70.58 |                 74.79 |              65.44 |                88.2  |                   11.8  |           93.44 |             82.58 |     nan     |         nan |       nan |      nan    |         9.62 |         10.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.09 |                  60.32 |                    71.1  |                 74.67 |              67.15 |                82.84 |                   17.16 |           87.52 |             88.1  |     nan     |         nan |       nan |      nan    |         9.06 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              114.95 |                  79.16 |                    74.13 |                 74.39 |              76.75 |                65.35 |                   34.65 |           67.93 |             79.86 |       0.14  |         nan |       nan |        1.8  |         4.78 |          4.8  |        5.42 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.95 |                  55.63 |                    69.07 |                 73.56 |              63.2  |                85.5  |                   14.5  |           96.26 |             77.58 |     nan     |         nan |       nan |      nan    |         9.42 |          6.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3    |                  57.54 |                    69.14 |                 73.04 |              64.56 |                81.89 |                   18.11 |           89.08 |             83.94 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.25 |                  56.39 |                    68.5  |                 72.71 |              63.27 |                80.86 |                   19.14 |           92.13 |             81.15 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.13 |                  63    |                    69.86 |                 72.49 |              66.75 |                73.49 |                   26.51 |           83.51 |             81.61 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              237.78 |                  65.84 |                    70.62 |                 72.03 |              69.32 |                77.19 |                   22.81 |           75.18 |             80.2  |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.9  |                  55.42 |                    67.82 |                 71.88 |              61.92 |                85.24 |                   14.76 |           96.57 |             66.73 |     nan     |         nan |       nan |      nan    |        10.92 |         14.84 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  85.14 |                    74.23 |                 71.74 |              77.58 |                76.02 |                   23.98 |           72.49 |             26    |       0.081 |         nan |       nan |        3.83 |         5.03 |          4.38 |        0.87 |                 nan |              nan |                  10 |                  0.53 |
|            5 | NVDA     | NVIDIA Corporation                   | US       |             4756.66 |                  60.87 |                    69.85 |                 71.39 |              65.56 |                75.77 |                   24.23 |           81.99 |             80.9  |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|            3 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  77.15 |                    70.87 |                 70.45 |              72.5  |                58.18 |                   41.82 |           69.17 |             64.76 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | MU       | MU                                   | US       |             1057.46 |                  49.34 |                    64.65 |                 70.18 |              57.78 |                77.83 |                   22.17 |           95.75 |             82.43 |     nan     |         nan |       nan |      nan    |         6.74 |         24.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MPC      | MPC                                  | US       |               95.27 |                  50.16 |                    65.14 |                 69.93 |              60.07 |                82.93 |                   17.07 |           85.49 |             90.3  |     nan     |         nan |       nan |      nan    |         8.24 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP                                 | US       |                5.43 |                  50.63 |                    65.26 |                 69.66 |              60.56 |                86.1  |                   13.9  |           84.16 |             86.17 |     nan     |         nan |       nan |      nan    |        12.94 |         76.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.4  |                  63.08 |                    67.84 |                 69.4  |              64.39 |                77.33 |                   22.67 |           87.32 |             50.54 |     nan     |         nan |       nan |      nan    |         8.57 |          7.57 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.52 |                  55.47 |                    65.53 |                 68.79 |              61.28 |                78.82 |                   21.18 |           85.07 |             71.6  |     nan     |         nan |       nan |      nan    |        10.29 |         22.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                  | US       |               94.53 |                  50.02 |                    64.23 |                 68.77 |              58.96 |                82.17 |                   17.83 |           86.83 |             81.54 |     nan     |         nan |       nan |      nan    |         9.88 |         15.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.36 |                  54.52 |                    65.12 |                 68.72 |              59.06 |                80.48 |                   19.52 |           96.54 |             53.22 |     nan     |         nan |       nan |      nan    |        11.73 |         11.99 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              177.16 |                  63.61 |                    67.55 |                 68.6  |              66.82 |                73.69 |                   26.31 |           69.14 |             77.6  |     nan     |         nan |       nan |      nan    |         9.06 |         11.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.95 |                     0.05 |    -0.05 |      0.1  |                  85.2  |                        85.41 |         78.57 |         83.48 |          84.82 |        82.53 |           96.26 |             77.58 |         3.73 |
|               2 | MPC       | MPC       | US       |               95.27 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        84.15 |         76.41 |         86.11 |          85.91 |        81.36 |           85.49 |             90.3  |         4.38 |
|               3 | FRO       | FRO       | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        82.18 |         80.89 |         80.16 |          81.94 |        78.7  |           92.13 |             81.15 |         5.61 |
|               4 | PSX       | PSX       | US       |               89.83 |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        81.89 |         77.96 |         83.37 |          80.87 |        75.51 |           80.96 |             86.24 |         3.87 |
|               5 | VLO       | VLO       | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        81.51 |         75.34 |         83.23 |          83.03 |        78.05 |           86.83 |             81.54 |         3.68 |
|               6 | DELL      | DELL      | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        80.05 |         83.34 |         82.25 |          79.27 |        66.54 |           73.42 |             86.72 |         7.87 |
|               7 | DHT       | DHT       | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        79.6  |         76.13 |         75.33 |          78.28 |        78.27 |           89.08 |             83.94 |         4.77 |
|               8 | BP        | BP        | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        79.45 |         74.94 |         71.45 |          71.08 |        76.22 |           87.52 |             88.1  |         4.58 |
|               9 | NAT       | NAT       | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        78.26 |         78.88 |         75.07 |          75.99 |        71.07 |           88.66 |             69.5  |         4.96 |
|              10 | SMTC      | SMTC      | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        77.56 |         84.52 |         72.03 |          73.62 |        61.28 |           75.82 |             84.93 |         8.49 |
|              11 | EQNR      | EQNR      | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        76.68 |         70.01 |         74.9  |          72.9  |        72.2  |           76.39 |             84.77 |         5.73 |
|              12 | PAGP      | PAGP      | US       |                5.43 |                     0.06 |    -0.04 |     -0.02 |                  76.61 |                        76.6  |         60.43 |         70.71 |          73.91 |        72.8  |           84.16 |             86.17 |         1.77 |
|              13 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.9  |                     0.02 |    -0.02 |      0.07 |                  52.01 |                        75.77 |         77.3  |         74.04 |          75.04 |        76.27 |           96.57 |             66.73 |         2.18 |
|              14 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.25 |                     0.03 |    -0.02 |      0.4  |                  59.45 |                        75.54 |         82.93 |         78.13 |          68.48 |        68    |           83.68 |             56.11 |         5.38 |
|              15 | MT.AS     | MT.AS     | EUROPE   |               47.19 |                     0.07 |    -0.04 |     -0.02 |                  73.06 |                        75.18 |         57.78 |         74.69 |          78.05 |        74.75 |           72.55 |             82.47 |         5.08 |
|              16 | C5H.IR    | C5H.IR    | EUROPE   |                1.66 |                     0.06 |    -0.01 |      0.05 |                  73.59 |                        75.04 |         72.81 |         67.16 |          71.59 |        75.09 |           98    |             53.3  |         2.7  |
|              17 | DAR       | DAR       | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        74.67 |         54.49 |         67.15 |          76.17 |        80.96 |           91.04 |             87    |         4.77 |
|              18 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.05 |                     0.05 |    -0.04 |      0.16 |                  79.29 |                        74.55 |         78.06 |         65.99 |          58.93 |        53.71 |           69.84 |             64.41 |         4.67 |
|              19 | APA       | APA       | US       |               13.37 |                     0.08 |    -0.02 |      0.06 |                  63.54 |                        73.97 |         72.09 |         73.86 |          72.97 |        74.22 |           75.83 |             82.31 |         6.09 |
|              20 | SHEL      | SHEL      | US       |              237.78 |                     0.04 |    -0    |      0.03 |                  59.82 |                        73.93 |         75.78 |         72.45 |          69.4  |        73.44 |           75.18 |             80.2  |         3.04 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              350.47 |             33.31 |         43.01 |         32.02 |          32.84 |        33.77 |           35.66 |             41.88 |             25.98 |          8.5 |             89.81 | short              |               -7.54 |                 -0.35 |                 0.03 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     29 | AMS.SW   | AMS.SW                         | EUROPE   |                2.32 |             74.31 |         85.03 |         78.3  |          70.32 |        53.28 |           55.46 |             89.85 |             10.38 |         8.7  |             73.14 | short              |                3.24 |                  4.94 |               nan    |
|    505 | CYH      | Community Health Systems, Inc. | US       |                0.37 |             48.19 |         56.27 |         40.06 |          42.06 |        54.32 |           42.28 |             27.04 |             92.54 |         8.21 |             82.05 | short              |                8.6  |                  4.54 |                 4.06 |
|    352 | ITRG     | ITRG                           | US       |                0.49 |             55.24 |         54.35 |         55.3  |          55.17 |        63.96 |           61.42 |             61.34 |             80.01 |         8.24 |             68.32 | long               |               -0.56 |                  4.34 |                 4.71 |
|      9 | AMC      | AMC                            | US       |                2.24 |             79.15 |         79.51 |         84.19 |          78.78 |        78.05 |           86.01 |             78.77 |            nan    |         9.51 |             65.07 | swing              |                2.95 |                  4.05 |                 3.82 |
|     96 | EMBC     | Embecta Corp.                  | US       |                0.28 |             67.85 |         75.06 |         65.6  |          56.8  |        70.11 |           69.17 |             64.76 |             90.87 |         7.88 |             84.47 | short              |                5.68 |                  3.95 |                 3.71 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    482 | TEVA     | TEVA    | US       |               39.74 |             49.65 |         64.7  |         54.12 |          45.18 |        37.23 |           17.12 |             25.44 |             42.77 |         4.82 |             72.34 | short              |               -5.36 |                 -4.02 |                -4    |
|    685 | PAH3.DE  | PAH3.DE | EUROPE   |                7.86 |             32.55 |         29    |         28.93 |          36.09 |        59.9  |          nan    |             24.07 |             94.04 |         5.21 |             70.3  | long               |              -12.8  |                 -3.79 |                -3.15 |
|    481 | CNC      | CNC     | US       |               26.79 |             49.66 |         42.52 |         54.6  |          57.61 |        44.72 |           12.3  |             70.7  |             56.86 |         6    |             71.66 | medium             |               -9.56 |                 -3.53 |                -3.03 |
|    436 | CMPS     | CMPS    | US       |                1.66 |             51.81 |         46.11 |         57.5  |          58.12 |        42.26 |           45.21 |             49.54 |              5.13 |         7.91 |             69.27 | medium             |              -13.85 |                 -3.2  |                -3.38 |
|    311 | UMC      | UMC     | US       |               54.07 |             56.73 |         73.82 |         53.81 |          59.65 |        51.02 |           64.31 |             35.97 |             19.08 |         7.86 |             72.68 | short              |               -2.32 |                 -3.06 |                -3.27 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_63d_rank` vs `sector_score`: r=0.92
- `relative_63d_rank` vs `sector_score`: r=0.91
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
- Excluded by hard/data filters: **289**
- Event watch (otherwise eligible): **1**
- Final eligible: **710**
- Eligible change vs previous stored run: **+1**

Top exclusion categories:
- liquidity: 236
- price: 186
- market_cap: 157
- price_history: 15
- data_confidence: 9
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 2 |  | 2 | main,pullback |
| CMBT.BR | 2 |  | 1 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| VLO | 6 |  | 5 |  | 2 | main,pullback |
| FRO | 7 |  | 3 |  | 2 | main,pullback |
| PSX | 8 |  | 4 |  | 2 | main,pullback |
| PBR-A | 17 | 2 | 23 | 1 | 1 | value,quality_value |
| NVDA | 37 | 5 |  | 3 | 1 | value,quality_value |
| EMBC | 96 | 3 |  | 4 | 1 | value,quality_value |
| GSL | 220 | 1 | 177 | 2 | 1 | value,quality_value |
| AVGO | 291 | 8 |  | 5 | 1 | value,quality_value |
| NOVO-B.CO | 586 | 9 |  | 10 | 1 | value,quality_value |
| BBWI | 598 | 4 |  | 9 | 1 | value,quality_value |
| HPE | 3 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **4** (HPE, MU, AMC, REP.MC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SMTC)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | GSL | value+pullback | 71.00 | 85.14 | 67.13 | 72.49 | 26.00 | 76.02 | 60.67 |
| 2 | PBR-A | value+pullback | 65.69 | 79.16 | 42.76 | 67.93 | 79.86 | 65.35 | 76.39 |
| 3 | ETG | value+pullback | 65.33 | 55.73 | 59.98 | 64.06 | 88.23 | 75.90 | 61.92 |
| 4 | ATNI | value+pullback | 63.89 | 77.71 | 71.90 | 42.39 | 51.18 | 55.65 | 52.04 |
| 5 | VOLV-B.ST | value+pullback | 63.38 | 71.64 | 71.72 | 49.68 | 62.68 | 51.16 | 53.37 |
| 6 | SAP.DE | value+pullback | 61.12 | 70.54 | 73.86 | 42.37 | 52.19 | 49.60 | 54.15 |
| 7 | CMBT.BR | pullback | 60.60 | 55.63 | 85.20 | 96.26 | 77.58 | 85.50 | 83.00 |
| 8 | STNE | value+pullback | 60.59 | 84.49 | 59.25 | 44.48 | 25.52 | 56.02 | 37.47 |
| 9 | AVK | value+pullback | 60.32 | 57.10 | 69.54 | 55.14 |  | 62.65 | 49.29 |
| 10 | PBR | value+pullback | 60.25 | 59.51 | 51.49 | 67.93 | 68.48 | 62.41 | 71.16 |
| 11 | RCI | value+pullback | 59.96 | 75.98 | 54.56 | 63.87 | 37.31 | 51.07 | 41.21 |
| 12 | PAGP | pullback | 57.61 | 50.63 | 76.61 | 84.16 | 86.17 | 86.10 | 71.75 |
| 13 | BP | pullback | 57.27 | 60.32 | 75.07 | 87.52 | 88.10 | 82.84 | 73.19 |
| 14 | BCE | value+pullback | 56.87 | 66.69 | 66.86 | 39.86 | 50.74 | 45.48 | 38.16 |
| 15 | DHT | pullback | 56.69 | 57.54 | 74.22 | 89.08 | 83.94 | 81.89 | 77.20 |
| 16 | FRO | pullback | 56.66 | 56.39 | 74.20 | 92.13 | 81.15 | 80.86 | 80.53 |
| 17 | MPC | pullback | 55.86 | 50.16 | 69.68 | 85.49 | 90.30 | 82.93 | 83.64 |
| 18 | DAR | pullback | 55.53 | 53.16 | 65.59 | 91.04 | 87.00 | 83.87 | 71.66 |
| 19 | PSX | pullback | 55.30 | 51.48 | 73.84 | 80.96 | 86.24 | 80.37 | 79.41 |
| 20 | VLO | pullback | 54.77 | 50.02 | 68.65 | 86.83 | 81.54 | 82.17 | 80.54 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 73.1 | 13 / 12 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 72.7 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
