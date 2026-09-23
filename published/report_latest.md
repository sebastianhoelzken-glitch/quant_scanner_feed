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
|      1 | MPC      | MPC     | US       |               99.23 |             86.39 |         76.77 |         88.26 |          88.37 |        84.52 |           85.07 |             89.98 |             72.63 |         4.22 |             73.14 | medium             |               -0.76 |                nan    |               nan    |
|      2 | MU       | MU      | US       |             1079.84 |             83.86 |         82.12 |         75.89 |          86.4  |        85.6  |           95.26 |             80.87 |             71.81 |         8.16 |             73.14 | medium             |                3.09 |                  2.99 |                 2.3  |
|      3 | VLO      | VLO     | US       |               94.72 |             83.5  |         76.58 |         85.39 |          85.57 |        81.6  |           86.28 |             81.97 |             63.83 |         3.6  |             69.68 | medium             |               -2.25 |                  1.24 |                 1.1  |
|      4 | CMBT.BR  | CMBT.BR | EUROPE   |                4.96 |             82.94 |         82.84 |         83.03 |          84.96 |        82.38 |           96.03 |             77.86 |             59.23 |         3.77 |             73.14 | medium             |               -1.25 |                  1.35 |                 1.27 |
|      5 | DELL     | DELL    | US       |              304.42 |             82.55 |         87.73 |         84.36 |          80.73 |        68.06 |           73.59 |             86.11 |             30.66 |         7.74 |             72.23 | short              |               -1.07 |                  0.06 |                -0.11 |
|      6 | FRO      | FRO     | US       |                9.31 |             82.06 |         82.67 |         79.94 |          83.68 |        81.45 |           91.26 |             80.4  |             60.73 |         5.47 |             73.14 | medium             |               -2.86 |                  0.54 |                 0.49 |
|      7 | PSX      | PSX     | US       |               89.37 |             81.25 |         76.66 |         85.4  |          83.6  |        78.91 |           80.45 |             85.4  |             61.88 |         3.73 |             73.14 | swing              |               -2.61 |                  1.24 |                 1.27 |
|      8 | AMC      | AMC     | US       |                2.31 |             81.16 |         82.1  |         86.82 |          80.23 |        79.36 |           84.64 |             79.8  |            nan    |         9.53 |             65.07 | swing              |                4.97 |                  4.45 |                 4.12 |
|      9 | HPE      | HPE     | US       |               70.67 |             80.81 |         88.27 |         82.09 |          79.53 |        71.86 |           74.29 |             73.05 |             52    |         6.89 |             72.34 | short              |               -0.55 |                  0.2  |               nan    |
|     10 | OKTA     | OKTA    | US       |               29.98 |             79.88 |         90.69 |         85.03 |          74.73 |        62.78 |           79.04 |             69.07 |             14.13 |         7.72 |             71.32 | short              |                1.35 |                  1.23 |                 1.14 |
|     11 | HSHP     | HSHP    | US       |                0.75 |             79.87 |         82.76 |         80.5  |          79.25 |        69.95 |           86.3  |            nan    |             29.12 |         4.81 |             62.84 | short              |               -2.93 |                nan    |               nan    |
|     12 | DHT      | DHT     | US       |                3.01 |             78.89 |         77    |         75.77 |          80.78 |        81.69 |           88.75 |             82.74 |             67.12 |         4.66 |             73.14 | long               |               -3.17 |                  0.5  |                 0.26 |
|     13 | HALO     | HALO    | US       |               11.4  |             78.15 |         80.72 |         81.42 |          75.58 |        72.47 |           87.29 |             51.4  |             49.89 |         5.86 |             72.11 | swing              |                2.04 |                nan    |               nan    |
|     14 | KIN.BR   | KIN.BR  | EUROPE   |                1.36 |             78.05 |         80.37 |         81.71 |          75.73 |        66.18 |           90.38 |             64.67 |             16.93 |         3.68 |             73.14 | swing              |                0.3  |                 -0.13 |                -0.1  |
|     15 | FSM      | FSM     | US       |                3.15 |             77.78 |         71.68 |         77.64 |          77.93 |        81.04 |           80.14 |             71.79 |             84.27 |         7.14 |             73.14 | long               |                2.42 |                  3.57 |                 3.02 |
|     16 | NAT      | NAT     | US       |                1.41 |             77.71 |         80.11 |         77.26 |          78.16 |        72.93 |           87.11 |             69.51 |             39.53 |         4.77 |             73.14 | short              |               -2.85 |                 -0.07 |                 0.01 |
|     17 | P        | P       | US       |               32.23 |             77.01 |         87.93 |         82.79 |          71.23 |        58.67 |           71.74 |             86.09 |             11.99 |         8.04 |             72.68 | short              |               -0.36 |                  2.48 |                 1.79 |
|     18 | ABN.AS   | ABN.AS  | EUROPE   |               35.33 |             76.62 |         77.79 |         77.37 |          75.87 |        70.33 |           80.63 |             68.84 |             46.09 |         2.81 |             73.14 | short              |                0.56 |                  1.51 |                 1.46 |
|     19 | REP.MC   | REP.MC  | EUROPE   |               31.81 |             76.24 |         77.8  |         80.19 |          74.69 |        70.97 |           61.37 |             77.04 |             68.88 |         3.64 |             73.14 | swing              |                1.59 |                  1.41 |                 1.14 |
|     20 | UGP      | UGP     | US       |                7.15 |             76.18 |         78.34 |         82.9  |          74.01 |        67.09 |           59.86 |             68.24 |             57.89 |         4.6  |             72.11 | swing              |               -0.29 |                  0.8  |                 0.32 |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  74.83 |                    75.65 |                 77.59 |              75.54 |                87.81 |                   12.19 |           87.87 |             58.54 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.18 |                  75.93 |                    75.48 |                 74.78 |              76.63 |                79.44 |                   20.56 |           69.91 |            nan    |       0.233 |         nan |       nan |        1.54 |       nan    |          2.96 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  80.07 |                    74.44 |                 74.44 |              77.77 |                67.02 |                   32.98 |           65.13 |             80.49 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.78 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  67.05 |                    71.4  |                 72.67 |              70.26 |                77.46 |                   22.54 |           75.29 |             80.41 |     nan     |         nan |       nan |      nan    |         9.07 |         10.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.07 |                  57.78 |                    70.92 |                 75.1  |              65.8  |                88.56 |                   11.44 |           93.73 |             82.52 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  60.44 |                    70.59 |                 74.03 |              66.47 |                81.56 |                   18.44 |           88.75 |             82.74 |     nan     |         nan |       nan |      nan    |         9.97 |          7.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  76.61 |                    70.51 |                 69.71 |              72.82 |                62.28 |                   37.72 |           64.86 |             64.51 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.41 |                  76.59 |                    70.46 |                 69.39 |              71.88 |                75.92 |                   24.08 |           75.72 |             30.73 |       0.08  |         nan |       nan |        3.86 |         5.06 |          4.37 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.82 |                 71.79 |              68.72 |                68.78 |                   31.22 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | STNE     | StoneCo Ltd.                         | OTHER    |                1.98 |                  72.17 |                    69.48 |                 69.07 |              67.5  |                68.19 |                   31.81 |           85.87 |             32.65 |       0.609 |         nan |       nan |        1.62 |         4.3  |          3.72 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | BBWI     | Bath & Body Works, Inc.              | US       |                3.02 |                  74.85 |                    69.24 |                 66.81 |              68.07 |                59.4  |                   40.6  |           75.98 |             34.84 |       0.221 |         nan |       nan |        5.64 |         6.16 |          4.51 |        0.69 |                 nan |              nan |                  11 |                  0.58 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.96 |                  55.82 |                    69.16 |                 73.61 |              63.35 |                85.4  |                   14.6  |           96.03 |             77.86 |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.45 |                    68.94 |                 71.43 |              65.98 |                72.47 |                   27.53 |           82.02 |             79.68 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  57.11 |                    68.64 |                 72.64 |              63.64 |                80.46 |                   19.54 |           91.26 |             80.4  |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               96.82 |                  56.67 |                    68.62 |                 72.54 |              64.19 |                82.29 |                   17.71 |           87.31 |             85.77 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  62.71 |                    68.15 |                 69.9  |              65.54 |                76.31 |                   23.69 |           81.03 |             66.52 |     nan     |         nan |       nan |      nan    |         9.48 |         13.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | IHS      | IHS Holding Limited                  | OTHER    |                2.49 |                  72.87 |                    68.1  |                 68.08 |              71.64 |                62.93 |                   37.07 |           56.31 |             78.45 |      -0.114 |         nan |       nan |        7.52 |        15.35 |          5.18 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              172.64 |                  63.79 |                    67.89 |                 69    |              67.1  |                74.36 |                   25.64 |           69.85 |             77.82 |     nan     |         nan |       nan |      nan    |         8.83 |         11.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | SDF.DE   | K+S Aktiengesellschaft               | EUROPE   |                2.91 |                  59.07 |                    67.74 |                 70.44 |              63.32 |                82.66 |                   17.34 |           90.36 |             59.14 |       0.117 |         nan |       nan |        2.04 |        13.67 |          2.75 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.68 |                  62.05 |                    67.62 |                 69.43 |              63.93 |                78.09 |                   21.91 |           88    |             51.95 |     nan     |         nan |       nan |      nan    |         8.73 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.06 |                  74.83 |                    75.65 |                 77.59 |              75.54 |                87.81 |                   12.19 |           87.87 |             58.54 |       0.858 |         nan |       nan |      nan    |       -79.36 |          2.12 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              234.07 |                  57.78 |                    70.92 |                 75.1  |              65.8  |                88.56 |                   11.44 |           93.73 |             82.52 |     nan     |         nan |       nan |      nan    |         9.35 |         10.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.18 |                  75.93 |                    75.48 |                 74.78 |              76.63 |                79.44 |                   20.56 |           69.91 |            nan    |       0.233 |         nan |       nan |        1.54 |       nan    |          2.96 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            3 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                  80.07 |                    74.44 |                 74.44 |              77.77 |                67.02 |                   32.98 |           65.13 |             80.49 |       0.142 |         nan |       nan |        1.79 |         4.71 |          4.78 |        5.39 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.01 |                  60.44 |                    70.59 |                 74.03 |              66.47 |                81.56 |                   18.44 |           88.75 |             82.74 |     nan     |         nan |       nan |      nan    |         9.97 |          7.28 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.96 |                  55.82 |                    69.16 |                 73.61 |              63.35 |                85.4  |                   14.6  |           96.03 |             77.86 |     nan     |         nan |       nan |      nan    |         9.44 |          6.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              233.82 |                  67.05 |                    71.4  |                 72.67 |              70.26 |                77.46 |                   22.54 |           75.29 |             80.41 |     nan     |         nan |       nan |      nan    |         9.07 |         10.39 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.31 |                  57.11 |                    68.64 |                 72.64 |              63.64 |                80.46 |                   19.54 |           91.26 |             80.4  |     nan     |         nan |       nan |      nan    |        10.47 |          7.18 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |               96.82 |                  56.67 |                    68.62 |                 72.54 |              64.19 |                82.29 |                   17.71 |           87.31 |             85.77 |     nan     |         nan |       nan |      nan    |         8.83 |         20.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.46 |                  68.48 |                    69.82 |                 71.79 |              68.72 |                68.78 |                   31.22 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.86 |         5.72 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.82 |                  54.76 |                    67.52 |                 71.69 |              61.53 |                85.41 |                   14.59 |           96.56 |             67.3  |     nan     |         nan |       nan |      nan    |        10.88 |         14.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                                   | US       |                7.04 |                  62.45 |                    68.94 |                 71.43 |              65.98 |                72.47 |                   27.53 |           82.02 |             79.68 |     nan     |         nan |       nan |      nan    |         4.28 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | SDF.DE   | K+S Aktiengesellschaft               | EUROPE   |                2.91 |                  59.07 |                    67.74 |                 70.44 |              63.32 |                82.66 |                   17.34 |           90.36 |             59.14 |       0.117 |         nan |       nan |        2.04 |        13.67 |          2.75 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|          nan | MPC      | MPC                                  | US       |               99.23 |                  50.81 |                    65.41 |                 70.07 |              60.51 |                82.92 |                   17.08 |           85.07 |             89.98 |     nan     |         nan |       nan |      nan    |         8.27 |         13.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY      | BMY                                  | US       |              110.91 |                  62.71 |                    68.15 |                 69.9  |              65.54 |                76.31 |                   23.69 |           81.03 |             66.52 |     nan     |         nan |       nan |      nan    |         9.48 |         13.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |             1079.84 |                  49.31 |                    64.3  |                 69.73 |              57.5  |                77.27 |                   22.73 |           95.26 |             80.87 |     nan     |         nan |       nan |      nan    |         6.9  |         24.77 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | EMBC     | Embecta Corp.                        | US       |                0.28 |                  76.61 |                    70.51 |                 69.71 |              72.82 |                62.28 |                   37.72 |           64.86 |             64.51 |       0.436 |         nan |       nan |        5.7  |         3.17 |          3.8  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.68 |                  62.05 |                    67.62 |                 69.43 |              63.93 |                78.09 |                   21.91 |           88    |             51.95 |     nan     |         nan |       nan |      nan    |         8.73 |          7.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.41 |                  76.59 |                    70.46 |                 69.39 |              71.88 |                75.92 |                   24.08 |           75.72 |             30.73 |       0.08  |         nan |       nan |        3.86 |         5.06 |          4.37 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                  | US       |               14.68 |                  55.17 |                    65.69 |                 69.1  |              61.29 |                79.58 |                   20.42 |           85.91 |             72.4  |     nan     |         nan |       nan |      nan    |        10.42 |         22.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | MPC       | MPC                                  | US       |               99.23 |                     0.08 |    -0.05 |      0.07 |                  68.18 |                        84.87 |         76.77 |         88.26 |          88.37 |        84.52 |           85.07 |             89.98 |         4.22 |
|               2 | PSX       | PSX                                  | US       |               89.37 |                     0.06 |    -0.03 |      0.06 |                  74.5  |                        82.78 |         76.66 |         85.4  |          83.6  |        78.91 |           80.45 |             85.4  |         3.73 |
|               3 | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.96 |                     0.05 |     0.01 |      0.1  |                  68.66 |                        82.7  |         82.84 |         83.03 |          84.96 |        82.38 |           96.03 |             77.86 |         3.77 |
|               4 | VLO       | VLO                                  | US       |               94.72 |                     0.09 |    -0.05 |      0.09 |                  65.45 |                        82.07 |         76.58 |         85.39 |          85.57 |        81.6  |           86.28 |             81.97 |         3.6  |
|               5 | FRO       | FRO                                  | US       |                9.31 |                     0.08 |    -0.02 |      0.15 |                  62.78 |                        81.06 |         82.67 |         79.94 |          83.68 |        81.45 |           91.26 |             80.4  |         5.47 |
|               6 | DELL      | DELL                                 | US       |              304.42 |                     0.06 |     0.02 |      0.28 |                  63.22 |                        80.98 |         87.73 |         84.36 |          80.73 |        68.06 |           73.59 |             86.11 |         7.74 |
|               7 | SHELL.AS  | SHELL.AS                             | EUROPE   |              234.07 |                     0.04 |    -0.04 |      0.03 |                  73.9  |                        79.11 |         73.31 |         73.81 |          74.72 |        80    |           93.73 |             82.52 |         2.35 |
|               8 | DHT       | DHT                                  | US       |                3.01 |                     0.08 |    -0.03 |      0.09 |                  64.88 |                        78.39 |         77    |         75.77 |          80.78 |        81.69 |           88.75 |             82.74 |         4.66 |
|               9 | NAT       | NAT                                  | US       |                1.41 |                     0.07 |    -0.03 |      0.13 |                  66.91 |                        77.94 |         80.11 |         77.26 |          78.16 |        72.93 |           87.11 |             69.51 |         4.77 |
|              10 | AVAH      | AVAH                                 | US       |                2.52 |                     0.09 |    -0.08 |     -0.04 |                  74.89 |                        76.6  |         56.41 |         77.06 |          78.01 |        73.56 |           92.63 |             55.41 |         7.63 |
|              11 | BP        | BP                                   | US       |               96.82 |                     0.07 |    -0.07 |     -0    |                  81.04 |                        75.89 |         61.65 |         66.81 |          72.09 |        78.76 |           87.31 |             85.77 |         4.42 |
|              12 | ARGX.BR   | ARGX.BR                              | EUROPE   |               53.51 |                     0.06 |    -0    |     -0.03 |                  67.36 |                        75.58 |         61.72 |         69.16 |          71.56 |        63.64 |           94.31 |             80.22 |         6.01 |
|              13 | SHEL      | SHEL                                 | US       |              233.82 |                     0.05 |    -0.05 |      0.01 |                  82.99 |                        75.08 |         66.92 |         71.03 |          71.43 |        77.41 |           75.29 |             80.41 |         2.96 |
|              14 | BIRG.IR   | BIRG.IR                              | EUROPE   |               18.82 |                     0.02 |     0    |      0.04 |                  48    |                        74.87 |         76.53 |         72.79 |          75.4  |        76.44 |           96.56 |             67.3  |         2.19 |
|              15 | DAR       | DAR                                  | US       |                8.48 |                     0.1  |    -0.08 |     -0.02 |                  67.9  |                        74.83 |         52.62 |         67.51 |          78.15 |        83.75 |           90.03 |             85.9  |         4.61 |
|              16 | DINO      | DINO                                 | US       |               16.54 |                     0.1  |    -0.06 |      0.1  |                  62.23 |                        74.71 |         70.54 |         84.47 |          79.6  |        71.58 |           50.61 |             86.83 |         4.56 |
|              17 | FORTUM.HE | FORTUM.HE                            | EUROPE   |               21.14 |                     0.05 |    -0.01 |      0.16 |                  68.4  |                        74.35 |         80.55 |         68.51 |          60.5  |        54.59 |           69.12 |             66.58 |         4.53 |
|              18 | EQNR      | EQNR                                 | US       |               86.45 |                     0.1  |    -0.1  |     -0.03 |                  72.7  |                        74.2  |         53.51 |         70.83 |          74.48 |        75.99 |           76.44 |             83.94 |         5.54 |
|              19 | MT.AS     | MT.AS                                | EUROPE   |               48.02 |                     0.06 |     0.01 |      0.02 |                  67.56 |                        74.11 |         67.44 |         74.54 |          77.57 |        74.62 |           72.81 |             80.98 |         4.97 |
|              20 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              113.11 |                     0.03 |    -0.03 |      0.16 |                  68.43 |                        73.86 |         76.98 |         75.41 |          72.43 |        76.05 |           65.13 |             80.49 |         3.69 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | COST     | Costco Wholesale Corporation | US       |              347.91 |             41.26 |         38.75 |         34.42 |          43.77 |        50.48 |           77.39 |             44.98 |                26 |          8.5 |             89.81 | long               |                0.42 |                  1.24 |                 1.22 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    253 | ITRG     | ITRG   | OTHER    |                0.51 |             61.03 |         66.25 |         59.04 |          57.33 |        63.01 |           70.5  |             63.59 |             58.16 |         8.15 |             68.32 | short              |                5.23 |                  5.5  |                 5.58 |
|     37 | AMS.SW   | AMS.SW | EUROPE   |                2.25 |             73.8  |         83.2  |         76.64 |          70.97 |        53.91 |           55.69 |             88.41 |             10.8  |         8.59 |             73.14 | short              |                2.73 |                  4.83 |               nan    |
|    200 | VZLA     | VZLA   | OTHER    |                1.33 |             63.08 |         76.65 |         67.31 |          58.85 |        54.24 |           72.79 |            nan    |             23.68 |         8.32 |             61.82 | short              |                5.57 |                  4.49 |               nan    |
|      8 | AMC      | AMC    | US       |                2.31 |             81.16 |         82.1  |         86.82 |          80.23 |        79.36 |           84.64 |             79.8  |            nan    |         9.53 |             65.07 | swing              |                4.97 |                  4.45 |                 4.12 |
|    218 | NEWP     | NEWP   | OTHER    |                1.12 |             62.43 |         69.18 |         66.31 |          58.56 |        44.36 |           46.22 |             37.43 |             10.53 |         7.9  |             68.25 | short              |                3.2  |                  4.2  |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                  | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    630 | FRSH     | FRSH                  | US       |                2.83 |             41.68 |         37.07 |         56.73 |          45.82 |        37.53 |           21.71 |             30.56 |             44.68 |         7.54 |             71.66 | swing              |               -4.72 |                 -3.38 |                -2.58 |
|    704 | MGPI     | MGP Ingredients, Inc. | US       |                0.25 |             25.28 |         22.58 |         20.55 |          27.98 |        36.6  |           43.7  |             26.42 |             45.6  |         6.18 |             84.71 | long               |                0.5  |                 -3.34 |               nan    |
|    432 | TEVA     | TEVA                  | US       |               40.2  |             53.11 |         66.33 |         58.55 |          47.67 |        39.14 |           13.38 |             28.97 |             48.86 |         4.67 |             72.34 | short              |               -1.9  |                 -3.33 |                -3.48 |
|    681 | HOS      | HOS                   | US       |                2.4  |             32.45 |         29.17 |         29.91 |          35    |        36.22 |            6.5  |             32.61 |             58.44 |         5.15 |             63.43 | long               |              -10.62 |                 -2.7  |               nan    |
|    173 | HAFN     | HAFN                  | US       |                4.02 |             64.24 |         73.61 |         63.65 |          62    |        64.82 |           74.78 |             16.33 |             59.19 |         5.6  |             69.68 | short              |               -1.73 |                 -2.51 |                -3.43 |

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
- Event watch (otherwise eligible): **1**
- Final eligible: **707**
- Eligible change vs previous stored run: **-2**

Top exclusion categories:
- liquidity: 235
- price: 183
- market_cap: 165
- price_history: 18
- data_confidence: 10
- asset_type: 1
- delisted: 1
- stale_price: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 1 |  | 2 | main,pullback |
| VLO | 3 |  | 4 |  | 2 | main,pullback |
| CMBT.BR | 4 |  | 3 |  | 2 | main,pullback |
| DELL | 5 |  | 6 |  | 2 | main,pullback |
| FRO | 6 |  | 5 |  | 2 | main,pullback |
| PSX | 7 |  | 2 |  | 2 | main,pullback |
| PBR-A | 22 | 3 | 20 | 3 | 1 | value,quality_value |
| PARR | 31 | 6 | 21 | 4 | 1 | value,quality_value |
| SDF.DE | 149 | 10 | 40 | 5 | 1 | value,quality_value |
| 0Q2N.IL | 161 | 2 |  | 2 | 1 | value,quality_value |
| BION.SW | 204 | 1 | 95 | 1 | 1 | value,quality_value |
| EMBC | 206 | 4 |  | 6 | 1 | value,quality_value |
| GSL | 237 | 5 | 142 | 7 | 1 | value,quality_value |
| IHS | 298 | 9 |  | 9 | 1 | value,quality_value |
| STNE | 508 | 7 | 146 | 8 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (MU, CMBT.BR, DELL, FRO, AMC, HPE)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **4** (CMBT.BR, FRO, DELL, NAT)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | PBR-A | value+pullback | 72.35 | 80.07 | 68.43 | 65.13 | 80.49 | 67.02 | 75.73 |
| 2 | BION.SW | value+pullback | 72.30 | 74.83 | 53.02 | 87.87 | 58.54 | 87.81 | 62.97 |
| 3 | SDF.DE | value+pullback | 71.14 | 59.07 | 69.69 | 90.36 | 59.14 | 82.66 | 65.27 |
| 4 | 0Q2N.IL | value+pullback | 70.42 | 75.93 | 65.06 | 69.91 |  | 79.44 | 64.82 |
| 5 | PARR | value+pullback | 69.86 | 68.48 | 65.86 | 80.43 | 70.33 | 68.78 | 74.58 |
| 6 | PBR | value+pullback | 69.45 | 67.72 | 78.37 | 65.13 | 69.35 | 64.20 | 71.77 |
| 7 | GSL | value+pullback | 67.37 | 76.59 | 59.10 | 75.72 | 30.73 | 75.92 | 61.75 |
| 8 | STNE | value+pullback | 67.04 | 72.17 | 62.40 | 85.87 | 32.65 | 68.19 | 49.36 |
| 9 | BCE | value+pullback | 66.05 | 58.92 | 73.54 | 82.61 | 58.53 | 58.74 | 44.36 |
| 10 | CNC | value+pullback | 64.19 | 72.86 | 69.23 | 51.67 | 65.13 | 53.83 | 60.58 |
| 11 | INVA | value+pullback | 63.48 | 63.55 | 45.55 | 89.38 | 31.43 | 82.37 | 50.51 |
| 12 | WB | value+pullback | 63.16 | 71.35 | 64.82 | 77.05 | 17.78 | 61.08 | 41.09 |
| 13 | UNIT | value+pullback | 62.90 | 80.01 | 70.08 | 63.96 | 29.50 | 44.18 | 43.14 |
| 14 | RCI | value+pullback | 62.50 | 63.99 | 55.10 | 89.32 | 43.13 | 59.10 | 42.67 |
| 15 | HMC | value+pullback | 61.03 | 55.46 | 46.50 | 75.65 | 81.28 | 66.45 | 67.39 |
| 16 | AIR.PA | value+pullback | 60.40 | 61.83 | 70.74 | 65.33 | 48.10 | 47.79 | 51.83 |
| 17 | PERI | value+pullback | 59.38 | 66.05 | 47.60 | 49.66 | 74.85 | 63.66 | 43.14 |
| 18 | ORC | value+pullback | 59.09 | 60.76 | 55.47 | 76.44 | 35.25 | 60.00 | 41.78 |
| 19 | SHELL.AS | pullback | 58.50 | 57.78 | 73.90 | 93.73 | 82.52 | 88.56 | 74.27 |
| 20 | BP | pullback | 58.39 | 56.67 | 81.04 | 87.31 | 85.77 | 82.29 | 69.45 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 72.7 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 11 / 14 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.9 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=5, mega_100b_plus=2
