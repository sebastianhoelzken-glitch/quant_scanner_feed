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

- **EUROPE:** 78.3/100
- **OTHER:** 66.4/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             84.09 |         89.77 |         87.03 |          81.15 |        71.92 |           70.75 |             81.12 |             52.13 |         6.91 |             72.34 | short              |                2.73 |                  0.86 |               nan    |
|      2 | MU        | MU        | US       |             1074.59 |             82.91 |         80.42 |         73.27 |          86    |        85.39 |           94.91 |             82.36 |             72.81 |         8.09 |             73.14 | medium             |                2.14 |                  2.8  |                 2.16 |
|      3 | DELL      | DELL      | US       |              314.64 |             82.8  |         86.23 |         85.55 |          80.05 |        67.94 |           71.71 |             81.91 |             35.02 |         7.82 |             72.23 | short              |               -0.82 |                  0.12 |                -0.07 |
|      4 | VLO       | VLO       | US       |               98.01 |             82.11 |         79.74 |         85.97 |          84.16 |        80.05 |           84.44 |             80.88 |             62.66 |         3.57 |             69.68 | swing              |               -3.64 |                  0.96 |                 0.9  |
|      5 | AMC       | AMC       | US       |                2.31 |             81.37 |         82.3  |         86.56 |          80.44 |        79.57 |           85.49 |             79.39 |            nan    |         9.49 |             65.07 | swing              |                5.18 |                  4.5  |                 4.15 |
|      6 | FRO       | FRO       | US       |                9.34 |             81.11 |         79.86 |         82.13 |          81.89 |        80.32 |           90.54 |             65.77 |             62.89 |         5.07 |             73.14 | swing              |               -3.81 |                  0.35 |                 0.34 |
|      7 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.87 |             81.06 |         74    |         80.09 |          82.81 |        82.03 |           96.12 |             68.83 |             65.19 |         3.66 |             73.14 | medium             |               -3.13 |                  0.98 |                 0.99 |
|      8 | PSX       | PSX       | US       |               90.15 |             80.25 |         75.69 |         84.87 |          82.22 |        78.27 |           77.95 |             86.3  |             64.27 |         3.78 |             73.14 | swing              |               -3.62 |                  1.04 |                 1.12 |
|      9 | DHT       | DHT       | US       |                3.09 |             79.83 |         78.28 |         79.94 |          79.72 |        80.45 |           88.32 |             70.72 |             66.5  |         4.46 |             73.14 | long               |               -2.24 |                  0.69 |                 0.4  |
|     10 | ERO       | ERO       | US       |                3.47 |             79.73 |         72.05 |         78.73 |          80.73 |        81.54 |           83.47 |             68.54 |             78.3  |         7.71 |             73.14 | long               |              nan    |                nan    |               nan    |
|     11 | SMTC      | SMTC      | US       |               14.96 |             79.28 |         85.41 |         82.34 |          76.22 |        62.05 |           71.71 |             84.49 |             14.86 |         8.43 |             73.14 | short              |                8.44 |                  0.82 |               nan    |
|     12 | SHELL.AS  | SHELL.AS  | EUROPE   |              243.53 |             78.41 |         83.93 |         77.08 |          74.15 |        79.75 |           93.01 |             79.72 |             65.43 |         2.4  |             73.14 | short              |                4.26 |                  2.87 |                 2.67 |
|     13 | REP.MC    | REP.MC    | EUROPE   |               33.1  |             78.28 |         84.5  |         81.34 |          75.21 |        71.27 |           59.13 |             83.5  |             72.46 |         3.84 |             73.14 | short              |                3.62 |                  1.81 |                 1.44 |
|     14 | HALO      | HALO      | US       |               11.37 |             77.37 |         80.54 |         80.1  |          74.63 |        71.46 |           84.15 |             52.28 |             51.43 |         6.03 |             72.11 | short              |                1.26 |                nan    |               nan    |
|     15 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             76.38 |         77.9  |         80.46 |          74.86 |        65.88 |           89.12 |             65.5  |             20.65 |         3.68 |             73.14 | swing              |               -1.37 |                 -0.46 |                -0.35 |
|     16 | OMV.VI    | OMV.VI    | EUROPE   |               23.6  |             76.02 |         78.06 |         79.2  |          73.98 |        70.59 |           61.46 |             86.12 |             68.52 |         1.96 |             72.34 | swing              |                4.8  |                  1.09 |                 0.6  |
|     17 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.22 |             75.99 |         78.11 |         77.8  |          74.17 |        73.39 |           68.57 |             74.91 |             74.53 |         5.46 |             73.14 | short              |                4.85 |                  1.2  |               nan    |
|     18 | SHEL      | SHEL      | US       |              240.17 |             75.7  |         78.73 |         75.24 |          70.72 |        76.17 |           72.01 |             80.02 |             80.38 |         2.97 |             72.8  | short              |               10.6  |                  3.25 |                 2.55 |
|     19 | GRAL      | GRAL      | US       |                4.98 |             75.07 |         82.62 |         82.79 |          67.52 |        57.78 |           40.56 |             68.32 |             57.85 |         9.44 |             66.84 | swing              |                6.11 |                nan    |               nan    |
|     20 | TRMD      | TRMD      | US       |                3.1  |             74.96 |         74.86 |         74.19 |          75.06 |        80.42 |           83.23 |             46.28 |             87.51 |         5.51 |             73.14 | long               |              nan    |                nan    |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                2.98 |                  73.97 |                    74.56 |                 76.27 |              74.76 |                86.91 |                   13.09 |           84.64 |             58.55 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | BBWI      | Bath & Body Works, Inc.              | US       |                2.92 |                  75.58 |                    71.44 |                 69.08 |              70.44 |                70.04 |                   29.96 |           77.77 |             34.09 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|            3 | NVDA      | NVIDIA Corporation                   | US       |             4777.92 |                  61.64 |                    71.07 |                 72.95 |              66.22 |                77.26 |                   22.74 |           86.9  |             79.31 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              243.53 |                  58.75 |                    70.86 |                 74.73 |              65.97 |                87.2  |                   12.8  |           93.01 |             79.72 |     nan     |         nan |       nan |      nan    |         9.73 |         10.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                                 | US       |              240.17 |                  66.39 |                    70.18 |                 71.23 |              69.43 |                75.68 |                   24.32 |           72.01 |             80.02 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.41 |                  68.48 |                    69.83 |                 71.81 |              68.73 |                68.79 |                   31.21 |           80.43 |             70.42 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SM        | SM                                   | US       |                7.09 |                  63.94 |                    69.78 |                 72.07 |              67.13 |                72.29 |                   27.71 |           81.33 |             80.78 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.75 |                  74.83 |                    69.23 |                 69.49 |              70.67 |                68.7  |                   31.3  |           75.5  |             44.27 |       0.62  |         nan |       nan |        4.54 |      -130.58 |          2.25 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | EMBC      | Embecta Corp.                        | US       |                0.29 |                  72.61 |                    69.19 |                 69.39 |              69.95 |                61.87 |                   38.13 |           70.56 |             65.31 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | TTE.PA    | TTE.PA                               | EUROPE   |              178.19 |                  65.37 |                    69.05 |                 69.92 |              69.06 |                74.85 |                   25.15 |           65.98 |             85.23 |     nan     |         nan |       nan |      nan    |         8.79 |         11.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                3.09 |                  60.1  |                    68.48 |                 71.41 |              64.36 |                77.88 |                   22.12 |           88.32 |             70.72 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | AVGO      | Broadcom Inc.                        | US       |             1480.63 |                  60.81 |                    68.39 |                 69.03 |              62.47 |                78.65 |                   21.35 |           92.29 |             45.34 |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.06 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP        | BP                                   | US       |               99.96 |                  55.94 |                    68.32 |                 72.31 |              64.17 |                82.44 |                   17.56 |           84.77 |             90.5  |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               58.72 |                  76.88 |                    68.25 |                 64.9  |              71.54 |                54.64 |                   45.36 |           50.31 |             63.51 |       0.036 |         nan |       nan |       15.57 |        13.09 |         18.51 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR   | CMBT.BR                              | EUROPE   |                4.87 |                  56.25 |                    68.06 |                 72.08 |              62.28 |                82.76 |                   17.24 |           96.12 |             68.83 |     nan     |         nan |       nan |      nan    |         9.23 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.47 |                  75.59 |                    67.69 |                 66.83 |              71.57 |                50.76 |                   49.24 |           52.72 |             80.16 |       0.143 |         nan |       nan |        1.78 |         4.61 |          4.68 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|          nan | AGS.BR    | AGS.BR                               | EUROPE   |               15.61 |                  63.64 |                    67.66 |                 68.96 |              64.58 |                76.26 |                   23.74 |           85.37 |             50.24 |     nan     |         nan |       nan |      nan    |         8.7  |          7.69 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | 0Q2N.IL   | K+S Aktiengesellschaft               | OTHER    |                3.04 |                  68.76 |                    67.6  |                 66.7  |              68.98 |                69.85 |                   30.15 |           61.12 |            nan    |       0.244 |         nan |       nan |        1.54 |       nan    |          2.83 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           11 | STNE      | StoneCo Ltd.                         | OTHER    |                1.89 |                  68.99 |                    67.59 |                 67.55 |              64.95 |                66.67 |                   33.33 |           86.35 |             32.76 |       0.635 |         nan |       nan |        1.61 |         4.12 |          3.54 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAA       | PAA                                  | US       |               15.15 |                  55.7  |                    67.3  |                 70.87 |              63.03 |                83.88 |                   16.12 |           85.91 |             78.29 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG              | EUROPE   |                2.98 |                  73.97 |                    74.56 |                 76.27 |              74.76 |                86.91 |                   13.09 |           84.64 |             58.55 |       0.877 |         nan |       nan |      nan    |       -77.69 |          2.08 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              243.53 |                  58.75 |                    70.86 |                 74.73 |              65.97 |                87.2  |                   12.8  |           93.01 |             79.72 |     nan     |         nan |       nan |      nan    |         9.73 |         10.81 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA     | NVIDIA Corporation         | US       |             4777.92 |                  61.64 |                    71.07 |                 72.95 |              66.22 |                77.26 |                   22.74 |           86.9  |             79.31 |       0.008 |         nan |       nan |       26.83 |        14.35 |         28.49 |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BP       | BP                         | US       |               99.96 |                  55.94 |                    68.32 |                 72.31 |              64.17 |                82.44 |                   17.56 |           84.77 |             90.5  |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.87 |                  56.25 |                    68.06 |                 72.08 |              62.28 |                82.76 |                   17.24 |           96.12 |             68.83 |     nan     |         nan |       nan |      nan    |         9.23 |          6.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM       | SM                         | US       |                7.09 |                  63.94 |                    69.78 |                 72.07 |              67.13 |                72.29 |                   27.71 |           81.33 |             80.78 |     nan     |         nan |       nan |      nan    |         4.25 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                  68.48 |                    69.83 |                 71.81 |              68.73 |                68.79 |                   31.21 |           80.43 |             70.42 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | DHT      | DHT                        | US       |                3.09 |                  60.1  |                    68.48 |                 71.41 |              64.36 |                77.88 |                   22.12 |           88.32 |             70.72 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                       | US       |              240.17 |                  66.39 |                    70.18 |                 71.23 |              69.43 |                75.68 |                   24.32 |           72.01 |             80.02 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                        | US       |               15.15 |                  55.7  |                    67.3  |                 70.87 |              63.03 |                83.88 |                   16.12 |           85.91 |             78.29 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.88 |                  55.8  |                    66.59 |                 70.21 |              60.68 |                82.25 |                   17.75 |           96.87 |             56.98 |     nan     |         nan |       nan |      nan    |        10.91 |         14.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.75 |                  56.66 |                    66.88 |                 70.17 |              62.78 |                80.3  |                   19.7  |           85.34 |             75.28 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                     | EUROPE   |              178.19 |                  65.37 |                    69.05 |                 69.92 |              69.06 |                74.85 |                   25.15 |           65.98 |             85.23 |     nan     |         nan |       nan |      nan    |         8.79 |         11.49 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                9.34 |                  57.58 |                    66.59 |                 69.84 |              61.75 |                76.2  |                   23.8  |           90.54 |             65.77 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                         | US       |             1074.59 |                  48.68 |                    64.11 |                 69.65 |              57.28 |                77.71 |                   22.29 |           94.91 |             82.36 |     nan     |         nan |       nan |      nan    |         6.76 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.75 |                  74.83 |                    69.23 |                 69.49 |              70.67 |                68.7  |                   31.3  |           75.5  |             44.27 |       0.62  |         nan |       nan |        4.54 |      -130.58 |          2.25 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | A5G.IR   | A5G.IR                     | EUROPE   |               24.32 |                  55.42 |                    65.85 |                 69.41 |              59.92 |                80.95 |                   19.05 |           96.64 |             54.46 |     nan     |         nan |       nan |      nan    |        11.71 |         11.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | EMBC     | Embecta Corp.              | US       |                0.29 |                  72.61 |                    69.19 |                 69.39 |              69.95 |                61.87 |                   38.13 |           70.56 |             65.31 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | BBWI     | Bath & Body Works, Inc.    | US       |                2.92 |                  75.58 |                    71.44 |                 69.08 |              70.44 |                70.04 |                   29.96 |           77.77 |             34.09 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|            7 | AVGO     | Broadcom Inc.              | US       |             1480.63 |                  60.81 |                    68.39 |                 69.03 |              62.47 |                78.65 |                   21.35 |           92.29 |             45.34 |       0.018 |         nan |       nan |       32.9  |        18.2  |         45.06 |        0.35 |                 nan |              nan |                  12 |                  0.63 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.64 |         79.74 |         85.97 |          84.16 |        80.05 |           84.44 |             80.88 |         3.57 |
|               2 | PSX       | PSX       | US       |               90.15 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.23 |         75.69 |         84.87 |          82.22 |        78.27 |           77.95 |             86.3  |         3.78 |
|               3 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        81.24 |         79.86 |         82.13 |          81.89 |        80.32 |           90.54 |             65.77 |         5.07 |
|               4 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.83 |         78.28 |         79.94 |          79.72 |        80.45 |           88.32 |             70.72 |         4.46 |
|               5 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.87 |                     0.07 |    -0.03 |      0.07 |                  70.45 |                        80.16 |         74    |         80.09 |          82.81 |        82.03 |           96.12 |             68.83 |         3.66 |
|               6 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        79.69 |         86.23 |         85.55 |          80.05 |        67.94 |           71.71 |             81.91 |         7.82 |
|               7 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        78.55 |         74.85 |         73.44 |          72.51 |        78.97 |           84.77 |             90.5  |         4.47 |
|               8 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.19 |                     0.04 |    -0.02 |      0.37 |                  69.93 |                        76.74 |         82.05 |         77.49 |          68.76 |        68.79 |           82.35 |             58.35 |         5.26 |
|               9 | C5H.IR    | C5H.IR    | EUROPE   |                1.69 |                     0.04 |     0.01 |      0.1  |                  56.03 |                        76.06 |         79.67 |         69.8  |          72.24 |        75.63 |           98.23 |             54.49 |         2.67 |
|              10 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.22 |                     0.06 |    -0.05 |      0.12 |                  79.79 |                        75.97 |         78.11 |         77.8  |          74.17 |        73.39 |           68.57 |             74.91 |         5.46 |
|              11 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        75.5  |         77.6  |         75.1  |          73.28 |        70.27 |           86.41 |             45.62 |         4.62 |
|              12 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        75.3  |         64.43 |         74.92 |          73.99 |        75.27 |           72.91 |             85.81 |         5.62 |
|              13 | DAR       | DAR       | US       |                8.5  |                     0.09 |    -0.06 |     -0    |                  64.43 |                        74.83 |         57.44 |         69.03 |          77.46 |        84.37 |           89.85 |             84.49 |         4.73 |
|              14 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.48 |         55.86 |         68.33 |          73.79 |        76.72 |           85.91 |             78.29 |         2.06 |
|              15 | TEAM      | TEAM      | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        74    |         68.79 |         84.13 |          66.9  |        47.89 |           40.07 |             91.07 |         9.5  |
|              16 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.28 |                     0.04 |     0    |      0.08 |                  62.46 |                        73.76 |         78.12 |         75.71 |          70.23 |        61.86 |           61.6  |             86.74 |         4.9  |
|              17 | SHEL      | SHEL      | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.69 |         78.73 |         75.24 |          70.72 |        76.17 |           72.01 |             80.02 |         2.97 |
|              18 | DNORD.CO  | DNORD.CO  | EUROPE   |                1.38 |                     0.06 |    -0.06 |      0.05 |                  85.58 |                        73.64 |         66.61 |         71.59 |          66.97 |        59.83 |           80.09 |             59.94 |         4.75 |
|              19 | ARIS      | ARIS      | US       |                3.44 |                     0.08 |    -0.02 |     -0.11 |                  63.15 |                        73.35 |         53.23 |         69.7  |          78.05 |        85.14 |           87.02 |             77.5  |         7.79 |
|              20 | GTLB      | GTLB      | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        73.19 |         69.95 |         79.22 |          63.6  |        48.75 |           55.91 |             72.46 |         8.38 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                0.51 |             29.94 |         32.63 |         22.27 |          27.25 |        35.18 |           46.41 |             32.02 |             33.52 |          8.9 |             78.44 | long               |                4.75 |                  0.49 |                 0.48 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    278 | ITRG     | ITRG   | OTHER    |                0.49 |             58.94 |         49.66 |         58.33 |          59.55 |        67.79 |           65.38 |             63.26 |             84.36 |         8.16 |             68.32 | long               |                3.14 |                  5.08 |                 5.27 |
|    313 | HUT      | HUT    | US       |               10.49 |             57.84 |         67.51 |         55.05 |          60.64 |        46.15 |           37.18 |             78.33 |             18.02 |         8.55 |             66.84 | short              |              nan    |                  4.83 |               nan    |
|      5 | AMC      | AMC    | US       |                2.31 |             81.37 |         82.3  |         86.56 |          80.44 |        79.57 |           85.49 |             79.39 |            nan    |         9.49 |             65.07 | swing              |                5.18 |                  4.5  |                 4.15 |
|     63 | AMS.SW   | AMS.SW | EUROPE   |                2.09 |             70.67 |         71.81 |         74.56 |          69.53 |        53.11 |           53.26 |             87.36 |             15.11 |         8.65 |             73.14 | swing              |               -0.4  |                  4.21 |               nan    |
|     58 | NNBR     | NNBR   | US       |                0.27 |             71.12 |         72.73 |         77.8  |          69.51 |        51.07 |           34.01 |             92.14 |             27.23 |         8.85 |             72.11 | swing              |               22    |                  4.14 |                 2.96 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    667 | PAH3.DE  | PAH3.DE | EUROPE   |                7.85 |             33.89 |         28.79 |         30.15 |          37.63 |        61.65 |          nan    |             27.48 |             96.94 |         5.12 |             70.3  | long               |              -11.46 |                 -3.52 |                -2.95 |
|    644 | BAS.DE   | BAS.DE  | EUROPE   |               42.96 |             38.11 |         39.13 |         40.62 |          37.09 |        35.67 |           29.11 |             30.14 |             31.24 |         2.21 |             67.86 | swing              |               -3.13 |                 -3.49 |               nan    |
|    439 | TEVA     | TEVA    | US       |               40.18 |             52.58 |         66.64 |         58.05 |          47.12 |        39.4  |           13.06 |             30.5  |             50.17 |         4.84 |             72.34 | short              |               -2.43 |                 -3.43 |                -3.56 |
|    650 | TIT.MI   | TIT.MI  | EUROPE   |               15.26 |             37.49 |         35.4  |         39.57 |          43.34 |        32.41 |           17.72 |             54.34 |             18.14 |         2.21 |             71.32 | medium             |              -11.94 |                 -3.36 |                -3.04 |
|    647 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.21 |             37.89 |         21.76 |         32.02 |          43.75 |        74.07 |          nan    |            nan    |             98.39 |         5.16 |             60    | long               |                0.28 |                 -2.97 |                -3.13 |

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
- Excluded by hard/data filters: **302**
- Event watch (otherwise eligible): **1**
- Final eligible: **697**
- Eligible change vs previous stored run: **-12**

Top exclusion categories:
- liquidity: 239
- price: 185
- market_cap: 166
- price_history: 22
- data_confidence: 12
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| DELL | 3 |  | 6 |  | 2 | main,pullback |
| VLO | 4 |  | 1 |  | 2 | main,pullback |
| FRO | 6 |  | 3 |  | 2 | main,pullback |
| CMBT.BR | 7 |  | 5 |  | 2 | main,pullback |
| PSX | 8 |  | 2 |  | 2 | main,pullback |
| DHT | 9 |  | 4 |  | 2 | main,pullback |
| NVDA | 49 | 3 | 21 | 2 | 1 | value,quality_value |
| PARR | 61 | 4 | 36 | 3 | 1 | value,quality_value |
| PBR-A | 64 | 9 | 33 | 10 | 1 | value,quality_value |
| EMBC | 149 | 6 |  | 5 | 1 | value,quality_value |
| BION.SW | 206 | 1 | 130 | 1 | 1 | value,quality_value |
| NWL.MI | 263 | 5 | 54 | 4 | 1 | value,quality_value |
| AVGO | 394 | 7 | 129 | 7 | 1 | value,quality_value |
| BBWI | 638 | 2 |  | 6 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **3** (MU, AMC, ERO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | BION.SW | value+pullback | 72.31 | 73.97 | 56.75 | 84.64 | 58.55 | 86.91 | 61.85 |
| 2 | NWL.MI | value+pullback | 70.65 | 74.83 | 74.84 | 75.50 | 44.27 | 68.70 | 59.52 |
| 3 | AVGO | value+pullback | 69.45 | 60.81 | 68.41 | 92.29 | 45.34 | 78.65 | 54.43 |
| 4 | PARR | value+pullback | 69.45 | 68.48 | 64.14 | 80.43 | 70.42 | 68.79 | 70.97 |
| 5 | GSL | value+pullback | 69.02 | 71.32 | 74.01 | 74.65 | 30.86 | 74.18 | 62.47 |
| 6 | INVA | value+pullback | 67.54 | 57.44 | 59.99 | 90.78 | 50.96 | 82.99 | 54.03 |
| 7 | PBR-A | value+pullback | 67.41 | 75.59 | 74.65 | 52.72 | 80.16 | 50.76 | 70.56 |
| 8 | NVDA | value+pullback | 66.57 | 61.64 | 46.65 | 86.90 | 79.31 | 77.26 | 72.13 |
| 9 | VOLV-B.ST | value+pullback | 65.08 | 76.88 | 68.76 | 50.31 | 63.51 | 54.64 | 54.89 |
| 10 | IRS | value+pullback | 63.23 | 67.73 | 69.38 | 62.56 | 40.88 | 60.50 | 46.50 |
| 11 | STNE | value+pullback | 62.27 | 68.99 | 48.05 | 86.35 | 32.76 | 66.67 | 43.11 |
| 12 | WB | value+pullback | 62.09 | 71.10 | 62.83 | 71.78 | 17.82 | 62.52 | 37.99 |
| 13 | AVK | value+pullback | 61.73 | 57.11 | 71.14 | 62.64 |  | 62.10 | 47.05 |
| 14 | 0Q2N.IL | value+pullback | 61.60 | 68.76 | 51.35 | 61.12 |  | 69.85 | 57.60 |
| 15 | VIPS | value+pullback | 60.50 | 66.61 | 51.86 | 85.79 | 25.16 | 60.82 | 42.55 |
| 16 | JD | value+pullback | 58.40 | 59.93 | 61.29 | 61.52 | 46.75 | 55.99 | 44.23 |
| 17 | BCE | value+pullback | 58.37 | 56.19 | 52.87 | 78.05 | 54.60 | 55.66 | 42.39 |
| 18 | CNC | value+pullback | 58.14 | 72.07 | 51.93 | 51.28 | 56.48 | 51.00 | 57.56 |
| 19 | VLO | pullback | 58.00 | 49.36 | 84.21 | 84.44 | 80.88 | 80.98 | 82.11 |
| 20 | GAB | value+pullback | 57.82 | 55.55 | 65.66 | 54.68 |  | 57.68 | 43.95 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 7 / 3 |
| Top 25 | 25/25 | 25/25 | 24/25 | 24/25 | 0/25 | 73.1 | 15 / 10 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 72.7 | 25 / 25 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
