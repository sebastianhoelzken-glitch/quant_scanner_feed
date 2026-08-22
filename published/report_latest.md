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

- **EUROPE:** 88.0/100
- **OTHER:** 72.6/100
- **US:** 84.2/100

## Main multi-horizon ranking

|   rank | symbol   | name                       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|      1 | PSX      | PSX                        | US       |               82.98 |             82.28 |         81.83 |         86.02 |          82.72 |        77.8  |           78.45 |             82.71 |             64.99 |         3.51 |             67.5  | swing              |                5.43 |                nan    |                  nan |
|      2 | ERO      | ERO                        | US       |                3.52 |             78.75 |         88.4  |         78.21 |          75.26 |        79.3  |           82.67 |             52.36 |             79.82 |         7.53 |             67.5  | short              |                3.6  |                nan    |                  nan |
|      3 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |             78.4  |         66.11 |         77.12 |          81.53 |        79.68 |           83.48 |             66.2  |             72.8  |         6.76 |             85.72 | medium             |                8.77 |                  0.47 |                  nan |
|      4 | MU       | MU                         | US       |              934.97 |             78.17 |         60.91 |         72.23 |          84.1  |        85.28 |           95.4  |             60.58 |             77.22 |         8.19 |             64.25 | long               |                0.26 |                nan    |                  nan |
|      5 | DK       | DK                         | US       |                3.75 |             78.12 |         82.99 |         82.99 |          73.25 |        59.13 |           53.86 |             74.61 |             32.85 |         6.76 |             67.5  | swing              |               10.96 |                  0.99 |                  nan |
|      6 | CRGY     | CRGY                       | US       |                3.98 |             78.04 |         82.98 |         75.77 |          76.38 |        79.7  |           70.73 |             84.04 |             95.6  |         6.19 |             67.05 | short              |              nan    |                nan    |                  nan |
|      7 | PBF      | PBF                        | US       |                7.46 |             77.91 |         80    |         81.46 |          75.82 |        72.11 |           50.88 |             58.89 |             92.9  |         7.13 |             67.05 | swing              |                4.32 |                 -0.07 |                  nan |
|      8 | AMC      | AMC                        | US       |                1.95 |             77.19 |         68.01 |         81.96 |          77.5  |        76.88 |           82.63 |             80.05 |            nan    |         9.61 |             61.25 | swing              |                0.41 |                nan    |                  nan |
|      9 | CCC      | CCC                        | US       |                3.76 |             77.13 |         82.73 |         81.01 |          73.25 |        72.27 |           86.89 |             80.65 |             57.93 |         7.97 |             66.02 | short              |                0.18 |                  0.96 |                  nan |
|     10 | FLYW     | FLYW                       | US       |                2.04 |             77.13 |         81.73 |         79.53 |          74.72 |        69.4  |           72.13 |             76.9  |             55.13 |         5.95 |             66.7  | short              |              nan    |                  1.48 |                  nan |
|     11 | TWST     | TWST                       | US       |                7.82 |             77    |         88.8  |         84.22 |          69.79 |        49.66 |           45.23 |             77.51 |              7.78 |         7.04 |             64.66 | short              |                1.61 |                  0.33 |                  nan |
|     12 | ZD       | ZD                         | US       |                1.65 |             76.45 |         74.27 |         83.67 |          78.63 |        72.96 |           52.38 |             89    |             86.9  |         5.5  |             67.05 | swing              |              nan    |                  0.24 |                  nan |
|     13 | HPE      | HPE                        | US       |               60.61 |             76.43 |         61.82 |         80.49 |          80.26 |        72.61 |           69.26 |             74.85 |             60.35 |         6.86 |             65.68 | swing              |                0.35 |                 -0.72 |                  nan |
|     14 | BAX      | BAX                        | US       |               11.66 |             76.31 |         76.82 |         81.71 |          75.79 |        74.18 |           76.36 |             96.32 |             62.95 |         6.01 |             63.95 | swing              |               -1.63 |                  0.05 |                  nan |
|     15 | SBLK     | SBLK                       | US       |                2.92 |             76.24 |         79.35 |         73.85 |          74.52 |        77.96 |           73.78 |             61.91 |             88.31 |         4.1  |             67.16 | short              |                1.19 |                  0.25 |                  nan |
|     16 | PGEN     | PGEN                       | US       |                2.2  |             75.9  |         89.36 |         82.75 |          69.05 |        52.28 |           67.46 |            nan    |              1.95 |         7.73 |             62.84 | short              |               -1.73 |                  1.14 |                  nan |
|     17 | BFLY     | BFLY                       | US       |                2.18 |             75.82 |         82.16 |         82.17 |          69.48 |        50.57 |           45.42 |             75.09 |             12.13 |         8.46 |             63.64 | swing              |                1.42 |                  0.96 |                  nan |
|     18 | TALO     | TALO                       | US       |                2.5  |             75.72 |         83.66 |         74.8  |          76.64 |        74.35 |           68.71 |             92.26 |             68.57 |         5.61 |             67.5  | short              |              nan    |                nan    |                  nan |
|     19 | JCAP     | JCAP                       | US       |                1.1  |             75.55 |         73.37 |         75.89 |          75.21 |        82.24 |           84.26 |             86.22 |             84.86 |         5.57 |             65.45 | long               |              nan    |                 -1.28 |                  nan |
|     20 | TGB      | TGB                        | US       |                2.88 |             75.48 |         88.5  |         79.15 |          71.82 |        68.18 |           55.74 |             83.92 |             61.07 |         7.62 |             67.05 | short              |                1.71 |                  0.76 |                  nan |

## Undervalued opportunities

Pure undervaluation combines six groups: cash-flow value, enterprise multiples, earnings multiples, sales/assets, growth-adjusted value, and shareholder-return value. Size, region and sector peers are used before global fallback. `value_conviction_score` then adds quality, revisions and value-trap safety without changing the pure undervaluation score.

|   value_rank | symbol   | name                                 | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:-------------------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            1 | STNE     | StoneCo Ltd.                         | OTHER    |                1.85 |                  77.14 |                    73.8  |                 73.65 |              72.54 |                70.88 |                   29.12 |           87.77 |             42.42 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | GSL      | Global Ship Lease, Inc.              | OTHER    |                1.35 |                  81.57 |                    72.75 |                 71.29 |              75.34 |                70.31 |                   29.69 |           72.39 |             39.56 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.28 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            3 | PARR     | Par Pacific Holdings, Inc.           | US       |                3.39 |                  72.81 |                    72.23 |                 73.84 |              71.37 |                68.49 |                   31.51 |           83.48 |             66.2  |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            4 | EMBC     | Embecta Corp.                        | US       |                0.25 |                  75.37 |                    71.22 |                 71.52 |              71.45 |                62.59 |                   37.41 |           77.39 |             59.1  |       0.466 |         nan |       nan |        5.62 |         2.97 |          3.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            5 | BION.SW  | BB Biotech AG                        | EUROPE   |                3.3  |                  76.24 |                    70.72 |                 68.59 |              69.08 |                77.8  |                   22.2  |           89.37 |              1.77 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | SHELL.AS | SHELL.AS                             | EUROPE   |              220.22 |                  64.86 |                    70.66 |                 72.79 |              66.41 |                79.13 |                   20.87 |           94.14 |             54.66 |     nan     |         nan |       nan |      nan    |        10.07 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            6 | 0P6O.IL  | Volkswagen AG                        | OTHER    |               41.5  |                  67.28 |                    69.57 |                 70.71 |              67.93 |                70.55 |                   29.45 |           76.99 |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|          nan | PAH3.DE  | PAH3.DE                              | EUROPE   |                8.56 |                  62.28 |                    68.11 |                 69.97 |              67.44 |                78.71 |                   21.29 |          nan    |             84.28 |     nan     |         nan |       nan |      nan    |         1.89 |         90.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            7 | PBR-A    | Petróleo Brasileiro S.A. - Petrobras | OTHER    |              100.96 |                  79.16 |                    67.85 |                 65.67 |              72.73 |                49.54 |                   50.46 |           49.57 |             68.16 |       0.154 |         nan |       nan |        1.75 |         7    |          4.3  |        4.17 |                 nan |              nan |                  12 |                  0.63 |
|            8 | WB       | Weibo Corporation                    | OTHER    |                1.48 |                  77.93 |                    67.59 |                 64.39 |              69.29 |                59.89 |                   40.11 |           66.92 |             24.08 |     nan     |         nan |       nan |        1.98 |         5.34 |          5.81 |        0.79 |                 nan |              nan |                   9 |                  0.47 |
|            9 | UNIT     | Uniti Group Inc.                     | US       |                2.07 |                  80.26 |                    67.08 |                 64.18 |              69.27 |                45.43 |                   54.57 |           65.19 |             33.02 |      -0.107 |         nan |       nan |        9.1  |       -14.04 |          2.6  |        0.17 |                 nan |              nan |                   9 |                  0.47 |
|           10 | AMCX     | AMC Global Media Inc.                | US       |                0.44 |                  64.77 |                    66.98 |                 67.67 |              68    |                75.36 |                   24.64 |           62.08 |             78.01 |       1.964 |         nan |       nan |        7.08 |         4.48 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|          nan | BMY      | BMY                                  | US       |              117.21 |                  63.73 |                    66.94 |                 68.04 |              64.73 |                72.31 |                   27.69 |           79.09 |             58.28 |     nan     |         nan |       nan |      nan    |        10.22 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI   | NewPrinces S.p.A.                    | EUROPE   |                0.65 |                  65.2  |                    66.71 |                 68.95 |              66.07 |                75.25 |                   24.75 |           79.78 |             55.84 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          1.97 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           12 | IHS      | IHS Holding Limited                  | OTHER    |                2.43 |                  71.87 |                    66.49 |                 66.06 |              70.86 |                60.17 |                   39.83 |           49.09 |             82.81 |      -0.114 |         nan |       nan |        7.5  |        15.27 |          5.15 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|           13 | PKX      | POSCO Holdings Inc.                  | OTHER    |               14.85 |                  65.91 |                    66.42 |                 68.81 |              65.43 |                61.82 |                   38.18 |           78.4  |             68.5  |      -0.144 |         nan |       nan |        3.9  |         9.94 |         28.11 |        0.89 |                 nan |              nan |                  12 |                  0.63 |
|          nan | BEN      | BEN                                  | US       |               14.93 |                  57.2  |                    66.34 |                 69.4  |              61.89 |                78.52 |                   21.48 |           88.05 |             65.78 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | VOW3.DE  | VOW3.DE                              | EUROPE   |               37.61 |                  67.72 |                    66.12 |                 65.72 |              66.27 |                62.15 |                   37.85 |          nan    |             63.29 |     nan     |         nan |       nan |      nan    |         3.19 |          7.25 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           14 | INVA     | Innoviva, Inc.                       | US       |                1.3  |                  60.62 |                    65.94 |                 68.9  |              62.54 |                82.21 |                   17.79 |           92.59 |             40.94 |       0.072 |         nan |       nan |        6.52 |         9.53 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|          nan | DHT      | DHT                                  | US       |                2.74 |                  61.71 |                    65.57 |                 67.24 |              61.62 |                70.16 |                   29.84 |           88.44 |             45.59 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Quality Value / GARP-style opportunities

|   value_rank | symbol   | name                       | region   |   market_cap_eur_bn |   undervaluation_score |   value_conviction_score |   quality_value_score |   deep_value_score |   value_safety_score |   value_trap_risk_score |   quality_score |   revisions_score |   fcf_yield |   cfo_yield |   ev_ebit |   ev_ebitda |   forward_pe |   trailing_pe |   peg_ratio |   shareholder_yield |   net_cash_yield |   value_data_points |   value_data_coverage |
|-------------:|:---------|:---------------------------|:---------|--------------------:|-----------------------:|-------------------------:|----------------------:|-------------------:|---------------------:|------------------------:|----------------:|------------------:|------------:|------------:|----------:|------------:|-------------:|--------------:|------------:|--------------------:|-----------------:|--------------------:|----------------------:|
|            3 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |                  72.81 |                    72.23 |                 73.84 |              71.37 |                68.49 |                   31.51 |           83.48 |             66.2  |       0.021 |         nan |       nan |        3.86 |         6.69 |          4.64 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            1 | STNE     | StoneCo Ltd.               | OTHER    |                1.85 |                  77.14 |                    73.8  |                 73.65 |              72.54 |                70.88 |                   29.12 |           87.77 |             42.42 |       0.633 |         nan |       nan |        1.61 |         4.03 |          3.56 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|          nan | SHELL.AS | SHELL.AS                   | EUROPE   |              220.22 |                  64.86 |                    70.66 |                 72.79 |              66.41 |                79.13 |                   20.87 |           94.14 |             54.66 |     nan     |         nan |       nan |      nan    |        10.07 |         10.23 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|            4 | EMBC     | Embecta Corp.              | US       |                0.25 |                  75.37 |                    71.22 |                 71.52 |              71.45 |                62.59 |                   37.41 |           77.39 |             59.1  |       0.466 |         nan |       nan |        5.62 |         2.97 |          3.71 |      nan    |                 nan |              nan |                  10 |                  0.53 |
|            2 | GSL      | Global Ship Lease, Inc.    | OTHER    |                1.35 |                  81.57 |                    72.75 |                 71.29 |              75.34 |                70.31 |                   29.69 |           72.39 |             39.56 |       0.082 |         nan |       nan |        3.78 |         4.95 |          4.28 |        0.87 |                 nan |              nan |                  11 |                  0.58 |
|            6 | 0P6O.IL  | Volkswagen AG              | OTHER    |               41.5  |                  67.28 |                    69.57 |                 70.71 |              67.93 |                70.55 |                   29.45 |           76.99 |            nan    |       0.417 |         nan |       nan |        7.45 |       nan    |          2.7  |        0.69 |                 nan |              nan |                   9 |                  0.47 |
|          nan | PAH3.DE  | PAH3.DE                    | EUROPE   |                8.56 |                  62.28 |                    68.11 |                 69.97 |              67.44 |                78.71 |                   21.29 |          nan    |             84.28 |     nan     |         nan |       nan |      nan    |         1.89 |         90.19 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BEN      | BEN                        | US       |               14.93 |                  57.2  |                    66.34 |                 69.4  |              61.89 |                78.52 |                   21.48 |           88.05 |             65.78 |     nan     |         nan |       nan |      nan    |        10.84 |         23.34 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           11 | NWL.MI   | NewPrinces S.p.A.          | EUROPE   |                0.65 |                  65.2  |                    66.71 |                 68.95 |              66.07 |                75.25 |                   24.75 |           79.78 |             55.84 |       1.028 |         nan |       nan |        5.16 |      -114.47 |          1.97 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|           14 | INVA     | Innoviva, Inc.             | US       |                1.3  |                  60.62 |                    65.94 |                 68.9  |              62.54 |                82.21 |                   17.79 |           92.59 |             40.94 |       0.072 |         nan |       nan |        6.52 |         9.53 |          4.89 |        0.31 |                 nan |              nan |                  11 |                  0.58 |
|           13 | PKX      | POSCO Holdings Inc.        | OTHER    |               14.85 |                  65.91 |                    66.42 |                 68.81 |              65.43 |                61.82 |                   38.18 |           78.4  |             68.5  |      -0.144 |         nan |       nan |        3.9  |         9.94 |         28.11 |        0.89 |                 nan |              nan |                  12 |                  0.63 |
|            5 | BION.SW  | BB Biotech AG              | EUROPE   |                3.3  |                  76.24 |                    70.72 |                 68.59 |              69.08 |                77.8  |                   22.2  |           89.37 |              1.77 |       0.801 |         nan |       nan |      nan    |       -84.98 |          2.31 |      nan    |                 nan |              nan |                   8 |                  0.42 |
|          nan | BMY      | BMY                        | US       |              117.21 |                  63.73 |                    66.94 |                 68.04 |              64.73 |                72.31 |                   27.69 |           79.09 |             58.28 |     nan     |         nan |       nan |      nan    |        10.22 |         14.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | KDP      | KDP                        | US       |               37.34 |                  54.81 |                    64.58 |                 67.89 |              60.09 |                76.36 |                   23.64 |           85.81 |             68.8  |     nan     |         nan |       nan |      nan    |        12.64 |         32.36 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|           10 | AMCX     | AMC Global Media Inc.      | US       |                0.44 |                  64.77 |                    66.98 |                 67.67 |              68    |                75.36 |                   24.64 |           62.08 |             78.01 |       1.964 |         nan |       nan |        7.08 |         4.48 |        nan    |        0.55 |                 nan |              nan |                  10 |                  0.53 |
|           16 | TNK      | Teekay Tankers Ltd.        | OTHER    |                2.7  |                  53.89 |                    63.9  |                 67.53 |              60.82 |                80.44 |                   19.56 |           79.57 |             75.46 |       0.071 |         nan |       nan |        3.88 |         8.35 |          5.36 |        1.1  |                 nan |              nan |                  12 |                  0.63 |
|          nan | DHT      | DHT                        | US       |                2.74 |                  61.71 |                    65.57 |                 67.24 |              61.62 |                70.16 |                   29.84 |           88.44 |             45.59 |     nan     |         nan |       nan |      nan    |        10.54 |          6.74 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | FRO      | FRO                        | US       |                8.32 |                  56.78 |                    64.29 |                 67.01 |              60.34 |                72.07 |                   27.93 |           83.68 |             64.81 |     nan     |         nan |       nan |      nan    |        11.05 |         10.76 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | BIRG.IR  | BIRG.IR                    | EUROPE   |               18.08 |                  54.55 |                    63.46 |                 66.58 |              57.53 |                77.21 |                   22.79 |           95.69 |             43.53 |     nan     |         nan |       nan |      nan    |        10.5  |         14.42 |      nan    |                 nan |              nan |                   5 |                  0.26 |
|          nan | PSX      | PSX                        | US       |               82.98 |                  50.56 |                    62.79 |                 66.57 |              58.84 |                78.7  |                   21.3  |           78.45 |             82.71 |     nan     |         nan |       nan |      nan    |        11.43 |        110.9  |      nan    |                 nan |              nan |                   5 |                  0.26 |

## Pullback opportunities

Pullback is now a **separate strategy view**, not a global eligibility requirement. Configured setup: 1.5%–12.0% below the 20-day high, 5d return <= 2.0%, 20d return >= -15.0%.

|   pullback_rank | symbol   | name                       | region   |   market_cap_eur_bn |   pullback_from_20d_high |   ret_5d |   ret_20d |   pullback_setup_score |   pullback_opportunity_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   risk_score |
|----------------:|:---------|:---------------------------|:---------|--------------------:|-------------------------:|---------:|----------:|-----------------------:|-----------------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|-------------:|
|               1 | BAX      | BAX                        | US       |               11.66 |                     0.07 |    -0.01 |      0.18 |                  65.25 |                        80.36 |         76.82 |         81.71 |          75.79 |        74.18 |           76.36 |             96.32 |         6.01 |
|               2 | JCAP     | JCAP                       | US       |                1.1  |                     0.07 |    -0.07 |      0.12 |                  81.56 |                        79.96 |         73.37 |         75.89 |          75.21 |        82.24 |           84.26 |             86.22 |         5.57 |
|               3 | GENI     | GENI                       | US       |                1.85 |                     0.04 |    -0.04 |      0.24 |                  71.56 |                        78.27 |         75.5  |         80.17 |          71.63 |        71.66 |           64.34 |             97.22 |         9.11 |
|               4 | DELL     | DELL                       | US       |              244.6  |                     0.11 |    -0.1  |      0.01 |                  68.21 |                        76.98 |         51.18 |         80.31 |          80.63 |        67.81 |           69.6  |             84.52 |         7.76 |
|               5 | RBRK     | RBRK                       | US       |               17.64 |                     0.05 |    -0.02 |      0.37 |                  72.34 |                        76.2  |         78.32 |         82.66 |          65.2  |        47.38 |           53.36 |             88.97 |         8.14 |
|               6 | AMRX     | AMRX                       | US       |                5.34 |                     0.06 |    -0.01 |     -0    |                  70.17 |                        75.38 |         56.5  |         72.78 |          76.68 |        74.67 |           92.09 |             66.99 |         4.64 |
|               7 | WDAY     | WDAY                       | US       |               42.3  |                     0.03 |     0.01 |      0.48 |                  54.14 |                        75.2  |         82.1  |         78.31 |          66.61 |        62.35 |           73.58 |             75.45 |         8.47 |
|               8 | HPE      | HPE                        | US       |               60.61 |                     0.11 |    -0.09 |      0.12 |                  65.09 |                        75.09 |         61.82 |         80.49 |          80.26 |        72.61 |           69.26 |             74.85 |         6.86 |
|               9 | P        | P                          | US       |               30.9  |                     0.08 |    -0.08 |      0.46 |                  78.25 |                        74.76 |         76.4  |         76.51 |          66.75 |        55.14 |           66.62 |             76.3  |         7.97 |
|              10 | AMC      | AMC                        | US       |                1.95 |                     0.11 |     0.02 |      0.12 |                  33.88 |                        74.6  |         68.01 |         81.96 |          77.5  |        76.88 |           82.63 |             80.05 |         9.61 |
|              11 | MU       | MU                         | US       |              934.97 |                     0.04 |    -0.01 |      0.05 |                  65.77 |                        74.15 |         60.91 |         72.23 |          84.1  |        85.28 |           95.4  |             60.58 |         8.19 |
|              12 | PARR     | Par Pacific Holdings, Inc. | US       |                3.39 |                     0.08 |    -0.02 |      0.02 |                  59.2  |                        74.07 |         66.11 |         77.12 |          81.53 |        79.68 |           83.48 |             66.2  |         6.76 |
|              13 | KRX.IR   | KRX.IR                     | EUROPE   |               18.1  |                     0.03 |    -0.01 |      0.32 |                  58.17 |                        73.81 |         79.76 |         68.17 |          63.62 |        63.76 |           97.46 |             38.09 |         5.26 |
|              14 | SYENS.BR | SYENS.BR                   | EUROPE   |                8.15 |                     0.03 |    -0.03 |      0.12 |                  64.95 |                        73.78 |         73.74 |         72.32 |          64.3  |        59.88 |           68.26 |             90.08 |         5.27 |
|              15 | BCRX     | BCRX                       | US       |                2.09 |                     0.1  |    -0.02 |      0.02 |                  49.78 |                        73.54 |         54.35 |         70.32 |          78.08 |        80.48 |           84.3  |             93.71 |         5.88 |
|              16 | CAKE     | CAKE                       | US       |                4.83 |                     0.03 |    -0    |      0.34 |                  57.81 |                        73.19 |         81.65 |         77.55 |          70.96 |        63.87 |           85.93 |             43.38 |         5.82 |
|              17 | GL9.IR   | GL9.IR                     | EUROPE   |                5.4  |                     0.06 |    -0.03 |      0.01 |                  75.43 |                        72.99 |         48.12 |         64.74 |          75.41 |        71.26 |           97.46 |             65.42 |         2.45 |
|              18 | DAR      | DAR                        | US       |                8.88 |                     0.04 |    -0.02 |      0.05 |                  65.99 |                        72.2  |         67.22 |         69.02 |          76.96 |        80    |           91.82 |             62.88 |         3.96 |
|              19 | NWL      | NWL                        | US       |                2.22 |                     0.04 |    -0.02 |      0.2  |                  70.08 |                        72.02 |         72.23 |         81.73 |          69.25 |        64.3  |           32.23 |             94.65 |         8.23 |
|              20 | QNST     | QNST                       | US       |                1.01 |                     0.06 |     0.01 |      0.36 |                  63.82 |                        72.01 |         80.76 |         74.71 |          68.58 |        70.37 |           83.08 |             36.28 |         7.88 |

## Event watch

Earnings within 14 days are separated because event risk can overwhelm the normal factor model.

|   rank | symbol   | name                                                 | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------------------------------------------------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    nan | PD       | PagerDuty, Inc.                                      | US       |                0.81 |             66.99 |         74.23 |         72.45 |          61.54 |        55.67 |           77.55 |             52.8  |             29.21 |         8.16 |             86.86 | short              |                4.12 |                  3.6  |                  nan |
|    nan | GOLD     | Gold.com, Inc.                                       | US       |                1.15 |             56.81 |         73.23 |         56.39 |          57.24 |        54.51 |           52.95 |             83.01 |             28.55 |         6.02 |             77.94 | short              |               -0.46 |                 -0.04 |                  nan |
|    nan | KSS      | Kohl's Corporation                                   | US       |                1.71 |             51.12 |         35.49 |         49.66 |          52.58 |        56.06 |           59.98 |             50.83 |             53    |         8.43 |             87.57 | long               |               -1.31 |                 -1.67 |                  nan |
|    nan | IRS      | IRSA Inversiones y Representaciones Sociedad Anónima | OTHER    |                1.07 |             50.42 |         47.11 |         43.78 |          53.72 |        64.32 |           84.01 |             44.84 |             54.36 |         3.92 |             75.81 | long               |                1.51 |                  0.17 |                  nan |
|    nan | MOMO     | Hello Group Inc.                                     | OTHER    |                0.73 |             47.29 |         43.13 |         42.48 |          51.46 |        64.4  |           67.05 |             58.88 |             85.35 |         4.36 |             82.14 | long               |                2.76 |                  0.37 |                  nan |
|    nan | JKS      | JinkoSolar Holding Co., Ltd.                         | OTHER    |                0.71 |             40.82 |         42.22 |         33.56 |          39.43 |        45.71 |           47.04 |             68.49 |             49.29 |         7.04 |             77.1  | long               |                1.97 |                  1.33 |                  nan |
|    nan | FINV     | FinVolution Group                                    | OTHER    |                0.88 |             38.86 |         31.11 |         35.14 |          42.58 |        54.17 |           47.24 |             49.35 |             80    |         6.22 |             78.58 | long               |                0.52 |                  0.04 |                  nan |
|    nan | QFIN     | Qfin Holdings, Inc.                                  | OTHER    |                1.21 |             38.35 |         28.1  |         34.63 |          42.08 |        56.36 |           48.12 |             39.62 |             93.21 |         7.09 |             78.48 | long               |               -6.2  |                  0.31 |                  nan |
|    nan | CSIQ     | Canadian Solar Inc.                                  | OTHER    |                0.85 |             36.77 |         35.12 |         24.09 |          38.43 |        50.67 |           67.83 |             21    |             49.33 |         8.96 |             78.45 | long               |                2.55 |                  1.14 |                  nan |

## Fastest improving (5 stored runs)

|   rank | symbol   | name     | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:---------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    600 | STLAP.PA | STLAP.PA | EUROPE   |               17.51 |             45.04 |         42.7  |         40.44 |          47.38 |        55.7  |           29.16 |             86.78 |             92.31 |         7.1  |             65.43 | long               |                2.64 |                  4.31 |                  nan |
|    627 | STLAM.MI | STLAM.MI | EUROPE   |               17.5  |             43.19 |         42.31 |         39.21 |          44.06 |        50.7  |           16.22 |             86.9  |             93.16 |         7.11 |             64.41 | long               |                3.06 |                  3.63 |                  nan |
|    407 | PAH3.DE  | PAH3.DE  | EUROPE   |                8.56 |             54.78 |         52.83 |         47.61 |          56.73 |        76.92 |          nan    |             84.28 |             96.53 |         3.82 |             62.59 | long               |                3.02 |                  3.53 |                  nan |
|    123 | HIMS     | HIMS     | US       |                6.75 |             67.07 |         75.35 |         74.5  |          59.65 |        41.42 |           36.47 |             96.13 |             11.86 |         9.47 |             67.5  | short              |                7.74 |                  3.36 |                  nan |
|     28 | MRVI     | MRVI     | US       |                2.74 |             74.59 |         82.2  |         82.16 |          67.01 |        48.6  |           29.14 |             73.52 |             30.43 |         6.95 |             63.64 | short              |                0.57 |                  3.21 |                  nan |

## Fastest deteriorating (5 stored runs)

|   rank | symbol   | name       | region   |   market_cap_eur_bn |   consensus_score |   short_score |   swing_score |   medium_score |   long_score |   quality_score |   revisions_score |   valuation_score |   risk_score |   data_confidence | best_fit_horizon   |   score_change_1run |   score_velocity_5run |   score_acceleration |
|-------:|:---------|:-----------|:---------|--------------------:|------------------:|--------------:|--------------:|---------------:|-------------:|----------------:|------------------:|------------------:|-------------:|------------------:|:-------------------|--------------------:|----------------------:|---------------------:|
|    634 | AMV0.DE  | Aumovio SE | EUROPE   |                3.66 |             42.73 |         44.55 |         33.81 |          40.91 |        52.19 |           49.64 |             37.89 |             75.11 |         6.02 |             75.5  | long               |              -17.86 |                 -4.34 |                  nan |
|    275 | TKA.DE   | TKA.DE     | EUROPE   |                8.32 |             60.28 |         62.49 |         57.62 |          58.2  |        62.37 |          nan    |             23.34 |             65.58 |         6.71 |             64.66 | short              |                8.65 |                 -3.85 |                  nan |
|    642 | AIR.PA   | AIR.PA     | EUROPE   |              161.22 |             42.26 |         40.05 |         48.17 |          43.79 |        40.73 |           58.58 |             16.91 |              8.78 |         4.22 |             65.43 | swing              |              -15.8  |                 -3.47 |                  nan |
|    655 | GLE.PA   | GLE.PA     | EUROPE   |               55.8  |             40.13 |         32.73 |         39.46 |          40.8  |        41.89 |            6.54 |             24.43 |             78.87 |         3.83 |             65.43 | long               |                0.72 |                 -3.37 |                  nan |
|    444 | ASML.AS  | ASML.AS    | EUROPE   |              578.45 |             53.16 |         43.36 |         52.88 |          61.35 |        53.44 |           70.11 |             56.97 |              4.32 |         5.24 |             65.43 | medium             |               -5.01 |                 -3.24 |                  nan |

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
- Excluded by hard/data filters: **277**
- Event watch (otherwise eligible): **9**
- Final eligible: **714**
- Eligible change vs previous stored run: **+0**

Top exclusion categories:
- liquidity: 230
- price: 163
- market_cap: 132
- price_history: 16
- data_confidence: 11
- asset_type: 1
- delisted: 1

## Strategy overlap

| symbol | main | value | pullback | quality-value | overlap | strategies |
|:--|--:|--:|--:|--:|--:|:--|
| PARR | 3 | 3 | 12 | 1 | 2 | main,value,quality_value |
| AMC | 8 |  | 10 |  | 2 | main,pullback |
| AMCX | 54 | 10 |  | 10 | 1 | value,quality_value |
| BION.SW | 114 | 5 |  | 9 | 1 | value,quality_value |
| EMBC | 145 | 4 |  | 3 | 1 | value,quality_value |
| GSL | 158 | 2 |  | 4 | 1 | value,quality_value |
| 0P6O.IL | 561 | 6 |  | 5 | 1 | value,quality_value |
| STNE | 651 | 1 |  | 2 | 1 | value,quality_value |
| PSX | 1 |  |  |  | 1 | main |
| ERO | 2 |  |  |  | 1 | main |
| MU | 4 |  | 11 |  | 1 | main |
| DK | 5 |  |  |  | 1 | main |
| CRGY | 6 |  |  |  | 1 | main |
| PBF | 7 |  |  |  | 1 | main |
| CCC | 9 |  |  |  | 1 | main |

## Adaptive deepening diagnostics

- Core selected: **600**
- Adaptive selected: **400**
- Discovery names not selected for Full Exact: **1000**
- Adaptive in Main Top 10: **6** (PSX, ERO, DK, CRGY, CCC, FLYW)
- Adaptive in Value Top 10: **0** (none)
- Adaptive in Quality Value Top 10: **0** (none)
- Adaptive in Pullback Top 10: **0** (none)

## Best Buys Now / Entry Opportunity

Separate Exact entry view; Main/Value/Pullback and horizon scores stay unchanged.
Candidate = eligible AND (undervaluation >= 55 with sufficient Value coverage OR published pullback_candidate).
Weights: 30% undervaluation, 25% pullback, 15% quality, 10% revisions, 20% value safety. No web/news inputs.

| entry | symbol | signal | score | under | pb setup | quality | revisions | safety | main |
|--:|:--|:--|--:|--:|--:|--:|--:|--:|--:|
| 1 | NWL.MI | value+pullback | 73.11 | 65.20 | 83.81 | 79.78 | 55.84 | 75.25 | 46.00 |
| 2 | PARR | value+pullback | 69.48 | 72.81 | 59.20 | 83.48 | 66.20 | 68.49 | 78.40 |
| 3 | INVA | value+pullback | 67.47 | 60.62 | 59.44 | 92.59 | 40.94 | 82.21 | 46.56 |
| 4 | PKX | value+pullback | 66.04 | 65.91 | 61.19 | 78.40 | 68.50 | 61.82 | 55.68 |
| 5 | ETG | value+pullback | 63.97 | 56.61 | 53.19 | 69.10 | 79.10 | 77.09 | 60.95 |
| 6 | MFA | value+pullback | 62.64 | 57.65 | 66.21 | 80.59 | 37.51 | 64.76 | 43.30 |
| 7 | 0P6O.IL | value+pullback | 62.45 | 67.28 | 46.44 | 76.99 |  | 70.55 | 47.62 |
| 8 | DOM.ST | value+pullback | 62.37 | 58.24 | 65.81 | 73.01 | 34.28 | 70.34 | 38.53 |
| 9 | ALL-PH | value+pullback | 61.94 | 62.77 | 63.20 | 70.58 | 44.04 | 61.60 | 44.45 |
| 10 | AVK | value+pullback | 61.39 | 55.18 | 57.85 | 62.59 | 78.86 | 65.48 | 58.02 |
| 11 | UNIT | value+pullback | 61.26 | 80.26 | 60.06 | 65.19 | 33.02 | 45.43 | 44.25 |
| 12 | TV | value+pullback | 61.12 | 69.83 | 74.47 | 44.52 | 33.45 | 57.67 | 38.95 |
| 13 | KYN | value+pullback | 60.63 | 60.33 | 51.74 | 56.07 | 79.10 | 66.34 | 58.73 |
| 14 | XNET | value+pullback | 59.22 | 60.43 | 40.47 | 58.55 | 78.86 | 71.53 | 44.86 |
| 15 | WKC | value+pullback | 59.16 | 61.83 | 40.04 | 64.35 | 74.66 | 67.42 | 69.98 |
| 16 | ONIT | value+pullback | 58.57 | 70.82 | 59.74 | 63.16 | 45.11 | 42.04 | 43.63 |
| 17 | CLW | value+pullback | 57.45 | 55.36 | 58.96 | 54.05 | 65.00 | 57.49 | 65.61 |
| 18 | JCAP | pullback | 57.38 | 57.28 | 81.56 | 84.26 | 86.22 | 78.64 | 75.55 |
| 19 | 1VOW3.MI | value+pullback | 56.98 | 59.09 | 42.75 | 69.20 |  | 65.95 | 47.85 |
| 20 | GL9.IR | pullback | 56.96 | 39.27 | 75.43 | 97.46 | 65.42 | 84.73 | 68.00 |

## Ranking data-quality diagnostics

Diagnostic only: these checks do **not** change eligibility, scores, weights, backtests or optimizer inputs.

| window | quality | revisions | valuation | complete 3/3 | sparse <=1/3 | median confidence | Core / Adaptive |
|:--|--:|--:|--:|--:|--:|--:|--:|
| Top 10 | 10/10 | 10/10 | 9/10 | 9/10 | 0/10 | 67.0 | 4 / 6 |
| Top 25 | 25/25 | 24/25 | 24/25 | 23/25 | 0/25 | 67.0 | 8 / 17 |
| Top 50 | 49/50 | 49/50 | 49/50 | 47/50 | 0/50 | 66.9 | 17 / 33 |

Top-10 market-cap mix: small_1_5b=7, mid_5_20b=1, large_20_100b=1, mega_100b_plus=1
