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

- **EUROPE:** 77.7/100
- **OTHER:** 71.5/100
- **US:** 80.7/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC       | MPC       | US       |               95.27 |             83.26 |         76.39 |         85.97 |          85.63 |        80.88 |           85.01 |             90.34 |             63.94 |         4.37 |             73.14 | swing              |               -3.89 |                nan    |               nan    |
|      2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.93 |             82.74 |         77.7  |         82.94 |          84.72 |        82.53 |           96.57 |             77.55 |             61.36 |         3.72 |             73.14 | medium             |               -1.45 |                  1.31 |                 1.24 |
|      3 | MU        | MU        | US       |             1057.46 |             81.37 |         79.61 |         73.05 |          84.84 |        83.12 |           95.45 |             82.53 |             65.55 |         8.25 |             73.14 | medium             |                0.6  |                  2.49 |                 1.93 |
|      4 | HPE       | HPE       | US       |               72.28 |             81.36 |         89.71 |         83.59 |          79.13 |        69.15 |           72.95 |             81.88 |             43    |         7.01 |             72.34 | short              |                0    |                  0.31 |               nan    |
|      5 | DELL      | DELL      | US       |              305.37 |             80.59 |         83.34 |         82.13 |          79.04 |        66.1  |           72.81 |             86.89 |             28.67 |         7.84 |             72.23 | short              |               -3.03 |                 -0.33 |                -0.4  |
|      6 | FRO       | FRO       | US       |                9.25 |             80.53 |         81.01 |         80.06 |          81.78 |        78.42 |           92.04 |             81.29 |             50.91 |         5.6  |             73.14 | medium             |               -4.38 |                  0.23 |                 0.26 |
|      7 | VLO       | VLO       | US       |               94.53 |             80.24 |         75.39 |         83.16 |          82.82 |        77.66 |           86.43 |             81.76 |             53.95 |         3.67 |             69.68 | swing              |               -5.5  |                  0.59 |                 0.62 |
|      8 | AMC       | AMC       | US       |                2.24 |             79.28 |         79.6  |         84.19 |          78.97 |        78.41 |           86.65 |             78.94 |            nan    |         9.51 |             65.07 | swing              |                3.09 |                  4.08 |                 3.84 |
|      9 | PSX       | PSX       | US       |               89.83 |             79.26 |         77.92 |         83.21 |          80.6  |        75.02 |           80.3  |             86.39 |             52    |         3.86 |             73.14 | swing              |               -4.6  |                  0.84 |                 0.97 |
|     10 | REP.MC    | REP.MC    | EUROPE   |               33.62 |             78.98 |         83    |         82.35 |          75.61 |        70.66 |           62.28 |             80.48 |             66.63 |         3.8  |             73.14 | short              |                4.33 |                  1.95 |                 1.55 |
|     11 | HSHP      | HSHP      | US       |                0.75 |             78.49 |         83.86 |         79.99 |          77    |        66.97 |           86.82 |            nan    |             22.52 |         4.84 |             62.84 | short              |               -4.31 |                nan    |               nan    |
|     12 | SHELL.AS  | SHELL.AS  | EUROPE   |              241.03 |             78.48 |         83.18 |         77.05 |          75.11 |        79.91 |           93.8  |             82.83 |             62.85 |         2.45 |             73.14 | short              |                4.33 |                  2.88 |                 2.68 |
|     13 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.41 |             77.81 |         63.2  |         74.56 |          81.06 |        83.26 |           73.63 |            nan    |             98.52 |         4.3  |             62.84 | long               |                2.63 |                nan    |               nan    |
|     14 | PBR-A     | PBR-A     | US       |              114.95 |             77.41 |         84.13 |         76.24 |          72.19 |        78.58 |           74.69 |             70.83 |             87.03 |         4.55 |             69.89 | short              |                2.89 |                  0.78 |                 0.39 |
|     15 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             77.37 |         80.5  |         80.17 |          74.56 |        65.51 |           90.63 |             64.45 |             17.62 |         3.81 |             73.14 | short              |               -0.38 |                 -0.26 |                -0.2  |
|     16 | DHT       | DHT       | US       |                3    |             77.04 |         76.11 |         75.3  |          78.17 |        77.97 |           88.87 |             84.07 |             55.34 |         4.77 |             73.14 | medium             |               -5.03 |                  0.13 |                -0.02 |
|     17 | OKTA      | OKTA      | US       |               31.36 |             76.6  |         89.77 |         82.51 |          70.68 |        56.88 |           69.01 |             69.01 |             11.76 |         7.83 |             72.11 | short              |               -1.93 |                  0.57 |                 0.65 |
|     18 | OMV.VI    | OMV.VI    | EUROPE   |               23.45 |             76.34 |         77.81 |         80.12 |          74.86 |        71.01 |           65.6  |             85.08 |             64.51 |         1.79 |             72.34 | swing              |                5.12 |                  1.15 |                 0.64 |
|     19 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.87 |             75.76 |         77.37 |         74.1  |          75.14 |        76.38 |           96.75 |             66.83 |             53.73 |         2.18 |             73.14 | short              |                0.03 |                  1.81 |                 1.55 |
|     20 | NAT       | NAT       | US       |                1.41 |             75.39 |         78.95 |         74.95 |          75.83 |        70.77 |           88.43 |             69.68 |             33.62 |         4.96 |             73.14 | short              |               -5.17 |                 -0.54 |                -0.34 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                 | EUROPE   |               58.38 |                  82.31 |                    71.52 |                 67.76 |              75.46 |                55.2  |                   44.8  |           52.22 |             62.57 |       0.037 |         nan |       nan |       15.65 |        13    |         18.38 |        0.97 |                 nan |              nan |                  12 |                  0.63 |
|            2 | EMBC      | Embecta Corp.                   | US       |                0.28 |                  77.15 |                    70.85 |                 70.43 |              72.48 |                58.19 |                   41.81 |           69.17 |             64.62 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PBR-A     | PBR-A                           | US       |              114.95 |                  69.76 |                    70.83 |                 71.33 |              70.08 |                70.91 |                   29.09 |           74.69 |             70.83 |     nan     |         nan |       nan |      nan    |         4.78 |          4.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                        | EUROPE   |              241.03 |                  57.36 |                    70.71 |                 74.96 |              65.51 |                88.5  |                   11.5  |           93.8  |             82.83 |     nan     |         nan |       nan |      nan    |         9.63 |         10.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                              | US       |              100.09 |                  58.96 |                    70.19 |                 73.88 |              66.14 |                82.6  |                   17.4  |           86.92 |             88.21 |     nan     |         nan |       nan |      nan    |         9.06 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA      | NVIDIA Corporation              | US       |             4756.66 |                  60.87 |                    69.9  |                 71.47 |              65.62 |                75.89 |                   24.11 |           81.99 |             81.3  |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SM        | SM                              | US       |                7.13 |                  62.93 |                    69.74 |                 72.36 |              66.7  |                73.38 |                   26.62 |           83.04 |             81.78 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                            | US       |              237.78 |                  64.26 |                    69.6  |                 71.17 |              68.16 |                76.96 |                   23.04 |           74.6  |             80.4  |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                         | EUROPE   |                4.93 |                  55.36 |                    68.99 |                 73.54 |              63.04 |                85.67 |                   14.33 |           96.57 |             77.55 |     nan     |         nan |       nan |      nan    |         9.38 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                             | US       |                3    |                  56.67 |                    68.61 |                 72.6  |              63.94 |                81.84 |                   18.16 |           88.87 |             84.07 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                             | US       |                9.25 |                  56.39 |                    68.51 |                 72.71 |              63.29 |                80.88 |                   19.12 |           92.04 |             81.29 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                         | EUROPE   |               18.87 |                  55.97 |                    68.2  |                 72.21 |              62.35 |                85.38 |                   14.62 |           96.75 |             66.83 |     nan     |         nan |       nan |      nan    |        10.91 |         14.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | STNE      | StoneCo Ltd.                    | OTHER    |                1.91 |                  85.75 |                    68.19 |                 61.97 |              74.29 |                55.55 |                   44.45 |           44.86 |             25.57 |       0.632 |         nan |       nan |        1.61 |         4.13 |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR    | AGS.BR                          | EUROPE   |               15.36 |                  63.5  |                    68.09 |                 69.6  |              64.69 |                77.34 |                   22.66 |           87.43 |             50.47 |     nan     |         nan |       nan |      nan    |         8.56 |          7.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                          | EUROPE   |              177.78 |                  63.61 |                    67.55 |                 68.6  |              66.87 |                73.73 |                   26.27 |           68.88 |             77.99 |     nan     |         nan |       nan |      nan    |         9.09 |         11.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | AVGO      | Broadcom Inc.                   | US       |             1480.26 |                  60.81 |                    66.72 |                 66.6  |              61.38 |                76.06 |                   23.94 |           87.89 |             39.05 |       0.018 |         nan |       nan |       33.1  |        18.32 |         45.34 |        0.36 |                 nan |              nan |                  12 |                  0.63 |
|          nan | NN.AS     | NN.AS                           | EUROPE   |               20.45 |                  62.23 |                    66.02 |                 67    |              64.51 |                74.41 |                   25.59 |           73.48 |             63.09 |     nan     |         nan |       nan |      nan    |         8.85 |         11.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | ATNI      | ATN International, Inc.         | US       |                0.39 |                  80.24 |                    65.85 |                 62.05 |              72.95 |                55.91 |                   44.09 |           39.57 |             51.13 |       0.269 |         nan |       nan |        5.28 |        26.93 |          2.88 |        2.72 |                 nan |              nan |                  12 |                  0.63 |
|          nan | ASRNL.AS  | ASRNL.AS                        | EUROPE   |               14.54 |                  57.51 |                    65.72 |                 68.18 |              62.19 |                79.66 |                   20.34 |           82.73 |             64.48 |     nan     |         nan |       nan |      nan    |        11.11 |         14.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | HOS       | Hornbeck Offshore Services, Inc | US       |                2.39 |                  72.11 |                    65.66 |                 64.78 |              70.85 |                67.59 |                   32.41 |           48.16 |             67.64 |     nan     |         nan |       nan |        1.99 |        15.46 |         19.88 |      nan    |                 nan |              nan |                   7 |                  0.37 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS           | EUROPE   |              241.03 |                  57.36 |                    70.71 |                 74.96 |              65.51 |                88.5  |                   11.5  |           93.8  |             82.83 |     nan     |         nan |       nan |      nan    |         9.63 |         10.72 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                 | US       |              100.09 |                  58.96 |                    70.19 |                 73.88 |              66.14 |                82.6  |                   17.4  |           86.92 |             88.21 |     nan     |         nan |       nan |      nan    |         9.06 |         20.6  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR            | EUROPE   |                4.93 |                  55.36 |                    68.99 |                 73.54 |              63.04 |                85.67 |                   14.33 |           96.57 |             77.55 |     nan     |         nan |       nan |      nan    |         9.38 |          6.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                | US       |                9.25 |                  56.39 |                    68.51 |                 72.71 |              63.29 |                80.88 |                   19.12 |           92.04 |             81.29 |     nan     |         nan |       nan |      nan    |        10.39 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                | US       |                3    |                  56.67 |                    68.61 |                 72.6  |              63.94 |                81.84 |                   18.16 |           88.87 |             84.07 |     nan     |         nan |       nan |      nan    |         9.92 |          7.29 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                 | US       |                7.13 |                  62.93 |                    69.74 |                 72.36 |              66.7  |                73.38 |                   26.62 |           83.04 |             81.78 |     nan     |         nan |       nan |      nan    |         4.3  |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR            | EUROPE   |               18.87 |                  55.97 |                    68.2  |                 72.21 |              62.35 |                85.38 |                   14.62 |           96.75 |             66.83 |     nan     |         nan |       nan |      nan    |        10.91 |         14.82 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation | US       |             4756.66 |                  60.87 |                    69.9  |                 71.47 |              65.62 |                75.89 |                   24.11 |           81.99 |             81.3  |       0.008 |         nan |       nan |       26.89 |        14.38 |         28.91 |        0.49 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PBR-A    | PBR-A              | US       |              114.95 |                  69.76 |                    70.83 |                 71.33 |              70.08 |                70.91 |                   29.09 |           74.69 |             70.83 |     nan     |         nan |       nan |      nan    |         4.78 |          4.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL               | US       |              237.78 |                  64.26 |                    69.6  |                 71.17 |              68.16 |                76.96 |                   23.04 |           74.6  |             80.4  |     nan     |         nan |       nan |      nan    |         9.21 |         10.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | EMBC     | Embecta Corp.      | US       |                0.28 |                  77.15 |                    70.85 |                 70.43 |              72.48 |                58.19 |                   41.81 |           69.17 |             64.62 |       0.437 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | MPC      | MPC                | US       |               95.27 |                  50.18 |                    65.04 |                 69.79 |              60.05 |                82.71 |                   17.29 |           85.01 |             90.34 |     nan     |         nan |       nan |      nan    |         8.24 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                 | US       |             1057.46 |                  48.55 |                    64.14 |                 69.75 |              57.2  |                77.73 |                   22.27 |           95.45 |             82.53 |     nan     |         nan |       nan |      nan    |         6.74 |         24.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR             | EUROPE   |               15.36 |                  63.5  |                    68.09 |                 69.6  |              64.69 |                77.34 |                   22.66 |           87.43 |             50.47 |     nan     |         nan |       nan |      nan    |         8.56 |          7.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAGP     | PAGP               | US       |                5.43 |                  50.63 |                    65.12 |                 69.46 |              60.54 |                85.78 |                   14.22 |           83.37 |             86.42 |     nan     |         nan |       nan |      nan    |        12.94 |         76.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR             | EUROPE   |               24.26 |                  54.48 |                    65.18 |                 68.82 |              59.08 |                80.65 |                   19.35 |           96.8  |             53.36 |     nan     |         nan |       nan |      nan    |        11.68 |         11.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                | US       |               94.53 |                  50.04 |                    64.18 |                 68.7  |              58.97 |                82.05 |                   17.95 |           86.43 |             81.76 |     nan     |         nan |       nan |      nan    |         9.88 |         15.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA             | EUROPE   |              177.78 |                  63.61 |                    67.55 |                 68.6  |              66.87 |                73.73 |                   26.27 |           68.88 |             77.99 |     nan     |         nan |       nan |      nan    |         9.09 |         11.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                | US       |               14.52 |                  54.98 |                    65.1  |                 68.36 |              60.9  |                78.52 |                   21.48 |           84.3  |             71.8  |     nan     |         nan |       nan |      nan    |        10.29 |         22.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX                | US       |               89.83 |                  51.54 |                    64.26 |                 68.24 |              60.16 |                80.09 |                   19.91 |           80.3  |             86.39 |     nan     |         nan |       nan |      nan    |        10.3  |         14.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.93 |                     0.06 |    -0.06 |      0.09 |                  85.67 |                        85.27 |         77.7  |         82.94 |          84.72 |        82.53 |           96.57 |             77.55 |         3.72 |
|               2 | MPC       | MPC       | US       |               95.27 |                     0.09 |    -0.06 |      0.09 |                  69.68 |                        83.99 |         76.39 |         85.97 |          85.63 |        80.88 |           85.01 |             90.34 |         4.37 |
|               3 | FRO       | FRO       | US       |                9.25 |                     0.08 |    -0.05 |      0.17 |                  74.2  |                        82.23 |         81.01 |         80.06 |          81.78 |        78.42 |           92.04 |             81.29 |         5.6  |
|               4 | PSX       | PSX       | US       |               89.83 |                     0.06 |    -0.03 |      0.08 |                  73.84 |                        81.7  |         77.92 |         83.21 |          80.6  |        75.02 |           80.3  |             86.39 |         3.86 |
|               5 | VLO       | VLO       | US       |               94.53 |                     0.09 |    -0.07 |      0.1  |                  68.65 |                        81.43 |         75.39 |         83.16 |          82.82 |        77.66 |           86.43 |             81.76 |         3.67 |
|               6 | DELL      | DELL      | US       |              305.37 |                     0.07 |    -0.02 |      0.22 |                  71.27 |                        79.96 |         83.34 |         82.13 |          79.04 |        66.1  |           72.81 |             86.89 |         7.84 |
|               7 | DHT       | DHT       | US       |                3    |                     0.09 |    -0.08 |      0.11 |                  74.22 |                        79.57 |         76.11 |         75.3  |          78.17 |        77.97 |           88.87 |             84.07 |         4.77 |
|               8 | BP        | BP        | US       |              100.09 |                     0.05 |    -0.02 |      0.04 |                  75.07 |                        79.29 |         74.83 |         71.28 |          70.84 |        75.71 |           86.92 |             88.21 |         4.56 |
|               9 | NAT       | NAT       | US       |                1.41 |                     0.08 |    -0.05 |      0.15 |                  71.11 |                        78.28 |         78.95 |         74.95 |          75.83 |        70.77 |           88.43 |             69.68 |         4.96 |
|              10 | SMTC      | SMTC      | US       |               13.8  |                     0.08 |     0.01 |      0.33 |                  49.35 |                        77.53 |         84.58 |         72.08 |          73.55 |        61.08 |           75.21 |             85.3  |         8.48 |
|              11 | EQNR      | EQNR      | US       |               88.83 |                     0.06 |    -0.03 |      0.04 |                  74.9  |                        76.45 |         69.97 |         74.71 |          72.64 |        71.66 |           75.58 |             84.94 |         5.72 |
|              12 | PAGP      | PAGP      | US       |                5.43 |                     0.06 |    -0.04 |     -0.02 |                  76.61 |                        76.39 |         60.24 |         70.53 |          73.62 |        72.25 |           83.37 |             86.42 |         1.77 |
|              13 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.23 |                     0.03 |    -0.03 |      0.39 |                  63.12 |                        76.26 |         83.04 |         77.87 |          68.54 |        68.18 |           84.05 |             56.44 |         5.39 |
|              14 | MT.AS     | MT.AS     | EUROPE   |               47.39 |                     0.06 |    -0.04 |     -0.01 |                  75.42 |                        76.09 |         60.98 |         75.62 |          78.25 |        74.87 |           72.87 |             82.61 |         5.07 |
|              15 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.87 |                     0.02 |    -0.02 |      0.07 |                  51.56 |                        75.8  |         77.37 |         74.1  |          75.14 |        76.38 |           96.75 |             66.83 |         2.18 |
|              16 | DAR       | DAR       | US       |                8.46 |                     0.09 |    -0.06 |     -0.02 |                  65.59 |                        74.6  |         54.49 |         67.12 |          75.97 |        80.55 |           90.7  |             87.06 |         4.76 |
|              17 | PBR-A     | PBR-A     | US       |              114.95 |                     0.02 |     0.02 |      0.2  |                  42.76 |                        74.04 |         84.13 |         76.24 |          72.19 |        78.58 |           74.69 |             70.83 |         4.55 |
|              18 | FORTUM.HE | FORTUM.HE | EUROPE   |               21.18 |                     0.04 |    -0.03 |      0.17 |                  72.63 |                        74.02 |         79.19 |         66.65 |          59.03 |        53.4  |           69.27 |             64.51 |         4.66 |
|              19 | C5H.IR    | C5H.IR    | EUROPE   |                1.64 |                     0.06 |    -0.02 |      0.05 |                  71.93 |                        74.01 |         71.13 |         66.44 |          71.52 |        75.31 |           98.22 |             53.41 |         2.71 |
|              20 | SHEL      | SHEL      | US       |              237.78 |                     0.04 |    -0    |      0.03 |                  59.82 |                        73.79 |         75.67 |         72.27 |          69.16 |        72.93 |           74.6  |             80.4  |         3.03 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              350.47 |             32.93 |         42.24 |         31.08 |           32.3 |        33.56 |           35.89 |             41.53 |             27.37 |          8.5 |             89.81 | short              |               -7.92 |                 -0.43 |                -0.03 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     29 | AMS.SW   | AMS.SW                         | EUROPE   |                2.26 |             74.06 |         84.74 |         77.92 |          70.2  |        53.13 |           55.16 |             89.88 |             10.28 |         8.69 |             73.14 | short              |                2.99 |                  4.89 |               nan    |
|    502 | CYH      | Community Health Systems, Inc. | US       |                0.37 |             48.35 |         56.33 |         40.28 |          42.26 |        54.43 |           42.28 |             27.79 |             92.54 |         8.14 |             82.05 | short              |                8.76 |                  4.57 |                 4.08 |
|    337 | ITRG     | ITRG                           | OTHER    |                0.49 |             55.67 |         54.72 |         55.34 |          56    |        65.23 |           65.38 |             61.63 |             79.8  |         8.23 |             68.32 | long               |               -0.13 |                  4.43 |                 4.78 |
|    136 | GVR.IR   | GVR.IR                         | EUROPE   |                1.19 |             64.72 |         62.23 |         56.11 |          67.21 |        72.88 |           93.24 |             62.53 |             58.2  |         2.7  |             73.14 | long               |              nan    |                  4.42 |               nan    |
|      8 | AMC      | AMC                            | US       |                2.24 |             79.28 |         79.6  |         84.19 |          78.97 |        78.41 |           86.65 |             78.94 |            nan    |         9.51 |             65.07 | swing              |                3.09 |                  4.08 |                 3.84 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    479 | TEVA     | TEVA    | US       |               39.74 |             49.66 |         64.69 |         54.14 |          45.19 |        37.17 |           17.61 |             25.56 |             41.76 |         4.81 |             72.34 | short              |               -5.35 |                 -4.01 |                -4    |
|    686 | PAH3.DE  | PAH3.DE | EUROPE   |                7.84 |             32.54 |         28.94 |         28.95 |          36.12 |        59.97 |          nan    |             23.85 |             94.19 |         5.23 |             70.3  | long               |              -12.81 |                 -3.79 |                -3.15 |
|    483 | CNC      | CNC     | US       |               26.79 |             49.55 |         42.53 |         54.67 |          57.52 |        44.43 |           12.31 |             70.88 |             55.62 |         5.98 |             71.66 | medium             |               -9.67 |                 -3.55 |                -3.05 |
|    425 | CMPS     | CMPS    | US       |                1.66 |             51.9  |         46.24 |         57.56 |          58.01 |        42.03 |           44.67 |             49.66 |              4.96 |         7.91 |             69.27 | medium             |              -13.76 |                 -3.18 |                -3.37 |
|    643 | PIRC.MI  | PIRC.MI | EUROPE   |                7    |             39.19 |         49.9  |         42.42 |          35.96 |        34.98 |           18.02 |             16.74 |             54.61 |         2.16 |             71.32 | short              |               -4.88 |                 -3.18 |                -2.99 |

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
- Excluded by hard/data filters: **288**
- Event watch (otherwise eligible): **1**
- Final eligible: **711**
- Eligible change vs previous stored run: **+2**

Top exclusion categories:
- liquidity: 238
- price: 184
- market_cap: 161
- price_history: 15
- data_confidence: 10
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 2 |  | 2 | main,pullback |
| CMBT.BR | 2 |  | 1 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 3 |  | 2 | main,pullback |
| VLO | 7 |  | 5 |  | 2 | main,pullback |
| PSX | 9 |  | 4 |  | 2 | main,pullback |
| NVDA | 34 | 3 |  | 1 | 1 | value,quality_value |
| PBR | 61 | 9 | 44 | 7 | 1 | value,quality_value |
| EMBC | 97 | 2 |  | 2 | 1 | value,quality_value |
| AVGO | 294 | 5 |  | 4 | 1 | value,quality_value |
| VOLV-B.ST | 366 | 1 | 209 | 3 | 1 | value,quality_value |
| ATNI | 424 | 6 | 273 | 9 | 1 | value,quality_value |
| HOS | 559 | 7 |  | 6 | 1 | value,quality_value |
| NOVO-B.CO | 583 | 8 |  | 8 | 1 | value,quality_value |
| STNE | 653 | 4 | 375 | 10 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **4** (MU, HPE, AMC, REP.MC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SMTC)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | VOLV-B.ST | value+pullback | 67.82 | 82.31 | 72.00 | 52.22 | 62.57 | 55.20 | 54.60 |
| 2 | ATNI | value+pullback | 64.27 | 80.24 | 71.90 | 39.57 | 51.13 | 55.91 | 51.91 |
| 3 | STNE | value+pullback | 60.93 | 85.75 | 59.25 | 44.86 | 25.57 | 55.55 | 37.86 |
| 4 | CMBT.BR | pullback | 60.79 | 55.36 | 85.67 | 96.57 | 77.55 | 85.67 | 82.74 |
| 5 | PBR | value+pullback | 60.52 | 67.50 | 51.49 | 74.98 | 40.47 | 60.53 | 70.64 |
| 6 | SAP.DE | value+pullback | 60.27 | 71.58 | 70.03 | 42.49 | 52.21 | 48.45 | 54.99 |
| 7 | PAGP | pullback | 57.46 | 50.63 | 76.61 | 83.37 | 86.42 | 85.78 | 71.39 |
| 8 | BP | pullback | 57.15 | 58.96 | 75.07 | 86.92 | 88.21 | 82.60 | 73.06 |
| 9 | FRO | pullback | 56.66 | 56.39 | 74.20 | 92.04 | 81.29 | 80.88 | 80.53 |
| 10 | DHT | pullback | 56.66 | 56.67 | 74.22 | 88.87 | 84.07 | 81.84 | 77.04 |
| 11 | MPC | pullback | 55.75 | 50.18 | 69.68 | 85.01 | 90.34 | 82.71 | 83.26 |
| 12 | DAR | pullback | 55.45 | 53.04 | 65.59 | 90.70 | 87.06 | 83.73 | 71.55 |
| 13 | PSX | pullback | 55.16 | 51.54 | 73.84 | 80.30 | 86.39 | 80.09 | 79.26 |
| 14 | VLO | pullback | 54.71 | 50.04 | 68.65 | 86.43 | 81.76 | 82.05 | 80.24 |
| 15 | ARGX.BR | pullback | 54.25 | 35.12 | 62.70 | 94.83 | 81.39 | 81.08 | 63.67 |
| 16 | C5H.IR | pullback | 54.21 | 52.02 | 71.93 | 98.22 | 53.41 | 80.75 | 71.33 |
| 17 | NVDA | value | 53.87 | 60.87 | 43.31 | 81.99 | 81.30 | 75.89 | 73.23 |
| 18 | AMV0.DE | pullback | 53.58 | 59.22 | 78.91 | 92.77 | 55.94 | 71.70 | 63.33 |
| 19 | RDDT | pullback | 53.45 | 43.21 | 75.63 | 87.10 | 74.98 | 69.92 | 52.26 |
| 20 | GVR.IR | pullback | 53.43 | 52.05 | 67.79 | 93.24 | 62.53 | 81.20 | 64.72 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 6 / 4 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 73.1 | 14 / 11 |
| Top 50 | 49/50 | 48/50 | 49/50 | 46/50 | 0/50 | 72.7 | 24 / 26 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
