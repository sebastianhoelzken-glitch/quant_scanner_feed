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

- **EUROPE:** 78.7/100
- **OTHER:** 55.6/100
- **US:** 77.5/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AMC       | AMC       | US       |                2.58 |             82.79 |         86    |         89.36 |          79.57 |        78.96 |           85.96 |             78.55 |            nan    |         9.51 |             65.07 | swing              |                6.6  |                  4.78 |                 4.36 |
|      2 | VLO       | VLO       | US       |               98.58 |             82.65 |         82.86 |         84.12 |          82.44 |        76.98 |           87.72 |             82.07 |             50.49 |         3.66 |             69.68 | swing              |               -3.09 |                  1.07 |                 0.98 |
|      3 | HPE       | HPE       | US       |               73.07 |             82.41 |         88.27 |         85.11 |          79.71 |        69.42 |           74.19 |             82.44 |             41.94 |         6.96 |             72.34 | short              |                1.05 |                  0.52 |               nan    |
|      4 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.86 |             80.96 |         73.7  |         80.17 |          83    |        81.74 |           96.04 |             70.35 |             63.1  |         3.78 |             73.14 | medium             |               -3.23 |                  0.96 |                 0.97 |
|      5 | FRO       | FRO       | US       |                9.41 |             80.03 |         81.06 |         80.4  |          79.66 |        76.4  |           92.11 |             65.57 |             50.63 |         5.19 |             73.14 | short              |               -4.89 |                  0.13 |                 0.18 |
|      6 | MU        | MU        | US       |             1046.19 |             79.32 |         76.47 |         70.22 |          84.04 |        82.17 |           95.03 |             84.24 |             63.84 |         8.17 |             73.14 | medium             |               -1.44 |                  2.08 |                 1.62 |
|      7 | SHELL.AS  | SHELL.AS  | EUROPE   |              241.35 |             78.69 |         81.55 |         77.47 |          75.19 |        79.9  |           93.16 |             81.29 |             64.17 |         2.51 |             73.14 | short              |                4.53 |                  2.92 |                 2.72 |
|      8 | REP.MC    | REP.MC    | EUROPE   |               32.45 |             78.54 |         81.63 |         81.19 |          75.89 |        71.34 |           60.17 |             84.68 |             70.28 |         4.01 |             73.14 | short              |                3.88 |                  1.86 |                 1.48 |
|      9 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             78.06 |         78.27 |         83.23 |          77.84 |        67.52 |           89.31 |             76.48 |             19.77 |         3.71 |             73.14 | swing              |                0.31 |                 -0.13 |                -0.1  |
|     10 | DHT       | DHT       | US       |                3.1  |             77.78 |         79.93 |         78.37 |          77.18 |        76.14 |           89.22 |             70    |             53.31 |         4.55 |             73.14 | short              |               -4.29 |                  0.28 |                 0.09 |
|     11 | DELL      | DELL      | US       |              303.67 |             77.19 |         78.15 |         79.6  |          76.23 |        64.52 |           73.45 |             73.41 |             29.12 |         7.82 |             72.23 | swing              |               -6.43 |                 -1.01 |                -0.91 |
|     12 | PSX       | PSX       | US       |               89.35 |             77.02 |         73.56 |         81.16 |          79.31 |        74.72 |           80.66 |             84.25 |             52.88 |         3.9  |             73.14 | swing              |               -6.84 |                  0.39 |                 0.63 |
|     13 | ABN.AS    | ABN.AS    | EUROPE   |               35.81 |             76.1  |         77.52 |         77.18 |          75.02 |        69.79 |           78.7  |             68.03 |             50.01 |         2.85 |             73.14 | short              |                0.04 |                  1.41 |                 1.38 |
|     14 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.21 |             75.97 |         82.96 |         77.22 |          74.72 |        73.68 |           69.24 |             75.7  |             73.39 |         5.42 |             73.14 | short              |                4.84 |                  1.2  |               nan    |
|     15 | DOCM.SW   | DOCM.SW   | EUROPE   |                0.67 |             75.81 |         86.22 |         81.65 |          69.97 |        54.4  |           38.7  |             81.5  |             40.82 |         7.71 |             70.3  | short              |                3.87 |                  2.15 |                 1.73 |
|     16 | SMTC      | SMTC      | US       |               14.34 |             75.76 |         83.5  |         76.86 |          74.66 |        60.99 |           75.44 |             85.34 |             10.83 |         8.51 |             73.14 | short              |                4.93 |                  0.12 |               nan    |
|     17 | PBF       | PBF       | US       |                7.75 |             75.58 |         77.23 |         78.12 |          73.92 |        70.12 |           51.9  |             74.85 |             81.41 |         7.64 |             72.68 | swing              |               -3.01 |                  0.54 |                 0.53 |
|     18 | PBR-A     | PBR-A     | US       |              112.22 |             75.56 |         77.8  |         73.33 |          71.07 |        78.58 |           75.96 |             71.1  |             85.76 |         4.62 |             69.89 | long               |                1.04 |                  0.41 |                 0.12 |
|     19 | WT        | WT        | US       |                3.2  |             75.48 |         74.66 |         80.55 |          76.3  |        64.43 |           73.53 |             84.25 |             26.03 |         5.84 |             73.14 | swing              |                1.53 |                  2.42 |                 2.18 |
|     20 | BP        | BP        | US       |              100.57 |             75.11 |         79.95 |         73.26 |          71.7  |        76.96 |           88.63 |             91.73 |             58.77 |         4.54 |             72.34 | short              |               12.88 |                  3.79 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | VOLV-B.ST | AB Volvo (publ)                 | EUROPE   |               58.72 |                  89.18 |                    74.13 |                 69.33 |              79.58 |                51.39 |                   48.61 |           49.24 |             61.2  |       0.036 |         nan |       nan |       15.6  |        13.13 |         18.54 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS  | SHELL.AS                        | EUROPE   |              241.35 |                  60.2  |                    71.95 |                 75.71 |              67.24 |                87.57 |                   12.43 |           93.16 |             81.29 |     nan     |         nan |       nan |      nan    |         9.64 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                              | US       |              100.57 |                  59.76 |                    71.61 |                 75.51 |              67.44 |                84.64 |                   15.36 |           88.63 |             91.73 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A     | PBR-A                           | US       |              112.22 |                  69.63 |                    71.08 |                 71.71 |              70.11 |                71.5  |                   28.5  |           75.96 |             71.1  |     nan     |         nan |       nan |      nan    |         4.64 |          4.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL                            | US       |              241.8  |                  64.99 |                    70.89 |                 72.63 |              69.43 |                78.74 |                   21.26 |           75.52 |             84.62 |     nan     |         nan |       nan |      nan    |         9.28 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            2 | NOVO-B.CO | Novo Nordisk A/S                | EUROPE   |              149.42 |                  76.92 |                    69.82 |                 67.92 |              70.53 |                52.76 |                   47.24 |           67.67 |             56.55 |       0.034 |         nan |       nan |        6.98 |        11.57 |          9.63 |        4.39 |                 nan |              nan |                  11 |                  0.58 |
|          nan | TTE.PA    | TTE.PA                          | EUROPE   |              173.7  |                  65.37 |                    69.5  |                 70.53 |              69.34 |                75.68 |                   24.32 |           67.11 |             86.56 |     nan     |         nan |       nan |      nan    |         8.54 |         11.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA      | NVIDIA Corporation              | US       |             4856.99 |                  61.64 |                    69.29 |                 70.4  |              65    |                74.29 |                   25.71 |           82.61 |             72.48 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | EC        | EC                              | US       |               30.17 |                  65.31 |                    68.83 |                 69.81 |              68.42 |                73.21 |                   26.79 |           68.45 |             82.18 |     nan     |         nan |       nan |      nan    |         9.04 |          8.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                              | US       |                7.01 |                  61.88 |                    68.83 |                 71.48 |              65.76 |                72.71 |                   27.29 |           82.15 |             81.26 |     nan     |         nan |       nan |      nan    |         4.21 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA       | PAA                             | US       |               15.21 |                  55.06 |                    67.58 |                 71.47 |              62.91 |                85.27 |                   14.73 |           88.06 |             79.25 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR                         | EUROPE   |                4.86 |                  55.11 |                    67.58 |                 71.81 |              61.65 |                82.98 |                   17.02 |           96.04 |             70.35 |     nan     |         nan |       nan |      nan    |         9.19 |          6.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                         | EUROPE   |               18.95 |                  56.68 |                    66.99 |                 70.48 |              61.21 |                81.96 |                   18.04 |           96.82 |             56.52 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN       | DVN                             | US       |               45.18 |                  61.13 |                    66.88 |                 68.93 |              64.08 |                72.62 |                   27.38 |           80.18 |             69.92 |     nan     |         nan |       nan |      nan    |         8.67 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | HOS       | Hornbeck Offshore Services, Inc | US       |                2.28 |                  72.51 |                    66.68 |                 66.22 |              71.16 |                68.55 |                   31.45 |           53.55 |             66.12 |     nan     |         nan |       nan |        1.96 |        14.7  |         19.85 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | DHT       | DHT                             | US       |                3.1  |                  56.7  |                    66.59 |                 70.01 |              61.85 |                77.92 |                   22.08 |           89.22 |             70    |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | AVGO      | Broadcom Inc.                   | US       |             1466.62 |                  60.81 |                    66.42 |                 66.19 |              61.06 |                75.58 |                   24.42 |           87.89 |             36.78 |       0.018 |         nan |       nan |       32.61 |        18.03 |         45.05 |        0.35 |                 nan |              nan |                  12 |                  0.63 |
|          nan | A5G.IR    | A5G.IR                          | EUROPE   |               24.33 |                  55.92 |                    66.37 |                 69.95 |              60.37 |                81.35 |                   18.65 |           97.56 |             54.63 |     nan     |         nan |       nan |      nan    |        11.71 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                             | US       |                9.41 |                  56.67 |                    66.37 |                 69.87 |              61.17 |                76.68 |                   23.32 |           92.11 |             65.57 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX       | CVX                             | US       |              355.79 |                  59.27 |                    66.04 |                 67.99 |              64.73 |                74.78 |                   25.22 |           68.85 |             85.9  |     nan     |         nan |       nan |      nan    |        14.6  |         19.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name               | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS  | SHELL.AS           | EUROPE   |              241.35 |                  60.2  |                    71.95 |                 75.71 |              67.24 |                87.57 |                   12.43 |           93.16 |             81.29 |     nan     |         nan |       nan |      nan    |         9.64 |         10.66 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BP        | BP                 | US       |              100.57 |                  59.76 |                    71.61 |                 75.51 |              67.44 |                84.64 |                   15.36 |           88.63 |             91.73 |     nan     |         nan |       nan |      nan    |         8.6  |         21.26 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL      | SHEL               | US       |              241.8  |                  64.99 |                    70.89 |                 72.63 |              69.43 |                78.74 |                   21.26 |           75.52 |             84.62 |     nan     |         nan |       nan |      nan    |         9.28 |         10.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR   | CMBT.BR            | EUROPE   |                4.86 |                  55.11 |                    67.58 |                 71.81 |              61.65 |                82.98 |                   17.02 |           96.04 |             70.35 |     nan     |         nan |       nan |      nan    |         9.19 |          6.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PBR-A     | PBR-A              | US       |              112.22 |                  69.63 |                    71.08 |                 71.71 |              70.11 |                71.5  |                   28.5  |           75.96 |             71.1  |     nan     |         nan |       nan |      nan    |         4.64 |          4.71 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SM        | SM                 | US       |                7.01 |                  61.88 |                    68.83 |                 71.48 |              65.76 |                72.71 |                   27.29 |           82.15 |             81.26 |     nan     |         nan |       nan |      nan    |         4.21 |          6.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA       | PAA                | US       |               15.21 |                  55.06 |                    67.58 |                 71.47 |              62.91 |                85.27 |                   14.73 |           88.06 |             79.25 |     nan     |         nan |       nan |      nan    |        12.86 |         20.79 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA    | TTE.PA             | EUROPE   |              173.7  |                  65.37 |                    69.5  |                 70.53 |              69.34 |                75.68 |                   24.32 |           67.11 |             86.56 |     nan     |         nan |       nan |      nan    |         8.54 |         11.21 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR            | EUROPE   |               18.95 |                  56.68 |                    66.99 |                 70.48 |              61.21 |                81.96 |                   18.04 |           96.82 |             56.52 |     nan     |         nan |       nan |      nan    |        10.96 |         14.89 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | NVDA      | NVIDIA Corporation | US       |             4856.99 |                  61.64 |                    69.29 |                 70.4  |              65    |                74.29 |                   25.71 |           82.61 |             72.48 |       0.008 |         nan |       nan |       27.29 |        14.59 |         28.5  |        0.47 |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                | US       |                3.1  |                  56.7  |                    66.59 |                 70.01 |              61.85 |                77.92 |                   22.08 |           89.22 |             70    |     nan     |         nan |       nan |      nan    |        10.21 |          7.4  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR    | A5G.IR             | EUROPE   |               24.33 |                  55.92 |                    66.37 |                 69.95 |              60.37 |                81.35 |                   18.65 |           97.56 |             54.63 |     nan     |         nan |       nan |      nan    |        11.71 |         12.1  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                | US       |                9.41 |                  56.67 |                    66.37 |                 69.87 |              61.17 |                76.68 |                   23.32 |           92.11 |             65.57 |     nan     |         nan |       nan |      nan    |        10.51 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU        | MU                 | US       |             1046.19 |                  48.22 |                    64.14 |                 69.83 |              57.23 |                78.23 |                   21.77 |           95.03 |             84.24 |     nan     |         nan |       nan |      nan    |         6.53 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | EC        | EC                 | US       |               30.17 |                  65.31 |                    68.83 |                 69.81 |              68.42 |                73.21 |                   26.79 |           68.45 |             82.18 |     nan     |         nan |       nan |      nan    |         9.04 |          8.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | VOLV-B.ST | AB Volvo (publ)    | EUROPE   |               58.72 |                  89.18 |                    74.13 |                 69.33 |              79.58 |                51.39 |                   48.61 |           49.24 |             61.2  |       0.036 |         nan |       nan |       15.6  |        13.13 |         18.54 |        0.95 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN       | BEN                | US       |               14.59 |                  54.63 |                    65.52 |                 68.98 |              61.38 |                79.76 |                   20.24 |           83.63 |             76.86 |     nan     |         nan |       nan |      nan    |        10.25 |         22.54 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DVN       | DVN                | US       |               45.18 |                  61.13 |                    66.88 |                 68.93 |              64.08 |                72.62 |                   27.38 |           80.18 |             69.92 |     nan     |         nan |       nan |      nan    |         8.67 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VLO       | VLO                | US       |               98.58 |                  47.48 |                    63.06 |                 68.03 |              57.3  |                82.82 |                   17.18 |           87.72 |             82.07 |     nan     |         nan |       nan |      nan    |        10.24 |         16.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CVX       | CVX                | US       |              355.79 |                  59.27 |                    66.04 |                 67.99 |              64.73 |                74.78 |                   25.22 |           68.85 |             85.9  |     nan     |         nan |       nan |      nan    |        14.6  |         19.86 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.58 |                     0.06 |    -0.01 |      0.11 |                  72.11 |                        82.73 |         82.86 |         84.12 |          82.44 |        76.98 |           87.72 |             82.07 |         3.66 |
|               2 | SMTC      | SMTC      | US       |               14.34 |                     0.06 |    -0.01 |      0.33 |                  74.94 |                        80.88 |         83.5  |         76.86 |          74.66 |        60.99 |           75.44 |             85.34 |         8.51 |
|               3 | FRO       | FRO       | US       |                9.41 |                     0.06 |    -0.03 |      0.16 |                  74.92 |                        80.03 |         81.06 |         80.4  |          79.66 |        76.4  |           92.11 |             65.57 |         5.19 |
|               4 | DHT       | DHT       | US       |                3.1  |                     0.06 |    -0.02 |      0.11 |                  75.58 |                        79.65 |         79.93 |         78.37 |          77.18 |        76.14 |           89.22 |             70    |         4.55 |
|               5 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.86 |                     0.08 |    -0.02 |      0.07 |                  64.75 |                        79.56 |         73.7  |         80.17 |          83    |        81.74 |           96.04 |             70.35 |         3.78 |
|               6 | PSX       | PSX       | US       |               89.35 |                     0.08 |    -0.03 |      0.04 |                  67.38 |                        79.46 |         73.56 |         81.16 |          79.31 |        74.72 |           80.66 |             84.25 |         3.9  |
|               7 | MU        | MU        | US       |             1046.19 |                     0.04 |     0.01 |      0.13 |                  57.81 |                        78.55 |         76.47 |         70.22 |          84.04 |        82.17 |           95.03 |             84.24 |         8.17 |
|               8 | DELL      | DELL      | US       |              303.67 |                     0.08 |    -0.06 |      0.19 |                  73.73 |                        76.56 |         78.15 |         79.6  |          76.23 |        64.52 |           73.45 |             73.41 |         7.82 |
|               9 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.21 |                     0.07 |     0.01 |      0.11 |                  61.14 |                        75.85 |         82.96 |         77.22 |          74.72 |        73.68 |           69.24 |             75.7  |         5.42 |
|              10 | WT        | WT        | US       |                3.2  |                     0.03 |     0.01 |     -0.02 |                  53.25 |                        75.6  |         74.66 |         80.55 |          76.3  |        64.43 |           73.53 |             84.25 |         5.84 |
|              11 | NAT       | NAT       | US       |                1.45 |                     0.06 |    -0.03 |      0.2  |                  78.02 |                        75.49 |         79.23 |         73.38 |          71.02 |        66.96 |           88.46 |             43.18 |         4.75 |
|              12 | C5H.IR    | C5H.IR    | EUROPE   |                1.71 |                     0.03 |     0.02 |      0.07 |                  47.88 |                        75.33 |         80.78 |         71.04 |          72.99 |        75.21 |           98.03 |             54.35 |         2.79 |
|              13 | PBR-A     | PBR-A     | US       |              112.22 |                     0.05 |    -0    |      0.11 |                  67.29 |                        74.85 |         77.8  |         73.33 |          71.07 |        78.58 |           75.96 |             71.1  |         4.62 |
|              14 | PAA       | PAA       | US       |               15.21 |                     0.06 |    -0.02 |     -0.04 |                  73.01 |                        74.53 |         60.28 |         68.16 |          72.82 |        73.92 |           88.06 |             79.25 |         2.05 |
|              15 | EQNR      | EQNR      | US       |               88.07 |                     0.08 |    -0.01 |      0.02 |                  59.3  |                        73.96 |         69.04 |         73.46 |          72.42 |        72.66 |           77.26 |             85.9  |         5.73 |
|              16 | CVX       | CVX       | US       |              355.79 |                     0.05 |     0.01 |      0.02 |                  65.33 |                        73.87 |         74.84 |         70.16 |          65.01 |        64.44 |           68.85 |             85.9  |         3.58 |
|              17 | ARGX.BR   | ARGX.BR   | EUROPE   |               53.12 |                     0.06 |    -0    |     -0.04 |                  65.8  |                        73.55 |         61.81 |         66.01 |          68.27 |        61.84 |           92.86 |             80.66 |         6.21 |
|              18 | DOCU      | DOCU      | US       |               11    |                     0.07 |    -0.02 |      0.05 |                  69.69 |                        73.32 |         71.15 |         75.89 |          64.99 |        57.97 |           63.7  |             81.19 |         7.92 |
|              19 | HOOD      | HOOD      | US       |               92.03 |                     0.07 |    -0.06 |      0.12 |                  80.06 |                        73.24 |         71.12 |         69.91 |          62.07 |        51.38 |           69.13 |             78.97 |         8.89 |
|              20 | UGP       | UGP       | US       |                6.68 |                     0.07 |    -0.06 |      0.11 |                  77.84 |                        72.99 |         66.77 |         75.93 |          71.04 |        65.67 |           65.01 |             68.94 |         5.04 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | JPM      | JPMorgan Chase & Co. | US       |              786.36 |             53.91 |         46.53 |         55.72 |          55.49 |        52.33 |           47.62 |             69.35 |             49.91 |         2.92 |             81.49 | swing              |                -0.4 |                  0.02 |                 0.06 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | AMC      | AMC    | US       |                2.58 |             82.79 |         86    |         89.36 |          79.57 |        78.96 |           85.96 |             78.55 |            nan    |         9.51 |             65.07 | swing              |                6.6  |                  4.78 |                 4.36 |
|    360 | ITRG     | ITRG   | US       |                0.46 |             54.07 |         37.63 |         53.58 |          54.56 |        63    |           59.4  |             61.54 |             79.54 |         8.27 |             68.32 | long               |               -1.73 |                  4.11 |                 4.54 |
|    239 | SPM.MI   | SPM.MI | EUROPE   |                8.65 |             58.72 |         63.87 |         57.97 |          59.47 |        49.99 |          nan    |             59.78 |             25.46 |         3.88 |             70.3  | short              |               10.05 |                  4.03 |                 3.64 |
|     20 | BP       | BP     | US       |              100.57 |             75.11 |         79.95 |         73.26 |          71.7  |        76.96 |           88.63 |             91.73 |             58.77 |         4.54 |             72.34 | short              |               12.88 |                  3.79 |               nan    |
|     85 | AMS.SW   | AMS.SW | EUROPE   |                2.29 |             68.16 |         81.51 |         71.66 |          64.67 |        49.67 |           54.28 |             65.85 |             11.54 |         8.71 |             73.14 | short              |               -2.91 |                  3.71 |               nan    |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name    | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    660 | PAH3.DE  | PAH3.DE | EUROPE   |                7.77 |             31.95 |         27.81 |         28.03 |          35.86 |        59.96 |          nan    |             23.36 |             94.66 |         5.24 |             70.3  | long               |              -13.4  |                 -3.91 |                -3.24 |
|    589 | NCNO     | NCNO    | US       |                1.73 |             41.28 |         27.54 |         50.13 |          44.11 |        38.45 |           22.4  |             51.47 |             50.73 |         7.74 |             71.66 | swing              |              -10.18 |                 -3.71 |                -2.84 |
|    641 | 0JHU.IL  | 0JHU.IL | OTHER    |                8.13 |             35.76 |         20    |         29.94 |          41.59 |        71.86 |          nan    |            nan    |             97.62 |         5.27 |             60    | long               |               -1.85 |                 -3.39 |                -3.44 |
|    463 | ESTC     | ESTC    | US       |                8.11 |             50.04 |         49.1  |         64.3  |          50.99 |        35.35 |           25.28 |             51.16 |             20.88 |         8.5  |             72.11 | swing              |              nan    |                 -3.29 |                -2.8  |
|    317 | PD       | PD      | US       |                1    |             55.73 |         66.68 |         63.74 |          47.73 |        40.26 |           29.29 |             23.98 |             53.35 |         8.5  |             72.68 | short              |               -8.76 |                 -3.24 |                -2.91 |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_63d_rank` vs `sector_score`: r=0.94
- `relative_63d_rank` vs `sector_score`: r=0.93
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
- Excluded by hard/data filters: **306**
- Event watch (otherwise eligible): **1**
- Final eligible: **693**
- Eligible change vs previous stored run: **-16**

Top exclusion categories:
- liquidity: 243
- price: 190
- market_cap: 166
- price_history: 20
- data_confidence: 14
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| VLO | 2 |  | 1 |  | 2 | main,pullback |
| CMBT.BR | 4 |  | 5 |  | 2 | main,pullback |
| FRO | 5 |  | 3 |  | 2 | main,pullback |
| MU | 6 |  | 7 |  | 2 | main,pullback |
| DHT | 10 |  | 4 |  | 2 | main,pullback |
| NVDA | 24 | 3 |  | 1 | 1 | value,quality_value |
| SAP.DE | 218 | 6 |  | 8 | 1 | value,quality_value |
| VOLV-B.ST | 333 | 1 | 210 | 2 | 1 | value,quality_value |
| NOVN.SW | 335 | 7 |  | 6 | 1 | value,quality_value |
| AVGO | 401 | 5 | 144 | 5 | 1 | value,quality_value |
| NOVO-B.CO | 541 | 2 |  | 3 | 1 | value,quality_value |
| HOS | 563 | 4 |  | 4 | 1 | value,quality_value |
| AMC | 1 |  |  |  | 1 | main |
| HPE | 3 |  |  |  | 1 | main |
| SHELL.AS | 7 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **2** (SHELL.AS, KIN.BR)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | AVGO | value+pullback | 70.46 | 60.81 | 80.97 | 87.89 | 36.78 | 75.58 | 52.53 |
| 2 | VOLV-B.ST | value+pullback | 68.53 | 89.18 | 71.99 | 49.24 | 61.20 | 51.39 | 55.05 |
| 3 | PAA | pullback | 56.44 | 55.06 | 73.01 | 88.06 | 79.25 | 85.27 | 70.49 |
| 4 | VLO | pullback | 55.96 | 47.48 | 72.11 | 87.72 | 82.07 | 82.82 | 82.65 |
| 5 | ABI.BR | pullback | 55.38 | 47.31 | 75.88 | 84.52 | 74.99 | 81.15 | 57.76 |
| 6 | BEN | pullback | 55.35 | 54.63 | 76.66 | 83.63 | 76.86 | 79.76 | 68.50 |
| 7 | NOKIA.HE | value+pullback | 54.89 | 70.80 | 76.44 | 15.87 | 45.10 | 38.24 | 47.44 |
| 8 | DHT | pullback | 54.86 | 56.70 | 75.58 | 89.22 | 70.00 | 77.92 | 77.78 |
| 9 | ORSTED.CO | pullback | 54.60 | 48.30 | 80.75 | 64.47 | 97.88 | 74.75 | 57.58 |
| 10 | FRO | pullback | 54.44 | 56.67 | 74.92 | 92.11 | 65.57 | 76.68 | 80.03 |
| 11 | ARGX.BR | pullback | 54.42 | 36.13 | 65.80 | 92.86 | 80.66 | 79.87 | 63.93 |
| 12 | CMBT.BR | pullback | 54.23 | 55.11 | 64.75 | 96.04 | 70.35 | 82.98 | 80.96 |
| 13 | AOD | pullback | 53.33 | 52.65 | 75.35 | 83.15 |  | 85.10 | 64.83 |
| 14 | PSX | pullback | 53.27 | 50.95 | 67.38 | 80.66 | 84.25 | 79.52 | 77.02 |
| 15 | NVDA | value | 52.99 | 61.64 | 38.23 | 82.61 | 72.48 | 74.29 | 74.57 |
| 16 | MU | pullback | 52.78 | 48.22 | 57.81 | 95.03 | 84.24 | 78.23 | 79.32 |
| 17 | CYH | value+pullback | 52.74 | 74.87 | 63.43 | 29.67 | 27.17 | 36.26 | 41.27 |
| 18 | LION | pullback | 52.66 | 45.05 | 82.71 | 56.02 | 99.00 | 68.39 | 52.44 |
| 19 | BIT | pullback | 52.49 | 47.40 | 81.43 |  |  | 98.13 | 36.90 |
| 20 | HEIA.AS | pullback | 52.37 | 46.36 | 75.18 | 80.45 | 64.15 | 75.46 | 52.43 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 8 / 2 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 20 / 5 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 73.1 | 34 / 16 |

Top-10 market-cap mix: small_1_5b=4, mid_5_20b=1, large_20_100b=3, mega_100b_plus=2
