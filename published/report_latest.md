# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-29

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

- **EUROPE:** 78.2/100
- **OTHER:** 64.5/100
- **US:** 78.6/100

## Main multi-horizon ranking

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE      | HPE      | US       |               73.07 |             84.6  |         89.59 |         87.32 |          81.87 |        73.21 |           73.25 |             81.35 |             53.32 |         6.91 |             72.34 | short              |                3.24 |                  0.96 |               nan    |
|      2 | VLO      | VLO      | US       |               98.58 |             84.4  |         84.03 |         86.39 |          84.77 |        80.99 |           86.72 |             81.4  |             62.54 |         3.63 |             69.68 | swing              |               -1.35 |                  1.42 |                 1.24 |
|      3 | AMC      | AMC      | US       |                2.58 |             84.38 |         87.63 |         91.73 |          81.13 |        80.33 |           84.98 |             79.5  |            nan    |         9.53 |             65.07 | swing              |                8.19 |                  5.1  |                 4.6  |
|      4 | FRO      | FRO      | US       |                9.41 |             82.44 |         82.43 |         83.02 |          82.46 |        81.01 |           92.05 |             65.79 |             63.04 |         5.13 |             73.14 | swing              |               -2.47 |                  0.61 |                 0.54 |
|      5 | CMBT.BR  | CMBT.BR  | EUROPE   |                4.86 |             81.95 |         75.02 |         80.96 |          83.62 |        82.95 |           95.91 |             69.18 |             66.45 |         3.73 |             73.14 | medium             |               -2.23 |                  1.16 |                 1.12 |
|      6 | MU       | MU       | US       |             1046.19 |             81.63 |         77.31 |         72.1  |          86.18 |        85.94 |           95.24 |             83.08 |             74.2  |         8.15 |             73.14 | medium             |                0.86 |                  2.54 |                 1.96 |
|      7 | DHT      | DHT      | US       |                3.1  |             80.98 |         81.26 |         80.87 |          80.12 |        81.08 |           89.58 |             70.36 |             66.37 |         4.5  |             73.14 | short              |               -1.09 |                  0.92 |                 0.57 |
|      8 | P        | P        | US       |               37.9  |             80.72 |         93.86 |         88.64 |          72.8  |        58.62 |           69.48 |             88.87 |             11.12 |         8.23 |             72.68 | short              |                3.35 |                  3.22 |                 2.34 |
|      9 | PSX      | PSX      | US       |               88.92 |             80.38 |         74.66 |         83.36 |          81.72 |        79.04 |           79.91 |             83.26 |             65.89 |         3.85 |             73.14 | swing              |               -3.48 |                  1.06 |                 1.14 |
|     10 | SHELL.AS | SHELL.AS | EUROPE   |              241.21 |             79.64 |         81.73 |         77.99 |          75.87 |        81.28 |           93.03 |             80.18 |             68.02 |         2.48 |             73.14 | short              |                5.48 |                  3.11 |                 2.86 |
|     11 | DELL     | DELL     | US       |              303.67 |             78.93 |         79.5  |         81.83 |          78.36 |        67.46 |           73.58 |             73.56 |             35.16 |         7.82 |             72.23 | swing              |               -4.69 |                 -0.66 |                -0.65 |
|     12 | REP.MC   | REP.MC   | EUROPE   |               32.42 |             78.82 |         81.68 |         81.58 |          76.06 |        71.94 |           58.15 |             83.48 |             74.23 |         3.98 |             73.14 | short              |                4.16 |                  1.92 |                 1.52 |
|     13 | KIN.BR   | KIN.BR   | EUROPE   |                1.35 |             78.36 |         78.61 |         83.7  |          78.1  |        67.99 |           89.21 |             75.18 |             20.59 |         3.66 |             73.14 | swing              |                0.61 |                 -0.07 |                -0.06 |
|     14 | NTAP     | NTAP     | US       |               35.29 |             78.35 |         83.76 |         81.68 |          75.02 |        64.57 |           75.07 |             70.56 |             28.13 |         5.61 |             72.11 | short              |              nan    |                nan    |               nan    |
|     15 | BP       | BP       | US       |              100.56 |             77.83 |         80.88 |         75.03 |          73.73 |        80.63 |           87.83 |             90.51 |             70.08 |         4.5  |             72.34 | short              |               15.6  |                  4.34 |               nan    |
|     16 | SHEL     | SHEL     | US       |              241.8  |             77.73 |         81.74 |         77.49 |          72.71 |        77.97 |           74.3  |             83.48 |             81.04 |         2.98 |             72.8  | short              |               12.63 |                  3.65 |                 2.86 |
|     17 | TRMD     | TRMD     | US       |                3.2  |             77.67 |         78.68 |         76.67 |          76.34 |        81.36 |           84.59 |             46.11 |             87.79 |         5.58 |             73.14 | long               |              nan    |                nan    |               nan    |
|     18 | PBF      | PBF      | US       |                7.75 |             77.56 |         78.6  |         80.62 |          76.52 |        74.4  |           51.5  |             75.18 |             93.01 |         7.63 |             72.68 | swing              |               -1.03 |                  0.94 |                 0.83 |
|     19 | WT       | WT       | US       |                3.2  |             77.04 |         75.98 |         82.62 |          78.09 |        67.31 |           72.91 |             83.16 |             33.64 |         5.78 |             73.14 | swing              |                3.08 |                  2.74 |                 2.41 |
|     20 | SMTC     | SMTC     | US       |               14.34 |             76.66 |         84.32 |         78.12 |          75.19 |        61.53 |           73.42 |             84.52 |             12.91 |         8.51 |             73.14 | short              |                5.82 |                  0.3  |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                2.99 |                  73.97 |                    74.47 |                 76.14 |              74.66 |                86.73 |                   13.27 |           84.64 |             57.9  |       0.873 |         nan |       nan |      nan    |       -77.99 |          2.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              241.21 |                  61.3  |                    72.39 |                 75.95 |              67.85 |                87.22 |                   12.78 |           93.03 |             80.18 |     nan     |         nan |       nan |      nan    |         9.64 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.56 |                  60.88 |                    71.89 |                 75.52 |              67.99 |                83.92 |                   16.08 |           87.83 |             90.51 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.22 |                  76.66 |                    71.86 |                 71.88 |              74.82 |                64.63 |                   35.37 |           62.79 |             79.95 |       0.142 |         nan |       nan |        1.78 |         4.64 |          4.71 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|            3 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    71.85 |                 73.45 |              73.61 |                72.38 |                   27.62 |           75.5  |             67    |       0.605 |         nan |       nan |        4.69 |      -180.79 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            4 | BBWI     | Bath & Body Works, Inc.              | US       |                2.87 |                  75.58 |                    71.37 |                 68.99 |              70.36 |                69.85 |                   30.15 |           77.77 |             33.69 |       0.234 |         nan |       nan |        5.48 |         5.81 |          4.25 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHEL     | SHEL                                 | US       |              241.8  |                  66.49 |                    71.31 |                 72.7  |              70.25 |                77.91 |                   22.09 |           74.3  |             83.48 |     nan     |         nan |       nan |      nan    |         9.32 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.43 |                  68.48 |                    69.77 |                 71.73 |              68.67 |                68.65 |                   31.35 |           80.43 |             70.03 |       0.021 |         nan |       nan |        3.82 |         5.63 |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4856.99 |                  60.87 |                    69.71 |                 71.29 |              64.75 |                75.88 |                   24.12 |           86.5  |             72.59 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                                  | US       |                3.1  |                  61.05 |                    69.26 |                 72.17 |              65.09 |                78.33 |                   21.67 |           89.58 |             70.36 |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              173.66 |                  65.98 |                    69.26 |                 70    |              69.43 |                74.49 |                   25.51 |           65.45 |             85.19 |     nan     |         nan |       nan |      nan    |         8.57 |         11.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | EMBC     | Embecta Corp.                        | US       |                0.3  |                  73.04 |                    68.58 |                 68.48 |              69.66 |                59.04 |                   40.96 |           68.38 |             64.44 |       0.411 |         nan |       nan |        5.77 |         3.36 |          4.03 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAA      | PAA                                  | US       |               15.21 |                  56.83 |                    68.56 |                 72.2  |              64.08 |                85.2  |                   14.8  |           88.44 |             78.23 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1466.62 |                  60.81 |                    68.3  |                 68.91 |              62.37 |                78.45 |                   21.55 |           92.29 |             44.71 |       0.018 |         nan |       nan |       32.61 |        18.04 |         44.53 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EC       | EC                                   | US       |               30.17 |                  65.75 |                    68.23 |                 68.85 |              68.33 |                71.47 |                   28.53 |           65.39 |             81.29 |     nan     |         nan |       nan |      nan    |         9.04 |          8.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.86 |                  56.23 |                    68.03 |                 72.05 |              62.28 |                82.64 |                   17.36 |           95.91 |             69.18 |     nan     |         nan |       nan |      nan    |         9.2  |          6.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | STNE     | StoneCo Ltd.                         | OTHER    |                1.88 |                  68.64 |                    67.48 |                 67.4  |              64.89 |                68    |                   32    |           85.87 |             32.34 |       0.636 |         nan |       nan |        1.6  |         4.11 |          3.54 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           10 | 0Q2N.IL  | K+S Aktiengesellschaft               | OTHER    |                3.07 |                  68.5  |                    67.42 |                 66.55 |              68.75 |                69.74 |                   30.26 |           61.12 |            nan    |       0.242 |         nan |       nan |        1.54 |       nan    |          2.86 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.95 |                  57.03 |                    67.21 |                 70.65 |              61.51 |                82.04 |                   17.96 |           96.6  |             56.84 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.41 |                  57.84 |                    67.08 |                 70.43 |              62.05 |                76.83 |                   23.17 |           92.05 |             65.79 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                        | EUROPE   |                2.99 |                  73.97 |                    74.47 |                 76.14 |              74.66 |                86.73 |                   13.27 |           84.64 |             57.9  |       0.873 |         nan |       nan |      nan    |       -77.99 |          2.09 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              241.21 |                  61.3  |                    72.39 |                 75.95 |              67.85 |                87.22 |                   12.78 |           93.03 |             80.18 |     nan     |         nan |       nan |      nan    |         9.64 |         10.65 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP       | BP                                   | US       |              100.56 |                  60.88 |                    71.89 |                 75.52 |              67.99 |                83.92 |                   16.08 |           87.83 |             90.51 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.76 |                  74.83 |                    71.85 |                 73.45 |              73.61 |                72.38 |                   27.62 |           75.5  |             67    |       0.605 |         nan |       nan |        4.69 |      -180.79 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHEL     | SHEL                                 | US       |              241.8  |                  66.49 |                    71.31 |                 72.7  |              70.25 |                77.91 |                   22.09 |           74.3  |             83.48 |     nan     |         nan |       nan |      nan    |         9.32 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                  | US       |               15.21 |                  56.83 |                    68.56 |                 72.2  |              64.08 |                85.2  |                   14.8  |           88.44 |             78.23 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.1  |                  61.05 |                    69.26 |                 72.17 |              65.09 |                78.33 |                   21.67 |           89.58 |             70.36 |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.86 |                  56.23 |                    68.03 |                 72.05 |              62.28 |                82.64 |                   17.36 |           95.91 |             69.18 |     nan     |         nan |       nan |      nan    |         9.2  |          6.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              112.22 |                  76.66 |                    71.86 |                 71.88 |              74.82 |                64.63 |                   35.37 |           62.79 |             79.95 |       0.142 |         nan |       nan |        1.78 |         4.64 |          4.71 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|            5 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.43 |                  68.48 |                    69.77 |                 71.73 |              68.67 |                68.65 |                   31.35 |           80.43 |             70.03 |       0.021 |         nan |       nan |        3.82 |         5.63 |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | NVDA     | NVIDIA Corporation                   | US       |             4856.99 |                  60.87 |                    69.71 |                 71.29 |              64.75 |                75.88 |                   24.12 |           86.5  |             72.59 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BIRG.IR  | BIRG.IR                              | EUROPE   |               18.95 |                  57.03 |                    67.21 |                 70.65 |              61.51 |                82.04 |                   17.96 |           96.6  |             56.84 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                  | US       |               14.59 |                  56.38 |                    67.02 |                 70.45 |              62.7  |                80.86 |                   19.14 |           86.49 |             75.53 |     nan     |         nan |       nan |      nan    |        10.25 |         22.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.41 |                  57.84 |                    67.08 |                 70.43 |              62.05 |                76.83 |                   23.17 |           92.05 |             65.79 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              173.66 |                  65.98 |                    69.26 |                 70    |              69.43 |                74.49 |                   25.51 |           65.45 |             85.19 |     nan     |         nan |       nan |      nan    |         8.57 |         11.27 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                                   | US       |             1046.19 |                  48.79 |                    64.34 |                 69.93 |              57.47 |                77.99 |                   22.01 |           95.24 |             83.08 |     nan     |         nan |       nan |      nan    |         6.53 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                               | EUROPE   |               24.36 |                  54.92 |                    65.74 |                 69.42 |              59.62 |                81.29 |                   18.71 |           97.37 |             54.44 |     nan     |         nan |       nan |      nan    |        11.73 |         12.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | BBWI     | Bath & Body Works, Inc.              | US       |                2.87 |                  75.58 |                    71.37 |                 68.99 |              70.36 |                69.85 |                   30.15 |           77.77 |             33.69 |       0.234 |         nan |       nan |        5.48 |         5.81 |          4.25 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|            8 | AVGO     | Broadcom Inc.                        | US       |             1466.62 |                  60.81 |                    68.3  |                 68.91 |              62.37 |                78.45 |                   21.55 |           92.29 |             44.71 |       0.018 |         nan |       nan |       32.61 |        18.04 |         44.53 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EC       | EC                                   | US       |               30.17 |                  65.75 |                    68.23 |                 68.85 |              68.33 |                71.47 |                   28.53 |           65.39 |             81.29 |     nan     |         nan |       nan |      nan    |         9.04 |          8.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name              | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO               | US       |               98.58 |                     0.06 |    -0.01 |      0.11 |                  72.11 |                        83.57 |         84.03 |         86.39 |          84.77 |        80.99 |           86.72 |             81.4  |         3.63 |
|               2 | FRO       | FRO               | US       |                9.41 |                     0.06 |    -0.03 |      0.16 |                  74.92 |                        81.03 |         82.43 |         83.02 |          82.46 |        81.01 |           92.05 |             65.79 |         5.13 |
|               3 | SMTC      | SMTC              | US       |               14.34 |                     0.06 |    -0.01 |      0.33 |                  74.94 |                        80.76 |         84.32 |         78.12 |          75.19 |        61.53 |           73.42 |             84.52 |         8.51 |
|               4 | DHT       | DHT               | US       |                3.1  |                     0.06 |    -0.02 |      0.11 |                  75.58 |                        80.44 |         81.26 |         80.87 |          80.12 |        81.08 |           89.58 |             70.36 |         4.5  |
|               5 | PSX       | PSX               | US       |               88.92 |                     0.08 |    -0.03 |      0.04 |                  67.38 |                        80.26 |         74.66 |         83.36 |          81.72 |        79.04 |           79.91 |             83.26 |         3.85 |
|               6 | CMBT.BR   | CMBT.BR           | EUROPE   |                4.86 |                     0.07 |    -0.02 |      0.07 |                  65.44 |                        79.86 |         75.02 |         80.96 |          83.62 |        82.95 |           95.91 |             69.18 |         3.73 |
|               7 | MU        | MU                | US       |             1046.19 |                     0.04 |     0.01 |      0.13 |                  57.81 |                        78.84 |         77.31 |         72.1  |          86.18 |        85.94 |           95.24 |             83.08 |         8.15 |
|               8 | KRX.IR    | KRX.IR            | EUROPE   |               18.11 |                     0.05 |     0.01 |     -0.01 |                  61.78 |                        78.11 |         71.14 |         76.58 |          74.75 |        68.7  |           97.8  |             73.27 |         5.63 |
|               9 | DELL      | DELL              | US       |              303.67 |                     0.08 |    -0.06 |      0.19 |                  73.73 |                        77.72 |         79.5  |         81.83 |          78.36 |        67.46 |           73.58 |             73.56 |         7.82 |
|              10 | NAT       | NAT               | US       |                1.45 |                     0.06 |    -0.03 |      0.2  |                  78.02 |                        76.52 |         80.9  |         76.22 |          73.73 |        70.72 |           87.56 |             45.66 |         4.7  |
|              11 | WT        | WT                | US       |                3.2  |                     0.03 |     0.01 |     -0.02 |                  53.25 |                        76.35 |         75.98 |         82.62 |          78.09 |        67.31 |           72.91 |             83.16 |         5.78 |
|              12 | C5H.IR    | C5H.IR            | EUROPE   |                1.71 |                     0.02 |     0.02 |      0.07 |                  46.25 |                        75.43 |         81.64 |         72.21 |          73.87 |        76.41 |           97.8  |             54.11 |         2.75 |
|              13 | PAA       | PAA               | US       |               15.21 |                     0.06 |    -0.02 |     -0.04 |                  73.01 |                        75.38 |         61.27 |         70.02 |          75.07 |        78.27 |           88.44 |             78.23 |         2.02 |
|              14 | TRMD-A.CO | TRMD-A.CO         | EUROPE   |                3.2  |                     0.07 |     0.01 |      0.11 |                  60.17 |                        75.15 |         82.6  |         77.46 |          75.04 |        74.77 |           68.22 |             74.56 |         5.37 |
|              15 | EQNR      | EQNR              | US       |               88.07 |                     0.08 |    -0.01 |      0.02 |                  59.3  |                        74.36 |         70.25 |         75.45 |          74.32 |        76.14 |           74.98 |             84.94 |         5.68 |
|              16 | TRMD      | TRMD              | US       |                3.2  |                     0.07 |    -0.05 |      0.17 |                  72.74 |                        74.09 |         78.68 |         76.67 |          76.34 |        81.36 |           84.59 |             46.11 |         5.58 |
|              17 | NWL.MI    | NewPrinces S.p.A. | EUROPE   |                0.76 |                     0.04 |    -0.01 |      0.17 |                  66.22 |                        73.69 |         77.21 |         63.18 |          60.09 |        69.77 |           75.5  |             67    |         5.7  |
|              18 | ARGX.BR   | ARGX.BR           | EUROPE   |               53.43 |                     0.06 |    -0    |     -0.04 |                  65.73 |                        73.55 |         62.02 |         66.43 |          68.41 |        61.97 |           92.51 |             79.79 |         6.18 |
|              19 | BEN       | BEN               | US       |               14.59 |                     0.06 |    -0.03 |     -0.06 |                  76.66 |                        72.92 |         53.17 |         65.59 |          77.98 |        79.23 |           86.49 |             75.53 |         3.28 |
|              20 | UGP       | UGP               | US       |                6.68 |                     0.07 |    -0.06 |      0.11 |                  77.84 |                        72.76 |         67.75 |         77.91 |          72.29 |        67.95 |           58.97 |             68.91 |         4.99 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | JPM      | JPMorgan Chase & Co. | US       |              786.36 |             50.32 |         47.61 |         55.56 |          53.03 |         45.5 |           49.09 |             67.56 |             21.01 |         3.03 |             81.49 | swing              |               -3.99 |                 -0.7  |                -0.48 |
|    nan | TLRY     | Tilray Brands, Inc.  | OTHER    |                0.5  |             26.93 |         26.95 |         21.93 |          26.91 |         34.3 |           44.15 |             32.01 |             32.86 |         8.94 |             77.79 | long               |                1.74 |                 -0.12 |                 0.03 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      3 | AMC      | AMC    | US       |                2.58 |             84.38 |         87.63 |         91.73 |          81.13 |        80.33 |           84.98 |             79.5  |            nan    |         9.53 |             65.07 | swing              |                8.19 |                  5.1  |                 4.6  |
|    126 | NEWP     | NEWP   | OTHER    |                1.04 |             65.95 |         59.85 |         70.36 |          71.29 |        61.54 |           81.04 |             60.41 |             13.33 |         8.06 |             68.25 | medium             |                6.72 |                  4.9  |               nan    |
|     15 | BP       | BP     | US       |              100.56 |             77.83 |         80.88 |         75.03 |          73.73 |        80.63 |           87.83 |             90.51 |             70.08 |         4.5  |             72.34 | short              |               15.6  |                  4.34 |               nan    |
|    279 | SPM.MI   | SPM.MI | EUROPE   |                8.64 |             59.14 |         63.42 |         58.3  |          59.98 |        50.91 |          nan    |             59.91 |             25.9  |         3.84 |             70.3  | short              |               10.48 |                  4.11 |                 3.7  |
|    419 | ITRG     | ITRG   | OTHER    |                0.46 |             53.79 |         38.9  |         54.03 |          53.55 |        57.62 |           65.38 |             63.66 |             48.38 |         8.26 |             68.32 | long               |               -2.01 |                  4.05 |                 4.49 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    664 | PAH3.DE  | PAH3.DE | EUROPE   |                7.72 |             33.95 |         28.19 |         29.9  |          38    |        62.34 |          nan    |             27.58 |             96.29 |         5.23 |             70.3  | long               |              -11.4  |                 -3.51 |                -2.94 |
|    648 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.09 |             37.13 |         20.47 |         31.29 |          42.97 |        73.66 |          nan    |            nan    |             98.33 |         5.3  |             60    | long               |               -0.48 |                 -3.12 |                -3.24 |
|    637 | TIT.MI   | TIT.MI  | EUROPE   |               15.12 |             38.71 |         37.85 |         39.57 |          42.31 |        31.78 |           14.71 |             54.46 |             18.45 |         2.25 |             71.32 | medium             |              -10.72 |                 -3.11 |                -2.85 |
|    464 | ESTC     | ESTC    | US       |                8.11 |             51.83 |         50.56 |         66.59 |          53.09 |        38.27 |           25.73 |             51.16 |             26.35 |         8.49 |             72.11 | swing              |              nan    |                 -2.93 |                -2.53 |
|    573 | NCNO     | NCNO    | US       |                1.73 |             45.44 |         29.18 |         52.92 |          47.33 |        43.56 |           22.69 |             53.83 |             64.08 |         7.74 |             71.66 | swing              |               -6.01 |                 -2.88 |                -2.22 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91

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
- Excluded by hard/data filters: **298**
- Event watch (otherwise eligible): **2**
- Final eligible: **700**
- Eligible change vs previous stored run: **-9**

Top exclusion categories:
- liquidity: 242
- price: 187
- market_cap: 158
- price_history: 21
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| VLO | 2 |  | 1 |  | 2 | main,pullback |
| FRO | 4 |  | 2 |  | 2 | main,pullback |
| CMBT.BR | 5 |  | 6 |  | 2 | main,pullback |
| MU | 6 |  | 7 |  | 2 | main,pullback |
| DHT | 7 |  | 4 |  | 2 | main,pullback |
| PSX | 9 |  | 5 |  | 2 | main,pullback |
| NVDA | 43 | 6 |  | 5 | 1 | value,quality_value |
| PBR-A | 46 | 2 | 22 | 3 | 1 | value,quality_value |
| PARR | 65 | 5 | 45 | 4 | 1 | value,quality_value |
| NWL.MI | 111 | 3 | 17 | 2 | 1 | value,quality_value |
| EMBC | 132 | 7 |  | 8 | 1 | value,quality_value |
| BION.SW | 205 | 1 | 118 | 1 | 1 | value,quality_value |
| AVGO | 430 | 8 | 115 | 7 | 1 | value,quality_value |
| STNE | 611 | 9 | 352 | 10 | 1 | value,quality_value |
| BBWI | 639 | 4 |  | 6 | 1 | value,quality_value |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **1** (SHELL.AS)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.77 | 73.97 | 58.97 | 84.64 | 57.90 | 86.73 | 62.06 |
| 2 | AVGO | value+pullback | 72.49 | 60.81 | 80.97 | 92.29 | 44.71 | 78.45 | 53.47 |
| 3 | NWL.MI | value+pullback | 71.50 | 74.83 | 66.22 | 75.50 | 67.00 | 72.38 | 66.47 |
| 4 | PBR-A | value+pullback | 70.16 | 76.66 | 67.29 | 62.79 | 79.95 | 64.63 | 73.02 |
| 5 | GSL | value+pullback | 69.31 | 67.77 | 81.16 | 73.55 | 30.34 | 73.11 | 61.11 |
| 6 | PARR | value+pullback | 67.90 | 68.48 | 58.23 | 80.43 | 70.03 | 68.65 | 70.53 |
| 7 | ETG | value+pullback | 67.18 | 55.45 | 67.96 | 68.22 | 77.94 | 77.62 | 59.95 |
| 8 | WB | value+pullback | 66.60 | 71.10 | 81.10 | 71.78 | 17.59 | 62.35 | 35.96 |
| 9 | PBR | value+pullback | 66.15 | 66.52 | 68.35 | 62.79 | 72.04 | 62.42 | 70.20 |
| 10 | VIPS | value+pullback | 64.69 | 64.89 | 71.35 | 88.16 | 24.82 | 58.41 | 44.52 |
| 11 | MAGN | value+pullback | 63.85 | 69.00 | 67.78 | 68.70 | 33.60 | 62.71 | 51.78 |
| 12 | VOLV-B.ST | value+pullback | 63.61 | 66.20 | 71.99 | 55.10 | 63.20 | 55.85 | 54.28 |
| 13 | GAB | value+pullback | 63.53 | 57.19 | 70.56 | 54.76 | 77.94 | 63.63 | 50.73 |
| 14 | STNE | value+pullback | 63.41 | 68.64 | 52.43 | 85.87 | 32.34 | 68.00 | 42.06 |
| 15 | JD | value+pullback | 62.51 | 60.01 | 75.90 | 65.58 | 46.21 | 55.36 | 46.86 |
| 16 | AVK | value+pullback | 61.98 | 58.79 | 73.47 | 62.58 | 49.54 | 58.17 | 46.38 |
| 17 | 0Q2N.IL | value+pullback | 61.53 | 68.50 | 51.47 | 61.12 |  | 69.74 | 58.68 |
| 18 | IRS | value+pullback | 61.49 | 68.37 | 61.53 | 62.42 | 40.67 | 60.82 | 43.80 |
| 19 | ALL-PH | value+pullback | 60.00 | 61.06 | 59.58 | 70.11 | 41.06 | 60.81 | 50.15 |
| 20 | WKC | value+pullback | 59.84 | 55.98 | 48.10 | 63.66 | 78.08 | 68.34 | 64.05 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 9 / 1 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 19 / 6 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 73.1 | 37 / 13 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
