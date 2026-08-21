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

- **EUROPE:** 86.7/100
- **OTHER:** 74.6/100
- **US:** 83.8/100

## Main multi-horizon ranking

|   rank | symbol   | name          | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | MPC      | MPC           | US       |               86.18 |             78.94 |         78.63 |         80.01 |          79.25 |        76.2  |           85.9  |             63.2  |             61.09 |         4.1  |             67.5  | swing              |              nan    |                 -0.26 |                  nan |
|      2 | AKER.OL  | Aker ASA      | EUROPE   |                9.86 |             78.02 |         83.08 |         76.18 |          79.85 |        73.76 |           86.31 |             82.19 |             43.22 |         3.53 |             74.34 | short              |               -0.35 |                 -0.46 |                  nan |
|      3 | CRGY     | CRGY          | US       |                4.65 |             77.02 |         81.61 |         71.47 |          74.93 |        79.12 |           72.4  |             84.26 |             95.73 |         6.22 |             67.05 | short              |                1.57 |                nan    |                  nan |
|      4 | BAX      | BAX           | US       |               11.7  |             76.52 |         78.14 |         81.35 |          74.9  |        73.39 |           78.42 |             95.88 |             61.57 |         5.99 |             66.02 | swing              |               12.63 |                 -0.45 |                  nan |
|      5 | PSX      | PSX           | US       |               82.43 |             75.98 |         77.52 |         76.89 |          75.07 |        73.28 |           80.22 |             55.21 |             64.48 |         3.46 |             67.5  | short              |                0.97 |                nan    |                  nan |
|      6 | PGEN     | PGEN          | US       |                2.28 |             75.6  |         90.21 |         82.82 |          68.37 |        51.28 |           67.22 |            nan    |              1.79 |         7.71 |             62.84 | short              |                3.82 |                  1.95 |                  nan |
|      7 | CCC      | CCC           | US       |                3.76 |             75.51 |         81.63 |         79.2  |          71.82 |        70.93 |           86.52 |             80.75 |             57.25 |         7.95 |             66.02 | short              |                1.43 |                  0.14 |                  nan |
|      8 | HPE      | HPE           | US       |               60    |             75.49 |         59.95 |         78.82 |          79.45 |        72.15 |           71.38 |             74.94 |             59.53 |         6.85 |             65.68 | medium             |                1.18 |                 -1.14 |                  nan |
|      9 | GH       | GH            | US       |               19.3  |             75.3  |         74.55 |         78.59 |          76.06 |        70.66 |           62.14 |             69.85 |            nan    |         6.51 |             62.73 | swing              |               13.04 |                  0.33 |                  nan |
|     10 | FRO      | FRO           | US       |                8.31 |             75.14 |         74.08 |         72.32 |          76.2  |        76.36 |           85.62 |             65.01 |             64.85 |         5.24 |             67.5  | long               |              nan    |                  0.26 |                  nan |
|     11 | HAE      | HAE           | US       |                4.22 |             74.65 |         80.51 |         81.11 |          68.78 |        56.71 |           52.52 |             70.82 |             36    |         6.57 |             66.14 | swing              |              nan    |                nan    |                  nan |
|     12 | TALO     | TALO          | US       |                2.54 |             74.64 |         82.47 |         73.97 |          75.3  |        73.04 |           69.19 |             91.04 |             67.6  |         5.58 |             67.5  | short              |                2.08 |                nan    |                  nan |
|     13 | U        | U             | US       |               17.55 |             74.57 |         83.59 |         84.22 |          65.54 |        48.94 |           44.71 |             95.12 |             20.7  |         8.37 |             65.43 | swing              |                0.92 |                 -0.28 |                  nan |
|     14 | DHT      | DHT           | US       |                2.73 |             74.54 |         76.84 |         69.31 |          72.26 |        76.81 |           89.37 |             45.4  |             72.07 |         4.29 |             67.5  | short              |                1.69 |                  0.67 |                  nan |
|     15 | TWST     | TWST          | US       |                7.32 |             74.39 |         84.55 |         80.31 |          68.47 |        49.14 |           47.4  |             75.79 |              7.44 |         7.04 |             64.66 | short              |               -0.21 |                 -0.1  |                  nan |
|     16 | FLYW     | FLYW          | US       |                1.95 |             74.37 |         77.79 |         75.66 |          73.09 |        68.7  |           72.22 |             76.88 |             57.94 |         5.97 |             67.05 | short              |                1.72 |                  0.39 |                  nan |
|     17 | MTA      | MTA           | OTHER    |                0.9  |             74.32 |         82.98 |         80.3  |          68.34 |        58.21 |           56    |             73.97 |             33.91 |         6.79 |             67.5  | short              |                3.93 |                  1.03 |                  nan |
|     18 | SBLK     | SBLK          | US       |                2.88 |             74.01 |         75.77 |         69.25 |          72.26 |        77.14 |           75.27 |             61.86 |             89.2  |         3.9  |             67.16 | long               |                0.12 |                nan    |                  nan |
|     19 | BION.SW  | BB Biotech AG | EUROPE   |                3.26 |             73.98 |         74.43 |         70.59 |          73.53 |        77.7  |           84.24 |             58.88 |             82    |         2.27 |             79.55 | long               |               -0.68 |                  1.04 |                  nan |
|     20 | NIQ      | NIQ           | US       |                4.59 |             73.88 |         84.03 |         84.44 |          63.73 |        53.06 |           37.32 |             95.04 |             50.56 |         9.05 |             66.02 | swing              |              nan    |                 -0.28 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | INVA     | Innoviva, Inc.                  | US       |                1.3  |                  83.63 |                    77.15 |                 77.23 |              78.25 |                78.78 |                   21.22 |           88    |             38.5  |       0.073 |         nan |       nan |        6.5  |         9.5  |          4.98 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE     | StoneCo Ltd.                    | OTHER    |                1.81 |                  78.14 |                    76.28 |                 76.86 |              73.89 |                76.14 |                   23.86 |           97.55 |             39.22 |       0.648 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.  | US       |                0.59 |                  73.21 |                    75.69 |                 78.49 |              74.84 |                81.8  |                   18.2  |           88.69 |             74.03 |       0.178 |         nan |       nan |        4.21 |         2.81 |          5.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.26 |                  72.81 |                    73.87 |                 75.67 |              73.93 |                86.78 |                   13.22 |           84.24 |             58.88 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3.02 |                  72.57 |                    72.5  |                 71.98 |              73.36 |                76.5  |                   23.5  |           68.22 |            nan    |       0.246 |         nan |       nan |        1.54 |       nan    |          2.81 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               25.94 |                  71.62 |                    71.11 |                 71.72 |              70.01 |                63.6  |                   36.4  |           76.78 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              222.26 |                  65.32 |                    70.52 |                 72.43 |              66.54 |                78.43 |                   21.57 |           92.7  |             54    |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.11 |                  70.05 |                    70.1  |                 71.57 |              69.32 |                68.59 |                   31.41 |           79.81 |             65.38 |       0.023 |         nan |       nan |        3.6  |         6.13 |          4.53 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.66 |                  68.97 |                    69.42 |                 71.03 |              70.02 |                81.86 |                   18.14 |           77.1  |             56.27 |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            9 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.78 |                  65.05 |                    69.07 |                 71.63 |              66.42 |                77.98 |                   22.02 |           89.36 |             55.49 |       0.123 |         nan |       nan |        1.96 |        15.74 |          2.63 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|           10 | DXC      | DXC Technology Company          | US       |                1.46 |                  85.24 |                    68.14 |                 62.6  |              73.63 |                48.29 |                   51.71 |           46.61 |             35.65 |       0.513 |         nan |       nan |        3.07 |         3.62 |         14.66 |        0.49 |                 nan |              nan |                  10 |                  0.53 |
|           11 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.32 |                  63.92 |                    67.71 |                 69.41 |              65.32 |                70.94 |                   29.06 |           78.39 |            nan    |       0.419 |         nan |       nan |        7.45 |       nan    |          2.69 |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|           12 | PAH3.DE  | Porsche Automobil Holding SE    | EUROPE   |                8.5  |                  79.46 |                    67.47 |                 64.66 |              74.79 |                64.82 |                   35.18 |           41.25 |             59.15 |      -0.05  |         nan |       nan |     -234.58 |         1.88 |         89.52 |        0.05 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                             | US       |              114.56 |                  62.78 |                    67.18 |                 68.67 |              64.47 |                74.16 |                   25.84 |           81.64 |             59.2  |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           13 | XNET     | Xunlei Limited                  | OTHER    |                0.28 |                  67.15 |                    67.13 |                 66.54 |              69.22 |                70.58 |                   29.42 |           53.95 |             81.67 |     nan     |         nan |       nan |        5.59 |       nan    |          0.37 |        2.58 |                 nan |              nan |                   6 |                  0.32 |
|          nan | BEN      | BEN                             | US       |               14.78 |                  58.31 |                    67.04 |                 69.97 |              62.7  |                78.85 |                   21.15 |           88.45 |             65.25 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | UNIT     | Uniti Group Inc.                | US       |                2.09 |                  80.26 |                    66.65 |                 63.59 |              68.81 |                44.67 |                   55.33 |           65.19 |             29.8  |      -0.106 |         nan |       nan |        9.11 |       -14.17 |          2.69 |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           15 | NEXI.MI  | Nexi S.p.A.                     | EUROPE   |                4.85 |                  78.23 |                    66.34 |                 62.06 |              69.01 |                45.11 |                   54.89 |           52.99 |             45.65 |       0.162 |         nan |       nan |        7.28 |         6.22 |        nan    |        0.07 |                 nan |              nan |                  11 |                  0.58 |
|          nan | BIRG.IR  | BIRG.IR                         | EUROPE   |               17.78 |                  59.79 |                    66.22 |                 68.59 |              60.95 |                76.82 |                   23.18 |           96.23 |             40.68 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           16 | IHS      | IHS Holding Limited             | OTHER    |                2.42 |                  69.56 |                    66.05 |                 66.52 |              69.02 |                59.12 |                   40.88 |           55.61 |             82.95 |      -0.115 |         nan |       nan |        7.48 |        15.2  |          5.1  |      nan    |                 nan |              nan |                  10 |                  0.53 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                            | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:--------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            3 | IRWD     | Ironwood Pharmaceuticals, Inc.  | US       |                0.59 |                  73.21 |                    75.69 |                 78.49 |              74.84 |                81.8  |                   18.2  |           88.69 |             74.03 |       0.178 |         nan |       nan |        4.21 |         2.81 |          5.52 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | INVA     | Innoviva, Inc.                  | US       |                1.3  |                  83.63 |                    77.15 |                 77.23 |              78.25 |                78.78 |                   21.22 |           88    |             38.5  |       0.073 |         nan |       nan |        6.5  |         9.5  |          4.98 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|            2 | STNE     | StoneCo Ltd.                    | OTHER    |                1.81 |                  78.14 |                    76.28 |                 76.86 |              73.89 |                76.14 |                   23.86 |           97.55 |             39.22 |       0.648 |         nan |       nan |        1.6  |         3.91 |          3.61 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | BION.SW  | BB Biotech AG                   | EUROPE   |                3.26 |                  72.81 |                    73.87 |                 75.67 |              73.93 |                86.78 |                   13.22 |           84.24 |             58.88 |       0.813 |         nan |       nan |      nan    |       -83.77 |          2.24 |      nan    |                 nan |              nan |                   7 |                  0.37 |
|          nan | SHELL.AS | SHELL.AS                        | EUROPE   |              222.26 |                  65.32 |                    70.52 |                 72.43 |              66.54 |                78.43 |                   21.57 |           92.7  |             54    |     nan     |         nan |       nan |      nan    |        10.15 |         10.3  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            5 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3.02 |                  72.57 |                    72.5  |                 71.98 |              73.36 |                76.5  |                   23.5  |           68.22 |            nan    |       0.246 |         nan |       nan |        1.54 |       nan    |          2.81 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|            6 | 0QXR.IL  | Stellantis N.V.                 | OTHER    |               25.94 |                  71.62 |                    71.11 |                 71.72 |              70.01 |                63.6  |                   36.4  |           76.78 |            nan    |       0.249 |         nan |       nan |        1.16 |       nan    |          1.3  |        3.92 |                 nan |              nan |                   9 |                  0.47 |
|            9 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.78 |                  65.05 |                    69.07 |                 71.63 |              66.42 |                77.98 |                   22.02 |           89.36 |             55.49 |       0.123 |         nan |       nan |        1.96 |        15.74 |          2.63 |        9.5  |                 nan |              nan |                  11 |                  0.58 |
|            7 | PARR     | Par Pacific Holdings, Inc.      | US       |                3.11 |                  70.05 |                    70.1  |                 71.57 |              69.32 |                68.59 |                   31.41 |           79.81 |             65.38 |       0.023 |         nan |       nan |        3.6  |         6.13 |          4.53 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            8 | NWL.MI   | NewPrinces S.p.A.               | EUROPE   |                0.66 |                  68.97 |                    69.42 |                 71.03 |              70.02 |                81.86 |                   18.14 |           77.1  |             56.27 |       1.004 |         nan |       nan |        5.23 |      -117.15 |          2.06 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BEN      | BEN                             | US       |               14.78 |                  58.31 |                    67.04 |                 69.97 |              62.7  |                78.85 |                   21.15 |           88.45 |             65.25 |     nan     |         nan |       nan |      nan    |        10.73 |         23.11 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.32 |                  63.92 |                    67.71 |                 69.41 |              65.32 |                70.94 |                   29.06 |           78.39 |            nan    |       0.419 |         nan |       nan |        7.45 |       nan    |          2.69 |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|          nan | BMY      | BMY                             | US       |              114.56 |                  62.78 |                    67.18 |                 68.67 |              64.47 |                74.16 |                   25.84 |           81.64 |             59.2  |     nan     |         nan |       nan |      nan    |         9.98 |         14.91 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                         | EUROPE   |               17.78 |                  59.79 |                    66.22 |                 68.59 |              60.95 |                76.82 |                   23.18 |           96.23 |             40.68 |     nan     |         nan |       nan |      nan    |        10.32 |         13.97 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                             | US       |               36.91 |                  55.06 |                    65.14 |                 68.57 |              60.41 |                77.36 |                   22.64 |           87.73 |             68.4  |     nan     |         nan |       nan |      nan    |        12.49 |         31.35 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           21 | AKER.OL  | Aker ASA                        | EUROPE   |                9.86 |                  53.96 |                    64.37 |                 68.5  |              59.44 |                68.73 |                   31.27 |           86.31 |             82.19 |       0.113 |         nan |       nan |        5.35 |        55.39 |          3.82 |        1.88 |                 nan |              nan |                  11 |                  0.58 |
|          nan | FRO      | FRO                             | US       |                8.31 |                  57.15 |                    65    |                 67.85 |              60.82 |                73.14 |                   26.86 |           85.62 |             65.01 |     nan     |         nan |       nan |      nan    |        11.02 |         10.94 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | CRGY     | CRGY                            | US       |                4.65 |                  58.35 |                    65.26 |                 67.61 |              63.18 |                70.78 |                   29.22 |           72.4  |             84.26 |     nan     |         nan |       nan |      nan    |         6.43 |        172.63 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | DHT      | DHT                             | US       |                2.73 |                  61.86 |                    65.85 |                 67.58 |              61.79 |                70.6  |                   29.4  |           89.37 |             45.4  |     nan     |         nan |       nan |      nan    |        10.53 |          6.8  |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | SBLK     | SBLK                            | US       |                2.88 |                  62.86 |                    65.78 |                 66.83 |              63.98 |                69.62 |                   30.38 |           75.27 |             61.86 |     nan     |         nan |       nan |      nan    |         8.44 |         11.83 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                    | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX                     | US       |               11.7  |                     0.07 |    -0.02 |      0.22 |                  69.42 |                        81.15 |         78.14 |         81.35 |          74.9  |        73.39 |           78.42 |             95.88 |         5.99 |
|               2 | WDAY     | WDAY                    | US       |               41.75 |                     0.04 |    -0.04 |      0.54 |                  77.06 |                        76.52 |         77.36 |         75.8  |          65.08 |        61.73 |           74.92 |             75.3  |         8.47 |
|               3 | RBRK     | RBRK                    | US       |               17.19 |                     0.07 |    -0.07 |      0.34 |                  81.3  |                        76.04 |         73.49 |         79.31 |          63.54 |        46.42 |           53.83 |             89.47 |         8.14 |
|               4 | HPE      | HPE                     | US       |               60    |                     0.12 |    -0.12 |      0.11 |                  62.33 |                        74.28 |         59.95 |         78.82 |          79.45 |        72.15 |           71.38 |             74.94 |         6.85 |
|               5 | SYENS.BR | SYENS.BR                | EUROPE   |                8.08 |                     0.04 |    -0.01 |      0.13 |                  64.27 |                        73.94 |         76.14 |         72.07 |          63.31 |        59.61 |           63.98 |             89.59 |         5.1  |
|               6 | DK       | Delek US Holdings, Inc. | US       |                3.36 |                     0.06 |    -0.06 |     -0.01 |                  84.46 |                        73.65 |         58.26 |         75.04 |          75.21 |        67.93 |           66.4  |             67.89 |         6.83 |
|               7 | MPC      | MPC                     | US       |               86.18 |                     0.02 |     0.01 |      0.15 |                  46.29 |                        73.61 |         78.63 |         80.01 |          79.25 |        76.2  |           85.9  |             63.2  |         4.1  |
|               8 | PLTR     | PLTR                    | US       |              358.1  |                     0.03 |    -0.03 |      0.41 |                  62.48 |                        73.54 |         76.56 |         65.3  |          57.92 |        54.58 |           90.74 |             51.57 |         8.4  |
|               9 | KRX.IR   | KRX.IR                  | EUROPE   |               18.12 |                     0.03 |    -0.02 |      0.34 |                  61.51 |                        73.37 |         79.4  |         70.37 |          63.77 |        62.74 |           94.33 |             37.17 |         5.25 |
|              10 | BCRX     | BCRX                    | US       |                2.11 |                     0.09 |    -0.02 |      0.03 |                  54.98 |                        73.26 |         56.85 |         68.04 |          76.6  |        79.19 |           85.31 |             92.86 |         5.93 |
|              11 | SMWB     | SMWB                    | US       |                0.62 |                     0.09 |    -0.09 |      0.35 |                  74    |                        72.84 |         72.33 |         80.69 |          61.87 |        42.85 |           35.43 |             95.4  |         9.45 |
|              12 | GL9.IR   | GL9.IR                  | EUROPE   |                5.35 |                     0.07 |    -0.06 |     -0    |                  77.21 |                        72.45 |         44.12 |         63.63 |          74.96 |        71.77 |           96.65 |             64.77 |         2.35 |
|              13 | OMDA     | Omada Health, Inc.      | US       |                1.24 |                     0.05 |    -0.03 |      0.12 |                  76.39 |                        71.94 |         72.53 |         75.49 |          64.73 |        52.72 |           58.81 |             73.16 |         8.1  |
|              14 | JHX      | JHX                     | US       |               14.93 |                     0.03 |    -0.03 |      0.16 |                  65.82 |                        71.4  |         73.81 |         75.78 |          67.23 |        59.66 |           57.81 |             80.51 |         6.49 |
|              15 | TPG      | TPG                     | US       |               17.25 |                     0.06 |    -0.06 |      0.24 |                  86.6  |                        71.38 |         72.39 |         67.69 |          57.87 |        54.61 |           52.34 |             78.21 |         6.42 |
|              16 | NTNX     | NTNX                    | US       |               15.36 |                     0.02 |    -0.02 |      0.26 |                  58.5  |                        71.07 |         70.29 |         74.07 |          63.64 |        54.71 |           77.11 |             65.62 |         7.08 |
|              17 | MP       | MP                      | US       |                8.4  |                     0.06 |    -0.01 |      0.23 |                  69.14 |                        70.83 |         72.33 |         49.09 |          47.44 |        45.13 |           57.65 |             85.11 |         8.68 |
|              18 | COUR     | COUR                    | US       |                1.44 |                     0.05 |     0.01 |      0.09 |                  67.33 |                        70.72 |         65.48 |         60.44 |          62.12 |        71.67 |           67.66 |             95.64 |         8.19 |
|              19 | TCPC     | TCPC                    | US       |                0.29 |                     0.04 |    -0.04 |      0.29 |                  75.72 |                        70.53 |         71.36 |         59.77 |          55.86 |        62.28 |           48.1  |             92.49 |         6.95 |
|              20 | BEN      | BEN                     | US       |               14.78 |                     0.05 |     0    |      0.05 |                  66.99 |                        70.25 |         63.68 |         65.46 |          74    |        77.77 |           88.45 |             65.25 |         3.12 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | NTAP     | NetApp, Inc.                                         | US       |               32.41 |             65.82 |         64.02 |         72.92 |          67.62 |        58.16 |           57.44 |             58.89 |             41.58 |         6.54 |             88.72 | swing              |                0.38 |                 -2.22 |                  nan |
|    nan | SNOW     | Snowflake Inc.                                       | US       |               95.39 |             65.17 |         68.48 |         75.32 |          61.86 |        46.42 |           44.57 |             66.88 |             16.73 |         8.2  |             86.03 | swing              |               -0.5  |                 -1.35 |                  nan |
|    nan | NVDA     | NVIDIA Corporation                                   | US       |             4499.25 |             59.06 |         56.5  |         53.62 |          61.61 |        63.79 |           91.27 |             63.36 |             29.72 |         5.51 |             89.48 | long               |                1.61 |                 -0.95 |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.13 |             56.53 |         71.96 |         56.1  |          56.95 |        54.94 |           52.06 |             83.58 |             33.62 |         5.96 |             77.94 | short              |                0.4  |                  0.31 |                  nan |
|    nan | AVGO     | Broadcom Inc.                                        | US       |             1483.58 |             50.78 |         32.53 |         43    |          58.57 |        61.61 |           85.08 |             64.05 |             30.98 |         6.08 |             89.81 | long               |                0.49 |                 -0.71 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.68 |             50.67 |         32.04 |         49.75 |          51.58 |        57.19 |           40.81 |             50.29 |             83.81 |         8.44 |             85.47 | long               |               -2.75 |                 -1.79 |                  nan |
|    nan | MTRX     | Matrix Service Company                               | US       |                0.27 |             47.61 |         36.47 |         42.62 |          52.61 |        61.46 |           60.76 |             62.09 |             78    |         5.89 |             80.44 | long               |              nan    |                 -0.12 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.05 |             47.37 |         40.69 |         42.64 |          52.11 |        61.24 |           78.9  |             43.36 |             52.62 |         3.87 |             75.81 | long               |               -2.44 |                 -0.74 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.72 |             46.11 |         39.91 |         41.1  |          51.12 |        64.22 |           66.38 |             56.46 |             87.68 |         4.23 |             82.14 | long               |               -0.87 |                 -0.13 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             38.04 |         38.35 |         31.09 |          37.72 |        43.18 |           42.43 |             68.57 |             48.1  |         7.02 |             77.1  | long               |               -6.39 |                  0.19 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.89 |             37.64 |         29.35 |         33.87 |          41.41 |        53.17 |           45.83 |             46.74 |             81.26 |         6.15 |             78.58 | long               |                0.39 |                 -0.27 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.19 |             36.53 |         25.28 |         32.76 |          40.3  |        54.17 |           43.47 |             40.78 |             93.85 |         7.1  |             78.43 | long               |               -0.25 |                 -0.47 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.86 |             32.9  |         30.22 |         22.74 |          35.57 |        46.31 |           64.89 |             18.95 |             39.11 |         9.02 |             78.45 | long               |               -6.54 |                 -0.47 |                  nan |
|    nan | AT1.DE   | Aroundtown SA                                        | EUROPE   |                2.13 |             30.22 |         26.35 |         24.69 |          34.09 |        46    |           54.37 |             36.76 |             59.38 |         5.48 |             75.53 | long               |                0.35 |                  0.49 |                  nan |
|    nan | LI       | Li Auto Inc.                                         | OTHER    |               10.85 |             24.71 |         45.27 |         24.29 |          23.48 |        25.13 |           26.05 |             39.3  |             24.85 |         6.71 |             76.54 | short              |                1.6  |                 -0.45 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name                            | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:--------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|     64 | OMDA     | Omada Health, Inc.              | US       |                1.24 |             68.63 |         72.53 |         75.49 |          64.73 |        52.72 |           58.81 |             73.16 |             23.97 |         8.1  |             85.63 | swing              |               19.57 |                  3.25 |                  nan |
|    123 | SDF.DE   | K+S Aktiengesellschaft        N | EUROPE   |                2.78 |             65.15 |         66.99 |         54.63 |          63.3  |        71.52 |           89.36 |             55.49 |             64.17 |         4.33 |             82    | long               |                1.53 |                  3.01 |                  nan |
|    238 | SLDB     | Solid Biosciences Inc.          | US       |                0.84 |             60.46 |         62.93 |         64.54 |          57.99 |        44.72 |           43.72 |             51.39 |             16.29 |         8.12 |             79.67 | swing              |                1.88 |                  2.43 |                  nan |
|    137 | 0Q2N.IL  | K+S Aktiengesellschaft          | OTHER    |                3.02 |             64.44 |         71.69 |         52.17 |          60.08 |        68.81 |           68.22 |            nan    |             76.1  |         4.52 |             67.39 | short              |               -0.59 |                  2.36 |                  nan |
|    564 | 0P6O.IL  | Volkswagen AG                   | OTHER    |               41.32 |             46.05 |         47.24 |         28.89 |          44.86 |        62.82 |           78.39 |            nan    |             68.44 |         4.98 |             70.77 | long               |                0.29 |                  2.15 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name            | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:----------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    400 | TKA.DE   | TKA.DE          | EUROPE   |                7.88 |             54.47 |         52.89 |         50.95 |          56.04 |        67.61 |          nan    |             19.37 |             80.7  |         6.6  |             64.66 | long               |              -21.9  |                 -4.67 |                  nan |
|    636 | AMV0.DE  | Aumovio SE      | EUROPE   |                3.64 |             41.36 |         43.52 |         31.97 |          39.2  |        50.56 |           51.14 |             35.29 |             71.84 |         6.03 |             75.47 | long               |                3.48 |                 -4.6  |                  nan |
|    700 | HFG.DE   | HelloFresh SE   | EUROPE   |                0.42 |             24.63 |         22.43 |         19.23 |          26.84 |        37.49 |           39.86 |             28.86 |             57.74 |         6.84 |             80.79 | long               |               -0.25 |                 -4.48 |                  nan |
|    583 | FOSL     | FOSL            | US       |                0.28 |             45.08 |         67.68 |         51.83 |          38.33 |        32.12 |            7.81 |              2.42 |             48.97 |         8.12 |             63.18 | short              |              -16.99 |                 -3.56 |                  nan |
|    698 | STLAP.PA | Stellantis N.V. | EUROPE   |               16.81 |             26.15 |         24.38 |         18.79 |          27.92 |        35.78 |           43.97 |             37.64 |             40.95 |         6.16 |             84.82 | long               |               -1.99 |                 -3.26 |                  nan |

## Duplicate-security checks

- TEK.L duplicates MTCL.XC (security_id=ISIN:PLCTHQM00018)
- STLA.VI duplicates STLA (security_id=ISIN:AR0940941575)
- VTYL.XC duplicates MTCL.XC (security_id=ISIN:PLCTHQM00018)
- HEADL.XC duplicates MTCL.XC (security_id=ISIN:PLCTHQM00018)
- STLAM.MI duplicates STLA (security_id=ISIN:AR0940941575)

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
- Excluded by hard/data filters: **284**
- Event watch (otherwise eligible): **15**
- Final eligible: **701**
- Eligible change vs previous stored run: **+7**

Top exclusion categories:
- liquidity: 230
- price: 169
- market_cap: 157
- price_history: 20
- data_confidence: 12
- duplicate_listing: 5
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| MPC | 1 |  | 7 |  | 2 | main,pullback |
| BAX | 4 |  | 1 |  | 2 | main,pullback |
| HPE | 8 |  | 4 |  | 2 | main,pullback |
| BION.SW | 19 | 4 |  | 4 | 1 | value,quality_value |
| PARR | 42 | 7 |  | 8 | 1 | value,quality_value |
| IRWD | 84 | 3 | 23 | 1 | 1 | value,quality_value |
| SDF.DE | 123 | 9 |  | 7 | 1 | value,quality_value |
| 0Q2N.IL | 137 | 5 |  | 5 | 1 | value,quality_value |
| 0QXR.IL | 432 | 6 |  | 6 | 1 | value,quality_value |
| INVA | 511 | 1 | 228 | 2 | 1 | value,quality_value |
| NWL.MI | 591 | 8 | 204 | 9 | 1 | value,quality_value |
| STNE | 643 | 2 |  | 3 | 1 | value,quality_value |
| AKER.OL | 2 | 21 |  | 11 | 1 | main |
| CRGY | 3 |  |  |  | 1 | main |
| PSX | 5 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **7** (CRGY, PSX, PGEN, CCC, HPE, GH, FRO)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **3** (HPE, SYENS.BR, BCRX)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 75.10 | 68.97 | 83.41 | 77.10 | 56.27 | 81.86 | 44.66 |
| 2 | IRWD | value+pullback | 74.37 | 73.21 | 61.38 | 88.69 | 74.03 | 81.80 | 67.50 |
| 3 | INVA | value+pullback | 71.96 | 83.63 | 56.26 | 88.00 | 38.50 | 78.78 | 49.14 |
| 4 | DK | value+pullback | 68.99 | 60.68 | 84.46 | 66.40 | 67.89 | 64.62 | 71.48 |
| 5 | PAH3.DE | value+pullback | 65.86 | 79.46 | 67.83 | 41.25 | 59.15 | 64.82 | 41.01 |
| 6 | ETG | value+pullback | 64.95 | 57.92 | 56.72 | 67.74 | 81.93 | 75.21 | 60.76 |
| 7 | GDRX | value+pullback | 64.02 | 70.20 | 78.33 | 65.77 | 40.70 | 47.20 | 62.59 |
| 8 | NEXI.MI | value+pullback | 63.87 | 78.23 | 75.47 | 52.99 | 45.65 | 45.11 | 58.59 |
| 9 | DOM.ST | value+pullback | 62.89 | 56.18 | 78.41 | 66.81 | 31.87 | 66.12 | 33.51 |
| 10 | CNC | value+pullback | 62.77 | 70.10 | 75.73 | 45.68 | 65.00 | 47.30 | 61.96 |
| 11 | MSFT | value+pullback | 62.42 | 58.21 | 74.85 | 61.82 | 64.84 | 52.43 | 59.15 |
| 12 | DBX | value+pullback | 61.88 | 59.28 | 85.71 | 51.55 | 38.90 | 55.22 | 59.80 |
| 13 | MFA | value+pullback | 61.57 | 57.65 | 63.80 | 80.59 | 34.45 | 63.96 | 43.40 |
| 14 | DXC | value+pullback | 61.19 | 85.24 | 61.62 | 46.61 | 35.65 | 48.29 | 53.25 |
| 15 | ORCL | value+pullback | 60.84 | 69.90 | 75.23 | 50.65 | 58.16 | 38.28 | 41.97 |
| 16 | ALL-PH | value+pullback | 59.43 | 62.51 | 57.83 | 67.90 | 42.68 | 58.85 | 44.41 |
| 17 | KYN | value+pullback | 58.42 | 60.07 | 46.38 | 53.68 | 81.93 | 62.79 | 58.98 |
| 18 | ONIT | value+pullback | 58.20 | 70.77 | 60.49 | 60.22 | 44.61 | 41.75 | 42.42 |
| 19 | WKC | value+pullback | 57.87 | 56.05 | 47.71 | 55.71 | 75.13 | 66.28 | 65.71 |
| 20 | BION.SW | value | 57.72 | 72.81 | 37.64 | 84.24 | 58.88 | 86.78 | 73.98 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 9/10 | 9/10 | 8/10 | 0/10 | 66.5 | 3 / 7 |
| Top 25 | 24/25 | 24/25 | 24/25 | 22/25 | 0/25 | 67.0 | 7 / 18 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 67.0 | 12 / 38 |

Top-10 market-cap mix: small_1_5b=3, mid_5_20b=4, large_20_100b=3
