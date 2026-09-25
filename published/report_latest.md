# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-25

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

- **EUROPE:** 79.5/100
- **OTHER:** 63.5/100
- **US:** 80.7/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | FRO       | FRO       | US       |                9.38 |             83.64 |         83.26 |         84.23 |          84.03 |        80.02 |           90.9  |             80.85 |             54.1  |         5.45 |             73.14 | swing              |               -1.27 |                  0.85 |                 0.72 |
|      2 | HPE       | HPE       | US       |               74.08 |             83.48 |         89.86 |         86.28 |          80.69 |        70.6  |           71.87 |             82.66 |             45.08 |         6.92 |             72.34 | short              |                2.12 |                  0.74 |               nan    |
|      3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.83 |             82.01 |         71.72 |         80.98 |          84.75 |        83.04 |           96.4  |             78.85 |             63.84 |         3.74 |             73.14 | medium             |               -2.18 |                  1.17 |                 1.13 |
|      4 | MU        | MU        | US       |             1072.18 |             81.78 |         80.09 |         70.99 |          84.87 |        83.48 |           94.75 |             82.92 |             65.77 |         8.14 |             73.14 | medium             |                1.02 |                  2.57 |                 1.99 |
|      5 | VLO       | VLO       | US       |               96.85 |             81.55 |         77.91 |         85.43 |          84.28 |        78.81 |           86    |             81.85 |             55.16 |         3.58 |             69.68 | swing              |               -4.2  |                  0.85 |                 0.81 |
|      6 | DHT       | DHT       | US       |                3.07 |             80.95 |         80.63 |         81.74 |          81.27 |        79.2  |           87.16 |             83.66 |             57.44 |         4.51 |             73.14 | swing              |               -1.12 |                  0.91 |                 0.57 |
|      7 | AMC       | AMC       | US       |                2.28 |             80.9  |         81.89 |         87.22 |          79.92 |        78.56 |           83.66 |             79.42 |            nan    |         9.52 |             65.07 | swing              |                4.71 |                  4.4  |                 4.08 |
|      8 | P         | P         | US       |               35.68 |             80.46 |         92.54 |         87.59 |          73.33 |        58.75 |           68.55 |             92.14 |             11.61 |         8.15 |             72.68 | short              |                3.09 |                  3.17 |                 2.3  |
|      9 | DELL      | DELL      | US       |              299.43 |             79.89 |         78.91 |         83.71 |          80.88 |        68.28 |           71.94 |             87.94 |             33.33 |         7.82 |             72.23 | swing              |               -3.73 |                 -0.47 |                -0.5  |
|     10 | PSX       | PSX       | US       |               89.7  |             79.26 |         74.96 |         84.62 |          82.12 |        76.4  |           78.93 |             86.91 |             55.26 |         3.8  |             73.14 | swing              |               -4.6  |                  0.84 |                 0.97 |
|     11 | HSHP      | HSHP      | US       |                0.75 |             78.75 |         79.41 |         81.98 |          78.09 |        67.19 |           85.58 |            nan    |             21.36 |         4.83 |             62.84 | swing              |               -4.05 |                nan    |               nan    |
|     12 | OKTA      | OKTA      | US       |               31.74 |             78.1  |         90.44 |         84.11 |          72.09 |        57.7  |           68.14 |             70.12 |             11.13 |         7.81 |             71.77 | short              |               -0.43 |                  0.87 |                 0.88 |
|     13 | NAT       | NAT       | US       |                1.43 |             78.08 |         80.41 |         78.44 |          77.71 |        71.82 |           86.92 |             69.37 |             35.75 |         4.87 |             73.14 | short              |               -2.49 |                 -0    |                 0.07 |
|     14 | PBR-A     | PBR-A     | US       |              114.23 |             78.01 |         82.56 |         76.87 |          72.86 |        79.15 |           74.12 |             71.59 |             86.56 |         4.5  |             69.89 | short              |                3.49 |                  0.9  |                 0.48 |
|     15 | HALO      | HALO      | US       |               11.49 |             77.27 |         82.04 |         80.14 |          74.39 |        70.73 |           87.06 |             50.25 |             45.6  |         6.07 |             72.11 | short              |                1.16 |                nan    |               nan    |
|     16 | REP.MC    | REP.MC    | EUROPE   |               33.14 |             77.15 |         83.09 |         80.01 |          74.29 |        70.33 |           61.09 |             79.09 |             68.91 |         3.77 |             73.14 | short              |                2.49 |                  1.59 |                 1.27 |
|     17 | SHELL.AS  | SHELL.AS  | EUROPE   |              240.62 |             77.14 |         80.85 |         74.95 |          73.47 |        79.32 |           93.45 |             80.3  |             64.07 |         2.47 |             73.14 | short              |                2.99 |                  2.62 |                 2.48 |
|     18 | KIN.BR    | KIN.BR    | EUROPE   |                1.36 |             76.93 |         79.47 |         80.06 |          74.39 |        65.14 |           89.95 |             64.96 |             17.7  |         3.69 |             73.14 | swing              |               -0.82 |                 -0.35 |                -0.27 |
|     19 | SSABBH.HE | SSABBH.HE | EUROPE   |                9.41 |             76.64 |         66.66 |         73.29 |          79.99 |        82.4  |           72.53 |            nan    |             98.54 |         4.29 |             62.84 | long               |                1.46 |                nan    |               nan    |
|     20 | OMV.VI    | OMV.VI    | EUROPE   |               23.68 |             75.96 |         78.49 |         78.97 |          73.43 |        69.94 |           62.69 |             85.04 |             65.65 |         1.87 |             72.34 | swing              |                4.74 |                  1.08 |                 0.59 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                                            | EUROPE   |              240.62 |                  59.43 |                    71.43 |                 75.27 |              66.57 |                87.48 |                   12.52 |           93.45 |             80.3  |     nan     |         nan |       nan |      nan    |         9.61 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                                               | US       |              114.23 |                  69.82 |                    70.87 |                 71.33 |              70.21 |                70.98 |                   29.02 |           74.12 |             71.59 |     nan     |         nan |       nan |      nan    |         4.72 |          4.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                                  | US       |              100.49 |                  58.86 |                    70.09 |                 73.79 |              66    |                82.61 |                   17.39 |           87.11 |             87.54 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                | US       |              239.6  |                  64.96 |                    69.72 |                 71.08 |              68.61 |                76.43 |                   23.57 |           73.01 |             80.86 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                                             | EUROPE   |                4.83 |                  55.78 |                    69.39 |                 73.93 |              63.52 |                85.97 |                   14.03 |           96.4  |             78.85 |     nan     |         nan |       nan |      nan    |         9.15 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                 | US       |                3.07 |                  57.3  |                    68.59 |                 72.33 |              64.27 |                81.36 |                   18.64 |           87.16 |             83.66 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                 | US       |                9.38 |                  56.93 |                    68.53 |                 72.54 |              63.56 |                80.47 |                   19.53 |           90.9  |             80.85 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                             | EUROPE   |               18.95 |                  56.03 |                    68.3  |                 72.32 |              62.45 |                85.46 |                   14.54 |           96.77 |             67.29 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                                  | US       |                7.34 |                  61.28 |                    68.26 |                 70.9  |              65.28 |                72.3  |                   27.7  |           81.07 |             81.45 |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                                              | EUROPE   |              176.81 |                  64.23 |                    68.14 |                 69.13 |              67.78 |                74.14 |                   25.86 |           67.29 |             81.89 |     nan     |         nan |       nan |      nan    |         9.05 |         11.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                              | EUROPE   |               15.64 |                  63.29 |                    67.9  |                 69.39 |              64.63 |                77.2  |                   22.8  |           86.31 |             51.68 |     nan     |         nan |       nan |      nan    |         8.71 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GGN      | GAMCO Global Gold, Natural Resources & Income Trust | US       |                0.74 |                  58.16 |                    67.24 |                 69.77 |              65.31 |                80.7  |                   19.3  |           72.51 |             89.11 |     nan     |         nan |       nan |      nan    |       nan    |          4.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | WB       | Weibo Corporation                                   | OTHER    |                1.41 |                  75.84 |                    67.21 |                 63.84 |              70.29 |                65.43 |                   34.57 |           56.16 |             39.02 |     nan     |         nan |       nan |        1.74 |         5.09 |          5.44 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|            2 | AVGO     | Broadcom Inc.                                       | US       |             1469.43 |                  54.72 |                    66.97 |                 68.92 |              59.04 |                84.71 |                   15.29 |          100    |             43.96 |       0.018 |         nan |       nan |       32.68 |        18.08 |         44.63 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | A5G.IR   | A5G.IR                                              | EUROPE   |               24.43 |                  55.75 |                    65.99 |                 69.48 |              60.15 |                80.84 |                   19.16 |           96.29 |             54.62 |     nan     |         nan |       nan |      nan    |        11.76 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | NN.AS    | NN.AS                                               | EUROPE   |               20.82 |                  62.76 |                    65.94 |                 66.7  |              64.8  |                73.58 |                   26.42 |           71.47 |             63.68 |     nan     |         nan |       nan |      nan    |         9.01 |         11.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR      | PBR                                                 | US       |              118    |                  68.81 |                    65.52 |                 64.87 |              64.6  |                60.66 |                   39.34 |           74.41 |             41.35 |     nan     |         nan |       nan |      nan    |         5.23 |          5.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | ASRNL.AS | ASRNL.AS                                            | EUROPE   |               14.88 |                  57.01 |                    65.18 |                 67.6  |              61.83 |                79.11 |                   20.89 |           81.07 |             65.41 |     nan     |         nan |       nan |      nan    |        11.37 |         14.37 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EQNR     | EQNR                                                | US       |               89.91 |                  55.41 |                    64.77 |                 67.87 |              61.76 |                74.05 |                   25.95 |           76.05 |             85.41 |     nan     |         nan |       nan |      nan    |        10.5  |         11.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBMO.AS  | SBMO.AS                                             | EUROPE   |                6.01 |                  56.54 |                    64.66 |                 67.46 |              60.96 |                73.66 |                   26.34 |           81.94 |             69.91 |     nan     |         nan |       nan |      nan    |         9.16 |          7.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:----------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                                            | EUROPE   |              240.62 |                  59.43 |                    71.43 |                 75.27 |              66.57 |                87.48 |                   12.52 |           93.45 |             80.3  |     nan     |         nan |       nan |      nan    |         9.61 |         10.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                                             | EUROPE   |                4.83 |                  55.78 |                    69.39 |                 73.93 |              63.52 |                85.97 |                   14.03 |           96.4  |             78.85 |     nan     |         nan |       nan |      nan    |         9.15 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                                  | US       |              100.49 |                  58.86 |                    70.09 |                 73.79 |              66    |                82.61 |                   17.39 |           87.11 |             87.54 |     nan     |         nan |       nan |      nan    |         9.03 |         21.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                                 | US       |                9.38 |                  56.93 |                    68.53 |                 72.54 |              63.56 |                80.47 |                   19.53 |           90.9  |             80.85 |     nan     |         nan |       nan |      nan    |        10.48 |          7.13 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                 | US       |                3.07 |                  57.3  |                    68.59 |                 72.33 |              64.27 |                81.36 |                   18.64 |           87.16 |             83.66 |     nan     |         nan |       nan |      nan    |        10.1  |          7.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                             | EUROPE   |               18.95 |                  56.03 |                    68.3  |                 72.32 |              62.45 |                85.46 |                   14.54 |           96.77 |             67.29 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A    | PBR-A                                               | US       |              114.23 |                  69.82 |                    70.87 |                 71.33 |              70.21 |                70.98 |                   29.02 |           74.12 |             71.59 |     nan     |         nan |       nan |      nan    |         4.72 |          4.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                                | US       |              239.6  |                  64.96 |                    69.72 |                 71.08 |              68.61 |                76.43 |                   23.57 |           73.01 |             80.86 |     nan     |         nan |       nan |      nan    |         9.23 |         10.56 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                                  | US       |                7.34 |                  61.28 |                    68.26 |                 70.9  |              65.28 |                72.3  |                   27.7  |           81.07 |             81.45 |     nan     |         nan |       nan |      nan    |         4.4  |          6.08 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | GGN      | GAMCO Global Gold, Natural Resources & Income Trust | US       |                0.74 |                  58.16 |                    67.24 |                 69.77 |              65.31 |                80.7  |                   19.3  |           72.51 |             89.11 |     nan     |         nan |       nan |      nan    |       nan    |          4.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                                  | US       |             1072.18 |                  48.24 |                    63.89 |                 69.49 |              57.02 |                77.73 |                   22.27 |           94.75 |             82.92 |     nan     |         nan |       nan |      nan    |         6.77 |         24.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                                              | EUROPE   |               24.43 |                  55.75 |                    65.99 |                 69.48 |              60.15 |                80.84 |                   19.16 |           96.29 |             54.62 |     nan     |         nan |       nan |      nan    |        11.76 |         12.15 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                                              | EUROPE   |               15.64 |                  63.29 |                    67.9  |                 69.39 |              64.63 |                77.2  |                   22.8  |           86.31 |             51.68 |     nan     |         nan |       nan |      nan    |         8.71 |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                                              | EUROPE   |              176.81 |                  64.23 |                    68.14 |                 69.13 |              67.78 |                74.14 |                   25.86 |           67.29 |             81.89 |     nan     |         nan |       nan |      nan    |         9.05 |         11.47 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | AVGO     | Broadcom Inc.                                       | US       |             1469.43 |                  54.72 |                    66.97 |                 68.92 |              59.04 |                84.71 |                   15.29 |          100    |             43.96 |       0.018 |         nan |       nan |       32.68 |        18.08 |         44.63 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | C5H.IR   | C5H.IR                                              | EUROPE   |                1.67 |                  51.95 |                    64.09 |                 68.22 |              57.43 |                81.05 |                   18.95 |           98.09 |             54.39 |     nan     |         nan |       nan |      nan    |        10.42 |         10.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO      | VLO                                                 | US       |               96.85 |                  49.16 |                    63.61 |                 68.21 |              58.35 |                82.05 |                   17.95 |           86    |             81.85 |     nan     |         nan |       nan |      nan    |        10.06 |         15.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX                                                 | US       |               89.7  |                  51.74 |                    64.15 |                 68.01 |              60.29 |                79.71 |                   20.29 |           78.93 |             86.91 |     nan     |         nan |       nan |      nan    |        10.28 |         14.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | ADAM     | Adamas Trust, Inc.                                  | US       |                0.64 |                  53.16 |                    64.09 |                 67.95 |              58.78 |                77.35 |                   22.65 |           90.22 |             65.8  |     nan     |         nan |       nan |      nan    |         6.52 |          5.02 |        2.5  |                 nan |              nan |                   9 |                  0.47 |
|          nan | EQNR     | EQNR                                                | US       |               89.91 |                  55.41 |                    64.77 |                 67.87 |              61.76 |                74.05 |                   25.95 |           76.05 |             85.41 |     nan     |         nan |       nan |      nan    |        10.5  |         11.64 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO      | VLO      | US       |               96.85 |                     0.07 |    -0.07 |      0.1  |                  80.29 |                        84.24 |         77.91 |         85.43 |          84.28 |        78.81 |           86    |             81.85 |         3.58 |
|               2 | FRO      | FRO      | US       |                9.38 |                     0.07 |    -0.05 |      0.24 |                  78.62 |                        84.21 |         83.26 |         84.23 |          84.03 |        80.02 |           90.9  |             80.85 |         5.45 |
|               3 | PSX      | PSX      | US       |               89.7  |                     0.07 |    -0.07 |      0.06 |                  82.98 |                        83.58 |         74.96 |         84.62 |          82.12 |        76.4  |           78.93 |             86.91 |         3.8  |
|               4 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.83 |                     0.08 |    -0.06 |      0.05 |                  72.39 |                        82.45 |         71.72 |         80.98 |          84.75 |        83.04 |           96.4  |             78.85 |         3.74 |
|               5 | DHT      | DHT      | US       |                3.07 |                     0.07 |    -0.05 |      0.18 |                  77.15 |                        82.42 |         80.63 |         81.74 |          81.27 |        79.2  |           87.16 |             83.66 |         4.51 |
|               6 | DELL     | DELL     | US       |              299.43 |                     0.09 |    -0.09 |      0.16 |                  75.74 |                        80.8  |         78.91 |         83.71 |          80.88 |        68.28 |           71.94 |             87.94 |         7.82 |
|               7 | SMTC     | SMTC     | US       |               14.31 |                     0.06 |    -0.02 |      0.24 |                  75.79 |                        80.1  |         82.09 |         75.02 |          74.89 |        61.9  |           74.02 |             85.93 |         8.45 |
|               8 | NAT      | NAT      | US       |                1.43 |                     0.07 |    -0.06 |      0.22 |                  78.15 |                        79.71 |         80.41 |         78.44 |          77.71 |        71.82 |           86.92 |             69.37 |         4.87 |
|               9 | BP       | BP       | US       |              100.49 |                     0.05 |    -0.02 |      0.04 |                  76.89 |                        79.32 |         74.48 |         72.55 |          71.77 |        76.89 |           87.11 |             87.54 |         4.5  |
|              10 | EQNR     | EQNR     | US       |               89.91 |                     0.06 |    -0.03 |      0.05 |                  77.6  |                        78.14 |         71.67 |         76.95 |          74.41 |        73.66 |           76.05 |             85.41 |         5.68 |
|              11 | DAR      | DAR      | US       |                8.56 |                     0.09 |    -0.07 |     -0.01 |                  71.22 |                        76.04 |         57.28 |         68.94 |          76.93 |        81.14 |           88.95 |             87.31 |         4.77 |
|              12 | CIRSA.MC | CIRSA.MC | EUROPE   |                3.25 |                     0.03 |    -0.01 |      0.39 |                  55.7  |                        75.74 |         84.15 |         77.9  |          68.61 |        68    |           83.21 |             57.8  |         5.38 |
|              13 | C5H.IR   | C5H.IR   | EUROPE   |                1.67 |                     0.05 |     0.02 |      0.06 |                  63.04 |                        75.3  |         76.14 |         67.68 |          71.84 |        75.1  |           98.09 |             54.39 |         2.68 |
|              14 | PBR-A    | PBR-A    | US       |              114.23 |                     0.03 |     0    |      0.19 |                  54.36 |                        75    |         82.56 |         76.87 |          72.86 |        79.15 |           74.12 |             71.59 |         4.5  |
|              15 | NTNX     | NTNX     | US       |               16.31 |                     0.02 |    -0.02 |      0.05 |                  55.35 |                        74.57 |         71.16 |         77.23 |          69.42 |        62.1  |           92.71 |             60.71 |         6.6  |
|              16 | APA      | APA      | US       |               13.45 |                     0.08 |    -0.04 |      0.06 |                  67.6  |                        74.53 |         71.35 |         75.12 |          73.43 |        74.4  |           72.7  |             81.94 |         6.06 |
|              17 | BE       | BE       | US       |               69    |                     0.05 |    -0.05 |      0.22 |                  82.56 |                        74.51 |         72.15 |         56.84 |          67.57 |        59.89 |           85.18 |             60.1  |         9.16 |
|              18 | SHEL     | SHEL     | US       |              239.6  |                     0.03 |    -0    |      0.05 |                  58.41 |                        73.83 |         76.67 |         74.37 |          70.13 |        73.72 |           73.01 |             80.86 |         2.98 |
|              19 | ARGX.BR  | ARGX.BR  | EUROPE   |               53.09 |                     0.07 |    -0.03 |     -0.05 |                  69.36 |                        73.81 |         56.37 |         65.06 |          68.79 |        61.64 |           93.16 |             81.6  |         6.16 |
|              20 | NESTE.HE | NESTE.HE | EUROPE   |               26.7  |                     0.03 |    -0    |      0.11 |                  56.55 |                        73.78 |         79.44 |         74.31 |          69.25 |        60.72 |           62.34 |             87.38 |         4.91 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                 0.5 |             27.04 |         29.53 |          22.1 |          24.55 |        29.83 |           34.31 |             31.79 |             29.46 |          8.9 |             78.44 | long               |                1.85 |                 -0.09 |                 0.05 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      7 | AMC      | AMC     | US       |                2.28 |             80.9  |         81.89 |         87.22 |          79.92 |        78.56 |           83.66 |             79.42 |            nan    |         9.52 |             65.07 | swing              |                4.71 |                  4.4  |                 4.08 |
|    561 | ZH       | ZH      | US       |                0.28 |             45.69 |         73.04 |         55.05 |          36.33 |        27.98 |           18.05 |             25.98 |             26.06 |         7.37 |             73.14 | short              |                6.65 |                  4.37 |                 3.26 |
|    292 | BHF      | BHF     | US       |                2.7  |             58.26 |         65.84 |         41.64 |          50.69 |        67.84 |           65.51 |             46.4  |             97.81 |         4.07 |             69.55 | long               |               15.52 |                  3.94 |                 3.2  |
|    140 | RBI.VI   | RBI.VI  | EUROPE   |               21.41 |             65.34 |         74.33 |         69.77 |          60.9  |        47.64 |           10.09 |             71.56 |             66.09 |         4.45 |             71.77 | short              |                5.09 |                  3.72 |                 3.14 |
|    145 | 0N9S.IL  | 0N9S.IL | OTHER    |               79.1  |             65.14 |         85.63 |         69.68 |          60.59 |        58.26 |          nan    |            nan    |             38.46 |         3.32 |             60    | short              |              nan    |                  3.63 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    639 | SONY     | SONY    | US       |              118.07 |             39.63 |         40.34 |         49.89 |          38.91 |        33.75 |           22.66 |             43.93 |             32.2  |         5.2  |             69.5  | swing              |              nan    |                 -4.14 |                -3.99 |
|    681 | PAH3.DE  | PAH3.DE | EUROPE   |                7.87 |             33.17 |         28.02 |         29.42 |          36.91 |        60.88 |          nan    |             24.8  |             96.3  |         5.17 |             70.3  | long               |              -12.18 |                 -3.66 |                -3.05 |
|    648 | PIRC.MI  | PIRC.MI | EUROPE   |                7.01 |             38.83 |         48.24 |         41.5  |          36.16 |        35.66 |           18.44 |             17.73 |             57.19 |         2.16 |             71.32 | short              |               -5.24 |                 -3.25 |                -3.05 |
|    473 | CNC      | CNC     | US       |               26.87 |             51.12 |         41.98 |         55.38 |          59.19 |        46.85 |           13.15 |             71.63 |             59.73 |         5.93 |             71.66 | medium             |               -8.11 |                 -3.24 |                -2.82 |
|    409 | TEVA     | TEVA    | US       |               41.21 |             53.85 |         70.56 |         59.79 |          47.91 |        39.22 |           17.77 |             25.97 |             43.92 |         4.81 |             72.34 | short              |               -1.16 |                 -3.18 |                -3.37 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.86

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
- Excluded by hard/data filters: **294**
- Event watch (otherwise eligible): **1**
- Final eligible: **705**
- Eligible change vs previous stored run: **-4**

Top exclusion categories:
- liquidity: 241
- price: 184
- market_cap: 165
- price_history: 19
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| FRO | 1 |  | 2 |  | 2 | main,pullback |
| CMBT.BR | 3 |  | 4 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| DHT | 6 |  | 5 |  | 2 | main,pullback |
| DELL | 9 |  | 6 |  | 2 | main,pullback |
| PSX | 10 |  | 3 |  | 2 | main,pullback |
| SAP.DE | 214 | 10 | 91 | 8 | 1 | value,quality_value |
| AVGO | 336 | 2 | 77 | 1 | 1 | value,quality_value |
| ADAM | 368 | 3 |  | 2 | 1 | value,quality_value |
| DX | 525 | 4 | 199 | 3 | 1 | value,quality_value |
| NFLX | 605 | 7 |  | 5 | 1 | value,quality_value |
| WB | 655 | 1 | 341 | 4 | 1 | value,quality_value |
| MC.PA | 669 | 6 |  | 6 | 1 | value,quality_value |
| HPE | 2 |  |  |  | 1 | main |
| MU | 4 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **3** (HPE, MU, P)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **1** (SMTC)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | WB | value+pullback | 64.42 | 75.84 | 65.03 | 56.16 | 39.02 | 65.43 | 37.94 |
| 2 | KYN | value+pullback | 61.58 | 55.90 | 75.47 | 66.67 | 49.25 | 55.11 | 53.76 |
| 3 | CMBT.BR | pullback | 57.63 | 55.78 | 72.39 | 96.40 | 78.85 | 85.97 | 82.01 |
| 4 | VLO | pullback | 57.57 | 49.16 | 80.29 | 86.00 | 81.85 | 82.05 | 81.55 |
| 5 | BP | pullback | 57.56 | 58.86 | 76.89 | 87.11 | 87.54 | 82.61 | 73.52 |
| 6 | FRO | pullback | 57.47 | 56.93 | 78.62 | 90.90 | 80.85 | 80.47 | 83.64 |
| 7 | PSX | pullback | 57.22 | 51.74 | 82.98 | 78.93 | 86.91 | 79.71 | 79.26 |
| 8 | DHT | pullback | 57.00 | 57.30 | 77.15 | 87.16 | 83.66 | 81.36 | 80.95 |
| 9 | GTN | value+pullback | 56.76 | 72.75 | 67.08 | 43.79 | 37.79 | 39.10 | 47.58 |
| 10 | DAR | pullback | 56.46 | 52.25 | 71.22 | 88.95 | 87.31 | 82.92 | 72.94 |
| 11 | ARGX.BR | pullback | 55.56 | 35.50 | 69.36 | 93.16 | 81.60 | 80.42 | 63.35 |
| 12 | NAT | pullback | 54.70 | 51.32 | 78.15 | 86.92 | 69.37 | 75.94 | 78.08 |
| 13 | HSHP | pullback | 54.19 | 45.89 | 82.86 | 85.58 |  | 78.17 | 78.75 |
| 14 | EQNR | pullback | 54.16 | 55.41 | 77.60 | 76.05 | 85.41 | 74.05 | 74.03 |
| 15 | GGN | pullback | 53.41 | 58.16 | 69.94 | 72.51 | 89.11 | 80.70 | 61.07 |
| 16 | AVGO | pullback | 53.23 | 54.72 | 67.55 | 100.00 | 43.96 | 84.71 | 56.64 |
| 17 | NETC.CO | pullback | 52.64 | 41.19 | 72.37 | 82.35 | 73.60 | 74.21 | 55.39 |
| 18 | KDP | pullback | 52.28 | 53.82 | 72.33 | 87.93 | 58.96 | 75.58 | 60.00 |
| 19 | DELL | pullback | 52.23 | 43.95 | 75.74 | 71.94 | 87.94 | 68.57 | 79.89 |
| 20 | SMTC | pullback | 52.18 | 36.72 | 75.79 | 74.02 | 85.93 | 67.71 | 74.96 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 72.9 | 7 / 3 |
| Top 25 | 25/25 | 23/25 | 24/25 | 22/25 | 0/25 | 72.3 | 14 / 11 |
| Top 50 | 50/50 | 48/50 | 49/50 | 47/50 | 0/50 | 72.5 | 24 / 26 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
