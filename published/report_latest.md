# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-21

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

- **EUROPE:** 87.1/100
- **OTHER:** 74.9/100
- **US:** 83.4/100

## Main multi-horizon ranking

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | BAX      | BAX           | US       |               11.7  |             77.93 |         79.68 |         83.19 |          76.18 |        74.12 |           77.34 |             97.07 |             61.04 |         5.88 |             66.02 | swing              |               14.04 |                 -0.17 |                  nan |
|      2 | MU       | MU            | US       |              942.63 |             77.91 |         58.67 |         72.12 |          83.7  |        84.53 |           95.36 |             57.39 |             75.24 |         8.12 |             64.25 | long               |              nan    |                nan    |                  nan |
|      3 | PGEN     | PGEN          | US       |                2.27 |             77.63 |         91.9  |         85.22 |          70.04 |        52.44 |           67.1  |            nan    |              1.62 |         7.64 |             62.84 | short              |                5.85 |                  2.36 |                  nan |
|      4 | BION.SW  | BB Biotech AG | EUROPE   |                3.26 |             77.26 |         77.79 |         74.3  |          76.72 |        80.89 |           87.62 |             58.75 |             80.62 |         2.2  |             79.55 | long               |                2.6  |                  1.69 |                  nan |
|      5 | CCC      | CCC           | US       |                3.76 |             76.96 |         83.53 |         80.85 |          73.06 |        72.12 |           87.08 |             80.37 |             57.15 |         7.95 |             66.02 | short              |                2.88 |                  0.43 |                  nan |
|      6 | PSX      | PSX           | US       |               82.03 |             76.85 |         78.71 |         78.04 |          75.66 |        73.55 |           79.24 |             53.54 |             63.74 |         3.43 |             67.5  | short              |                1.84 |                nan    |                  nan |
|      7 | AMC      | AMC           | US       |                1.89 |             76.78 |         58.11 |         80.55 |          77.1  |        76.46 |           82.15 |             79.27 |            nan    |         9.65 |             61.25 | swing              |              nan    |                nan    |                  nan |
|      8 | GH       | GH            | US       |               19.3  |             76.71 |         76.19 |         80.18 |          77.24 |        72.05 |           62.46 |             68.66 |            nan    |         6.43 |             62.73 | swing              |               14.45 |                  0.61 |                  nan |
|      9 | NAT      | NAT           | US       |                1.27 |             76.49 |         75.34 |         79.66 |          77.64 |        70.16 |           78.57 |             73.17 |             40.53 |         4.57 |             66.7  | swing              |              nan    |                nan    |                  nan |
|     10 | KOS      | KOS           | US       |                1.54 |             76.4  |         77.78 |         69.95 |          79.55 |        75.01 |          nan    |             89.27 |             64.83 |         8.56 |             64.66 | medium             |              nan    |                nan    |                  nan |
|     11 | NIQ      | NIQ           | US       |                4.59 |             76.37 |         85.37 |         87.15 |          67.38 |        57.96 |           46.53 |             94.83 |             51.13 |         9.03 |             61.25 | swing              |              nan    |                  0.22 |                  nan |
|     12 | DAR      | DAR           | US       |                9.17 |             76.34 |         75.46 |         72.28 |          77.22 |        79.19 |           91.84 |             61.1  |             65.57 |         3.75 |             65.68 | long               |              nan    |                nan    |                  nan |
|     13 | U        | U             | US       |               17.55 |             76.26 |         85.31 |         86.43 |          67.21 |        50.29 |           44.46 |             96.95 |             20.81 |         8.34 |             67.5  | swing              |                2.61 |                  0.06 |                  nan |
|     14 | HPE      | HPE           | US       |               60    |             76.08 |         61.15 |         79.95 |          79.84 |        72.31 |           70.1  |             72.9  |             59.16 |         6.78 |             62.43 | swing              |                1.77 |                 -1.03 |                  nan |
|     15 | FRO      | FRO           | US       |                8.31 |             75.79 |         75.48 |         73.5  |          76.5  |        76.1  |           83.45 |             64.15 |             63.73 |         5.14 |             67.5  | medium             |              nan    |                  0.39 |                  nan |
|     16 | NOEJ.DE  | NOEJ.DE       | EUROPE   |                0.57 |             75.49 |         80.48 |         75.54 |          75.44 |        69.73 |           94.24 |             89.02 |             26.1  |         4.23 |             65.68 | short              |              nan    |                nan    |                  nan |
|     17 | TWN      | TWN           | US       |                0.48 |             75.44 |         68.64 |         70.32 |          80.76 |        80.56 |           76.84 |            nan    |             84.53 |         5.03 |             58.41 | medium             |                9.27 |                  1.52 |                  nan |
|     18 | TWST     | TWST          | US       |                7.32 |             75.39 |         85.72 |         81.62 |          69.16 |        49.75 |           46.77 |             74.05 |              7.62 |         6.98 |             62.59 | short              |                0.79 |                  0.1  |                  nan |
|     19 | W        | W             | US       |               11.68 |             75.36 |         84.1  |         80.51 |          70.21 |        54.32 |          nan    |             95.98 |             19.49 |         8.71 |             63.75 | short              |                5.44 |                  1.08 |                  nan |
|     20 | ERO      | ERO           | US       |                3.22 |             75.15 |         83.63 |         71.61 |          71.97 |        78.34 |           82.86 |             46.34 |             80.66 |         7.42 |             67.5  | short              |              nan    |                nan    |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.26 |                  74.19 |                    75.28 |                 77.27 |              75.1  |                87.78 |                   12.22 |           87.62 |             58.75 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.81 |                  77.14 |                    73.35 |                 73.02 |              72.08 |                70.27 |                   29.73 |           87.77 |             38.85 |       0.645 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | GSL      | Global Ship Lease, Inc.                                | OTHER    |                1.34 |                  79.95 |                    71.79 |                 70.61 |              73.7  |                69.07 |                   30.93 |           74.89 |             37    |       0.083 |         nan |       nan |        3.74 |         4.89 |          4.24 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras                   | OTHER    |               99.94 |                  78.74 |                    69.53 |                 67.93 |              73.7  |                56.97 |                   43.03 |           55.31 |             67.5  |       0.155 |         nan |       nan |        1.74 |         6.93 |          4.13 |        4.17 |                 nan |              nan |                  12 |                  0.63 |
|            5 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.7  |                  63.45 |                    69.24 |                 71.7  |              68.14 |                83.17 |                   16.83 |           77.82 |             74.8  |       0.071 |         nan |       nan |        3.89 |         8.36 |          5.35 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|            6 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.84 |                  65.64 |                    69.06 |                 72.2  |              67.26 |                73.33 |                   26.67 |           85.86 |             67.98 |     nan     |         nan |       nan |        3.7  |         9.93 |         29.08 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.5  |                  63.12 |                    68.71 |                 70.47 |              68.07 |                79.05 |                   20.95 |          nan    |             83.91 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              222.26 |                  61.38 |                    68.2  |                 70.63 |              63.57 |                78.39 |                   21.61 |           93.4  |             52.68 |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | DXC      | DXC Technology Company                                 | US       |                1.46 |                  84.67 |                    68.1  |                 62.83 |              73.17 |                48.13 |                   51.87 |           48.75 |             35.47 |       0.513 |         nan |       nan |        3.07 |         3.62 |         14.66 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|            8 | EMBC     | Embecta Corp.                                          | US       |                0.27 |                  74.15 |                    67.6  |                 66.46 |              69.72 |                59.01 |                   40.99 |           62.68 |             57.12 |       0.446 |         nan |       nan |        5.67 |         3.1  |          3.7  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.96 |                  58.42 |                    67.35 |                 69.94 |              64.66 |                81.01 |                   18.99 |           77.91 |             80.16 |     nan     |         nan |       nan |      nan    |       nan    |          4.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | DAC      | Danaos Corporation                                     | OTHER    |                2.32 |                  64.59 |                    67.15 |                 69.17 |              66.11 |                78.91 |                   21.09 |           80.65 |             54.02 |       0.002 |         nan |       nan |        3.98 |         6.07 |          5    |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|           10 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.56 |                  60.08 |                    66.63 |                 68.61 |              64.83 |                75.2  |                   24.8  |           72.93 |             80.41 |       0.028 |         nan |       nan |      nan    |       nan    |          3.73 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | BMY      | BMY                                                    | US       |              114.56 |                  62.87 |                    66.56 |                 67.81 |              64.1  |                72.8  |                   27.2  |           80.01 |             57.32 |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                                                    | US       |               14.78 |                  58.33 |                    66.44 |                 69.15 |              62.35 |                77.58 |                   22.42 |           86.71 |             63.96 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | IHS      | IHS Holding Limited                                    | OTHER    |                2.42 |                  72.16 |                    66.37 |                 65.9  |              70.73 |                58.72 |                   41.28 |           49.25 |             82.03 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | VOW.DE   | VOW.DE                                                 | EUROPE   |               37.92 |                  67.21 |                    66.36 |                 66.11 |              66.46 |                64.65 |                   35.35 |          nan    |             64.31 |     nan     |         nan |       nan |      nan    |         2.79 |          7.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           12 | RCI      | Rogers Communications Inc.                             | OTHER    |               16.82 |                  67.27 |                    66.31 |                 65.61 |              63.27 |                59.62 |                   40.38 |           80.98 |             41.03 |       0.281 |         nan |       nan |        7.3  |        10.33 |          4.44 |        0.86 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW3.DE  | VOW3.DE                                                | EUROPE   |               37.32 |                  67.72 |                    65.83 |                 65.31 |              66.03 |                61.71 |                   38.29 |          nan    |             61.66 |     nan     |         nan |       nan |      nan    |         3.16 |          7.14 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | PBR      | Petróleo Brasileiro S.A. - Petrobras                   | OTHER    |              104.94 |                  72.87 |                    65.81 |                 64.43 |              68.82 |                56.02 |                   43.98 |           55.31 |             62.69 |       0.148 |         nan |       nan |        1.8  |         4.77 |          4.73 |        4.64 |                 nan |              nan |                  12 |                  0.63 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                                                   | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW  | BB Biotech AG                                          | EUROPE   |                3.26 |                  74.19 |                    75.28 |                 77.27 |              75.1  |                87.78 |                   12.22 |           87.62 |             58.75 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            2 | STNE     | StoneCo Ltd.                                           | OTHER    |                1.81 |                  77.14 |                    73.35 |                 73.02 |              72.08 |                70.27 |                   29.73 |           87.77 |             38.85 |       0.645 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            6 | PKX      | POSCO Holdings Inc.                                    | OTHER    |               14.84 |                  65.64 |                    69.06 |                 72.2  |              67.26 |                73.33 |                   26.67 |           85.86 |             67.98 |     nan     |         nan |       nan |        3.7  |         9.93 |         29.08 |        0.89 |                 nan |              nan |                  10 |                  0.53 |
|            5 | TNK      | Teekay Tankers Ltd.                                    | OTHER    |                2.7  |                  63.45 |                    69.24 |                 71.7  |              68.14 |                83.17 |                   16.83 |           77.82 |             74.8  |       0.071 |         nan |       nan |        3.89 |         8.36 |          5.35 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | SHELL.AS | SHELL.AS                                               | EUROPE   |              222.26 |                  61.38 |                    68.2  |                 70.63 |              63.57 |                78.39 |                   21.61 |           93.4  |             52.68 |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL      | Global Ship Lease, Inc.                                | OTHER    |                1.34 |                  79.95 |                    71.79 |                 70.61 |              73.7  |                69.07 |                   30.93 |           74.89 |             37    |       0.083 |         nan |       nan |        3.74 |         4.89 |          4.24 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE  | PAH3.DE                                                | EUROPE   |                8.5  |                  63.12 |                    68.71 |                 70.47 |              68.07 |                79.05 |                   20.95 |          nan    |             83.91 |     nan     |         nan |       nan |      nan    |         1.88 |         89.52 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD      | Abrdn Total Dynamic Dividend Fund                      | OTHER    |                0.96 |                  58.42 |                    67.35 |                 69.94 |              64.66 |                81.01 |                   18.99 |           77.91 |             80.16 |     nan     |         nan |       nan |      nan    |       nan    |          4.06 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | DAC      | Danaos Corporation                                     | OTHER    |                2.32 |                  64.59 |                    67.15 |                 69.17 |              66.11 |                78.91 |                   21.09 |           80.65 |             54.02 |       0.002 |         nan |       nan |        3.98 |         6.07 |          5    |        0.12 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN      | BEN                                                    | US       |               14.78 |                  58.33 |                    66.44 |                 69.15 |              62.35 |                77.58 |                   22.42 |           86.71 |             63.96 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | ETG      | Eaton Vance Tax-Advantaged Global Dividend Income Fund | US       |                1.56 |                  60.08 |                    66.63 |                 68.61 |              64.83 |                75.2  |                   24.8  |           72.93 |             80.41 |       0.028 |         nan |       nan |      nan    |       nan    |          3.73 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|           14 | INVA     | Innoviva, Inc.                                         | US       |                1.3  |                  60.22 |                    65.43 |                 68.13 |              62.26 |                83.65 |                   16.35 |           90.86 |             38.47 |       0.073 |         nan |       nan |        6.5  |         9.5  |          4.98 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | KDP      | KDP                                                    | US       |               36.91 |                  56.05 |                    65.06 |                 68.12 |              60.78 |                76.09 |                   23.91 |           85.57 |             67.32 |     nan     |         nan |       nan |      nan    |        12.49 |         31.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras                   | OTHER    |               99.94 |                  78.74 |                    69.53 |                 67.93 |              73.7  |                56.97 |                   43.03 |           55.31 |             67.5  |       0.155 |         nan |       nan |        1.74 |         6.93 |          4.13 |        4.17 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY      | BMY                                                    | US       |              114.56 |                  62.87 |                    66.56 |                 67.81 |              64.1  |                72.8  |                   27.2  |           80.01 |             57.32 |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           18 | MU       | MU                                                     | US       |              942.63 |                  55.16 |                    64.06 |                 67.75 |              58.03 |                69.85 |                   30.15 |           95.36 |             57.39 |     nan     |         nan |       nan |      nan    |         6.26 |         21.19 |        0.14 |                 nan |              nan |                   6 |                  0.32 |
|          nan | FRO      | FRO                                                    | US       |                8.31 |                  57.61 |                    64.65 |                 67.21 |              60.85 |                71.98 |                   28.02 |           83.45 |             64.15 |     nan     |         nan |       nan |      nan    |        11.02 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                                                    | US       |                2.73 |                  61.74 |                    65.29 |                 66.86 |              61.41 |                69.69 |                   30.31 |           88.03 |             44.15 |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                                                | EUROPE   |               17.78 |                  56.28 |                    63.99 |                 66.76 |              58.21 |                76.43 |                   23.57 |           96.3  |             39.27 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DRH      | DRH                                                    | US       |                2.25 |                  49.35 |                    62.24 |                 66.5  |              56.73 |                86.27 |                   13.73 |           85.5  |            nan    |     nan     |         nan |       nan |      nan    |        21.64 |         17.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name     | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX      | US       |               11.7  |                     0.07 |    -0.02 |      0.22 |                  69.42 |                        82.04 |         79.68 |         83.19 |          76.18 |        74.12 |           77.34 |             97.07 |         5.88 |
|               2 | GENI     | GENI     | US       |                1.82 |                     0.05 |     0    |      0.23 |                  69.29 |                        77.65 |         79.62 |         78.51 |          70.14 |        71.3  |           64.82 |             96.53 |         9.13 |
|               3 | RBRK     | RBRK     | US       |               17.19 |                     0.07 |    -0.07 |      0.34 |                  81.3  |                        77.08 |         74.99 |         81.2  |          65.05 |        47.69 |           54.02 |             89.88 |         8.12 |
|               4 | WDAY     | WDAY     | US       |               41.75 |                     0.04 |    -0.04 |      0.54 |                  77.06 |                        76.57 |         78.51 |         77.04 |          65.63 |        62.16 |           73.41 |             73.78 |         8.48 |
|               5 | SNOW     | SNOW     | US       |               95.39 |                     0.05 |    -0.05 |      0.21 |                  80.22 |                        76.24 |         71.82 |         83.07 |          67.57 |        47.07 |           42.81 |             94.02 |         8.84 |
|               6 | ZETA     | ZETA     | US       |                5.99 |                     0.06 |    -0.06 |      0.44 |                  85.32 |                        75.98 |         78.59 |         81.33 |          67.49 |        53.22 |           49.01 |             84.76 |         7.53 |
|               7 | NTAP     | NTAP     | US       |               32.36 |                     0.07 |    -0.06 |      0.17 |                  79.55 |                        75.95 |         67.82 |         77.13 |          74.5  |        67.56 |           87.51 |             52.98 |         6.24 |
|               8 | P        | P        | US       |               31.32 |                     0.07 |    -0.06 |      0.46 |                  80.34 |                        75.48 |         77.65 |         77.45 |          66.93 |        55.28 |           67.09 |             74.57 |         7.87 |
|               9 | SYENS.BR | SYENS.BR | EUROPE   |                8.08 |                     0.04 |    -0.01 |      0.13 |                  64.27 |                        75.42 |         75.71 |         70.55 |          63.41 |        59.61 |           71.91 |             90.24 |         5.09 |
|              10 | HPE      | HPE      | US       |               60    |                     0.12 |    -0.12 |      0.11 |                  62.33 |                        74.28 |         61.15 |         79.95 |          79.84 |        72.31 |           70.1  |             72.9  |         6.78 |
|              11 | BCRX     | BCRX     | US       |                2.11 |                     0.09 |    -0.02 |      0.03 |                  54.98 |                        74.17 |         58.56 |         69.84 |          77.86 |        79.69 |           84.61 |             93.9  |         5.8  |
|              12 | SMWB     | SMWB     | US       |                0.62 |                     0.09 |    -0.09 |      0.35 |                  74    |                        74.14 |         73.9  |         82.57 |          63.5  |        44.62 |           37.4  |             95.19 |         9.42 |
|              13 | PLTR     | PLTR     | US       |              358.1  |                     0.03 |    -0.03 |      0.41 |                  62.48 |                        73.56 |         77.58 |         66.39 |          58.35 |        54.72 |           89.09 |             50.49 |         8.35 |
|              14 | DK       | DK       | US       |                3.36 |                     0.06 |    -0.06 |     -0.01 |                  84.46 |                        72.96 |         56.68 |         76.24 |          73.29 |        61.03 |           55.88 |             73.33 |         6.52 |
|              15 | KRX.IR   | KRX.IR   | EUROPE   |               18.12 |                     0.03 |    -0.02 |      0.34 |                  61.51 |                        72.86 |         78.03 |         67.88 |          62.25 |        61.13 |           95.81 |             36.4  |         5.13 |
|              16 | DOCS     | DOCS     | US       |                3.96 |                     0.05 |    -0.02 |      0.27 |                  76.9  |                        72.29 |         74.62 |         60.63 |          53    |        57.67 |           74.06 |             57.58 |         9.22 |
|              17 | JHX      | JHX      | US       |               14.93 |                     0.03 |    -0.03 |      0.16 |                  65.82 |                        72.15 |         75.34 |         77.37 |          68.5  |        60.78 |           58.16 |             79.76 |         6.42 |
|              18 | MP       | MP       | US       |                8.4  |                     0.06 |    -0.01 |      0.23 |                  69.14 |                        72.04 |         73.96 |         51    |          49.13 |        46.98 |           59.77 |             84.88 |         8.68 |
|              19 | COUR     | COUR     | US       |                1.32 |                     0.05 |     0.01 |      0.09 |                  67.33 |                        71.84 |         67.54 |         62.25 |          63.26 |        72.19 |           67.24 |             96.83 |         8.17 |
|              20 | NTNX     | NTNX     | US       |               15.36 |                     0.02 |    -0.02 |      0.26 |                  58.5  |                        71.78 |         71.66 |         75.64 |          64.8  |        55.8  |           77.36 |             64.76 |         7.03 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.8  |             62.87 |         70.87 |         69.28 |          56.47 |        51.46 |           53.63 |             48.77 |             53.25 |         8.23 |             86.86 | short              |                0.49 |                  2.47 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4499.25 |             59.14 |         56.95 |         53.5  |          61.34 |        62.76 |           91.97 |             62.58 |             24.75 |         5.53 |             89.48 | long               |                1.69 |                 -0.94 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.13 |             57.28 |         72.95 |         56.89 |          57.66 |        55.71 |           51.99 |             82.62 |             34.27 |         5.89 |             77.94 | short              |                1.15 |                  0.46 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.68 |             52.43 |         33.59 |         50.8  |          54.06 |        60.09 |           54.35 |             48.97 |             73.5  |         8.45 |             87.57 | long               |               -0.99 |                 -1.44 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1483.58 |             49.98 |         32.53 |         42.44 |          57.53 |        59.43 |           83.72 |             63.03 |             25.37 |         6.11 |             89.81 | long               |               -0.31 |                 -0.87 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             48.91 |         40.7  |         43.28 |          54.53 |        65.11 |           86.53 |             43.7  |             54.82 |         3.83 |             75.81 | long               |               -0.91 |                 -0.43 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.72 |             44.53 |         39.4  |         39.96 |          49.11 |        61.29 |           60.56 |             56.06 |             87.11 |         4.24 |             82.14 | long               |               -2.45 |                 -0.44 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.27 |             40.92 |         32.68 |         36.75 |          45.08 |        50.88 |           47.6  |             60.22 |             68.86 |         5.87 |             80.44 | long               |              nan    |                 -1.46 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             38.85 |         38.88 |         31.56 |          38.83 |        45.3  |           47.04 |             66.54 |             49.29 |         6.97 |             77.1  | long               |               -5.58 |                  0.36 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.89 |             38.33 |         29.75 |         34.37 |          42.3  |        55.22 |           45.11 |             46.85 |             90    |         6.2  |             78.58 | long               |                1.08 |                 -0.14 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.86 |             34.22 |         30.68 |         23.62 |          37.76 |        50.46 |           67.83 |             19.13 |             49.33 |         9.04 |             78.45 | long               |               -5.22 |                 -0.21 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     68 | ASA      | ASA           | US       |                1    |             70.3  |         74.36 |         51.61 |          66.24 |        83.15 |           82.26 |            nan    |             93.76 |         6.77 |             58.41 | long               |               12.64 |                  2.75 |                  nan |
|    212 | AMN      | AMN           | US       |                1.15 |             62.5  |         61.42 |         67.2  |          63.59 |        52.54 |           57.85 |             42.93 |             24.15 |         6.4  |             67.05 | swing              |              nan    |                  2.56 |                  nan |
|    389 | UNIT     | UNIT          | US       |                2.09 |             55.37 |         48.46 |         43.72 |          65.45 |        62.29 |           83.25 |            nan    |             22.17 |         5.36 |             60.32 | medium             |                7.73 |                  2.38 |                  nan |
|    567 | 0P6O.IL  | Volkswagen AG | OTHER    |               41.32 |             47.14 |         49.49 |         31.47 |          44.79 |        60.34 |           74.57 |            nan    |             60.4  |         4.97 |             70.77 | long               |                1.37 |                  2.37 |                  nan |
|      3 | PGEN     | PGEN          | US       |                2.27 |             77.63 |         91.9  |         85.22 |          70.04 |        52.44 |           67.1  |            nan    |              1.62 |         7.64 |             62.84 | short              |                5.85 |                  2.36 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    471 | TKA.DE    | TKA.DE    | EUROPE   |                7.88 |             51.63 |         51.61 |         47.63 |          51.65 |        58.45 |          nan    |             18.29 |             65.18 |         6.5  |             64.66 | long               |              -24.74 |                 -5.24 |                  nan |
|    700 | NWL.MI    | NWL.MI    | EUROPE   |                0.66 |             30.57 |         32.77 |         25.58 |          28.37 |        41    |           39.31 |              2.56 |             66.22 |         4.19 |             60.23 | long               |              -16.54 |                 -4.18 |                  nan |
|    261 | AKER.OL   | AKER.OL   | EUROPE   |                9.85 |             60.79 |         78.51 |         64.91 |          56.66 |        37.8  |           34.84 |            nan    |             10.8  |         3.82 |             63.61 | short              |              -17.58 |                 -3.9  |                  nan |
|    634 | INDU-A.ST | INDU-A.ST | EUROPE   |               20.29 |             42.5  |         36.71 |         43.18 |          48.03 |        41.83 |           40.53 |            nan    |             25.1  |         1.77 |             63.61 | medium             |              -15.5  |                 -3.32 |                  nan |
|    557 | FOSL      | FOSL      | US       |                0.28 |             47.68 |         69.72 |         54.42 |          40.94 |        34.59 |           10.4  |              5.05 |             48.73 |         8.03 |             58.75 | short              |              -14.39 |                 -3.04 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=0.99
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.92
- `ret_126d_rank` vs `dist_sma_200_rank`: r=0.89

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
- Excluded by hard/data filters: **275**
- Event watch (otherwise eligible): **11**
- Final eligible: **714**
- Eligible change vs previous stored run: **+20**

Top exclusion categories:
- liquidity: 224
- price: 166
- market_cap: 127
- data_confidence: 18
- price_history: 16
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| BION.SW | 4 | 1 |  | 1 | 2 | main,value,quality_value |
| BAX | 1 |  | 1 |  | 2 | main,pullback |
| MU | 2 | 18 |  | 10 | 1 | main,quality_value |
| TNK | 28 | 5 |  | 4 | 1 | value,quality_value |
| DAC | 61 | 9 |  | 6 | 1 | value,quality_value |
| GSL | 206 | 3 |  | 5 | 1 | value,quality_value |
| ETG | 209 | 10 | 45 | 7 | 1 | value,quality_value |
| PBR-A | 234 | 4 |  | 9 | 1 | value,quality_value |
| PKX | 298 | 6 | 79 | 3 | 1 | value,quality_value |
| STNE | 666 | 2 |  | 2 | 1 | value,quality_value |
| PGEN | 3 |  |  |  | 1 | main |
| CCC | 5 |  |  |  | 1 | main |
| PSX | 6 |  |  |  | 1 | main |
| AMC | 7 |  |  |  | 1 | main |
| GH | 8 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (PGEN, CCC, PSX, AMC, GH, NAT, KOS)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **2** (SYENS.BR, HPE)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | FITB | value+pullback | 67.16 | 60.19 | 84.24 | 67.61 | 51.20 | 63.91 | 57.01 |
| 2 | PKX | value+pullback | 67.02 | 65.64 | 51.94 | 85.86 | 67.98 | 73.33 | 59.16 |
| 3 | INVA | value+pullback | 66.34 | 60.22 | 56.26 | 90.86 | 38.47 | 83.65 | 47.77 |
| 4 | ETG | value+pullback | 66.22 | 60.08 | 56.72 | 72.93 | 80.41 | 75.20 | 62.58 |
| 5 | HLF | value+pullback | 65.54 | 69.27 | 68.70 | 85.41 | 36.57 | 55.60 | 46.80 |
| 6 | CNC | value+pullback | 64.86 | 71.16 | 75.73 | 51.59 | 63.61 | 52.43 | 61.08 |
| 7 | AVK | value+pullback | 63.96 | 59.97 | 61.69 | 68.00 | 80.16 | 61.64 | 59.59 |
| 8 | MSFT | value+pullback | 62.87 | 58.21 | 74.85 | 64.55 | 63.91 | 53.08 | 58.96 |
| 9 | MFA | value+pullback | 62.19 | 57.86 | 64.79 | 82.12 | 34.33 | 64.43 | 44.32 |
| 10 | STNG | value+pullback | 61.90 | 60.41 | 50.52 | 84.06 | 31.33 | 77.02 | 56.88 |
| 11 | DXC | value+pullback | 61.29 | 84.67 | 61.62 | 48.75 | 35.47 | 48.13 | 53.43 |
| 12 | ORCL | value+pullback | 61.11 | 69.90 | 75.23 | 52.44 | 57.54 | 38.55 | 41.49 |
| 13 | ALL-PH | value+pullback | 60.07 | 67.16 | 57.83 | 69.59 | 39.34 | 55.48 | 45.35 |
| 14 | KYN | value+pullback | 59.23 | 59.90 | 46.38 | 58.78 | 80.41 | 64.03 | 61.48 |
| 15 | BION.SW | value | 58.83 | 74.19 | 37.64 | 87.62 | 58.75 | 87.78 | 77.26 |
| 16 | BCS | value+pullback | 58.00 | 67.74 | 83.08 | 39.54 | 29.08 | 40.35 | 48.48 |
| 17 | HRTG | value+pullback | 57.75 | 55.13 | 61.41 | 59.87 | 61.29 | 53.74 | 67.95 |
| 18 | CNXC | value+pullback | 57.70 | 80.12 | 64.61 | 46.11 | 31.23 | 37.35 | 45.48 |
| 19 | CHTR | value+pullback | 57.34 | 58.96 | 82.24 | 55.81 | 40.27 | 33.49 | 43.17 |
| 20 | GL9.IR | pullback | 57.23 | 40.94 | 77.21 | 97.84 | 63.49 | 84.49 | 65.40 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 9/10 | 9/10 | 8/10 | 6/10 | 0/10 | 65.3 | 3 / 7 |
| Top 25 | 23/25 | 23/25 | 23/25 | 19/25 | 0/25 | 65.7 | 5 / 20 |
| Top 50 | 46/50 | 48/50 | 48/50 | 42/50 | 0/50 | 66.0 | 14 / 36 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=2, large_20_100b=1, mega_100b_plus=1
