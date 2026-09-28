# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-09-28

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

- **EUROPE:** 77.6/100
- **OTHER:** 67.6/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             84.15 |         89.74 |         87.04 |          81.25 |        72.29 |           70.55 |             81.43 |             53.85 |         6.89 |             72.34 | short              |                2.79 |                  0.87 |               nan    |
|      2 | MU        | MU        | US       |             1074.59 |             83.15 |         80.35 |         73.28 |          86.23 |        85.95 |           95    |             82.41 |             74.75 |         8.07 |             73.14 | medium             |                2.39 |                  2.85 |                 2.19 |
|      3 | DELL      | DELL      | US       |              314.64 |             82.88 |         86.27 |         85.65 |          80.12 |        68.12 |           71.44 |             82.1  |             36.01 |         7.81 |             72.23 | short              |               -0.74 |                  0.13 |                -0.06 |
|      4 | VLO       | VLO       | US       |               98.01 |             82.75 |         79.71 |         86.02 |          84.52 |        80.98 |           84.99 |             80.78 |             65.46 |         3.55 |             69.68 | swing              |               -3    |                  1.09 |                 0.99 |
|      5 | FRO       | FRO       | US       |                9.34 |             81.65 |         79.84 |         82.18 |          82.2  |        81.11 |           90.7  |             66    |             65.63 |         5.05 |             73.14 | medium             |               -3.27 |                  0.45 |                 0.42 |
|      6 | AMC       | AMC       | US       |                2.31 |             81.34 |         82.1  |         86.49 |          80.57 |        79.74 |           85.71 |             79.56 |            nan    |         9.48 |             65.07 | swing              |                5.15 |                  4.49 |                 4.14 |
|      7 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.89 |             81.13 |         75.43 |         80.76 |          82.77 |        81.51 |           95.68 |             68.95 |             62.85 |         3.67 |             73.14 | medium             |               -3.05 |                  0.99 |                 1    |
|      8 | PSX       | PSX       | US       |               89.72 |             80.74 |         75.45 |         84.82 |          82.45 |        79.03 |           78.15 |             86.23 |             66.96 |         3.78 |             73.14 | swing              |               -3.12 |                  1.13 |                 1.19 |
|      9 | P         | P         | US       |               36.91 |             80.29 |         93.96 |         88.04 |          72.54 |        58.68 |           68.31 |             88.88 |             13.45 |         8.12 |             72.68 | short              |                2.92 |                  3.13 |                 2.28 |
|     10 | DHT       | DHT       | US       |                3.09 |             79.73 |         78.05 |         79.73 |          79.74 |        81.01 |           87.99 |             70.5  |             69.33 |         4.46 |             73.14 | long               |               -2.33 |                  0.67 |                 0.39 |
|     11 | SMTC      | SMTC      | US       |               14.96 |             79.35 |         85.41 |         82.34 |          76.37 |        62.3  |           72.13 |             84.95 |             15.08 |         8.41 |             73.14 | short              |                8.51 |                  0.84 |               nan    |
|     12 | REP.MC    | REP.MC    | EUROPE   |               33.31 |             78.66 |         85.27 |         81.94 |          75.39 |        70.93 |           59.39 |             83.68 |             69.71 |         3.87 |             73.14 | short              |                4.01 |                  1.89 |                 1.5  |
|     13 | SHELL.AS  | SHELL.AS  | EUROPE   |              244.3  |             78.36 |         84.44 |         77.44 |          74.18 |        79.29 |           92.58 |             79.77 |             63.11 |         2.38 |             73.14 | short              |                4.21 |                  2.86 |                 2.67 |
|     14 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             76.74 |         78.43 |         80.91 |          75.06 |        66.01 |           88.96 |             65.5  |             20.33 |         3.65 |             73.14 | swing              |               -1    |                 -0.39 |                -0.3  |
|     15 | OMV.VI    | OMV.VI    | EUROPE   |               23.77 |             76.62 |         79.04 |         79.8  |          74.21 |        70.5  |           62.31 |             85.98 |             65.94 |         1.94 |             72.34 | swing              |                5.41 |                  1.21 |                 0.69 |
|     16 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.23 |             76.16 |         78.56 |         78.08 |          74.23 |        73.13 |           68.75 |             75.04 |             72.17 |         5.47 |             73.14 | short              |                5.02 |                  1.23 |               nan    |
|     17 | SHEL      | SHEL      | US       |              240.17 |             76.09 |         78.64 |         75.19 |          71.07 |        76.99 |           72.43 |             80.15 |             82.78 |         2.94 |             72.8  | short              |               10.99 |                  3.32 |                 2.61 |
|     18 | OKTA      | OKTA      | US       |               30    |             75.36 |         85.07 |         79.26 |          71.47 |        58.94 |           70.07 |             59.58 |             16.75 |         7.85 |             71.77 | short              |               -3.16 |                  0.32 |                 0.47 |
|     19 | TRMD      | TRMD      | US       |                3.1  |             75.11 |         74.84 |         74.17 |          75.37 |        81.3  |           83.74 |             46.25 |             90.13 |         5.5  |             73.14 | long               |              nan    |                nan    |               nan    |
|     20 | EQNR      | EQNR      | US       |               87.93 |             74.7  |         64.38 |         74.96 |          74.44 |        76.34 |           73.85 |             85.57 |             65.69 |         5.61 |             72.11 | long               |                1.38 |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.05 |                  75.11 |                    77.86 |                 78.27 |              77.53 |                87.21 |                   12.79 |           78.6  |            nan    |       0.243 |         nan |       nan |        1.54 |       nan    |          2.84 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | BION.SW   | BB Biotech AG                        | EUROPE   |                2.98 |                  75.25 |                    74.72 |                 76.11 |              74.93 |                86.19 |                   13.81 |           85.87 |             52.38 |       0.878 |         nan |       nan |      nan    |       -77.53 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            3 | BBWI      | Bath & Body Works, Inc.              | US       |                2.92 |                  75.58 |                    71.47 |                 69.11 |              70.47 |                70.09 |                   29.91 |           77.77 |             34.3  |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|            4 | NVDA      | NVIDIA Corporation                   | US       |             4777.92 |                  61.64 |                    71    |                 72.84 |              66.21 |                77.16 |                   22.84 |           86.5  |             79.39 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHEL      | SHEL                                 | US       |              240.17 |                  67.04 |                    70.68 |                 71.7  |              69.96 |                75.99 |                   24.01 |           72.43 |             80.15 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              244.3  |                  58.11 |                    70.4  |                 74.32 |              65.49 |                87.05 |                   12.95 |           92.58 |             79.77 |     nan     |         nan |       nan |      nan    |         9.76 |         10.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               58.82 |                  79.58 |                    70.1  |                 66.55 |              73.79 |                56.29 |                   43.71 |           51.02 |             63.59 |       0.036 |         nan |       nan |       15.57 |        13.12 |         18.55 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|            6 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  76.2  |                    70.07 |                 68.89 |              71.64 |                76.17 |                   23.83 |           74.29 |             30.67 |       0.081 |         nan |       nan |        3.82 |         5    |          4.32 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            7 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.41 |                  68.48 |                    69.82 |                 71.8  |              68.73 |                68.81 |                   31.19 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | EMBC      | Embecta Corp.                        | US       |                0.29 |                  72.61 |                    69.22 |                 69.44 |              69.98 |                61.94 |                   38.06 |           70.56 |             65.53 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            9 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.47 |                  79.55 |                    69.12 |                 67.33 |              74.48 |                51.1  |                   48.9  |           47.39 |             80.13 |       0.143 |         nan |       nan |        1.78 |         4.61 |          4.68 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                                  | US       |                3.09 |                  60.9  |                    68.83 |                 71.62 |              64.87 |                77.65 |                   22.35 |           87.99 |             70.5  |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA                               | EUROPE   |              178.94 |                  64.69 |                    68.67 |                 69.64 |              68.57 |                74.89 |                   25.11 |           66.11 |             85.08 |     nan     |         nan |       nan |      nan    |         8.83 |         11.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                                   | US       |               99.96 |                  56.38 |                    68.67 |                 72.65 |              64.5  |                82.67 |                   17.33 |           85.37 |             90.21 |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AVGO      | Broadcom Inc.                        | US       |             1480.63 |                  60.81 |                    68.35 |                 68.98 |              62.43 |                78.59 |                   21.41 |           92.29 |             45.01 |       0.018 |         nan |       nan |       32.9  |        18.2  |         44.94 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | PAA       | PAA                                  | US       |               15.15 |                  56.8  |                    67.87 |                 71.27 |              63.8  |                83.77 |                   16.23 |           85.65 |             78.2  |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | STNE      | StoneCo Ltd.                         | OTHER    |                1.89 |                  68.99 |                    67.56 |                 67.51 |              64.92 |                66.64 |                   33.36 |           86.35 |             32.54 |       0.635 |         nan |       nan |        1.61 |         4.12 |          3.54 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | FRO       | FRO                                  | US       |                9.34 |                  58.92 |                    67.44 |                 70.55 |              62.77 |                76.38 |                   23.62 |           90.7  |             66    |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.62 |                  62.72 |                    67.16 |                 68.59 |              63.94 |                76.35 |                   23.65 |           85.4  |             50.43 |     nan     |         nan |       nan |      nan    |         8.69 |          7.68 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN       | BEN                                  | US       |               14.75 |                  57.08 |                    66.87 |                 70    |              63.01 |                79.78 |                   20.22 |           84.05 |             75.58 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | 0Q2N.IL  | K+S Aktiengesellschaft     | OTHER    |                3.05 |                  75.11 |                    77.86 |                 78.27 |              77.53 |                87.21 |                   12.79 |           78.6  |            nan    |       0.243 |         nan |       nan |        1.54 |       nan    |          2.84 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | BION.SW  | BB Biotech AG              | EUROPE   |                2.98 |                  75.25 |                    74.72 |                 76.11 |              74.93 |                86.19 |                   13.81 |           85.87 |             52.38 |       0.878 |         nan |       nan |      nan    |       -77.53 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              244.3  |                  58.11 |                    70.4  |                 74.32 |              65.49 |                87.05 |                   12.95 |           92.58 |             79.77 |     nan     |         nan |       nan |      nan    |         9.76 |         10.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | NVDA     | NVIDIA Corporation         | US       |             4777.92 |                  61.64 |                    71    |                 72.84 |              66.21 |                77.16 |                   22.84 |           86.5  |             79.39 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                         | US       |               99.96 |                  56.38 |                    68.67 |                 72.65 |              64.5  |                82.67 |                   17.33 |           85.37 |             90.21 |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                  68.48 |                    69.82 |                 71.8  |              68.73 |                68.81 |                   31.19 |           80.43 |             70.33 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHEL     | SHEL                       | US       |              240.17 |                  67.04 |                    70.68 |                 71.7  |              69.96 |                75.99 |                   24.01 |           72.43 |             80.15 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                        | US       |                3.09 |                  60.9  |                    68.83 |                 71.62 |              64.87 |                77.65 |                   22.35 |           87.99 |             70.5  |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                        | US       |               15.15 |                  56.8  |                    67.87 |                 71.27 |              63.8  |                83.77 |                   16.23 |           85.65 |             78.2  |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.89 |                  54.1  |                    66.72 |                 70.99 |              60.71 |                82.55 |                   17.45 |           95.68 |             68.95 |     nan     |         nan |       nan |      nan    |         9.26 |          6.48 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                9.34 |                  58.92 |                    67.44 |                 70.55 |              62.77 |                76.38 |                   23.62 |           90.7  |             66    |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.75 |                  57.08 |                    66.87 |                 70    |              63.01 |                79.78 |                   20.22 |           84.05 |             75.58 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.94 |                  55.61 |                    66.38 |                 69.98 |              60.52 |                82.07 |                   17.93 |           96.37 |             57.04 |     nan     |         nan |       nan |      nan    |        10.94 |         14.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                         | US       |             1074.59 |                  49.26 |                    64.48 |                 69.95 |              57.72 |                77.82 |                   22.18 |           95    |             82.41 |     nan     |         nan |       nan |      nan    |         6.76 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                     | EUROPE   |              178.94 |                  64.69 |                    68.67 |                 69.64 |              68.57 |                74.89 |                   25.11 |           66.11 |             85.08 |     nan     |         nan |       nan |      nan    |         8.83 |         11.61 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | EMBC     | Embecta Corp.              | US       |                0.29 |                  72.61 |                    69.22 |                 69.44 |              69.98 |                61.94 |                   38.06 |           70.56 |             65.53 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | BBWI     | Bath & Body Works, Inc.    | US       |                2.92 |                  75.58 |                    71.47 |                 69.11 |              70.47 |                70.09 |                   29.91 |           77.77 |             34.3  |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|           10 | AVGO     | Broadcom Inc.              | US       |             1480.63 |                  60.81 |                    68.35 |                 68.98 |              62.43 |                78.59 |                   21.41 |           92.29 |             45.01 |       0.018 |         nan |       nan |       32.9  |        18.2  |         44.94 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|            6 | GSL      | Global Ship Lease, Inc.    | OTHER    |                1.4  |                  76.2  |                    70.07 |                 68.89 |              71.64 |                76.17 |                   23.83 |           74.29 |             30.67 |       0.081 |         nan |       nan |        3.82 |         5    |          4.32 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | A5G.IR   | A5G.IR                     | EUROPE   |               24.43 |                  54.26 |                    65.15 |                 68.83 |              59.09 |                80.93 |                   19.07 |           96.38 |             54.55 |     nan     |         nan |       nan |      nan    |        11.76 |         12.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name               | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:-------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO                | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.76 |         79.71 |         86.02 |          84.52 |        80.98 |           84.99 |             80.78 |         3.55 |
|               2 | PSX       | PSX                | US       |               89.72 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.24 |         75.45 |         84.82 |          82.45 |        79.03 |           78.15 |             86.23 |         3.78 |
|               3 | FRO       | FRO                | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        81.34 |         79.84 |         82.18 |          82.2  |        81.11 |           90.7  |             66    |         5.05 |
|               4 | CMBT.BR   | CMBT.BR            | EUROPE   |                4.89 |                     0.06 |    -0.02 |      0.08 |                  72.19 |                        80.69 |         75.43 |         80.76 |          82.77 |        81.51 |           95.68 |             68.95 |         3.67 |
|               5 | DHT       | DHT                | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.62 |         78.05 |         79.73 |          79.74 |        81.01 |           87.99 |             70.5  |         4.46 |
|               6 | DELL      | DELL               | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        79.68 |         86.27 |         85.65 |          80.12 |        68.12 |           71.44 |             82.1  |         7.81 |
|               7 | BP        | BP                 | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        78.58 |         74.76 |         73.34 |          72.84 |        79.88 |           85.37 |             90.21 |         4.46 |
|               8 | CIRSA.MC  | CIRSA.MC           | EUROPE   |                3.19 |                     0.04 |    -0.02 |      0.37 |                  69.93 |                        76.97 |         82.43 |         77.85 |          68.96 |        68.82 |           82.59 |             58.32 |         5.27 |
|               9 | TRMD-A.CO | TRMD-A.CO          | EUROPE   |                3.23 |                     0.06 |    -0.05 |      0.12 |                  80.31 |                        76.33 |         78.56 |         78.08 |          74.23 |        73.13 |           68.75 |             75.04 |         5.47 |
|              10 | C5H.IR    | C5H.IR             | EUROPE   |                1.7  |                     0.03 |     0.02 |      0.11 |                  51.13 |                        75.9  |         80.95 |         70.7  |          72.45 |        75.23 |           97.87 |             54.57 |         2.71 |
|              11 | NAT       | NAT                | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        75.54 |         77.56 |         75.03 |          73.35 |        70.57 |           86.7  |             45.61 |         4.62 |
|              12 | EQNR      | EQNR               | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        75.48 |         64.38 |         74.96 |          74.44 |        76.34 |           73.85 |             85.57 |         5.61 |
|              13 | PAA       | PAA                | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.32 |         55.67 |         68.14 |          73.89 |        77.25 |           85.65 |             78.2  |         2.03 |
|              14 | TEAM      | TEAM               | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        74.3  |         68.78 |         84.25 |          67.29 |        48.58 |           41.39 |             90.96 |         9.48 |
|              15 | DNORD.CO  | DNORD.CO           | EUROPE   |                1.38 |                     0.06 |    -0.06 |      0.05 |                  85.9  |                        73.88 |         67.11 |         71.96 |          67.15 |        59.86 |           79.94 |             60.16 |         4.77 |
|              16 | SHEL      | SHEL               | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.75 |         78.64 |         75.19 |          71.07 |        76.99 |           72.43 |             80.15 |         2.94 |
|              17 | NESTE.HE  | NESTE.HE           | EUROPE   |               26.41 |                     0.04 |     0.01 |      0.08 |                  58.33 |                        73.69 |         79.42 |         76.29 |          70.28 |        61.7  |           61.42 |             86.31 |         4.9  |
|              18 | ARGX.BR   | ARGX.BR            | EUROPE   |               52.71 |                     0.08 |    -0.03 |     -0.04 |                  66.06 |                        73.66 |         56.12 |         66.02 |          68.5  |        61.89 |           92.88 |             81.15 |         6.11 |
|              19 | GTLB      | GTLB               | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        73.04 |         69.76 |         79.09 |          63.58 |        48.81 |           55.47 |             72.52 |         8.35 |
|              20 | NVDA      | NVIDIA Corporation | US       |             4777.92 |                     0.02 |     0.01 |     -0.01 |                  46.65 |                        72.98 |         72.31 |         73.55 |          71.75 |        69.24 |           86.5  |             79.39 |         5.82 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                0.51 |             30.09 |         32.65 |         22.32 |          27.53 |        35.62 |           47.27 |             32.19 |             33.81 |         8.89 |             78.44 | long               |                 4.9 |                  0.51 |                  0.5 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                           | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    315 | ITRG     | ITRG                           | OTHER    |                0.49 |             57.92 |         49.89 |         57.7  |          58.14 |        63.86 |           67.96 |             63.45 |             65.82 |         8.14 |             68.32 | long               |                2.12 |                  4.88 |                 5.11 |
|    312 | HUT      | HUT                            | US       |               10.49 |             58.01 |         67.54 |         55.1  |          60.92 |        46.93 |           38.23 |             78.14 |             19.58 |         8.54 |             66.84 | short              |              nan    |                  4.86 |               nan    |
|      6 | AMC      | AMC                            | US       |                2.31 |             81.34 |         82.1  |         86.49 |          80.57 |        79.74 |           85.71 |             79.56 |            nan    |         9.48 |             65.07 | swing              |                5.15 |                  4.49 |                 4.14 |
|     47 | NNBR     | NNBR                           | US       |                0.27 |             71.6  |         72.88 |         78.32 |          70.32 |        52.34 |           33.44 |             94.41 |             31.7  |         8.84 |             72.11 | swing              |               22.48 |                  4.24 |                 3.03 |
|    562 | CYH      | Community Health Systems, Inc. | US       |                0.36 |             45.79 |         51.91 |         35.83 |          40.07 |        51.51 |           48.21 |             28.36 |             79.27 |         7.92 |             82.05 | short              |                6.2  |                  4.06 |                 3.7  |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    655 | BAS.DE   | BAS.DE  | EUROPE   |               43.79 |             37.63 |         37.85 |         40.47 |          37.41 |        35.94 |           29.32 |             31.2  |             30.61 |         2.23 |             67.86 | swing              |               -3.62 |                 -3.58 |               nan    |
|    459 | TEVA     | TEVA    | US       |               40.18 |             52.24 |         66.39 |         57.59 |          46.89 |        39.63 |           12.25 |             29.66 |             52.73 |         4.83 |             72.34 | short              |               -2.77 |                 -3.5  |                -3.61 |
|    669 | PAH3.DE  | PAH3.DE | EUROPE   |                7.87 |             34.39 |         29.5  |         30.73 |          38.06 |        62.12 |          nan    |             27.1  |             96.91 |         5.13 |             70.3  | long               |              -10.95 |                 -3.42 |                -2.87 |
|    654 | TIT.MI   | TIT.MI  | EUROPE   |               15.25 |             37.72 |         35.67 |         39.77 |          43.29 |        32.27 |           16.94 |             53.79 |             17.97 |         2.18 |             71.66 | medium             |              -11.71 |                 -3.31 |                -3    |
|    638 | PIRC.MI  | PIRC.MI | EUROPE   |                7.04 |             39.88 |         48.66 |         42.77 |          36.99 |        36.15 |           17.55 |             21.45 |             56.74 |         2.09 |             71.32 | short              |               -4.19 |                 -3.04 |                -2.89 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.90
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
- Excluded by hard/data filters: **298**
- Event watch (otherwise eligible): **1**
- Final eligible: **701**
- Eligible change vs previous stored run: **-8**

Top exclusion categories:
- liquidity: 242
- price: 185
- market_cap: 158
- price_history: 21
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 3 |  | 6 |  | 2 | main,pullback |
| VLO | 4 |  | 1 |  | 2 | main,pullback |
| FRO | 5 |  | 3 |  | 2 | main,pullback |
| CMBT.BR | 7 |  | 4 |  | 2 | main,pullback |
| PSX | 8 |  | 2 |  | 2 | main,pullback |
| DHT | 10 |  | 5 |  | 2 | main,pullback |
| NVDA | 46 | 4 | 20 | 3 | 1 | value,quality_value |
| PARR | 58 | 7 | 34 | 4 | 1 | value,quality_value |
| EMBC | 150 | 8 |  | 5 | 1 | value,quality_value |
| 0Q2N.IL | 201 | 1 |  | 1 | 1 | value,quality_value |
| GSL | 202 | 6 | 143 | 8 | 1 | value,quality_value |
| BION.SW | 250 | 2 | 175 | 2 | 1 | value,quality_value |
| AVGO | 408 | 10 | 132 | 7 | 1 | value,quality_value |
| BBWI | 645 | 3 |  | 6 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **2** (MU, AMC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 71.71 | 75.25 | 55.12 | 85.87 | 52.38 | 86.19 | 60.15 |
| 2 | GSL | value+pullback | 70.81 | 76.20 | 74.01 | 74.29 | 30.67 | 76.17 | 61.92 |
| 3 | 0Q2N.IL | value+pullback | 69.87 | 75.11 | 52.41 | 78.60 |  | 87.21 | 61.98 |
| 4 | PARR | value+pullback | 69.44 | 68.48 | 64.14 | 80.43 | 70.33 | 68.81 | 70.82 |
| 5 | AVGO | value+pullback | 69.41 | 60.81 | 68.41 | 92.29 | 45.01 | 78.59 | 54.31 |
| 6 | PBR-A | value+pullback | 67.87 | 79.55 | 74.65 | 47.39 | 80.13 | 51.10 | 69.39 |
| 7 | INVA | value+pullback | 67.56 | 57.44 | 59.99 | 90.78 | 51.09 | 83.04 | 54.09 |
| 8 | NVDA | value+pullback | 66.50 | 61.64 | 46.65 | 86.50 | 79.39 | 77.16 | 72.03 |
| 9 | VOLV-B.ST | value+pullback | 66.40 | 79.58 | 69.02 | 51.02 | 63.59 | 56.29 | 55.36 |
| 10 | IRS | value+pullback | 63.33 | 66.83 | 69.38 | 63.30 | 40.96 | 61.71 | 46.64 |
| 11 | STNE | value+pullback | 62.24 | 68.99 | 48.05 | 86.35 | 32.54 | 66.64 | 43.02 |
| 12 | WB | value+pullback | 62.11 | 71.10 | 62.83 | 71.78 | 17.91 | 62.57 | 37.99 |
| 13 | GAB | value+pullback | 62.05 | 55.91 | 65.66 | 54.68 | 80.39 | 63.10 | 51.82 |
| 14 | AVK | value+pullback | 61.83 | 59.28 | 71.14 | 62.64 | 50.14 | 59.26 | 47.49 |
| 15 | VIPS | value+pullback | 60.52 | 66.61 | 51.86 | 85.79 | 25.32 | 60.88 | 42.53 |
| 16 | PBR | value+pullback | 58.66 | 55.90 | 71.10 | 47.39 | 72.28 | 48.90 | 64.34 |
| 17 | BCE | value+pullback | 58.39 | 56.19 | 52.87 | 78.05 | 54.67 | 55.71 | 42.41 |
| 18 | JD | value+pullback | 58.39 | 59.93 | 61.29 | 61.52 | 46.61 | 55.98 | 44.24 |
| 19 | VLO | pullback | 58.13 | 49.24 | 84.21 | 84.99 | 80.78 | 81.26 | 82.75 |
| 20 | CNC | value+pullback | 58.12 | 72.07 | 51.93 | 51.28 | 56.30 | 50.98 | 57.49 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 72.9 | 8 / 2 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 73.1 | 16 / 9 |
| Top 50 | 50/50 | 49/50 | 49/50 | 48/50 | 0/50 | 72.7 | 27 / 23 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=1, large_20_100b=4, mega_100b_plus=2
