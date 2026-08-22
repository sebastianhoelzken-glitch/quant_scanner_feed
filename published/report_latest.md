# Daily Multi-Horizon + Broad Value Stock Scanner — 2026-08-22

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

- **EUROPE:** 88.2/100
- **OTHER:** 73.5/100
- **US:** 84.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | CRGY     | CRGY                       | US       |                3.98 |             78.26 |         83.05 |         75.85 |          76.55 |        79.97 |           71.36 |             84.04 |             95.61 |         6.19 |             67.05 | short              |              nan    |                nan    |                  nan |
|      2 | MU       | MU                         | US       |              934.97 |             78.18 |         60.92 |         72.25 |          84.11 |        85.22 |           95.42 |             60.82 |             76.89 |         8.19 |             67.5  | long               |                0.27 |                nan    |                  nan |
|      3 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |             78.15 |         65.94 |         76.8  |          81.21 |        79.49 |           83.48 |             64.82 |             72.8  |         6.78 |             85.72 | medium             |                8.51 |                  0.42 |                  nan |
|      4 | AMC      | AMC                        | US       |                1.95 |             77.99 |         68.15 |         82.13 |          78.04 |        77.93 |           84.59 |             79.93 |            nan    |         9.61 |             61.25 | swing              |                1.2  |                nan    |                  nan |
|      5 | ERO      | ERO                        | US       |                3.52 |             77.58 |         87.65 |         76.63 |          73.83 |        78.52 |           83.39 |             45.71 |             79.28 |         7.53 |             67.5  | short              |                2.42 |                nan    |                  nan |
|      6 | DK       | DK                         | US       |                3.75 |             77.56 |         82.74 |         82.4  |          72.72 |        58.79 |           54.55 |             72.07 |             31.83 |         6.76 |             67.5  | short              |               10.4  |                  0.88 |                  nan |
|      7 | PBF      | PBF                        | US       |                7.46 |             77.39 |         79.63 |         80.7  |          75.15 |        71.8  |           51.33 |             55.62 |             92.8  |         7.13 |             67.05 | swing              |                3.8  |                 -0.17 |                  nan |
|      8 | PSX      | PSX                        | US       |               82.98 |             77.3  |         78.44 |         79.17 |          76.17 |        73.82 |           78.99 |             54.78 |             63.99 |         3.51 |             67.5  | swing              |                0.45 |                nan    |                  nan |
|      9 | CCC      | CCC                        | US       |                3.76 |             77.23 |         82.81 |         81.1  |          73.36 |        72.29 |           87.49 |             80.89 |             56.94 |         7.97 |             66.02 | short              |                0.28 |                  0.98 |                  nan |
|     10 | TWST     | TWST                       | US       |                7.82 |             76.98 |         88.82 |         84.16 |          69.79 |        49.66 |           45.96 |             77.15 |              6.9  |         7.04 |             64.66 | short              |                1.58 |                  0.33 |                  nan |
|     11 | FLYW     | FLYW                       | US       |                2.04 |             76.92 |         81.66 |         79.35 |          74.49 |        69.09 |           72.28 |             76.3  |             54.08 |         5.95 |             66.7  | short              |              nan    |                  1.44 |                  nan |
|     12 | BAX      | BAX                        | US       |               11.66 |             76.49 |         76.98 |         81.98 |          76    |        74.09 |           76.5  |             97.7  |             61.79 |         6.01 |             66.02 | swing              |               -1.44 |                  0.09 |                  nan |
|     13 | ZD       | ZD                         | US       |                1.65 |             76.48 |         74.28 |         83.67 |          78.68 |        73.01 |           52.82 |             89    |             86.52 |         5.5  |             67.05 | swing              |              nan    |                  0.24 |                  nan |
|     14 | HPE      | HPE                        | US       |               60.61 |             76.28 |         61.8  |         80.36 |          80.14 |        72.43 |           69.82 |             74.24 |             59.14 |         6.86 |             65.68 | swing              |                0.2  |                 -0.75 |                  nan |
|     15 | SBLK     | SBLK                       | US       |                2.92 |             76.12 |         79.22 |         73.59 |          74.35 |        77.89 |           74.23 |             61.06 |             88.01 |         4.1  |             67.16 | short              |                1.07 |                  0.22 |                  nan |
|     16 | PGEN     | PGEN                       | US       |                2.2  |             75.85 |         89.35 |         82.73 |          68.96 |        52.13 |           67.31 |            nan    |              1.67 |         7.73 |             62.84 | short              |               -1.78 |                  1.13 |                  nan |
|     17 | BFLY     | BFLY                       | US       |                2.18 |             75.82 |         82.2  |         82.16 |          69.49 |        50.5  |           46.07 |             74.97 |             10.95 |         8.46 |             63.64 | short              |                1.42 |                  0.96 |                  nan |
|     18 | JCAP     | JCAP                       | US       |                1.1  |             75.82 |         73.49 |         75.98 |          75.66 |        83.02 |           86.6  |             85.85 |             84.54 |         5.57 |             65.45 | long               |              nan    |                 -1.23 |                  nan |
|     19 | TALO     | TALO                       | US       |                2.5  |             75.8  |         83.74 |         74.91 |          76.7  |        74.25 |           68.94 |             92.74 |             67.58 |         5.61 |             67.5  | short              |              nan    |                nan    |                  nan |
|     20 | U        | U                          | US       |               17.69 |             75.67 |         84.68 |         86.47 |          66.66 |        49.38 |           43.73 |             97.1  |             18.41 |         8.33 |             67.5  | swing              |               -0.59 |                 -0.12 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol    | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                        | EUROPE   |                3.3  |                  77.64 |                    77.12 |                 78.75 |              77.57 |                87.66 |                   12.34 |           87.32 |             58.88 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            2 | STNE      | StoneCo Ltd.                         | OTHER    |                1.85 |                  77.14 |                    73.4  |                 73.1  |              72.13 |                70.31 |                   29.69 |           87.77 |             39.33 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.51 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | GSL       | Global Ship Lease, Inc.              | OTHER    |                1.35 |                  81.57 |                    72.48 |                 70.92 |              75.07 |                69.98 |                   30.02 |           72.39 |             37.42 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            4 | VOLV-B.ST | AB Volvo (publ)                      | EUROPE   |               63.01 |                  84.11 |                    72.25 |                 68.22 |              76.51 |                56.18 |                   43.82 |           52.72 |             58.41 |       0.034 |         nan |       nan |       16.21 |        13.77 |         19.47 |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|            5 | PARR      | Par Pacific Holdings, Inc.           | US       |                3.39 |                  72.81 |                    72.06 |                 73.59 |              71.19 |                68.22 |                   31.78 |           83.48 |             64.82 |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.25 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                             | EUROPE   |              220.22 |                  64.52 |                    70.61 |                 72.83 |              66.26 |                79.45 |                   20.55 |           94.53 |             55.02 |     nan     |         nan |       nan |      nan    |        10.07 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | EMBC      | Embecta Corp.                        | US       |                0.25 |                  75.37 |                    69.07 |                 68.26 |              70.79 |                59.55 |                   40.45 |           66.82 |             58.05 |       0.466 |         nan |       nan |        5.62 |         2.97 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | PAH3.DE   | PAH3.DE                              | EUROPE   |                8.56 |                  62.95 |                    68.63 |                 70.45 |              67.97 |                78.87 |                   21.13 |          nan    |             84.52 |     nan     |         nan |       nan |      nan    |         1.89 |         90.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | NWL.MI    | NewPrinces S.p.A.                    | EUROPE   |                0.65 |                  68.71 |                    68.52 |                 70.41 |              68.43 |                74.45 |                   25.55 |           79.95 |             55.56 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            8 | PBR-A     | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              100.96 |                  79.16 |                    67.84 |                 65.65 |              72.72 |                49.59 |                   50.41 |           49.57 |             67.96 |       0.154 |         nan |       nan |        1.75 |         7    |          4.3  |        4.17 |                 nan |              nan |                  12 |                  0.63 |
|          nan | VOW.DE    | VOW.DE                               | EUROPE   |               38.25 |                  67.77 |                    66.89 |                 66.67 |              66.97 |                64.72 |                   35.28 |          nan    |             65.3  |     nan     |         nan |       nan |      nan    |         2.81 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            9 | UNIT      | Uniti Group Inc.                     | US       |                2.07 |                  80.26 |                    66.72 |                 63.68 |              68.88 |                44.78 |                   55.22 |           65.19 |             30.33 |      -0.107 |         nan |       nan |        9.1  |       -14.04 |          2.61 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           10 | INVA      | Innoviva, Inc.                       | US       |                1.3  |                  63.69 |                    66.56 |                 68.67 |              64.25 |                80.86 |                   19.14 |           88.46 |             38.43 |       0.072 |         nan |       nan |        6.52 |         9.53 |          4.88 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | VOW3.DE   | VOW3.DE                              | EUROPE   |               37.61 |                  68.46 |                    66.5  |                 65.99 |              66.7  |                61.81 |                   38.19 |          nan    |             62.76 |     nan     |         nan |       nan |      nan    |         3.19 |          7.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BMY       | BMY                                  | US       |              117.21 |                  62.49 |                    66.39 |                 67.74 |              63.77 |                72.69 |                   27.31 |           80.7  |             56.95 |     nan     |         nan |       nan |      nan    |        10.22 |         14.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | WB        | Weibo Corporation                    | OTHER    |                1.48 |                  77.93 |                    66.39 |                 62.62 |              68.72 |                57.79 |                   42.21 |           62.28 |             22.11 |     nan     |         nan |       nan |        1.98 |         5.34 |          5.96 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|           12 | IHS       | IHS Holding Limited                  | OTHER    |                2.43 |                  71.77 |                    66.34 |                 65.96 |              70.61 |                59.33 |                   40.67 |           49.49 |             82.59 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.12 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | BEN       | BEN                                  | US       |               14.93 |                  57.23 |                    66.14 |                 69.12 |              61.76 |                78.06 |                   21.94 |           87.58 |             65.05 |     nan     |         nan |       nan |      nan    |        10.84 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT       | DHT                                  | US       |                2.74 |                  61.63 |                    65.54 |                 67.23 |              61.54 |                70.19 |                   29.81 |           88.66 |             45.34 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK      | SBLK                                 | US       |                2.92 |                  62.86 |                    65.35 |                 66.27 |              63.69 |                68.45 |                   31.55 |           74.23 |             61.06 |     nan     |         nan |       nan |      nan    |         8.57 |         11.78 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol    | name                              | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:----------|:----------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | BION.SW   | BB Biotech AG                     | EUROPE   |                3.3  |                  77.64 |                    77.12 |                 78.75 |              77.57 |                87.66 |                   12.34 |           87.32 |             58.88 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.28 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            5 | PARR      | Par Pacific Holdings, Inc.        | US       |                3.39 |                  72.81 |                    72.06 |                 73.59 |              71.19 |                68.22 |                   31.78 |           83.48 |             64.82 |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.25 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | STNE      | StoneCo Ltd.                      | OTHER    |                1.85 |                  77.14 |                    73.4  |                 73.1  |              72.13 |                70.31 |                   29.69 |           87.77 |             39.33 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.51 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS  | SHELL.AS                          | EUROPE   |              220.22 |                  64.52 |                    70.61 |                 72.83 |              66.26 |                79.45 |                   20.55 |           94.53 |             55.02 |     nan     |         nan |       nan |      nan    |        10.07 |         10.31 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            3 | GSL       | Global Ship Lease, Inc.           | OTHER    |                1.35 |                  81.57 |                    72.48 |                 70.92 |              75.07 |                69.98 |                   30.02 |           72.39 |             37.42 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.23 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|          nan | PAH3.DE   | PAH3.DE                           | EUROPE   |                8.56 |                  62.95 |                    68.63 |                 70.45 |              67.97 |                78.87 |                   21.13 |          nan    |             84.52 |     nan     |         nan |       nan |      nan    |         1.89 |         90.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | NWL.MI    | NewPrinces S.p.A.                 | EUROPE   |                0.65 |                  68.71 |                    68.52 |                 70.41 |              68.43 |                74.45 |                   25.55 |           79.95 |             55.56 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          2.01 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN       | BEN                               | US       |               14.93 |                  57.23 |                    66.14 |                 69.12 |              61.76 |                78.06 |                   21.94 |           87.58 |             65.05 |     nan     |         nan |       nan |      nan    |        10.84 |         23.03 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | INVA      | Innoviva, Inc.                    | US       |                1.3  |                  63.69 |                    66.56 |                 68.67 |              64.25 |                80.86 |                   19.14 |           88.46 |             38.43 |       0.072 |         nan |       nan |        6.52 |         9.53 |          4.88 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            6 | EMBC      | Embecta Corp.                     | US       |                0.25 |                  75.37 |                    69.07 |                 68.26 |              70.79 |                59.55 |                   40.45 |           66.82 |             58.05 |       0.466 |         nan |       nan |        5.62 |         2.97 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | VOLV-B.ST | AB Volvo (publ)                   | EUROPE   |               63.01 |                  84.11 |                    72.25 |                 68.22 |              76.51 |                56.18 |                   43.82 |           52.72 |             58.41 |       0.034 |         nan |       nan |       16.21 |        13.77 |         19.47 |        1.41 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BMY       | BMY                               | US       |              117.21 |                  62.49 |                    66.39 |                 67.74 |              63.77 |                72.69 |                   27.31 |           80.7  |             56.95 |     nan     |         nan |       nan |      nan    |        10.22 |         14.44 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP       | KDP                               | US       |               37.34 |                  54.39 |                    64.26 |                 67.61 |              59.68 |                76.2  |                   23.8  |           85.96 |             68.08 |     nan     |         nan |       nan |      nan    |        12.64 |         32.04 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           17 | TNK       | Teekay Tankers Ltd.               | OTHER    |                2.7  |                  53.89 |                    63.94 |                 67.59 |              60.86 |                80.44 |                   19.56 |           79.57 |             75.86 |       0.071 |         nan |       nan |        3.88 |         8.35 |          5.37 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT       | DHT                               | US       |                2.74 |                  61.63 |                    65.54 |                 67.23 |              61.54 |                70.19 |                   29.81 |           88.66 |             45.34 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO       | FRO                               | US       |                8.32 |                  56.89 |                    64.42 |                 67.16 |              60.42 |                72.23 |                   27.77 |           84.16 |             64.57 |     nan     |         nan |       nan |      nan    |        11.05 |         10.73 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR   | BIRG.IR                           | EUROPE   |               18.08 |                  56.02 |                    64.12 |                 67    |              58.35 |                76.81 |                   23.19 |           95.97 |             41.84 |     nan     |         nan |       nan |      nan    |        10.5  |         14.2  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | AOD       | Abrdn Total Dynamic Dividend Fund | OTHER    |                0.97 |                  51.83 |                    63.56 |                 66.99 |              60.06 |                80.97 |                   19.03 |           77.03 |             81.75 |     nan     |         nan |       nan |      nan    |       nan    |          4.09 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW.DE    | VOW.DE                            | EUROPE   |               38.25 |                  67.77 |                    66.89 |                 66.67 |              66.97 |                64.72 |                   35.28 |          nan    |             65.3  |     nan     |         nan |       nan |      nan    |         2.81 |          7.32 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY      | CRGY                              | US       |                3.98 |                  56.95 |                    64.18 |                 66.61 |              62.06 |                70.25 |                   29.75 |           71.36 |             84.04 |     nan     |         nan |       nan |      nan    |         6.55 |        175.75 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX                        | US       |               11.66 |                     0.07 |    -0.01 |      0.18 |                  65.25 |                        80.73 |         76.98 |         81.98 |          76    |        74.09 |           76.5  |             97.7  |         6.01 |
|               2 | JCAP     | JCAP                       | US       |                1.1  |                     0.07 |    -0.07 |      0.12 |                  81.56 |                        80.42 |         73.49 |         75.98 |          75.66 |        83.02 |           86.6  |             85.85 |         5.57 |
|               3 | GENI     | GENI                       | US       |                1.85 |                     0.04 |    -0.04 |      0.24 |                  71.56 |                        78.45 |         75.58 |         80.26 |          71.77 |        71.78 |           64.83 |             97.46 |         9.11 |
|               4 | RBRK     | RBRK                       | US       |               17.64 |                     0.05 |    -0.02 |      0.37 |                  72.34 |                        76.65 |         78.51 |         82.98 |          65.64 |        47.86 |           54.18 |             89.84 |         8.14 |
|               5 | AMRX     | AMRX                       | US       |                5.34 |                     0.06 |    -0.01 |     -0    |                  70.17 |                        75.32 |         56.45 |         72.62 |          76.57 |        74.59 |           92.71 |             66.26 |         4.64 |
|               6 | WDAY     | WDAY                       | US       |               42.3  |                     0.03 |     0.01 |      0.48 |                  54.14 |                        75.3  |         82.1  |         78.21 |          66.57 |        62.28 |           74.51 |             74.85 |         8.47 |
|               7 | AMC      | AMC                        | US       |                1.95 |                     0.11 |     0.02 |      0.12 |                  33.88 |                        75.06 |         68.15 |         82.13 |          78.04 |        77.93 |           84.59 |             79.93 |         9.61 |
|               8 | HPE      | HPE                        | US       |               60.61 |                     0.11 |    -0.09 |      0.12 |                  65.09 |                        75.04 |         61.8  |         80.36 |          80.14 |        72.43 |           69.82 |             74.24 |         6.86 |
|               9 | P        | P                          | US       |               30.9  |                     0.08 |    -0.08 |      0.46 |                  78.25 |                        74.94 |         76.44 |         76.54 |          66.93 |        55.45 |           67.52 |             76.18 |         7.97 |
|              10 | MU       | MU                         | US       |              934.97 |                     0.04 |    -0.01 |      0.05 |                  65.77 |                        74.2  |         60.92 |         72.25 |          84.11 |        85.22 |           95.42 |             60.82 |         8.19 |
|              11 | BCRX     | BCRX                       | US       |                2.09 |                     0.1  |    -0.02 |      0.02 |                  49.78 |                        73.72 |         54.41 |         70.42 |          78.16 |        80.43 |           84.5  |             94.32 |         5.88 |
|              12 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |                     0.08 |    -0.02 |      0.02 |                  59.2  |                        73.7  |         65.94 |         76.8  |          81.21 |        79.49 |           83.48 |             64.82 |         6.78 |
|              13 | SYENS.BR | SYENS.BR                   | EUROPE   |                8.15 |                     0.03 |    -0.03 |      0.12 |                  64.95 |                        73.38 |         71.99 |         69.84 |          62.8  |        58.47 |           70.58 |             90.21 |         5.27 |
|              14 | NWL      | NWL                        | US       |                2.22 |                     0.04 |    -0.02 |      0.2  |                  70.08 |                        72.75 |         72.52 |         82.21 |          69.91 |        64.97 |           33.57 |             96.13 |         8.23 |
|              15 | KRX.IR   | KRX.IR                     | EUROPE   |               18.1  |                     0.03 |    -0.01 |      0.32 |                  58.17 |                        72.74 |         77.73 |         65.31 |          61.45 |        61.5  |           97.63 |             37.48 |         5.26 |
|              16 | CAKE     | CAKE                       | US       |                4.83 |                     0.03 |    -0    |      0.34 |                  57.81 |                        72.15 |         80.93 |         75.96 |          69.64 |        63.29 |           87.74 |             36.4  |         5.82 |
|              17 | ZETA     | ZETA                       | US       |                6.25 |                     0.02 |     0    |      0.52 |                  48.08 |                        72.04 |         84.82 |         83.35 |          67.07 |        52.39 |           48.27 |             85.13 |         7.62 |
|              18 | DAR      | DAR                        | US       |                8.88 |                     0.04 |    -0.02 |      0.05 |                  65.99 |                        71.94 |         67.12 |         68.79 |          76.63 |        79.53 |           91.5  |             62.27 |         3.96 |
|              19 | QNST     | QNST                       | US       |                1.01 |                     0.06 |     0.01 |      0.36 |                  63.82 |                        71.73 |         80.57 |         74.22 |          68.13 |        70.02 |           83.72 |             34.22 |         7.88 |
|              20 | EXK      | EXK                        | US       |                2.69 |                     0.03 |    -0    |      0.36 |                  58.72 |                        71.65 |         78.36 |         61.58 |          61.85 |        68.73 |           59.7  |             78.11 |         8.24 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             64.01 |         71.93 |         70.38 |          57.63 |        53.11 |           52.32 |             49.73 |             59.48 |         8.18 |             86.86 | short              |                1.13 |                  3    |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4453.39 |             57.69 |         53.72 |         53.35 |          61.66 |        64.38 |           92.75 |             63.22 |             28.69 |         5.59 |             89.48 | long               |               -1.46 |                 -1.08 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.15 |             57.49 |         73.4  |         56.97 |          58.02 |        56.08 |           51.89 |             83.45 |             34.81 |         5.9  |             77.94 | short              |                0.22 |                  0.1  |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.71 |             52.74 |         35.74 |         50.74 |          54.74 |        61.3  |           59.57 |             49.31 |             72    |         8.42 |             87.57 | long               |                0.31 |                 -1.35 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1501.03 |             51.3  |         35.44 |         44.13 |          58.47 |        60.61 |           83.03 |             63.75 |             29.37 |         6.13 |             89.81 | long               |                1.32 |                 -0.55 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             50.68 |         47.38 |         44.08 |          53.97 |        64.73 |           84.51 |             44    |             54.56 |         3.89 |             75.81 | long               |                1.77 |                  0.23 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             46.52 |         42.84 |         41.97 |          50.21 |        62.71 |           62.68 |             57.34 |             85.93 |         4.3  |             82.14 | long               |                1.99 |                  0.21 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             40.63 |         42.11 |         33.29 |          39.15 |        45.55 |           47.04 |             67.22 |             49.29 |         7.06 |             77.1  | long               |                1.77 |                  1.29 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             38.35 |         30.79 |         34.56 |          42.13 |        53.91 |           48.14 |             47.17 |             78.96 |         6.22 |             78.58 | long               |                0.01 |                 -0.06 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.21 |             37.84 |         27.76 |         34.03 |          41.65 |        56.23 |           49.06 |             37.23 |             92.69 |         7.05 |             78.48 | long               |               -6.71 |                  0.21 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.85 |             36.25 |         34.91 |         23.53 |          37.59 |        49.36 |           67.83 |             19.22 |             45.33 |         8.97 |             78.45 | long               |                2.03 |                  1.04 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    614 | STLAP.PA | STLAP.PA | EUROPE   |               17.51 |             43.4  |         40.96 |         37.95 |          45.83 |        54.07 |           31.68 |             87.06 |             88.27 |         7.1  |             67.5  | long               |                1    |                  3.99 |                  nan |
|    113 | HIMS     | HIMS     | US       |                6.75 |             67.23 |         75.44 |         74.62 |          59.84 |        41.61 |           37.08 |             96.49 |             11.49 |         9.47 |             67.5  | short              |                7.9  |                  3.39 |                  nan |
|    635 | STLAM.MI | STLAM.MI | EUROPE   |               17.5  |             41.64 |         40.63 |         36.77 |          42.66 |        49.28 |           19.33 |             87.18 |             89.05 |         7.11 |             66.48 | long               |                1.51 |                  3.32 |                  nan |
|     26 | MRVI     | MRVI     | US       |                2.74 |             74.56 |         82.24 |         82.12 |          66.99 |        48.47 |           30.01 |             73.28 |             28.81 |         6.95 |             63.64 | short              |                0.54 |                  3.2  |                  nan |
|    447 | PAH3.DE  | PAH3.DE  | EUROPE   |                8.56 |             52.43 |         50.77 |         44.7  |          54.08 |        73.35 |          nan    |             84.52 |             94.27 |         3.82 |             64.66 | long               |                0.66 |                  3.06 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol    | name      | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:----------|:----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    396 | TKA.DE    | TKA.DE    | EUROPE   |                8.32 |             54.82 |         59.74 |         53.18 |          53.46 |        56.18 |          nan    |             18.5  |             60.14 |         6.71 |             64.66 | short              |                3.19 |                 -4.94 |                  nan |
|    666 | GLE.PA    | GLE.PA    | EUROPE   |               55.8  |             37.87 |         31.05 |         36.97 |          38.77 |        39.13 |            7.39 |             25.03 |             72.55 |         3.83 |             67.5  | long               |               -1.54 |                 -3.82 |                  nan |
|    246 | AKER.OL   | AKER.OL   | EUROPE   |               10.12 |             61.22 |         78.14 |         65.97 |          56.47 |        37.69 |           35.85 |            nan    |             10.1  |         3.98 |             65.68 | short              |                0.43 |                 -3.45 |                  nan |
|    615 | INDU-A.ST | INDU-A.ST | EUROPE   |               20.75 |             43.33 |         42.97 |         43.68 |          47.65 |        40.81 |           39.58 |            nan    |             24.87 |         1.87 |             65.68 | medium             |                0.82 |                 -3.28 |                  nan |
|    690 | AF.PA     | AF.PA     | EUROPE   |                3.02 |             34.54 |         26.08 |         30.96 |          38.12 |        52.92 |           44.43 |             12.98 |             93.42 |         6.15 |             64.52 | long               |               -3.57 |                 -2.97 |                  nan |

## Duplicate-security checks

- None detected.

## Factor-correlation warnings

- `ret_63d_rank` vs `relative_63d_rank`: r=1.00
- `ret_126d_rank` vs `risk_adj_mom_126d_rank`: r=0.91
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
- Excluded by hard/data filters: **278**
- Event watch (otherwise eligible): **11**
- Final eligible: **711**
- Eligible change vs previous stored run: **-3**

Top exclusion categories:
- liquidity: 230
- price: 164
- market_cap: 149
- price_history: 16
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 3 | 5 | 12 | 2 | 2 | main,value,quality_value |
| MU | 2 |  | 10 |  | 2 | main,pullback |
| AMC | 4 |  | 7 |  | 2 | main,pullback |
| BION.SW | 27 | 1 |  | 1 | 1 | value,quality_value |
| GSL | 159 | 3 |  | 4 | 1 | value,quality_value |
| EMBC | 207 | 6 |  | 7 | 1 | value,quality_value |
| VOLV-B.ST | 449 | 4 | 247 | 8 | 1 | value,quality_value |
| INVA | 576 | 10 | 230 | 6 | 1 | value,quality_value |
| NWL.MI | 608 | 7 | 187 | 5 | 1 | value,quality_value |
| STNE | 648 | 2 |  | 3 | 1 | value,quality_value |
| CRGY | 1 |  |  |  | 1 | main |
| ERO | 5 |  |  |  | 1 | main |
| DK | 6 |  |  |  | 1 | main |
| PBF | 7 |  |  |  | 1 | main |
| PSX | 8 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (CRGY, ERO, DK, PSX, CCC, TWST)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 74.00 | 68.71 | 83.81 | 79.95 | 55.56 | 74.45 | 43.67 |
| 2 | PARR | value+pullback | 69.29 | 72.81 | 59.20 | 83.48 | 64.82 | 68.22 | 78.15 |
| 3 | INVA | value+pullback | 67.25 | 63.69 | 59.44 | 88.46 | 38.43 | 80.86 | 45.70 |
| 4 | ETG | value+pullback | 64.20 | 56.61 | 53.19 | 68.15 | 82.01 | 77.50 | 62.05 |
| 5 | VOLV-B.ST | value+pullback | 63.93 | 84.11 | 54.83 | 52.72 | 58.41 | 56.18 | 52.24 |
| 6 | MFA | value+pullback | 62.23 | 57.65 | 66.21 | 80.59 | 35.03 | 63.95 | 43.18 |
| 7 | AVK | value+pullback | 61.81 | 55.76 | 57.85 | 62.17 | 81.75 | 65.58 | 59.08 |
| 8 | MSFT | value+pullback | 61.65 | 58.21 | 70.21 | 63.55 | 65.09 | 52.97 | 59.83 |
| 9 | TV | value+pullback | 60.98 | 69.83 | 74.47 | 44.82 | 31.92 | 57.51 | 38.94 |
| 10 | UNIT | value+pullback | 60.86 | 80.26 | 60.06 | 65.19 | 30.33 | 44.78 | 44.06 |
| 11 | ALL-PH | value+pullback | 60.86 | 62.26 | 63.20 | 69.04 | 41.40 | 59.44 | 44.04 |
| 12 | KYN | value+pullback | 60.86 | 60.33 | 51.74 | 55.15 | 82.01 | 66.76 | 59.95 |
| 13 | ORCL | value+pullback | 60.41 | 69.90 | 74.09 | 50.26 | 57.77 | 38.03 | 42.42 |
| 14 | BION.SW | value | 59.81 | 77.64 | 30.95 | 87.32 | 58.88 | 87.66 | 74.43 |
| 15 | XNET | value+pullback | 59.63 | 60.43 | 40.47 | 58.55 | 81.75 | 72.15 | 45.55 |
| 16 | PKX | value+pullback | 59.60 | 59.86 | 61.19 | 52.49 | 68.31 | 58.19 | 50.26 |
| 17 | WKC | value+pullback | 59.17 | 61.83 | 40.04 | 64.35 | 74.65 | 67.45 | 69.96 |
| 18 | ONIT | value+pullback | 58.34 | 71.13 | 59.74 | 62.17 | 44.08 | 41.64 | 43.62 |
| 19 | JCAP | pullback | 57.90 | 57.24 | 81.56 | 86.60 | 85.85 | 79.69 | 75.82 |
| 20 | GL9.IR | pullback | 56.89 | 39.96 | 75.43 | 97.63 | 64.69 | 84.58 | 65.26 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 67.3 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 67.0 | 8 / 17 |
| Top 50 | 50/50 | 49/50 | 49/50 | 48/50 | 0/50 | 67.0 | 17 / 33 |

Top-10 market-cap mix: small_1_5b=6, mid_5_20b=2, large_20_100b=1, mega_100b_plus=1
