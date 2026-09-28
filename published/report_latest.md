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

- **EUROPE:** 77.7/100
- **OTHER:** 65.0/100
- **US:** 83.2/100

## Main multi-horizon ranking

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | HPE       | HPE       | US       |               73.45 |             84.67 |         90.13 |         87.61 |          81.72 |        72.9  |           70.46 |             81.59 |             55.18 |         6.89 |             72.34 | short              |                3.31 |                  0.97 |               nan    |
|      2 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.91 |             84.08 |         77.63 |         83.49 |          85.12 |        84.67 |           95.88 |             68.79 |             69.02 |         3.68 |             73.14 | medium             |               -0.11 |                  1.58 |                 1.44 |
|      3 | MU        | MU        | US       |             1074.59 |             83.37 |         80.67 |         73.63 |          86.37 |        86.07 |           94.67 |             82.08 |             74.98 |         8.08 |             73.14 | medium             |                2.6  |                  2.89 |                 2.23 |
|      4 | DELL      | DELL      | US       |              314.64 |             83.14 |         86.51 |         86.01 |          80.28 |        68.27 |           70.7  |             81.87 |             36.78 |         7.82 |             70.16 | short              |               -0.48 |                  0.18 |                -0.02 |
|      5 | VLO       | VLO       | US       |               98.01 |             82.81 |         79.94 |         86.4  |          84.61 |        81.02 |           83.88 |             80.63 |             66.3  |         3.56 |             66.43 | swing              |               -2.93 |                  1.1  |                 1    |
|      6 | FRO       | FRO       | US       |                9.34 |             81.78 |         80.14 |         82.59 |          82.34 |        81.21 |           89.67 |             66.06 |             66.48 |         5.06 |             73.14 | swing              |               -3.14 |                  0.48 |                 0.44 |
|      7 | SHELL.AS  | SHELL.AS  | EUROPE   |              244.61 |             81.45 |         86.36 |         80.25 |          76.73 |        82.65 |           93.14 |             79.96 |             69.35 |         2.39 |             73.14 | short              |                7.3  |                  3.48 |                 3.13 |
|      8 | AMC       | AMC       | US       |                2.31 |             81.25 |         82.3  |         86.76 |          80.2  |        78.75 |           83.27 |             79.66 |            nan    |         9.48 |             65.07 | swing              |                5.05 |                  4.47 |                 4.13 |
|      9 | REP.MC    | REP.MC    | EUROPE   |               33.35 |             81.02 |         87.08 |         84.56 |          77.48 |        73.73 |           58.38 |             83.47 |             76.33 |         3.86 |             73.14 | short              |                6.36 |                  2.36 |                 1.85 |
|     10 | PSX       | PSX       | US       |               89.72 |             80.92 |         75.77 |         85.33 |          82.67 |        79.16 |           77.17 |             86.46 |             67.74 |         3.79 |             73.14 | swing              |               -2.94 |                  1.17 |                 1.22 |
|     11 | P         | P         | US       |               36.91 |             80.45 |         94.23 |         88.41 |          72.49 |        58.39 |           66.77 |             88.93 |             13.57 |         8.13 |             72.68 | short              |                3.08 |                  3.16 |                 2.3  |
|     12 | DHT       | DHT       | US       |                3.09 |             79.94 |         78.33 |         80.07 |          79.81 |        81.01 |           86.87 |             70.32 |             70.09 |         4.46 |             69.89 | long               |               -2.12 |                  0.71 |                 0.42 |
|     13 | SMTC      | SMTC      | US       |               14.96 |             79.56 |         85.73 |         82.71 |          76.4  |        62.18 |           71.44 |             84.72 |             14.89 |         8.42 |             73.14 | short              |                8.72 |                  0.88 |               nan    |
|     14 | AMD       | AMD       | US       |              905.06 |             78.65 |         86.08 |         81.56 |          75.75 |        62    |           76.69 |             73.73 |             11.64 |         7.15 |             69.09 | short              |                6.54 |                  2.26 |                 1.05 |
|     15 | KIN.BR    | KIN.BR    | EUROPE   |                1.35 |             78.61 |         80.16 |         83.31 |          77.07 |        68.28 |           88.91 |             65.72 |             23.43 |         3.64 |             73.14 | swing              |                0.87 |                 -0.01 |                -0.02 |
|     16 | OMV.VI    | OMV.VI    | EUROPE   |               23.75 |             78.56 |         81    |         82.43 |          76.13 |        72.91 |           60.39 |             86.11 |             72.29 |         1.94 |             72.34 | swing              |                7.34 |                  1.6  |                 0.98 |
|     17 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.23 |             78.38 |         80.39 |         80.7  |          76.37 |        75.96 |           68.08 |             75.01 |             78.36 |         5.47 |             73.14 | swing              |                7.25 |                  1.68 |               nan    |
|     18 | ABN.AS    | ABN.AS    | EUROPE   |               35.56 |             76.71 |         76.23 |         79.35 |          77.19 |        72.98 |           78.38 |             66.53 |             57.02 |         2.86 |             73.14 | swing              |                0.65 |                  1.53 |                 1.48 |
|     19 | BIRG.IR   | BIRG.IR   | EUROPE   |               18.96 |             76.48 |         77.71 |         74.86 |          75.25 |        78.48 |           96.52 |             56.89 |             62.06 |         2.15 |             73.14 | long               |                0.75 |                  1.95 |                 1.65 |
|     20 | C5H.IR    | C5H.IR    | EUROPE   |                1.69 |             76.37 |         81.64 |         72.67 |          74.54 |        78.2  |           97.93 |             54.67 |             60.75 |         2.67 |             73.14 | short              |                4.71 |                  1.93 |               nan    |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BBWI     | Bath & Body Works, Inc.              | US       |                2.92 |                  75.58 |                    73.03 |                 71.45 |              71.12 |                72.36 |                   27.64 |           84.25 |             36.79 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|            2 | EMBC     | Embecta Corp.                        | US       |                0.29 |                  75.2  |                    72.55 |                 73.3  |              72.81 |                66.45 |                   33.55 |           77.71 |             67.13 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               39.46 |                  69.74 |                    72.27 |                 74.11 |              69.49 |                68.52 |                   31.48 |           85.32 |            nan    |       0.438 |         nan |       nan |        7.45 |       nan    |          2.57 |        0.61 |                 nan |              nan |                   9 |                  0.47 |
|            4 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.41 |                  72.12 |                    72.12 |                 74.04 |              71.22 |                67.46 |                   32.54 |           82.97 |             71.49 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              244.61 |                  58.22 |                    70.62 |                 74.58 |              65.64 |                87.36 |                   12.64 |           93.14 |             79.96 |     nan     |         nan |       nan |      nan    |         9.77 |         10.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHEL     | SHEL                                 | US       |              240.17 |                  67.42 |                    70.6  |                 71.45 |              70.11 |                75.34 |                   24.66 |           71.18 |             80.07 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                  | US       |                3.09 |                  61.21 |                    68.72 |                 71.37 |              64.97 |                77.03 |                   22.97 |           86.87 |             70.32 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | 1VOW3.MI | Volkswagen AG                        | EUROPE   |               35.78 |                  70.07 |                    68.7  |                 67.9  |              69.88 |                69.11 |                   30.89 |           63.27 |            nan    |       0.394 |         nan |       nan |       13.72 |       nan    |          6.84 |        0.59 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BP       | BP                                   | US       |               99.96 |                  56.38 |                    68.56 |                 72.5  |              64.46 |                82.43 |                   17.57 |           84.85 |             90.31 |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | STNE     | StoneCo Ltd.                         | OTHER    |                1.89 |                  68.99 |                    68.07 |                 68.22 |              65.46 |                67.4  |                   32.6  |           86.35 |             36.52 |       0.635 |         nan |       nan |        1.61 |         4.12 |          3.54 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            7 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              111.47 |                  75.59 |                    67.82 |                 67    |              71.7  |                50.9  |                   49.1  |           52.72 |             81.16 |       0.143 |         nan |       nan |        1.78 |         4.61 |          4.68 |        5.3  |                 nan |              nan |                  12 |                  0.63 |
|          nan | CMBT.BR  | CMBT.BR                              | EUROPE   |                4.91 |                  55.92 |                    67.79 |                 71.84 |              62    |                82.59 |                   17.41 |           95.88 |             68.79 |     nan     |         nan |       nan |      nan    |         9.3  |          6.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AGS.BR   | AGS.BR                               | EUROPE   |               15.61 |                  63.54 |                    67.65 |                 68.98 |              64.55 |                76.39 |                   23.61 |           85.41 |             50.51 |     nan     |         nan |       nan |      nan    |         8.69 |          7.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                                  | US       |               15.15 |                  56.38 |                    67.48 |                 70.88 |              63.43 |                83.47 |                   16.53 |           85.1  |             78.12 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                               | EUROPE   |              179.13 |                  62.91 |                    67.34 |                 68.43 |              67.17 |                74.26 |                   25.74 |           64.82 |             85.15 |     nan     |         nan |       nan |      nan    |         8.84 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                                  | US       |                9.34 |                  58.62 |                    67.03 |                 70.09 |              62.47 |                75.87 |                   24.13 |           89.67 |             66.06 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            8 | UNIT     | Uniti Group Inc.                     | US       |                1.9  |                  78.52 |                    67.02 |                 64.13 |              69.17 |                52.41 |                   47.59 |           64.51 |             32.04 |      -0.113 |         nan |       nan |        8.78 |       -12.55 |          2.32 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|            9 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.4  |                  63.62 |                    66.94 |                 69.22 |              63.34 |                79.12 |                   20.88 |           95.11 |             32.97 |       0.081 |         nan |       nan |        3.82 |         5    |          4.32 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BEN      | BEN                                  | US       |               14.75 |                  57.02 |                    66.75 |                 69.88 |              62.84 |                79.61 |                   20.39 |           84.36 |             74.57 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | WB       | Weibo Corporation                    | OTHER    |                1.4  |                  71.58 |                    66.7  |                 65    |              65.36 |                65.84 |                   34.16 |           79.82 |             19.72 |     nan     |         nan |       nan |        1.72 |         5.06 |          5.36 |        0.79 |                 nan |              nan |                   9 |                  0.47 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              244.61 |                  58.22 |                    70.62 |                 74.58 |              65.64 |                87.36 |                   12.64 |           93.14 |             79.96 |     nan     |         nan |       nan |      nan    |         9.77 |         10.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | 0P6O.IL  | Volkswagen AG              | OTHER    |               39.46 |                  69.74 |                    72.27 |                 74.11 |              69.49 |                68.52 |                   31.48 |           85.32 |            nan    |       0.438 |         nan |       nan |        7.45 |       nan    |          2.57 |        0.61 |                 nan |              nan |                   9 |                  0.47 |
|            4 | PARR     | Par Pacific Holdings, Inc. | US       |                3.41 |                  72.12 |                    72.12 |                 74.04 |              71.22 |                67.46 |                   32.54 |           82.97 |             71.49 |       0.021 |         nan |       nan |        3.8  |         5.6  |          4.55 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | EMBC     | Embecta Corp.              | US       |                0.29 |                  75.2  |                    72.55 |                 73.3  |              72.81 |                66.45 |                   33.55 |           77.71 |             67.13 |       0.413 |         nan |       nan |        5.76 |         3.35 |          4.01 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BP       | BP                         | US       |               99.96 |                  56.38 |                    68.56 |                 72.5  |              64.46 |                82.43 |                   17.57 |           84.85 |             90.31 |     nan     |         nan |       nan |      nan    |         8.63 |         21.12 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CMBT.BR  | CMBT.BR                    | EUROPE   |                4.91 |                  55.92 |                    67.79 |                 71.84 |              62    |                82.59 |                   17.41 |           95.88 |             68.79 |     nan     |         nan |       nan |      nan    |         9.3  |          6.51 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            1 | BBWI     | Bath & Body Works, Inc.    | US       |                2.92 |                  75.58 |                    73.03 |                 71.45 |              71.12 |                72.36 |                   27.64 |           84.25 |             36.79 |       0.231 |         nan |       nan |        5.52 |         5.9  |          4.32 |        0.67 |                 nan |              nan |                  11 |                  0.58 |
|          nan | SHEL     | SHEL                       | US       |              240.17 |                  67.42 |                    70.6  |                 71.45 |              70.11 |                75.34 |                   24.66 |           71.18 |             80.07 |     nan     |         nan |       nan |      nan    |         9.25 |         10.58 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                        | US       |                3.09 |                  61.21 |                    68.72 |                 71.37 |              64.97 |                77.03 |                   22.97 |           86.87 |             70.32 |     nan     |         nan |       nan |      nan    |        10.15 |          7.41 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PAA      | PAA                        | US       |               15.15 |                  56.38 |                    67.48 |                 70.88 |              63.43 |                83.47 |                   16.53 |           85.1  |             78.12 |     nan     |         nan |       nan |      nan    |        12.8  |         20.87 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.96 |                  55.99 |                    66.61 |                 70.18 |              60.78 |                82.12 |                   17.88 |           96.52 |             56.89 |     nan     |         nan |       nan |      nan    |        10.96 |         14.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                9.34 |                  58.62 |                    67.03 |                 70.09 |              62.47 |                75.87 |                   24.13 |           89.67 |             66.06 |     nan     |         nan |       nan |      nan    |        10.43 |          7.16 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | MU       | MU                         | US       |             1074.59 |                  49.82 |                    64.67 |                 70.03 |              58.04 |                77.53 |                   22.47 |           94.67 |             82.08 |     nan     |         nan |       nan |      nan    |         6.76 |         24.45 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.75 |                  57.02 |                    66.75 |                 69.88 |              62.84 |                79.61 |                   20.39 |           84.36 |             74.57 |     nan     |         nan |       nan |      nan    |        10.35 |         22.46 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | A5G.IR   | A5G.IR                     | EUROPE   |               24.39 |                  55.84 |                    66.09 |                 69.57 |              60.24 |                80.97 |                   19.03 |           96.42 |             54.62 |     nan     |         nan |       nan |      nan    |        11.74 |         12.01 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | GSL      | Global Ship Lease, Inc.    | OTHER    |                1.4  |                  63.62 |                    66.94 |                 69.22 |              63.34 |                79.12 |                   20.88 |           95.11 |             32.97 |       0.081 |         nan |       nan |        3.82 |         5    |          4.32 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | AGS.BR   | AGS.BR                     | EUROPE   |               15.61 |                  63.54 |                    67.65 |                 68.98 |              64.55 |                76.39 |                   23.61 |           85.41 |             50.51 |     nan     |         nan |       nan |      nan    |         8.69 |          7.67 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | INVA     | Innoviva, Inc.             | US       |                1.32 |                  54.35 |                    64.92 |                 68.95 |              60.05 |                86.43 |                   13.57 |           94    |             53.55 |       0.074 |         nan |       nan |        6.4  |         9.38 |          4.81 |        3.1  |                 nan |              nan |                  10 |                  0.53 |
|          nan | C5H.IR   | C5H.IR                     | EUROPE   |                1.69 |                  52.71 |                    64.54 |                 68.56 |              58.01 |                81.08 |                   18.92 |           97.93 |             54.67 |     nan     |         nan |       nan |      nan    |        10.57 |         10.92 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | TTE.PA   | TTE.PA                     | EUROPE   |              179.13 |                  62.91 |                    67.34 |                 68.43 |              67.17 |                74.26 |                   25.74 |           64.82 |             85.15 |     nan     |         nan |       nan |      nan    |         8.84 |         11.62 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol    | name      | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:----------|:----------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | VLO       | VLO       | US       |               98.01 |                     0.06 |    -0.06 |      0.12 |                  84.21 |                        84.7  |         79.94 |         86.4  |          84.61 |        81.02 |           83.88 |             80.63 |         3.56 |
|               2 | PSX       | PSX       | US       |               89.72 |                     0.07 |    -0.06 |      0.07 |                  81.77 |                        83.34 |         75.77 |         85.33 |          82.67 |        79.16 |           77.17 |             86.46 |         3.79 |
|               3 | CMBT.BR   | CMBT.BR   | EUROPE   |                4.91 |                     0.06 |    -0.02 |      0.08 |                  72.54 |                        82.12 |         77.63 |         83.49 |          85.12 |        84.67 |           95.88 |             68.79 |         3.68 |
|               4 | FRO       | FRO       | US       |                9.34 |                     0.07 |    -0.07 |      0.16 |                  81.39 |                        81.35 |         80.14 |         82.59 |          82.34 |        81.21 |           89.67 |             66.06 |         5.06 |
|               5 | DHT       | DHT       | US       |                3.09 |                     0.06 |    -0.06 |      0.13 |                  83.92 |                        80.55 |         78.33 |         80.07 |          79.81 |        81.01 |           86.87 |             70.32 |         4.46 |
|               6 | DELL      | DELL      | US       |              314.64 |                     0.04 |    -0.01 |      0.19 |                  66.28 |                        79.62 |         86.51 |         86.01 |          80.28 |        68.27 |           70.7  |             81.87 |         7.82 |
|               7 | BP        | BP        | US       |               99.96 |                     0.06 |    -0.01 |      0.04 |                  70.65 |                        78.65 |         75.07 |         73.75 |          73.06 |        80.05 |           84.85 |             90.31 |         4.47 |
|               8 | CIRSA.MC  | CIRSA.MC  | EUROPE   |                3.18 |                     0.05 |    -0.02 |      0.37 |                  72.71 |                        78.05 |         83.7  |         80.35 |          71.14 |        71.48 |           82.09 |             59.19 |         5.28 |
|               9 | TRMD-A.CO | TRMD-A.CO | EUROPE   |                3.23 |                     0.06 |    -0.05 |      0.12 |                  80.31 |                        77.26 |         80.39 |         80.7  |          76.37 |        75.96 |           68.08 |             75.01 |         5.47 |
|              10 | C5H.IR    | C5H.IR    | EUROPE   |                1.69 |                     0.04 |     0.01 |      0.1  |                  56.03 |                        77.01 |         81.64 |         72.67 |          74.54 |        78.2  |           97.93 |             54.67 |         2.67 |
|              11 | NAT       | NAT       | US       |                1.44 |                     0.06 |    -0.06 |      0.19 |                  83.85 |                        75.6  |         77.94 |         75.62 |          73.66 |        70.75 |           85.43 |             46.46 |         4.63 |
|              12 | EQNR      | EQNR      | US       |               87.93 |                     0.08 |    -0.04 |      0.02 |                  69.28 |                        75.4  |         64.67 |         75.38 |          74.48 |        76.23 |           72.29 |             85.73 |         5.62 |
|              13 | DNORD.CO  | DNORD.CO  | EUROPE   |                1.39 |                     0.05 |    -0.05 |      0.05 |                  85.48 |                        75.07 |         70.16 |         74.76 |          68.91 |        61.54 |           79.38 |             59.95 |         4.77 |
|              14 | ARGX.BR   | ARGX.BR   | EUROPE   |               52.6  |                     0.08 |    -0.03 |     -0.04 |                  65.58 |                        74.63 |         57.33 |         68.09 |          70.07 |        63.47 |           92.99 |             81    |         6.12 |
|              15 | NESTE.HE  | NESTE.HE  | EUROPE   |               26.45 |                     0.04 |     0.01 |      0.08 |                  59.1  |                        74.53 |         81.09 |         78.76 |          72.2  |        63.98 |           60.77 |             86.42 |         4.9  |
|              16 | PAA       | PAA       | US       |               15.15 |                     0.06 |    -0.04 |     -0.04 |                  75.96 |                        74.4  |         56.05 |         68.54 |          74.13 |        77.55 |           85.1  |             78.12 |         2.03 |
|              17 | TEAM      | TEAM      | US       |               41.78 |                     0.04 |    -0.02 |      0.01 |                  68.38 |                        74.27 |         69.16 |         84.6  |          67.26 |        48.33 |           40.42 |             90.86 |         9.5  |
|              18 | SHEL      | SHEL      | US       |              240.17 |                     0.03 |     0.01 |      0.06 |                  52.79 |                        73.68 |         79.03 |         75.56 |          71.04 |        76.76 |           71.18 |             80.07 |         2.94 |
|              19 | AZE.BR    | AZE.BR    | EUROPE   |                2.89 |                     0.06 |    -0.01 |     -0.05 |                  72.84 |                        73.35 |         58.53 |         75.32 |          69.29 |        62.84 |           66.77 |             76.06 |         5.56 |
|              20 | GTLB      | GTLB      | US       |                6.86 |                     0.07 |    -0.05 |      0.05 |                  76.83 |                        73.08 |         70.14 |         79.41 |          63.67 |        48.89 |           55.28 |             71.98 |         8.36 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | TLRY     | Tilray Brands, Inc. | OTHER    |                0.51 |             32.04 |         33.34 |         23.34 |          30.74 |        41.05 |           58.97 |             33.23 |             37.05 |         8.91 |             78.44 | long               |                6.85 |                  0.91 |                  0.8 |

## Fastest improving (5 stored runs)

|   rank | symbol   | name   | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    316 | ITRG     | ITRG   | US       |                0.49 |             58.57 |         49.75 |         58.74 |          58.4  |        65.79 |           54.67 |             63.87 |             89.37 |         8.15 |             68.32 | long               |                2.77 |                  5.01 |                 5.21 |
|    322 | HUT      | HUT    | US       |               10.49 |             58.42 |         67.9  |         55.57 |          61.26 |        47.35 |           37.44 |             78.5  |             21.15 |         8.54 |             66.84 | short              |              nan    |                  4.94 |               nan    |
|      8 | AMC      | AMC    | US       |                2.31 |             81.25 |         82.3  |         86.76 |          80.2  |        78.75 |           83.27 |             79.66 |            nan    |         9.48 |             65.07 | swing              |                5.05 |                  4.47 |                 4.13 |
|     60 | AMS.SW   | AMS.SW | EUROPE   |                2.07 |             71.96 |         72.3  |         76.62 |          71.62 |        55.64 |           53.58 |             87.22 |             18.03 |         8.64 |             73.14 | swing              |                0.88 |                  4.46 |               nan    |
|     61 | NNBR     | NNBR   | US       |                0.27 |             71.93 |         73.27 |         78.79 |          70.58 |        52.64 |           32.9  |             94.35 |             32.62 |         8.84 |             72.11 | swing              |               22.81 |                  4.3  |                 3.08 |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name                         | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    688 | 0JHU.IL  | Porsche Automobil Holding SE | OTHER    |                8.2  |             29.23 |         21.22 |         26.6  |          31.86 |        38.62 |           38.77 |            nan    |             43.12 |         5.74 |             66.3  | long               |               -8.38 |                 -4.7  |                -4.42 |
|    463 | TEVA     | TEVA                         | US       |               40.18 |             52.95 |         66.9  |         58.34 |          47.56 |        40.32 |           12.18 |             30.93 |             53.87 |         4.83 |             72.34 | short              |               -2.06 |                 -3.36 |                -3.51 |
|    654 | BAS.DE   | BAS.DE                       | EUROPE   |               43.81 |             38.88 |         39.08 |         42.72 |          38.68 |        37    |           25.42 |             32.51 |             34.54 |         2.23 |             67.86 | swing              |               -2.37 |                 -3.33 |               nan    |
|    648 | TIT.MI   | TIT.MI                       | EUROPE   |               15.23 |             39.58 |         37.16 |         41.99 |          44.99 |        34.08 |           16.53 |             54.13 |             20    |         2.18 |             71.32 | medium             |               -9.85 |                 -2.94 |                -2.72 |
|    571 | NCNO     | NCNO                         | US       |                1.8  |             46.23 |         32.55 |         55.6  |          48.02 |        44.45 |           23.36 |             54.69 |             63.9  |         7.58 |             71.66 | swing              |               -5.22 |                 -2.72 |                -2.1  |

## Duplicate-security checks

- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.98
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
- Excluded by hard/data filters: **296**
- Event watch (otherwise eligible): **1**
- Final eligible: **703**
- Eligible change vs previous stored run: **-6**

Top exclusion categories:
- liquidity: 240
- price: 182
- market_cap: 145
- price_history: 21
- data_confidence: 11
- duplicate_listing: 2
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| CMBT.BR | 2 |  | 3 |  | 2 | main,pullback |
| DELL | 4 |  | 6 |  | 2 | main,pullback |
| VLO | 5 |  | 1 |  | 2 | main,pullback |
| FRO | 6 |  | 4 |  | 2 | main,pullback |
| PSX | 10 |  | 2 |  | 2 | main,pullback |
| PARR | 52 | 4 | 23 | 2 | 1 | value,quality_value |
| PBR-A | 75 | 7 | 31 | 9 | 1 | value,quality_value |
| EMBC | 133 | 2 |  | 3 | 1 | value,quality_value |
| GSL | 170 | 9 | 71 | 5 | 1 | value,quality_value |
| 0P6O.IL | 569 | 3 |  | 1 | 1 | value,quality_value |
| STNE | 605 | 6 | 318 | 7 | 1 | value,quality_value |
| BBWI | 639 | 1 |  | 4 | 1 | value,quality_value |
| 1VOW3.MI | 649 | 5 |  | 8 | 1 | value,quality_value |
| HPE | 1 |  |  |  | 1 | main |
| MU | 3 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **5** (HPE, MU, SHELL.AS, AMC, REP.MC)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | GSL | value+pullback | 70.98 | 63.62 | 74.01 | 95.11 | 32.97 | 79.12 | 64.57 |
| 2 | PARR | value+pullback | 70.76 | 72.12 | 64.14 | 82.97 | 71.49 | 67.46 | 72.69 |
| 3 | PBR-A | value+pullback | 67.54 | 75.59 | 74.65 | 52.72 | 81.16 | 50.90 | 70.66 |
| 4 | CVX | value+pullback | 66.34 | 60.14 | 74.06 | 63.84 | 70.58 | 65.72 | 65.60 |
| 5 | WB | value+pullback | 64.30 | 71.58 | 62.83 | 79.82 | 19.72 | 65.84 | 39.41 |
| 6 | IRS | value+pullback | 63.28 | 68.71 | 69.38 | 63.27 | 41.33 | 58.47 | 46.67 |
| 7 | STNE | value+pullback | 62.79 | 68.99 | 48.05 | 86.35 | 36.52 | 67.40 | 43.87 |
| 8 | AVK | value+pullback | 62.17 | 58.98 | 71.14 | 64.35 | 50.49 | 59.97 | 47.94 |
| 9 | PKX | value+pullback | 62.07 | 57.54 | 50.59 | 80.80 | 76.07 | 62.18 | 60.35 |
| 10 | GAB | value+pullback | 61.70 | 55.91 | 65.66 | 54.73 | 78.02 | 62.49 | 51.28 |
| 11 | LKFT.AS | value+pullback | 60.90 | 66.52 | 60.72 | 62.59 | 25.09 | 69.30 | 47.95 |
| 12 | CNC | value+pullback | 59.58 | 70.48 | 51.93 | 59.19 | 56.80 | 54.51 | 59.19 |
| 13 | ALL-PH | value+pullback | 58.84 | 59.68 | 49.33 | 72.96 | 47.80 | 64.40 | 53.76 |
| 14 | VLO | pullback | 57.83 | 49.24 | 84.21 | 83.88 | 80.63 | 80.65 | 82.81 |
| 15 | MFA | value+pullback | 57.08 | 56.50 | 57.56 | 74.83 | 28.47 | 58.33 | 39.79 |
| 16 | DHT | pullback | 56.45 | 61.21 | 83.92 | 86.87 | 70.32 | 77.03 | 79.94 |
| 17 | PSX | pullback | 56.41 | 52.14 | 81.77 | 77.17 | 86.46 | 78.71 | 80.92 |
| 18 | PAA | pullback | 56.26 | 56.38 | 75.96 | 85.10 | 78.12 | 83.47 | 71.34 |
| 19 | CMBT.BR | pullback | 55.91 | 55.92 | 72.54 | 95.88 | 68.79 | 82.59 | 84.08 |
| 20 | BP | pullback | 55.91 | 56.38 | 70.65 | 84.85 | 90.31 | 82.43 | 74.41 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 73.1 | 5 / 5 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 73.1 | 14 / 11 |
| Top 50 | 48/50 | 49/50 | 49/50 | 46/50 | 0/50 | 72.5 | 24 / 26 |

Top-10 market-cap mix: small_1_5b=2, mid_5_20b=1, large_20_100b=4, mega_100b_plus=3
